---
pageType: entity
id: entity.features-overview
title: Features Overview
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-features-overview.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-features-overview.md
updatedAt: '2026-04-24T15:05:25.856301+00:00'
sourceIds:
- agentskillsio
sources:
- sourceId: agentskillsio
  sourceType: web
  sourcePath: https://agentskills.io/specification
  title: '[agentskills.io](https://agentskills.io/specification)'
claims:
- id: tools-toolsetsdocsuser-guidefeaturestools-tool
  text: "[[[entity.features-tools|Tools & Toolsets]]](/docs/user-guide/features/tools)** \u2014 Tools are functions\
    \ that extend the agent's capabilities. They're organized into logical toolsets\
    \ that can be enabled or disabled per platform, covering web search, terminal\
    \ execution, file editing, memory, delegation, and more."
  status: supported
  confidence: null
- id: skills-systemdocsuser-guidefeaturesskills-on-dem
  text: "[[[entity.features-skills|Skills System]]](/docs/user-guide/features/skills)** \u2014 On-demand knowledge\
    \ documents the agent can load when needed. Skills follow a progressive disclosure\
    \ pattern to minimize token usage and are compatible with the [agentskills.io](https://agentskills.io/specification)\
    \ open standard."
  status: supported
  confidence: null
- id: persistent-memorydocsuser-guidefeaturesmemory-bo
  text: "[[[entity.features-memory|Persistent Memory]]](/docs/user-guide/features/memory)** \u2014 Bounded, curated\
    \ memory that persists across sessions. Hermes remembers your preferences, projects,\
    \ environment, and things it has learned via `MEMORY.md` and `USER.md`."
  status: supported
  confidence: null
- id: context-filesdocsuser-guidefeaturescontext-files
  text: "[[[entity.features-context-files|Context Files]]](/docs/user-guide/features/context-files)** \u2014 Hermes\
    \ automatically discovers and loads project [[entity.features-context-files|Context Files]] (`.hermes.md`, `AGENTS.md`,\
    \ `CLAUDE.md`, `SOUL.md`, `.cursorrules`) that shape how it behaves in your project."
  status: supported
  confidence: null
- id: context-referencesdocsuser-guidefeaturescontext-refer
  text: "[[[entity.features-context-files|Context References]]](/docs/user-guide/features/context-references)** \u2014\
    \ Type `@` followed by a reference to inject files, folders, git diffs, and URLs\
    \ directly into your messages. Hermes expands the reference inline and appends\
    \ the content automatically."
  status: supported
  confidence: null
- id: checkpointsdocsuser-guidecheckpoints-and-rollback
  text: "[[[entity.features-checkpoints|Checkpoints]]](/docs/user-guide/[[entity.features-checkpoints|Checkpoints]]-and-rollback)** \u2014 Hermes\
    \ automatically snapshots your working directory before making file changes, giving\
    \ you a safety net to roll back with `/rollback` if something goes wrong."
  status: supported
  confidence: null
- id: scheduled-tasks-crondocsuser-guidefeaturescron
  text: "[Scheduled Tasks (Cron)](/docs/user-guide/features/cron)** \u2014 Schedule\
    \ tasks to run automatically with natural language or cron expressions. Jobs can\
    \ attach skills, deliver results to any platform, and support pause/resume/edit\
    \ operations."
  status: supported
  confidence: null
- id: subagent-delegationdocsuser-guidefeaturesdelegation
  text: "[[[entity.features-delegation|Subagent Delegation]]](/docs/user-guide/features/delegation)** \u2014 The\
    \ `delegate_task` tool spawns child agent instances with isolated context, restricted\
    \ toolsets, and their own terminal sessions. Run 3 concurrent subagents by default\
    \ (configurable) for parallel workstreams."
  status: supported
  confidence: null
- id: code-executiondocsuser-guidefeaturescode-execution
  text: "[[[entity.features-code-execution|Code Execution]]](/docs/user-guide/features/code-execution)** \u2014 The `execute_code`\
    \ tool lets the agent write Python scripts that call Hermes tools programmatically,\
    \ collapsing multi-step workflows into a single LLM turn via sandboxed RPC execution."
  status: supported
  confidence: null
- id: event-hooksdocsuser-guidefeatureshooks-run-custo
  text: "[[[entity.features-hooks|Event Hooks]]](/docs/user-guide/features/hooks)** \u2014 Run custom code at\
    \ key lifecycle points. Gateway hooks handle logging, alerts, and webhooks; plugin\
    \ hooks handle tool interception, metrics, and guardrails."
  status: supported
  confidence: null
- id: batch-processingdocsuser-guidefeaturesbatch-processin
  text: "[[[entity.features-batch-processing|Batch Processing]]](/docs/user-guide/features/batch-processing)** \u2014 Run\
    \ the Hermes agent across hundreds or thousands of prompts in parallel, generating\
    \ structured ShareGPT-format trajectory data for training data generation or evaluation."
  status: supported
  confidence: null
- id: voice-modedocsuser-guidefeaturesvoice-mode-full
  text: "[[[entity.features-voice-mode|Voice Mode]]](/docs/user-guide/features/voice-mode)** \u2014 Full voice interaction\
    \ across CLI and messaging platforms. Talk to the agent using your microphone,\
    \ hear spoken replies, and have live voice conversations in Discord voice channels."
  status: supported
  confidence: null
- id: browser-automationdocsuser-guidefeaturesbrowser
  text: "[[[entity.features-browser|Browser Automation]]](/docs/user-guide/features/browser)** \u2014 Full browser\
    \ automation with multiple backends: Browserbase cloud, Browser Use cloud, local\
    \ Chrome via CDP, or local Chromium. Navigate websites, fill forms, and extract\
    \ information."
  status: supported
  confidence: null
- id: vision-image-pastedocsuser-guidefeaturesvision
  text: "[[[entity.features-vision|Vision & Image Paste]]](/docs/user-guide/features/vision)** \u2014 Multimodal\
    \ vision support. Paste images from your clipboard into the CLI and ask the agent\
    \ to analyze, describe, or work with them using any vision-capable model."
  status: supported
  confidence: null
- id: image-generationdocsuser-guidefeaturesimage-generatio
  text: "[[[entity.features-image-generation|Image Generation]]](/docs/user-guide/features/image-generation)** \u2014 Generate\
    \ images from text prompts using FAL.ai. Eight models supported (FLUX 2 Klein/Pro,\
    \ GPT-Image 1.5, Nano Banana Pro, Ideogram V3, Recraft V4 Pro, Qwen, Z-Image Turbo);\
    \ pick one via `hermes tools`."
  status: supported
  confidence: null
- id: voice-ttsdocsuser-guidefeaturestts-text-to-spe
  text: "[Voice & [[entity.features-tts|TTS]]](/docs/user-guide/features/[[entity.features-tts|TTS]])** \u2014 Text-to-speech output\
    \ and voice message transcription across all messaging platforms, with five provider\
    \ options: Edge [[entity.features-tts|TTS]] (free), ElevenLabs, OpenAI [[entity.features-tts|TTS]], MiniMax, and NeuTTS."
  status: supported
  confidence: null
- id: [[entity.features-mcp|MCP]]-integrationdocsuser-guidefeaturesmcp-connect
  text: "[[[entity.features-mcp|MCP]] Integration](/docs/user-guide/features/[[entity.features-mcp|MCP]])** \u2014 Connect to any\
    \ [[entity.features-mcp|MCP]] server via stdio or HTTP transport. Access external tools from GitHub, databases,\
    \ file systems, and internal APIs without writing native Hermes tools. Includes\
    \ per-server tool filtering and sampling support."
  status: supported
  confidence: null
- id: provider-routingdocsuser-guidefeaturesprovider-routin
  text: "[[[entity.features-provider-routing|Provider Routing]]](/docs/user-guide/features/provider-routing)** \u2014 Fine-grained\
    \ control over which AI providers handle your requests. Optimize for cost, speed,\
    \ or quality with sorting, whitelists, blacklists, and priority ordering."
  status: supported
  confidence: null
- id: fallback-providersdocsuser-guidefeaturesfallback-prov
  text: "[[[entity.features-fallback-providers|Fallback Providers]]](/docs/user-guide/features/fallback-providers)** \u2014\
    \ Automatic failover to backup LLM providers when your primary model encounters\
    \ errors, including independent fallback for auxiliary tasks like vision and compression."
  status: supported
  confidence: null
- id: credential-poolsdocsuser-guidefeaturescredential-pool
  text: "[[[entity.features-credential-pools|Credential Pools]]](/docs/user-guide/features/credential-pools)** \u2014 Distribute\
    \ API calls across multiple keys for the same provider. Automatic rotation on\
    \ rate limits or failures."
  status: supported
  confidence: null
- id: memory-providersdocsuser-guidefeaturesmemory-provider
  text: "[[[entity.features-memory-providers|Memory Providers]]](/docs/user-guide/features/memory-providers)** \u2014 Plug\
    \ in external memory backends (Honcho, OpenViking, Mem0, Hindsight, Holographic,\
    \ RetainDB, ByteRover) for cross-session user modeling and personalization beyond\
    \ the built-in memory system."
  status: supported
  confidence: null
- id: api-serverdocsuser-guidefeaturesapi-server-expos
  text: "[[[entity.features-api-server|API Server]]](/docs/user-guide/features/api-server)** \u2014 Expose Hermes\
    \ as an OpenAI-compatible HTTP endpoint. Connect any frontend that speaks the\
    \ OpenAI format \u2014 Open WebUI, LobeChat, LibreChat, and more."
  status: supported
  confidence: null
- id: ide-integration-acpdocsuser-guidefeaturesacp-u
  text: "[IDE Integration ([[entity.features-acp|ACP]])](/docs/user-guide/features/[[entity.features-acp|ACP]])** \u2014 Use Hermes\
    \ inside [[entity.features-acp|ACP]]-compatible editors such as VS Code, Zed, and JetBrains. Chat, tool\
    \ activity, file diffs, and terminal commands render inside your editor."
  status: supported
  confidence: null
- id: rl-trainingdocsuser-guidefeaturesrl-training-gen
  text: "[[[entity.features-rl-training|RL Training]]](/docs/user-guide/features/rl-training)** \u2014 Generate trajectory\
    \ data from agent sessions for reinforcement learning and model fine-tuning."
  status: supported
  confidence: null
- id: [[entity.features-personality|Personality]]-soulmddocsuser-guidefeaturespersonalit
  text: "[[[entity.features-personality|Personality]] & SOUL.md](/docs/user-guide/features/[[entity.features-personality|Personality]])** \u2014 Fully\
    \ customizable agent [[entity.features-personality|Personality]]. `SOUL.md` is the primary identity file \u2014\
    \ the first thing in the system prompt \u2014 and you can swap in built-in or\
    \ custom `/[[entity.features-personality|Personality]]` presets per session."
  status: supported
  confidence: null
- id: skins-themesdocsuser-guidefeaturesskins-custom
  text: "[Skins & Themes](/docs/user-guide/features/skins)** \u2014 Customize the\
    \ CLI's visual presentation: banner colors, spinner faces and verbs, response-box\
    \ labels, branding text, and the tool activity prefix."
  status: supported
  confidence: null
- id: pluginsdocsuser-guidefeaturesplugins-add-custom
  text: "[[[entity.features-plugins|Plugins]]](/docs/user-guide/features/[[entity.features-plugins|Plugins]])** \u2014 Add custom tools, hooks,\
    \ and integrations without modifying core code. Three plugin types: general [[entity.features-plugins|Plugins]]\
    \ (tools/hooks), [[entity.features-memory-providers|Memory Providers]] (cross-session knowledge), and context engines\
    \ (alternative context management). Managed via the unified `hermes [[entity.features-plugins|Plugins]]` interactive\
    \ UI."
  status: supported
  confidence: null
---

Hermes Agent includes a rich set of capabilities that extend far beyond basic chat. From [[entity.features-memory|Persistent Memory]] and file-aware context to [[entity.features-browser|Browser Automation]] and voice conversations, these features work together to make Hermes a powerful autonomous assistant.

## Core[​](#core "Direct link to Core")

- **[[[entity.features-tools|Tools & Toolsets]]](/docs/user-guide/features/tools)** — Tools are functions that extend the agent's capabilities. They're organized into logical toolsets that can be enabled or disabled per platform, covering web search, terminal execution, file editing, memory, delegation, and more.
- **[[[entity.features-skills|Skills System]]](/docs/user-guide/features/skills)** — On-demand knowledge documents the agent can load when needed. Skills follow a progressive disclosure pattern to minimize token usage and are compatible with the [agentskills.io](https://agentskills.io/specification) open standard.
- **[[[entity.features-memory|Persistent Memory]]](/docs/user-guide/features/memory)** — Bounded, curated memory that persists across sessions. Hermes remembers your preferences, projects, environment, and things it has learned via `MEMORY.md` and `USER.md`.
- **[[[entity.features-context-files|Context Files]]](/docs/user-guide/features/context-files)** — Hermes automatically discovers and loads project [[entity.features-context-files|Context Files]] (`.hermes.md`, `AGENTS.md`, `CLAUDE.md`, `SOUL.md`, `.cursorrules`) that shape how it behaves in your project.
- **[[[entity.features-context-files|Context References]]](/docs/user-guide/features/context-references)** — Type `@` followed by a reference to inject files, folders, git diffs, and URLs directly into your messages. Hermes expands the reference inline and appends the content automatically.
- **[[[entity.features-checkpoints|Checkpoints]]](/docs/user-guide/[[entity.features-checkpoints|Checkpoints]]-and-rollback)** — Hermes automatically snapshots your working directory before making file changes, giving you a safety net to roll back with `/rollback` if something goes wrong.

## Automation[​](#automation "Direct link to Automation")

- **[Scheduled Tasks (Cron)](/docs/user-guide/features/cron)** — Schedule tasks to run automatically with natural language or cron expressions. Jobs can attach skills, deliver results to any platform, and support pause/resume/edit operations.
- **[[[entity.features-delegation|Subagent Delegation]]](/docs/user-guide/features/delegation)** — The `delegate_task` tool spawns child agent instances with isolated context, restricted toolsets, and their own terminal sessions. Run 3 concurrent subagents by default (configurable) for parallel workstreams.
- **[[[entity.features-code-execution|Code Execution]]](/docs/user-guide/features/code-execution)** — The `execute_code` tool lets the agent write Python scripts that call Hermes tools programmatically, collapsing multi-step workflows into a single LLM turn via sandboxed RPC execution.
- **[[[entity.features-hooks|Event Hooks]]](/docs/user-guide/features/hooks)** — Run custom code at key lifecycle points. Gateway hooks handle logging, alerts, and webhooks; plugin hooks handle tool interception, metrics, and guardrails.
- **[[[entity.features-batch-processing|Batch Processing]]](/docs/user-guide/features/batch-processing)** — Run the Hermes agent across hundreds or thousands of prompts in parallel, generating structured ShareGPT-format trajectory data for training data generation or evaluation.

## Media & Web[​](#media--web "Direct link to Media & Web")

- **[[[entity.features-voice-mode|Voice Mode]]](/docs/user-guide/features/voice-mode)** — Full voice interaction across CLI and messaging platforms. Talk to the agent using your microphone, hear spoken replies, and have live voice conversations in Discord voice channels.
- **[[[entity.features-browser|Browser Automation]]](/docs/user-guide/features/browser)** — Full [[entity.features-browser|Browser Automation]] with multiple backends: Browserbase cloud, Browser Use cloud, local Chrome via CDP, or local Chromium. Navigate websites, fill forms, and extract information.
- **[[[entity.features-vision|Vision & Image Paste]]](/docs/user-guide/features/vision)** — Multimodal vision support. Paste images from your clipboard into the CLI and ask the agent to analyze, describe, or work with them using any vision-capable model.
- **[[[entity.features-image-generation|Image Generation]]](/docs/user-guide/features/image-generation)** — Generate images from text prompts using FAL.ai. Eight models supported (FLUX 2 Klein/Pro, GPT-Image 1.5, Nano Banana Pro, Ideogram V3, Recraft V4 Pro, Qwen, Z-Image Turbo); pick one via `hermes tools`.
- **[Voice & [[entity.features-tts|TTS]]](/docs/user-guide/features/[[entity.features-tts|TTS]])** — Text-to-speech output and voice message transcription across all messaging platforms, with five provider options: Edge [[entity.features-tts|TTS]] (free), ElevenLabs, OpenAI [[entity.features-tts|TTS]], MiniMax, and NeuTTS.

## Integrations[​](#integrations "Direct link to Integrations")

- **[[[entity.features-mcp|MCP]] Integration](/docs/user-guide/features/[[entity.features-mcp|MCP]])** — Connect to any [[entity.features-mcp|MCP]] server via stdio or HTTP transport. Access external tools from GitHub, databases, file systems, and internal APIs without writing native Hermes tools. Includes per-server tool filtering and sampling support.
- **[[[entity.features-provider-routing|Provider Routing]]](/docs/user-guide/features/provider-routing)** — Fine-grained control over which AI providers handle your requests. Optimize for cost, speed, or quality with sorting, whitelists, blacklists, and priority ordering.
- **[[[entity.features-fallback-providers|Fallback Providers]]](/docs/user-guide/features/fallback-providers)** — Automatic failover to backup LLM providers when your primary model encounters errors, including independent fallback for auxiliary tasks like vision and compression.
- **[[[entity.features-credential-pools|Credential Pools]]](/docs/user-guide/features/credential-pools)** — Distribute API calls across multiple keys for the same provider. Automatic rotation on rate limits or failures.
- **[[[entity.features-memory-providers|Memory Providers]]](/docs/user-guide/features/memory-providers)** — Plug in external memory backends (Honcho, OpenViking, Mem0, Hindsight, Holographic, RetainDB, ByteRover) for cross-session user modeling and personalization beyond the built-in memory system.
- **[[[entity.features-api-server|API Server]]](/docs/user-guide/features/api-server)** — Expose Hermes as an OpenAI-compatible HTTP endpoint. Connect any frontend that speaks the OpenAI format — Open WebUI, LobeChat, LibreChat, and more.
- **[IDE Integration ([[entity.features-acp|ACP]])](/docs/user-guide/features/[[entity.features-acp|ACP]])** — Use Hermes inside [[entity.features-acp|ACP]]-compatible editors such as VS Code, Zed, and JetBrains. Chat, tool activity, file diffs, and terminal commands render inside your editor.
- **[[[entity.features-rl-training|RL Training]]](/docs/user-guide/features/rl-training)** — Generate trajectory data from agent sessions for reinforcement learning and model fine-tuning.

## Customization[​](#customization "Direct link to Customization")

- **[[[entity.features-personality|Personality]] & SOUL.md](/docs/user-guide/features/[[entity.features-personality|Personality]])** — Fully customizable agent [[entity.features-personality|Personality]]. `SOUL.md` is the primary identity file — the first thing in the system prompt — and you can swap in built-in or custom `/[[entity.features-personality|Personality]]` presets per session.
- **[Skins & Themes](/docs/user-guide/features/skins)** — Customize the CLI's visual presentation: banner colors, spinner faces and verbs, response-box labels, branding text, and the tool activity prefix.
- **[[[entity.features-plugins|Plugins]]](/docs/user-guide/features/[[entity.features-plugins|Plugins]])** — Add custom tools, hooks, and integrations without modifying core code. Three plugin types: general [[entity.features-plugins|Plugins]] (tools/hooks), [[entity.features-memory-providers|Memory Providers]] (cross-session knowledge), and context engines (alternative context management). Managed via the unified `hermes [[entity.features-plugins|Plugins]]` interactive UI.