---
pageType: report
id: report.claim-health
title: Claim Health
status: active
updatedAt: '2026-04-29T16:02:00.169559+00:00'
---

# Claim Health

## Generated
<!-- openclaw:wiki:claim-health:start -->
- Claims missing evidence: 2444
- Contested claims: 0

### Missing Evidence
- [[entities/cli-commands-reference|CLI Commands Reference]]: add a new provider** (OpenRouter, Anthropic, Copilot, DeepSeek, custom, etc.)
- [[entities/cli-commands-reference|CLI Commands Reference]]: log into OAuth-backed providers (Anthropic, Copilot, Codex, Nous Portal)
- [[entities/cli-commands-reference|CLI Commands Reference]]: enter or update API keys
- [[entities/cli-commands-reference|CLI Commands Reference]]: pick from provider-specific model lists
- [[entities/cli-commands-reference|CLI Commands Reference]]: configure a custom/self-hosted endpoint
- [[entities/cli-commands-reference|CLI Commands Reference]]: save the new default into config
- [[entities/cli-commands-reference|CLI Commands Reference]]: hermes dump ---version:          0.8.0 (2026.4.8) [af4abd2f]os:               Linux 6.14.0-37-generic x86_64python:           3.11.14openai_sdk:       2.24.0profile:          defaulthermes_home:      ~/.hermesmodel:            anthropic/claude-opus-4.6provider:         openrouterterminal:         localapi_keys:  openrouter           set  openai               not set  anthropic            set  nous                 not set  firecrawl            set  ...features:  toolsets:           all  mcp_servers:        0  memory_provider:    built-in  gateway:            running (systemd)  platforms:          telegram, discord  cron_jobs:          3 active / 5 total  skills:             42config_overrides:  agent.max_turns: 250  compression.threshold: 0.85  display.streaming: True--- end dump ---
- [[entities/cli-commands-reference|CLI Commands Reference]]: Reporting a bug on GitHub — paste the dump into your issue
- [[entities/cli-commands-reference|CLI Commands Reference]]: Asking for help in Discord — share it in a code block
- [[entities/cli-commands-reference|CLI Commands Reference]]: Comparing your setup to someone else&#x27;s
- [[entities/cli-commands-reference|CLI Commands Reference]]: Quick sanity check when something isn&#x27;t working
- [[entities/cli-commands-reference|CLI Commands Reference]]: `--force` can override non-dangerous policy blocks for third-party/community skills.
- [[entities/cli-commands-reference|CLI Commands Reference]]: `--force` does not override a `dangerous` scan verdict.
- [[entities/cli-commands-reference|CLI Commands Reference]]: `--source skills-sh` searches the public `skills.sh` directory.
- [[entities/cli-commands-reference|CLI Commands Reference]]: `--source well-known` lets you point Hermes at a site exposing `/.well-known/skills/index.json`.
- [[entities/cli-commands-reference|CLI Commands Reference]]: General Plugins** — multi-select checkboxes to enable/disable installed plugins
- [[entities/cli-commands-reference|CLI Commands Reference]]: Provider Plugins** — single-select configuration for Memory Provider and Context Engine. Press ENTER on a category to open a radio picker.
- [[entities/cli-commands-reference|CLI Commands Reference]]: `memory.provider` — active memory provider (empty = built-in only)
- [[entities/cli-commands-reference|CLI Commands Reference]]: `context.engine` — active context engine (`&quot;compressor&quot;` = built-in default)
- [[entities/cli-commands-reference|CLI Commands Reference]]: [Slash Commands Reference](/docs/reference/slash-commands)
<!-- openclaw:wiki:claim-health:end -->
