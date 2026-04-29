---
title: "Use MCP with Hermes"
id: hermes-agent-use-mcp-with-hermes
pageType: entity
tags:
  - hermes-agent
  - documentation
hermes-source: https://hermes-agent.nousresearch.com/docs
---

Use MCP with Hermes | Hermes Agent-
[Skip to main content](#__docusaurus_skipToContent_fallback)[Hermes Agent](/docs/)[Docs](/docs/getting-started/quickstart)[Skills](/docs/skills)[Home](https://hermes-agent.nousresearch.com)[GitHub](https://github.com/NousResearch/hermes-agent)[Discord](https://discord.gg/NousResearch)[Getting Started](/docs/getting-started/quickstart)
- [Using Hermes](/docs/user-guide/cli)
- [Features](/docs/user-guide/features/overview)
- [Messaging Platforms](/docs/user-guide/messaging/)
- [Integrations](/docs/integrations/)
- [Guides & Tutorials](/docs/guides/tips)[Tips & Best Practices](/docs/guides/tips)
- [Run Local LLMs on Mac](/docs/guides/local-llm-on-mac)
- [Tutorial: Daily Briefing Bot](/docs/guides/daily-briefing-bot)
- [Tutorial: Team Telegram Assistant](/docs/guides/team-telegram-assistant)
- [Using Hermes as a Python Library](/docs/guides/python-library)
- [Use MCP with Hermes](/docs/guides/use-mcp-with-hermes)
- [Use SOUL.md with Hermes](/docs/guides/use-soul-with-hermes)
- [Use Voice Mode with Hermes](/docs/guides/use-voice-mode-with-hermes)
- [Build a Plugin](/docs/guides/build-a-hermes-plugin)
- [Automate Anything with Cron](/docs/guides/automate-with-cron)
- [Automation Templates](/docs/guides/automation-templates)
- [Cron Troubleshooting](/docs/guides/cron-troubleshooting)
- [Working with Skills](/docs/guides/work-with-skills)
- [Delegation & Parallel Work](/docs/guides/delegation-patterns)
- [Tutorial: GitHub PR Review Agent](/docs/guides/github-pr-review-agent)
- [GitHub PR Reviews via Webhook](/docs/guides/webhook-github-pr-review)
- [Migrate from OpenClaw](/docs/guides/migrate-from-openclaw)
- [AWS Bedrock](/docs/guides/aws-bedrock)
- [Developer Guide](/docs/developer-guide/contributing)
- [Reference](/docs/reference/cli-commands)
- [](/docs/)
- Guides & Tutorials
- Use MCP with Hermes
On this page# Use MCP with Hermes
This guide shows how to actually use MCP with Hermes Agent in day-to-day workflows.
If the feature page explains what MCP is, this guide is about how to get value from it quickly and safely.
## When should you use MCP?[​](#when-should-you-use-mcp)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->
Use MCP when:
- a tool already exists in MCP form and you do not want to build a native Hermes tool
- you want Hermes to operate against a local or remote system through a clean RPC layer
- you want fine-grained per-server exposure control
- you want to connect Hermes to internal APIs, databases, or company systems without modifying Hermes core
Do not use MCP when:
- a built-in Hermes tool already solves the job well
- the server exposes a huge dangerous tool surface and you are not prepared to filter it
- you only need one very narrow integration and a native tool would be simpler and safer
## Mental model[​](#mental-model)
Think of MCP as an adapter layer:
- Hermes remains the agent
- MCP servers contribute tools
- Hermes discovers those tools at startup or reload time
- the model can use them like normal tools
- you control how much of each server is visible
That last part matters. Good MCP usage is not just “connect everything.” It is “connect the right thing, with the smallest useful surface.”
## Step 1: install MCP support[​](#step-1-install-mcp-support)
If you installed Hermes with the standard install script, MCP support is already included (the installer runs `uv pip install -e ".[all]"`).
If you installed without extras and need to add MCP separately:
```
cd ~/.hermes/hermes-agentuv pip install -e ".[mcp]"
```
For npm-based servers, make sure Node.js and `npx` are available.
For many Python MCP servers, `uvx` is a nice default.
## Step 2: add one server first[​](#step-2-add-one-server-first)
Start with a single, safe server.
Example: filesystem access to one project directory only.
```
mcp_servers:  project_fs:    command: "npx"    args: ["-y", "@modelcontextprotocol/server-filesystem", "/home/user/my-project"]
```
Then start Hermes:
```
hermes chat
```
Now ask something concrete:
```
Inspect this project and summarize the repo layout.
```
## Step 3: verify MCP loaded[​](#step-3-verify-mcp-loaded)
You can verify MCP in a few ways:
- Hermes banner/status should show MCP integration when configured
- ask Hermes what tools it has available
- use `/reload-mcp` after config changes
- check logs if the server failed to connect
A practical test prompt:
```
Tell me which MCP-backed tools are available right now.
```
## Step 4: start filtering immediately[​](#step-4-start-filtering-immediately)
Do not wait until later if the server exposes a lot of tools.
### Example: whitelist only what you want[​](#example-whitelist-only-what-you-want)
```
mcp_servers:  github:    command: "npx"    args: ["-y", "@modelcontextprotocol/server-github"]    env:      GITHUB_PERSONAL_ACCESS_TOKEN: "***"    tools:      include: [list_issues, create_issue, search_code]
```
This is usually the best default for sensitive systems.
### Example: blacklist dangerous actions[​](#example-blacklist-dangerous-actions)
```
mcp_servers:  stripe:    url: "https://mcp.stripe.com"    headers:      Authorization: "Bearer ***"    tools:      exclude: [delete_customer, refund_payment]
```
### Example: disable utility wrappers too[​](#example-disable-utility-wrappers-too)
```
mcp_servers:  docs:    url: "https://mcp.docs.example.com"    tools:      prompts: false      resources: false
```
## What does filtering actually affect?[​](#what-does-filtering-actually-affect)
There are two categories of MCP-exposed functionality in Hermes:
- Server-native MCP tools
- filtered with:
`tools.include`
- `tools.exclude`
- Hermes-added utility wrappers
- filtered with:
`tools.resources`
- `tools.prompts`
### Utility wrappers you may see[​](#utility-wrappers-you-may-see)
Resources:
- `list_resources`
- `read_resource`
Prompts:
- `list_prompts`
- `get_prompt`
These wrappers only appear if:
- your config allows them, and
- the MCP server session actually supports those capabilities
So Hermes will not pretend a server has resources/prompts if it does not.
## Common patterns[​](#common-patterns)
### Pattern 1: local project assistant[​](#pattern-1-local-project-assistant)
Use MCP for a repo-local filesystem or git server when you want Hermes to reason over a bounded workspace.
```
mcp_servers:  fs:    command: "npx"    args: ["-y", "@modelcontextprotocol/server-filesystem", "/home/user/project"]  git:    command: "uvx"    args: ["mcp-server-git", "--repository", "/home/user/project"]
```
Good prompts:
```
Review the project structure and identify where configuration lives.
```
```
Check the local git state and summarize what changed recently.
```
### Pattern 2: GitHub triage assistant[​](#pattern-2-github-triage-assistant)
```
mcp_servers:  github:    command: "npx"    args: ["-y", "@modelcontextprotocol/server-github"]    env:      GITHUB_PERSONAL_ACCESS_TOKEN: "***"    tools:      include: [list_issues, create_issue, update_issue, search_code]      prompts: false      resources: false
```
Good prompts:
```
List open issues about MCP, cluster them by theme, and draft a high-quality issue for the most common bug.
```
```
Search the repo for uses of _discover_and_register_server and explain how MCP tools are registered.
```
### Pattern 3: internal API assistant[​](#pattern-3-internal-api-assistant)
```
mcp_servers:  internal_api:    url: "https://mcp.internal.example.com"    headers:      Authorization: "Bearer ***"    tools:      include: [list_customers, get_customer, list_invoices]      resources: false      prompts: false
```
Good prompts:
```
Look up customer ACME Corp and summarize recent invoice activity.
```
This is the sort of place where a strict whitelist is far better than an exclude list.
### Pattern 4: documentation / knowledge servers[​](#pattern-4-documentation--knowledge-servers)
Some MCP servers expose prompts or resources that are more like shared knowledge assets than direct actions.
```
mcp_servers:  docs:    url: "https://mcp.docs.example.com"    tools:      prompts: true      resources: true
```
Good prompts:
```
List available MCP resources from the docs server, then read the onboarding guide and summarize it.
```
```
List prompts exposed by the docs server and tell me which ones would help with incident response.
```
## Tutorial: end-to-end setup with filtering[​](#tutorial-end-to-end-setup-with-filtering)
Here is a practical progression.
### Phase 1: add GitHub MCP with a tight whitelist[​](#phase-1-add-github-mcp-with-a-tight-whitelist)
```
mcp_servers:  github:    command: "npx"    args: ["-y", "@modelcontextprotocol/server-github"]    env:      GITHUB_PERSONAL_ACCESS_TOKEN: "***"    tools:      include: [list_issues, create_issue, search_code]      prompts: false      resources: false
```
Start Hermes and ask:
```
Search the codebase for references to MCP and summarize the main integration points.
```
### Phase 2: expand only when needed[​](#phase-2-expand-only-when-needed)
If you later need issue updates too:
```
tools:  include: [list_issues, create_issue, update_issue, search_code]
```
Then reload:
```
/reload-mcp
```
### Phase 3: add a second server with different policy[​](#phase-3-add-a-second-server-with-different-policy)
```
mcp_servers:  github:    command: "npx"    args: ["-y", "@modelcontextprotocol/server-github"]    env:      GITHUB_PERSONAL_ACCESS_TOKEN: "***"    tools:      include: [list_issues, create_issue, update_issue, search_code]      prompts: false      resources: false  filesystem:    command: "npx"    args: ["-y", "@modelcontextprotocol/server-filesystem", "/home/user/project"]
```
Now Hermes can combine them:
```
Inspect the local project files, then create a GitHub issue summarizing the bug you find.
```
That is where MCP gets powerful: multi-system workflows without changing Hermes core.
## Safe usage recommendations[​](#safe-usage-recommendations)
### Prefer allowlists for dangerous systems[​](#prefer-allowlists-for-dangerous-systems)
For anything financial, customer-facing, or destructive:
- use `tools.include`
- start with the smallest set possible
### Disable unused utilities[​](#disable-unused-utilities)
If you do not want the model browsing server-provided resources/prompts, turn them off:
```
tools:  resources: false  prompts: false
```
### Keep servers scoped narrowly[​](#keep-servers-scoped-narrowly)
Examples:
- filesystem server rooted to one project dir, not your whole home directory
- git server pointed at one repo
- internal API server with read-heavy tool exposure by default
### Reload after config changes[​](#reload-after-config-changes)
```
/reload-mcp
```
Do this after changing:
- include/exclude lists
- enabled flags
- resources/prompts toggles
- auth headers / env
## Troubleshooting by symptom[​](#troubleshooting-by-symptom)
### "The server connects but the tools I expected are missing"[​](#the-server-connects-but-the-tools-i-expected-are-missing)
Possible causes:
- filtered by `tools.include`
- excluded by `tools.exclude`
- utility wrappers disabled via `resources: false` or `prompts: false`
- server does not actually support resources/prompts
### "The server is configured but nothing loads"[​](#the-server-is-configured-but-nothing-loads)
Check:
- `enabled: false` was not left in config
- command/runtime exists (`npx`, `uvx`, etc.)
- HTTP endpoint is reachable
- auth env or headers are correct
### "Why do I see fewer tools than the MCP server advertises?"[​](#why-do-i-see-fewer-tools-than-the-mcp-server-advertises)
Because Hermes now respects your per-server policy and capability-aware registration. That is expected, and usually desirable.
### "How do I remove an MCP server without deleting the config?"[​](#how-do-i-remove-an-mcp-server-without-deleting-the-config)
Use:
```
enabled: false
```
That keeps the config around but prevents connection and registration.
## Recommended first MCP setups[​](#recommended-first-mcp-setups)
Good first servers for most users:
- filesystem
- git
- GitHub
- fetch / documentation MCP servers
- one narrow internal API
Not-great first servers:
- giant business systems with lots of destructive actions and no filtering
- anything you do not understand well enough to constrain
## Related docs[​](#related-docs)
- [MCP (Model Context Protocol)](/docs/user-guide/features/mcp)
- [FAQ](/docs/reference/faq)
- [Slash Commands](/docs/reference/slash-commands)
[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/guides/use-mcp-with-hermes.md)[PreviousUsing Hermes as a Python Library](/docs/guides/python-library)[NextUse SOUL.md with Hermes](/docs/guides/use-soul-with-hermes)- [When should you use MCP?](#when-should-you-use-mcp)
- [Mental model](#mental-model)
- [Step 1: install MCP support](#step-1-install-mcp-support)
- [Step 2: add one server first](#step-2-add-one-server-first)
- [Step 3: verify MCP loaded](#step-3-verify-mcp-loaded)
- [Step 4: start filtering immediately](#step-4-start-filtering-immediately)[Example: whitelist only what you want](#example-whitelist-only-what-you-want)
- [Example: blacklist dangerous actions](#example-blacklist-dangerous-actions)
- [Example: disable utility wrappers too](#example-disable-utility-wrappers-too)
- [What does filtering actually affect?](#what-does-filtering-actually-affect)[Utility wrappers you may see](#utility-wrappers-you-may-see)
- [Common patterns](#common-patterns)[Pattern 1: local project assistant](#pattern-1-local-project-assistant)
- [Pattern 2: GitHub triage assistant](#pattern-2-github-triage-assistant)
- [Pattern 3: internal API assistant](#pattern-3-internal-api-assistant)
- [Pattern 4: documentation / knowledge servers](#pattern-4-documentation--knowledge-servers)
- [Tutorial: end-to-end setup with filtering](#tutorial-end-to-end-setup-with-filtering)[Phase 1: add GitHub MCP with a tight whitelist](#phase-1-add-github-mcp-with-a-tight-whitelist)
- [Phase 2: expand only when needed](#phase-2-expand-only-when-needed)
- [Phase 3: add a second server with different policy](#phase-3-add-a-second-server-with-different-policy)
- [Safe usage recommendations](#safe-usage-recommendations)[Prefer allowlists for dangerous systems](#prefer-allowlists-for-dangerous-systems)
- [Disable unused utilities](#disable-unused-utilities)
- [Keep servers scoped narrowly](#keep-servers-scoped-narrowly)
- [Reload after config changes](#reload-after-config-changes)
- [Troubleshooting by symptom](#troubleshooting-by-symptom)["The server connects but the tools I expected are missing"](#the-server-connects-but-the-tools-i-expected-are-missing)
- ["The server is configured but nothing loads"](#the-server-is-configured-but-nothing-loads)
- ["Why do I see fewer tools than the MCP server advertises?"](#why-do-i-see-fewer-tools-than-the-mcp-server-advertises)
- ["How do I remove an MCP server without deleting the config?"](#how-do-i-remove-an-mcp-server-without-deleting-the-config)
- [Recommended first MCP setups](#recommended-first-mcp-setups)
- [Related docs](#related-docs)
Docs- [Getting Started](/docs/getting-started/quickstart)
- [User Guide](/docs/user-guide/cli)
- [Developer Guide](/docs/developer-guide/architecture)
- [Reference](/docs/reference/cli-commands)
Community- [Discord](https://discord.gg/NousResearch)
- [GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions)
- [Skills Hub](https://agentskills.io)
More- [GitHub](https://github.com/NousResearch/hermes-agent)
- [Nous Research](https://nousresearch.com)
Built by [Nous Research](https://nousresearch.com) · MIT License · 2026
