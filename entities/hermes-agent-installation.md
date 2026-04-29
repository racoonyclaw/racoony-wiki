---
title: "Installation"
id: hermes-agent-installation
pageType: entity
tags:
  - hermes-agent
  - documentation
hermes-source: https://hermes-agent.nousresearch.com/docs
---

Installation | Hermes Agent-
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
- Installation
On this page# Installation
Get Hermes Agent up and running in under two minutes with the one-line installer.
## Quick Install[​](#quick-install)
### Linux / macOS / WSL2[​](#linux--macos--wsl2)
```
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
```
### Android / Termux[​](#android--termux)
Hermes now ships a Termux-aware installer path too:
```
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
```
The installer detects Termux automatically and switches to a tested Android flow:
- uses Termux `pkg` for system dependencies (`git`, `python`, `nodejs`, `ripgrep`, `ffmpeg`, build tools)
- creates the virtualenv with `python -m venv`
- exports `ANDROID_API_LEVEL` automatically for Android wheel builds
- installs a curated `.[termux]` extra with `pip`
- skips the untested browser / WhatsApp bootstrap by default
If you want the fully explicit path, follow the dedicated [Termux guide](/docs/getting-started/termux).
WindowsNative Windows is not supported. Please install [WSL2](https://learn.microsoft.com/en-us/windows/wsl/install) and run Hermes Agent from there. The install command above works inside WSL2.
### What the Installer Does[​](#what-the-installer-does)
The installer handles everything automatically — all dependencies (Python, Node.js, ripgrep, ffmpeg), the repo clone, virtual environment, global `hermes` command setup, and LLM provider configuration. By the end, you're ready to chat.
### After Installation[​](#after-installation)
Reload your shell and start chatting:
```
source ~/.bashrc   # or: source ~/.zshrchermes             # Start chatting!
```
To reconfigure individual settings later, use the dedicated commands:
```
hermes model          # Choose your LLM provider and modelhermes tools          # Configure which tools are enabledhermes gateway setup  # Set up messaging platformshermes config set     # Set individual config valueshermes setup          # Or run the full setup wizard to configure everything at once
```
## Prerequisites[​](#prerequisites)
The only prerequisite is Git. The installer automatically handles everything else:
- uv (fast Python package manager)
- Python 3.11 (via uv, no sudo needed)
- Node.js v22 (for browser automation and WhatsApp bridge)
- ripgrep (fast file search)
- ffmpeg (audio format conversion for TTS)
infoYou do not need to install Python, Node.js, ripgrep, or ffmpeg manually. The installer detects what's missing and installs it for you. Just make sure `git` is available (`git --version`).
Nix usersIf you use Nix (on NixOS, macOS, or Linux), there's a dedicated setup path with a Nix flake, declarative NixOS module, and optional container mode. See the [Nix & NixOS Setup](/docs/getting-started/nix-setup) guide.
## Manual / Developer Installation[​](#manual--developer-installation)
If you want to clone the repo and install from source — for contributing, running from a specific branch, or having full control over the virtual environment — see the [Development Setup](/docs/developer-guide/contributing#development-setup) section in the Contributing guide.
## Troubleshooting[​](#troubleshooting)
ProblemSolution`hermes: command not found`Reload your shell (`source ~/.bashrc`) or check PATH`API key not set`Run `hermes model` to configure your provider, or `hermes config set OPENROUTER_API_KEY your_key`Missing config after updateRun `hermes config check` then `hermes config migrate`
For more diagnostics, run `hermes doctor` — it will tell you exactly what's missing and how to fix it.
[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/getting-started/installation.md)[PreviousQuickstart](/docs/getting-started/quickstart)[NextAndroid / Termux](/docs/getting-started/termux)- [Quick Install](#quick-install)[Linux / macOS / WSL2](#linux--macos--wsl2)
- [Android / Termux](#android--termux)
- [What the Installer Does](#what-the-installer-does)
- [After Installation](#after-installation)
- [Prerequisites](#prerequisites)
- [Manual / Developer Installation](#manual--developer-installation)
- [Troubleshooting](#troubleshooting)
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
