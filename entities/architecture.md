---
pageType: entity
id: entity.architecture
title: Architecture
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-architecture.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-architecture.md
updatedAt: '2026-04-24T15:05:24.456599+00:00'
sourceIds:
- githubcom
sources:
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent/edit/main/website/docs/developer-guide/architecture.md
  title: '[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/developer-guide'
claims:
- id: this-page-orient-yourself
  text: "This page** \u2014 orient yourself"
  status: supported
  confidence: null
- id: agent-loop-internalsdocsdeveloper-guideagent-loop
  text: "[Agent Loop Internals](/docs/developer-guide/agent-loop)** \u2014 how AIAgent\
    \ works"
  status: supported
  confidence: null
- id: prompt-assemblydocsdeveloper-guideprompt-assembly
  text: "[Prompt Assembly](/docs/developer-guide/prompt-assembly)** \u2014 system\
    \ prompt construction"
  status: supported
  confidence: null
- id: provider-runtime-resolutiondocsdeveloper-guideprovider
  text: "[Provider Runtime Resolution](/docs/developer-guide/provider-runtime)** \u2014\
    \ how providers are selected"
  status: supported
  confidence: null
- id: adding-providersdocsdeveloper-guideadding-providers
  text: "[Adding Providers](/docs/developer-guide/adding-providers)** \u2014 practical\
    \ guide to adding a new provider"
  status: supported
  confidence: null
- id: tools-runtimedocsdeveloper-guidetools-runtime-too
  text: "[Tools Runtime](/docs/developer-guide/tools-runtime)** \u2014 tool registry,\
    \ dispatch, environments"
  status: supported
  confidence: null
- id: session-storagedocsdeveloper-guidesession-storage
  text: "[Session Storage](/docs/developer-guide/session-storage)** \u2014 SQLite\
    \ schema, FTS5, session lineage"
  status: supported
  confidence: null
- id: gateway-internalsdocsdeveloper-guidegateway-internals
  text: "[Gateway Internals](/docs/developer-guide/gateway-internals)** \u2014 messaging\
    \ platform gateway"
  status: supported
  confidence: null
- id: context-compression-amp-prompt-cachingdocsdeveloper-g
  text: "[Context Compression &amp; Prompt Caching](/docs/developer-guide/context-compression-and-caching)**\
    \ \u2014 compression and caching"
  status: supported
  confidence: null
- id: acp-internalsdocsdeveloper-guideacp-internals-ide
  text: "[ACP Internals](/docs/developer-guide/acp-internals)** \u2014 IDE integration"
  status: supported
  confidence: null
- id: environments-benchmarks-amp-data-generationdocsdevel
  text: "[Environments, Benchmarks &amp; Data Generation](/docs/developer-guide/environments)**\
    \ \u2014 RL training"
  status: supported
  confidence: null
- id: prompt-builderpy-assembles-the-system-prompt-from-pe
  text: "`prompt_builder.py`** \u2014 Assembles the system prompt from: personality\
    \ (SOUL.md), memory (MEMORY.md, USER.md), skills, context files (AGENTS.md, .hermes.md),\
    \ tool-use guidance, and model-specific instructions"
  status: supported
  confidence: null
- id: prompt-cachingpy-applies-anthropic-cache-breakpoints
  text: "`prompt_caching.py`** \u2014 Applies Anthropic cache breakpoints for prefix\
    \ caching"
  status: supported
  confidence: null
- id: context-compressorpy-summarizes-middle-conversation-t
  text: "`context_compressor.py`** \u2014 Summarizes middle conversation turns when\
    \ context exceeds thresholds"
  status: supported
  confidence: null
---

This page is the top-level map of Hermes Agent internals. Use it to orient yourself in the codebase, then dive into subsystem-specific docs for implementation details.

## System Overview

```
┌─────────────────────────────────────────────────────────────────────┐│                        Entry Points                                  ││                                                                      ││  CLI (cli.py)    Gateway (gateway/run.py)    ACP (acp_adapter/)     ││  Batch Runner    API Server                  Python Library          │└──────────┬──────────────┬───────────────────────┬───────────────────┘           │              │                       │           ▼              ▼                       ▼┌─────────────────────────────────────────────────────────────────────┐│                     AIAgent (run_agent.py)                          ││                                                                     ││  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐               ││  │ Prompt       │  │ Provider     │  │ Tool         │               ││  │ Builder      │  │ Resolution   │  │ Dispatch     │               ││  │ (prompt_     │  │ (runtime_    │  │ (model_      │               ││  │  builder.py) │  │  provider.py)│  │  tools.py)   │               ││  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘               ││         │                 │                 │                       ││  ┌──────┴───────┐  ┌──────┴───────┐  ┌──────┴───────┐               ││  │ Compression  │  │ 3 API Modes  │  │ Tool Registry│               ││  │ &amp; Caching    │  │ chat_compl.  │  │ (registry.py)│               ││  │              │  │ codex_resp.  │  │ 47 tools     │               ││  │              │  │ anthropic    │  │ 19 toolsets  │               ││  └──────────────┘  └──────────────┘  └──────────────┘               │└─────────────────────────────────────────────────────────────────────┘           │                                    │           ▼                                    ▼┌───────────────────┐              ┌──────────────────────┐│ Session Storage   │              │ Tool Backends         ││ (SQLite + FTS5)   │              │ Terminal (6 backends) ││ hermes_state.py   │              │ Browser (5 backends)  ││ gateway/session.py│              │ Web (4 backends)      │└───────────────────┘              │ MCP (dynamic)         │                                   │ File, Vision, etc.    │                                   └──────────────────────┘
```
## Directory Structure

```
hermes-agent/├── run_agent.py              # AIAgent — core conversation loop (~10,700 lines)├── cli.py                    # HermesCLI — interactive terminal UI (~10,000 lines)├── model_tools.py            # Tool discovery, schema collection, dispatch├── toolsets.py               # Tool groupings and platform presets├── hermes_state.py           # SQLite session/state database with FTS5├── hermes_constants.py       # HERMES_HOME, profile-aware paths├── batch_runner.py           # Batch trajectory generation│├── agent/                    # Agent internals│   ├── prompt_builder.py     # System prompt assembly│   ├── context_engine.py     # ContextEngine ABC (pluggable)│   ├── context_compressor.py # Default engine — lossy summarization│   ├── prompt_caching.py     # Anthropic prompt caching│   ├── auxiliary_client.py   # Auxiliary LLM for side tasks (vision, summarization)│   ├── model_metadata.py     # Model context lengths, token estimation│   ├── models_dev.py         # models.dev registry integration│   ├── anthropic_adapter.py  # Anthropic Messages API format conversion│   ├── display.py            # KawaiiSpinner, tool preview formatting│   ├── skill_commands.py     # Skill slash commands│   ├── memory_manager.py    # Memory manager orchestration│   ├── memory_provider.py   # Memory provider ABC│   └── trajectory.py         # Trajectory saving helpers│├── hermes_cli/               # CLI subcommands and setup│   ├── main.py               # Entry point — all `hermes` subcommands (~6,000 lines)│   ├── config.py             # DEFAULT_CONFIG, OPTIONAL_ENV_VARS, migration│   ├── commands.py           # COMMAND_REGISTRY — central slash command definitions│   ├── auth.py               # PROVIDER_REGISTRY, credential resolution│   ├── runtime_provider.py   # Provider → api_mode + credentials│   ├── models.py             # Model catalog, provider model lists│   ├── model_switch.py       # /model command logic (CLI + gateway shared)│   ├── setup.py              # Interactive setup wizard (~3,100 lines)│   ├── skin_engine.py        # CLI theming engine│   ├── skills_config.py      # hermes skills — enable/disable per platform│   ├── skills_hub.py         # /skills slash command│   ├── tools_config.py       # hermes tools — enable/disable per platform│   ├── plugins.py            # PluginManager — discovery, loading, hooks│   ├── callbacks.py          # Terminal callbacks (clarify, sudo, approval)│   └── gateway.py            # hermes gateway start/stop│├── tools/                    # Tool implementations (one file per tool)│   ├── registry.py           # Central tool registry│   ├── approval.py           # Dangerous command detection│   ├── terminal_tool.py      # Terminal orchestration│   ├── process_registry.py   # Background process management│   ├── file_tools.py         # read_file, write_file, patch, search_files│   ├── web_tools.py          # web_search, web_extract│   ├── browser_tool.py       # 10 browser automation tools│   ├── code_execution_tool.py # execute_code sandbox│   ├── delegate_tool.py      # Subagent delegation│   ├── mcp_tool.py           # MCP client (~2,200 lines)│   ├── credential_files.py   # File-based credential passthrough│   ├── env_passthrough.py    # Env var passthrough for sandboxes│   ├── ansi_strip.py         # ANSI escape stripping│   └── environments/         # Terminal backends (local, docker, ssh, modal, daytona, singularity)│├── gateway/                  # Messaging platform gateway│   ├── run.py                # GatewayRunner — message dispatch (~9,000 lines)│   ├── session.py            # SessionStore — conversation persistence│   ├── delivery.py           # Outbound message delivery│   ├── pairing.py            # DM pairing authorization│   ├── hooks.py              # Hook discovery and lifecycle events│   ├── mirror.py             # Cross-session message mirroring│   ├── status.py             # Token locks, profile-scoped process tracking│   ├── builtin_hooks/        # Always-registered hooks│   └── platforms/            # 18 adapters: telegram, discord, slack, whatsapp,│                             #   signal, matrix, mattermost, email, sms,│                             #   dingtalk, feishu, wecom, wecom_callback, weixin,│                             #   bluebubbles, qqbot, homeassistant, webhook, api_server│├── acp_adapter/              # ACP server (VS Code / Zed / JetBrains)├── cron/                     # Scheduler (jobs.py, scheduler.py)├── plugins/memory/           # Memory provider plugins├── plugins/context_engine/   # Context engine plugins├── environments/             # RL training environments (Atropos)├── skills/                   # Bundled skills (always available)├── optional-skills/          # Official optional skills (install explicitly)├── website/                  # Docusaurus documentation site└── tests/                    # Pytest suite (~3,000+ tests)
```
## Data Flow

### CLI Session

```
User input → HermesCLI.process_input()  → AIAgent.run_conversation()    → prompt_builder.build_system_prompt()    → runtime_provider.resolve_runtime_provider()    → API call (chat_completions / codex_responses / anthropic_messages)    → tool_calls? → model_tools.handle_function_call() → loop    → final response → display → save to SessionDB
```
### Gateway Message

```
Platform event → Adapter.on_message() → MessageEvent  → GatewayRunner._handle_message()    → authorize user    → resolve session key    → create AIAgent with session history    → AIAgent.run_conversation()    → deliver response back through adapter
```
### Cron Job

```
Scheduler tick → load due jobs from jobs.json  → create fresh AIAgent (no history)  → inject attached skills as context  → run job prompt  → deliver response to target platform  → update job state and next_run
```
## Recommended Reading Order

If you are new to the codebase:

- **This page** — orient yourself

- **[Agent Loop Internals](/docs/developer-guide/agent-loop)** — how AIAgent works

- **[Prompt Assembly](/docs/developer-guide/prompt-assembly)** — system prompt construction

- **[Provider Runtime Resolution](/docs/developer-guide/provider-runtime)** — how providers are selected

- **[Adding Providers](/docs/developer-guide/adding-providers)** — practical guide to adding a new provider

- **[Tools Runtime](/docs/developer-guide/tools-runtime)** — tool registry, dispatch, environments

- **[Session Storage](/docs/developer-guide/session-storage)** — SQLite schema, FTS5, session lineage

- **[Gateway Internals](/docs/developer-guide/gateway-internals)** — messaging platform gateway

- **[Context Compression &amp; Prompt Caching](/docs/developer-guide/context-compression-and-caching)** — compression and caching

- **[ACP Internals](/docs/developer-guide/acp-internals)** — IDE integration

- **[Environments, Benchmarks &amp; Data Generation](/docs/developer-guide/environments)** — RL training

## Major Subsystems

### Agent Loop

The synchronous orchestration engine (`AIAgent` in `run_agent.py`). Handles provider selection, prompt construction, tool execution, retries, fallback, callbacks, compression, and persistence. Supports three API modes for different provider backends.

→ [Agent Loop Internals](/docs/developer-guide/agent-loop)

### Prompt System

Prompt construction and maintenance across the conversation lifecycle:

- **`prompt_builder.py`** — Assembles the system prompt from: personality (SOUL.md), memory (MEMORY.md, USER.md), skills, context files (AGENTS.md, .hermes.md), tool-use guidance, and model-specific instructions

- **`prompt_caching.py`** — Applies Anthropic cache breakpoints for prefix caching

- **`context_compressor.py`** — Summarizes middle conversation turns when context exceeds thresholds

→ [Prompt Assembly](/docs/developer-guide/prompt-assembly), [Context Compression &amp; Prompt Caching](/docs/developer-guide/context-compression-and-caching)

### Provider Resolution

A shared runtime resolver used by CLI, gateway, cron, ACP, and auxiliary calls. Maps `(provider, model)` tuples to `(api_mode, api_key, base_url)`. Handles 18+ providers, OAuth flows, credential pools, and alias resolution.

→ [Provider Runtime Resolution](/docs/developer-guide/provider-runtime)

### Tool System

Central tool registry (`tools/registry.py`) with 47 registered tools across 19 toolsets. Each tool file self-registers at import time. The registry handles schema collection, dispatch, availability checking, and error wrapping. Terminal tools support 6 backends (local, Docker, SSH, Daytona, Modal, Singularity).

→ [Tools Runtime](/docs/developer-guide/tools-runtime)

### Session Persistence

SQLite-based session storage with FTS5 full-text search. Sessions have lineage tracking (parent/child across compressions), per-platform isolation, and atomic writes with contention handling.

→ [Session Storage](/docs/developer-guide/session-storage)

### Messaging Gateway

Long-running process with 18 platform adapters, unified session routing, user authorization (allowlists + DM pairing), slash command dispatch, hook system, cron ticking, and background maintenance.

→ [Gateway Internals](/docs/developer-guide/gateway-internals)

### Plugin System

Three discovery sources: `~/.hermes/plugins/` (user), `.hermes/plugins/` (project), and pip entry points. Plugins register tools, hooks, and CLI commands through a context API. Two specialized plugin types exist: memory providers (`plugins/memory/`) and context engines (`plugins/context_engine/`). Both are single-select — only one of each can be active at a time, configured via `hermes plugins` or `config.yaml`.

→ [Plugin Guide](/docs/guides/build-a-hermes-plugin), [Memory Provider Plugin](/docs/developer-guide/memory-provider-plugin)

### Cron

First-class agent tasks (not shell tasks). Jobs store in JSON, support multiple schedule formats, can attach skills and scripts, and deliver to any platform.

→ [Cron Internals](/docs/developer-guide/cron-internals)

### ACP Integration

Exposes Hermes as an editor-native agent over stdio/JSON-RPC for VS Code, Zed, and JetBrains.

→ [ACP Internals](/docs/developer-guide/acp-internals)

### RL / Environments / Trajectories

Full environment framework for evaluation and RL training. Integrates with Atropos, supports multiple tool-call parsers, and generates ShareGPT-format trajectories.

→ [Environments, Benchmarks &amp; Data Generation](/docs/developer-guide/environments), [Trajectories &amp; Training Format](/docs/developer-guide/trajectory-format)

## Design Principles

PrincipleWhat it means in practice**Prompt stability**System prompt doesn&#x27;t change mid-conversation. No cache-breaking mutations except explicit user actions (`/model`).**Observable execution**Every tool call is visible to the user via callbacks. Progress updates in CLI (spinner) and gateway (chat messages).**Interruptible**API calls and tool execution can be cancelled mid-flight by user input or signals.**Platform-agnostic core**One AIAgent class serves CLI, gateway, ACP, batch, and API server. Platform differences live in the entry point, not the agent.**Loose coupling**Optional subsystems (MCP, plugins, memory providers, RL environments) use registry patterns and check_fn gating, not hard dependencies.**Profile isolation**Each profile (`hermes -p &lt;name&gt;`) gets its own HERMES_HOME, config, memory, sessions, and gateway PID. Multiple profiles run concurrently.
## File Dependency Chain

```
tools/registry.py  (no deps — imported by all tool files)       ↑tools/*.py  (each calls registry.register() at import time)       ↑model_tools.py  (imports tools/registry + triggers tool discovery)       ↑run_agent.py, cli.py, batch_runner.py, environments/
```
This chain means tool registration happens at import time, before any agent instance is created. Any `tools/*.py` file with a top-level `registry.register()` call is auto-discovered — no manual import list needed.
[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/developer-guide/architecture.md)