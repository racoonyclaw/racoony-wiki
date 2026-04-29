---
pageType: entity
id: entity.ai-providers
title: AI Providers
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/providers.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/providers.md
updatedAt: '2026-04-24T15:05:24.508727+00:00'
sourceIds:
- consolecloudgoogleco
- ollamacom
- ollamacom
- buildnvidiacom
- huggingfaceco
- huggingfaceco
- ollamacom
- ollamacom
- docsvllmai
- githubcom
- githubcom
- githubcom
- huggingfaceco
- lmstudioai
- docslitellmai
- githubcom
- firecrawldev
- githubcom
- cloudcode-pagoogleap
- portalqwenai
- '17229192111434'
- wsl-host11434
- hostname
- '17229192111434'
- apitogetherxyz
- gpu-serverinternalco
- proxyexamplecom
- githubcom
sources:
- sourceId: consolecloudgoogleco
  sourceType: web
  sourcePath: https://console.cloud.google.com/apis/credentials
  title: '[console.cloud.google.com/apis/credentials](https://console.cloud.google.com/apis/credentials)'
- sourceId: ollamacom
  sourceType: web
  sourcePath: https://ollama.com/cloud
  title: '[Ollama Cloud](https://ollama.com/cloud)'
- sourceId: ollamacom
  sourceType: web
  sourcePath: https://ollama.com/settings/keys
  title: '[ollama.com/settings/keys](https://ollama.com/settings/keys)'
- sourceId: buildnvidiacom
  sourceType: web
  sourcePath: https://build.nvidia.com
  title: '[build.nvidia.com](https://build.nvidia.com)'
- sourceId: huggingfaceco
  sourceType: web
  sourcePath: https://huggingface.co/docs/inference-providers
  title: '[Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers)'
- sourceId: huggingfaceco
  sourceType: web
  sourcePath: https://huggingface.co/settings/tokens
  title: '[huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)'
- sourceId: ollamacom
  sourceType: web
  sourcePath: https://ollama.com/
  title: '[Ollama](https://ollama.com/)'
- sourceId: ollamacom
  sourceType: web
  sourcePath: https://ollama.com/library
  title: '[Ollama library](https://ollama.com/library)'
- sourceId: docsvllmai
  sourceType: web
  sourcePath: https://docs.vllm.ai/
  title: '[vLLM](https://docs.vllm.ai/)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/sgl-project/sglang
  title: '[SGLang](https://github.com/sgl-project/sglang)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/ggml-org/llama.cpp
  title: '[llama.cpp](https://github.com/ggml-org/llama.cpp)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/ggml-org/llama.cpp/blob/master/docs/function-calling.md
  title: '[llama.cpp function calling docs](https://github.com/ggml-org/llama.cpp/blob/master/docs/function-ca'
- sourceId: huggingfaceco
  sourceType: web
  sourcePath: https://huggingface.co/models?library=gguf
  title: '[Hugging Face](https://huggingface.co/models?library=gguf)'
- sourceId: lmstudioai
  sourceType: web
  sourcePath: https://lmstudio.ai/
  title: '[LM Studio](https://lmstudio.ai/)'
- sourceId: docslitellmai
  sourceType: web
  sourcePath: https://docs.litellm.ai/
  title: '[LiteLLM](https://docs.litellm.ai/)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/BlockRunAI/ClawRouter
  title: '[ClawRouter](https://github.com/BlockRunAI/ClawRouter)'
- sourceId: firecrawldev
  sourceType: web
  sourcePath: https://firecrawl.dev/
  title: '[Firecrawl cloud API](https://firecrawl.dev/)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/firecrawl/firecrawl/blob/main/SELF_HOST.md
  title: '[SELF_HOST.md](https://github.com/firecrawl/firecrawl/blob/main/SELF_HOST.md)'
- sourceId: cloudcode-pagoogleap
  sourceType: web
  sourcePath: https://cloudcode-pa.googleapis.com/v1internal:generateContent
  title: cloudcode-pa.googleapis.com
- sourceId: portalqwenai
  sourceType: web
  sourcePath: https://portal.qwen.ai/v1
  title: portal.qwen.ai
- sourceId: '17229192111434'
  sourceType: web
  sourcePath: http://172.29.192.1:11434/v1
  title: 172.29.192.1:11434
- sourceId: wsl-host11434
  sourceType: web
  sourcePath: http://$WSL_HOST:11434/v1/models
  title: $WSL_HOST:11434
- sourceId: hostname
  sourceType: web
  sourcePath: http://$(hostname
  title: $(hostname
- sourceId: '17229192111434'
  sourceType: web
  sourcePath: http://172.29.192.1:11434/v1/models
  title: 172.29.192.1:11434
- sourceId: apitogetherxyz
  sourceType: web
  sourcePath: https://api.together.xyz/v1
  title: api.together.xyz
- sourceId: gpu-serverinternalco
  sourceType: web
  sourcePath: https://gpu-server.internal.corp/v1
  title: gpu-server.internal.corp
- sourceId: proxyexamplecom
  sourceType: web
  sourcePath: https://proxy.example.com/anthropic
  title: proxy.example.com
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/firecrawl/firecrawlcd
  title: github.com
claims:
- id: pkce-authorization-code-flow-against-accountsgooglecom
  text: PKCE Authorization Code flow against accounts.google.com
  status: supported
  confidence: null
- id: browser-callback-at-http1270018085oauth2callback-wi
  text: Browser callback at http://127.0.0.1:8085/oauth2callback (with ephemeral-port
    fallback if busy)
  status: supported
  confidence: null
- id: tokens-stored-at-hermesauthgoogle-oauthjson-chmod-060
  text: Tokens stored at ~/.hermes/auth/google_oauth.json (chmod 0600, atomic write,
    cross-process fcntl lock)
  status: supported
  confidence: null
- id: automatic-refresh-60-s-before-expiry
  text: Automatic refresh 60 s before expiry
  status: supported
  confidence: null
- id: headless-environments-ssh-hermes-headless1-paste-mode
  text: "Headless environments (SSH, HERMES_HEADLESS=1) \u2192 paste-mode fallback"
  status: supported
  confidence: null
- id: inflight-refresh-deduplication-two-concurrent-requests-won
  text: "Inflight refresh deduplication \u2014 two concurrent requests won't double-refresh"
  status: supported
  confidence: null
- id: invalid-grant-revoked-refresh-credential-file-wiped-use
  text: "invalid_grant (revoked refresh) \u2192 credential file wiped, user prompted\
    \ to re-login"
  status: supported
  confidence: null
- id: traffic-goes-to-httpscloudcode-pagoogleapiscomv1intern
  text: Traffic goes to https://cloudcode-pa.googleapis.com/v1internal:generateContent
  status: supported
  confidence: null
- id: request-body-wrapped-project-model-user-prompt-id-reques
  text: Request body wrapped {project, model, user_prompt_id, request}
  status: supported
  confidence: null
- id: openai-shaped-messages-tools-tool-choice-are-translate
  text: OpenAI-shaped messages[], tools[], tool_choice are translated to Gemini's
    native
  status: supported
  confidence: null
- id: responses-translated-back-to-openai-shape-so-the-rest-of-her
  text: Responses translated back to OpenAI shape so the rest of Hermes works unchanged
  status: supported
  confidence: null
- id: provider-claude-and---provider-claude-code-also-work-as-shor
  text: provider claude and --provider claude-code also work as shorthand for --provider
    anthropic.
  status: supported
  confidence: null
- id: port-8000
  text: port 8000 \
  status: supported
  confidence: null
- id: max-model-len-65536
  text: max-model-len 65536 \
  status: supported
  confidence: null
- id: tensor-parallel-size-2
  text: tensor-parallel-size 2 \
  status: supported
  confidence: null
- id: enable-auto-tool-choice
  text: enable-auto-tool-choice \
  status: supported
  confidence: null
- id: tool-call-parser-hermes
  text: tool-call-parser hermes
  status: supported
  confidence: null
- id: model-meta-llamallama-31-70b-instruct
  text: model meta-llama/Llama-3.1-70B-Instruct \
  status: supported
  confidence: null
- id: port-30000
  text: port 30000 \
  status: supported
  confidence: null
- id: context-length-65536
  text: context-length 65536 \
  status: supported
  confidence: null
- id: tool-call-parser-qwen
  text: tool-call-parser qwen
  status: supported
  confidence: null
- id: jinja--fa
  text: jinja -fa \
  status: supported
  confidence: null
- id: m-modelsqwen25-coder-32b-instruct-q4-k-mgguf
  text: m models/qwen2.5-coder-32b-instruct-Q4_K_M.gguf \
  status: supported
  confidence: null
- id: port-8080---host-0000
  text: port 8080 --host 0.0.0.0
  status: supported
  confidence: null
- id: jinja-is-required-for-tool-calling
  text: jinja is required for tool calling
  status: supported
  confidence: null
- id: model-name-best
  text: 'model_name: "best"'
  status: supported
  confidence: null
- id: model-name-best
  text: 'model_name: "best"'
  status: supported
  confidence: null
- id: name-my-local-llm
  text: 'name: "My Local LLM"'
  status: supported
  confidence: null
- id: youre-using-ollama-with-a-custom-num-ctx-thats-lower-than
  text: You're using Ollama with a custom num_ctx that's lower than the model's maximum
  status: supported
  confidence: null
- id: you-want-to-limit-context-below-the-models-maximum-eg-8
  text: You want to limit context below the model's maximum (e.g., 8k on a 128k model
    to save VRAM)
  status: supported
  confidence: null
- id: youre-running-behind-a-proxy-that-doesnt-expose-v1models
  text: You're running behind a proxy that doesn't expose /v1/models
  status: supported
  confidence: null
- id: name-local
  text: 'name: local'
  status: supported
  confidence: null
- id: name-work
  text: 'name: work'
  status: supported
  confidence: null
- id: name-anthropic-proxy
  text: 'name: anthropic-proxy'
  status: supported
  confidence: null
- id: configuration-general-configuration-directory-structure
  text: "Configuration \u2014 General configuration (directory structure, config precedence,\
    \ terminal backends, memory, compression, and more)"
  status: supported
  confidence: null
- id: environment-variables-complete-reference-of-all-environmen
  text: "Environment Variables \u2014 Complete reference of all environment variables"
  status: supported
  confidence: null
- id: google-gemini-via-oauth-google-gemini-cli
  text: Google Gemini via OAuth (google-gemini-cli)
  status: supported
  confidence: null
- id: two-commands-for-model-management
  text: Two Commands for Model Management
  status: supported
  confidence: null
- id: anthropic-native
  text: Anthropic (Native)
  status: supported
  confidence: null
- id: github-copilot
  text: GitHub Copilot
  status: supported
  confidence: null
- id: first-class-chinese-ai-providers
  text: First-Class Chinese AI Providers
  status: supported
  confidence: null
- id: xai-grok-responses-api-prompt-caching
  text: "xAI (Grok) \u2014 Responses API + Prompt Caching"
  status: supported
  confidence: null
- id: ollama-cloud-managed-ollama-models-oauth-api-key
  text: "Ollama Cloud \u2014 Managed Ollama Models, OAuth + API Key"
  status: supported
  confidence: null
- id: aws-bedrock
  text: AWS Bedrock
  status: supported
  confidence: null
- id: qwen-portal-oauth
  text: Qwen Portal (OAuth)
  status: supported
  confidence: null
- id: nvidia-nim
  text: NVIDIA NIM
  status: supported
  confidence: null
- id: hugging-face-inference-providers
  text: Hugging Face Inference Providers
  status: supported
  confidence: null
- id: custom-self-hosted-llm-providerscustom--self-hosted-ll
  text: '[Custom & Self-Hosted LLM Providers](#custom--self-hosted-llm-providers)[](#general-setup)[](#switching-models-with-model)[](#ollama--local-models-zero-config)[](#vllm--high-performance-gpu-inference)[](#sglang--fast-serving-with-radixattention)[](#llamacpp--llama-server--cpu--metal-inference)[](#lm-studio--desktop-app-with-local-models)[](#wsl2-networking-windows-users)[](#troubleshooting-local-models)[](#litellm-proxy--multi-provider-gateway)[](#clawrouter--cost-optimized-routing)[](#other-compatible-providers)[](#context-length-detection)[](#named-custom-providers)[](#choosing-the-right-setup)'
  status: supported
  confidence: null
- id: general-setup
  text: General Setup
  status: supported
  confidence: null
- id: switching-models-with-model
  text: Switching Models with /model
  status: supported
  confidence: null
- id: ollama-local-models-zero-config
  text: "Ollama \u2014 Local Models, Zero Config"
  status: supported
  confidence: null
- id: vllm-high-performance-gpu-inference
  text: "vLLM \u2014 High-Performance GPU Inference"
  status: supported
  confidence: null
- id: sglang-fast-serving-with-radixattention
  text: "SGLang \u2014 Fast Serving with RadixAttention"
  status: supported
  confidence: null
- id: llamacpp-llama-server-cpu-metal-inference
  text: "llama.cpp / llama-server \u2014 CPU & Metal Inference"
  status: supported
  confidence: null
- id: lm-studio-desktop-app-with-local-models
  text: "LM Studio \u2014 Desktop App with Local Models"
  status: supported
  confidence: null
- id: wsl2-networking-windows-users
  text: WSL2 Networking (Windows Users)
  status: supported
  confidence: null
- id: troubleshooting-local-models
  text: Troubleshooting Local Models
  status: supported
  confidence: null
- id: litellm-proxy-multi-provider-gateway
  text: "LiteLLM Proxy \u2014 Multi-Provider Gateway"
  status: supported
  confidence: null
- id: clawrouter-cost-optimized-routing
  text: "ClawRouter \u2014 Cost-Optimized Routing"
  status: supported
  confidence: null
- id: other-compatible-providers
  text: Other Compatible Providers
  status: supported
  confidence: null
- id: context-length-detection
  text: Context Length Detection
  status: supported
  confidence: null
- id: named-custom-providers
  text: Named Custom Providers
  status: supported
  confidence: null
- id: choosing-the-right-setup
  text: Choosing the Right Setup
  status: supported
  confidence: null
- id: optional-api-keysoptional-api-keysself-hosting-fire
  text: '[Optional API Keys](#optional-api-keys)[](#self-hosting-firecrawl)'
  status: supported
  confidence: null
- id: self-hosting-firecrawl
  text: Self-Hosting Firecrawl
  status: supported
  confidence: null
- id: openrouter-provider-routingopenrouter-provider-routing
  text: '[OpenRouter Provider Routing](#openrouter-provider-routing)'
  status: supported
  confidence: null
- id: fallback-modelfallback-model
  text: '[Fallback Model](#fallback-model)'
  status: supported
  confidence: null
- id: see-alsosee-also
  text: '[See Also](#see-also)'
  status: supported
  confidence: null
---

On this page

This page covers setting up inference providers for Hermes Agent — from cloud APIs like OpenRouter and Anthropic, to self-hosted endpoints like Ollama and vLLM, to advanced routing and fallback configurations. You need at least one provider configured to use Hermes.

## Inference Providers[​](#inference-providers)

You need at least one way to connect to an LLM. Use hermes model to switch providers and models interactively, or configure directly:

********************************************************************************************
Model key alias

In the model: config section, you can use either default: or model: as the key name for your model ID. Both model: { default: my-model } and model: { model: my-model } work identically.

### Google Gemini via OAuth (google-gemini-cli)[​](#google-gemini-via-oauth-google-gemini-cli)

The google-gemini-cli provider uses Google's Cloud Code Assist backend — the
same API that Google's own gemini-cli tool uses. This supports both the
**free tier** (generous daily quota for personal accounts) and **paid tiers**
(Standard/Enterprise via a GCP project).

**Quick start:**

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# → pick "Google Gemini (OAuth)"
# → see policy warning, confirm
# → browser opens to accounts.google.com, sign in
# → done — Hermes auto-provisions your free tier on first request

```

Hermes ships Google's **public** gemini-cli desktop OAuth client by default —
the same credentials Google includes in their open-source gemini-cli. Desktop
OAuth clients are not confidential (PKCE provides the security). You do not
need to install gemini-cli or register your own GCP OAuth client.

**How auth works:**

- PKCE Authorization Code flow against accounts.google.com

- Browser callback at http://127.0.0.1:8085/oauth2callback (with ephemeral-port fallback if busy)

- Tokens stored at ~/.hermes/auth/google_oauth.json (chmod 0600, atomic write, cross-process fcntl lock)

- Automatic refresh 60 s before expiry

- Headless environments (SSH, HERMES_HEADLESS=1) → paste-mode fallback

- Inflight refresh deduplication — two concurrent requests won't double-refresh

- invalid_grant (revoked refresh) → credential file wiped, user prompted to re-login

**How inference works:**

- Traffic goes to https://cloudcode-pa.googleapis.com/v1internal:generateContent
(or :streamGenerateContent?alt=sse for streaming), NOT the paid v1beta/openai endpoint

- Request body wrapped {project, model, user_prompt_id, request}

- OpenAI-shaped messages[], tools[], tool_choice are translated to Gemini's native
contents[], tools[].functionDeclarations, toolConfig shape

- Responses translated back to OpenAI shape so the rest of Hermes works unchanged

**Tiers & project IDs:**

Free tier auto-provisions a Google-managed project on first use. No GCP setup required.

**Quota monitoring:**

```prism-code text codeBlock_bY9V thin-scrollbar
/gquota

```

Shows remaining Code Assist quota per model with progress bars:

```prism-code text codeBlock_bY9V thin-scrollbar
Gemini Code Assist quota (project: 123-abc)

 gemini-2.5-pro ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░ 85%
 gemini-2.5-flash [input] ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░ 92%

```

Policy risk

Google considers using the Gemini CLI OAuth client with third-party software a
policy violation. Some users have reported account restrictions. For the lowest-risk
experience, use your own API key via the gemini provider instead. Hermes shows
an upfront warning and requires explicit confirmation before OAuth begins.

**Custom OAuth client (optional):**

If you'd rather register your own Google OAuth client — e.g., to keep quota
and consent scoped to your own GCP project — set:

```prism-code bash codeBlock_bY9V thin-scrollbar
HERMES_GEMINI_CLIENT_ID=your-client.apps.googleusercontent.com
HERMES_GEMINI_CLIENT_SECRET=... # optional for Desktop clients

```

Register a **Desktop app** OAuth client at
[console.cloud.google.com/apis/credentials](https://console.cloud.google.com/apis/credentials)
with the Generative Language API enabled.

Codex Note

The OpenAI Codex provider authenticates via device code (open a URL, enter a code). Hermes stores the resulting credentials in its own auth store under ~/.hermes/auth.json and can import existing Codex CLI credentials from ~/.codex/auth.json when present. No Codex CLI installation is required.

warning

Even when using Nous Portal, Codex, or a custom endpoint, some tools (vision, web summarization, MoA) use a separate "auxiliary" model — by default Gemini Flash via OpenRouter. An OPENROUTER_API_KEY enables these tools automatically. You can also configure which model and provider these tools use — see [Auxiliary Models](/docs/user-guide/configuration#auxiliary-models).

Nous Tool Gateway

Paid Nous Portal subscribers also get access to the **[Tool Gateway](/docs/user-guide/features/tool-gateway)** — web search, image generation, TTS, and browser automation routed through your subscription. No extra API keys needed. It's offered automatically during hermes model setup, or enable it later with hermes tools.

### Two Commands for Model Management[​](#two-commands-for-model-management)

Hermes has **two** model commands that serve different purposes:

************

If you're trying to switch to a provider you haven't set up yet (e.g. you only have OpenRouter configured and want to use Anthropic), you need hermes model, not /model. Exit your session first (Ctrl+C or /quit), run hermes model, complete the provider setup, then start a new session.

### Anthropic (Native)[​](#anthropic-native)

Use Claude models directly through the Anthropic API — no OpenRouter proxy needed. Supports three auth methods:

```prism-code bash codeBlock_bY9V thin-scrollbar
# With an API key (pay-per-token)
export ANTHROPIC_API_KEY=***
hermes chat --provider anthropic --model claude-sonnet-4-6

# Preferred: authenticate through `hermes model`
# Hermes will use Claude Code's credential store directly when available
hermes model

# Manual override with a setup-token (fallback / legacy)
export ANTHROPIC_TOKEN=*** # setup-token or manual OAuth token
hermes chat --provider anthropic

# Auto-detect Claude Code credentials (if you already use Claude Code)
hermes chat --provider anthropic # reads Claude Code credential files automatically

```

When you choose Anthropic OAuth through hermes model, Hermes prefers Claude Code's own credential store over copying the token into ~/.hermes/.env. That keeps refreshable Claude credentials refreshable.

Or set it permanently:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "anthropic"
 default: "claude-sonnet-4-6"

```

Aliases

--provider claude and --provider claude-code also work as shorthand for --provider anthropic.

### GitHub Copilot[​](#github-copilot)

Hermes supports GitHub Copilot as a first-class provider with two modes:

**copilot — Direct Copilot API** (recommended). Uses your GitHub Copilot subscription to access GPT-5.x, Claude, Gemini, and other models through the Copilot API.

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes chat --provider copilot --model gpt-5.4

```

**Authentication options** (checked in this order):

1. COPILOT_GITHUB_TOKEN environment variable

2. GH_TOKEN environment variable

3. GITHUB_TOKEN environment variable

4. gh auth token CLI fallback

If no token is found, hermes model offers an **OAuth device code login** — the same flow used by the Copilot CLI and opencode.

Token types

The Copilot API does **not** support classic Personal Access Tokens (ghp_*). Supported token types:
****

If your gh auth token returns a ghp_* token, use hermes model to authenticate via OAuth instead.

Copilot auth behavior in Hermes

Hermes sends a supported GitHub token (gho_*, github_pat_*, or ghu_*) directly to api.githubcopilot.com and includes Copilot-specific headers (Editor-Version, Copilot-Integration-Id, Openai-Intent, x-initiator).

On HTTP 401, Hermes now performs a one-shot credential recovery before fallback:

1. Re-resolve token via the normal priority chain (COPILOT_GITHUB_TOKEN → GH_TOKEN → GITHUB_TOKEN → gh auth token)

2. Rebuild the shared OpenAI client with refreshed headers

3. Retry the request once

Some older community proxies use api.github.com/copilot_internal/v2/token exchange flows. That endpoint can be unavailable for some account types (returns 404). Hermes therefore keeps direct-token auth as the primary path and relies on runtime credential refresh + retry for robustness.

**API routing**: GPT-5+ models (except gpt-5-mini) automatically use the Responses API. All other models (GPT-4o, Claude, Gemini, etc.) use Chat Completions. Models are auto-detected from the live Copilot catalog.

**copilot-acp — Copilot ACP agent backend**. Spawns the local Copilot CLI as a subprocess:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes chat --provider copilot-acp --model copilot-acp
# Requires the GitHub Copilot CLI in PATH and an existing `copilot login` session

```

**Permanent config:**

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "copilot"
 default: "gpt-5.4"

```

### First-Class Chinese AI Providers[​](#first-class-chinese-ai-providers)

These providers have built-in support with dedicated provider IDs. Set the API key and use --provider to select:

```prism-code bash codeBlock_bY9V thin-scrollbar
# z.ai / ZhipuAI GLM
hermes chat --provider zai --model glm-5
# Requires: GLM_API_KEY in ~/.hermes/.env

# Kimi / Moonshot AI (international: api.moonshot.ai)
hermes chat --provider kimi-coding --model kimi-for-coding
# Requires: KIMI_API_KEY in ~/.hermes/.env

# Kimi / Moonshot AI (China: api.moonshot.cn)
hermes chat --provider kimi-coding-cn --model kimi-k2.5
# Requires: KIMI_CN_API_KEY in ~/.hermes/.env

# MiniMax (global endpoint)
hermes chat --provider minimax --model MiniMax-M2.7
# Requires: MINIMAX_API_KEY in ~/.hermes/.env

# MiniMax (China endpoint)
hermes chat --provider minimax-cn --model MiniMax-M2.7
# Requires: MINIMAX_CN_API_KEY in ~/.hermes/.env

# Alibaba Cloud / DashScope (Qwen models)
hermes chat --provider alibaba --model qwen3.5-plus
# Requires: DASHSCOPE_API_KEY in ~/.hermes/.env

# Xiaomi MiMo
hermes chat --provider xiaomi --model mimo-v2-pro
# Requires: XIAOMI_API_KEY in ~/.hermes/.env

# Arcee AI (Trinity models)
hermes chat --provider arcee --model trinity-large-thinking
# Requires: ARCEEAI_API_KEY in ~/.hermes/.env

```

Or set the provider permanently in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "zai" # or: kimi-coding, kimi-coding-cn, minimax, minimax-cn, alibaba, xiaomi, arcee
 default: "glm-5"

```

Base URLs can be overridden with GLM_BASE_URL, KIMI_BASE_URL, MINIMAX_BASE_URL, MINIMAX_CN_BASE_URL, DASHSCOPE_BASE_URL, or XIAOMI_BASE_URL environment variables.

Z.AI Endpoint Auto-Detection

When using the Z.AI / GLM provider, Hermes automatically probes multiple endpoints (global, China, coding variants) to find one that accepts your API key. You don't need to set GLM_BASE_URL manually — the working endpoint is detected and cached automatically.

### xAI (Grok) — Responses API + Prompt Caching[​](#xai-grok--responses-api--prompt-caching)

xAI is wired through the Responses API (codex_responses transport) for automatic reasoning support on Grok 4 models — no reasoning_effort parameter needed, the server reasons by default. Set XAI_API_KEY in ~/.hermes/.env and pick xAI in hermes model, or drop grok as a shortcut into /model grok-4-1-fast-reasoning.

When using xAI as a provider (any base URL containing x.ai), Hermes automatically enables prompt caching by sending the x-grok-conv-id header with every API request. This routes requests to the same server within a conversation session, allowing xAI's infrastructure to reuse cached system prompts and conversation history.

No configuration is needed — caching activates automatically when an xAI endpoint is detected and a session ID is available. This reduces latency and cost for multi-turn conversations.

xAI also ships a dedicated TTS endpoint (/v1/tts). Select **xAI TTS** in hermes tools → Voice & TTS, or see the [Voice & TTS](/docs/user-guide/features/tts#text-to-speech) page for config.

### Ollama Cloud — Managed Ollama Models, OAuth + API Key[​](#ollama-cloud--managed-ollama-models-oauth--api-key)

[Ollama Cloud](https://ollama.com/cloud) hosts the same open-weight catalog as local Ollama but without the GPU requirement. Pick it in hermes model as **Ollama Cloud**, paste your API key from [ollama.com/settings/keys](https://ollama.com/settings/keys), and Hermes auto-discovers the available models.

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# → pick "Ollama Cloud"
# → paste your OLLAMA_API_KEY
# → select from discovered models (gpt-oss:120b, glm-4.6:cloud, qwen3-coder:480b-cloud, etc.)

```

Or config.yaml directly:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "ollama-cloud"
 default: "gpt-oss:120b"

```

The model catalog is fetched dynamically from ollama.com/v1/models and cached for one hour. model:tag notation (e.g. qwen3-coder:480b-cloud) is preserved through normalization — don't use dashes.

Ollama Cloud vs local Ollama

Both speak the same OpenAI-compatible API. Cloud is a first-class provider (--provider ollama-cloud, OLLAMA_API_KEY); local Ollama is reached via the Custom Endpoint flow (base URL http://localhost:11434/v1, no key). Use cloud for large models you can't run locally; use local for privacy or offline work.

### AWS Bedrock[​](#aws-bedrock)

Anthropic Claude, Amazon Nova, DeepSeek v3.2, Meta Llama 4, and other models via AWS Bedrock. Uses the AWS SDK (boto3) credential chain — no API key, just standard AWS auth.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Simplest — named profile in ~/.aws/credentials
hermes chat --provider bedrock --model us.anthropic.claude-sonnet-4-6

# Or with explicit env vars
AWS_PROFILE=myprofile AWS_REGION=us-east-1 hermes chat --provider bedrock --model us.anthropic.claude-sonnet-4-6

```

Or permanently in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "bedrock"
 default: "us.anthropic.claude-sonnet-4-6"
bedrock:
 region: "us-east-1" # or set AWS_REGION
 # profile: "myprofile" # or set AWS_PROFILE
 # discovery: true # auto-discover region from IAM
 # guardrail: # optional Bedrock Guardrails
 # id: "your-guardrail-id"
 # version: "DRAFT"

```

Authentication uses the standard boto3 chain: explicit AWS_ACCESS_KEY_ID/AWS_SECRET_ACCESS_KEY, AWS_PROFILE from ~/.aws/credentials, IAM role on EC2/ECS/Lambda, IMDS, or SSO. No env var is required if you're already authenticated with the AWS CLI.

Bedrock uses the **Converse API** under the hood — requests are translated to Bedrock's model-agnostic shape, so the same config works for Claude, Nova, DeepSeek, and Llama models. Set BEDROCK_BASE_URL only if you're calling a non-default regional endpoint.

See the [AWS Bedrock guide](/docs/guides/aws-bedrock) for a walkthrough of IAM setup, region selection, and cross-region inference.

### Qwen Portal (OAuth)[​](#qwen-portal-oauth)

Alibaba's Qwen Portal with browser-based OAuth login. Pick **Qwen OAuth (Portal)** in hermes model, sign in through the browser, and Hermes persists the refresh token.

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# → pick "Qwen OAuth (Portal)"
# → browser opens; sign in with your Alibaba account
# → confirm — credentials are saved to ~/.hermes/auth.json

hermes chat # uses portal.qwen.ai/v1 endpoint

```

Or configure config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "qwen-oauth"
 default: "qwen3-coder-plus"

```

Set HERMES_QWEN_BASE_URL only if the portal endpoint relocates (default: https://portal.qwen.ai/v1).

Qwen OAuth vs DashScope (Alibaba)

qwen-oauth uses the consumer-facing Qwen Portal with OAuth login — ideal for individual users. The alibaba provider uses DashScope's enterprise API with a DASHSCOPE_API_KEY — ideal for programmatic / production workloads. Both route to Qwen-family models but live at different endpoints.

### NVIDIA NIM[​](#nvidia-nim)

Nemotron and other open source models via [build.nvidia.com](https://build.nvidia.com) (free API key) or a local NIM endpoint.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Cloud (build.nvidia.com)
hermes chat --provider nvidia --model nvidia/nemotron-3-super-120b-a12b
# Requires: NVIDIA_API_KEY in ~/.hermes/.env

# Local NIM endpoint — override base URL
NVIDIA_BASE_URL=http://localhost:8000/v1 hermes chat --provider nvidia --model nvidia/nemotron-3-super-120b-a12b

```

Or set it permanently in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "nvidia"
 default: "nvidia/nemotron-3-super-120b-a12b"

```

Local NIM

For on-prem deployments (DGX Spark, local GPU), set NVIDIA_BASE_URL=http://localhost:8000/v1. NIM exposes the same OpenAI-compatible chat completions API as build.nvidia.com, so switching between cloud and local is a one-line env-var change.

### Hugging Face Inference Providers[​](#hugging-face-inference-providers)

[Hugging Face Inference Providers](https://huggingface.co/docs/inference-providers) routes to 20+ open models through a unified OpenAI-compatible endpoint (router.huggingface.co/v1). Requests are automatically routed to the fastest available backend (Groq, Together, SambaNova, etc.) with automatic failover.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Use any available model
hermes chat --provider huggingface --model Qwen/Qwen3-235B-A22B-Thinking-2507
# Requires: HF_TOKEN in ~/.hermes/.env

# Short alias
hermes chat --provider hf --model deepseek-ai/DeepSeek-V3.2

```

Or set it permanently in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 provider: "huggingface"
 default: "Qwen/Qwen3-235B-A22B-Thinking-2507"

```

Get your token at [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens) — make sure to enable the "Make calls to Inference Providers" permission. Free tier included ($0.10/month credit, no markup on provider rates).

You can append routing suffixes to model names: :fastest (default), :cheapest, or :provider_name to force a specific backend.

The base URL can be overridden with HF_BASE_URL.

## Custom & Self-Hosted LLM Providers[​](#custom--self-hosted-llm-providers)

Hermes Agent works with **any OpenAI-compatible API endpoint**. If a server implements /v1/chat/completions, you can point Hermes at it. This means you can use local models, GPU inference servers, multi-provider routers, or any third-party API.

### General Setup[​](#general-setup)

Three ways to configure a custom endpoint:

**Interactive setup (recommended):**

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# Select "Custom endpoint (self-hosted / VLLM / etc.)"
# Enter: API base URL, API key, Model name

```

**Manual config (config.yaml):**

```prism-code yaml codeBlock_bY9V thin-scrollbar
# In ~/.hermes/config.yaml
model:
 default: your-model-name
 provider: custom
 base_url: http://localhost:8000/v1
 api_key: your-key-or-leave-empty-for-local

```

Legacy env vars

OPENAI_BASE_URL and LLM_MODEL in .env are **removed**. Neither is read by any part of Hermes — config.yaml is the single source of truth for model and endpoint configuration. If you have stale entries in your .env, they are automatically cleared on the next hermes setup or config migration. Use hermes model or edit config.yaml directly.

Both approaches persist to config.yaml, which is the source of truth for model, provider, and base URL.

### Switching Models with /model[​](#switching-models-with-model)

hermes model vs /model

**hermes model** (run from your terminal, outside any chat session) is the **full provider setup wizard**. Use it to add new providers, run OAuth flows, enter API keys, and configure custom endpoints.

**/model** (typed inside an active Hermes chat session) can only **switch between providers and models you've already set up**. It cannot add new providers, run OAuth, or prompt for API keys. If you've only configured one provider (e.g. OpenRouter), /model will only show models for that provider.

**To add a new provider:** Exit your session (Ctrl+C or /quit), run hermes model, set up the new provider, then start a new session.

Once you have at least one custom endpoint configured, you can switch models mid-session:

```prism-code text codeBlock_bY9V thin-scrollbar
/model custom:qwen-2.5 # Switch to a model on your custom endpoint
/model custom # Auto-detect the model from the endpoint
/model openrouter:claude-sonnet-4 # Switch back to a cloud provider

```

If you have **named custom providers** configured (see below), use the triple syntax:

```prism-code text codeBlock_bY9V thin-scrollbar
/model custom:local:qwen-2.5 # Use the "local" custom provider with model qwen-2.5
/model custom:work:llama3 # Use the "work" custom provider with llama3

```

When switching providers, Hermes persists the base URL and provider to config so the change survives restarts. When switching away from a custom endpoint to a built-in provider, the stale base URL is automatically cleared.

tip

/model custom (bare, no model name) queries your endpoint's /models API and auto-selects the model if exactly one is loaded. Useful for local servers running a single model.

Everything below follows this same pattern — just change the URL, key, and model name.

---

### Ollama — Local Models, Zero Config[​](#ollama--local-models-zero-config)

[Ollama](https://ollama.com/) runs open-weight models locally with one command. Best for: quick local experimentation, privacy-sensitive work, offline use. Supports tool calling via the OpenAI-compatible API.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Install and run a model
ollama pull qwen2.5-coder:32b
ollama serve # Starts on port 11434

```

Then configure Hermes:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# Select "Custom endpoint (self-hosted / VLLM / etc.)"
# Enter URL: http://localhost:11434/v1
# Skip API key (Ollama doesn't need one)
# Enter model name (e.g. qwen2.5-coder:32b)

```

Or configure config.yaml directly:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 default: qwen2.5-coder:32b
 provider: custom
 base_url: http://localhost:11434/v1
 context_length: 32768 # See warning below

```

Ollama defaults to very low context lengths

Ollama does **not** use your model's full context window by default. Depending on your VRAM, the default is:
****

For agent use with tools, **you need at least 16k–32k context**. At 4k, the system prompt + tool schemas alone can fill the window, leaving no room for conversation.

**How to increase it** (pick one):

```prism-code bash codeBlock_bY9V thin-scrollbar
# Option 1: Set server-wide via environment variable (recommended)
OLLAMA_CONTEXT_LENGTH=32768 ollama serve

# Option 2: For systemd-managed Ollama
sudo systemctl edit ollama.service
# Add: Environment="OLLAMA_CONTEXT_LENGTH=32768"
# Then: sudo systemctl daemon-reload && sudo systemctl restart ollama

# Option 3: Bake it into a custom model (persistent per-model)
echo -e "FROM qwen2.5-coder:32b\nPARAMETER num_ctx 32768" > Modelfile
ollama create qwen2.5-coder-32k -f Modelfile

```

**You cannot set context length through the OpenAI-compatible API** (/v1/chat/completions). It must be configured server-side or via a Modelfile. This is the #1 source of confusion when integrating Ollama with tools like Hermes.

**Verify your context is set correctly:**

```prism-code bash codeBlock_bY9V thin-scrollbar
ollama ps
# Look at the CONTEXT column — it should show your configured value

```

tip

List available models with ollama list. Pull any model from the [Ollama library](https://ollama.com/library) with ollama pull <model>. Ollama handles GPU offloading automatically — no configuration needed for most setups.

---

### vLLM — High-Performance GPU Inference[​](#vllm--high-performance-gpu-inference)

[vLLM](https://docs.vllm.ai/) is the standard for production LLM serving. Best for: maximum throughput on GPU hardware, serving large models, continuous batching.

```prism-code bash codeBlock_bY9V thin-scrollbar
pip install vllm
vllm serve meta-llama/Llama-3.1-70B-Instruct \
 --port 8000 \
 --max-model-len 65536 \
 --tensor-parallel-size 2 \
 --enable-auto-tool-choice \
 --tool-call-parser hermes

```

Then configure Hermes:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# Select "Custom endpoint (self-hosted / VLLM / etc.)"
# Enter URL: http://localhost:8000/v1
# Skip API key (or enter one if you configured vLLM with --api-key)
# Enter model name: meta-llama/Llama-3.1-70B-Instruct

```

**Context length:** vLLM reads the model's max_position_embeddings by default. If that exceeds your GPU memory, it errors and asks you to set --max-model-len lower. You can also use --max-model-len auto to automatically find the maximum that fits. Set --gpu-memory-utilization 0.95 (default 0.9) to squeeze more context into VRAM.

**Tool calling requires explicit flags:**

Supported parsers: hermes (Qwen 2.5, Hermes 2/3), llama3_json (Llama 3.x), mistral, deepseek_v3, deepseek_v31, xlam, pythonic. Without these flags, tool calls won't work — the model will output tool calls as text.

tip

vLLM supports human-readable sizes: --max-model-len 64k (lowercase k = 1000, uppercase K = 1024).

---

### SGLang — Fast Serving with RadixAttention[​](#sglang--fast-serving-with-radixattention)

[SGLang](https://github.com/sgl-project/sglang) is an alternative to vLLM with RadixAttention for KV cache reuse. Best for: multi-turn conversations (prefix caching), constrained decoding, structured output.

```prism-code bash codeBlock_bY9V thin-scrollbar
pip install "sglang[all]"
python -m sglang.launch_server \
 --model meta-llama/Llama-3.1-70B-Instruct \
 --port 30000 \
 --context-length 65536 \
 --tp 2 \
 --tool-call-parser qwen

```

Then configure Hermes:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# Select "Custom endpoint (self-hosted / VLLM / etc.)"
# Enter URL: http://localhost:30000/v1
# Enter model name: meta-llama/Llama-3.1-70B-Instruct

```

**Context length:** SGLang reads from the model's config by default. Use --context-length to override. If you need to exceed the model's declared maximum, set SGLANG_ALLOW_OVERWRITE_LONGER_CONTEXT_LEN=1.

**Tool calling:** Use --tool-call-parser with the appropriate parser for your model family: qwen (Qwen 2.5), llama3, llama4, deepseekv3, mistral, glm. Without this flag, tool calls come back as plain text.

SGLang defaults to 128 max output tokens

If responses seem truncated, add max_tokens to your requests or set --default-max-tokens on the server. SGLang's default is only 128 tokens per response if not specified in the request.

---

### llama.cpp / llama-server — CPU & Metal Inference[​](#llamacpp--llama-server--cpu--metal-inference)

[llama.cpp](https://github.com/ggml-org/llama.cpp) runs quantized models on CPU, Apple Silicon (Metal), and consumer GPUs. Best for: running models without a datacenter GPU, Mac users, edge deployment.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Build and start llama-server
cmake -B build && cmake --build build --config Release
./build/bin/llama-server \
 --jinja -fa \
 -c 32768 \
 -ngl 99 \
 -m models/qwen2.5-coder-32b-instruct-Q4_K_M.gguf \
 --port 8080 --host 0.0.0.0

```

**Context length (-c):** Recent builds default to 0 which reads the model's training context from the GGUF metadata. For models with 128k+ training context, this can OOM trying to allocate the full KV cache. Set -c explicitly to what you need (32k–64k is a good range for agent use). If using parallel slots (-np), the total context is divided among slots — with -c 32768 -np 4, each slot only gets 8k.

Then configure Hermes to point at it:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# Select "Custom endpoint (self-hosted / VLLM / etc.)"
# Enter URL: http://localhost:8080/v1
# Skip API key (local servers don't need one)
# Enter model name — or leave blank to auto-detect if only one model is loaded

```

This saves the endpoint to config.yaml so it persists across sessions.

--jinja is required for tool calling

Without --jinja, llama-server ignores the tools parameter entirely. The model will try to call tools by writing JSON in its response text, but Hermes won't recognize it as a tool call — you'll see raw JSON like {"name": "web_search", ...} printed as a message instead of an actual search.

Native tool calling support (best performance): Llama 3.x, Qwen 2.5 (including Coder), Hermes 2/3, Mistral, DeepSeek, Functionary. All other models use a generic handler that works but may be less efficient. See the [llama.cpp function calling docs](https://github.com/ggml-org/llama.cpp/blob/master/docs/function-calling.md) for the full list.

You can verify tool support is active by checking http://localhost:8080/props — the chat_template field should be present.

tip

Download GGUF models from [Hugging Face](https://huggingface.co/models?library=gguf). Q4_K_M quantization offers the best balance of quality vs. memory usage.

---

### LM Studio — Desktop App with Local Models[​](#lm-studio--desktop-app-with-local-models)

[LM Studio](https://lmstudio.ai/) is a desktop app for running local models with a GUI. Best for: users who prefer a visual interface, quick model testing, developers on macOS/Windows/Linux.

Start the server from the LM Studio app (Developer tab → Start Server), or use the CLI:

```prism-code bash codeBlock_bY9V thin-scrollbar
lms server start # Starts on port 1234
lms load qwen2.5-coder --context-length 32768

```

Then configure Hermes:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes model
# Select "Custom endpoint (self-hosted / VLLM / etc.)"
# Enter URL: http://localhost:1234/v1
# Skip API key (LM Studio doesn't require one)
# Enter model name

```

Context length often defaults to 2048

LM Studio reads context length from the model's metadata, but many GGUF models report low defaults (2048 or 4096). **Always set context length explicitly** in the LM Studio model settings:

1. Click the gear icon next to the model picker

2. Set "Context Length" to at least 16384 (preferably 32768)

3. Reload the model for the change to take effect

Alternatively, use the CLI: lms load model-name --context-length 32768

To set persistent per-model defaults: My Models tab → gear icon on the model → set context size.

**Tool calling:** Supported since LM Studio 0.3.6. Models with native tool-calling training (Qwen 2.5, Llama 3.x, Mistral, Hermes) are auto-detected and shown with a tool badge. Other models use a generic fallback that may be less reliable.

---

### WSL2 Networking (Windows Users)[​](#wsl2-networking-windows-users)

Since Hermes Agent requires a Unix environment, Windows users run it inside WSL2. If your model server (Ollama, LM Studio, etc.) runs on the **Windows host**, you need to bridge the network gap — WSL2 uses a virtual network adapter with its own subnet, so localhost inside WSL2 refers to the Linux VM, **not** the Windows host.

Both in WSL2? No problem.

If your model server also runs inside WSL2 (common for vLLM, SGLang, and llama-server), localhost works as expected — they share the same network namespace. Skip this section.

#### Option 1: Mirrored Networking Mode (Recommended)[​](#option-1-mirrored-networking-mode-recommended)

Available on **Windows 11 22H2+**, mirrored mode makes localhost work bidirectionally between Windows and WSL2 — the simplest fix.

```prism-code ini codeBlock_bY9V thin-scrollbar

```

```prism-code powershell codeBlock_bY9V thin-scrollbar

```

```prism-code bash codeBlock_bY9V thin-scrollbar

```

1.
Create or edit %USERPROFILE%\.wslconfig (e.g., C:\Users\YourName\.wslconfig):
[wsl2]networkingMode=mirrored

2.
Restart WSL from PowerShell:
wsl --shutdown

3.
Reopen your WSL2 terminal. localhost now reaches Windows services:
curl http://localhost:11434/v1/models # Ollama on Windows — works

Hyper-V Firewall

On some Windows 11 builds, the Hyper-V firewall blocks mirrored connections by default. If localhost still doesn't work after enabling mirrored mode, run this in an **Admin PowerShell**:

```prism-code powershell codeBlock_bY9V thin-scrollbar
Set-NetFirewallHyperVVMSetting -Name '{40E0AC32-46A5-438A-A0B2-2B479E8F2E90}' -DefaultInboundAction Allow

```

#### Option 2: Use the Windows Host IP (Windows 10 / older builds)[​](#option-2-use-the-windows-host-ip-windows-10--older-builds)

If you can't use mirrored mode, find the Windows host IP from inside WSL2 and use that instead of localhost:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Get the Windows host IP (the default gateway of WSL2's virtual network)
ip route show | grep -i default | awk '{ print $3 }'
# Example output: 172.29.192.1

```

Use that IP in your Hermes config:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 default: qwen2.5-coder:32b
 provider: custom
 base_url: http://172.29.192.1:11434/v1 # Windows host IP, not localhost

```

Dynamic helper

The host IP can change on WSL2 restart. You can grab it dynamically in your shell:

```prism-code bash codeBlock_bY9V thin-scrollbar
export WSL_HOST=$(ip route show | grep -i default | awk '{ print $3 }')
echo "Windows host at: $WSL_HOST"
curl http://$WSL_HOST:11434/v1/models # Test Ollama

```

Or use your machine's mDNS name (requires libnss-mdns in WSL2):

```prism-code bash codeBlock_bY9V thin-scrollbar
sudo apt install libnss-mdns
curl http://$(hostname).local:11434/v1/models

```

#### Server Bind Address (Required for NAT Mode)[​](#server-bind-address-required-for-nat-mode)

If you're using **Option 2** (NAT mode with the host IP), the model server on Windows must accept connections from outside 127.0.0.1. By default, most servers only listen on localhost — WSL2 connections in NAT mode come from a different virtual subnet and will be refused. In mirrored mode, localhost maps directly so the default 127.0.0.1 binding works fine.

************************

**Ollama on Windows (detailed):** Ollama runs as a Windows service. To set OLLAMA_HOST:

************
1. Open System Properties → Environment Variables

2. Add a new System variable: OLLAMA_HOST = 0.0.0.0

3. Restart the Ollama service (or reboot)

#### Windows Firewall[​](#windows-firewall)

Windows Firewall treats WSL2 as a separate network (in both NAT and mirrored mode). If connections still fail after the steps above, add a firewall rule for your model server's port:

```prism-code powershell codeBlock_bY9V thin-scrollbar
# Run in Admin PowerShell — replace PORT with your server's port
New-NetFirewallRule -DisplayName "Allow WSL2 to Model Server" -Direction Inbound -Action Allow -Protocol TCP -LocalPort 11434

```

Common ports: Ollama 11434, vLLM 8000, SGLang 30000, llama-server 8080, LM Studio 1234.

#### Quick Verification[​](#quick-verification)

From inside WSL2, test that you can reach your model server:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Replace URL with your server's address and port
curl http://localhost:11434/v1/models # Mirrored mode
curl http://172.29.192.1:11434/v1/models # NAT mode (use your actual host IP)

```

If you get a JSON response listing your models, you're good. Use that same URL as the base_url in your Hermes config.

---

### Troubleshooting Local Models[​](#troubleshooting-local-models)

These issues affect **all** local inference servers when used with Hermes.

#### "Connection refused" from WSL2 to a Windows-hosted model server[​](#connection-refused-from-wsl2-to-a-windows-hosted-model-server)

If you're running Hermes inside WSL2 and your model server on the Windows host, http://localhost:<port> won't work in WSL2's default NAT networking mode. See [WSL2 Networking](#wsl2-networking-windows-users) above for the fix.

#### Tool calls appear as text instead of executing[​](#tool-calls-appear-as-text-instead-of-executing)

The model outputs something like {"name": "web_search", "arguments": {...}} as a message instead of actually calling the tool.

**Cause:** Your server doesn't have tool calling enabled, or the model doesn't support it through the server's tool calling implementation.

********************

#### Model seems to forget context or give incoherent responses[​](#model-seems-to-forget-context-or-give-incoherent-responses)

**Cause:** Context window is too small. When the conversation exceeds the context limit, most servers silently drop older messages. Hermes's system prompt + tool schemas alone can use 4k–8k tokens.

**Diagnosis:**

```prism-code bash codeBlock_bY9V thin-scrollbar
# Check what Hermes thinks the context is
# Look at startup line: "Context limit: X tokens"

# Check your server's actual context
# Ollama: ollama ps (CONTEXT column)
# llama.cpp: curl http://localhost:8080/props | jq '.default_generation_settings.n_ctx'
# vLLM: check --max-model-len in startup args

```

**Fix:** Set context to at least **32,768 tokens** for agent use. See each server's section above for the specific flag.

#### "Context limit: 2048 tokens" at startup[​](#context-limit-2048-tokens-at-startup)

Hermes auto-detects context length from your server's /v1/models endpoint. If the server reports a low value (or doesn't report one at all), Hermes uses the model's declared limit which may be wrong.

**Fix:** Set it explicitly in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 default: your-model
 provider: custom
 base_url: http://localhost:11434/v1
 context_length: 32768

```

#### Responses get cut off mid-sentence[​](#responses-get-cut-off-mid-sentence)

**Possible causes:**

********[](/docs/user-guide/configuration#context-compression)
1. Low output cap (max_tokens) on the server — SGLang defaults to 128 tokens per response. Set --default-max-tokens on the server or configure Hermes with model.max_tokens in config.yaml. Note: max_tokens controls response length only — it is unrelated to how long your conversation history can be (that is context_length).

2. Context exhaustion — The model filled its context window. Increase model.context_length or enable context compression in Hermes.

---

### LiteLLM Proxy — Multi-Provider Gateway[​](#litellm-proxy--multi-provider-gateway)

[LiteLLM](https://docs.litellm.ai/) is an OpenAI-compatible proxy that unifies 100+ LLM providers behind a single API. Best for: switching between providers without config changes, load balancing, fallback chains, budget controls.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Install and start
pip install "litellm[proxy]"
litellm --model anthropic/claude-sonnet-4 --port 4000

# Or with a config file for multiple models:
litellm --config litellm_config.yaml --port 4000

```

Then configure Hermes with hermes model → Custom endpoint → http://localhost:4000/v1.

Example litellm_config.yaml with fallback:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model_list:
 - model_name: "best"
 litellm_params:
 model: anthropic/claude-sonnet-4
 api_key: sk-ant-...
 - model_name: "best"
 litellm_params:
 model: openai/gpt-4o
 api_key: sk-...
router_settings:
 routing_strategy: "latency-based-routing"

```

---

### ClawRouter — Cost-Optimized Routing[​](#clawrouter--cost-optimized-routing)

[ClawRouter](https://github.com/BlockRunAI/ClawRouter) by BlockRunAI is a local routing proxy that auto-selects models based on query complexity. It classifies requests across 14 dimensions and routes to the cheapest model that can handle the task. Payment is via USDC cryptocurrency (no API keys).

```prism-code bash codeBlock_bY9V thin-scrollbar
# Install and start
npx @blockrun/clawrouter # Starts on port 8402

```

Then configure Hermes with hermes model → Custom endpoint → http://localhost:8402/v1 → model name blockrun/auto.

Routing profiles:

note

ClawRouter requires a USDC-funded wallet on Base or Solana for payment. All requests route through BlockRun's backend API. Run npx @blockrun/clawrouter doctor to check wallet status.

---

### Other Compatible Providers[​](#other-compatible-providers)

Any service with an OpenAI-compatible API works. Some popular options:

[](https://together.ai)[](https://groq.com)[](https://deepseek.com)[](https://fireworks.ai)[](https://www.gmicloud.ai/)[](https://cerebras.ai)[](https://mistral.ai)[](https://openai.com)[](https://azure.microsoft.com)[](https://localai.io)[](https://jan.ai)

Configure any of these with hermes model → Custom endpoint, or in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 default: meta-llama/Llama-3.1-70B-Instruct-Turbo
 provider: custom
 base_url: https://api.together.xyz/v1
 api_key: your-together-key

```

---

### Context Length Detection[​](#context-length-detection)

Two settings, easy to confuse

**context_length** is the **total context window** — the combined budget for input *and* output tokens (e.g. 200,000 for Claude Opus 4.6). Hermes uses this to decide when to compress history and to validate API requests.

**model.max_tokens** is the **output cap** — the maximum number of tokens the model may generate in a *single response*. It has nothing to do with how long your conversation history can be. The industry-standard name max_tokens is a common source of confusion; Anthropic's native API has since renamed it max_output_tokens for clarity.

Set context_length when auto-detection gets the window size wrong.
Set model.max_tokens only when you need to limit how long individual responses can be.

Hermes uses a multi-source resolution chain to detect the correct context window for your model and provider:

******************************[](https://models.dev)******
1. Config override — model.context_length in config.yaml (highest priority)

2. Custom provider per-model — custom_providers[].models.<id>.context_length

3. Persistent cache — previously discovered values (survives restarts)

4. Endpoint /models — queries your server's API (local/custom endpoints)

5. Anthropic /v1/models — queries Anthropic's API for max_input_tokens (API-key users only)

6. OpenRouter API — live model metadata from OpenRouter

7. Nous Portal — suffix-matches Nous model IDs against OpenRouter metadata

8. models.dev — community-maintained registry with provider-specific context lengths for 3800+ models across 100+ providers

9. Fallback defaults — broad model family patterns (128K default)

For most setups this works out of the box. The system is provider-aware — the same model can have different context limits depending on who serves it (e.g., claude-opus-4.6 is 1M on Anthropic direct but 128K on GitHub Copilot).

To set the context length explicitly, add context_length to your model config:

```prism-code yaml codeBlock_bY9V thin-scrollbar
model:
 default: "qwen3.5:9b"
 base_url: "http://localhost:8080/v1"
 context_length: 131072 # tokens

```

For custom endpoints, you can also set context length per model:

```prism-code yaml codeBlock_bY9V thin-scrollbar
custom_providers:
 - name: "My Local LLM"
 base_url: "http://localhost:11434/v1"
 models:
 qwen3.5:27b:
 context_length: 32768
 deepseek-r1:70b:
 context_length: 65536

```

hermes model will prompt for context length when configuring a custom endpoint. Leave it blank for auto-detection.

When to set this manually
- You're using Ollama with a custom num_ctx that's lower than the model's maximum

- You want to limit context below the model's maximum (e.g., 8k on a 128k model to save VRAM)

- You're running behind a proxy that doesn't expose /v1/models

---

### Named Custom Providers[​](#named-custom-providers)

If you work with multiple custom endpoints (e.g., a local dev server and a remote GPU server), you can define them as named custom providers in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
custom_providers:
 - name: local
 base_url: http://localhost:8080/v1
 # api_key omitted — Hermes uses "no-key-required" for keyless local servers
 - name: work
 base_url: https://gpu-server.internal.corp/v1
 key_env: CORP_API_KEY
 api_mode: chat_completions # optional, auto-detected from URL
 - name: anthropic-proxy
 base_url: https://proxy.example.com/anthropic
 key_env: ANTHROPIC_PROXY_KEY
 api_mode: anthropic_messages # for Anthropic-compatible proxies

```

Switch between them mid-session with the triple syntax:

```prism-code text codeBlock_bY9V thin-scrollbar
/model custom:local:qwen-2.5 # Use the "local" endpoint with qwen-2.5
/model custom:work:llama3-70b # Use the "work" endpoint with llama3-70b
/model custom:anthropic-proxy:claude-sonnet-4 # Use the proxy

```

You can also select named custom providers from the interactive hermes model menu.

---

### Choosing the Right Setup[​](#choosing-the-right-setup)

************************************
tip

You can switch between providers at any time with hermes model — no restart required. Your conversation history, memory, and skills carry over regardless of which provider you use.

## Optional API Keys[​](#optional-api-keys)

[](https://firecrawl.dev/)[](https://browserbase.com/)[](https://fal.ai/)[](https://elevenlabs.io/)[](https://platform.openai.com/api-keys)[](https://console.mistral.ai/)[](https://tinker-console.thinkingmachines.ai/)[](https://wandb.ai/)[](https://honcho.dev/)[](https://supermemory.ai)

### Self-Hosting Firecrawl[​](#self-hosting-firecrawl)

By default, Hermes uses the [Firecrawl cloud API](https://firecrawl.dev/) for web search and scraping. If you prefer to run Firecrawl locally, you can point Hermes at a self-hosted instance instead. See Firecrawl's [SELF_HOST.md](https://github.com/firecrawl/firecrawl/blob/main/SELF_HOST.md) for complete setup instructions.

**What you get:** No API key required, no rate limits, no per-page costs, full data sovereignty.

**What you lose:** The cloud version uses Firecrawl's proprietary "Fire-engine" for advanced anti-bot bypassing (Cloudflare, CAPTCHAs, IP rotation). Self-hosted uses basic fetch + Playwright, so some protected sites may fail. Search uses DuckDuckGo instead of Google.

**Setup:**

```prism-code bash codeBlock_bY9V thin-scrollbar

```

```prism-code bash codeBlock_bY9V thin-scrollbar

```

1.
Clone and start the Firecrawl Docker stack (5 containers: API, Playwright, Redis, RabbitMQ, PostgreSQL — requires ~4-8 GB RAM):
git clone https://github.com/firecrawl/firecrawlcd firecrawl# In .env, set: USE_DB_AUTHENTICATION=false, HOST=0.0.0.0, PORT=3002docker compose up -d

2.
Point Hermes at your instance (no API key needed):
hermes config set FIRECRAWL_API_URL http://localhost:3002

You can also set both FIRECRAWL_API_KEY and FIRECRAWL_API_URL if your self-hosted instance has authentication enabled.

## OpenRouter Provider Routing[​](#openrouter-provider-routing)

When using OpenRouter, you can control how requests are routed across providers. Add a provider_routing section to ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
provider_routing:
 sort: "throughput" # "price" (default), "throughput", or "latency"
 # only: ["anthropic"] # Only use these providers
 # ignore: ["deepinfra"] # Skip these providers
 # order: ["anthropic", "google"] # Try providers in this order
 # require_parameters: true # Only use providers that support all request params
 # data_collection: "deny" # Exclude providers that may store/train on data

```

**Shortcuts:** Append :nitro to any model name for throughput sorting (e.g., anthropic/claude-sonnet-4:nitro), or :floor for price sorting.

## Fallback Model[​](#fallback-model)

Configure a backup provider:model that Hermes switches to automatically when your primary model fails (rate limits, server errors, auth failures):

```prism-code yaml codeBlock_bY9V thin-scrollbar
fallback_model:
 provider: openrouter # required
 model: anthropic/claude-sonnet-4 # required
 # base_url: http://localhost:8000/v1 # optional, for custom endpoints
 # key_env: MY_CUSTOM_KEY # optional, env var name for custom endpoint API key

```

When activated, the fallback swaps the model and provider mid-session without losing your conversation. It fires **at most once** per session.

Supported providers: openrouter, nous, openai-codex, copilot, copilot-acp, anthropic, gemini, google-gemini-cli, qwen-oauth, huggingface, zai, kimi-coding, kimi-coding-cn, minimax, minimax-cn, deepseek, nvidia, xai, ollama-cloud, bedrock, ai-gateway, opencode-zen, opencode-go, kilocode, xiaomi, arcee, alibaba, custom.

tip

Fallback is configured exclusively through config.yaml — there are no environment variables for it. For full details on when it triggers, supported providers, and how it interacts with auxiliary tasks and delegation, see [Fallback Providers](/docs/user-guide/features/fallback-providers).

---

## See Also[​](#see-also)

[](/docs/user-guide/configuration)[](/docs/reference/environment-variables)
- Configuration — General configuration (directory structure, config precedence, terminal backends, memory, compression, and more)

- Environment Variables — Complete reference of all environment variables
[](#inference-providers)[](#google-gemini-via-oauth-google-gemini-cli)[](#two-commands-for-model-management)[](#anthropic-native)[](#github-copilot)[](#first-class-chinese-ai-providers)[](#xai-grok--responses-api--prompt-caching)[](#ollama-cloud--managed-ollama-models-oauth--api-key)[](#aws-bedrock)[](#qwen-portal-oauth)[](#nvidia-nim)[](#hugging-face-inference-providers)
- Google Gemini via OAuth (google-gemini-cli)
- Two Commands for Model Management
- Anthropic (Native)
- GitHub Copilot
- First-Class Chinese AI Providers
- xAI (Grok) — Responses API + Prompt Caching
- Ollama Cloud — Managed Ollama Models, OAuth + API Key
- AWS Bedrock
- Qwen Portal (OAuth)
- NVIDIA NIM
- Hugging Face Inference Providers
- [Custom & Self-Hosted LLM Providers](#custom--self-hosted-llm-providers)[](#general-setup)[](#switching-models-with-model)[](#ollama--local-models-zero-config)[](#vllm--high-performance-gpu-inference)[](#sglang--fast-serving-with-radixattention)[](#llamacpp--llama-server--cpu--metal-inference)[](#lm-studio--desktop-app-with-local-models)[](#wsl2-networking-windows-users)[](#troubleshooting-local-models)[](#litellm-proxy--multi-provider-gateway)[](#clawrouter--cost-optimized-routing)[](#other-compatible-providers)[](#context-length-detection)[](#named-custom-providers)[](#choosing-the-right-setup)
- General Setup
- Switching Models with /model
- Ollama — Local Models, Zero Config
- vLLM — High-Performance GPU Inference
- SGLang — Fast Serving with RadixAttention
- llama.cpp / llama-server — CPU & Metal Inference
- LM Studio — Desktop App with Local Models
- WSL2 Networking (Windows Users)
- Troubleshooting Local Models
- LiteLLM Proxy — Multi-Provider Gateway
- ClawRouter — Cost-Optimized Routing
- Other Compatible Providers
- Context Length Detection
- Named Custom Providers
- Choosing the Right Setup
- [Optional API Keys](#optional-api-keys)[](#self-hosting-firecrawl)
- Self-Hosting Firecrawl
- [OpenRouter Provider Routing](#openrouter-provider-routing)
- [Fallback Model](#fallback-model)
- [See Also](#see-also)