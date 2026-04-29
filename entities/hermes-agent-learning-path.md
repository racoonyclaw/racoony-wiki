---
title: "Learning Path"
id: hermes-agent-learning-path
pageType: entity
tags:
  - hermes-agent
  - documentation
hermes-source: https://hermes-agent.nousresearch.com/docs
---

Learning Path | Hermes Agent-
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
- Learning Path
On this page# Learning Path
Hermes Agent can do a lot — CLI assistant, Telegram/Discord bot, task automation, RL training, and more. This page helps you figure out where to start and what to read based on your experience level and what you're trying to accomplish.
Start HereIf you haven't installed Hermes Agent yet, begin with the [Installation guide](/docs/getting-started/installation) and then run through the [Quickstart](/docs/getting-started/quickstart). Everything below assumes you have a working installation.
## How to Use This Page[​](#how-to-use-this-page)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->
- Know your level? Jump to the [experience-level table](#by-experience-level) and follow the reading order for your tier.
- Have a specific goal? Skip to [By Use Case](#by-use-case) and find the scenario that matches.
- Just browsing? Check the [Key Features](#key-features-at-a-glance) table for a quick overview of everything Hermes Agent can do.
## By Experience Level[​](#by-experience-level)
LevelGoalRecommended ReadingTime EstimateBeginnerGet up and running, have basic conversations, use built-in tools[Installation](/docs/getting-started/installation) → [Quickstart](/docs/getting-started/quickstart) → [CLI Usage](/docs/user-guide/cli) → [Configuration](/docs/user-guide/configuration)~1 hourIntermediateSet up messaging bots, use advanced features like memory, cron jobs, and skills[Sessions](/docs/user-guide/sessions) → [Messaging](/docs/user-guide/messaging) → [Tools](/docs/user-guide/features/tools) → [Skills](/docs/user-guide/features/skills) → [Memory](/docs/user-guide/features/memory) → [Cron](/docs/user-guide/features/cron)~2–3 hoursAdvancedBuild custom tools, create skills, train models with RL, contribute to the project[Architecture](/docs/developer-guide/architecture) → [Adding Tools](/docs/developer-guide/adding-tools) → [Creating Skills](/docs/developer-guide/creating-skills) → [RL Training](/docs/user-guide/features/rl-training) → [Contributing](/docs/developer-guide/contributing)~4–6 hours
## By Use Case[​](#by-use-case)
Pick the scenario that matches what you want to do. Each one links you to the relevant docs in the order you should read them.
### "I want a CLI coding assistant"[​](#i-want-a-cli-coding-assistant)
Use Hermes Agent as an interactive terminal assistant for writing, reviewing, and running code.
- [Installation](/docs/getting-started/installation)
- [Quickstart](/docs/getting-started/quickstart)
- [CLI Usage](/docs/user-guide/cli)
- [Code Execution](/docs/user-guide/features/code-execution)
- [Context Files](/docs/user-guide/features/context-files)
- [Tips & Tricks](/docs/guides/tips)
tipPass files directly into your conversation with context files. Hermes Agent can read, edit, and run code in your projects.
### "I want a Telegram/Discord bot"[​](#i-want-a-telegramdiscord-bot)
Deploy Hermes Agent as a bot on your favorite messaging platform.
- [Installation](/docs/getting-started/installation)
- [Configuration](/docs/user-guide/configuration)
- [Messaging Overview](/docs/user-guide/messaging)
- [Telegram Setup](/docs/user-guide/messaging/telegram)
- [Discord Setup](/docs/user-guide/messaging/discord)
- [Voice Mode](/docs/user-guide/features/voice-mode)
- [Use Voice Mode with Hermes](/docs/guides/use-voice-mode-with-hermes)
- [Security](/docs/user-guide/security)
For full project examples, see:
- [Daily Briefing Bot](/docs/guides/daily-briefing-bot)
- [Team Telegram Assistant](/docs/guides/team-telegram-assistant)
### "I want to automate tasks"[​](#i-want-to-automate-tasks)
Schedule recurring tasks, run batch jobs, or chain agent actions together.
- [Quickstart](/docs/getting-started/quickstart)
- [Cron Scheduling](/docs/user-guide/features/cron)
- [Batch Processing](/docs/user-guide/features/batch-processing)
- [Delegation](/docs/user-guide/features/delegation)
- [Hooks](/docs/user-guide/features/hooks)
tipCron jobs let Hermes Agent run tasks on a schedule — daily summaries, periodic checks, automated reports — without you being present.
### "I want to build custom tools/skills"[​](#i-want-to-build-custom-toolsskills)
Extend Hermes Agent with your own tools and reusable skill packages.
- [Tools Overview](/docs/user-guide/features/tools)
- [Skills Overview](/docs/user-guide/features/skills)
- [MCP (Model Context Protocol)](/docs/user-guide/features/mcp)
- [Architecture](/docs/developer-guide/architecture)
- [Adding Tools](/docs/developer-guide/adding-tools)
- [Creating Skills](/docs/developer-guide/creating-skills)
tipTools are individual functions the agent can call. Skills are bundles of tools, prompts, and configuration packaged together. Start with tools, graduate to skills.
### "I want to train models"[​](#i-want-to-train-models)
Use reinforcement learning to fine-tune model behavior with Hermes Agent's built-in RL training pipeline.
- [Quickstart](/docs/getting-started/quickstart)
- [Configuration](/docs/user-guide/configuration)
- [RL Training](/docs/user-guide/features/rl-training)
- [Provider Routing](/docs/user-guide/features/provider-routing)
- [Architecture](/docs/developer-guide/architecture)
tipRL training works best when you already understand the basics of how Hermes Agent handles conversations and tool calls. Run through the Beginner path first if you're new.
### "I want to use it as a Python library"[​](#i-want-to-use-it-as-a-python-library)
Integrate Hermes Agent into your own Python applications programmatically.
- [Installation](/docs/getting-started/installation)
- [Quickstart](/docs/getting-started/quickstart)
- [Python Library Guide](/docs/guides/python-library)
- [Architecture](/docs/developer-guide/architecture)
- [Tools](/docs/user-guide/features/tools)
- [Sessions](/docs/user-guide/sessions)
## Key Features at a Glance[​](#key-features-at-a-glance)
Not sure what's available? Here's a quick directory of major features:
FeatureWhat It DoesLinkToolsBuilt-in tools the agent can call (file I/O, search, shell, etc.)[Tools](/docs/user-guide/features/tools)SkillsInstallable plugin packages that add new capabilities[Skills](/docs/user-guide/features/skills)MemoryPersistent memory across sessions[Memory](/docs/user-guide/features/memory)Context FilesFeed files and directories into conversations[Context Files](/docs/user-guide/features/context-files)MCPConnect to external tool servers via Model Context Protocol[MCP](/docs/user-guide/features/mcp)CronSchedule recurring agent tasks[Cron](/docs/user-guide/features/cron)DelegationSpawn sub-agents for parallel work[Delegation](/docs/user-guide/features/delegation)Code ExecutionRun Python scripts that call Hermes tools programmatically[Code Execution](/docs/user-guide/features/code-execution)BrowserWeb browsing and scraping[Browser](/docs/user-guide/features/browser)HooksEvent-driven callbacks and middleware[Hooks](/docs/user-guide/features/hooks)Batch ProcessingProcess multiple inputs in bulk[Batch Processing](/docs/user-guide/features/batch-processing)RL TrainingFine-tune models with reinforcement learning[RL Training](/docs/user-guide/features/rl-training)Provider RoutingRoute requests across multiple LLM providers[Provider Routing](/docs/user-guide/features/provider-routing)
## What to Read Next[​](#what-to-read-next)
Based on where you are right now:
- Just finished installing? → Head to the [Quickstart](/docs/getting-started/quickstart) to run your first conversation.
- Completed the Quickstart? → Read [CLI Usage](/docs/user-guide/cli) and [Configuration](/docs/user-guide/configuration) to customize your setup.
- Comfortable with the basics? → Explore [Tools](/docs/user-guide/features/tools), [Skills](/docs/user-guide/features/skills), and [Memory](/docs/user-guide/features/memory) to unlock the full power of the agent.
- Setting up for a team? → Read [Security](/docs/user-guide/security) and [Sessions](/docs/user-guide/sessions) to understand access control and conversation management.
- Ready to build? → Jump into the [Developer Guide](/docs/developer-guide/architecture) to understand the internals and start contributing.
- Want practical examples? → Check out the [Guides](/docs/guides/tips) section for real-world projects and tips.
tipYou don't need to read everything. Pick the path that matches your goal, follow the links in order, and you'll be productive quickly. You can always come back to this page to find your next step.
[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/getting-started/learning-path.md)[PreviousUpdating & Uninstalling](/docs/getting-started/updating)[NextCLI Interface](/docs/user-guide/cli)- [How to Use This Page](#how-to-use-this-page)
- [By Experience Level](#by-experience-level)
- [By Use Case](#by-use-case)["I want a CLI coding assistant"](#i-want-a-cli-coding-assistant)
- ["I want a Telegram/Discord bot"](#i-want-a-telegramdiscord-bot)
- ["I want to automate tasks"](#i-want-to-automate-tasks)
- ["I want to build custom tools/skills"](#i-want-to-build-custom-toolsskills)
- ["I want to train models"](#i-want-to-train-models)
- ["I want to use it as a Python library"](#i-want-to-use-it-as-a-python-library)
- [Key Features at a Glance](#key-features-at-a-glance)
- [What to Read Next](#what-to-read-next)
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
