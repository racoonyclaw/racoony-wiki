---
title: "Quickstart"
id: hermes-agent-quickstart
pageType: entity
tags:
  - hermes-agent
  - documentation
hermes-source: https://hermes-agent.nousresearch.com/docs
---

Quickstart | Hermes Agent-
[Skip to main content](#__docusaurus_skipToContent_fallback)[Hermes Agent](/docs/)[Docs](/docs/getting-started/quickstart)[Skills](/docs/skills)[Home](https://hermes-agent.nousresearch.com)[GitHub](https://github.com/NousResearch/hermes-agent)[Discord](https://discord.gg/NousResearch)[Getting Started](/docs/getting-started/quickstart)[Quickstart](/docs/getting-started/quickstart)
- [Installation](/docs/getting-started/installation)
- [Android / Termux](/docs/getting-started/termux)
- [Nix & NixOS Setup](/docs/getting-started/nix-setup)
- [Updating & Uninstalling](/docs/getting-started/updating)
- [Learning Path](/docs/getting-started/learning-path)
- [Using Hermes](/docs/user-guide/cli)
- [Features](/docs/user-guide/features/overview)
- [Messaging Platforms](/docs/user-guide/messaging/)
- [Integrations](/docs/integrations/)
- [Guides & Tutorials](/docs/guides/tips)
- [Developer Guide](/docs/developer-guide/contributing)
- [Reference](/docs/reference/cli-commands)
- [](/docs/)
- Getting Started
- Quickstart
On this page# Quickstart
This guide gets you from zero to a working Hermes setup that survives real use. Install, choose a provider, verify a working chat, and know exactly what to do when something breaks.
## Who this is for[​](#who-this-is-for)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->
- Brand new and want the shortest path to a working setup
- Switching providers and don't want to lose time to config mistakes
- Setting up Hermes for a team, bot, or always-on workflow
- Tired of "it installed, but it still does nothing"
## The fastest path[​](#the-fastest-path)
Pick the row that matches your goal:
GoalDo this firstThen do thisI just want Hermes working on my machine`hermes setup`Run a real chat and verify it respondsI already know my provider`hermes model`Save the config, then start chattingI want a bot or always-on setup`hermes gateway setup` after CLI worksConnect Telegram, Discord, Slack, or another platformI want a local or self-hosted model`hermes model` → custom endpointVerify the endpoint, model name, and context lengthI want multi-provider fallback`hermes model` firstAdd routing and fallback only after the base chat works
Rule of thumb: if Hermes cannot complete a normal chat, do not add more features yet. Get one clean conversation working first, then layer on gateway, cron, skills, voice, or routing.
## 1. Install Hermes Agent[​](#1-install-hermes-agent)
Run the one-line installer:
```
# Linux / macOS / WSL2 / Android (Termux)curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
```
Android / TermuxIf you're installing on a phone, see the dedicated [Termux guide](/docs/getting-started/termux) for the tested manual path, supported extras, and current Android-specific limitations.
Windows UsersInstall [WSL2](https://learn.microsoft.com/en-us/windows/wsl/install) first, then run the command above inside your WSL2 terminal.
After it finishes, reload your shell:
```
source ~/.bashrc   # or source ~/.zshrc
```
For detailed installation options, prerequisites, and troubleshooting, see the [Installation guide](/docs/getting-started/installation).
## 2. Choose a Provider[​](#2-choose-a-provider)
The single most important setup step. Use `hermes model` to walk through the choice interactively:
```
hermes model
```
Good defaults:
SituationRecommended pathLeast frictionNous Portal or OpenRouterYou already have Claude or Codex authAnthropic or OpenAI CodexYou want local/private inferenceOllama or any custom OpenAI-compatible endpointYou want multi-provider routingOpenRouterYou have a custom GPU servervLLM, SGLang, LiteLLM, or any OpenAI-compatible endpoint
For most first-time users: choose a provider, accept the defaults unless you know why you're changing them. The full provider catalog with env vars and setup steps lives on the [Providers](/docs/integrations/providers) page.
Minimum context: 64K tokensHermes Agent requires a model with at least 64,000 tokens of context. Models with smaller windows cannot maintain enough working memory for multi-step tool-calling workflows and will be rejected at startup. Most hosted models (Claude, GPT, Gemini, Qwen, DeepSeek) meet this easily. If you're running a local model, set its context size to at least 64K (e.g. `--ctx-size 65536` for llama.cpp or `-c 65536` for Ollama).
tipYou can switch providers at any time with `hermes model` — no lock-in. For a full list of all supported providers and setup details, see [AI Providers](/docs/integrations/providers).
### How settings are stored[​](#how-settings-are-stored)
Hermes separates secrets from normal config:
- Secrets and tokens → `~/.hermes/.env`
- Non-secret settings → `~/.hermes/config.yaml`
The easiest way to set values correctly is through the CLI:
```
hermes config set model anthropic/claude-opus-4.6hermes config set terminal.backend dockerhermes config set OPENROUTER_API_KEY sk-or-...
```
The right value goes to the right file automatically.
## 3. Run Your First Chat[​](#3-run-your-first-chat)
```
hermes            # classic CLIhermes --tui      # modern TUI (recommended)
```
You'll see a welcome banner with your model, available tools, and skills. Use a prompt that's specific and easy to verify:
Pick your interfaceHermes ships with two terminal interfaces: the classic `prompt_toolkit` CLI and a newer [TUI](/docs/user-guide/tui) with modal overlays, mouse selection, and non-blocking input. Both share the same sessions, slash commands, and config — try each with `hermes` vs `hermes --tui`.
```
Summarize this repo in 5 bullets and tell me what the main entrypoint is.
```
```
Check my current directory and tell me what looks like the main project file.
```
```
Help me set up a clean GitHub PR workflow for this codebase.
```
What success looks like:
- The banner shows your chosen model/provider
- Hermes replies without error
- It can use a tool if needed (terminal, file read, web search)
- The conversation continues normally for more than one turn
If that works, you're past the hardest part.
## 4. Verify Sessions Work[​](#4-verify-sessions-work)
Before moving on, make sure resume works:
```
hermes --continue    # Resume the most recent sessionhermes -c            # Short form
```
That should bring you back to the session you just had. If it doesn't, check whether you're in the same profile and whether the session actually saved. This matters later when you're juggling multiple setups or machines.
## 5. Try Key Features[​](#5-try-key-features)
### Use the terminal[​](#use-the-terminal)
```
❯ What's my disk usage? Show the top 5 largest directories.
```
The agent runs terminal commands on your behalf and shows results.
### Slash commands[​](#slash-commands)
Type `/` to see an autocomplete dropdown of all commands:
CommandWhat it does`/help`Show all available commands`/tools`List available tools`/model`Switch models interactively`/personality pirate`Try a fun personality`/save`Save the conversation
### Multi-line input[​](#multi-line-input)
Press `Alt+Enter` or `Ctrl+J` to add a new line. Great for pasting code or writing detailed prompts.
### Interrupt the agent[​](#interrupt-the-agent)
If the agent is taking too long, type a new message and press Enter — it interrupts the current task and switches to your new instructions. `Ctrl+C` also works.
## 6. Add the Next Layer[​](#6-add-the-next-layer)
Only after the base chat works. Pick what you need:
### Bot or shared assistant[​](#bot-or-shared-assistant)
```
hermes gateway setup    # Interactive platform configuration
```
Connect [Telegram](/docs/user-guide/messaging/telegram), [Discord](/docs/user-guide/messaging/discord), [Slack](/docs/user-guide/messaging/slack), [WhatsApp](/docs/user-guide/messaging/whatsapp), [Signal](/docs/user-guide/messaging/signal), [Email](/docs/user-guide/messaging/email), or [Home Assistant](/docs/user-guide/messaging/homeassistant).
### Automation and tools[​](#automation-and-tools)
- `hermes tools` — tune tool access per platform
- `hermes skills` — browse and install reusable workflows
- Cron — only after your bot or CLI setup is stable
### Sandboxed terminal[​](#sandboxed-terminal)
For safety, run the agent in a Docker container or on a remote server:
```
hermes config set terminal.backend docker    # Docker isolationhermes config set terminal.backend ssh       # Remote server
```
### Voice mode[​](#voice-mode)
```
pip install "hermes-agent[voice]"# Includes faster-whisper for free local speech-to-text
```
Then in the CLI: `/voice on`. Press `Ctrl+B` to record. See [Voice Mode](/docs/user-guide/features/voice-mode).
### Skills[​](#skills)
```
hermes skills search kuberneteshermes skills install openai/skills/k8s
```
Or use `/skills` inside a chat session.
### MCP servers[​](#mcp-servers)
```
# Add to ~/.hermes/config.yamlmcp_servers:  github:    command: npx    args: ["-y", "@modelcontextprotocol/server-github"]    env:      GITHUB_PERSONAL_ACCESS_TOKEN: "ghp_xxx"
```
### Editor integration (ACP)[​](#editor-integration-acp)
```
pip install -e '.[acp]'hermes acp
```
See [ACP Editor Integration](/docs/user-guide/features/acp).
## Common Failure Modes[​](#common-failure-modes)
These are the problems that waste the most time:
SymptomLikely causeFixHermes opens but gives empty or broken repliesProvider auth or model selection is wrongRun `hermes model` again and confirm provider, model, and authCustom endpoint "works" but returns garbageWrong base URL, model name, or not actually OpenAI-compatibleVerify the endpoint in a separate client firstGateway starts but nobody can message itBot token, allowlist, or platform setup is incompleteRe-run `hermes gateway setup` and check `hermes gateway status``hermes --continue` can't find old sessionSwitched profiles or session never savedCheck `hermes sessions list` and confirm you're in the right profileModel unavailable or odd fallback behaviorProvider routing or fallback settings are too aggressiveKeep routing off until the base provider is stable`hermes doctor` flags config problemsConfig values are missing or staleFix the config, retest a plain chat before adding features
## Recovery Toolkit[​](#recovery-toolkit)
When something feels off, use this order:
- `hermes doctor`
- `hermes model`
- `hermes setup`
- `hermes sessions list`
- `hermes --continue`
- `hermes gateway status`
That sequence gets you from "broken vibes" back to a known state fast.
## Quick Reference[​](#quick-reference)
CommandDescription`hermes`Start chatting`hermes model`Choose your LLM provider and model`hermes tools`Configure which tools are enabled per platform`hermes setup`Full setup wizard (configures everything at once)`hermes doctor`Diagnose issues`hermes update`Update to latest version`hermes gateway`Start the messaging gateway`hermes --continue`Resume last session
## Next Steps[​](#next-steps)
- [CLI Guide](/docs/user-guide/cli) — Master the terminal interface
- [Configuration](/docs/user-guide/configuration) — Customize your setup
- [Messaging Gateway](/docs/user-guide/messaging/) — Connect Telegram, Discord, Slack, WhatsApp, Signal, Email, or Home Assistant
- [Tools & Toolsets](/docs/user-guide/features/tools) — Explore available capabilities
- [AI Providers](/docs/integrations/providers) — Full provider list and setup details
- [Skills System](/docs/user-guide/features/skills) — Reusable workflows and knowledge
- [Tips & Best Practices](/docs/guides/tips) — Power user tips
[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/getting-started/quickstart.md)[NextInstallation](/docs/getting-started/installation)- [Who this is for](#who-this-is-for)
- [The fastest path](#the-fastest-path)
- [1. Install Hermes Agent](#1-install-hermes-agent)
- [2. Choose a Provider](#2-choose-a-provider)[How settings are stored](#how-settings-are-stored)
- [3. Run Your First Chat](#3-run-your-first-chat)
- [4. Verify Sessions Work](#4-verify-sessions-work)
- [5. Try Key Features](#5-try-key-features)[Use the terminal](#use-the-terminal)
- [Slash commands](#slash-commands)
- [Multi-line input](#multi-line-input)
- [Interrupt the agent](#interrupt-the-agent)
- [6. Add the Next Layer](#6-add-the-next-layer)[Bot or shared assistant](#bot-or-shared-assistant)
- [Automation and tools](#automation-and-tools)
- [Sandboxed terminal](#sandboxed-terminal)
- [Voice mode](#voice-mode)
- [Skills](#skills)
- [MCP servers](#mcp-servers)
- [Editor integration (ACP)](#editor-integration-acp)
- [Common Failure Modes](#common-failure-modes)
- [Recovery Toolkit](#recovery-toolkit)
- [Quick Reference](#quick-reference)
- [Next Steps](#next-steps)
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
