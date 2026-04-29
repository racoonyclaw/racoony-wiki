---
pageType: synthesis
id: synthesis.raccoony-ops
title: Raccoony Operations
topics:
- entities/randomstix
sourceIds:
- '17217018642'
- '17229192111434'
- '19216811008123'
- '19216811008642'
- '1921681101234'
- MEMORY.md
- USER.md
- agentskillsio
- apigroqcom
- apiopenaicom
- apislackcom
- apitogetherxyz
- astralsh
- bluebubblesapp
- botqqqcom
- buildnvidiacom
- chat-agentslobehubco
- clawhubai
- cloudcode-pagoogleap
- consolecloudgoogleco
- consoletwiliocom
- developersgooglecom
- discordcom
- discordgg
- docsastralsh
- docsbluebubblesapp
- docslitellmai
- docsvllmai
- firecrawldev
- githubcom
- gpu-serverinternalco
- hermes-agentnousrese
- homeassistantlocal81
- hostdockerinternal86
- hostname
- huggingfaceco
- learnmicrosoftcom
- lmstudioai
- lobehubcom
- mac-ip8642
- matrixexampleorg
- mattermost-backend
- mcpdocsexamplecom
- mcpexamplecom
- mcpinternalexampleco
- mcplegacyinternal
- mcpstripecom
- mintlifycom
- mmexamplecom
- my-appflydev
- nousresearchcom
- ollamacom
- openbigmodelcn
- openfeishucn
- openlarksuitecom
- openrouterai
- portalnousresearchco
- portalqwenai
- proxyexamplecom
- proxyexamplecom8080
- python-telegram-boto
- rawgithubusercontent
- session-2026-04-23
- skillssh
- source.lark2022ethanol
- tme
- weixinqqcom
- workweixinqqcom
- wsl-host11434
- wwwconventionalcommi
- wwwhome-assistantio
- wwwtwiliocom
- your-mattermost-serv
- your-server
- your-server8080
- your-server8644
- your-server8765
claims:
- id: type
  text: Web application running in Docker container
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lolok-site
    path: entities/lolok-site.md
- id: port
  text: Live container at port 5001
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lolok-site
    path: entities/lolok-site.md
- id: deployment
  text: CI/CD via GitHub Actions + self-hosted runner (lolok-runner)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lolok-site
    path: entities/lolok-site.md
- id: static-server
  text: Static file server was on port 8080, may need restart
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lolok-site
    path: entities/lolok-site.md
- id: dates
  text: September 18-20, 2026
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lost-lands-2026
    path: entities/lost-lands-2026.md
- id: location
  text: Legend Valley, OH
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lost-lands-2026
    path: entities/lost-lands-2026.md
- id: cost
  text: GA Tier 4 ($512.91) + Thursday Early Entry ($107.02) + shipping ($16.49) -
    promo ($25) = $611.42 total
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lost-lands-2026
    path: entities/lost-lands-2026.md
- id: ticket-type
  text: GA Tier 4 with Thursday Early Entry
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.lost-lands-2026
    path: entities/lost-lands-2026.md
- id: name
  text: Name is randomstix
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.randomstix
    path: entities/randomstix.md
- id: email
  text: Email is quocvu2640@gmail.com
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.randomstix
    path: entities/randomstix.md
- id: discord-handle
  text: 'Contact via Discord #general'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.randomstix
    path: entities/randomstix.md
- id: timezone
  text: America/New_York (EDT/EST)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.randomstix
    path: entities/randomstix.md
- id: location
  text: Running at /opt/stacks/hindsight_memory/
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.hindsight-memory-server
    path: entities/hindsight-memory-server.md
- id: api-port
  text: API on port 8888, Control Plane on port 9999
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.hindsight-memory-server
    path: entities/hindsight-memory-server.md
- id: database
  text: Uses pgvector/pgvector:pg18 (PostgreSQL with pgvector extension)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.hindsight-memory-server
    path: entities/hindsight-memory-server.md
- id: llm-provider
  text: Uses MiniMax-M2.7 via HINDSIGHT_API_LLM_PROVIDER=minimax
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.hindsight-memory-server
    path: entities/hindsight-memory-server.md
- id: api-key
  text: HINDSIGHT_API_KEY is set in .env but API key auth is not enforced in this
    version (v0.5.4)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.hindsight-memory-server
    path: entities/hindsight-memory-server.md
- id: volumes
  text: Data persisted at ./db (pgvector data) and ./hindsight-data (embedded pg0
    fallback)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.hindsight-memory-server
    path: entities/hindsight-memory-server.md
- id: compose-fix
  text: "compose.yaml had two bugs: (1) wrong env_file syntax 'path: .env' should\
    \ be '.env', (2) volume mount ./db:/var/lib/postgresql/data wrong \u2014 pgvector\
    \ image stores at /var/lib/postgresql not /var/lib/postgresql/data"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.hindsight-memory-server
    path: entities/hindsight-memory-server.md
- id: add-a-new-provider-openrouter-anthropic-copilot-deepse
  text: add a new provider** (OpenRouter, Anthropic, Copilot, DeepSeek, custom, etc.)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: log-into-oauth-backed-providers-anthropic-copilot-codex
  text: log into OAuth-backed providers (Anthropic, Copilot, Codex, Nous Portal)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: enter-or-update-api-keys
  text: enter or update API keys
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: pick-from-provider-specific-model-lists
  text: pick from provider-specific model lists
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: configure-a-customself-hosted-endpoint
  text: configure a custom/self-hosted endpoint
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: save-the-new-default-into-config
  text: save the new default into config
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: hermes-dump----version-080-202648-af4abd2f
  text: 'hermes dump ---version:          0.8.0 (2026.4.8) [af4abd2f]os:               Linux
    6.14.0-37-generic x86_64python:           3.11.14openai_sdk:       2.24.0profile:          defaulthermes_home:      ~/.hermesmodel:            anthropic/claude-opus-4.6provider:         openrouterterminal:         localapi_keys:  openrouter           set  openai               not
    set  anthropic            set  nous                 not set  firecrawl            set  ...features:  toolsets:           all  mcp_servers:        0  memory_provider:    built-in  gateway:            running
    (systemd)  platforms:          telegram, discord  cron_jobs:          3 active
    / 5 total  skills:             42config_overrides:  agent.max_turns: 250  compression.threshold:
    0.85  display.streaming: True--- end dump ---'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: reporting-a-bug-on-github-paste-the-dump-into-your-issue
  text: "Reporting a bug on GitHub \u2014 paste the dump into your issue"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: asking-for-help-in-discord-share-it-in-a-code-block
  text: "Asking for help in Discord \u2014 share it in a code block"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: comparing-your-setup-to-someone-elsex27s
  text: Comparing your setup to someone else&#x27;s
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: quick-sanity-check-when-something-isnx27t-working
  text: Quick sanity check when something isn&#x27;t working
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: force-can-override-non-dangerous-policy-blocks-for-third
  text: '`--force` can override non-dangerous policy blocks for third-party/community
    skills.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: force-does-not-override-a-dangerous-scan-verdict
  text: '`--force` does not override a `dangerous` scan verdict.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: source-skills-sh-searches-the-public-skillssh-directo
  text: '`--source skills-sh` searches the public `skills.sh` directory.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: source-well-known-lets-you-point-hermes-at-a-site-exposi
  text: '`--source well-known` lets you point Hermes at a site exposing `/.well-known/skills/index.json`.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: general-plugins-multi-select-checkboxes-to-enabledisabl
  text: "General Plugins** \u2014 multi-select checkboxes to enable/disable installed\
    \ plugins"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: provider-plugins-single-select-configuration-for-memory
  text: "Provider Plugins** \u2014 single-select configuration for Memory Provider\
    \ and Context Engine. Press ENTER on a category to open a radio picker."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: memoryprovider-active-memory-provider-empty-built-in
  text: "`memory.provider` \u2014 active memory provider (empty = built-in only)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: contextengine-active-context-engine-quotcompressor
  text: "`context.engine` \u2014 active context engine (`&quot;compressor&quot;` =\
    \ built-in default)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: slash-commands-referencedocsreferenceslash-commands
  text: '[Slash Commands Reference](/docs/reference/slash-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: cli-interfacedocsuser-guidecli
  text: '[CLI Interface](/docs/user-guide/cli)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: sessionsdocsuser-guidesessions
  text: '[Sessions](/docs/user-guide/sessions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: skills-systemdocsuser-guidefeaturesskills
  text: '[Skills System](/docs/user-guide/features/skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: skins-amp-themesdocsuser-guidefeaturesskins
  text: '[Skins &amp; Themes](/docs/user-guide/features/skins)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-commands-reference
    path: entities/cli-commands-reference.md
- id: bug-fixes-crashes-incorrect-behavior-data-loss
  text: "Bug fixes** \u2014 crashes, incorrect behavior, data loss"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: cross-platform-compatibility-macos-different-linux-dist
  text: "Cross-platform compatibility** \u2014 macOS, different Linux distros, WSL2"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: security-hardening-shell-injection-prompt-injection-pa
  text: "Security hardening** \u2014 shell injection, prompt injection, path traversal"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: performance-and-robustness-retry-logic-error-handling
  text: "Performance and robustness** \u2014 retry logic, error handling, graceful\
    \ degradation"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: new-skills-broadly-useful-ones-see-creating-skillsd
  text: "New skills** \u2014 broadly useful ones (see [Creating Skills](/docs/developer-guide/creating-skills))"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: new-tools-rarely-needed-most-capabilities-should-be-ski
  text: "New tools** \u2014 rarely needed; most capabilities should be skills"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: documentation-fixes-clarifications-new-examples
  text: "Documentation** \u2014 fixes, clarifications, new examples"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: building-a-new-tool-start-with-adding-toolsdocsdevelop
  text: Building a new tool? Start with [Adding Tools](/docs/developer-guide/adding-tools)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: building-a-new-skill-start-with-creating-skillsdocsdev
  text: Building a new skill? Start with [Creating Skills](/docs/developer-guide/creating-skills)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: building-a-new-inference-provider-start-with-adding-provid
  text: Building a new inference provider? Start with [Adding Providers](/docs/developer-guide/adding-providers)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: pep-8-with-practical-exceptions-no-strict-line-length-enf
  text: PEP 8** with practical exceptions (no strict line length enforcement)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: comments-only-when-explaining-non-obvious-intent-trade-o
  text: 'Comments**: Only when explaining non-obvious intent, trade-offs, or API quirks'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: error-handling-catch-specific-exceptions-use-loggerwar
  text: 'Error handling**: Catch specific exceptions. Use `logger.warning()`/`logger.error()`
    with `exc_info=True` for unexpected errors'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: cross-platform-never-assume-unix-see-below
  text: 'Cross-platform**: Never assume Unix (see below)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: profile-safe-paths-never-hardcode-hermes-use-get
  text: "Profile-safe paths**: Never hardcode `~/.hermes` \u2014 use `get_hermes_home()`\
    \ from `hermes_constants` for code paths and `display_hermes_home()` for user-facing\
    \ messages. See [AGENTS.md](https://github.com/NousResearch/hermes-agent/blob/main/AGENTS.md#profiles-multi-instance-support)\
    \ for full rules."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: always-use-shlexquote-when-interpolating-user-input-int
  text: Always use `shlex.quote()` when interpolating user input into shell commands
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: resolve-symlinks-with-ospathrealpath-before-access-con
  text: Resolve symlinks with `os.path.realpath()` before access control checks
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: donx27t-log-secrets
  text: Don&#x27;t log secrets
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: catch-broad-exceptions-around-tool-execution
  text: Catch broad exceptions around tool execution
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: test-on-all-platforms-if-your-change-touches-file-paths-or-p
  text: Test on all platforms if your change touches file paths or processes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: run-tests-pytest-tests--v
  text: 'Run tests**: `pytest tests/ -v`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: test-manually-run-hermes-and-exercise-the-code-path-you
  text: 'Test manually**: Run `hermes` and exercise the code path you changed'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: check-cross-platform-impact-consider-macos-and-different
  text: 'Check cross-platform impact**: Consider macOS and different Linux distros'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: keep-prs-focused-one-logical-change-per-pr
  text: 'Keep PRs focused**: One logical change per PR'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: what-changed-and-why
  text: What** changed and **why**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: how-to-test-it
  text: How to test** it
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: what-platforms-you-tested-on
  text: What platforms** you tested on
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: reference-any-related-issues
  text: Reference any related issues
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: use-github-issueshttpsgithubcomnousresearchhermes-a
  text: Use [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: include-os-python-version-hermes-version-hermes-version
  text: 'Include: OS, Python version, Hermes version (`hermes version`), full error
    traceback'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: include-steps-to-reproduce
  text: Include steps to reproduce
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: check-existing-issues-before-creating-duplicates
  text: Check existing issues before creating duplicates
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: for-security-vulnerabilities-please-report-privately
  text: For security vulnerabilities, please report privately
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: discord-discordggnousresearchhttpsdiscordggnous
  text: 'Discord**: [discord.gg/NousResearch](https://discord.gg/NousResearch)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: github-discussions-for-design-proposals-and-architecture
  text: 'GitHub Discussions**: For design proposals and architecture discussions'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: skills-hub-upload-specialized-skills-and-share-with-the-c
  text: 'Skills Hub**: Upload specialized skills and share with the community'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.contributing
    path: entities/contributing.md
- id: this-page-orient-yourself
  text: "This page** \u2014 orient yourself"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: agent-loop-internalsdocsdeveloper-guideagent-loop
  text: "[Agent Loop Internals](/docs/developer-guide/agent-loop)** \u2014 how AIAgent\
    \ works"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: prompt-assemblydocsdeveloper-guideprompt-assembly
  text: "[Prompt Assembly](/docs/developer-guide/prompt-assembly)** \u2014 system\
    \ prompt construction"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: provider-runtime-resolutiondocsdeveloper-guideprovider
  text: "[Provider Runtime Resolution](/docs/developer-guide/provider-runtime)** \u2014\
    \ how providers are selected"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: adding-providersdocsdeveloper-guideadding-providers
  text: "[Adding Providers](/docs/developer-guide/adding-providers)** \u2014 practical\
    \ guide to adding a new provider"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: tools-runtimedocsdeveloper-guidetools-runtime-too
  text: "[Tools Runtime](/docs/developer-guide/tools-runtime)** \u2014 tool registry,\
    \ dispatch, environments"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: session-storagedocsdeveloper-guidesession-storage
  text: "[Session Storage](/docs/developer-guide/session-storage)** \u2014 SQLite\
    \ schema, FTS5, session lineage"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: gateway-internalsdocsdeveloper-guidegateway-internals
  text: "[Gateway Internals](/docs/developer-guide/gateway-internals)** \u2014 messaging\
    \ platform gateway"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: context-compression-amp-prompt-cachingdocsdeveloper-g
  text: "[Context Compression &amp; Prompt Caching](/docs/developer-guide/context-compression-and-caching)**\
    \ \u2014 compression and caching"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: acp-internalsdocsdeveloper-guideacp-internals-ide
  text: "[ACP Internals](/docs/developer-guide/acp-internals)** \u2014 IDE integration"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: environments-benchmarks-amp-data-generationdocsdevel
  text: "[Environments, Benchmarks &amp; Data Generation](/docs/developer-guide/environments)**\
    \ \u2014 RL training"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: prompt-builderpy-assembles-the-system-prompt-from-pe
  text: "`prompt_builder.py`** \u2014 Assembles the system prompt from: personality\
    \ (SOUL.md), memory (MEMORY.md, USER.md), skills, context files (AGENTS.md, .hermes.md),\
    \ tool-use guidance, and model-specific instructions"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: prompt-cachingpy-applies-anthropic-cache-breakpoints
  text: "`prompt_caching.py`** \u2014 Applies Anthropic cache breakpoints for prefix\
    \ caching"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: context-compressorpy-summarizes-middle-conversation-t
  text: "`context_compressor.py`** \u2014 Summarizes middle conversation turns when\
    \ context exceeds thresholds"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.architecture
    path: entities/architecture.md
- id: pkce-authorization-code-flow-against-accountsgooglecom
  text: PKCE Authorization Code flow against accounts.google.com
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: browser-callback-at-http1270018085oauth2callback-wi
  text: Browser callback at http://127.0.0.1:8085/oauth2callback (with ephemeral-port
    fallback if busy)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: tokens-stored-at-hermesauthgoogle-oauthjson-chmod-060
  text: Tokens stored at ~/.hermes/auth/google_oauth.json (chmod 0600, atomic write,
    cross-process fcntl lock)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: automatic-refresh-60-s-before-expiry
  text: Automatic refresh 60 s before expiry
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: headless-environments-ssh-hermes-headless1-paste-mode
  text: "Headless environments (SSH, HERMES_HEADLESS=1) \u2192 paste-mode fallback"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: inflight-refresh-deduplication-two-concurrent-requests-won
  text: "Inflight refresh deduplication \u2014 two concurrent requests won't double-refresh"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: invalid-grant-revoked-refresh-credential-file-wiped-use
  text: "invalid_grant (revoked refresh) \u2192 credential file wiped, user prompted\
    \ to re-login"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: traffic-goes-to-httpscloudcode-pagoogleapiscomv1intern
  text: Traffic goes to https://cloudcode-pa.googleapis.com/v1internal:generateContent
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: request-body-wrapped-project-model-user-prompt-id-reques
  text: Request body wrapped {project, model, user_prompt_id, request}
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: openai-shaped-messages-tools-tool-choice-are-translate
  text: OpenAI-shaped messages[], tools[], tool_choice are translated to Gemini's
    native
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: responses-translated-back-to-openai-shape-so-the-rest-of-her
  text: Responses translated back to OpenAI shape so the rest of Hermes works unchanged
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: provider-claude-and---provider-claude-code-also-work-as-shor
  text: provider claude and --provider claude-code also work as shorthand for --provider
    anthropic.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: port-8000
  text: port 8000 \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: max-model-len-65536
  text: max-model-len 65536 \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: tensor-parallel-size-2
  text: tensor-parallel-size 2 \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: enable-auto-tool-choice
  text: enable-auto-tool-choice \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: tool-call-parser-hermes
  text: tool-call-parser hermes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: model-meta-llamallama-31-70b-instruct
  text: model meta-llama/Llama-3.1-70B-Instruct \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: port-30000
  text: port 30000 \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: context-length-65536
  text: context-length 65536 \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: tool-call-parser-qwen
  text: tool-call-parser qwen
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: jinja--fa
  text: jinja -fa \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: m-modelsqwen25-coder-32b-instruct-q4-k-mgguf
  text: m models/qwen2.5-coder-32b-instruct-Q4_K_M.gguf \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: port-8080---host-0000
  text: port 8080 --host 0.0.0.0
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: jinja-is-required-for-tool-calling
  text: jinja is required for tool calling
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: model-name-best
  text: 'model_name: "best"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: name-my-local-llm
  text: 'name: "My Local LLM"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: youre-using-ollama-with-a-custom-num-ctx-thats-lower-than
  text: You're using Ollama with a custom num_ctx that's lower than the model's maximum
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: you-want-to-limit-context-below-the-models-maximum-eg-8
  text: You want to limit context below the model's maximum (e.g., 8k on a 128k model
    to save VRAM)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: youre-running-behind-a-proxy-that-doesnt-expose-v1models
  text: You're running behind a proxy that doesn't expose /v1/models
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: name-local
  text: 'name: local'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: name-work
  text: 'name: work'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: name-anthropic-proxy
  text: 'name: anthropic-proxy'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: configuration-general-configuration-directory-structure
  text: "Configuration \u2014 General configuration (directory structure, config precedence,\
    \ terminal backends, memory, compression, and more)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: environment-variables-complete-reference-of-all-environmen
  text: "Environment Variables \u2014 Complete reference of all environment variables"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: google-gemini-via-oauth-google-gemini-cli
  text: Google Gemini via OAuth (google-gemini-cli)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: two-commands-for-model-management
  text: Two Commands for Model Management
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: anthropic-native
  text: Anthropic (Native)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: github-copilot
  text: GitHub Copilot
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: first-class-chinese-ai-providers
  text: First-Class Chinese AI Providers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: xai-grok-responses-api-prompt-caching
  text: "xAI (Grok) \u2014 Responses API + Prompt Caching"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: ollama-cloud-managed-ollama-models-oauth-api-key
  text: "Ollama Cloud \u2014 Managed Ollama Models, OAuth + API Key"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: aws-bedrock
  text: AWS Bedrock
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: qwen-portal-oauth
  text: Qwen Portal (OAuth)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: nvidia-nim
  text: NVIDIA NIM
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: hugging-face-inference-providers
  text: Hugging Face Inference Providers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: custom-self-hosted-llm-providerscustom--self-hosted-ll
  text: '[Custom & Self-Hosted LLM Providers](#custom--self-hosted-llm-providers)[](#general-setup)[](#switching-models-with-model)[](#ollama--local-models-zero-config)[](#vllm--high-performance-gpu-inference)[](#sglang--fast-serving-with-radixattention)[](#llamacpp--llama-server--cpu--metal-inference)[](#lm-studio--desktop-app-with-local-models)[](#wsl2-networking-windows-users)[](#troubleshooting-local-models)[](#litellm-proxy--multi-provider-gateway)[](#clawrouter--cost-optimized-routing)[](#other-compatible-providers)[](#context-length-detection)[](#named-custom-providers)[](#choosing-the-right-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: general-setup
  text: General Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: switching-models-with-model
  text: Switching Models with /model
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: ollama-local-models-zero-config
  text: "Ollama \u2014 Local Models, Zero Config"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: vllm-high-performance-gpu-inference
  text: "vLLM \u2014 High-Performance GPU Inference"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: sglang-fast-serving-with-radixattention
  text: "SGLang \u2014 Fast Serving with RadixAttention"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: llamacpp-llama-server-cpu-metal-inference
  text: "llama.cpp / llama-server \u2014 CPU & Metal Inference"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: lm-studio-desktop-app-with-local-models
  text: "LM Studio \u2014 Desktop App with Local Models"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: wsl2-networking-windows-users
  text: WSL2 Networking (Windows Users)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: troubleshooting-local-models
  text: Troubleshooting Local Models
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: litellm-proxy-multi-provider-gateway
  text: "LiteLLM Proxy \u2014 Multi-Provider Gateway"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: clawrouter-cost-optimized-routing
  text: "ClawRouter \u2014 Cost-Optimized Routing"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: other-compatible-providers
  text: Other Compatible Providers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: context-length-detection
  text: Context Length Detection
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: named-custom-providers
  text: Named Custom Providers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: choosing-the-right-setup
  text: Choosing the Right Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: optional-api-keysoptional-api-keysself-hosting-fire
  text: '[Optional API Keys](#optional-api-keys)[](#self-hosting-firecrawl)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: self-hosting-firecrawl
  text: Self-Hosting Firecrawl
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: openrouter-provider-routingopenrouter-provider-routing
  text: '[OpenRouter Provider Routing](#openrouter-provider-routing)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: fallback-modelfallback-model
  text: '[Fallback Model](#fallback-model)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: see-alsosee-also
  text: '[See Also](#see-also)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.ai-providers
    path: entities/ai-providers.md
- id: pull-requesttitle-resolves-to-payloadpull-requestti
  text: '{pull_request.title} resolves to payload["pull_request"]["title"]'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: repositoryfull-name-resolves-to-payloadrepositoryfu
  text: '{repository.full_name} resolves to payload["repository"]["full_name"]'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: raw-special-token-that-dumps-the-entire-payload-as-i
  text: "{__raw__} \u2014 special token that dumps the entire payload as indented\
    \ JSON (truncated at 4000 characters). Useful for monitoring alerts or generic\
    \ webhooks where the agent needs the full context."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: missing-keys-are-left-as-the-literal-key-string-no-error
  text: Missing keys are left as the literal {key} string (no error)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: nested-dicts-and-lists-are-json-serialized-and-truncated-at
  text: Nested dicts and lists are JSON-serialized and truncated at 2000 characters
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: external-service-push-supabasefirebase-webhook-fires-on-a
  text: "External service push \u2014 Supabase/Firebase webhook fires on a database\
    \ change \u2192 notify a user in Telegram instantly"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: monitoring-alerts-datadoggrafana-alert-webhook-push-to
  text: "Monitoring alerts \u2014 Datadog/Grafana alert webhook \u2192 push to a Discord\
    \ channel"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: inter-agent-pings-agent-a-notifies-agent-bs-user-that-a-l
  text: "Inter-agent pings \u2014 Agent A notifies Agent B's user that a long-running\
    \ task finished"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: background-job-completion-cron-job-finishes-post-result
  text: "Background job completion \u2014 Cron job finishes \u2192 post result to\
    \ Slack"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: zero-llm-tokens-the-agent-is-never-invoked
  text: "Zero LLM tokens \u2014 the agent is never invoked"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: sub-second-delivery-a-single-adapter-call-no-reasoning-lo
  text: "Sub-second delivery \u2014 a single adapter call, no reasoning loop"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: same-security-as-agent-mode-hmac-auth-rate-limits-idempo
  text: "Same security as agent mode \u2014 HMAC auth, rate limits, idempotency, and\
    \ body-size limits all still apply"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: synchronous-response-the-post-returns-200-ok-once-delivery
  text: "Synchronous response \u2014 the POST returns 200 OK once delivery succeeds,\
    \ or 502 if the target rejects it, so your upstream service can retry intelligently"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: deliver-telegram
  text: deliver telegram \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: deliver-chat-id-123456789
  text: deliver-chat-id "123456789" \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: deliver-only
  text: deliver-only \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: prompt-new-match-matchuser-name-matched-with-you
  text: "prompt \"\U0001F389 New match: {match.user_name} matched with you!\" \\"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: description-antenna-match-notifications
  text: description "Antenna match notifications"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: deliver-only-true-requires-deliver-to-be-a-real-target-del
  text: "deliver_only: true requires deliver to be a real target. deliver: log (or\
    \ omitting deliver) is rejected at startup \u2014 the adapter refuses to start\
    \ if it finds a misconfigured route."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: the-skills-field-is-ignored-in-direct-delivery-mode-no-agen
  text: The skills field is ignored in direct delivery mode (no agent runs, so there's
    nothing to inject skills into).
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: template-rendering-uses-the-same-dotnotation-syntax-as-ag
  text: Template rendering uses the same {dot.notation} syntax as agent mode, including
    the {__raw__} token.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: idempotency-uses-the-same-x-github-delivery-x-request-id-h
  text: "Idempotency uses the same X-GitHub-Delivery / X-Request-ID header \u2014\
    \ retries with the same ID return status=duplicate and do NOT re-deliver."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: events-issues
  text: events "issues" \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: prompt-new-issue-issuenumber-issuetitlenby-issue
  text: 'prompt "New issue #{issue.number}: {issue.title}\nBy: {issue.user.login}\n\n{issue.body}"
    \'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: deliver-chat-id--100123456789
  text: deliver-chat-id "-100123456789" \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: description-triage-new-github-issues
  text: description "Triage new GitHub issues"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: subscriptions-are-stored-in-hermeswebhook-subscriptions
  text: Subscriptions are stored in ~/.hermes/webhook_subscriptions.json
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: the-webhook-adapter-hot-reloads-this-file-on-each-incoming-r
  text: The webhook adapter hot-reloads this file on each incoming request (mtime-gated,
    negligible overhead)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: static-routes-from-configyaml-always-take-precedence-over-d
  text: Static routes from config.yaml always take precedence over dynamic ones with
    the same name
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: dynamic-subscriptions-use-the-same-route-format-and-capabili
  text: Dynamic subscriptions use the same route format and capabilities as static
    routes (events, prompt templates, skills, delivery)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: no-gateway-restart-required-subscribe-and-its-immediately
  text: "No gateway restart required \u2014 subscribe and it's immediately live"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: github-x-hub-signature-256-header-hmac-sha256-hex-digest
  text: "GitHub: X-Hub-Signature-256 header \u2014 HMAC-SHA256 hex digest prefixed\
    \ with sha256="
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: gitlab-x-gitlab-token-header-plain-secret-string-match
  text: "GitLab: X-Gitlab-Token header \u2014 plain secret string match"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: generic-x-webhook-signature-header-raw-hmac-sha256-hex-di
  text: "Generic: X-Webhook-Signature header \u2014 raw HMAC-SHA256 hex digest"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: verify-the-port-is-exposed-and-accessible-from-the-webhook-s
  text: Verify the port is exposed and accessible from the webhook source
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: check-firewall-rules-port-8644-or-your-configured-port-m
  text: "Check firewall rules \u2014 port 8644 (or your configured port) must be open"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: verify-the-url-path-matches-httpyour-server8644webhook
  text: 'Verify the URL path matches: http://your-server:8644/webhooks/<route-name>'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: use-the-health-endpoint-to-confirm-the-server-is-running
  text: Use the /health endpoint to confirm the server is running
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: ensure-the-secret-in-your-route-config-exactly-matches-the-s
  text: Ensure the secret in your route config exactly matches the secret configured
    in the webhook source
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: for-github-the-secret-is-hmac-based-check-x-hub-signature
  text: "For GitHub, the secret is HMAC-based \u2014 check X-Hub-Signature-256"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: for-gitlab-the-secret-is-a-plain-token-match-check-x-gitl
  text: "For GitLab, the secret is a plain token match \u2014 check X-Gitlab-Token"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: check-gateway-logs-for-invalid-signature-warnings
  text: Check gateway logs for Invalid signature warnings
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: check-that-the-event-type-is-in-your-routes-events-list
  text: Check that the event type is in your route's events list
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: github-events-use-values-like-pull-request-push-issues-th
  text: GitHub events use values like pull_request, push, issues (the X-GitHub-Event
    header value)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: gitlab-events-use-values-like-merge-request-push-the-x-git
  text: GitLab events use values like merge_request, push (the X-GitLab-Event header
    value)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: if-events-is-empty-or-not-set-all-events-are-accepted
  text: If events is empty or not set, all events are accepted
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: run-the-gateway-in-foreground-to-see-logs-hermes-gateway-ru
  text: 'Run the gateway in foreground to see logs: hermes gateway run'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: check-that-the-prompt-template-is-rendering-correctly
  text: Check that the prompt template is rendering correctly
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: verify-the-delivery-target-is-configured-and-connected
  text: Verify the delivery target is configured and connected
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: the-idempotency-cache-should-prevent-this-check-that-the-w
  text: "The idempotency cache should prevent this \u2014 check that the webhook source\
    \ is sending a delivery ID header (X-GitHub-Delivery or X-Request-ID)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: delivery-ids-are-cached-for-1-hour
  text: Delivery IDs are cached for 1 hour
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: run-gh-auth-login-on-the-gateway-host
  text: Run gh auth login on the gateway host
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: ensure-the-authenticated-github-user-has-write-access-to-the
  text: Ensure the authenticated GitHub user has write access to the repository
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: check-that-gh-is-installed-and-on-the-path
  text: Check that gh is installed and on the PATH
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: via-setup-wizard
  text: Via setup wizard
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: via-environment-variables
  text: Via environment variables
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: verify-the-server
  text: Verify the server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: configuring-routesconfiguring-routesroute-propertie
  text: '[Configuring Routes](#configuring-routes)[](#route-properties)[](#full-example)[](#prompt-templates)[](#forum-topic-delivery)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: route-properties
  text: Route properties
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: full-example
  text: Full example
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: prompt-templates
  text: Prompt Templates
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: forum-topic-delivery
  text: Forum Topic Delivery
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: github-pr-review-step-by-stepgithub-pr-review1-cr
  text: '[GitHub PR Review (Step by Step)](#github-pr-review)[](#1-create-the-webhook-in-github)[](#2-add-the-route-config)[](#3-ensure-gh-cli-is-authenticated)[](#4-test-it)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: 1-create-the-webhook-in-github
  text: 1. Create the webhook in GitHub
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: 2-add-the-route-config
  text: 2. Add the route config
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: 3-ensure-gh-cli-is-authenticated
  text: 3. Ensure gh CLI is authenticated
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: 4-test-it
  text: 4. Test it
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: gitlab-webhook-setupgitlab-webhook-setup1-create-th
  text: '[GitLab Webhook Setup](#gitlab-webhook-setup)[](#1-create-the-webhook-in-gitlab)[](#2-add-the-route-config-1)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: 1-create-the-webhook-in-gitlab
  text: 1. Create the webhook in GitLab
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: delivery-optionsdelivery-options
  text: '[Delivery Options](#delivery-options)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: direct-delivery-modedirect-delivery-modewhen-to-use
  text: '[Direct Delivery Mode](#direct-delivery-mode)[](#when-to-use-direct-delivery)[](#example-telegram-push-from-supabase)[](#example-dynamic-subscription-via-cli)[](#response-codes)[](#configuration-gotchas)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: when-to-use-direct-delivery
  text: When to use direct delivery
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: example-telegram-push-from-supabase
  text: 'Example: Telegram push from Supabase'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: example-dynamic-subscription-via-cli
  text: 'Example: Dynamic subscription via CLI'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: response-codes
  text: Response codes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: configuration-gotchas
  text: Configuration gotchas
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: dynamic-subscriptions-clidynamic-subscriptionscre
  text: '[Dynamic Subscriptions (CLI)](#dynamic-subscriptions)[](#create-a-subscription)[](#list-subscriptions)[](#remove-a-subscription)[](#test-a-subscription)[](#how-dynamic-subscriptions-work)[](#agent-driven-subscriptions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: create-a-subscription
  text: Create a subscription
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: list-subscriptions
  text: List subscriptions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: remove-a-subscription
  text: Remove a subscription
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: test-a-subscription
  text: Test a subscription
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: how-dynamic-subscriptions-work
  text: How dynamic subscriptions work
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: agent-driven-subscriptions
  text: Agent-driven subscriptions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: securitysecurityhmac-signature-validationsecre
  text: '[Security](#security)[](#hmac-signature-validation)[](#secret-is-required)[](#rate-limiting)[](#idempotency)[](#body-size-limits)[](#prompt-injection-risk)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: hmac-signature-validation
  text: HMAC signature validation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: secret-is-required
  text: Secret is required
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: rate-limiting
  text: Rate limiting
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: idempotency
  text: Idempotency
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: body-size-limits
  text: Body size limits
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: prompt-injection-risk
  text: Prompt injection risk
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: troubleshootingtroubleshootingwebhook-not-arriving
  text: '[Troubleshooting](#troubleshooting)[](#webhook-not-arriving)[](#signature-validation-failing)[](#event-being-ignored)[](#agent-not-responding)[](#duplicate-responses)[](#gh-cli-errors-github-comment-delivery)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: webhook-not-arriving
  text: Webhook not arriving
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: signature-validation-failing
  text: Signature validation failing
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: event-being-ignored
  text: Event being ignored
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: agent-not-responding
  text: Agent not responding
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: duplicate-responses
  text: Duplicate responses
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: gh-cli-errors-github-comment-delivery
  text: gh CLI errors (GitHub comment delivery)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
- id: environment-variablesenvironment-variables
  text: '[Environment Variables](#environment-variables)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.webhooks
    path: entities/webhooks.md
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: e-openai-api-base-urlhttphostdockerinternal8642v1
  text: e OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1 \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: e-openai-api-keyyour-secret-key
  text: e OPENAI_API_KEY=your-secret-key \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: add-hosthostdockerinternalhost-gateway
  text: add-host=host.docker.internal:host-gateway \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: v-open-webuiappbackenddata
  text: v open-webui:/app/backend/data \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: name-open-webui
  text: name open-webui \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: restart-always
  text: restart always \
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: '30008080'
  text: '"3000:8080"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: open-webuiappbackenddata
  text: open-webui:/app/backend/data
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: openai-api-base-urlhttphostdockerinternal8642v1
  text: OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: openai-api-keyyour-secret-key
  text: OPENAI_API_KEY=your-secret-key
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: hostdockerinternalhost-gateway
  text: '"host.docker.internal:host-gateway"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: url-httphostdockerinternal8642v1
  text: 'URL: http://host.docker.internal:8642/v1'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: api-key-your-key-or-any-non-empty-value-eg-not-needed
  text: 'API Key: your key or any non-empty value (e.g., not-needed)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: click-the-checkmark-to-verify-the-connection
  text: Click the **checkmark** to verify the connection
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: check-the-url-has-v1-suffix-httphostdockerinternal86
  text: 'Check the URL has /v1 suffix: http://host.docker.internal:8642/v1 (not just
    :8642)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: verify-the-gateway-is-running-curl-httplocalhost8642he
  text: 'Verify the gateway is running: curl http://localhost:8642/health should return
    {"status": "ok"}'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: check-model-listing-curl-httplocalhost8642v1models-sh
  text: 'Check model listing: curl http://localhost:8642/v1/models should return a
    list with hermes-agent'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: docker-networking-from-inside-docker-localhost-means-the-c
  text: 'Docker networking: From inside Docker, localhost means the container, not
    your host. Use host.docker.internal or --network=host.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: 1-enable-the-api-server
  text: 1. Enable the API server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: 2-start-hermes-agent-gateway
  text: 2. Start Hermes Agent gateway
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: 3-start-open-webui
  text: 3. Start Open WebUI
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: 4-open-the-ui
  text: 4. Open the UI
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: docker-compose-setupdocker-compose-setup
  text: '[Docker Compose Setup](#docker-compose-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: configuring-via-the-admin-uiconfiguring-via-the-admin-ui
  text: '[Configuring via the Admin UI](#configuring-via-the-admin-ui)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: api-type-chat-completions-vs-responsesapi-type-chat-com
  text: '[API Type: Chat Completions vs Responses](#api-type-chat-completions-vs-responses)[](#using-chat-completions-recommended)[](#using-responses-api)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: using-chat-completions-recommended
  text: Using Chat Completions (recommended)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: using-responses-api
  text: Using Responses API
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: how-it-workshow-it-works
  text: '[How It Works](#how-it-works)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: configuration-referenceconfiguration-referenceherme
  text: '[Configuration Reference](#configuration-reference)[](#hermes-agent-api-server)[](#open-webui)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: hermes-agent-api-server
  text: Hermes Agent (API server)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: open-webui
  text: Open WebUI
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: troubleshootingtroubleshootingno-models-appear-in-t
  text: '[Troubleshooting](#troubleshooting)[](#no-models-appear-in-the-dropdown)[](#connection-test-passes-but-no-models-load)[](#response-takes-a-long-time)[](#invalid-api-key-errors)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: no-models-appear-in-the-dropdown
  text: No models appear in the dropdown
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: connection-test-passes-but-no-models-load
  text: Connection test passes but no models load
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: response-takes-a-long-time
  text: Response takes a long time
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: invalid-api-key-errors
  text: '"Invalid API key" errors'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: multi-user-setup-with-profilesmulti-user-setup-with-prof
  text: '[Multi-User Setup with Profiles](#multi-user-setup-with-profiles)[](#1-create-profiles-and-configure-api-servers)[](#2-start-each-gateway)[](#3-add-connections-in-open-webui)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: 1-create-profiles-and-configure-api-servers
  text: 1. Create profiles and configure API servers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: 2-start-each-gateway
  text: 2. Start each gateway
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: 3-add-connections-in-open-webui
  text: 3. Add connections in Open WebUI
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: linux-docker-no-docker-desktoplinux-docker-no-docker-d
  text: '[Linux Docker (no Docker Desktop)](#linux-docker-no-docker-desktop)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.open-webui-integration
    path: entities/open-webui-integration.md
- id: receive-messages-via-a-persistent-websocket-connection-to-th
  text: Receive messages via a persistent WebSocket connection to the QQ Gateway
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: send-text-and-markdown-replies-via-the-rest-api
  text: Send text and markdown replies via the REST API
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: download-and-process-images-voice-messages-and-file-attach
  text: Download and process images, voice messages, and file attachments
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: transcribe-voice-messages-using-tencents-built-in-asr-or-a
  text: Transcribe voice messages using Tencent's built-in ASR or a configurable STT
    provider
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: create-a-new-application-and-note-your-app-id-and-app-secret
  text: Create a new application and note your App ID and App Secret
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: enable-the-required-intents-c2c-messages-group--messages
  text: 'Enable the required intents: C2C messages, Group @-messages, Guild messages'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: configure-your-bot-in-sandbox-mode-for-testing-or-publish-f
  text: Configure your bot in sandbox mode for testing, or publish for production
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: user-openid-1
  text: '"user_openid_1"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: group-openid-1
  text: '"group_openid_1"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: zhipuglm-zai-default-provider-uses-glm-asr-model
  text: 'Zhipu/GLM (zai): Default provider, uses glm-asr model'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: openai-whisper-set-qq-stt-base-url-and-qq-stt-model
  text: 'OpenAI Whisper: Set QQ_STT_BASE_URL and QQ_STT_MODEL'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: any-openai-compatible-stt-endpoint
  text: Any OpenAI-compatible STT endpoint
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: invalid-app-id-secret-double-check-your-credentials-at-q
  text: "Invalid App ID / Secret \u2014 Double-check your credentials at q.qq.com"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: missing-permissions-ensure-the-bot-has-the-required-intent
  text: "Missing permissions \u2014 Ensure the bot has the required intents enabled"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: sandbox-only-bot-if-the-bot-is-in-sandbox-mode-it-can-onl
  text: "Sandbox-only bot \u2014 If the bot is in sandbox mode, it can only receive\
    \ messages from QQ's sandbox test channel"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: verify-the-bots-intents-are-enabled-at-qqqcom
  text: Verify the bot's intents are enabled at q.qq.com
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: check-qq-allowed-users-if-dm-access-is-restricted
  text: Check QQ_ALLOWED_USERS if DM access is restricted
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: for-group-messages-ensure-the-bot-is-mentioned-group-poli
  text: For group messages, ensure the bot is @mentioned (group policy may require
    allowlisting)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: check-qqbot-home-channel-for-cronnotification-delivery
  text: Check QQBOT_HOME_CHANNEL for cron/notification delivery
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: ensure-aiohttp-and-httpx-are-installed-pip-install-aiohttp
  text: 'Ensure aiohttp and httpx are installed: pip install aiohttp httpx'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: check-network-connectivity-to-apisgroupqqcom-and-the-webs
  text: Check network connectivity to api.sgroup.qq.com and the WebSocket gateway
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: review-gateway-logs-for-detailed-error-messages-and-reconnec
  text: Review gateway logs for detailed error messages and reconnect behavior
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: interactive-setup
  text: Interactive setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: manual-configuration
  text: Manual configuration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.email-setup
    path: entities/email-setup.md
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: advanced-configurationadvanced-configuration
  text: '[Advanced Configuration](#advanced-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: voice-messages-sttvoice-messages-stt
  text: '[Voice Messages (STT)](#voice-messages-stt)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: troubleshootingtroubleshootingbot-disconnects-immed
  text: '[Troubleshooting](#troubleshooting)[](#bot-disconnects-immediately-quick-disconnect)[](#voice-messages-not-transcribed)[](#messages-not-delivered)[](#connection-errors)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: bot-disconnects-immediately-quick-disconnect
  text: Bot disconnects immediately (quick disconnect)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: voice-messages-not-transcribed
  text: Voice messages not transcribed
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: messages-not-delivered
  text: Messages not delivered
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: connection-errors
  text: Connection errors
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.qq-bot
    path: entities/qq-bot.md
- id: a-mac-always-on-running-bluebubbles-server
  text: A Mac (always on) running BlueBubbles Server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: apple-id-signed-into-messagesapp-on-that-mac
  text: Apple ID signed into Messages.app on that Mac
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: bluebubbles-server-v100-webhooks-require-this-version
  text: BlueBubbles Server v1.0.0+ (webhooks require this version)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: network-connectivity-between-hermes-and-the-bluebubbles-serv
  text: Network connectivity between Hermes and the BlueBubbles server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: server-url-eg-http1921681101234
  text: Server URL (e.g., http://192.168.1.10:1234)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: server-password
  text: Server Password
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: inbound-bluebubbles-sends-webhook-events-to-a-local-listene
  text: "Inbound: BlueBubbles sends webhook events to a local listener when new messages\
    \ arrive. No polling \u2014 instant delivery."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: outbound-hermes-sends-messages-via-the-bluebubbles-rest-api
  text: 'Outbound: Hermes sends messages via the BlueBubbles REST API.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: media-images-voice-messages-videos-and-documents-are-sup
  text: 'Media: Images, voice messages, videos, and documents are supported in both
    directions. Inbound attachments are downloaded and cached locally for the agent
    to process.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: images-photos-appear-natively-in-the-imessage-conversation
  text: 'Images: Photos appear natively in the iMessage conversation'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: voice-messages-audio-files-sent-as-imessage-voice-messages
  text: 'Voice messages: Audio files sent as iMessage voice messages'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: videos-video-attachments
  text: 'Videos: Video attachments'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: documents-files-sent-as-imessage-attachments
  text: 'Documents: Files sent as iMessage attachments'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: tapback-reactions
  text: Tapback reactions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: typing-indicators
  text: Typing indicators
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: read-receipts
  text: Read receipts
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: creating-new-chats-by-address
  text: Creating new chats by address
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: verify-the-server-url-is-correct-and-the-mac-is-on
  text: Verify the server URL is correct and the Mac is on
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: check-that-bluebubbles-server-is-running
  text: Check that BlueBubbles Server is running
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: ensure-network-connectivity-firewall-port-forwarding
  text: Ensure network connectivity (firewall, port forwarding)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: check-that-the-webhook-is-registered-in-bluebubbles-server
  text: "Check that the webhook is registered in BlueBubbles Server \u2192 Settings\
    \ \u2192 API \u2192 Webhooks"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: verify-the-webhook-url-is-reachable-from-the-mac
  text: Verify the webhook URL is reachable from the Mac
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: check-hermes-logs-gateway-for-webhook-errors-or-hermes-logs
  text: Check hermes logs gateway for webhook errors (or hermes logs -f to follow
    in real-time)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: install-the-private-api-helper-docsbluebubblesapp
  text: 'Install the Private API helper: docs.bluebubbles.app'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: basic-messaging-works-without-it-only-reactions-typing-a
  text: "Basic messaging works without it \u2014 only reactions, typing, and read\
    \ receipts require it"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: 1-install-bluebubbles-server
  text: 1. Install BlueBubbles Server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: 2-get-your-server-url-and-password
  text: 2. Get your Server URL and Password
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: 3-configure-hermes
  text: 3. Configure Hermes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: 4-authorize-users
  text: 4. Authorize Users
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: 5-start-the-gateway
  text: 5. Start the Gateway
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: featuresfeaturestext-messagingrich-mediat
  text: '[Features](#features)[](#text-messaging)[](#rich-media)[](#tapback-reactions)[](#typing-indicators)[](#read-receipts)[](#chat-addressing)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: text-messaging
  text: Text Messaging
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: rich-media
  text: Rich Media
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: chat-addressing
  text: Chat Addressing
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: private-apiprivate-api
  text: '[Private API](#private-api)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: troubleshootingtroubleshootingcannot-reach-server
  text: '[Troubleshooting](#troubleshooting)[](#cannot-reach-server)[](#messages-not-arriving)[](#private-api-helper-not-connected)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: cannot-reach-server
  text: '"Cannot reach server"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: messages-not-arriving
  text: Messages not arriving
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: private-api-helper-not-connected
  text: '"Private API helper not connected"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.bluebubbles-imessage
    path: entities/bluebubbles-imessage.md
- id: a-personal-wechat-account
  text: A personal WeChat account
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: python-packages-aiohttp-and-cryptography
  text: 'Python packages: aiohttp and cryptography'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: terminal-qr-rendering-is-included-when-hermes-is-installed-w
  text: Terminal QR rendering is included when Hermes is installed with the messaging
    extra
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: long-poll-transport-no-public-endpoint-webhook-or-websoc
  text: "Long-poll transport \u2014 no public endpoint, webhook, or WebSocket needed"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: qr-code-login-scan-to-connect-setup-via-hermes-gateway-set
  text: "QR code login \u2014 scan-to-connect setup via hermes gateway setup"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: dm-and-group-messaging-configurable-access-policies
  text: "DM and group messaging \u2014 configurable access policies"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: media-support-images-video-files-and-voice-messages
  text: "Media support \u2014 images, video, files, and voice messages"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: aes-128-ecb-encrypted-cdn-automatic-encryptiondecryption
  text: "AES-128-ECB encrypted CDN \u2014 automatic encryption/decryption for all\
    \ media transfers"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: context-token-persistence-disk-backed-reply-continuity-acr
  text: "Context token persistence \u2014 disk-backed reply continuity across restarts"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: markdown-formatting-preserves-markdown-including-headers
  text: "Markdown formatting \u2014 preserves Markdown, including headers, tables,\
    \ and code blocks, so WeChat clients that support Markdown can render it natively"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: smart-message-chunking-messages-stay-as-a-single-bubble-wh
  text: "Smart message chunking \u2014 messages stay as a single bubble when under\
    \ the limit; only oversized payloads split at logical boundaries"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: typing-indicators-shows-typing-status-in-the-wechat-cli
  text: "Typing indicators \u2014 shows \"typing\u2026\" status in the WeChat client\
    \ while the agent processes"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: ssrf-protection-outbound-media-urls-are-validated-before-d
  text: "SSRF protection \u2014 outbound media URLs are validated before download"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: message-deduplication-5-minute-sliding-window-prevents-dou
  text: "Message deduplication \u2014 5-minute sliding window prevents double-processing"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: automatic-retry-with-backoff-recovers-from-transient-api-e
  text: "Automatic retry with backoff \u2014 recovers from transient API errors"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: inbound-encrypted-media-is-downloaded-from-the-cdn-using-en
  text: 'Inbound: Encrypted media is downloaded from the CDN using encrypted_query_param
    URLs, then decrypted with AES-128-ECB using the per-file key provided in the message
    payload.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: outbound-files-are-encrypted-locally-with-a-random-aes-128
  text: 'Outbound: Files are encrypted locally with a random AES-128-ECB key, uploaded
    to the CDN, and the encrypted reference is included in the outbound message.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: the-aes-key-is-16-bytes-128-bit-keys-may-arrive-as-raw-ba
  text: "The AES key is 16 bytes (128-bit). Keys may arrive as raw base64 or hex-encoded\
    \ \u2014 the adapter handles both formats."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: this-requires-the-cryptography-python-package
  text: This requires the cryptography Python package.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: tokens-are-saved-per-accountpeer-to-hermesweixinaccoun
  text: Tokens are saved per account+peer to ~/.hermes/weixin/accounts/<account_id>.context-tokens.json
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: on-startup-previously-saved-tokens-are-restored
  text: On startup, previously saved tokens are restored
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: every-inbound-message-updates-the-stored-token-for-that-send
  text: Every inbound message updates the stored token for that sender
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: outbound-messages-automatically-include-the-latest-context-t
  text: Outbound messages automatically include the latest context token
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: headers-stay-as-markdown-headings
  text: 'Headers stay as Markdown headings (#, ##, ...)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: tables-stay-as-markdown-tables
  text: Tables stay as Markdown tables
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: code-fences-stay-as-fenced-code-blocks
  text: Code fences stay as fenced code blocks
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: excessive-blank-lines-are-collapsed-to-double-newlines-outsi
  text: Excessive blank lines are collapsed to double newlines outside fenced code
    blocks
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: maximum-message-length-4000-characters
  text: 'Maximum message length: 4000 characters'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: messages-under-the-limit-stay-intact-even-when-they-contain
  text: Messages under the limit stay intact even when they contain multiple paragraphs
    or line breaks
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: oversized-messages-split-at-logical-boundaries-paragraphs
  text: Oversized messages split at logical boundaries (paragraphs, blank lines, code
    fences)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: code-fences-are-kept-intact-whenever-possible-never-split-m
  text: Code fences are kept intact whenever possible (never split mid-block unless
    the fence itself exceeds the limit)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: oversized-individual-blocks-fall-back-to-the-base-adapters
  text: Oversized individual blocks fall back to the base adapter's truncation logic
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: a-03-s-inter-chunk-delay-prevents-wechat-rate-limit-drops-w
  text: A 0.3 s inter-chunk delay prevents WeChat rate-limit drops when multiple chunks
    are sent
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: 1-run-the-setup-wizard
  text: 1. Run the Setup Wizard
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: 2-configure-environment-variables
  text: 2. Configure Environment Variables
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: 3-start-the-gateway
  text: 3. Start the Gateway
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: featuresfeatures
  text: '[Features](#features)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: configuration-optionsconfiguration-options
  text: '[Configuration Options](#configuration-options)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: access-policiesaccess-policiesdm-policygroup-p
  text: '[Access Policies](#access-policies)[](#dm-policy)[](#group-policy)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: group-policy
  text: Group Policy
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: media-supportmedia-supportinbound-receivingaes
  text: '[Media Support](#media-support)[](#inbound-receiving)[](#aes-128-ecb-encrypted-cdn)[](#outbound-sending)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: inbound-receiving
  text: Inbound (receiving)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: aes-128-ecb-encrypted-cdn
  text: AES-128-ECB Encrypted CDN
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: outbound-sending
  text: Outbound (sending)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: context-token-persistencecontext-token-persistence
  text: '[Context Token Persistence](#context-token-persistence)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: markdown-formattingmarkdown-formatting
  text: '[Markdown Formatting](#markdown-formatting)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: message-chunkingmessage-chunking
  text: '[Message Chunking](#message-chunking)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: typing-indicatorstyping-indicators
  text: '[Typing Indicators](#typing-indicators)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: long-poll-connectionlong-poll-connectionhow-it-work
  text: '[Long-Poll Connection](#long-poll-connection)[](#how-it-works)[](#retry-behavior)[](#deduplication)[](#token-lock)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: how-it-works
  text: How It Works
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: retry-behavior
  text: Retry Behavior
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: deduplication
  text: Deduplication
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: token-lock
  text: Token Lock
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
- id: all-environment-variablesall-environment-variables
  text: '[All Environment Variables](#all-environment-variables)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: troubleshootingtroubleshooting
  text: '[Troubleshooting](#troubleshooting)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.weixin-wechat
    path: entities/weixin-wechat.md
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
  - sourceId: entity.email-setup
    path: entities/email-setup.md
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.installation
    path: entities/installation.md
- id: a-wecom-organization-account
  text: A WeCom organization account
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: an-ai-bot-created-in-the-wecom-admin-console
  text: An AI Bot created in the WeCom Admin Console
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: the-bot-id-and-secret-from-the-bots-credentials-page
  text: The Bot ID and Secret from the bot's credentials page
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: python-packages-aiohttp-and-httpx
  text: 'Python packages: aiohttp and httpx'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: bot-credentials-via-qr-scan-or-manual-entry
  text: Bot credentials (via QR scan or manual entry)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: access-control-settings-allowlist-pairing-mode-or-open-ac
  text: Access control settings (allowlist, pairing mode, or open access)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: home-channel-for-notifications
  text: Home channel for notifications
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: websocket-transport-persistent-connection-no-public-endpo
  text: "WebSocket transport \u2014 persistent connection, no public endpoint needed"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: per-group-sender-allowlists-fine-grained-control-over-who
  text: "Per-group sender allowlists \u2014 fine-grained control over who can interact\
    \ in each group"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: media-support-images-files-voice-video-upload-and-downl
  text: "Media support \u2014 images, files, voice, video upload and download"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: aes-encrypted-media-automatic-decryption-for-inbound-attac
  text: "AES-encrypted media \u2014 automatic decryption for inbound attachments"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: quote-context-preserves-reply-threading
  text: "Quote context \u2014 preserves reply threading"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: markdown-rendering-rich-text-responses
  text: "Markdown rendering \u2014 rich text responses"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: reply-mode-streaming-correlates-responses-to-inbound-messa
  text: "Reply-mode streaming \u2014 correlates responses to inbound message context"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: auto-reconnect-exponential-backoff-on-connection-drops
  text: "Auto-reconnect \u2014 exponential backoff on connection drops"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: group-id-1
  text: '"group_id_1"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: group-id-2
  text: '"group_id_2"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: user-alice
  text: '"user_alice"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: user-bob
  text: '"user_bob"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: user-charlie
  text: '"user_charlie"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: user-admin
  text: '"user_admin"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: when-an-inbound-media-item-includes-an-aeskey-field-the-ada
  text: When an inbound media item includes an aeskey field, the adapter downloads
    the encrypted bytes and decrypts them using AES-256-CBC with PKCS#7 padding.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: the-aes-key-is-the-base64-decoded-value-of-the-aeskey-field
  text: The AES key is the base64-decoded value of the aeskey field (must be exactly
    32 bytes).
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: the-iv-is-derived-from-the-first-16-bytes-of-the-key
  text: The IV is derived from the first 16 bytes of the key.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: this-requires-the-cryptography-python-package-pip-install-c
  text: This requires the cryptography Python package (pip install cryptography).
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: images-10-mb-sent-as-file
  text: "Images > 10 MB \u2192 sent as file"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: videos-10-mb-sent-as-file
  text: "Videos > 10 MB \u2192 sent as file"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: voice-2-mb-sent-as-file
  text: "Voice > 2 MB \u2192 sent as file"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: non-amr-audio-sent-as-file-wecom-only-supports-amr-for-na
  text: "Non-AMR audio \u2192 sent as file (WeCom only supports AMR for native voice)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: step-1-create-an-ai-bot
  text: 'Step 1: Create an AI Bot'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: step-2-configure-hermes
  text: 'Step 2: Configure Hermes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: step-3-start-the-gateway
  text: 'Step 3: Start the gateway'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: access-policiesaccess-policiesdm-policygroup-p
  text: '[Access Policies](#access-policies)[](#dm-policy)[](#group-policy)[](#per-group-sender-allowlists)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: per-group-sender-allowlists
  text: Per-Group Sender Allowlists
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: media-supportmedia-supportinbound-receivingaes
  text: '[Media Support](#media-support)[](#inbound-receiving)[](#aes-encrypted-media-decryption)[](#outbound-sending)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: aes-encrypted-media-decryption
  text: AES-Encrypted Media Decryption
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: reply-mode-stream-responsesreply-mode-stream-responses
  text: '[Reply-Mode Stream Responses](#reply-mode-stream-responses)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: connection-and-reconnectionconnection-and-reconnection
  text: '[Connection and Reconnection](#connection-and-reconnection)[](#connection-lifecycle)[](#reconnection-behavior)[](#deduplication)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: connection-lifecycle
  text: Connection Lifecycle
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: reconnection-behavior
  text: Reconnection Behavior
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.wecom-enterprise-wechat
    path: entities/wecom-enterprise-wechat.md
- id: websocket-recommended-hermes-opens-the-outbound-connectio
  text: "websocket \u2014 recommended; Hermes opens the outbound connection and you\
    \ do not need a public webhook endpoint"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: webhook-useful-when-you-want-feishulark-to-push-events-in
  text: "webhook \u2014 useful when you want Feishu/Lark to push events into your\
    \ gateway over HTTP"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: feishu-httpsopenfeishucn
  text: 'Feishu: https://open.feishu.cn/'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: lark-httpsopenlarksuitecom
  text: 'Lark: https://open.larksuite.com/'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: create-a-new-app
  text: Create a new app.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: in-credentials-basic-info-copy-the-app-id-and-a
  text: In **Credentials & Basic Info**, copy the **App ID** and **App Secret**.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: enable-the-bot-capability-for-the-app
  text: Enable the **Bot** capability for the app.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: run-hermes-gateway-setup-select-feishu-lark-and-ente
  text: Run hermes gateway setup, select **Feishu / Lark**, and enter the credentials
    when prompted.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: feishu-for-feishu-china
  text: feishu for Feishu China
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: lark-for-lark-international
  text: lark for Lark international
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: button-clicks-become-card-button-key-value
  text: 'Button clicks become: /card button {"key": "value", ...}'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: the-actions-value-payload-from-the-card-definition-is-inclu
  text: The action's value payload from the card definition is included as JSON.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: card-actions-are-deduplicated-with-a-15-minute-window-to-pre
  text: Card actions are deduplicated with a 15-minute window to prevent double processing.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: fetches-the-document-content-and-comment-timeline-in-paralle
  text: Fetches the document content and comment timeline in parallel (20 messages
    for whole-doc threads, 12 for local-selection threads).
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: runs-the-agent-with-the-feishu-doc-feishu-drive-toolsets-s
  text: Runs the agent with the feishu_doc + feishu_drive toolsets scoped to that
    single comment session.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: chunks-replies-at-4000-chars-and-posts-them-back-as-threaded
  text: Chunks replies at 4000 chars and posts them back as threaded replies.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: caches-per-document-sessions-for-1-hour-with-a-50-message-ca
  text: Caches per-document sessions for 1 hour with a 50-message cap so follow-up
    comments on the same doc keep context.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: allowlist-a-static-list-of-users-tenants
  text: "allowlist \u2014 a static list of users / tenants."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: pairing-static-list-runtime-approved-store-useful-for-r
  text: "pairing \u2014 static list \u222A runtime-approved store. Useful for rollouts\
    \ where moderators can grant access live."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: subscribe-to-drivenoticecomment-add-v1-in-event-subscripti
  text: Subscribe to drive.notice.comment_add_v1 in Event Subscriptions.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: grant-the-docsdocreadonly-and-drivedrivereadonly-scopes
  text: Grant the docs:doc:readonly and drive:drive:readonly scopes so the handler
    can read document content.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: ogg-opus-uploaded-as-opus-audio
  text: ".ogg, .opus \u2192 uploaded as opus audio"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: mp4-mov-avi-m4v-uploaded-as-mp4-media
  text: ".mp4, .mov, .avi, .m4v \u2192 uploaded as mp4 media"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: pdf-docx-xlsx-pptx-uploaded-with-their-docume
  text: ".pdf, .doc(x), .xls(x), .ppt(x) \u2192 uploaded with their document type"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: everything-else-uploaded-as-a-generic-stream-file
  text: "Everything else \u2192 uploaded as a generic stream file"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: window-60-second-sliding-window
  text: 'Window: 60-second sliding window'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: limit-120-requests-per-window-per-app-id-path-ip-triple
  text: 'Limit: 120 requests per window per (app_id, path, IP) triple'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: tracking-cap-up-to-4096-unique-keys-tracked-prevents-unbou
  text: 'Tracking cap: Up to 4096 unique keys tracked (prevents unbounded memory growth)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: body-size-limit-1-mb-maximum
  text: 'Body size limit: 1 MB maximum'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: body-read-timeout-30-seconds
  text: 'Body read timeout: 30 seconds'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: content-type-enforcement-only-applicationjson-is-accepted
  text: 'Content-Type enforcement: Only application/json is accepted'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: ou-admin-open-id
  text: '"ou_admin_open_id"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: ou-user-open-id-1
  text: '"ou_user_open_id_1"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: ou-user-open-id-2
  text: '"ou_user_open_id_2"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: ou-blocked-user
  text: '"ou_blocked_user"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: recommended-scan-to-create-one-command
  text: 'Recommended: Scan-to-Create (one command)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: alternative-manual-setup
  text: 'Alternative: Manual Setup'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: step-2-choose-a-connection-modestep-2-choose-a-connecti
  text: '[Step 2: Choose a Connection Mode](#step-2-choose-a-connection-mode)[](#recommended-websocket-mode)[](#optional-webhook-mode)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: recommended-websocket-mode
  text: 'Recommended: WebSocket mode'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: optional-webhook-mode
  text: 'Optional: Webhook mode'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: step-3-configure-hermesstep-3-configure-hermesopti
  text: '[Step 3: Configure Hermes](#step-3-configure-hermes)[](#option-a-interactive-setup)[](#option-b-manual-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: option-a-interactive-setup
  text: 'Option A: Interactive Setup'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: option-b-manual-configuration
  text: 'Option B: Manual Configuration'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: step-4-start-the-gatewaystep-4-start-the-gateway
  text: '[Step 4: Start the Gateway](#step-4-start-the-gateway)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: home-chathome-chat
  text: '[Home Chat](#home-chat)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: securitysecurityuser-allowlistwebhook-encrypti
  text: '[Security](#security)[](#user-allowlist)[](#webhook-encryption-key)[](#verification-token)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: user-allowlist
  text: User Allowlist
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: webhook-encryption-key
  text: Webhook Encryption Key
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: verification-token
  text: Verification Token
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: group-message-policygroup-message-policybot-identit
  text: '[Group Message Policy](#group-message-policy)[](#bot-identity-for-mention-gating)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: bot-identity-for-mention-gating
  text: Bot Identity for @Mention Gating
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: interactive-card-actionsinteractive-card-actionsreq
  text: '[Interactive Card Actions](#interactive-card-actions)[](#required-feishu-app-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: required-feishu-app-configuration
  text: Required Feishu App Configuration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: document-comment-intelligent-replydocument-comment-intel
  text: '[Document Comment Intelligent Reply](#document-comment-intelligent-reply)[](#3-tier-access-control)[](#required-feishu-app-configuration-1)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: 3-tier-access-control
  text: 3-Tier Access Control
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: media-supportmedia-supportinbound-receivingout
  text: '[Media Support](#media-support)[](#inbound-receiving)[](#outbound-sending)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: markdown-rendering-and-post-fallbackmarkdown-rendering-a
  text: '[Markdown Rendering and Post Fallback](#markdown-rendering-and-post-fallback)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: processing-status-reactionsprocessing-status-reactions
  text: '[Processing Status Reactions](#processing-status-reactions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: burst-protection-and-batchingburst-protection-and-batchi
  text: '[Burst Protection and Batching](#burst-protection-and-batching)[](#text-batching)[](#media-batching)[](#per-chat-serialization)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: text-batching
  text: Text Batching
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: media-batching
  text: Media Batching
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: per-chat-serialization
  text: Per-Chat Serialization
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: rate-limiting-webhook-moderate-limiting-webhook-mode
  text: '[Rate Limiting (Webhook Mode)](#rate-limiting-webhook-mode)[](#webhook-anomaly-tracking)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: webhook-anomaly-tracking
  text: Webhook Anomaly Tracking
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: websocket-tuningwebsocket-tuning
  text: '[WebSocket Tuning](#websocket-tuning)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: per-group-access-controlper-group-access-control
  text: '[Per-Group Access Control](#per-group-access-control)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: deduplicationdeduplication
  text: '[Deduplication](#deduplication)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: toolsettoolset
  text: '[Toolset](#toolset)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.feishu-lark-setup
    path: entities/feishu-lark-setup.md
- id: each-dm-gets-its-own-session
  text: each DM gets its own session
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: each-user-in-a-shared-group-chat-gets-their-own-session-insi
  text: each user in a shared group chat gets their own session inside that group
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: dingtalk-stream-dingtalks-official-sdk-for-stream-mode-w
  text: "dingtalk-stream \u2014 DingTalk's official SDK for Stream Mode (WebSocket-based\
    \ real-time messaging)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: alibabacloud-dingtalk-dingtalk-openapi-sdk-for-ai-cards-e
  text: "alibabacloud-dingtalk \u2014 DingTalk OpenAPI SDK for AI Cards, emoji reactions,\
    \ and media downloads"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: app-name-eg-hermes-agent
  text: 'App Name: e.g., Hermes Agent'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: description-optional
  text: 'Description: optional'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: after-creating-navigate-to-credentials-basic-info-to
  text: After creating, navigate to **Credentials & Basic Info** to find your **Client
    ID** (AppKey) and **Client Secret** (AppSecret). Copy both.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: qr-code-device-flow-recommended-scan-the-qr-that-prints-i
  text: "QR-code device flow (recommended). Scan the QR that prints in your terminal\
    \ with the DingTalk mobile app \u2014 your Client ID and Client Secret are returned\
    \ automatically and written to ~/.hermes/.env. No developer-console trip needed."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: manual-paste-if-you-already-have-credentials-or-qr-scannin
  text: Manual paste. If you already have credentials (or QR scanning isn't convenient),
    paste your Client ID, Client Secret, and allowed user IDs when prompted.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: group-sessions-per-user-true-keeps-each-participants-conte
  text: 'group_sessions_per_user: true keeps each participant''s context isolated
    inside shared group chats'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: thinking-added-when-the-bot-starts-processing-your-messag
  text: "\U0001F914Thinking \u2014 added when the bot starts processing your message"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: done-added-when-the-response-is-complete-replaces-the-th
  text: "\U0001F973Done \u2014 added when the response is complete (replaces the Thinking\
    \ reaction)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: stream-mode-no-public-url-domain-name-or-webhook-server-n
  text: 'Stream Mode: No public URL, domain name, or webhook server needed. The connection
    is initiated from your machine via WebSocket, so it works behind NAT and firewalls.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: ai-cards-optionally-reply-with-rich-ai-cards-instead-of-pla
  text: 'AI Cards: Optionally reply with rich AI Cards instead of plain markdown.
    Configure via card_template_id.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: emoji-reactions-automatic-thinkingdone-reactions-for-pro
  text: "Emoji Reactions: Automatic \U0001F914Thinking/\U0001F973Done reactions for\
    \ processing status."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: markdown-responses-replies-are-formatted-in-dingtalks-mark
  text: 'Markdown responses: Replies are formatted in DingTalk''s markdown format
    for rich text display.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: media-support-images-and-files-in-incoming-messages-are-aut
  text: 'Media support: Images and files in incoming messages are automatically resolved
    and can be processed by vision tools.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: message-deduplication-the-adapter-deduplicates-messages-wit
  text: 'Message deduplication: The adapter deduplicates messages with a 5-minute
    window to prevent processing the same message twice.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: auto-reconnection-if-the-stream-connection-drops-the-adapt
  text: 'Auto-reconnection: If the stream connection drops, the adapter automatically
    reconnects with exponential backoff.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: message-length-limit-responses-are-capped-at-20000-charact
  text: 'Message length limit: Responses are capped at 20,000 characters per message.
    Longer responses are truncated.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: session-model-in-dingtalk
  text: Session Model in DingTalk
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: prerequisitesprerequisites
  text: '[Prerequisites](#prerequisites)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.installation
    path: entities/installation.md
- id: step-1-create-a-dingtalk-appstep-1-create-a-dingtalk-ap
  text: '[Step 1: Create a DingTalk App](#step-1-create-a-dingtalk-app)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: step-2-enable-the-robot-capabilitystep-2-enable-the-rob
  text: '[Step 2: Enable the Robot Capability](#step-2-enable-the-robot-capability)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: step-3-find-your-dingtalk-user-idstep-3-find-your-dingt
  text: '[Step 3: Find Your DingTalk User ID](#step-3-find-your-dingtalk-user-id)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: step-4-configure-hermes-agentstep-4-configure-hermes-ag
  text: '[Step 4: Configure Hermes Agent](#step-4-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: option-a-interactive-setup-recommended
  text: 'Option A: Interactive Setup (Recommended)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: start-the-gateway
  text: Start the Gateway
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: featuresfeaturesai-cardsemoji-reactionsdi
  text: '[Features](#features)[](#ai-cards)[](#emoji-reactions)[](#display-settings)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: emoji-reactions
  text: Emoji Reactions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: display-settings
  text: Display Settings
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: troubleshootingtroubleshootingbot-is-not-responding
  text: '[Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#dingtalk-stream-not-installed-error)[](#dingtalk_client_id-and-dingtalk_client_secret-required)[](#stream-disconnects--reconnection-loops)[](#bot-is-offline)[](#no-session_webhook-available)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: bot-is-not-responding-to-messages
  text: Bot is not responding to messages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: dingtalk-stream-not-installed-error
  text: '"dingtalk-stream not installed" error'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: dingtalk-client-id-and-dingtalk-client-secret-required
  text: '"DINGTALK_CLIENT_ID and DINGTALK_CLIENT_SECRET required"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: stream-disconnects-reconnection-loops
  text: Stream disconnects / reconnection loops
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: bot-is-offline
  text: Bot is offline
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: no-session-webhook-available
  text: '"No session_webhook available"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
- id: securitysecurity
  text: '[Security](#security)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
  - sourceId: entity.email-setup
    path: entities/email-setup.md
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: notesnotes
  text: '[Notes](#notes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.dingtalk-setup
    path: entities/dingtalk-setup.md
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: each-thread-gets-its-own-session-namespace
  text: each thread gets its own session namespace
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: each-user-in-a-shared-room-gets-their-own-session-inside-tha
  text: each user in a shared room gets their own session inside that room
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: users-share-context-growth-and-token-costs
  text: users share context growth and token costs
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: one-persons-long-tool-heavy-task-can-bloat-everyone-elses
  text: one person's long tool-heavy task can bloat everyone else's context
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: one-persons-in-flight-run-can-interrupt-another-persons-fo
  text: one person's in-flight run can interrupt another person's follow-up in the
    same room
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: abc123matrixorg
  text: '"!abc123:matrix.org"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: h-content-type-applicationjson
  text: 'H "Content-Type: application/json" \'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: group-sessions-per-user-true-keeps-each-participants-conte
  text: 'group_sessions_per_user: true keeps each participant''s context isolated
    inside shared rooms'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: stores-encryption-keys-in-hermesplatformsmatrixstore
  text: 'Stores encryption keys in ~/.hermes/platforms/matrix/store/ (legacy installs:
    ~/.hermes/matrix/store/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: uploads-device-keys-on-first-connection
  text: Uploads device keys on first connection
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: decrypts-incoming-messages-and-encrypts-outgoing-messages-au
  text: Decrypts incoming messages and encrypts outgoing messages automatically
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: auto-joins-encrypted-rooms-when-invited
  text: Auto-joins encrypted rooms when invited
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: api-server-host0000-binds-to-all-interfaces-so-the-docke
  text: API_SERVER_HOST=0.0.0.0 binds to all interfaces so the Docker container can
    reach it.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: api-server-key-is-required-for-non-loopback-binding-pick-a
  text: API_SERVER_KEY is required for non-loopback binding. Pick a strong random
    string.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: the-api-server-runs-on-port-8642-by-default-change-with-api
  text: The API server runs on port 8642 by default (change with API_SERVER_PORT if
    needed).
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: matrix-storeroothermesplatformsmatrixstore
  text: ./matrix-store:/root/.hermes/platforms/matrix/store
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: any-homeserver-works-with-synapse-conduit-dendrite-matri
  text: 'Any homeserver: Works with Synapse, Conduit, Dendrite, matrix.org, or any
    spec-compliant Matrix homeserver. No specific homeserver software required.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: federation-if-youre-on-a-federated-homeserver-the-bot-can
  text: "Federation: If you're on a federated homeserver, the bot can communicate\
    \ with users from other servers \u2014 just add their full @user:server IDs to\
    \ MATRIX_ALLOWED_USERS."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: auto-join-the-bot-automatically-accepts-room-invites-and-jo
  text: 'Auto-join: The bot automatically accepts room invites and joins. It starts
    responding immediately after joining.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: media-support-hermes-can-send-and-receive-images-audio-vi
  text: 'Media support: Hermes can send and receive images, audio, video, and file
    attachments. Media is uploaded to your homeserver using the Matrix content repository
    API.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: native-voice-messages-msc3245-the-matrix-adapter-automati
  text: "Native voice messages (MSC3245): The Matrix adapter automatically tags outgoing\
    \ voice messages with the org.matrix.msc3245.voice flag. This means TTS responses\
    \ and voice audio are rendered as native voice bubbles in Element and other clients\
    \ that support MSC3245, rather than as generic audio file attachments. Incoming\
    \ voice messages with the MSC3245 flag are also correctly identified and routed\
    \ to speech-to-text transcription. No configuration is needed \u2014 this works\
    \ automatically."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: session-model-in-matrix
  text: Session Model in Matrix
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: mention-and-threading-configuration
  text: Mention and Threading Configuration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: step-1-create-a-bot-accountstep-1-create-a-bot-account
  text: '[Step 1: Create a Bot Account](#step-1-create-a-bot-account)[](#option-a-register-on-your-homeserver-recommended)[](#option-b-use-matrixorg-or-another-public-homeserver)[](#option-c-use-your-own-account)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: option-a-register-on-your-homeserver-recommended
  text: 'Option A: Register on Your Homeserver (Recommended)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: option-b-use-matrixorg-or-another-public-homeserver
  text: 'Option B: Use matrix.org or Another Public Homeserver'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: option-c-use-your-own-account
  text: 'Option C: Use Your Own Account'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: step-2-get-an-access-tokenstep-2-get-an-access-token
  text: '[Step 2: Get an Access Token](#step-2-get-an-access-token)[](#option-a-access-token-recommended)[](#option-b-password-login)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: option-a-access-token-recommended
  text: 'Option A: Access Token (Recommended)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: option-b-password-login
  text: 'Option B: Password Login'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: step-3-find-your-matrix-user-idstep-3-find-your-matrix
  text: '[Step 3: Find Your Matrix User ID](#step-3-find-your-matrix-user-id)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: end-to-end-encryption-e2eeend-to-end-encryption-e2ee
  text: '[End-to-End Encryption (E2EE)](#end-to-end-encryption-e2ee)[](#requirements)[](#enable-e2ee)[](#cross-signing-verification-recommended)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: requirements
  text: Requirements
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: enable-e2ee
  text: Enable E2EE
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: cross-signing-verification-recommended
  text: Cross-Signing Verification (Recommended)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: home-roomhome-roomusing-the-slash-commandmanua
  text: '[Home Room](#home-room)[](#using-the-slash-command)[](#manual-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: using-the-slash-command
  text: Using the Slash Command
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: troubleshootingtroubleshootingbot-is-not-responding
  text: '[Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#failed-to-authenticate--whoami-failed-on-startup)[](#mautrix-not-installed-error)[](#encryption-errors--could-not-decrypt-event)[](#upgrading-from-a-previous-version-with-e2ee)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: failed-to-authenticate-whoami-failed-on-startup
  text: '"Failed to authenticate" / "whoami failed" on startup'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: mautrix-not-installed-error
  text: '"mautrix not installed" error'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: encryption-errors-could-not-decrypt-event
  text: Encryption errors / "could not decrypt event"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: upgrading-from-a-previous-version-with-e2ee
  text: Upgrading from a previous version with E2EE
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: proxy-mode-e2ee-on-macosproxy-mode-e2ee-on-macosh
  text: '[Proxy Mode (E2EE on macOS)](#proxy-mode-e2ee-on-macos)[](#how-it-works)[](#step-1-configure-the-host-macos)[](#step-2-configure-the-docker-container-linux-vm)[](#step-3-start-both)[](#configuration-reference)[](#works-for-any-platform)[](#sync-issues--bot-falls-behind)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: step-1-configure-the-host-macos
  text: 'Step 1: Configure the Host (macOS)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: step-2-configure-the-docker-container-linux-vm
  text: 'Step 2: Configure the Docker Container (Linux VM)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: step-3-start-both
  text: 'Step 3: Start Both'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: configuration-reference
  text: Configuration Reference
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: works-for-any-platform
  text: Works for Any Platform
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: sync-issues-bot-falls-behind
  text: Sync issues / bot falls behind
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
- id: user-not-allowed-bot-ignores-you
  text: '"User not allowed" / Bot ignores you'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.matrix-setup
    path: entities/matrix-setup.md
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: each-user-in-a-shared-channel-gets-their-own-session-inside
  text: each user in a shared channel gets their own session inside that channel
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: one-persons-in-flight-run-can-interrupt-another-persons-fo
  text: one person's in-flight run can interrupt another person's follow-up in the
    same channel
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: username-eg-hermes
  text: 'Username: e.g., hermes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: display-name-eg-hermes-agent
  text: 'Display Name: e.g., Hermes Agent'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: role-member-is-sufficient
  text: 'Role: Member is sufficient'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: click-create-bot-account
  text: Click **Create Bot Account**.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: mattermost-will-display-the-bot-token-copy-it-immedia
  text: Mattermost will display the **bot token**. **Copy it immediately.**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: group-sessions-per-user-true-keeps-each-participants-conte
  text: 'group_sessions_per_user: true keeps each participant''s context isolated
    inside shared channels and threads'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: self-hosted-friendly-works-with-any-self-hosted-mattermost
  text: 'Self-hosted friendly: Works with any self-hosted Mattermost instance. No
    Mattermost Cloud account or subscription required.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: no-extra-dependencies-the-adapter-uses-aiohttp-for-http-and
  text: 'No extra dependencies: The adapter uses aiohttp for HTTP and WebSocket, which
    is already included with Hermes Agent.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: team-edition-compatible-works-with-both-mattermost-team-edi
  text: 'Team Edition compatible: Works with both Mattermost Team Edition (free) and
    Enterprise Edition.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: session-model-in-mattermost
  text: Session Model in Mattermost
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: step-1-enable-bot-accountsstep-1-enable-bot-accounts
  text: '[Step 1: Enable Bot Accounts](#step-1-enable-bot-accounts)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: step-2-create-a-bot-accountstep-2-create-a-bot-account
  text: '[Step 2: Create a Bot Account](#step-2-create-a-bot-account)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: step-3-add-the-bot-to-channelsstep-3-add-the-bot-to-cha
  text: '[Step 3: Add the Bot to Channels](#step-3-add-the-bot-to-channels)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: step-4-find-your-mattermost-user-idstep-4-find-your-mat
  text: '[Step 4: Find Your Mattermost User ID](#step-4-find-your-mattermost-user-id)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: step-5-configure-hermes-agentstep-5-configure-hermes-ag
  text: '[Step 5: Configure Hermes Agent](#step-5-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: home-channelhome-channelusing-the-slash-command
  text: '[Home Channel](#home-channel)[](#using-the-slash-command)[](#manual-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: reply-modereply-mode
  text: '[Reply Mode](#reply-mode)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: mention-behaviormention-behavior
  text: '[Mention Behavior](#mention-behavior)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: troubleshootingtroubleshootingbot-is-not-responding
  text: '[Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#403-forbidden-errors)[](#websocket-disconnects--reconnection-loops)[](#failed-to-authenticate-on-startup)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: 403-forbidden-errors
  text: 403 Forbidden errors
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: websocket-disconnects-reconnection-loops
  text: WebSocket disconnects / reconnection loops
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: failed-to-authenticate-on-startup
  text: '"Failed to authenticate" on startup'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
- id: per-channel-promptsper-channel-prompts
  text: '[Per-Channel Prompts](#per-channel-prompts)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.mattermost-setup
    path: entities/mattermost-setup.md
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: domain-optional-filter-by-entity-domain-light-switch
  text: "domain (optional) \u2014 Filter by entity domain: light, switch, climate,\
    \ sensor, binary_sensor, cover, fan, media_player, etc."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: area-optional-filter-by-arearoom-name-matches-against
  text: "area (optional) \u2014 Filter by area/room name (matches against friendly\
    \ names): living room, kitchen, bedroom, etc."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: entity-id-required-the-entity-to-query-eg-lightlivi
  text: "entity_id (required) \u2014 The entity to query, e.g., light.living_room,\
    \ climate.thermostat, sensor.temperature"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: domain-optional-filter-by-domain-eg-light-climate
  text: "domain (optional) \u2014 Filter by domain, e.g., light, climate, switch"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: domain-required-service-domain-light-switch-climate
  text: "domain (required) \u2014 Service domain: light, switch, climate, cover, media_player,\
    \ fan, scene, script"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: service-required-service-name-turn-on-turn-off-toggle
  text: "service (required) \u2014 Service name: turn_on, turn_off, toggle, set_temperature,\
    \ set_hvac_mode, open_cover, close_cover, set_volume_level"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: entity-id-optional-target-entity-eg-lightliving-roo
  text: "entity_id (optional) \u2014 Target entity, e.g., light.living_room"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: data-optional-additional-parameters-as-a-json-object
  text: "data (optional) \u2014 Additional parameters as a JSON object"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: binary-sensor
  text: binary_sensor
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: alarm-control-panel
  text: alarm_control_panel
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: sensorfront-door-battery
  text: sensor.front_door_battery
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: sensoruptime
  text: sensor.uptime
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: sensorcpu-usage
  text: sensor.cpu_usage
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: sensormemory-usage
  text: sensor.memory_usage
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: websocket-with-30-second-heartbeat-for-real-time-events
  text: WebSocket with 30-second heartbeat for real-time events
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: automatic-reconnection-with-backoff-5s-10s-30s-60s
  text: "Automatic reconnection with backoff: 5s \u2192 10s \u2192 30s \u2192 60s"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: rest-api-for-outbound-notifications-separate-session-to-avo
  text: REST API for outbound notifications (separate session to avoid WebSocket conflicts)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: authorization-ha-events-are-always-authorized-no-user-all
  text: "Authorization \u2014 HA events are always authorized (no user allowlist needed,\
    \ since the HASS_TOKEN authenticates the connection)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: shell-command-arbitrary-shell-commands
  text: "shell_command \u2014 arbitrary shell commands"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: command-line-sensorsswitches-that-execute-commands
  text: "command_line \u2014 sensors/switches that execute commands"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: python-script-scripted-python-execution
  text: "python_script \u2014 scripted Python execution"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: pyscript-broader-scripting-integration
  text: "pyscript \u2014 broader scripting integration"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: hassio-addon-control-host-shutdownreboot
  text: "hassio \u2014 addon control, host shutdown/reboot"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: rest-command-http-requests-from-ha-server-ssrf-vector
  text: "rest_command \u2014 HTTP requests from HA server (SSRF vector)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: 1-create-a-long-lived-access-token
  text: 1. Create a Long-Lived Access Token
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: available-toolsavailable-toolsha-list-entities
  text: '[Available Tools](#available-tools)[](#ha_list_entities)[](#ha_get_state)[](#ha_list_services)[](#ha_call_service)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: ha-list-entities
  text: ha_list_entities
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: ha-get-state
  text: ha_get_state
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: ha-list-services
  text: ha_list_services
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: ha-call-service
  text: ha_call_service
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: gateway-platform-real-time-eventsgateway-platform-real
  text: '[Gateway Platform: Real-Time Events](#gateway-platform-real-time-events)[](#event-filtering)[](#event-formatting)[](#agent-responses)[](#connection-management)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: event-filtering
  text: Event Filtering
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: event-formatting
  text: Event Formatting
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: agent-responses
  text: Agent Responses
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: connection-management
  text: Connection Management
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: example-automationsexample-automationsmorning-routi
  text: '[Example Automations](#example-automations)[](#morning-routine)[](#security-check)[](#reactive-automation-via-gateway-events)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: morning-routine
  text: Morning Routine
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: security-check
  text: Security Check
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: reactive-automation-via-gateway-events
  text: Reactive Automation (via Gateway Events)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.home-assistant-integration
    path: entities/home-assistant-integration.md
- id: twilio-account-sign-up-at-twiliocom-free-trial-available
  text: "Twilio account \u2014 Sign up at twilio.com (free trial available)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: a-twilio-phone-number-with-sms-capability
  text: A Twilio phone number with SMS capability
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: a-publicly-accessible-server-twilio-sends-webhooks-to-your
  text: "A publicly accessible server \u2014 Twilio sends webhooks to your server\
    \ when SMS arrives"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: aiohttp-pip-install-hermes-agentsms
  text: "aiohttp \u2014 pip install 'hermes-agent[sms]'"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: webhook-httpsyour-server8080webhookstwilio
  text: 'Webhook: https://your-server:8080/webhooks/twilio'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: http-method-post
  text: 'HTTP Method: POST'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: plain-text-only-markdown-is-automatically-stripped-since-s
  text: "Plain text only \u2014 Markdown is automatically stripped since SMS renders\
    \ it as literal characters"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: 1600-character-limit-longer-responses-are-split-across-mul
  text: "1600 character limit \u2014 Longer responses are split across multiple messages\
    \ at natural boundaries (newlines, then spaces)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: echo-prevention-messages-from-your-own-twilio-number-are-i
  text: "Echo prevention \u2014 Messages from your own Twilio number are ignored to\
    \ prevent loops"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: phone-number-redaction-phone-numbers-are-redacted-in-logs
  text: "Phone number redaction \u2014 Phone numbers are redacted in logs for privacy"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: interactive-setup-recommended
  text: Interactive setup (recommended)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: manual-setup
  text: Manual setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: step-3-configure-twilio-webhookstep-3-configure-twilio
  text: '[Step 3: Configure Twilio Webhook](#step-3-configure-twilio-webhook)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: sms-specific-behaviorsms-specific-behavior
  text: '[SMS-Specific Behavior](#sms-specific-behavior)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: securitysecuritywebhook-signature-validationus
  text: '[Security](#security)[](#webhook-signature-validation)[](#user-allowlists)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: webhook-signature-validation
  text: Webhook signature validation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: user-allowlists
  text: User allowlists
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: troubleshootingtroubleshootingmessages-not-arriving
  text: '[Troubleshooting](#troubleshooting)[](#messages-not-arriving)[](#replies-not-sending)[](#webhook-port-conflicts)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: replies-not-sending
  text: Replies not sending
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: webhook-port-conflicts
  text: Webhook port conflicts
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.sms-setup-twilio
    path: entities/sms-setup-twilio.md
- id: a-dedicated-email-account-for-your-hermes-agent-dont-use-y
  text: A dedicated email account for your Hermes agent (don't use your personal email)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: imap-enabled-on-the-email-account
  text: IMAP enabled on the email account
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: an-app-password-if-using-gmail-or-another-provider-with-2fa
  text: An app password if using Gmail or another provider with 2FA
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: imap-host-and-port-usually-port-993-with-ssl
  text: IMAP host and port (usually port 993 with SSL)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: smtp-host-and-port-usually-port-587-with-starttls
  text: SMTP host and port (usually port 587 with STARTTLS)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: whether-app-passwords-are-required
  text: Whether app passwords are required
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: images-jpeg-png-gif-webp-available-to-the-vision-tool
  text: "Images (JPEG, PNG, GIF, WebP) \u2192 available to the vision tool"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: documents-pdf-zip-etc-available-for-file-access
  text: "Documents (PDF, ZIP, etc.) \u2192 available for file access"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: html-only-emails-have-tags-stripped-for-plain-text-extract
  text: HTML-only emails** have tags stripped for plain text extraction
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: self-messages-are-filtered-out-to-prevent-reply-loops
  text: Self-messages** are filtered out to prevent reply loops
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: automatednoreply-senders-are-silently-ignored-noreply
  text: "Automated/noreply senders** are silently ignored \u2014 noreply@, mailer-daemon@,\
    \ bounce@, no-reply@, and emails with Auto-Submitted, Precedence: bulk, or List-Unsubscribe\
    \ headers"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: in-reply-to-and-references-headers-maintain-the-thread
  text: In-Reply-To and References headers maintain the thread
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: subject-line-preserved-with-re-prefix-no-double-re-re
  text: 'Subject line preserved with Re: prefix (no double Re: Re:)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: message-id-generated-with-the-agents-domain
  text: Message-ID generated with the agent's domain
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: responses-are-sent-as-plain-text-utf-8
  text: Responses are sent as plain text (UTF-8)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: use-app-passwords-instead-of-your-main-password-required-fo
  text: Use App Passwords instead of your main password (required for Gmail with 2FA)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: set-email-allowed-users-to-restrict-who-can-interact-with-th
  text: Set EMAIL_ALLOWED_USERS to restrict who can interact with the agent
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: the-password-is-stored-in-hermesenv-protect-this-file
  text: "The password is stored in ~/.hermes/.env \u2014 protect this file (chmod\
    \ 600)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: imap-uses-ssl-port-993-and-smtp-uses-starttls-port-587-b
  text: "IMAP uses SSL (port 993) and SMTP uses STARTTLS (port 587) by default \u2014\
    \ connections are encrypted"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: gmail-setup
  text: Gmail Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: outlook-microsoft-365
  text: Outlook / Microsoft 365
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: other-providers
  text: Other Providers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: step-1-configure-hermesstep-1-configure-hermesmanu
  text: '[Step 1: Configure Hermes](#step-1-configure-hermes)[](#manual-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: step-2-start-the-gatewaystep-2-start-the-gateway
  text: '[Step 2: Start the Gateway](#step-2-start-the-gateway)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: how-it-workshow-it-worksreceiving-messagessend
  text: '[How It Works](#how-it-works)[](#receiving-messages)[](#sending-replies)[](#file-attachments)[](#skipping-attachments)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: receiving-messages
  text: Receiving Messages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: sending-replies
  text: Sending Replies
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: file-attachments
  text: File Attachments
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: skipping-attachments
  text: Skipping Attachments
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: access-controlaccess-control
  text: '[Access Control](#access-control)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
- id: environment-variables-referenceenvironment-variables-ref
  text: '[Environment Variables Reference](#environment-variables-reference)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.email-setup
    path: entities/email-setup.md
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: signal-cli-java-based-signal-client-github
  text: "signal-cli \u2014 Java-based Signal client (GitHub)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: java-17-runtime-required-by-signal-cli
  text: "Java 17+ runtime \u2014 required by signal-cli"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: a-phone-number-with-signal-installed-for-linking-as-a-secon
  text: A phone number with Signal installed (for linking as a secondary device)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: images-png-jpeg-gif-webp-auto-detected-via-magic-bytes
  text: "Images \u2014 PNG, JPEG, GIF, WebP (auto-detected via magic bytes)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: audio-mp3-ogg-wav-m4a-voice-messages-transcribed-if-wh
  text: "Audio \u2014 MP3, OGG, WAV, M4A (voice messages transcribed if Whisper is\
    \ configured)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: documents-pdf-zip-and-other-file-types
  text: "Documents \u2014 PDF, ZIP, and other file types"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: images-send-image-file-sends-png-jpeg-gif-webp-as-nativ
  text: "Images \u2014 send_image_file sends PNG, JPEG, GIF, WebP as native Signal\
    \ attachments"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: voice-send-voice-sends-audio-files-ogg-mp3-wav-m4a-aa
  text: "Voice \u2014 send_voice sends audio files (OGG, MP3, WAV, M4A, AAC) as attachments"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: video-send-video-sends-mp4-video-files
  text: "Video \u2014 send_video sends MP4 video files"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: documents-send-document-sends-any-file-type-pdf-zip-etc
  text: "Documents \u2014 send_document sends any file type (PDF, ZIP, etc.)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: 15551234567-1554567
  text: "+15551234567 \u2192 +155****4567"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: this-applies-to-both-hermes-gateway-logs-and-the-global-reda
  text: This applies to both Hermes gateway logs and the global redaction system
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: note-to-self-messages-arrive-as-syncmessagesentmessage-en
  text: '"Note to Self" messages arrive as syncMessage.sentMessage envelopes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: the-adapter-detects-when-these-are-addressed-to-the-bots-ow
  text: The adapter detects when these are addressed to the bot's own account and
    processes them as regular inbound messages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: echo-back-protection-sent-timestamp-tracking-prevents-infi
  text: "Echo-back protection (sent-timestamp tracking) prevents infinite loops \u2014\
    \ the bot's own replies are filtered out automatically"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: the-connection-drops-with-exponential-backoff-2s-60s
  text: "The connection drops (with exponential backoff: 2s \u2192 60s)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: no-activity-is-detected-for-120-seconds-pings-signal-cli-to
  text: No activity is detected for 120 seconds (pings signal-cli to verify)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: phone-numbers-are-redacted-in-all-log-output
  text: Phone numbers are redacted in all log output
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: use-dm-pairing-or-explicit-allowlists-for-safe-onboarding-of
  text: Use DM pairing or explicit allowlists for safe onboarding of new users
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: keep-groups-disabled-unless-you-specifically-need-group-supp
  text: Keep groups disabled unless you specifically need group support, or allowlist
    only the groups you trust
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: signals-end-to-end-encryption-protects-message-content-in-t
  text: Signal's end-to-end encryption protects message content in transit
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: the-signal-cli-session-data-in-localsharesignal-cli-co
  text: "The signal-cli session data in ~/.local/share/signal-cli/ contains account\
    \ credentials \u2014 protect it like a password"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: installing-signal-cli
  text: Installing signal-cli
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: step-1-link-your-signal-accountstep-1-link-your-signal
  text: '[Step 1: Link Your Signal Account](#step-1-link-your-signal-account)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: step-2-start-the-signal-cli-daemonstep-2-start-the-sign
  text: '[Step 2: Start the signal-cli Daemon](#step-2-start-the-signal-cli-daemon)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: step-3-configure-hermesstep-3-configure-hermesmanu
  text: '[Step 3: Configure Hermes](#step-3-configure-hermes)[](#manual-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: access-controlaccess-controldm-accessgroup-acc
  text: '[Access Control](#access-control)[](#dm-access)[](#group-access)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: group-access
  text: Group Access
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: featuresfeaturesattachmentstyping-indicators
  text: '[Features](#features)[](#attachments)[](#typing-indicators)[](#phone-number-redaction)[](#note-to-self-single-number-setup)[](#health-monitoring)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: attachments
  text: Attachments
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: phone-number-redaction
  text: Phone Number Redaction
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: note-to-self-single-number-setup
  text: Note to Self (Single-Number Setup)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: health-monitoring
  text: Health Monitoring
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.signal-setup
    path: entities/signal-setup.md
- id: use-a-dedicated-phone-number-for-the-bot-not-your-personal
  text: Use a dedicated phone number for the bot (not your personal number)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: dont-send-bulkspam-messages-keep-usage-conversational
  text: "Don't send bulk/spam messages \u2014 keep usage conversational"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: dont-automate-outbound-messaging-to-people-who-havent-mess
  text: Don't automate outbound messaging to people who haven't messaged first
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: nodejs-v18-and-npm-the-whatsapp-bridge-runs-as-a-nodejs
  text: "Node.js v18+ and npm \u2014 the WhatsApp bridge runs as a Node.js process"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: a-phone-with-whatsapp-installed-for-scanning-the-qr-code
  text: A phone with WhatsApp installed (for scanning the QR code)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: unauthorized-dm-behavior-pair-is-the-global-default-unknow
  text: 'unauthorized_dm_behavior: pair is the global default. Unknown DM senders
    get a pairing code.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: whatsappunauthorized-dm-behavior-ignore-makes-whatsapp-sta
  text: 'whatsapp.unauthorized_dm_behavior: ignore makes WhatsApp stay silent for
    unauthorized DMs, which is usually the better choice for a private number.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: sessions-survive-restarts-you-dont-need-to-re-scan-the-qr
  text: "Sessions survive restarts \u2014 you don't need to re-scan the QR code every\
    \ time"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: the-session-data-includes-encryption-keys-and-device-credent
  text: The session data includes encryption keys and device credentials
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: do-not-share-or-commit-this-session-directory-it-grants-fu
  text: "Do not share or commit this session directory \u2014 it grants full access\
    \ to the WhatsApp account"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: incoming-voice-messages-ogg-opus-are-automatically-trans
  text: 'Incoming: Voice messages (.ogg opus) are automatically transcribed using
    the configured STT provider: local faster-whisper, Groq Whisper (GROQ_API_KEY),
    or OpenAI Whisper (VOICE_TOOLS_OPENAI_KEY)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: outgoing-tts-responses-are-sent-as-mp3-audio-file-attachmen
  text: 'Outgoing: TTS responses are sent as MP3 audio file attachments'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: agent-responses-are-prefixed-with-hermes-agent-by-defaul
  text: "Agent responses are prefixed with \"\u2695 Hermes Agent\" by default. You\
    \ can customize or disable this in config.yaml:"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: the-hermesplatformswhatsappsession-directory-contains
  text: "The ~/.hermes/platforms/whatsapp/session directory contains full session\
    \ credentials \u2014 protect it like a password"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: set-file-permissions-chmod-700-hermesplatformswhatsapp
  text: 'Set file permissions: chmod 700 ~/.hermes/platforms/whatsapp/session'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: use-a-dedicated-phone-number-for-the-bot-to-isolate-risk-fro
  text: Use a dedicated phone number for the bot to isolate risk from your personal
    account
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: if-you-suspect-compromise-unlink-the-device-from-whatsapp
  text: "If you suspect compromise, unlink the device from WhatsApp \u2192 Settings\
    \ \u2192 Linked Devices"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: phone-numbers-in-logs-are-partially-redacted-but-review-you
  text: Phone numbers in logs are partially redacted, but review your log retention
    policy
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: whatsapp-compatible-markdown
  text: WhatsApp-Compatible Markdown
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: tool-progress
  text: Tool Progress
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.whatsapp-setup
    path: entities/whatsapp-setup.md
- id: name-it-something-like-hermes-socket-the-name-doesnt-matte
  text: Name it something like hermes-socket (the name doesn't matter)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: add-the-connectionswrite-scope
  text: Add the connections:write scope
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: click-generate
  text: Click Generate
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: copy-the-token-it-starts-with-xapp--this-is-your-slack
  text: "Copy the token** \u2014 it starts with xapp-. This is your SLACK_APP_TOKEN"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: hey-hermes
  text: '"hey hermes"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: the-first-token-in-the-list-is-the-primary-token-used-for-t
  text: The first token in the list is the primary token, used for the Socket Mode
    connection (AsyncApp).
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: each-token-is-authenticated-via-authtest-on-startup-the-ga
  text: Each token is authenticated via auth.test on startup. The gateway maps each
    team_id to its own WebClient and bot_user_id.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: when-a-message-arrives-hermes-uses-the-correct-workspace-sp
  text: When a message arrives, Hermes uses the correct workspace-specific client
    to respond.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: the-primary-bot-user-id-from-the-first-token-is-used-for-b
  text: The primary bot_user_id (from the first token) is used for backward compatibility
    with features that expect a single bot identity.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: incoming-voiceaudio-messages-are-automatically-transcribed
  text: 'Incoming: Voice/audio messages are automatically transcribed using the configured
    STT provider: local faster-whisper, Groq Whisper (GROQ_API_KEY), or OpenAI Whisper
    (VOICE_TOOLS_OPENAI_KEY)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: outgoing-tts-responses-are-sent-as-audio-file-attachments
  text: 'Outgoing: TTS responses are sent as audio file attachments'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: tokens-should-be-stored-in-hermesenv-file-permissions
  text: Tokens should be stored in ~/.hermes/.env (file permissions 600)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: rotate-tokens-periodically-via-the-slack-app-settings
  text: Rotate tokens periodically via the Slack app settings
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: audit-who-has-access-to-your-hermes-config-directory
  text: Audit who has access to your Hermes config directory
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: socket-mode-means-no-public-endpoint-is-exposed-one-less-a
  text: "Socket Mode means no public endpoint is exposed \u2014 one less attack surface"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: thread-reply-behavior
  text: Thread & Reply Behavior
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: session-isolation
  text: Session Isolation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: mention-trigger-behavior
  text: Mention & Trigger Behavior
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: unauthorized-user-handling
  text: Unauthorized User Handling
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: voice-transcription
  text: Voice Transcription
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: home-channelhome-channel
  text: '[Home Channel](#home-channel)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: multi-workspace-supportmulti-workspace-supportconfi
  text: '[Multi-Workspace Support](#multi-workspace-support)[](#configuration)[](#oauth-token-file)[](#how-it-works)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: configuration
  text: Configuration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: oauth-token-file
  text: OAuth Token File
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: voice-messagesvoice-messages
  text: '[Voice Messages](#voice-messages)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: troubleshootingtroubleshootingquick-checklist
  text: '[Troubleshooting](#troubleshooting)[](#quick-checklist)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: quick-checklist
  text: Quick Checklist
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.slack-setup
    path: entities/slack-setup.md
- id: each-server-thread-gets-its-own-session-namespace
  text: each server thread gets its own session namespace
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: alice-interrupting-her-own-in-flight-request-only-affects-al
  text: Alice interrupting her own in-flight request only affects Alice's session
    in that channel
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: bob-can-keep-talking-in-the-same-channel-without-inheriting
  text: Bob can keep talking in the same channel without inheriting Alice's history
    or interrupting Alice's run
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: the-whole-room-shares-one-running-agent-slot-for-that-channe
  text: the whole room shares one running-agent slot for that channel/thread
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: follow-up-messages-from-different-people-can-interrupt-or-qu
  text: follow-up messages from different people can interrupt or queue behind each
    other
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: set-public-bot-to-on-required-to-use-the-discord-provided
  text: "Set Public Bot to ON \u2014 required to use the Discord-provided invite link\
    \ (recommended). This allows the Installation tab to generate a default authorization\
    \ URL."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: leave-require-oauth2-code-grant-set-to-off
  text: Leave Require OAuth2 Code Grant set to OFF.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: without-message-content-intent-your-bot-receives-message-ev
  text: "Without Message Content Intent, your bot receives message events but the\
    \ message text is empty \u2014 the bot literally cannot see what you typed."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: without-server-members-intent-the-bot-cannot-resolve-userna
  text: Without Server Members Intent, the bot cannot resolve usernames for the allowed
    users list and may fail to identify who is messaging it.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: if-your-bot-is-in-fewer-than-100-servers-you-can-simply-tog
  text: If your bot is in fewer than 100 servers, you can simply toggle intents on
    and off freely.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: if-your-bot-is-in-100-or-more-servers-discord-requires-you
  text: If your bot is in 100 or more servers, Discord requires you to submit a verification
    application to use privileged intents. For personal use, this is not a concern.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: scopes-select-bot-and-applicationscommands
  text: 'Scopes: select bot and applications.commands'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: permissions-select-the-permissions-listed-below
  text: 'Permissions: select the permissions listed below.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: view-channels-see-the-channels-it-has-access-to
  text: "View Channels \u2014 see the channels it has access to"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: send-messages-respond-to-your-messages
  text: "Send Messages \u2014 respond to your messages"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: embed-links-format-rich-responses
  text: "Embed Links \u2014 format rich responses"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: attach-files-send-images-audio-and-file-outputs
  text: "Attach Files \u2014 send images, audio, and file outputs"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: read-message-history-maintain-conversation-context
  text: "Read Message History \u2014 maintain conversation context"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: send-messages-in-threads-respond-in-thread-conversations
  text: "Send Messages in Threads \u2014 respond in thread conversations"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: add-reactions-react-to-messages-for-acknowledgment
  text: "Add Reactions \u2014 react to messages for acknowledgment"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: '1234567890'
  text: '1234567890'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: '9876543210'
  text: '9876543210'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: added-when-the-bot-starts-processing-your-message
  text: "\U0001F440 added when the bot starts processing your message"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: added-when-the-response-is-delivered-successfully
  text: "\u2705 added when the response is delivered successfully"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: added-if-an-error-occurs-during-processing
  text: "\u274C added if an error occurs during processing"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: 1234567890-bot-responds-inline-here
  text: '1234567890 # Bot responds inline here'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: exact-threadchannel-id-matches-win
  text: Exact thread/channel ID matches win.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: if-a-message-arrives-inside-a-thread-or-forum-post-and-that
  text: If a message arrives inside a thread or forum post and that thread has no
    explicit entry, Hermes falls back to the parent channel/forum ID.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: prompts-are-applied-ephemerally-at-runtime-so-changing-them
  text: Prompts are applied ephemerally at runtime, so changing them affects future
    turns immediately without rewriting past session history.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: off-no-progress-messages
  text: "off \u2014 no progress messages"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: new-only-show-the-first-tool-call-per-turn
  text: "new \u2014 only show the first tool call per turn"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: all-show-all-tool-calls-truncated-to-40-characters-in-gat
  text: "all \u2014 show all tool calls (truncated to 40 characters in gateway messages)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: verbose-show-full-tool-call-details-can-produce-long-mess
  text: "verbose \u2014 show full tool call details (can produce long messages)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: each-skill-becomes-a-discord-slash-command-eg-code-revi
  text: Each skill becomes a Discord slash command (e.g., /code-review, /ascii-art)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: skills-accept-an-optional-args-string-parameter
  text: Skills accept an optional args string parameter
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: discord-has-a-limit-of-100-application-commands-per-bot-if
  text: "Discord has a limit of 100 application commands per bot \u2014 if you have\
    \ more skills than available slots, extra skills are skipped with a warning in\
    \ the logs"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: skills-are-registered-during-bot-startup-alongside-built-in
  text: Skills are registered during bot startup alongside built-in commands like
    /model, /reset, and /background
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: incoming-voice-messages-are-automatically-transcribed-using
  text: 'Incoming voice messages are automatically transcribed using the configured
    STT provider: local faster-whisper (no key), Groq Whisper (GROQ_API_KEY), or OpenAI
    Whisper (VOICE_TOOLS_OPENAI_KEY).'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: text-to-speech-use-voice-tts-to-have-the-bot-send-spoken-a
  text: 'Text-to-speech: Use /voice tts to have the bot send spoken audio responses
    alongside text replies.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: discord-voice-channels-hermes-can-also-join-a-voice-channel
  text: 'Discord voice channels: Hermes can also join a voice channel, listen to users
    speaking, and talk back in the channel.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: voice-mode
  text: Voice Mode
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: use-voice-mode-with-hermes
  text: Use Voice Mode with Hermes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: thread-name-is-derived-from-the-first-line-of-the-message-m
  text: Thread name is derived from the first line of the message (markdown heading
    prefix stripped, capped at 100 chars). When the message is attachment-only, the
    filename is used as the fallback thread name.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: attachments-ride-along-on-the-starter-message-of-the-new-thr
  text: "Attachments ride along on the starter message of the new thread \u2014 no\
    \ separate upload step, no partial sends."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: one-call-one-thread-each-forum-send-creates-a-new-thread
  text: 'One call, one thread: each forum send creates a new thread. Successive sends
    to the same forum will therefore produce separate threads.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: detection-is-three-layered-the-channel-directory-cache-firs
  text: 'Detection is three-layered: the channel directory cache first, a process-local
    probe cache second, and a live GET /channels/{id} probe as a last resort (whose
    result is then memoized for the life of the process).'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: or-with-user-allowlist-a-user-is-authorized-if-their-id-is
  text: OR with user allowlist. A user is authorized if their ID is in DISCORD_ALLOWED_USERS
    or they have any role in DISCORD_ALLOWED_ROLES.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: server-members-intent-auto-enabled-when-discord-allowed-rol
  text: "Server Members Intent auto-enabled. When DISCORD_ALLOWED_ROLES is set, the\
    \ bot enables the Members intent on connect \u2014 required for Discord to send\
    \ role information with member records."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: role-ids-not-names-grab-them-from-discord-user-settings
  text: "Role IDs, not names. Grab them from Discord: User Settings \u2192 Advanced\
    \ \u2192 Developer Mode ON, then right-click any role \u2192 Copy Role ID."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: dm-fallback-in-dms-the-role-check-scans-mutual-guilds-a-us
  text: DM fallback. In DMs the role check scans mutual guilds; a user with an allowed
    role in any shared server is authorized in DMs too.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: discord-gateway-model
  text: Discord Gateway Model
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: session-model-in-discord
  text: Session Model in Discord
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: interrupts-and-concurrency
  text: Interrupts and Concurrency
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-1-create-a-discord-applicationstep-1-create-a-disc
  text: '[Step 1: Create a Discord Application](#step-1-create-a-discord-application)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-2-create-the-botstep-2-create-the-bot
  text: '[Step 2: Create the Bot](#step-2-create-the-bot)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-3-enable-privileged-gateway-intentsstep-3-enable-p
  text: '[Step 3: Enable Privileged Gateway Intents](#step-3-enable-privileged-gateway-intents)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-4-get-the-bot-tokenstep-4-get-the-bot-token
  text: '[Step 4: Get the Bot Token](#step-4-get-the-bot-token)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-5-generate-the-invite-urlstep-5-generate-the-invit
  text: '[Step 5: Generate the Invite URL](#step-5-generate-the-invite-url)[](#option-a-using-the-installation-tab-recommended)[](#option-b-manual-url)[](#required-permissions)[](#recommended-additional-permissions)[](#permission-integers)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: option-a-using-the-installation-tab-recommended
  text: 'Option A: Using the Installation Tab (Recommended)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: option-b-manual-url
  text: 'Option B: Manual URL'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: required-permissions
  text: Required Permissions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: recommended-additional-permissions
  text: Recommended Additional Permissions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: permission-integers
  text: Permission Integers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-6-invite-to-your-serverstep-6-invite-to-your-serve
  text: '[Step 6: Invite to Your Server](#step-6-invite-to-your-server)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-7-find-your-discord-user-idstep-7-find-your-discor
  text: '[Step 7: Find Your Discord User ID](#step-7-find-your-discord-user-id)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: step-8-configure-hermes-agentstep-8-configure-hermes-ag
  text: '[Step 8: Configure Hermes Agent](#step-8-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: configuration-referenceconfiguration-referenceenvir
  text: '[Configuration Reference](#configuration-reference)[](#environment-variables-env)[](#config-file-configyaml)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: environment-variables-env
  text: Environment Variables (.env)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: config-file-configyaml
  text: Config File (config.yaml)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: interactive-model-pickerinteractive-model-picker
  text: '[Interactive Model Picker](#interactive-model-picker)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: native-slash-commands-for-skillsnative-slash-commands-fo
  text: '[Native Slash Commands for Skills](#native-slash-commands-for-skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: forum-channelsforum-channels
  text: '[Forum Channels](#forum-channels)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: troubleshootingtroubleshootingbot-is-online-but-not
  text: '[Troubleshooting](#troubleshooting)[](#bot-is-online-but-not-responding-to-messages)[](#disallowed-intents-error-on-startup)[](#bot-cant-see-messages-in-a-specific-channel)[](#403-forbidden-errors)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)[](#people-in-the-same-channel-are-sharing-context-unexpectedly)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: bot-is-online-but-not-responding-to-messages
  text: Bot is online but not responding to messages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: disallowed-intents-error-on-startup
  text: '"Disallowed Intents" error on startup'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: bot-cant-see-messages-in-a-specific-channel
  text: Bot can't see messages in a specific channel
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: people-in-the-same-channel-are-sharing-context-unexpectedly
  text: People in the same channel are sharing context unexpectedly
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: securitysecurityrole-based-access-controlmenti
  text: '[[[entity.security|Security]]](#[[entity.security|Security]])[](#role-based-access-control)[](#mention-control)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: role-based-access-control
  text: Role-Based Access Control
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: mention-control
  text: Mention Control
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.discord-setup
    path: entities/discord-setup.md
- id: messages-that-start-with-a-command
  text: Messages that start with a / command
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: replies-directly-to-the-bots-own-messages
  text: Replies directly to the bot's own messages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: service-messages-member-joinsleaves-pinned-messages-etc
  text: Service messages (member joins/leaves, pinned messages, etc.)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: messages-in-channels-where-the-bot-is-an-admin
  text: Messages in channels where the bot is an admin
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: the-agent-writes-a-file-inside-docker-to-workspacereportt
  text: the agent writes a file inside Docker to /workspace/report.txt
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: the-model-emits-mediaworkspacereporttxt
  text: the model emits MEDIA:/workspace/report.txt
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: telegram-delivery-fails-because-workspacereporttxt-only-e
  text: Telegram delivery fails because /workspace/report.txt only exists inside the
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: homeuserhermescachedocumentsoutput
  text: '"/home/user/.hermes/cache/documents:/output"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: write-files-inside-docker-to-output
  text: write files inside Docker to /output/...
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: emit-the-host-visible-path-in-media-for-example
  text: 'emit the host-visible path in MEDIA:, for example:'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: local-uses-faster-whisper-on-the-machine-running-hermes-no
  text: "local uses faster-whisper on the machine running Hermes \u2014 no API key\
    \ required"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: groq-uses-groq-whisper-and-requires-groq-api-key
  text: groq uses Groq Whisper and requires GROQ_API_KEY
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: openai-uses-openai-whisper-and-requires-voice-tools-openai-k
  text: openai uses OpenAI Whisper and requires VOICE_TOOLS_OPENAI_KEY
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: openai-and-elevenlabs-produce-opus-natively-no-extra-setup
  text: "OpenAI and ElevenLabs produce Opus natively \u2014 no extra setup needed"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: edge-tts-the-default-free-provider-outputs-mp3-and-require
  text: 'Edge TTS (the default free provider) outputs MP3 and requires ffmpeg to convert
    to Opus:'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: slash-commands
  text: slash commands
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: replies-to-one-of-the-bots-messages
  text: replies to one of the bot's messages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: botusername-mentions
  text: '@botusername mentions'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: matches-for-one-of-your-configured-regex-wake-words-in-teleg
  text: matches for one of your configured regex wake words in telegram.mention_patterns
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: use-telegramignored-threads-to-keep-hermes-silent-in-specif
  text: Use telegram.ignored_threads to keep Hermes silent in specific Telegram forum
    topics, even when the group would otherwise allow free responses or mention-triggered
    replies
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: if-telegramrequire-mention-is-left-unset-or-false-hermes-k
  text: If telegram.require_mention is left unset or false, Hermes keeps the previous
    open-group behavior and responds to normal group messages it can see
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: schompyb
  text: '"^\\s*chompy\\b"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: patterns-use-python-regular-expressions
  text: Patterns use Python regular expressions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: matching-is-case-insensitive
  text: Matching is case-insensitive
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: patterns-are-checked-against-both-text-messages-and-media-ca
  text: Patterns are checked against both text messages and media captions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: invalid-regex-patterns-are-ignored-with-a-warning-in-the-gat
  text: Invalid regex patterns are ignored with a warning in the gateway logs rather
    than crashing the bot
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: if-you-want-a-pattern-to-match-only-at-the-start-of-a-messag
  text: If you want a pattern to match only at the start of a message, anchor it with
    ^
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: topic-website-work-on-your-production-web-service
  text: "Topic \"Website\" \u2014 work on your production web service"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: topic-research-literature-review-and-paper-exploration
  text: "Topic \"Research\" \u2014 literature review and paper exploration"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: topic-general-miscellaneous-tasks-and-quick-questions
  text: "Topic \"General\" \u2014 miscellaneous tasks and quick questions"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: chat-id-123456789-your-telegram-user-id
  text: 'chat_id: 123456789 # Your Telegram user ID'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: name-general
  text: 'name: General'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: name-website
  text: 'name: Website'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: name-research
  text: 'name: Research'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: engineering-topic-auto-loads-the-software-development-skil
  text: "Engineering topic \u2192 auto-loads the software-development skill"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: research-topic-auto-loads-the-arxiv-skill
  text: "Research topic \u2192 auto-loads the arxiv skill"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: general-topic-no-skill-general-purpose-assistant
  text: "General topic \u2192 no skill, general-purpose assistant"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: chat-id--1001234567890-supergroup-id
  text: 'chat_id: -1001234567890 # Supergroup ID'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: name-engineering
  text: 'name: Engineering'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: bot-api-94-feb-2026-private-chat-topics-bots-can-creat
  text: "Bot API 9.4 (Feb 2026): Private Chat Topics \u2014 bots can create forum\
    \ topics in 1-on-1 DM chats via createForumTopic. See Private Chat Topics above."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: privacy-policy-telegram-now-requires-bots-to-have-a-privacy
  text: 'Privacy policy: Telegram now requires bots to have a privacy policy. Set
    one via BotFather with /setprivacy_policy, or Telegram may auto-generate a placeholder.
    This is particularly important if your bot is public-facing.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: message-streaming-bot-api-9x-added-support-for-streaming-l
  text: 'Message streaming: Bot API 9.x added support for streaming long responses,
    which can improve perceived latency for lengthy agent replies.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: '149154167220'
  text: '"149.154.167.220"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: when-the-bot-starts-processing-your-message
  text: "\U0001F440 when the bot starts processing your message"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: when-the-response-is-delivered-successfully
  text: "\u2705 when the response is delivered successfully"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: if-an-error-occurs-during-processing
  text: "\u274C if an error occurs during processing"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: message-in-topic-42-inside-group--1001234567890-uses-topic
  text: "Message in topic 42 inside group -1001234567890 \u2192 uses topic 42's prompt"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: message-in-topic-99-no-explicit-entry-falls-back-to-grou
  text: "Message in topic 99 (no explicit entry) \u2192 falls back to group -1001234567890's\
    \ prompt"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: message-in-a-group-with-no-entry-no-channel-prompt-applied
  text: "Message in a group with no entry \u2192 no channel prompt applied"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: how-to-disable-privacy-mode
  text: How to disable privacy mode
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: step-4-find-your-user-idstep-4-find-your-user-id
  text: '[Step 4: Find Your User ID](#step-4-find-your-user-id)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: step-5-configure-hermesstep-5-configure-hermesopti
  text: '[Step 5: Configure Hermes](#step-5-configure-hermes)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: sending-generated-files-from-docker-backed-terminalssend
  text: '[Sending Generated Files from Docker-backed Terminals](#sending-generated-files-from-docker-backed-terminals)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: webhook-modewebhook-modeconfigurationcloud-dep
  text: '[Webhook Mode](#webhook-mode)[](#configuration)[](#cloud-deployment-example-flyio)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: cloud-deployment-example-flyio
  text: Cloud deployment example (Fly.io)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: proxy-supportproxy-support
  text: '[Proxy Support](#proxy-support)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: voice-messagesvoice-messagesincoming-voice-speech-t
  text: '[Voice Messages](#voice-messages)[](#incoming-voice-speech-to-text)[](#outgoing-voice-text-to-speech)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: incoming-voice-speech-to-text
  text: Incoming Voice (Speech-to-Text)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: outgoing-voice-text-to-speech
  text: Outgoing Voice (Text-to-Speech)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: group-chat-usagegroup-chat-usageexample-group-trigg
  text: '[Group Chat Usage](#group-chat-usage)[](#example-group-trigger-configuration)[](#notes-on-mention_patterns)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: example-group-trigger-configuration
  text: Example group trigger configuration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: notes-on-mention-patterns
  text: Notes on mention_patterns
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: private-chat-topics-bot-api-94private-chat-topics-bot
  text: '[Private Chat Topics (Bot API 9.4)](#private-chat-topics-bot-api-94)[](#use-case)[](#configuration-1)[](#how-it-works)[](#skill-binding)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: skill-binding
  text: Skill binding
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: group-forum-topic-skill-bindinggroup-forum-topic-skill-b
  text: '[Group Forum Topic Skill Binding](#group-forum-topic-skill-binding)[](#use-case-1)[](#configuration-2)[](#how-it-works-1)[](#differences-from-dm-topics)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: differences-from-dm-topics
  text: Differences from DM Topics
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: recent-bot-api-featuresrecent-bot-api-features
  text: '[Recent Bot API Features](#recent-bot-api-features)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: dns-over-https-fallback-ipsdns-over-https-fallback-ips
  text: '[DNS-over-HTTPS Fallback IPs](#dns-over-https-fallback-ips)[](#how-it-works-2)[](#configuration-3)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: proxy-supportproxy-support-1supported-variables
  text: '[Proxy Support](#proxy-support-1)[](#supported-variables)[](#configuration-4)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: supported-variables
  text: Supported variables
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: message-reactionsmessage-reactions
  text: '[Message Reactions](#message-reactions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: exec-approvalexec-approval
  text: '[Exec Approval](#exec-approval)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: securitysecurity
  text: '[[[entity.security|Security]]](#[[entity.security|Security]])'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.telegram-setup
    path: entities/telegram-setup.md
- id: in-progress-terminal-commands-are-killed-immediately-sigter
  text: In-progress terminal commands are killed immediately (SIGTERM, then SIGKILL
    after 1s)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: tool-calls-are-cancelled-only-the-currently-executing-one
  text: "Tool calls are cancelled \u2014 only the currently-executing one runs, the\
    \ rest are skipped"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: multiple-messages-are-combined-messages-sent-during-interr
  text: "Multiple messages are combined \u2014 messages sent during interruption are\
    \ joined into one prompt"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: stop-command-interrupts-without-queuing-a-follow-up-messa
  text: "/stop command \u2014 interrupts without queuing a follow-up message"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: isolated-session-the-background-agent-has-its-own-session
  text: "Isolated session \u2014 the background agent has its own session with its\
    \ own conversation history. It has no knowledge of your current chat context and\
    \ receives only the prompt you provide."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: same-configuration-inherits-your-model-provider-toolsets
  text: "Same configuration \u2014 inherits your model, provider, toolsets, reasoning\
    \ settings, and provider routing from the current gateway setup."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: non-blocking-your-main-chat-stays-fully-interactive-send
  text: "Non-blocking \u2014 your main chat stays fully interactive. Send messages,\
    \ run other commands, or start more background tasks while it works."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: result-delivery-when-the-task-finishes-the-result-is-sent
  text: "Result delivery \u2014 when the task finishes, the result is sent back to\
    \ the same chat or channel where you issued the command, prefixed with \"\u2705\
    \ Background task complete\". If it fails, you'll see \"\u274C Background task\
    \ failed\" with the error."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: server-monitoring-background-check-the-health-of-all-ser
  text: "Server monitoring \u2014 \"/background Check the health of all services and\
    \ alert me if anything is down\""
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: long-builds-background-build-and-deploy-the-staging-envi
  text: "Long builds \u2014 \"/background Build and deploy the staging environment\"\
    \ while you continue chatting"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: research-tasks-background-research-competitor-pricing-an
  text: "Research tasks \u2014 \"/background Research competitor pricing and summarize\
    \ in a table\""
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: file-operations-background-organize-the-photos-in-down
  text: "File operations \u2014 \"/background Organize the photos in ~/Downloads by\
    \ date into folders\""
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: path-your-full-shell-path-at-install-time-with-the-venv-b
  text: "PATH \u2014 your full shell PATH at install time, with the venv bin/ and\
    \ node_modules/.bin prepended. This ensures user-installed tools (Node.js, ffmpeg,\
    \ etc.) are available to gateway subprocesses like the WhatsApp bridge."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: virtual-env-points-to-the-python-virtualenv-so-tools-can-r
  text: "VIRTUAL_ENV \u2014 points to the Python virtualenv so tools can resolve packages\
    \ correctly."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: hermes-home-scopes-the-gateway-to-your-hermes-installation
  text: "HERMES_HOME \u2014 scopes the gateway to your Hermes installation."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: slack-setup
  text: Slack Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: whatsapp-setup
  text: WhatsApp Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: signal-setup
  text: Signal Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: sms-setup-twilio
  text: SMS Setup (Twilio)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: email-setup
  text: Email Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: home-assistant-integration
  text: Home Assistant Integration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: mattermost-setup
  text: Mattermost Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: matrix-setup
  text: Matrix Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: dingtalk-setup
  text: DingTalk Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: feishulark-setup
  text: Feishu/Lark Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: wecom-setup
  text: WeCom Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: wecom-callback-setup
  text: WeCom Callback Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: weixin-setup-wechat
  text: Weixin Setup (WeChat)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: bluebubbles-setup-imessage
  text: BlueBubbles Setup (iMessage)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: qqbot-setup
  text: QQBot Setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: open-webui-api-server
  text: Open WebUI + API Server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: session-persistence
  text: Session Persistence
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: reset-policies
  text: Reset Policies
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: securitysecuritydm-pairing-alternative-to-allowlist
  text: '[[[entity.security|Security]]](#[[entity.security|Security]])[](#dm-pairing-alternative-to-allowlists)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: dm-pairing-alternative-to-allowlists
  text: DM Pairing (Alternative to Allowlists)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: interrupting-the-agentinterrupting-the-agent
  text: '[Interrupting the Agent](#interrupting-the-agent)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: tool-progress-notificationstool-progress-notifications
  text: '[Tool Progress Notifications](#tool-progress-notifications)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: background-sessionsbackground-sessionshow-it-works
  text: '[Background Sessions](#background-sessions)[](#how-it-works)[](#background-process-notifications)[](#use-cases)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: background-process-notifications
  text: Background Process Notifications
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: service-managementservice-managementlinux-systemd
  text: '[Service Management](#service-management)[](#linux-systemd)[](#macos-launchd)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: linux-systemd
  text: Linux (systemd)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: macos-launchd
  text: macOS (launchd)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: platform-specific-toolsetsplatform-specific-toolsets
  text: '[Platform-Specific Toolsets](#platform-specific-toolsets)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
- id: next-stepsnext-steps
  text: '[Next Steps](#next-steps)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.messaging-gateway
    path: entities/messaging-gateway.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: mode-behavior
  text: 'Mode**: Behavior'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: manual-default-always-prompt-the-user-for-approval-on
  text: 'manual** (default)**: Always prompt the user for approval on dangerous commands'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: smart-use-an-auxiliary-llm-to-assess-risk-low-risk-com
  text: 'smart****: Use an auxiliary LLM to assess risk. Low-risk commands (e.g.,
    `python -c "print(''hello'')"`) are auto-approved. Genuinely dangerous commands
    are auto-denied. Uncertain cases escalate to a manual prompt.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: off-disable-all-approval-checks-equivalent-to-running
  text: "off****: Disable all approval checks \u2014 equivalent to running with `--yolo`.\
    \ All commands execute without prompts."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: pattern-description
  text: 'Pattern**: Description'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: rm--r-rm---recursive-recursive-delete
  text: '`rm -r` / `rm --recursive`**: Recursive delete'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: rm-delete-in-root-path
  text: '`rm ... /`**: Delete in root path'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: chmod-777666-ow-aw-worldother-writable-perm
  text: '`chmod 777/666` / `o+w` / `a+w`**: World/other-writable permissions'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: chmod---recursive-with-unsafe-perms-recursive-worldoth
  text: '`chmod --recursive` with unsafe perms**: Recursive world/other-writable (long
    flag)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: chown--r-root-chown---recursive-root-recursive-chow
  text: '`chown -R root` / `chown --recursive root`**: Recursive chown to root'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: mkfs-format-filesystem
  text: '`mkfs`**: Format filesystem'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: dd-if-disk-copy
  text: '`dd if=`**: Disk copy'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: devsd-write-to-block-device
  text: '`> /dev/sd`**: Write to block device'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: drop-tabledatabase-sql-drop
  text: '`DROP TABLE/DATABASE`**: SQL DROP'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: delete-from-without-where-sql-delete-without-where
  text: '`DELETE FROM` (without WHERE)**: SQL DELETE without WHERE'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: truncate-table-sql-truncate
  text: '`TRUNCATE TABLE`**: SQL TRUNCATE'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: etc-overwrite-system-config
  text: '`> /etc/`**: Overwrite system config'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: systemctl-stopdisablemask-stopdisable-system-service
  text: '`systemctl stop/disable/mask`**: Stop/disable system services'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: kill--9--1-kill-all-processes
  text: '`kill -9 -1`**: Kill all processes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: pkill--9-force-kill-processes
  text: '`pkill -9`**: Force kill processes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: fork-bomb-patterns-fork-bombs
  text: 'Fork bomb patterns**: Fork bombs'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: bash--c-sh--c-zsh--c-ksh--c-shell-command-e
  text: '`bash -c` / `sh -c` / `zsh -c` / `ksh -c`**: Shell command execution via
    `-c` flag (including combined flags like `-lc`)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: python--e-perl--e-ruby--e-node--c-script-ex
  text: '`python -e` / `perl -e` / `ruby -e` / `node -c`**: Script execution via `-e`/`-c`
    flag'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: curl-sh-wget
  text: '`curl ...**: sh` / `wget ...'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: bash-curl-sh-wget-execute-remote-scri
  text: '`bash <(curl ...)` / `sh <(wget ...)`**: Execute remote script via process
    substitution'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: tee-to-etc-ssh-hermesenv-overwrite-s
  text: '`tee` to `/etc/`, `~/.ssh/`, `~/.hermes/.env`**: Overwrite sensitive file
    via tee'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: to-etc-ssh-hermesenv-overwr
  text: '`>` / `>>` to `/etc/`, `~/.ssh/`, `~/.hermes/.env`**: Overwrite sensitive
    file via redirection'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: xargs-rm-xargs-with-rm
  text: '`xargs rm`**: xargs with rm'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: find--exec-rm-find--delete-find-with-destructive-ac
  text: '`find -exec rm` / `find -delete`**: Find with destructive actions'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: cpmvinstall-to-etc-copymove-file-into-system
  text: '`cp`/`mv`/`install` to `/etc/`**: Copy/move file into system config'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: sed--i-sed---in-place-on-etc-in-place-edit-of-s
  text: '`sed -i` / `sed --in-place` on `/etc/`**: In-place edit of system config'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: pkillkillall-hermesgateway-self-termination-prevent
  text: '`pkill`/`killall` hermes/gateway**: Self-termination prevention'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: gateway-run-with-disownnohupsetsid-prevents
  text: '`gateway run` with `&`/`disown`/`nohup`/`setsid`**: Prevents starting gateway
    outside service manager'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: once-allow-this-single-execution
  text: "once** \u2014 allow this single execution"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: session-allow-this-pattern-for-the-rest-of-the-session
  text: "session** \u2014 allow this pattern for the rest of the session"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: always-add-to-permanent-allowlist-saved-to-configyaml
  text: "always** \u2014 add to permanent allowlist (saved to `config.yaml`)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: deny-default-block-the-command
  text: "deny** (default) \u2014 block the command"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: reply-yes-y-approve-ok-or-go-to-appr
  text: Reply **yes**, **y**, **approve**, **ok**, or **go** to approve
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: reply-no-n-deny-or-cancel-to-deny
  text: Reply **no**, **n**, **deny**, or **cancel** to deny
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: pair-is-the-default-unauthorized-dms-get-a-pairing-code-r
  text: '`pair` is the default. Unauthorized DMs get a pairing code reply.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: ignore-silently-drops-unauthorized-dms
  text: '`ignore` silently drops unauthorized DMs.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: platform-sections-override-the-global-default-so-you-can-ke
  text: Platform sections override the global default, so you can keep pairing on
    Telegram while keeping WhatsApp silent.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: feature-details
  text: 'Feature**: Details'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: code-format-8-char-from-32-char-unambiguous-alphabet-no
  text: 'Code format**: 8-char from 32-char unambiguous alphabet (no 0/O/1/I)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: randomness-cryptographic-secretschoice
  text: 'Randomness**: Cryptographic (`secrets.choice()`)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: code-ttl-1-hour-expiry
  text: 'Code TTL**: 1 hour expiry'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: rate-limiting-1-request-per-user-per-10-minutes
  text: 'Rate limiting**: 1 request per user per 10 minutes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: pending-limit-max-3-pending-codes-per-platform
  text: 'Pending limit**: Max 3 pending codes per platform'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: lockout-5-failed-approval-attempts-1-hour-lockout
  text: "Lockout**: 5 failed approval attempts \u2192 1-hour lockout"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: file-security-chmod-0600-on-all-pairing-data-files
  text: 'File security**: `chmod 0600` on all pairing data files'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: logging-codes-are-never-logged-to-stdout
  text: 'Logging**: Codes are never logged to stdout'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: platform-pendingjson-pending-pairing-requests
  text: "`{platform}-pending.json` \u2014 pending pairing requests"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: platform-approvedjson-approved-users
  text: "`{platform}-approved.json` \u2014 approved users"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: rate-limitsjson-rate-limit-and-lockout-tracking
  text: "`_rate_limits.json` \u2014 rate limit and lockout tracking"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: persistent-mode-container-persistent-true-bind-mount
  text: 'Persistent mode** (`container_persistent: true`): Bind-mounts `/workspace`
    and `/root` from `~/.hermes/sandboxes/docker/<task_id>/`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: ephemeral-mode-container-persistent-false-uses-tmpfs
  text: "Ephemeral mode** (`container_persistent: false`): Uses tmpfs for workspace\
    \ \u2014 everything is lost on cleanup"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: backend-isolation-dangerous-cmd-check-best-fo
  text: Backend**, **Isolation**, **Dangerous Cmd Check**, **Best For**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: backend-local-isolation-none-runs-on-host
  text: "Backend**: **local**, **Isolation**: None \u2014 runs on host, **Dangerous\
    \ Cmd Check**: \u2705 Yes, **Best For**: Development, trusted users"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: backend-ssh-isolation-remote-machine-dangero
  text: "Backend**: **ssh**, **Isolation**: Remote machine, **Dangerous Cmd Check**:\
    \ \u2705 Yes, **Best For**: Running on a separate server"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: backend-docker-isolation-container-dangerous
  text: "Backend**: **docker**, **Isolation**: Container, **Dangerous Cmd Check**:\
    \ \u274C Skipped (container is boundary), **Best For**: Production gateway"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: backend-singularity-isolation-container-dang
  text: "Backend**: **singularity**, **Isolation**: Container, **Dangerous Cmd Check**:\
    \ \u274C Skipped, **Best For**: HPC environments"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: backend-modal-isolation-cloud-sandbox-danger
  text: "Backend**: **modal**, **Isolation**: Cloud sandbox, **Dangerous Cmd Check**:\
    \ \u274C Skipped, **Best For**: Scalable cloud isolation"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: backend-daytona-isolation-cloud-sandbox-dang
  text: "Backend**: **daytona**, **Isolation**: Cloud sandbox, **Dangerous Cmd Check**:\
    \ \u274C Skipped, **Best For**: Persistent cloud workspaces"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: name-tenor-api-key
  text: 'name: TENOR_API_KEY'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: my-custom-key
  text: MY_CUSTOM_KEY
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: another-token
  text: ANOTHER_TOKEN
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: path-google-tokenjson
  text: 'path: google_token.json'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: path-google-client-secretjson
  text: 'path: google_client_secret.json'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: docker-read-only-bind-mounts--v-hostcontainerro
  text: 'Docker**: Read-only bind mounts (`-v host:container:ro`)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: modal-mounted-at-sandbox-creation-synced-before-each-co
  text: 'Modal**: Mounted at sandbox creation + synced before each command (handles
    mid-session OAuth setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: local-no-action-needed-files-already-accessible
  text: 'Local**: No action needed (files already accessible)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: google-tokenjson
  text: google_token.json
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: my-custom-oauth-tokenjson
  text: my_custom_oauth_token.json
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: sandbox-default-filter-passthrough-override
  text: Sandbox**, **Default Filter**, **Passthrough Override**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: sandbox-execute-code-default-filter-blocks-var
  text: "Sandbox**: **execute\\_code**, **Default Filter**: Blocks vars containing\
    \ `KEY`, `TOKEN`, `SECRET`, `PASSWORD`, `CREDENTIAL`, `PASSWD`, `AUTH` in name;\
    \ only allows safe-prefix vars through, **Passthrough Override**: \u2705 Passthrough\
    \ vars bypass both checks"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: sandbox-terminal-local-default-filter-blocks
  text: "Sandbox**: **terminal** (local), **Default Filter**: Blocks explicit Hermes\
    \ infrastructure vars (provider keys, gateway tokens, tool API keys), **Passthrough\
    \ Override**: \u2705 Passthrough vars bypass the blocklist"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: sandbox-terminal-docker-default-filter-no-hos
  text: "Sandbox**: **terminal** (Docker), **Default Filter**: No host env vars by\
    \ default, **Passthrough Override**: \u2705 Passthrough vars + `docker_forward_env`\
    \ forwarded via `-e`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: sandbox-terminal-modal-default-filter-no-host
  text: "Sandbox**: **terminal** (Modal), **Default Filter**: No host env/files by\
    \ default, **Passthrough Override**: \u2705 Credential files mounted; env passthrough\
    \ via sync"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: sandbox-mcp-default-filter-blocks-everything-ex
  text: "Sandbox**: **MCP**, **Default Filter**: Blocks everything except safe system\
    \ vars + explicitly configured `env`, **Passthrough Override**: \u274C Not affected\
    \ by passthrough (use MCP `env` config instead)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: the-passthrough-only-affects-vars-you-or-your-skills-explici
  text: "The passthrough only affects vars you or your skills explicitly declare \u2014\
    \ the default security posture is unchanged for arbitrary LLM-generated code"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: credential-files-are-mounted-read-only-into-docker-conta
  text: Credential files are mounted **read-only** into Docker containers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: skills-guard-scans-skill-content-for-suspicious-env-access-p
  text: Skills Guard scans skill content for suspicious env access patterns before
    installation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: missingunset-vars-are-never-registered-you-cant-leak-what
  text: Missing/unset vars are never registered (you can't leak what doesn't exist)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: hermes-infrastructure-secrets-provider-api-keys-gateway-to
  text: "Hermes infrastructure secrets (provider API keys, gateway tokens) should\
    \ never be added to `env_passthrough` \u2014 they have dedicated mechanisms"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: github-pats-ghp
  text: GitHub PATs (`ghp_...`)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: openai-style-keys-sk
  text: OpenAI-style keys (`sk-...`)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: bearer-tokens
  text: Bearer tokens
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: token-key-api-key-password-secret-paramet
  text: '`token=`, `key=`, `API_KEY=`, `password=`, `secret=` parameters'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: internalcompanycom
  text: '"*.internal.company.com"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: adminexamplecom
  text: '"admin.example.com"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: etchermesblocked-sitestxt
  text: '"/etc/hermes/blocked-sites.txt"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: private-networks-rfc-1918-100008-172160012
  text: 'Private networks** (RFC 1918): `10.0.0.0/8`, `172.16.0.0/12`, `192.168.0.0/16`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: loopback-1270008-1
  text: 'Loopback**: `127.0.0.0/8`, `::1`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: link-local-1692540016-includes-cloud-metadata-at
  text: 'Link-local**: `169.254.0.0/16` (includes cloud metadata at `169.254.169.254`)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: cgnat-shared-address-space-rfc-6598-100640010
  text: 'CGNAT / shared address space** (RFC 6598): `100.64.0.0/10` (Tailscale, WireGuard
    VPNs)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: cloud-metadata-hostnames-metadatagoogleinternal-met
  text: 'Cloud metadata hostnames**: `metadata.google.internal`, `metadata.goog`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: reserved-multicast-and-unspecified-addresses
  text: Reserved, multicast, and unspecified addresses**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: homograph-url-spoofing-internationalized-domain-attacks
  text: Homograph URL spoofing (internationalized domain attacks)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: pipe-to-interpreter-patterns-curl-bash-wget-sh
  text: Pipe-to-interpreter patterns (`curl | bash`, `wget | sh`)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: terminal-injection-attacks
  text: Terminal injection attacks
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: instructions-to-ignoredisregard-prior-instructions
  text: Instructions to ignore/disregard prior instructions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: hidden-html-comments-with-suspicious-keywords
  text: Hidden HTML comments with suspicious keywords
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: attempts-to-read-secrets-env-credentials-netrc
  text: Attempts to read secrets (`.env`, `credentials`, `.netrc`)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: credential-exfiltration-via-curl
  text: Credential exfiltration via `curl`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: invisible-unicode-characters-zero-width-spaces-bidirection
  text: Invisible Unicode characters (zero-width spaces, bidirectional overrides)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.security
    path: entities/security.md
- id: file-purpose-discovery
  text: File**, **Purpose**, **Discovery**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: file-hermesmd-hermesmd-purpose-project
  text: 'File**: **.hermes.md** / **HERMES.md**, **Purpose**: Project instructions
    (highest priority), **Discovery**: Walks to git root'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: file-agentsmd-purpose-project-instructions-co
  text: 'File**: **AGENTS.md**, **Purpose**: Project instructions, conventions, architecture,
    **Discovery**: CWD at startup + subdirectories progressively'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: file-claudemd-purpose-claude-code-context-file
  text: 'File**: **CLAUDE.md**, **Purpose**: Claude Code context files (also detected),
    **Discovery**: CWD at startup + subdirectories progressively'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: file-soulmd-purpose-global-personality-and-ton
  text: 'File**: **SOUL.md**, **Purpose**: Global personality and tone customization
    for this Hermes instance, **Discovery**: `HERMES_HOME/SOUL.md` only'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: file-cursorrules-purpose-cursor-ide-coding-con
  text: 'File**: **.cursorrules**, **Purpose**: Cursor IDE coding conventions, **Discovery**:
    CWD only'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: file-cursorrulesmdc-purpose-cursor-ide-ru
  text: 'File**: **.cursor/rules/\*.mdc**, **Purpose**: Cursor IDE rule modules, **Discovery**:
    CWD only'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: no-system-prompt-bloat-subdirectory-hints-only-appear-wh
  text: "No system prompt bloat** \u2014 subdirectory hints only appear when needed"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: prompt-cache-preservation-the-system-prompt-stays-stable
  text: "Prompt cache preservation** \u2014 the system prompt stays stable across\
    \ turns"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: frontend-nextjs-14-with-app-router-in-frontend
  text: 'Frontend: Next.js 14 with App Router in `/frontend`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: backend-fastapi-in-backend-uses-sqlalchemy-orm
  text: 'Backend: FastAPI in `/backend`, uses SQLAlchemy ORM'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: database-postgresql-16
  text: 'Database: PostgreSQL 16'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: deployment-docker-compose-on-a-hetzner-vps
  text: 'Deployment: Docker Compose on a Hetzner VPS'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: use-typescript-strict-mode-for-all-frontend-code
  text: Use TypeScript strict mode for all frontend code
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: python-code-follows-pep-8-use-type-hints-everywhere
  text: Python code follows PEP 8, use type hints everywhere
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: all-api-endpoints-return-json-with-data-error-meta-sha
  text: All API endpoints return JSON with `{data, error, meta}` shape
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: tests-go-in-tests-directories-frontend-or-tests
  text: Tests go in `__tests__/` directories (frontend) or `tests/` (backend)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: never-modify-migration-files-directly-use-alembic-commands
  text: "Never modify migration files directly \u2014 use Alembic commands"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: the-envlocal-file-has-real-api-keys-dont-commit-it
  text: The `.env.local` file has real API keys, don't commit it
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: frontend-port-is-3000-backend-is-8000-db-is-5432
  text: Frontend port is 3000, backend is 8000, DB is 5432
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: hermessoulmd
  text: '`~/.hermes/SOUL.md`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: or-hermes-homesoulmd-if-you-run-hermes-with-a-custom-ho
  text: or `$HERMES_HOME/SOUL.md` if you run Hermes with a custom home directory
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: hermes-seeds-a-default-soulmd-automatically-if-one-does-n
  text: Hermes seeds a default `SOUL.md` automatically if one does not exist yet
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: hermes-loads-soulmd-only-from-hermes-home
  text: Hermes loads `SOUL.md` only from `HERMES_HOME`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: hermes-does-not-probe-the-working-directory-for-soulmd
  text: Hermes does not probe the working directory for `SOUL.md`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: if-the-file-is-empty-nothing-from-soulmd-is-added-to-the
  text: If the file is empty, nothing from `SOUL.md` is added to the prompt
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: if-the-file-has-content-the-content-is-injected-verbatim-af
  text: If the file has content, the content is injected verbatim after scanning and
    truncation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: instruction-override-attempts-ignore-previous-instructio
  text: 'Instruction override attempts**: "ignore previous instructions", "disregard
    your rules"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: deception-patterns-do-not-tell-the-user
  text: 'Deception patterns**: "do not tell the user"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: system-prompt-overrides-system-prompt-override
  text: 'System prompt overrides**: "system prompt override"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: hidden-html-comments----ignore-instructions
  text: 'Hidden HTML comments**: `<!-- ignore instructions -->`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: hidden-div-elements-div-styledisplaynone
  text: 'Hidden div elements**: `<div style="display:none">`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: credential-exfiltration-curl-api-key
  text: 'Credential exfiltration**: `curl ... $API_KEY`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: secret-file-access-cat-env-cat-credentials
  text: 'Secret file access**: `cat .env`, `cat credentials`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: invisible-characters-zero-width-spaces-bidirectional-ove
  text: 'Invisible characters**: zero-width spaces, bidirectional overrides, word
    joiners'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: limit-value
  text: 'Limit**: Value'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: max-chars-per-file-20000-7000-tokens
  text: 'Max chars per file**: 20,000 (~7,000 tokens)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: head-truncation-ratio-70
  text: 'Head truncation ratio**: 70%'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: tail-truncation-ratio-20
  text: 'Tail truncation ratio**: 20%'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: truncation-marker-10-shows-char-counts-and-suggests-usi
  text: 'Truncation marker**: 10% (shows char counts and suggests using file tools)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: use-pnpm-not-npm-for-package-management
  text: Use `pnpm` not `npm` for package management
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: components-go-in-srccomponents-pages-in-srcapp
  text: Components go in `src/components/`, pages in `src/app/`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: use-tailwind-css-never-inline-styles
  text: Use Tailwind CSS, never inline styles
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: run-tests-with-pnpm-test
  text: Run tests with `pnpm test`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: use-poetry-for-dependency-management
  text: Use `poetry` for dependency management
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: run-the-dev-server-with-poetry-run-uvicorn-mainapp---reloa
  text: Run the dev server with `poetry run uvicorn main:app --reload`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: all-endpoints-need-openapi-docstrings
  text: All endpoints need OpenAPI docstrings
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: database-models-are-in-models-schemas-in-schemas
  text: Database models are in `models/`, schemas in `schemas/`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-context-files
    path: entities/features-context-files.md
- id: soulmd-a-durable-persona-file-that-lives-in-hermes-hom
  text: "`SOUL.md` \u2014 a durable persona file that lives in `HERMES_HOME` and serves\
    \ as the agent's identity (slot #1 in the system prompt)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: built-in-or-custom-personality-presets-session-level-sy
  text: "built-in or custom `/personality` presets \u2014 session-level system-prompt\
    \ overlays"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: soulmd-is-the-agents-primary-identity-it-occupies-slot
  text: 'SOUL.md is the agent''s primary identity.** It occupies slot #1 in the system
    prompt, replacing the hardcoded default identity.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: hermes-creates-a-starter-soulmd-automatically-if-one-does
  text: Hermes creates a starter `SOUL.md` automatically if one does not exist yet
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: existing-user-soulmd-files-are-never-overwritten
  text: Existing user `SOUL.md` files are never overwritten
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: hermes-does-not-look-in-the-current-working-directory-for-s
  text: Hermes does not look in the current working directory for `SOUL.md`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: if-soulmd-exists-but-is-empty-or-cannot-be-loaded-herme
  text: If `SOUL.md` exists but is empty, or cannot be loaded, Hermes falls back to
    a built-in default identity
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: if-soulmd-has-content-that-content-is-injected-verbatim
  text: If `SOUL.md` has content, that content is injected verbatim after security
    scanning and truncation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: soulmd-is-not-duplicated-in-the-context-files-section
  text: "SOUL.md is **not** duplicated in the context files section \u2014 it appears\
    \ only once, as the identity"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: edit-hermessoulmd-to-change-hermes-default-personal
  text: '"Edit `~/.hermes/SOUL.md` to change Hermes'' default personality."'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: communication-style
  text: communication style
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: level-of-directness
  text: level of directness
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: default-interaction-style
  text: default interaction style
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: what-to-avoid-stylistically
  text: what to avoid stylistically
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: how-hermes-should-handle-uncertainty-disagreement-or-ambig
  text: how Hermes should handle uncertainty, disagreement, or ambiguity
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: one-off-project-instructions
  text: one-off project instructions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: file-paths
  text: file paths
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: repo-conventions
  text: repo conventions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: temporary-workflow-details
  text: temporary workflow details
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: stable-across-contexts
  text: stable across contexts
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: broad-enough-to-apply-in-many-conversations
  text: broad enough to apply in many conversations
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: specific-enough-to-materially-shape-the-voice
  text: specific enough to materially shape the voice
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: focused-on-communication-and-identity-not-task-specific-ins
  text: focused on communication and identity, not task-specific instructions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: be-direct-without-being-cold
  text: Be direct without being cold
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: prefer-substance-over-filler
  text: Prefer substance over filler
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: push-back-when-something-is-a-bad-idea
  text: Push back when something is a bad idea
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: admit-uncertainty-plainly
  text: Admit uncertainty plainly
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: keep-explanations-compact-unless-depth-is-useful
  text: Keep explanations compact unless depth is useful
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: sycophancy
  text: Sycophancy
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: hype-language
  text: Hype language
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: repeating-the-users-framing-if-its-wrong
  text: Repeating the user's framing if it's wrong
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: overexplaining-obvious-things
  text: Overexplaining obvious things
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: prefer-simple-systems-over-clever-systems
  text: Prefer simple systems over clever systems
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: care-about-operational-reality-not-idealized-architecture
  text: Care about operational reality, not idealized architecture
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: treat-edge-cases-as-part-of-the-design-not-cleanup
  text: Treat edge cases as part of the design, not cleanup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: prompt-injection-scanning
  text: prompt-injection scanning
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: truncation-if-it-is-too-large
  text: truncation if it is too large
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: communication-defaults
  text: communication defaults
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: personality-level-behavior
  text: personality-level behavior
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: project-architecture
  text: project architecture
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: coding-conventions
  text: coding conventions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: tool-preferences
  text: tool preferences
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: repo-specific-workflows
  text: repo-specific workflows
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: commands-ports-paths-deployment-notes
  text: commands, ports, paths, deployment notes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: if-it-should-follow-you-everywhere-it-belongs-in-soulmd
  text: if it should follow you everywhere, it belongs in `SOUL.md`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: if-it-belongs-to-a-project-it-belongs-in-agentsmd
  text: if it belongs to a project, it belongs in `AGENTS.md`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: soulmd-baseline-voice
  text: '`SOUL.md` = baseline voice'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: personality-temporary-mode-switch
  text: '`/personality` = temporary mode switch'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: keep-a-pragmatic-default-soul-then-use-personality-teache
  text: keep a pragmatic default SOUL, then use `/personality teacher` for a tutoring
    conversation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: keep-a-concise-soul-then-use-personality-creative-for-br
  text: keep a concise SOUL, then use `/personality creative` for brainstorming
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: name-description
  text: 'Name**: Description'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: helpful-friendly-general-purpose-assistant
  text: 'helpful****: Friendly, general-purpose assistant'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: concise-brief-to-the-point-responses
  text: 'concise****: Brief, to-the-point responses'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: technical-detailed-accurate-technical-expert
  text: 'technical****: Detailed, accurate technical expert'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: creative-innovative-outside-the-box-thinking
  text: 'creative****: Innovative, outside-the-box thinking'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: teacher-patient-educator-with-clear-examples
  text: 'teacher****: Patient educator with clear examples'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: kawaii-cute-expressions-sparkles-and-enthusiasm
  text: "kawaii****: Cute expressions, sparkles, and enthusiasm \u2605"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: catgirl-neko-chan-with-cat-like-expressions-nya
  text: 'catgirl****: Neko-chan with cat-like expressions, nya~'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: pirate-captain-hermes-tech-savvy-buccaneer
  text: 'pirate****: Captain Hermes, tech-savvy buccaneer'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: shakespeare-bardic-prose-with-dramatic-flair
  text: 'shakespeare****: Bardic prose with dramatic flair'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: surfer-totally-chill-bro-vibes
  text: 'surfer****: Totally chill bro vibes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: noir-hard-boiled-detective-narration
  text: 'noir****: Hard-boiled detective narration'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: uwu-maximum-cute-with-uwu-speak
  text: 'uwu****: Maximum cute with uwu-speak'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: philosopher-deep-contemplation-on-every-query
  text: 'philosopher****: Deep contemplation on every query'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: hype-maximum-energy-and-enthusiasm
  text: 'hype****: MAXIMUM ENERGY AND ENTHUSIASM!!!'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: a-stable-voice
  text: a stable voice
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: project-specific-behavior-where-it-belongs
  text: project-specific behavior where it belongs
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: temporary-control-when-needed
  text: temporary control when needed
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: context-filesdocsuser-guidefeaturescontext-files
  text: '[Context Files](/docs/user-guide/features/context-files)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: configurationdocsuser-guideconfiguration
  text: '[Configuration](/docs/user-guide/configuration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: tips-best-practicesdocsguidestips
  text: '[Tips & Best Practices](/docs/guides/tips)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: soulmd-guidedocsguidesuse-soul-with-hermes
  text: '[SOUL.md Guide](/docs/guides/use-soul-with-hermes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: soulmd-agentsystem-prompt-and-personality-affect
  text: '`SOUL.md`, `agent.system_prompt`, and `/personality` affect how Hermes speaks'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: displayskin-and-skin-affect-how-hermes-looks-in-the-te
  text: '`display.skin` and `/skin` affect how Hermes looks in the terminal'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-personality
    path: entities/features-personality.md
- id: feature-platform-description
  text: Feature**, **Platform**, **Description**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: feature-interactive-voice-platform-cli-descr
  text: 'Feature**: **Interactive Voice**, **Platform**: CLI, **Description**: Press
    Ctrl+B to record, agent auto-detects silence and responds'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: feature-auto-voice-reply-platform-telegram-dis
  text: 'Feature**: **Auto Voice Reply**, **Platform**: Telegram, Discord, **Description**:
    Agent sends spoken audio alongside text responses'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: feature-voice-channel-platform-discord-descr
  text: 'Feature**: **Voice Channel**, **Platform**: Discord, **Description**: Bot
    joins VC, listens to users speaking, speaks replies back'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: extra-packages-required-for
  text: Extra**, **Packages**, **Required For**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: extra-voice-packages-sounddevice-numpy-re
  text: 'Extra**: `voice`, **Packages**: `sounddevice`, `numpy`, **Required For**:
    CLI voice mode'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: extra-messaging-packages-discordpyvoice-py
  text: 'Extra**: `messaging`, **Packages**: `discord.py[voice]`, `python-telegram-bot`,
    `aiohttp`, **Required For**: Discord & Telegram bots'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: extra-tts-premium-packages-elevenlabs-requir
  text: 'Extra**: `tts-premium`, **Packages**: `elevenlabs`, **Required For**: ElevenLabs
    TTS provider'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: dependency-purpose-required-for
  text: Dependency**, **Purpose**, **Required For**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: dependency-portaudio-purpose-microphone-input-a
  text: 'Dependency**: **PortAudio**, **Purpose**: Microphone input and audio playback,
    **Required For**: CLI voice mode'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: dependency-ffmpeg-purpose-audio-format-conversi
  text: "Dependency**: **ffmpeg**, **Purpose**: Audio format conversion (MP3 \u2192\
    \ Opus, PCM \u2192 WAV), **Required For**: All platforms"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: dependency-opus-purpose-discord-voice-codec
  text: 'Dependency**: **Opus**, **Purpose**: Discord voice codec, **Required For**:
    Discord voice channels'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: dependency-espeak-ng-purpose-phonemizer-backend
  text: 'Dependency**: **espeak-ng**, **Purpose**: Phonemizer backend, **Required
    For**: Local NeuTTS provider'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: telegram-setup-guidedocsuser-guidemessagingtelegram
  text: '[Telegram Setup Guide](/docs/user-guide/messaging/telegram)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: discord-setup-guidedocsuser-guidemessagingdiscord
  text: '[Discord Setup Guide](/docs/user-guide/messaging/discord)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: mode-how-to-talk-mention-required-setup
  text: Mode**, **How to Talk**, **Mention Required**, **Setup**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: mode-direct-message-dm-how-to-talk-open-the-b
  text: "Mode**: **Direct Message (DM)**, **How to Talk**: Open the bot's profile\
    \ \u2192 \"Message\", **Mention Required**: No, **Setup**: Works immediately"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: mode-server-channel-how-to-talk-type-in-a-text
  text: 'Mode**: **Server Channel**, **How to Talk**: Type in a text channel where
    the bot is present, **Mention Required**: Yes (`@botname`), **Setup**: Bot must
    be invited to the server'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: mode-command-behavior
  text: Mode**, **Command**, **Behavior**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: mode-off-command-voice-off-behavior-text
  text: 'Mode**: `off`, **Command**: `/voice off`, **Behavior**: Text only (default)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: mode-voice-only-command-voice-on-behavior
  text: 'Mode**: `voice_only`, **Command**: `/voice on`, **Behavior**: Speaks reply
    only when you send a voice message'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: mode-all-command-voice-tts-behavior-spea
  text: 'Mode**: `all`, **Command**: `/voice tts`, **Behavior**: Speaks reply to every
    message'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: platform-format-notes
  text: Platform**, **Format**, **Notes**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: platform-telegram-format-voice-bubble-opusogg
  text: "Platform**: **Telegram**, **Format**: Voice bubble (Opus/OGG), **Notes**:\
    \ Plays inline in chat. ffmpeg converts MP3 \u2192 Opus if needed"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: platform-discord-format-native-voice-bubble-op
  text: 'Platform**: **Discord**, **Format**: Native voice bubble (Opus/OGG), **Notes**:
    Plays inline like a user voice message. Falls back to file attachment if voice
    bubble API fails'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: permission-purpose-required
  text: Permission**, **Purpose**, **Required**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: permission-connect-purpose-join-voice-channels
  text: 'Permission**: **Connect**, **Purpose**: Join voice channels, **Required**:
    Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: permission-speak-purpose-play-tts-audio-in-voic
  text: 'Permission**: **Speak**, **Purpose**: Play TTS audio in voice channels, **Required**:
    Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: permission-use-voice-activity-purpose-detect-wh
  text: 'Permission**: **Use Voice Activity**, **Purpose**: Detect when users are
    speaking, **Required**: Recommended'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: level-integer-whats-included
  text: Level**, **Integer**, **What's Included**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: level-text-only-integer-274878286912-whats-in
  text: 'Level**: Text only, **Integer**: `274878286912`, **What''s Included**: View
    Channels, Send Messages, Read History, Embeds, Attachments, Threads, Reactions'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: level-text-voice-integer-274881432640-whats
  text: 'Level**: Text + Voice, **Integer**: `274881432640`, **What''s Included**:
    All above + Connect, Speak'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: intent-purpose
  text: 'Intent**: Purpose'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: presence-intent-detect-user-onlineoffline-status
  text: 'Presence Intent****: Detect user online/offline status'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: server-members-intent-map-voice-ssrc-identifiers-to-dis
  text: 'Server Members Intent****: Map voice SSRC identifiers to Discord user IDs'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: message-content-intent-read-text-message-content-in-cha
  text: 'Message Content Intent****: Read text message content in channels'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: macos-opthomebrewliblibopusdylib
  text: macOS:** `/opt/homebrew/lib/libopus.dylib`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: linux-libopusso0
  text: Linux:** `libopus.so.0`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: transcripts-appear-in-the-text-channel-voice-user-what
  text: 'Transcripts appear in the text channel: `[Voice] @user: what you said`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: agent-responses-are-sent-as-text-in-the-channel-and-spoken-i
  text: Agent responses are sent as text in the channel AND spoken in the VC
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: the-text-channel-is-the-one-where-voice-join-was-issued
  text: The text channel is the one where `/voice join` was issued
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: provider-model-speed-quality-cost-a
  text: Provider**, **Model**, **Speed**, **Quality**, **Cost**, **API Key**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-local-model-base-speed-fast-d
  text: 'Provider**: **Local**, **Model**: `base`, **Speed**: Fast (depends on CPU/GPU),
    **Quality**: Good, **Cost**: Free, **API Key**: No'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-local-model-small-speed-medium
  text: 'Provider**: **Local**, **Model**: `small`, **Speed**: Medium, **Quality**:
    Better, **Cost**: Free, **API Key**: No'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-local-model-large-v3-speed-slo
  text: 'Provider**: **Local**, **Model**: `large-v3`, **Speed**: Slow, **Quality**:
    Best, **Cost**: Free, **API Key**: No'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-groq-model-whisper-large-v3-turbo
  text: 'Provider**: **Groq**, **Model**: `whisper-large-v3-turbo`, **Speed**: Very
    fast (~0.5s), **Quality**: Good, **Cost**: Free tier, **API Key**: Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-groq-model-whisper-large-v3-speed
  text: 'Provider**: **Groq**, **Model**: `whisper-large-v3`, **Speed**: Fast (~1s),
    **Quality**: Better, **Cost**: Free tier, **API Key**: Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-openai-model-whisper-1-speed-f
  text: 'Provider**: **OpenAI**, **Model**: `whisper-1`, **Speed**: Fast (~1s), **Quality**:
    Good, **Cost**: Paid, **API Key**: Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-openai-model-gpt-4o-transcribe-sp
  text: 'Provider**: **OpenAI**, **Model**: `gpt-4o-transcribe`, **Speed**: Medium
    (~2s), **Quality**: Best, **Cost**: Paid, **API Key**: Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-quality-cost-latency-key-requir
  text: Provider**, **Quality**, **Cost**, **Latency**, **Key Required**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-edge-tts-quality-good-cost-free
  text: 'Provider**: **Edge TTS**, **Quality**: Good, **Cost**: Free, **Latency**:
    ~1s, **Key Required**: No'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-elevenlabs-quality-excellent-cost
  text: 'Provider**: **ElevenLabs**, **Quality**: Excellent, **Cost**: Paid, **Latency**:
    ~2s, **Key Required**: Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-openai-tts-quality-good-cost-pai
  text: 'Provider**: **OpenAI TTS**, **Quality**: Good, **Cost**: Paid, **Latency**:
    ~1.5s, **Key Required**: Yes'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: provider-neutts-quality-good-cost-free
  text: 'Provider**: **NeuTTS**, **Quality**: Good, **Cost**: Free, **Latency**: Depends
    on CPU/GPU, **Key Required**: No'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: check-your-discord-user-id-is-in-discord-allowed-users
  text: Check your Discord user ID is in `DISCORD_ALLOWED_USERS`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: make-sure-youre-not-muted-in-discord
  text: Make sure you're not muted in Discord
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: the-bot-needs-a-speaking-event-from-discord-before-it-can-ma
  text: "The bot needs a SPEAKING event from Discord before it can map your audio\
    \ \u2014 start speaking within a few seconds of joining"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: verify-stt-is-available-install-faster-whisper-no-key-ne
  text: 'Verify STT is available: install `faster-whisper` (no key needed) or set
    `GROQ_API_KEY` / `VOICE_TOOLS_OPENAI_KEY`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: check-the-llm-model-is-configured-and-accessible
  text: Check the LLM model is configured and accessible
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: review-gateway-logs-tail--f-hermeslogsgatewaylog
  text: 'Review gateway logs: `tail -f ~/.hermes/logs/gateway.log`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: tts-provider-may-be-failing-check-api-key-and-quota
  text: "TTS provider may be failing \u2014 check API key and quota"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: edge-tts-free-no-key-is-the-default-fallback
  text: Edge TTS (free, no key) is the default fallback
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: check-logs-for-tts-errors
  text: Check logs for TTS errors
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: use-a-quieter-environment
  text: Use a quieter environment
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: adjust-silence-threshold-in-config-higher-less-sensitiv
  text: Adjust `silence_threshold` in config (higher = less sensitive)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: try-a-different-stt-model
  text: Try a different STT model
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-voice-mode
    path: entities/features-voice-mode.md
- id: access-to-external-tool-ecosystems-without-writing-a-native
  text: Access to external tool ecosystems without writing a native Hermes tool first
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: local-stdio-servers-and-remote-http-mcp-servers-in-the-same
  text: Local stdio servers and remote HTTP MCP servers in the same config
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: automatic-tool-discovery-and-registration-at-startup
  text: Automatic tool discovery and registration at startup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: utility-wrappers-for-mcp-resources-and-prompts-when-supporte
  text: Utility wrappers for MCP resources and prompts when supported by the server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: per-server-filtering-so-you-can-expose-only-the-mcp-tools-yo
  text: Per-server filtering so you can expose only the MCP tools you actually want
    Hermes to see
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: the-server-is-installed-locally
  text: the server is installed locally
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: you-want-low-latency-access-to-local-resources
  text: you want low-latency access to local resources
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: you-are-following-mcp-server-docs-that-show-command-args
  text: you are following MCP server docs that show `command`, `args`, and `env`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: the-mcp-server-is-hosted-elsewhere
  text: the MCP server is hosted elsewhere
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: your-organization-exposes-internal-mcp-endpoints
  text: your organization exposes internal MCP endpoints
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: you-do-not-want-hermes-spawning-a-local-subprocess-for-that
  text: you do not want Hermes spawning a local subprocess for that integration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-type-meaning
  text: Key**, **Type**, **Meaning**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-command-type-string-meaning-executable
  text: 'Key**: `command`, **Type**: string, **Meaning**: Executable for a stdio MCP
    server'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-args-type-list-meaning-arguments-for-th
  text: 'Key**: `args`, **Type**: list, **Meaning**: Arguments for the stdio server'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-env-type-mapping-meaning-environment-va
  text: 'Key**: `env`, **Type**: mapping, **Meaning**: Environment variables passed
    to the stdio server'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-url-type-string-meaning-http-mcp-endpoi
  text: 'Key**: `url`, **Type**: string, **Meaning**: HTTP MCP endpoint'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-headers-type-mapping-meaning-http-heade
  text: 'Key**: `headers`, **Type**: mapping, **Meaning**: HTTP headers for remote
    servers'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-timeout-type-number-meaning-tool-call-t
  text: 'Key**: `timeout`, **Type**: number, **Meaning**: Tool call timeout'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-connect-timeout-type-number-meaning-ini
  text: 'Key**: `connect_timeout`, **Type**: number, **Meaning**: Initial connection
    timeout'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-enabled-type-bool-meaning-if-false-h
  text: 'Key**: `enabled`, **Type**: bool, **Meaning**: If `false`, Hermes skips the
    server entirely'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: key-tools-type-mapping-meaning-per-server-t
  text: 'Key**: `tools`, **Type**: mapping, **Meaning**: Per-server tool filtering
    and utility policy'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: server-mcp-tool-registered-name
  text: Server**, **MCP tool**, **Registered name**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: server-filesystem-mcp-tool-read-file-registe
  text: 'Server**: `filesystem`, **MCP tool**: `read_file`, **Registered name**: `mcp_filesystem_read_file`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: server-github-mcp-tool-create-issue-register
  text: 'Server**: `github`, **MCP tool**: `create-issue`, **Registered name**: `mcp_github_create_issue`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: server-my-api-mcp-tool-querydata-registered
  text: 'Server**: `my-api`, **MCP tool**: `query.data`, **Registered name**: `mcp_my_api_query_data`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: list-resources
  text: '`list_resources`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: read-resource
  text: '`read_resource`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: list-prompts
  text: '`list_prompts`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: get-prompt
  text: '`get_prompt`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: mcp-github-list-resources
  text: '`mcp_github_list_resources`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: mcp-github-get-prompt
  text: '`mcp_github_get_prompt`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: hermes-only-registers-resource-utilities-if-the-mcp-session
  text: Hermes only registers resource utilities if the MCP session actually supports
    resource operations
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: hermes-only-registers-prompt-utilities-if-the-mcp-session-ac
  text: Hermes only registers prompt utilities if the MCP session actually supports
    prompt operations
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: toolsresources-false-disables-list-resources-and-read
  text: '`tools.resources: false` disables `list_resources` and `read_resource`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: toolsprompts-false-disables-list-prompts-and-get-prom
  text: '`tools.prompts: false` disables `list_prompts` and `get_prompt`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: disable-dangerous-tools-you-do-not-want-the-model-to-see
  text: disable dangerous tools you do not want the model to see
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: expose-only-a-minimal-whitelist-for-a-sensitive-server
  text: expose only a minimal whitelist for a sensitive server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: disable-resourceprompt-wrappers-when-you-do-not-want-that-s
  text: disable resource/prompt wrappers when you do not want that surface exposed
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: the-server-failed-to-connect
  text: the server failed to connect
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: discovery-failed
  text: discovery failed
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: your-filter-config-excluded-the-tools
  text: your filter config excluded the tools
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: the-utility-capability-does-not-exist-on-that-server
  text: the utility capability does not exist on that server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: the-server-is-disabled-with-enabled-false
  text: 'the server is disabled with `enabled: false`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: you-want-claude-code-cursor-or-another-coding-agent-to-sen
  text: You want Claude Code, Cursor, or another coding agent to send and read Telegram/Discord/Slack
    messages through Hermes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: you-want-a-single-mcp-server-that-bridges-to-all-of-hermess
  text: You want a single MCP server that bridges to all of Hermes's connected messaging
    platforms at once
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: you-already-have-a-running-hermes-gateway-with-connected-pla
  text: You already have a running Hermes gateway with connected platforms
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: tool-description
  text: 'Tool**: Description'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: conversations-list-list-active-messaging-conversations
  text: '`conversations_list`**: List active messaging conversations. Filter by platform
    or search by name.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: conversation-get-get-detailed-info-about-one-conversati
  text: '`conversation_get`**: Get detailed info about one conversation by session
    key.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: messages-read-read-recent-message-history-for-a-convers
  text: '`messages_read`**: Read recent message history for a conversation.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: attachments-fetch-extract-non-text-attachments-images
  text: '`attachments_fetch`**: Extract non-text attachments (images, media) from
    a specific message.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: events-poll-poll-for-new-conversation-events-since-a-cu
  text: '`events_poll`**: Poll for new conversation events since a cursor position.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: events-wait-long-poll-block-until-the-next-event-arri
  text: '`events_wait`**: Long-poll / block until the next event arrives (near-real-time).'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: messages-send-send-a-message-through-a-platform-eg
  text: '`messages_send`**: Send a message through a platform (e.g. `telegram:123456`,
    `discord:#general`).'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: channels-list-list-available-messaging-targets-across-a
  text: '`channels_list`**: List available messaging targets across all platforms.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: permissions-list-open-list-pending-approval-requests-ob
  text: '`permissions_list_open`**: List pending approval requests observed during
    this bridge session.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: permissions-respond-allow-or-deny-a-pending-approval-re
  text: '`permissions_respond`**: Allow or deny a pending approval request.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: stdio-transport-only-no-http-mcp-transport-yet
  text: Stdio transport only (no HTTP MCP transport yet)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: event-polling-at-200ms-intervals-via-mtime-optimized-db-pol
  text: Event polling at ~200ms intervals via mtime-optimized DB polling (skips work
    when files are unchanged)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: no-claudechannel-push-notification-protocol-yet
  text: No `claude/channel` push notification protocol yet
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: text-only-sends-no-mediaattachment-sending-through-messag
  text: Text-only sends (no media/attachment sending through `messages_send`)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: use-mcp-with-hermesdocsguidesuse-mcp-with-hermes
  text: '[Use MCP with Hermes](/docs/guides/use-mcp-with-hermes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: cli-commandsdocsreferencecli-commands
  text: '[CLI Commands](/docs/reference/cli-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
- id: slash-commandsdocsreferenceslash-commands
  text: '[Slash Commands](/docs/reference/slash-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: faqdocsreferencefaq
  text: '[FAQ](/docs/reference/faq)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-mcp
    path: entities/features-mcp.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: bundled-skills-catalogdocsreferenceskills-catalog
  text: '[Bundled Skills Catalog](/docs/reference/skills-catalog)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: official-optional-skills-catalogdocsreferenceoptional
  text: '[Official Optional Skills Catalog](/docs/reference/optional-skills-catalog)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: key-mysetting
  text: 'key: my.setting'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: known-failure-modes-and-fixes
  text: Known failure modes and fixes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: value-matches
  text: 'Value**: Matches'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: macos-macos-darwin
  text: '`macos`**: macOS (Darwin)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: linux-linux
  text: '`linux`**: Linux'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: windows-windows
  text: '`windows`**: Windows'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: field-behavior
  text: 'Field**: Behavior'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: fallback-for-toolsets-skill-is-hidden-when-the-list
  text: '`fallback_for_toolsets`**: Skill is **hidden** when the listed toolsets are
    available. Shown when they''re missing.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: fallback-for-tools-same-but-checks-individual-tools-in
  text: '`fallback_for_tools`**: Same, but checks individual tools instead of toolsets.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: requires-toolsets-skill-is-hidden-when-the-listed-t
  text: '`requires_toolsets`**: Skill is **hidden** when the listed toolsets are unavailable.
    Shown when they''re present.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: requires-tools-same-but-checks-individual-tools
  text: '`requires_tools`**: Same, but checks individual tools.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: key-mypluginpath
  text: 'key: myplugin.path'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: agentsskills
  text: ~/.agents/skills
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: homesharedteam-skills
  text: /home/shared/team-skills
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: skills-reposkills
  text: ${SKILLS_REPO}/skills
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: read-only-external-dirs-are-only-scanned-for-skill-discov
  text: 'Read-only**: External dirs are only scanned for skill discovery. When the
    agent creates or edits a skill, it always writes to `~/.hermes/skills/`.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: local-precedence-if-the-same-skill-name-exists-in-both-th
  text: 'Local precedence**: If the same skill name exists in both the local dir and
    an external dir, the local version wins.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: full-integration-external-skills-appear-in-the-system-pro
  text: "Full integration**: External skills appear in the system prompt index, `skills_list`,\
    \ `skill_view`, and as `/skill-name` slash commands \u2014 no different from local\
    \ skills."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: non-existent-paths-are-silently-skipped-if-a-configured-d
  text: 'Non-existent paths are silently skipped**: If a configured directory doesn''t
    exist, Hermes ignores it without errors. Useful for optional shared directories
    that may not be present on every machine.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: after-completing-a-complex-task-5-tool-calls-successfully
  text: After completing a complex task (5+ tool calls) successfully
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: when-it-hit-errors-or-dead-ends-and-found-the-working-path
  text: When it hit errors or dead ends and found the working path
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: when-the-user-corrected-its-approach
  text: When the user corrected its approach
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: when-it-discovered-a-non-trivial-workflow
  text: When it discovered a non-trivial workflow
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: action-use-for-key-params
  text: Action**, **Use for**, **Key params**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: action-create-use-for-new-skill-from-scratch-k
  text: 'Action**: `create`, **Use for**: New skill from scratch, **Key params**:
    `name`, `content` (full SKILL.md), optional `category`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: action-patch-use-for-targeted-fixes-preferred
  text: 'Action**: `patch`, **Use for**: Targeted fixes (preferred), **Key params**:
    `name`, `old_string`, `new_string`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: action-edit-use-for-major-structural-rewrites
  text: 'Action**: `edit`, **Use for**: Major structural rewrites, **Key params**:
    `name`, `content` (full SKILL.md replacement)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: action-delete-use-for-remove-a-skill-entirely
  text: 'Action**: `delete`, **Use for**: Remove a skill entirely, **Key params**:
    `name`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: action-write-file-use-for-addupdate-supporting-f
  text: 'Action**: `write_file`, **Use for**: Add/update supporting files, **Key params**:
    `name`, `file_path`, `file_content`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: action-remove-file-use-for-remove-a-supporting-fi
  text: 'Action**: `remove_file`, **Use for**: Remove a supporting file, **Key params**:
    `name`, `file_path`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: source-example-notes
  text: Source**, **Example**, **Notes**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: source-official-example-officialsecurity1passw
  text: 'Source**: `official`, **Example**: `official/security/1password`, **Notes**:
    Optional skills shipped with Hermes.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: source-skills-sh-example-skills-shvercel-labsa
  text: 'Source**: `skills-sh`, **Example**: `skills-sh/vercel-labs/agent-skills/vercel-react-best-practices`,
    **Notes**: Searchable via `hermes skills search <query> --source skills-sh`. Hermes
    resolves alias-style skills when the skills.sh slug differs from the repo folder.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: source-well-known-example-well-knownhttpsmin
  text: 'Source**: `well-known`, **Example**: `well-known:https://mintlify.com/docs/.well-known/skills/mintlify`,
    **Notes**: Skills served directly from `/.well-known/skills/index.json` on a website.
    Search using the site or docs URL.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: source-github-example-openaiskillsk8s-note
  text: 'Source**: `github`, **Example**: `openai/skills/k8s`, **Notes**: Direct GitHub
    repo/path installs and custom taps.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: source-clawhub-lobehub-claude-marketplace-exam
  text: 'Source**: `clawhub`, `lobehub`, `claude-marketplace`, **Example**: Source-specific
    identifiers, **Notes**: Community or marketplace integrations.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: catalog-official-optional-skills-catalogdocsreference
  text: 'Catalog: [Official Optional Skills Catalog](/docs/reference/optional-skills-catalog)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: source-in-repo-optional-skills
  text: 'Source in repo: `optional-skills/`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: directory-skillsshhttpsskillssh
  text: 'Directory: [skills.sh](https://skills.sh/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: clitooling-repo-vercel-labsskillshttpsgithubcomve
  text: 'CLI/tooling repo: [vercel-labs/skills](https://github.com/vercel-labs/skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: official-vercel-skills-repo-vercel-labsagent-skillshttp
  text: 'Official Vercel skills repo: [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: example-live-endpoint-mintlify-docs-skills-indexhttps
  text: 'Example live endpoint: [Mintlify docs skills index](https://mintlify.com/docs/.well-known/skills/index.json)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: reference-server-implementation-vercel-labsskills-handler
  text: 'Reference server implementation: [vercel-labs/skills-handler](https://github.com/vercel-labs/skills-handler)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: openaiskillshttpsgithubcomopenaiskills
  text: '[openai/skills](https://github.com/openai/skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: anthropicsskillshttpsgithubcomanthropicsskills
  text: '[anthropics/skills](https://github.com/anthropics/skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: voltagentawesome-agent-skillshttpsgithubcomvoltagen
  text: '[VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: garrytangstackhttpsgithubcomgarrytangstack
  text: '[garrytan/gstack](https://github.com/garrytan/gstack)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: site-clawhubaihttpsclawhubai
  text: 'Site: [clawhub.ai](https://clawhub.ai/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: hermes-source-id-clawhub
  text: 'Hermes source id: `clawhub`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: aiskillstoremarketplacehttpsgithubcomaiskillstorem
  text: '[aiskillstore/marketplace](https://github.com/aiskillstore/marketplace)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: site-lobehubhttpslobehubcom
  text: 'Site: [LobeHub](https://lobehub.com/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: public-agents-index-chat-agentslobehubcomhttpschat
  text: 'Public agents index: [chat-agents.lobehub.com](https://chat-agents.lobehub.com/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: backing-repo-lobehublobe-chat-agentshttpsgithubcom
  text: 'Backing repo: [lobehub/lobe-chat-agents](https://github.com/lobehub/lobe-chat-agents)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: hermes-source-id-lobehub
  text: 'Hermes source id: `lobehub`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: skillssh-detail-page-url
  text: skills.sh detail page URL
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: install-command
  text: install command
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: weekly-installs
  text: weekly installs
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: upstream-security-audit-statuses
  text: upstream security audit statuses
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: well-known-indexendpoint-urls
  text: well-known index/endpoint URLs
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: force-can-override-policy-blocks-for-cautionwarn-style
  text: '`--force` can override policy blocks for caution/warn-style findings.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: force-does-not-override-a-dangerous-scan-verdict
  text: '`--force` does **not** override a `dangerous` scan verdict.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: official-optional-skills-official-are-treated-as-bui
  text: Official optional skills (`official/...`) are treated as builtin trust and
    do not show the third-party warning panel.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: level-source-policy
  text: Level**, **Source**, **Policy**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: level-builtin-source-ships-with-hermes-policy
  text: 'Level**: `builtin`, **Source**: Ships with Hermes, **Policy**: Always trusted'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: level-official-source-optional-skills-in-the-r
  text: 'Level**: `official`, **Source**: `optional-skills/` in the repo, **Policy**:
    Builtin trust, no third-party warning'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: level-trusted-source-trusted-registriesrepos-suc
  text: 'Level**: `trusted`, **Source**: Trusted registries/repos such as `openai/skills`,
    `anthropics/skills`, **Policy**: More permissive policy than community sources'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: level-community-source-everything-else-skillss
  text: 'Level**: `community`, **Source**: Everything else (`skills.sh`, well-known
    endpoints, custom GitHub repos, most marketplaces), **Policy**: Non-dangerous
    findings can be overridden with `--force`; `dangerous` verdicts stay blocked'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: unchanged-safe-to-pull-upstream-changes-copy-the-new-bu
  text: "Unchanged** \u2192 safe to pull upstream changes, copy the new bundled version\
    \ in, record the new origin hash."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: changed-treated-as-user-modified-and-skipped-forever
  text: "Changed** \u2192 treated as **user-modified** and skipped forever, so your\
    \ edits never get stomped."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-skills
    path: entities/features-skills.md
- id: file-purpose-char-limit
  text: File**, **Purpose**, **Char Limit**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: file-memorymd-purpose-agents-personal-notes
  text: "File**: **MEMORY.md**, **Purpose**: Agent's personal notes \u2014 environment\
    \ facts, conventions, things learned, **Char Limit**: 2,200 chars (~800 tokens)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: file-usermd-purpose-user-profile-your-prefer
  text: "File**: **USER.md**, **Purpose**: User profile \u2014 your preferences, communication\
    \ style, expectations, **Char Limit**: 1,375 chars (~500 tokens)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: a-header-showing-which-store-memory-or-user-profile
  text: A header showing which store (MEMORY or USER PROFILE)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: usage-percentage-and-character-counts-so-the-agent-knows-cap
  text: Usage percentage and character counts so the agent knows capacity
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: individual-entries-separated-by-section-sign-delimiter
  text: "Individual entries separated by `\xA7` (section sign) delimiters"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: entries-can-be-multiline
  text: Entries can be multiline
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: add-add-a-new-memory-entry
  text: "add** \u2014 Add a new memory entry"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: replace-replace-an-existing-entry-with-updated-content
  text: "replace** \u2014 Replace an existing entry with updated content (uses substring\
    \ matching via `old_text`)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: remove-remove-an-entry-thats-no-longer-relevant-uses-s
  text: "remove** \u2014 Remove an entry that's no longer relevant (uses substring\
    \ matching via `old_text`)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: environment-facts-os-tools-project-structure
  text: Environment facts (OS, tools, project structure)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: project-conventions-and-configuration
  text: Project conventions and configuration
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: tool-quirks-and-workarounds-discovered
  text: Tool quirks and workarounds discovered
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: completed-task-diary-entries
  text: Completed task diary entries
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: skills-and-techniques-that-worked
  text: Skills and techniques that worked
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: name-role-timezone
  text: Name, role, timezone
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: communication-preferences-concise-vs-detailed-format-prefe
  text: Communication preferences (concise vs detailed, format preferences)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: pet-peeves-and-things-to-avoid
  text: Pet peeves and things to avoid
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: workflow-habits
  text: Workflow habits
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: technical-skill-level
  text: Technical skill level
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: user-preferences-i-prefer-typescript-over-javascript
  text: "User preferences:** \"I prefer TypeScript over JavaScript\" \u2192 save to\
    \ `user`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: environment-facts-this-server-runs-debian-12-with-postgr
  text: "Environment facts:** \"This server runs Debian 12 with PostgreSQL 16\" \u2192\
    \ save to `memory`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: corrections-dont-use-sudo-for-docker-commands-user-i
  text: "Corrections:** \"Don't use `sudo` for Docker commands, user is in docker\
    \ group\" \u2192 save to `memory`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: conventions-project-uses-tabs-120-char-line-width-goog
  text: "Conventions:** \"Project uses tabs, 120-char line width, Google-style docstrings\"\
    \ \u2192 save to `memory`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: completed-work-migrated-database-from-mysql-to-postgresq
  text: "Completed work:** \"Migrated database from MySQL to PostgreSQL on 2026-01-15\"\
    \ \u2192 save to `memory`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: explicit-requests-remember-that-my-api-key-rotation-happ
  text: "Explicit requests:** \"Remember that my API key rotation happens monthly\"\
    \ \u2192 save to `memory`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: trivialobvious-info-user-asked-about-python-too-vagu
  text: "Trivial/obvious info:** \"User asked about Python\" \u2014 too vague to be\
    \ useful"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: easily-re-discovered-facts-python-312-supports-f-string
  text: "Easily re-discovered facts:** \"Python 3.12 supports f-string nesting\" \u2014\
    \ can web search this"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: raw-data-dumps-large-code-blocks-log-files-data-tables
  text: "Raw data dumps:** Large code blocks, log files, data tables \u2014 too big\
    \ for memory"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: session-specific-ephemera-temporary-file-paths-one-off-d
  text: Session-specific ephemera:** Temporary file paths, one-off debugging context
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: information-already-in-context-files-soulmd-and-agentsm
  text: Information already in context files:** SOUL.md and AGENTS.md content
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: store-limit-typical-entries
  text: Store**, **Limit**, **Typical entries**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: store-memory-limit-2200-chars-typical-entries
  text: 'Store**: memory, **Limit**: 2,200 chars, **Typical entries**: 8-15 entries'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: store-user-limit-1375-chars-typical-entries
  text: 'Store**: user, **Limit**: 1,375 chars, **Typical entries**: 5-10 entries'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: all-cli-and-messaging-sessions-are-stored-in-sqlite-her
  text: All CLI and messaging sessions are stored in SQLite (`~/.hermes/state.db`)
    with FTS5 full-text search
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: search-queries-return-relevant-past-conversations-with-gemin
  text: Search queries return relevant past conversations with Gemini Flash summarization
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: the-agent-can-find-things-it-discussed-weeks-ago-even-if-th
  text: The agent can find things it discussed weeks ago, even if they're not in its
    active memory
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: feature-persistent-memory-session-search
  text: Feature**, **Persistent Memory**, **Session Search**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: feature-capacity-persistent-memory-1300-token
  text: 'Feature**: **Capacity**, **Persistent Memory**: ~1,300 tokens total, **Session
    Search**: Unlimited (all sessions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: feature-speed-persistent-memory-instant-in-sys
  text: 'Feature**: **Speed**, **Persistent Memory**: Instant (in system prompt),
    **Session Search**: Requires search + LLM summarization'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: feature-use-case-persistent-memory-key-facts-al
  text: 'Feature**: **Use case**, **Persistent Memory**: Key facts always available,
    **Session Search**: Finding specific past conversations'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: feature-management-persistent-memory-manually-c
  text: "Feature**: **Management**, **Persistent Memory**: Manually curated by agent,\
    \ **Session Search**: Automatic \u2014 all sessions stored"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: feature-token-cost-persistent-memory-fixed-per
  text: 'Feature**: **Token cost**, **Persistent Memory**: Fixed per session (~1,300
    tokens), **Session Search**: On-demand (searched when needed)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-memory
    path: entities/features-memory.md
- id: category-examples-description
  text: Category**, **Examples**, **Description**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-web-examples-web-search-web-extrac
  text: 'Category**: **Web**, **Examples**: `web_search`, `web_extract`, **Description**:
    Search the web and extract page content.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-terminal-files-examples-terminal
  text: 'Category**: **Terminal & Files**, **Examples**: `terminal`, `process`, `read_file`,
    `patch`, **Description**: Execute commands and manipulate files.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-browser-examples-browser-navigate
  text: 'Category**: **Browser**, **Examples**: `browser_navigate`, `browser_snapshot`,
    `browser_vision`, **Description**: Interactive browser automation with text and
    vision support.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-media-examples-vision-analyze-imag
  text: 'Category**: **Media**, **Examples**: `vision_analyze`, `image_generate`,
    `text_to_speech`, **Description**: Multimodal analysis and generation.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-agent-orchestration-examples-todo
  text: 'Category**: **Agent orchestration**, **Examples**: `todo`, `clarify`, `execute_code`,
    `delegate_task`, **Description**: Planning, clarification, code execution, and
    subagent delegation.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-memory-recall-examples-memory-se
  text: 'Category**: **Memory & recall**, **Examples**: `memory`, `session_search`,
    **Description**: Persistent memory and session search.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-automation-delivery-examples-cronjo
  text: 'Category**: **Automation & delivery**, **Examples**: `cronjob`, `send_message`,
    **Description**: Scheduled tasks with create/list/update/pause/resume/run/remove
    actions, plus outbound messaging delivery.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: category-integrations-examples-ha-mcp-serv
  text: 'Category**: **Integrations**, **Examples**: `ha_*`, MCP server tools, `rl_*`,
    **Description**: Home Assistant, MCP, RL training, and other integrations.'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: backend-description-use-case
  text: Backend**, **Description**, **Use Case**
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: backend-local-description-run-on-your-machine-de
  text: 'Backend**: `local`, **Description**: Run on your machine (default), **Use
    Case**: Development, trusted tasks'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: backend-docker-description-isolated-containers
  text: 'Backend**: `docker`, **Description**: Isolated containers, **Use Case**:
    Security, reproducibility'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: backend-ssh-description-remote-server-use-case
  text: 'Backend**: `ssh`, **Description**: Remote server, **Use Case**: Sandboxing,
    keep agent away from its own code'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: backend-singularity-description-hpc-containers
  text: 'Backend**: `singularity`, **Description**: HPC containers, **Use Case**:
    Cluster computing, rootless'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: backend-modal-description-cloud-execution-use
  text: 'Backend**: `modal`, **Description**: Cloud execution, **Use Case**: Serverless,
    scale'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: backend-daytona-description-cloud-sandbox-workspa
  text: 'Backend**: `daytona`, **Description**: Cloud sandbox workspace, **Use Case**:
    Persistent remote dev environments'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: read-only-root-filesystem-docker
  text: Read-only root filesystem (Docker)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: all-linux-capabilities-dropped
  text: All Linux capabilities dropped
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: no-privilege-escalation
  text: No privilege escalation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: pid-limits-256-processes
  text: PID limits (256 processes)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: full-namespace-isolation
  text: Full namespace isolation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: persistent-workspace-via-volumes-not-writable-root-layer
  text: Persistent workspace via volumes, not writable root layer
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.features-tools
    path: entities/features-tools.md
- id: model-name-current-model-truncated-if-longer-than-26-ch
  text: "Model name** \u2014 Current model (truncated if longer than 26 chars)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: token-count-context-tokens-used-max-context-window
  text: "Token count** \u2014 Context tokens used / max context window"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: context-bar-visual-fill-indicator-with-color-coded-thres
  text: "Context bar** \u2014 Visual fill indicator with color-coded thresholds"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: cost-estimated-session-cost-or-na-for-unknownzero-pri
  text: "Cost** \u2014 Estimated session cost (or n/a for unknown/zero-priced models)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: duration-elapsed-session-time
  text: "Duration** \u2014 Elapsed session time"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: full-layout-at-76-columns
  text: "Full layout at \u2265 76 columns"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: compact-at-5275-columns
  text: "Compact at 52\u201375 columns"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: minimal-model-duration-only-below-52-columns
  text: Minimal (model + duration only) below 52 columns
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: green-50-plenty-of-room
  text: "Green** < 50% \u2014 Plenty of room"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: yellow-5080-getting-full
  text: "Yellow** 50\u201380% \u2014 Getting full"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: orange-8095-approaching-limit
  text: "Orange** 80\u201395% \u2014 Approaching limit"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: red-95-near-overflow-consider-compress
  text: "Red** \u2265 95% \u2014 Near overflow \u2014 consider `/compress`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: help-show-command-help
  text: "`/help` \u2014 Show command help"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: model-show-or-change-the-current-model
  text: "`/model` \u2014 Show or change the current model"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: tools-list-currently-available-tools
  text: "`/tools` \u2014 List currently available tools"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: skills-browse-browse-the-skills-hub-and-official-option
  text: "`/skills browse` \u2014 Browse the skills hub and official optional skills"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: background-prompt-run-a-prompt-in-a-separate-backgrou
  text: "`/background <prompt>` \u2014 Run a prompt in a separate background session"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: skin-show-or-switch-the-active-cli-skin
  text: "`/skin` \u2014 Show or switch the active CLI skin"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: voice-on-enable-cli-voice-mode-press-ctrlb-to-record
  text: "`/voice on` \u2014 Enable CLI voice mode (press Ctrl+B to record)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: voice-tts-toggle-spoken-playback-for-hermes-replies
  text: "`/voice tts` \u2014 Toggle spoken playback for Hermes replies"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: reasoning-high-increase-reasoning-effort
  text: "`/reasoning high` \u2014 Increase reasoning effort"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: title-my-session-name-the-current-session
  text: "`/title My Session` \u2014 Name the current session"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: type-a-new-message-enter-while-the-agent-is-working-it-i
  text: "Type a new message + Enter while the agent is working \u2014 it interrupts\
    \ and processes your new instructions"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: ctrlc-interrupt-the-current-operation-press-twice-with
  text: "Ctrl+C** \u2014 interrupt the current operation (press twice within 2s to\
    \ force exit)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: interrupt-default-your-message-interrupts-the-curren
  text: "\"interrupt\"** (default) \u2014 Your message interrupts the current operation\
    \ and is processed immediately"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: queue-your-message-is-silently-queued-and-sent-as-the
  text: "\"queue\"** \u2014 Your message is silently queued and sent as the next turn\
    \ after the agent finishes"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: session-metadata-id-title-timestamps-token-counters
  text: session metadata (ID, title, timestamps, token counters)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: message-history
  text: message history
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: lineage-across-compressedresumed-sessions
  text: lineage across compressed/resumed sessions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: full-text-search-indexes-used-by-session-search
  text: full-text search indexes used by session_search
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: isolated-conversation-the-background-agent-has-no-knowle
  text: "Isolated conversation** \u2014 the background agent has no knowledge of your\
    \ current session's history. It receives only the prompt you provide."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: same-configuration-the-background-agent-inherits-your-mo
  text: "Same configuration** \u2014 the background agent inherits your model, provider,\
    \ toolsets, reasoning settings, and fallback model from the current session."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: non-blocking-your-foreground-session-stays-fully-interac
  text: "Non-blocking** \u2014 your foreground session stays fully interactive. You\
    \ can chat, run commands, or even start more background tasks."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: multiple-tasks-you-can-run-several-background-tasks-simu
  text: "Multiple tasks** \u2014 you can run several background tasks simultaneously.\
    \ Each gets a numbered ID."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: long-running-research-background-research-the-latest-d
  text: "Long-running research** \u2014 \"/background research the latest developments\
    \ in quantum error correction\" while you work on code"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: file-processing-background-analyze-all-python-files-in
  text: "File processing** \u2014 \"/background analyze all Python files in this repo\
    \ and list any security issues\" while you continue a conversation"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: parallel-investigations-start-multiple-background-tasks
  text: "Parallel investigations** \u2014 start multiple background tasks to explore\
    \ different angles simultaneously"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: suppresses-verbose-logging-from-tools
  text: Suppresses verbose logging from tools
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: enables-kawaii-style-animated-feedback
  text: Enables kawaii-style animated feedback
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: keeps-output-clean-and-user-friendly
  text: Keeps output clean and user-friendly
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.cli-interface
    path: entities/cli-interface.md
- id: using-hermesdocsuser-guidecli
  text: '[Using Hermes](/docs/user-guide/cli)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: featuresdocsuser-guidefeaturesoverview
  text: '[Features](/docs/user-guide/features/overview)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: messaging-platformsdocsuser-guidemessaging
  text: '[Messaging Platforms](/docs/user-guide/messaging/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: integrationsdocsintegrations
  text: '[Integrations](/docs/integrations/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: guides-tutorialsdocsguidestips
  text: '[Guides & Tutorials](/docs/guides/tips)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: developer-guidedocsdeveloper-guidecontributing
  text: '[Developer Guide](/docs/developer-guide/contributing)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: referencedocsreferencecli-commandscli-commands-refer
  text: '[Reference](/docs/reference/cli-commands)[CLI Commands Reference](/docs/reference/cli-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: profile-commands-referencedocsreferenceprofile-command
  text: '[Profile Commands Reference](/docs/reference/profile-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: environment-variablesdocsreferenceenvironment-variable
  text: '[Environment Variables](/docs/reference/environment-variables)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: built-in-tools-referencedocsreferencetools-reference
  text: '[Built-in Tools Reference](/docs/reference/tools-reference)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: toolsets-referencedocsreferencetoolsets-reference
  text: '[Toolsets Reference](/docs/reference/toolsets-reference)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: mcp-config-referencedocsreferencemcp-config-reference
  text: '[MCP Config Reference](/docs/reference/mcp-config-reference)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: optional-skills-catalogdocsreferenceoptional-skills-ca
  text: '[Optional Skills Catalog](/docs/reference/optional-skills-catalog)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: faq-troubleshootingdocsreferencefaq
  text: '[FAQ & Troubleshooting](/docs/reference/faq)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: docs
  text: '[](/docs/)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: faq-troubleshooting
  text: FAQ & Troubleshooting
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: openrouterhttpsopenrouterai-access-hundreds-of-mo
  text: "[OpenRouter](https://openrouter.ai/) \u2014 access hundreds of models through\
    \ one API key (recommended for flexibility)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: nous-portal-nous-researchs-own-inference-endpoint
  text: "Nous Portal \u2014 Nous Research's own inference endpoint"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: openai-gpt-4o-o1-o3-etc
  text: "OpenAI \u2014 GPT-4o, o1, o3, etc."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: anthropic-claude-models-via-openrouter-or-compatible-prox
  text: "Anthropic \u2014 Claude models (via OpenRouter or compatible proxy)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: google-gemini-models-via-openrouter-or-compatible-proxy
  text: "Google \u2014 Gemini models (via OpenRouter or compatible proxy)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: zai-zhipuai-glm-models
  text: "z.ai / ZhipuAI \u2014 GLM models"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: kimi-moonshot-ai-kimi-models
  text: "Kimi / Moonshot AI \u2014 Kimi models"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: minimax-global-and-china-endpoints
  text: "MiniMax \u2014 global and China endpoints"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: local-models-via-ollamahttpsollamacom-vllmhtt
  text: "Local models \u2014 via [Ollama](https://ollama.com/), [vLLM](https://docs.vllm.ai/),\
    \ [llama.cpp](https://github.com/ggerganov/llama.cpp), [SGLang](https://github.com/sgl-project/sglang),\
    \ or any OpenAI-compatible server"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: memory-stores-facts-things-the-agent-knows-about-you-your
  text: "Memory stores facts \u2014 things the agent knows about you, your projects,\
    \ and preferences. Memories are retrieved automatically based on relevance."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: skills-store-procedures-step-by-step-instructions-for-how
  text: "Skills store procedures \u2014 step-by-step instructions for how to do things.\
    \ Skills are recalled when the agent encounters a similar task."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: upgrading-your-provider-plan
  text: Upgrading your provider plan
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: switching-to-a-different-model-or-provider
  text: Switching to a different model or provider
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: using-hermes-chat---provider-to-route-to-a-different-back
  text: Using `hermes chat --provider ` to route to a different backend
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: ask-the-agent-to-use-a-safer-alternative
  text: Ask the agent to use a safer alternative
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: see-the-full-list-of-dangerous-patterns-in-the-[[entity.security|Security]]-doc
  text: See the full list of dangerous patterns in the [[[entity.security|Security]]
    docs](/docs/user-guide/[[entity.security|Security]])
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: avoid-sudo-in-messaging-ask-the-agent-to-find-alternativ
  text: "Avoid `sudo` in messaging \u2014 ask the agent to find alternatives"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: if-you-must-use-sudo-configure-passwordless-sudo-for-spec
  text: If you must use `sudo`, configure passwordless sudo for specific commands
    in `/etc/sudoers`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: or-switch-to-the-terminal-interface-for-administrative-tasks
  text: 'Or switch to the terminal interface for administrative tasks: `hermes chat`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: verify-your-bot-token-is-valid-with-hermes-gateway-setup
  text: Verify your bot token is valid with `hermes gateway setup`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: check-gateway-logs-cat-hermeslogsgatewaylog-tail
  text: 'Check gateway logs: `cat ~/.hermes/logs/gateway.log | tail -50`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: for-webhook-based-platforms-slack-whatsapp-ensure-your-s
  text: For webhook-based platforms (Slack, WhatsApp), ensure your server is publicly
    accessible
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: open-etcwslconf-create-it-if-it-doesnt-exist
  text: Open `/etc/wsl.conf` (create it if it doesn't exist)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: from-powershell-wsl---shutdown
  text: 'From PowerShell: `wsl --shutdown`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: reopen-your-wsl-terminal
  text: Reopen your WSL terminal
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: verify-systemctl-is-system-running-should-say-running-o
  text: 'Verify: `systemctl is-system-running` should say "running" or "degraded"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: create-a-task-that-runs-wsl--d-ubuntu----bash--lc-hermes-g
  text: Create a task that runs `wsl -d Ubuntu -- bash -lc 'hermes gateway run'`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: set-it-to-trigger-on-user-logon
  text: Set it to trigger on user logon
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: try-a-fastersmaller-model-hermes-chat---model-openrouter
  text: 'Try a faster/smaller model: `hermes chat --model openrouter/meta-llama/llama-3.1-8b-instruct`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: reduce-active-toolsets-hermes-chat--t-terminal
  text: 'Reduce active toolsets: `hermes chat -t "terminal"`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: check-your-network-latency-to-the-provider
  text: Check your network latency to the provider
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: for-local-models-ensure-you-have-enough-gpu-vram
  text: For local models, ensure you have enough GPU VRAM
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: check-gatewayagent-logs-for-mcp-connection-errors
  text: Check gateway/agent logs for MCP connection errors
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: ensure-the-server-responds-to-the-toolslist-rpc-method
  text: Ensure the server responds to the `tools/list` RPC method
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: review-any-toolsinclude-toolsexclude-toolsresource
  text: Review any `tools.include`, `tools.exclude`, `tools.resources`, `tools.prompts`,
    or `enabled` settings under that server
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: remember-that-resourceprompt-utility-tools-are-only-registe
  text: Remember that resource/prompt utility tools are only registered when the session
    actually supports those capabilities
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: use-reload-mcp-after-changing-config
  text: Use `/reload-mcp` after changing config
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: mcp-model-context-protocoldocsuser-guidefeaturesmcp
  text: '[MCP (Model Context Protocol)](/docs/user-guide/features/mcp)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: increase-the-timeout-in-your-mcp-server-config-if-supported
  text: Increase the timeout in your MCP server config if supported
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: check-if-the-mcp-server-process-is-still-running
  text: Check if the MCP server process is still running
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: for-remote-http-mcp-servers-check-network-connectivity
  text: For remote HTTP MCP servers, check network connectivity
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: off-only-the-final-response-no-tool-calls-no-reasoning
  text: "`off` \u2014 Only the final response. No tool calls, no reasoning, no logs."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: new-shows-new-tool-calls-as-they-happen-brief-one-liner
  text: "`new` \u2014 Shows new tool calls as they happen (brief one-liners)."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: all-shows-all-tool-activity-including-results
  text: "`all` \u2014 Shows all tool activity including results."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: verbose-full-detail-including-tool-arguments-and-outputs
  text: "`verbose` \u2014 Full detail including tool arguments and outputs."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: search-existing-issues-github-issueshttpsgithubcomn
  text: 'Search existing issues: [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: ask-the-community-nous-research-discordhttpsdiscordg
  text: 'Ask the community: [Nous Research Discord](https://discord.gg/nousresearch)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: file-a-bug-report-include-your-os-python-version-python3
  text: 'File a bug report: Include your OS, Python version (`python3 --version`),
    Hermes version (`hermes --version`), and the full error message'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: does-it-work-on-windowsdoes-it-work-on-windows
  text: '[Does it work on Windows?](#does-it-work-on-windows)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: does-it-work-on-android-termuxdoes-it-work-on-android
  text: '[Does it work on Android / Termux?](#does-it-work-on-android--termux)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: is-my-data-sent-anywhereis-my-data-sent-anywhere
  text: '[Is my data sent anywhere?](#is-my-data-sent-anywhere)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: can-i-use-it-offline-with-local-modelscan-i-use-it-of
  text: '[Can I use it offline / with local models?](#can-i-use-it-offline--with-local-models)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: how-much-does-it-costhow-much-does-it-cost
  text: '[How much does it cost?](#how-much-does-it-cost)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: can-multiple-people-use-one-instancecan-multiple-people
  text: '[Can multiple people use one instance?](#can-multiple-people-use-one-instance)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: what39s-the-difference-between-memory-and-skillswhat
  text: '[What&#39;s the difference between memory and skills?](#whats-the-difference-between-memory-and-skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: can-i-use-it-in-my-own-python-projectcan-i-use-it-in-my
  text: '[Can I use it in my own Python project?](#can-i-use-it-in-my-own-python-project)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: troubleshootingtroubleshootinginstallation-issuesin
  text: '[Troubleshooting](#troubleshooting)[Installation Issues](#installation-issues)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: provider-model-issuesprovider--model-issues
  text: '[Provider & Model Issues](#provider--model-issues)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: terminal-issuesterminal-issues
  text: '[Terminal Issues](#terminal-issues)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: messaging-issuesmessaging-issues
  text: '[Messaging Issues](#messaging-issues)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: performance-issuesperformance-issues
  text: '[Performance Issues](#performance-issues)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: mcp-issuesmcp-issues
  text: '[MCP Issues](#mcp-issues)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: profilesprofileshow-do-profiles-differ-from-just-setti
  text: '[Profiles](#profiles)[How do profiles differ from just setting HERMES_HOME?](#how-do-profiles-differ-from-just-setting-hermes_home)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: can-two-profiles-share-the-same-bot-tokencan-two-profil
  text: '[Can two profiles share the same bot token?](#can-two-profiles-share-the-same-bot-token)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: do-profiles-share-memory-or-sessionsdo-profiles-share-m
  text: '[Do profiles share memory or sessions?](#do-profiles-share-memory-or-sessions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: what-happens-when-i-run-hermes-updatewhat-happens-whe
  text: '[What happens when I run `hermes update`?](#what-happens-when-i-run-hermes-update)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: can-i-move-a-profile-to-a-different-machinecan-i-move-a
  text: '[Can I move a profile to a different machine?](#can-i-move-a-profile-to-a-different-machine)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: how-many-profiles-can-i-runhow-many-profiles-can-i-run
  text: '[How many profiles can I run?](#how-many-profiles-can-i-run)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: workflows-patternsworkflows--patternsusing-different
  text: '[Workflows & Patterns](#workflows--patterns)[Using different models for different
    tasks (multi-model workflows)](#using-different-models-for-different-tasks-multi-model-workflows)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: running-multiple-agents-on-one-whatsapp-number-per-chat-bi
  text: '[Running multiple agents on one WhatsApp number (per-chat binding)](#running-multiple-agents-on-one-whatsapp-number-per-chat-binding)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: controlling-what-shows-up-in-telegram-hiding-logs-and-reas
  text: '[Controlling what shows up in Telegram (hiding logs and reasoning)](#controlling-what-shows-up-in-telegram-hiding-logs-and-reasoning)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: managing-skills-on-telegram-slash-command-limitmanagin
  text: '[Managing skills on Telegram (slash command limit)](#managing-skills-on-telegram-slash-command-limit)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: shared-thread-sessions-multiple-users-one-conversation
  text: '[Shared thread sessions (multiple users, one conversation)](#shared-thread-sessions-multiple-users-one-conversation)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: exporting-hermes-to-another-machineexporting-hermes-to-a
  text: '[Exporting Hermes to another machine](#exporting-hermes-to-another-machine)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: permission-denied-when-reloading-shell-after-installperm
  text: '[Permission denied when reloading shell after install](#permission-denied-when-reloading-shell-after-install)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: error-400-on-first-agent-runerror-400-on-first-agent-run
  text: '[Error 400 on first agent run](#error-400-on-first-agent-run)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: still-stuckstill-stuck
  text: '[Still Stuck?](#still-stuck)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
- id: user-guidedocsuser-guidecli
  text: '[User Guide](/docs/user-guide/cli)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: developer-guidedocsdeveloper-guidearchitecture
  text: '[Developer Guide](/docs/developer-guide/architecture)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: referencedocsreferencecli-commands
  text: '[Reference](/docs/reference/cli-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: github-discussionshttpsgithubcomnousresearchhermes
  text: '[GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: skills-hubhttpsagentskillsio
  text: '[Skills Hub](https://agentskills.io)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: nous-researchhttpsnousresearchcom
  text: '[Nous Research](https://nousresearch.com)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.faq-troubleshooting
    path: entities/faq-troubleshooting.md
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: guides-tutorialsdocsguidestipstips-best-practice
  text: '[Guides & Tutorials](/docs/guides/tips)[Tips & Best Practices](/docs/guides/tips)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: run-local-llms-on-macdocsguideslocal-llm-on-mac
  text: '[Run Local LLMs on Mac](/docs/guides/local-llm-on-mac)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: tutorial-daily-briefing-botdocsguidesdaily-briefing-b
  text: '[Tutorial: Daily Briefing Bot](/docs/guides/daily-briefing-bot)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: tutorial-team-telegram-assistantdocsguidesteam-telegr
  text: '[Tutorial: Team Telegram Assistant](/docs/guides/team-telegram-assistant)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: using-hermes-as-a-python-librarydocsguidespython-libra
  text: '[Using Hermes as a Python Library](/docs/guides/python-library)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-soulmd-with-hermesdocsguidesuse-soul-with-hermes
  text: '[Use SOUL.md with Hermes](/docs/guides/use-soul-with-hermes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-voice-mode-with-hermesdocsguidesuse-voice-mode-wit
  text: '[Use Voice Mode with Hermes](/docs/guides/use-voice-mode-with-hermes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: build-a-plugindocsguidesbuild-a-hermes-plugin
  text: '[Build a Plugin](/docs/guides/build-a-hermes-plugin)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: automate-anything-with-crondocsguidesautomate-with-cro
  text: '[Automate Anything with Cron](/docs/guides/automate-with-cron)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: automation-templatesdocsguidesautomation-templates
  text: '[Automation Templates](/docs/guides/automation-templates)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: cron-troubleshootingdocsguidescron-troubleshooting
  text: '[Cron Troubleshooting](/docs/guides/cron-troubleshooting)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: working-with-skillsdocsguideswork-with-skills
  text: '[Working with Skills](/docs/guides/work-with-skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: delegation-parallel-workdocsguidesdelegation-pattern
  text: '[Delegation & Parallel Work](/docs/guides/delegation-patterns)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: tutorial-github-pr-review-agentdocsguidesgithub-pr-re
  text: '[Tutorial: GitHub PR Review Agent](/docs/guides/github-pr-review-agent)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: github-pr-reviews-via-webhookdocsguideswebhook-github
  text: '[GitHub PR Reviews via Webhook](/docs/guides/webhook-github-pr-review)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: migrate-from-openclawdocsguidesmigrate-from-openclaw
  text: '[Migrate from OpenClaw](/docs/guides/migrate-from-openclaw)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: aws-bedrockdocsguidesaws-bedrock
  text: '[AWS Bedrock](/docs/guides/aws-bedrock)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: guides-tutorials
  text: Guides & Tutorials
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: you-want-a-hands-free-cli-workflow
  text: you want a hands-free CLI workflow
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: you-want-spoken-responses-in-telegram-or-discord
  text: you want spoken responses in Telegram or Discord
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: you-want-hermes-sitting-in-a-discord-voice-channel-for-live
  text: you want Hermes sitting in a Discord voice channel for live conversation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: you-want-quick-idea-capture-debugging-or-back-and-forth-wh
  text: you want quick idea capture, debugging, or back-and-forth while walking around
    instead of typing
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: get-text-working-first
  text: get text working first
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: enable-voice-replies-second
  text: enable voice replies second
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: move-to-discord-voice-channels-last-if-you-want-the-full-exp
  text: move to Discord voice channels last if you want the full experience
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: hermes-starts
  text: Hermes starts
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: your-provider-is-configured
  text: your provider is configured
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: the-agent-can-answer-text-prompts-normally
  text: the agent can answer text prompts normally
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: portaudio-microphone-input-playback-for-cli-voice-mode
  text: "`portaudio` \u2192 microphone input / playback for CLI voice mode"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: ffmpeg-audio-conversion-for-tts-and-messaging-delivery
  text: "`ffmpeg` \u2192 audio conversion for TTS and messaging delivery"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: opus-discord-voice-codec-support
  text: "`opus` \u2192 Discord voice codec support"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: espeak-ng-phonemizer-backend-for-neutts
  text: "`espeak-ng` \u2192 phonemizer backend for NeuTTS"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: stt-provider-local
  text: 'STT provider: `local`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: tts-provider-edge
  text: 'TTS provider: `edge`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: local-best-default-for-privacy-and-zero-cost-use
  text: "`local` \u2192 best default for privacy and zero-cost use"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: groq-very-fast-cloud-transcription
  text: "`groq` \u2192 very fast cloud transcription"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: openai-good-paid-fallback
  text: "`openai` \u2192 good paid fallback"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: edge-free-and-good-enough-for-most-users
  text: "`edge` \u2192 free and good enough for most users"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: neutts-free-localon-device-tts
  text: "`neutts` \u2192 free local/on-device TTS"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: elevenlabs-best-quality
  text: "`elevenlabs` \u2192 best quality"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: openai-good-middle-ground
  text: "`openai` \u2192 good middle ground"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: mistral-multilingual-native-opus
  text: "`mistral` \u2192 multilingual, native Opus"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: press-ctrlb
  text: press `Ctrl+B`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: wait-for-silence-detection-to-stop-recording-automatically
  text: wait for silence detection to stop recording automatically
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: hermes-transcribes-and-responds
  text: Hermes transcribes and responds
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: if-tts-is-on-it-speaks-the-answer
  text: if TTS is on, it speaks the answer
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: the-loop-can-automatically-restart-for-continuous-use
  text: the loop can automatically restart for continuous use
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: read-the-last-error-again
  text: '"Read the last error again"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: explain-the-root-cause-in-simpler-terms
  text: '"Explain the root cause in simpler terms"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: now-give-me-the-exact-fix
  text: '"Now give me the exact fix"'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: walking-around-while-thinking
  text: walking around while thinking
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: dictating-half-formed-ideas
  text: dictating half-formed ideas
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: asking-hermes-to-structure-your-thoughts-in-real-time
  text: asking Hermes to structure your thoughts in real time
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: voice-on-if-you-want-spoken-replies-only-for-voice-origin
  text: '`/voice on` if you want spoken replies only for voice-originating messages'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: voice-tts-if-you-want-a-full-spoken-assistant-all-the-tim
  text: '`/voice tts` if you want a full spoken assistant all the time'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: you-are-away-from-your-machine
  text: you are away from your machine
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: you-want-to-send-voice-notes-and-get-quick-spoken-replies
  text: you want to send voice notes and get quick spoken replies
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: you-want-hermes-to-function-like-a-portable-research-or-ops
  text: you want Hermes to function like a portable research or ops assistant
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: preferably-use-voice-activity
  text: preferably Use Voice Activity
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: presence-intent
  text: Presence Intent
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: server-members-intent
  text: Server Members Intent
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: message-content-intent
  text: Message Content Intent
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: users-speak-in-the-vc
  text: users speak in the VC
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: hermes-detects-speech-boundaries
  text: Hermes detects speech boundaries
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: transcripts-are-posted-in-the-associated-text-channel
  text: transcripts are posted in the associated text channel
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: hermes-responds-in-text-and-audio
  text: Hermes responds in text and audio
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: keep-discord-allowed-users-tight
  text: keep `DISCORD_ALLOWED_USERS` tight
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: use-a-dedicated-bottesting-channel-at-first
  text: use a dedicated bot/testing channel at first
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: verify-stt-and-tts-work-in-ordinary-text-chat-voice-mode-bef
  text: verify STT and TTS work in ordinary text-chat voice mode before trying VC
    mode
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: stt-local-large-v3-or-groq-whisper-large-v3
  text: 'STT: local `large-v3` or Groq `whisper-large-v3`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: tts-elevenlabs
  text: 'TTS: ElevenLabs'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: stt-local-base-or-groq
  text: 'STT: local `base` or Groq'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: stt-local
  text: 'STT: local'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: your-discord-user-id-is-in-discord-allowed-users
  text: your Discord user ID is in `DISCORD_ALLOWED_USERS`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: you-are-not-muted
  text: you are not muted
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: privileged-intents-are-enabled
  text: privileged intents are enabled
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: the-bot-has-connectspeak-permissions
  text: the bot has Connect/Speak permissions
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: tts-provider-config
  text: TTS provider config
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: api-key-quota-for-elevenlabs-or-openai
  text: API key / quota for ElevenLabs or OpenAI
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: ffmpeg-install-for-edge-conversion-paths
  text: '`ffmpeg` install for Edge conversion paths'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: quieter-environment
  text: quieter environment
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: higher-silence-threshold
  text: higher `silence_threshold`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: different-stt-providermodel
  text: different STT provider/model
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: shorter-clearer-utterances
  text: shorter, clearer utterances
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: get-text-hermes-working
  text: get text Hermes working
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: install-hermes-agentvoice
  text: install `hermes-agent[voice]`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: use-cli-voice-mode-with-local-stt-edge-tts
  text: use CLI voice mode with local STT + Edge TTS
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: then-enable-voice-on-in-telegram-or-discord
  text: then enable `/voice on` in Telegram or Discord
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: only-after-that-try-discord-vc-mode
  text: only after that, try Discord VC mode
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: voice-mode-feature-referencedocsuser-guidefeaturesvoi
  text: '[Voice Mode feature reference](/docs/user-guide/features/voice-mode)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: messaging-gatewaydocsuser-guidemessaging
  text: '[Messaging Gateway](/docs/user-guide/messaging)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: discord-setupdocsuser-guidemessagingdiscord
  text: '[[[entity.discord-setup|Discord Setup]]](/docs/user-guide/messaging/discord)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: telegram-setupdocsuser-guidemessagingtelegram
  text: '[[[entity.telegram-setup|Telegram Setup]]](/docs/user-guide/messaging/telegram)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: choose-your-voice-mode-setupchoose-your-voice-mode-setup
  text: '[Choose your voice mode setup](#choose-your-voice-mode-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: step-1-make-sure-normal-hermes-works-firststep-1-make-s
  text: '[Step 1: make sure normal Hermes works first](#step-1-make-sure-normal-hermes-works-first)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: step-2-install-the-right-extrasstep-2-install-the-right
  text: '[Step 2: install the right extras](#step-2-install-the-right-extras)[CLI
    microphone + playback](#cli-microphone--playback)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: messaging-platformsmessaging-platforms
  text: '[Messaging platforms](#messaging-platforms)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: premium-elevenlabs-ttspremium-elevenlabs-tts
  text: '[Premium ElevenLabs TTS](#premium-elevenlabs-tts)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: local-neutts-optionallocal-neutts-optional
  text: '[Local NeuTTS (optional)](#local-neutts-optional)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: everythingeverything
  text: '[Everything](#everything)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: step-3-install-system-dependenciesstep-3-install-system
  text: '[Step 3: install system dependencies](#step-3-install-system-dependencies)[macOS](#macos)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: ubuntu-debianubuntu--debian
  text: '[Ubuntu / Debian](#ubuntu--debian)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: step-4-choose-stt-and-tts-providersstep-4-choose-stt-an
  text: '[Step 4: choose STT and TTS providers](#step-4-choose-stt-and-tts-providers)[Easiest
    / cheapest setup](#easiest--cheapest-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: environment-file-exampleenvironment-file-example
  text: '[Environment file example](#environment-file-example)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: provider-recommendationsprovider-recommendations
  text: '[Provider recommendations](#provider-recommendations)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: if-you-use-hermes-setupif-you-use-hermes-setup
  text: '[If you use `hermes setup`](#if-you-use-hermes-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: step-5-recommended-configstep-5-recommended-config
  text: '[Step 5: recommended config](#step-5-recommended-config)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: use-case-1-cli-voice-modeuse-case-1-cli-voice-mode
  text: '[Use case 1: CLI voice mode](#use-case-1-cli-voice-mode)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: turn-it-onturn-it-onrecording-flowrecording-flow
  text: '[Turn it on](#turn-it-on)[Recording flow](#recording-flow)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: useful-commandsuseful-commands
  text: '[Useful commands](#useful-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: good-cli-workflowsgood-cli-workflows
  text: '[Good CLI workflows](#good-cli-workflows)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: tuning-cli-behaviortuning-cli-behaviorsilence-threshol
  text: '[Tuning CLI behavior](#tuning-cli-behavior)[Silence threshold](#silence-threshold)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: silence-durationsilence-duration
  text: '[Silence duration](#silence-duration)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: record-keyrecord-key
  text: '[Record key](#record-key)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: use-case-2-voice-replies-in-telegram-or-discorduse-case
  text: '[Use case 2: voice replies in Telegram or Discord](#use-case-2-voice-replies-in-telegram-or-discord)[Start
    the gateway](#start-the-gateway)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: turn-on-voice-repliesturn-on-voice-replies
  text: '[Turn on voice replies](#turn-on-voice-replies)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: modesmodes
  text: '[Modes](#modes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: when-to-use-which-modewhen-to-use-which-mode
  text: '[When to use which mode](#when-to-use-which-mode)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: good-messaging-workflowsgood-messaging-workflows
  text: '[Good messaging workflows](#good-messaging-workflows)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: use-case-3-discord-voice-channelsuse-case-3-discord-voi
  text: '[Use case 3: Discord voice channels](#use-case-3-discord-voice-channels)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: required-discord-permissionsrequired-discord-permissions
  text: '[Required Discord permissions](#required-discord-permissions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: join-and-leavejoin-and-leavewhat-happens-when-joined
  text: '[Join and leave](#join-and-leave)[What happens when joined](#what-happens-when-joined)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: best-practices-for-discord-vc-usebest-practices-for-disc
  text: '[Best practices for Discord VC use](#best-practices-for-discord-vc-use)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: voice-quality-recommendationsvoice-quality-recommendatio
  text: '[Voice quality recommendations](#voice-quality-recommendations)[Best quality
    setup](#best-quality-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: best-speed-convenience-setupbest-speed--convenience-se
  text: '[Best speed / convenience setup](#best-speed--convenience-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: best-zero-cost-setupbest-zero-cost-setup
  text: '[Best zero-cost setup](#best-zero-cost-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: common-failure-modescommon-failure-modesno-audio-devi
  text: '[Common failure modes](#common-failure-modes)["No audio device found"](#no-audio-device-found)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: bot-joins-but-hears-nothingbot-joins-but-hears-nothing
  text: '["Bot joins but hears nothing"](#bot-joins-but-hears-nothing)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: it-transcribes-but-does-not-speakit-transcribes-but-do
  text: '["It transcribes but does not speak"](#it-transcribes-but-does-not-speak)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: whisper-outputs-garbagewhisper-outputs-garbage
  text: '["Whisper outputs garbage"](#whisper-outputs-garbage)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: it-works-in-dms-but-not-in-server-channelsit-works-in
  text: '["It works in DMs but not in server channels"](#it-works-in-dms-but-not-in-server-channels)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: suggested-first-week-setupsuggested-first-week-setup
  text: '[Suggested first-week setup](#suggested-first-week-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: where-to-read-nextwhere-to-read-next
  text: '[Where to read next](#where-to-read-next)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-voice-mode-with-hermes
    path: entities/use-voice-mode-with-hermes.md
- id: use-mcp-with-hermes
  text: Use MCP with Hermes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: a-tool-already-exists-in-mcp-form-and-you-do-not-want-to-bui
  text: a tool already exists in MCP form and you do not want to build a native Hermes
    tool
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: you-want-hermes-to-operate-against-a-local-or-remote-system
  text: you want Hermes to operate against a local or remote system through a clean
    RPC layer
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: you-want-fine-grained-per-server-exposure-control
  text: you want fine-grained per-server exposure control
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: you-want-to-connect-hermes-to-internal-apis-databases-or-c
  text: you want to connect Hermes to internal APIs, databases, or company systems
    without modifying Hermes core
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: a-built-in-hermes-tool-already-solves-the-job-well
  text: a built-in Hermes tool already solves the job well
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: the-server-exposes-a-huge-dangerous-tool-surface-and-you-are
  text: the server exposes a huge dangerous tool surface and you are not prepared
    to filter it
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: you-only-need-one-very-narrow-integration-and-a-native-tool
  text: you only need one very narrow integration and a native tool would be simpler
    and safer
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: hermes-remains-the-agent
  text: Hermes remains the agent
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: mcp-servers-contribute-tools
  text: MCP servers contribute tools
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: hermes-discovers-those-tools-at-startup-or-reload-time
  text: Hermes discovers those tools at startup or reload time
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: the-model-can-use-them-like-normal-tools
  text: the model can use them like normal tools
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: you-control-how-much-of-each-server-is-visible
  text: you control how much of each server is visible
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: hermes-bannerstatus-should-show-mcp-integration-when-config
  text: Hermes banner/status should show MCP integration when configured
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: ask-hermes-what-tools-it-has-available
  text: ask Hermes what tools it has available
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: use-reload-mcp-after-config-changes
  text: use `/reload-mcp` after config changes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: check-logs-if-the-server-failed-to-connect
  text: check logs if the server failed to connect
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: server-native-mcp-tools
  text: Server-native MCP tools
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: filtered-with
  text: 'filtered with:'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: toolsexclude
  text: '`tools.exclude`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: hermes-added-utility-wrappers
  text: Hermes-added utility wrappers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: toolsprompts
  text: '`tools.prompts`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: your-config-allows-them-and
  text: your config allows them, and
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: the-mcp-server-session-actually-supports-those-capabilities
  text: the MCP server session actually supports those capabilities
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: use-toolsinclude
  text: use `tools.include`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: start-with-the-smallest-set-possible
  text: start with the smallest set possible
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: filesystem-server-rooted-to-one-project-dir-not-your-whole
  text: filesystem server rooted to one project dir, not your whole home directory
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: git-server-pointed-at-one-repo
  text: git server pointed at one repo
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: internal-api-server-with-read-heavy-tool-exposure-by-default
  text: internal API server with read-heavy tool exposure by default
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: includeexclude-lists
  text: include/exclude lists
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: enabled-flags
  text: enabled flags
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: resourcesprompts-toggles
  text: resources/prompts toggles
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: auth-headers-env
  text: auth headers / env
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: filtered-by-toolsinclude
  text: filtered by `tools.include`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: excluded-by-toolsexclude
  text: excluded by `tools.exclude`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: utility-wrappers-disabled-via-resources-false-or-prompts
  text: 'utility wrappers disabled via `resources: false` or `prompts: false`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: server-does-not-actually-support-resourcesprompts
  text: server does not actually support resources/prompts
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: enabled-false-was-not-left-in-config
  text: '`enabled: false` was not left in config'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: commandruntime-exists-npx-uvx-etc
  text: command/runtime exists (`npx`, `uvx`, etc.)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: http-endpoint-is-reachable
  text: HTTP endpoint is reachable
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: auth-env-or-headers-are-correct
  text: auth env or headers are correct
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: filesystem
  text: filesystem
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: fetch-documentation-mcp-servers
  text: fetch / documentation MCP servers
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: one-narrow-internal-api
  text: one narrow internal API
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: giant-business-systems-with-lots-of-destructive-actions-and
  text: giant business systems with lots of destructive actions and no filtering
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: anything-you-do-not-understand-well-enough-to-constrain
  text: anything you do not understand well enough to constrain
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: mental-modelmental-model
  text: '[Mental model](#mental-model)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: step-1-install-mcp-supportstep-1-install-mcp-support
  text: '[Step 1: install MCP support](#step-1-install-mcp-support)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: step-2-add-one-server-firststep-2-add-one-server-first
  text: '[Step 2: add one server first](#step-2-add-one-server-first)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: step-3-verify-mcp-loadedstep-3-verify-mcp-loaded
  text: '[Step 3: verify MCP loaded](#step-3-verify-mcp-loaded)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: step-4-start-filtering-immediatelystep-4-start-filterin
  text: '[Step 4: start filtering immediately](#step-4-start-filtering-immediately)[Example:
    whitelist only what you want](#example-whitelist-only-what-you-want)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: example-blacklist-dangerous-actionsexample-blacklist-da
  text: '[Example: blacklist dangerous actions](#example-blacklist-dangerous-actions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: example-disable-utility-wrappers-tooexample-disable-uti
  text: '[Example: disable utility wrappers too](#example-disable-utility-wrappers-too)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: what-does-filtering-actually-affectwhat-does-filtering
  text: '[What does filtering actually affect?](#what-does-filtering-actually-affect)[Utility
    wrappers you may see](#utility-wrappers-you-may-see)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: common-patternscommon-patternspattern-1-local-project
  text: '[Common patterns](#common-patterns)[Pattern 1: local project assistant](#pattern-1-local-project-assistant)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: pattern-2-github-triage-assistantpattern-2-github-triag
  text: '[Pattern 2: GitHub triage assistant](#pattern-2-github-triage-assistant)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: pattern-3-internal-api-assistantpattern-3-internal-api
  text: '[Pattern 3: internal API assistant](#pattern-3-internal-api-assistant)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: pattern-4-documentation-knowledge-serverspattern-4-do
  text: '[Pattern 4: documentation / knowledge servers](#pattern-4-documentation--knowledge-servers)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: tutorial-end-to-end-setup-with-filteringtutorial-end-to
  text: '[Tutorial: end-to-end setup with filtering](#tutorial-end-to-end-setup-with-filtering)[Phase
    1: add GitHub MCP with a tight whitelist](#phase-1-add-github-mcp-with-a-tight-whitelist)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: phase-2-expand-only-when-neededphase-2-expand-only-when
  text: '[Phase 2: expand only when needed](#phase-2-expand-only-when-needed)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: phase-3-add-a-second-server-with-different-policyphase
  text: '[Phase 3: add a second server with different policy](#phase-3-add-a-second-server-with-different-policy)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: safe-usage-recommendationssafe-usage-recommendationspr
  text: '[Safe usage recommendations](#safe-usage-recommendations)[Prefer allowlists
    for dangerous systems](#prefer-allowlists-for-dangerous-systems)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: disable-unused-utilitiesdisable-unused-utilities
  text: '[Disable unused utilities](#disable-unused-utilities)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: keep-servers-scoped-narrowlykeep-servers-scoped-narrowly
  text: '[Keep servers scoped narrowly](#keep-servers-scoped-narrowly)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: reload-after-config-changesreload-after-config-changes
  text: '[Reload after config changes](#reload-after-config-changes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: troubleshooting-by-symptomtroubleshooting-by-symptomt
  text: '[Troubleshooting by symptom](#troubleshooting-by-symptom)["The server connects
    but the tools I expected are missing"](#the-server-connects-but-the-tools-i-expected-are-missing)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: the-server-is-configured-but-nothing-loadsthe-server-i
  text: '["The server is configured but nothing loads"](#the-server-is-configured-but-nothing-loads)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: why-do-i-see-fewer-tools-than-the-mcp-server-advertises
  text: '["Why do I see fewer tools than the MCP server advertises?"](#why-do-i-see-fewer-tools-than-the-mcp-server-advertises)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: how-do-i-remove-an-mcp-server-without-deleting-the-config
  text: '["How do I remove an MCP server without deleting the config?"](#how-do-i-remove-an-mcp-server-without-deleting-the-config)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: recommended-first-mcp-setupsrecommended-first-mcp-setups
  text: '[Recommended first MCP setups](#recommended-first-mcp-setups)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: related-docsrelated-docs
  text: '[Related docs](#related-docs)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.use-mcp-with-hermes
    path: entities/use-mcp-with-hermes.md
- id: tips-best-practices
  text: Tips & Best Practices
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: prefer-opening-files-with-an-explicit-utf-8-encoding
  text: 'Prefer opening files with an explicit UTF-8 encoding:'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: in-powershell-you-can-also-switch-the-current-session-to-ut
  text: 'In PowerShell, you can also switch the current session to UTF-8 for console
    and native command output:'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: provide-context-up-frontprovide-context-up-front
  text: '[Provide Context Up Front](#provide-context-up-front)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-context-files-for-recurring-instructionsuse-context
  text: '[Use Context Files for Recurring Instructions](#use-context-files-for-recurring-instructions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: let-the-agent-use-its-toolslet-the-agent-use-its-tools
  text: '[Let the Agent Use Its Tools](#let-the-agent-use-its-tools)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-skills-for-complex-workflowsuse-skills-for-complex-w
  text: '[Use Skills for Complex Workflows](#use-skills-for-complex-workflows)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: cli-power-user-tipscli-power-user-tipsmulti-line-input
  text: '[CLI Power User Tips](#cli-power-user-tips)[Multi-Line Input](#multi-line-input)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: paste-detectionpaste-detection
  text: '[Paste Detection](#paste-detection)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: interrupt-and-redirectinterrupt-and-redirect
  text: '[Interrupt and Redirect](#interrupt-and-redirect)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: resume-sessions-with--cresume-sessions-with--c
  text: '[Resume Sessions with `-c`](#resume-sessions-with--c)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: clipboard-image-pasteclipboard-image-paste
  text: '[Clipboard Image Paste](#clipboard-image-paste)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: slash-command-autocompleteslash-command-autocomplete
  text: '[Slash Command Autocomplete](#slash-command-autocomplete)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: context-filescontext-filesagentsmd-your-project39
  text: '[Context Files](#context-files)[AGENTS.md: Your Project&#39;s Brain](#agentsmd-your-projects-brain)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: soulmd-customize-personalitysoulmd-customize-personali
  text: '[SOUL.md: Customize Personality](#soulmd-customize-personality)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: cursorrules-compatibilitycursorrules-compatibility
  text: '[.cursorrules Compatibility](#cursorrules-compatibility)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: discoverydiscovery
  text: '[Discovery](#discovery)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: memory-skillsmemory--skillsmemory-vs-skills-what-g
  text: '[Memory & Skills](#memory--skills)[Memory vs. Skills: What Goes Where](#memory-vs-skills-what-goes-where)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: when-to-create-skillswhen-to-create-skills
  text: '[When to Create Skills](#when-to-create-skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: managing-memory-capacitymanaging-memory-capacity
  text: '[Managing Memory Capacity](#managing-memory-capacity)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: let-the-agent-rememberlet-the-agent-remember
  text: '[Let the Agent Remember](#let-the-agent-remember)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: performance-costperformance--costdon39t-break-the
  text: '[Performance & Cost](#performance--cost)[Don&#39;t Break the Prompt Cache](#dont-break-the-prompt-cache)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-compress-before-hitting-limitsuse-compress-before-h
  text: '[Use /compress Before Hitting Limits](#use-compress-before-hitting-limits)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: delegate-for-parallel-workdelegate-for-parallel-work
  text: '[Delegate for Parallel Work](#delegate-for-parallel-work)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-execute-code-for-batch-operationsuse-execute-code-fo
  text: '[Use execute_code for Batch Operations](#use-execute_code-for-batch-operations)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: choose-the-right-modelchoose-the-right-model
  text: '[Choose the Right Model](#choose-the-right-model)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: messaging-tipsmessaging-tipsset-a-home-channelset-a
  text: '[Messaging Tips](#messaging-tips)[Set a Home Channel](#set-a-home-channel)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-title-to-organize-sessionsuse-title-to-organize-ses
  text: '[Use /title to Organize Sessions](#use-title-to-organize-sessions)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: dm-pairing-for-team-accessdm-pairing-for-team-access
  text: '[DM Pairing for Team Access](#dm-pairing-for-team-access)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: tool-progress-display-modestool-progress-display-modes
  text: '[Tool Progress Display Modes](#tool-progress-display-modes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: securitysecurityuse-docker-for-untrusted-codeuse-do
  text: '[Security](#security)[Use Docker for Untrusted Code](#use-docker-for-untrusted-code)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: avoid-windows-encoding-pitfallsavoid-windows-encoding-pi
  text: '[Avoid Windows Encoding Pitfalls](#avoid-windows-encoding-pitfalls)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: review-before-choosing-alwaysreview-before-choosing-al
  text: '[Review Before Choosing "Always"](#review-before-choosing-always)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: command-approval-is-your-safety-netcommand-approval-is-y
  text: '[Command Approval Is Your Safety Net](#command-approval-is-your-safety-net)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: use-allowlists-for-messaging-botsuse-allowlists-for-mess
  text: '[Use Allowlists for Messaging Bots](#use-allowlists-for-messaging-bots)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.tips-best-practices
    path: entities/tips-best-practices.md
- id: installationdocsgetting-startedinstallation
  text: '[[[entity.installation|Installation]]](/docs/getting-started/[[entity.installation|Installation]])'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: android-termuxdocsgetting-startedtermux
  text: '[Android / Termux](/docs/getting-started/termux)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: nix-nixos-setupdocsgetting-startednix-setup
  text: '[Nix & NixOS Setup](/docs/getting-started/nix-setup)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: updating-uninstallingdocsgetting-startedupdating
  text: '[Updating & Uninstalling](/docs/getting-started/updating)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: learning-pathdocsgetting-startedlearning-path
  text: '[Learning Path](/docs/getting-started/learning-path)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: getting-started
  text: Getting Started
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.installation
    path: entities/installation.md
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: learning-path
  text: Learning Path
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: know-your-level-jump-to-the-experience-level-tableby-ex
  text: Know your level? Jump to the [experience-level table](#by-experience-level)
    and follow the reading order for your tier.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: have-a-specific-goal-skip-to-by-use-caseby-use-case-an
  text: Have a specific goal? Skip to [By Use Case](#by-use-case) and find the scenario
    that matches.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: just-browsing-check-the-key-featureskey-features-at-a-g
  text: Just browsing? Check the [Key Features](#key-features-at-a-glance) table for
    a quick overview of everything Hermes Agent can do.
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: quickstartdocsgetting-startedquickstart
  text: '[[[entity.quickstart|Quickstart]]](/docs/getting-started/[[entity.quickstart|Quickstart]])'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: cli-usagedocsuser-guidecli
  text: '[CLI Usage](/docs/user-guide/cli)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: code-executiondocsuser-guidefeaturescode-execution
  text: '[Code Execution](/docs/user-guide/features/code-execution)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: tips-tricksdocsguidestips
  text: '[Tips & Tricks](/docs/guides/tips)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: messaging-overviewdocsuser-guidemessaging
  text: '[Messaging Overview](/docs/user-guide/messaging)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: telegram-setupdocsuser-guidemessagingtelegram
  text: '[Telegram Setup](/docs/user-guide/messaging/telegram)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: discord-setupdocsuser-guidemessagingdiscord
  text: '[Discord Setup](/docs/user-guide/messaging/discord)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: voice-modedocsuser-guidefeaturesvoice-mode
  text: '[Voice Mode](/docs/user-guide/features/voice-mode)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: securitydocsuser-guidesecurity
  text: '[Security](/docs/user-guide/security)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: daily-briefing-botdocsguidesdaily-briefing-bot
  text: '[Daily Briefing Bot](/docs/guides/daily-briefing-bot)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: team-telegram-assistantdocsguidesteam-telegram-assista
  text: '[Team Telegram Assistant](/docs/guides/team-telegram-assistant)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: cron-schedulingdocsuser-guidefeaturescron
  text: '[Cron Scheduling](/docs/user-guide/features/cron)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: batch-processingdocsuser-guidefeaturesbatch-processin
  text: '[Batch Processing](/docs/user-guide/features/batch-processing)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: delegationdocsuser-guidefeaturesdelegation
  text: '[Delegation](/docs/user-guide/features/delegation)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: hooksdocsuser-guidefeatureshooks
  text: '[Hooks](/docs/user-guide/features/hooks)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: tools-overviewdocsuser-guidefeaturestools
  text: '[Tools Overview](/docs/user-guide/features/tools)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: skills-overviewdocsuser-guidefeaturesskills
  text: '[Skills Overview](/docs/user-guide/features/skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: architecturedocsdeveloper-guidearchitecture
  text: '[Architecture](/docs/developer-guide/architecture)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: adding-toolsdocsdeveloper-guideadding-tools
  text: '[Adding Tools](/docs/developer-guide/adding-tools)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: creating-skillsdocsdeveloper-guidecreating-skills
  text: '[Creating Skills](/docs/developer-guide/creating-skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: rl-trainingdocsuser-guidefeaturesrl-training
  text: '[RL Training](/docs/user-guide/features/rl-training)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: provider-routingdocsuser-guidefeaturesprovider-routin
  text: '[Provider Routing](/docs/user-guide/features/provider-routing)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: python-library-guidedocsguidespython-library
  text: '[Python Library Guide](/docs/guides/python-library)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: toolsdocsuser-guidefeaturestools
  text: '[Tools](/docs/user-guide/features/tools)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: just-finished-installing-head-to-the-quickstartdocsg
  text: "Just finished installing? \u2192 Head to the [[[entity.quickstart|Quickstart]]](/docs/getting-started/[[entity.quickstart|Quickstart]])\
    \ to run your first conversation."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: completed-the-[[entity.quickstart|Quickstart]]-read-cli-usagedocsuser-guid
  text: "Completed the [[entity.quickstart|Quickstart]]? \u2192 Read [CLI Usage](/docs/user-guide/cli)\
    \ and [Configuration](/docs/user-guide/configuration) to customize your setup."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: comfortable-with-the-basics-explore-toolsdocsuser-gu
  text: "Comfortable with the basics? \u2192 Explore [Tools](/docs/user-guide/features/tools),\
    \ [Skills](/docs/user-guide/features/skills), and [Memory](/docs/user-guide/features/memory)\
    \ to unlock the full power of the agent."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: setting-up-for-a-team-read-securitydocsuser-guidese
  text: "Setting up for a team? \u2192 Read [Security](/docs/user-guide/security)\
    \ and [Sessions](/docs/user-guide/sessions) to understand access control and conversation\
    \ management."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: ready-to-build-jump-into-the-developer-guidedocsdeve
  text: "Ready to build? \u2192 Jump into the [Developer Guide](/docs/developer-guide/architecture)\
    \ to understand the internals and start contributing."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: want-practical-examples-check-out-the-guidesdocsguid
  text: "Want practical examples? \u2192 Check out the [Guides](/docs/guides/tips)\
    \ section for real-world projects and tips."
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: by-experience-levelby-experience-level
  text: '[By Experience Level](#by-experience-level)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: by-use-caseby-use-casei-want-a-cli-coding-assistant
  text: '[By Use Case](#by-use-case)["I want a CLI coding assistant"](#i-want-a-cli-coding-assistant)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: i-want-a-telegramdiscord-boti-want-a-telegramdiscord
  text: '["I want a Telegram/Discord bot"](#i-want-a-telegramdiscord-bot)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: i-want-to-automate-tasksi-want-to-automate-tasks
  text: '["I want to automate tasks"](#i-want-to-automate-tasks)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: i-want-to-build-custom-toolsskillsi-want-to-build-cus
  text: '["I want to build custom tools/skills"](#i-want-to-build-custom-toolsskills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: i-want-to-train-modelsi-want-to-train-models
  text: '["I want to train models"](#i-want-to-train-models)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: i-want-to-use-it-as-a-python-libraryi-want-to-use-it-a
  text: '["I want to use it as a Python library"](#i-want-to-use-it-as-a-python-library)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: key-features-at-a-glancekey-features-at-a-glance
  text: '[Key Features at a Glance](#key-features-at-a-glance)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: what-to-read-nextwhat-to-read-next
  text: '[What to Read Next](#what-to-read-next)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.learning-path
    path: entities/learning-path.md
- id: installationdocsgetting-startedinstallation
  text: '[Installation](/docs/getting-started/installation)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: installation
  text: Installation
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: uses-termux-pkg-for-system-dependencies-git-python
  text: uses Termux `pkg` for system dependencies (`git`, `python`, `nodejs`, `ripgrep`,
    `ffmpeg`, build tools)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: creates-the-virtualenv-with-python--m-venv
  text: creates the virtualenv with `python -m venv`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: exports-android-api-level-automatically-for-android-wheel
  text: exports `ANDROID_API_LEVEL` automatically for Android wheel builds
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: installs-a-curated-termux-extra-with-pip
  text: installs a curated `.[termux]` extra with `pip`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: skips-the-untested-browser-whatsapp-bootstrap-by-default
  text: skips the untested browser / WhatsApp bootstrap by default
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: uv-fast-python-package-manager
  text: uv (fast Python package manager)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: python-311-via-uv-no-sudo-needed
  text: Python 3.11 (via uv, no sudo needed)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: nodejs-v22-for-browser-automation-and-whatsapp-bridge
  text: Node.js v22 (for browser automation and WhatsApp bridge)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: ripgrep-fast-file-search
  text: ripgrep (fast file search)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: ffmpeg-audio-format-conversion-for-tts
  text: ffmpeg (audio format conversion for TTS)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: android-termuxandroid--termux
  text: '[Android / Termux](#android--termux)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: what-the-installer-doeswhat-the-installer-does
  text: '[What the Installer Does](#what-the-installer-does)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: after-installationafter-installation
  text: '[After Installation](#after-installation)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: manual-developer-installationmanual--developer-install
  text: '[Manual / Developer Installation](#manual--developer-installation)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.installation
    path: entities/installation.md
- id: quickstart
  text: Quickstart
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: brand-new-and-want-the-shortest-path-to-a-working-setup
  text: Brand new and want the shortest path to a working setup
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: switching-providers-and-dont-want-to-lose-time-to-config-mi
  text: Switching providers and don't want to lose time to config mistakes
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: setting-up-hermes-for-a-team-bot-or-always-on-workflow
  text: Setting up Hermes for a team, bot, or always-on workflow
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: tired-of-it-installed-but-it-still-does-nothing
  text: Tired of "it installed, but it still does nothing"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: secrets-and-tokens-hermesenv
  text: "Secrets and tokens \u2192 `~/.hermes/.env`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: non-secret-settings-hermesconfigyaml
  text: "Non-secret settings \u2192 `~/.hermes/config.yaml`"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: the-banner-shows-your-chosen-modelprovider
  text: The banner shows your chosen model/provider
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-replies-without-error
  text: Hermes replies without error
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: it-can-use-a-tool-if-needed-terminal-file-read-web-search
  text: It can use a tool if needed (terminal, file read, web search)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: the-conversation-continues-normally-for-more-than-one-turn
  text: The conversation continues normally for more than one turn
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-tools-tune-tool-access-per-platform
  text: "`hermes tools` \u2014 tune tool access per platform"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-skills-browse-and-install-reusable-workflows
  text: "`hermes skills` \u2014 browse and install reusable workflows"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: cron-only-after-your-bot-or-cli-setup-is-stable
  text: "Cron \u2014 only after your bot or CLI setup is stable"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-doctor
  text: '`hermes doctor`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-model
  text: '`hermes model`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-setup
  text: '`hermes setup`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-sessions-list
  text: '`hermes sessions list`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes---continue
  text: '`hermes --continue`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: hermes-gateway-status
  text: '`hermes gateway status`'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: cli-guidedocsuser-guidecli-master-the-terminal-inte
  text: "[CLI Guide](/docs/user-guide/cli) \u2014 Master the terminal interface"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: configurationdocsuser-guideconfiguration-customize
  text: "[Configuration](/docs/user-guide/configuration) \u2014 Customize your setup"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: messaging-gatewaydocsuser-guidemessaging-connect-t
  text: "[Messaging Gateway](/docs/user-guide/messaging/) \u2014 Connect Telegram,\
    \ Discord, Slack, WhatsApp, Signal, Email, or Home Assistant"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: tools-toolsetsdocsuser-guidefeaturestools-explor
  text: "[Tools & Toolsets](/docs/user-guide/features/tools) \u2014 Explore available\
    \ capabilities"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: ai-providersdocsintegrationsproviders-full-provider
  text: "[AI Providers](/docs/integrations/providers) \u2014 Full provider list and\
    \ setup details"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: skills-systemdocsuser-guidefeaturesskills-reusable
  text: "[Skills System](/docs/user-guide/features/skills) \u2014 Reusable workflows\
    \ and knowledge"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: tips-best-practicesdocsguidestips-power-user-tips
  text: "[Tips & Best Practices](/docs/guides/tips) \u2014 Power user tips"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: the-fastest-paththe-fastest-path
  text: '[The fastest path](#the-fastest-path)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: 1-install-hermes-agent1-install-hermes-agent
  text: '[1. Install Hermes Agent](#1-install-hermes-agent)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: 2-choose-a-provider2-choose-a-providerhow-settings-ar
  text: '[2. Choose a Provider](#2-choose-a-provider)[How settings are stored](#how-settings-are-stored)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: 3-run-your-first-chat3-run-your-first-chat
  text: '[3. Run Your First Chat](#3-run-your-first-chat)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: 4-verify-sessions-work4-verify-sessions-work
  text: '[4. Verify Sessions Work](#4-verify-sessions-work)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: 5-try-key-features5-try-key-featuresuse-the-terminal
  text: '[5. Try Key Features](#5-try-key-features)[Use the terminal](#use-the-terminal)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: slash-commandsslash-commands
  text: '[Slash commands](#slash-commands)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: multi-line-inputmulti-line-input
  text: '[Multi-line input](#multi-line-input)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: interrupt-the-agentinterrupt-the-agent
  text: '[Interrupt the agent](#interrupt-the-agent)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: 6-add-the-next-layer6-add-the-next-layerbot-or-shared
  text: '[6. Add the Next Layer](#6-add-the-next-layer)[Bot or shared assistant](#bot-or-shared-assistant)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: automation-and-toolsautomation-and-tools
  text: '[Automation and tools](#automation-and-tools)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: sandboxed-terminalsandboxed-terminal
  text: '[Sandboxed terminal](#sandboxed-terminal)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: voice-modevoice-mode
  text: '[Voice mode](#voice-mode)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: skillsskills
  text: '[Skills](#skills)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: mcp-serversmcp-servers
  text: '[MCP servers](#mcp-servers)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: editor-integration-acpeditor-integration-acp
  text: '[Editor integration (ACP)](#editor-integration-acp)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: common-failure-modescommon-failure-modes
  text: '[Common Failure Modes](#common-failure-modes)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: recovery-toolkitrecovery-toolkit
  text: '[Recovery Toolkit](#recovery-toolkit)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: quick-referencequick-reference
  text: '[Quick Reference](#quick-reference)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.quickstart
    path: entities/quickstart.md
- id: the-update-ignores-sighup-so-closing-your-ssh-session-or-te
  text: The update ignores SIGHUP, so closing your SSH session or terminal window
    no longer kills it mid-install
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.updating-uninstalling
    path: entities/updating-uninstalling.md
- id: all-output-is-mirrored-to-hermeslogsupdatelog-while
  text: All output is mirrored to `~/.hermes/logs/update.log` while the update runs
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.updating-uninstalling
    path: entities/updating-uninstalling.md
- id: ctrl-c-sigint-and-system-shutdown-sigterm-are-still-hono
  text: Ctrl-C (SIGINT) and system shutdown (SIGTERM) are still honored
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.updating-uninstalling
    path: entities/updating-uninstalling.md
- id: pre-built-binary-with-all-deps-then-use-the-standard-cli-w
  text: "Pre-built binary with all deps \u2014 then use the standard CLI workflow"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: declarative-config-hardened-systemd-service-managed-secret
  text: Declarative config, hardened systemd service, managed secrets
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: everything-above-plus-a-persistent-ubuntu-container-where-t
  text: Everything above, plus a persistent Ubuntu container where the agent can apt/pip/npm
    install
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: nix-with-flakes-enabled-determinate-nix-recommended-enabl
  text: "Nix with flakes enabled \u2014 Determinate Nix recommended (enables flakes\
    \ by default)"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: api-keys-for-the-services-you-want-to-use-at-minimum-an-op
  text: 'API keys for the services you want to use (at minimum: an OpenRouter or Anthropic
    key)'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: hardened-systemd-service-on-the-host
  text: Hardened systemd service on the host
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: nonewprivileges-protectsystemstrict-privatetmp
  text: NoNewPrivileges, ProtectSystem=strict, PrivateTmp
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: agent-cannot-self-install-packages
  text: Agent cannot self-install packages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: persistent-ubuntu-container-with-nixstore-bind-mounted
  text: Persistent Ubuntu container with /nix/store bind-mounted
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: container-isolation-runs-as-unprivileged-user-inside
  text: Container isolation, runs as unprivileged user inside
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: agent-can-self-install-packages-apt-pip-npm-installs-pers
  text: Agent CAN self-install packages (apt, pip, npm installs persist across restarts)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: change-the-llm-model-settingsmodeldefault-anthropi
  text: Change the LLM model:** `settings.model.default` = "anthropic/claude-sonnet-4"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: use-a-different-provider-endpoint-settingsmodelbase-ur
  text: Use a different provider endpoint:** `settings.model.base_url` = "https://openrouter.ai/api/v1"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: add-api-keys-environmentfiles-with-sops-nix-or-agenix
  text: Add API keys:** `environmentFiles` with sops-nix or agenix
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: give-the-agent-a-personality-manage-statedirhermess
  text: Give the agent a personality:** Manage ${stateDir}/.hermes/SOUL.md directly
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: add-mcp-tool-servers-mcpserversname
  text: Add MCP tool servers:** `mcpServers.<name>`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: mount-host-directories-into-container-containerextravol
  text: Mount host directories into container:** `container.extraVolumes`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: pass-gpu-access-to-container-containerextraoptions-wit
  text: Pass GPU access to container:** `container.extraOptions` with "--gpus" "all"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: use-podman-instead-of-docker-containerbackend-podma
  text: Use Podman instead of Docker:** `container.backend` = "podman"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: share-state-between-host-cli-and-container-containerhos
  text: Share state between host CLI and container:** `container.hostUsers`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: hermes-setup-config-is-declarative
  text: "`hermes setup` \u2014 Config is declarative"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: hermes-config-edit-config-is-generated-from-settings
  text: "`hermes config edit` \u2014 Config is generated from settings"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: hermes-config-set-key-value-config-is-generated-from
  text: "`hermes config set <key> <value>` \u2014 Config is generated from settings"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: hermes-gateway-install-the-systemd-service-is-managed-by
  text: "`hermes gateway install` \u2014 The systemd service is managed by NixOS"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: hermes-gateway-uninstall-the-systemd-service-is-managed
  text: "`hermes gateway uninstall` \u2014 The systemd service is managed by NixOS"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: systemctl-restart-hermes-agent-container-not-recreated-a
  text: '`systemctl restart hermes-agent`: Container NOT recreated, all state persists'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: nixos-rebuild-switch-code-change-container-not-recreate
  text: '`nixos-rebuild switch` (code change): Container NOT recreated (symlink updated),
    all state persists'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: host-reboot-container-not-recreated-all-state-persists
  text: '`Host reboot`: Container NOT recreated, all state persists'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: nix-collect-garbage-container-not-recreated-gc-root-al
  text: '`nix-collect-garbage`: Container NOT recreated (GC root), all state persists'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: image-change-containerimage-container-is-recreated-d
  text: '`Image change (container.image)`: Container IS recreated, /data and /home/hermes
    persist, writable layer LOST'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: environmentenvironmentfiles-change-container-not-recreat
  text: '`environment/environmentFiles change`: Container NOT recreated, all state
    persists'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: cannot-save-configuration-managed-by-nixos-edit-configu
  text: "Cannot save configuration: managed by NixOS** \u2014 Edit configuration.nix\
    \ and nixos-rebuild switch"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: container-recreated-unexpectedly-expected-writable-lay
  text: "Container recreated unexpectedly** \u2014 Expected \u2014 writable layer\
    \ resets. Reinstall packages or use a custom image"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: hermes-version-shows-old-version-container-not-restarted
  text: "hermes version shows old version** \u2014 Container not restarted \u2014\
    \ systemctl restart hermes-agent"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: permission-denied-on-varlibhermes-use-docker-exec-or
  text: "Permission denied on /var/lib/hermes** \u2014 Use docker exec or sudo -u\
    \ hermes"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: nix-collect-garbage-removed-hermes-gc-root-missing-res
  text: "nix-collect-garbage removed hermes** \u2014 GC root missing \u2014 Restart\
    \ the service"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: no-container-with-name-or-id-hermes-agent-podman-add
  text: "no container with name or ID \"hermes-agent\" (Podman)** \u2014 Add passwordless\
    \ sudo for podman"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.nix-nixos-setup
    path: entities/nix-nixos-setup.md
- id: the-hermes-cli
  text: the Hermes CLI
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: cron-support
  text: cron support
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: ptybackground-terminal-support
  text: PTY/background terminal support
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: telegram-gateway-support-manual-best-effort-background-ru
  text: Telegram gateway support (manual / best-effort background runs)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: mcp-support
  text: MCP support
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: honcho-memory-support
  text: Honcho memory support
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: acp-support
  text: ACP support
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: all-is-not-supported-on-android-today
  text: '`.[all]` is not supported on Android today'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: the-voice-extra-is-blocked-by-faster-whisper---ctranslate2
  text: the voice extra is blocked by faster-whisper -> ctranslate2, and ctranslate2
    does not publish Android wheels
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: automatic-browser-playwright-bootstrap-is-skipped-in-the-t
  text: automatic browser / Playwright bootstrap is skipped in the Termux installer
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: docker-based-terminal-isolation-is-not-available-inside-term
  text: Docker-based terminal isolation is not available inside Termux
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: android-may-still-suspend-termux-background-jobs-so-gateway
  text: Android may still suspend Termux background jobs, so gateway persistence is
    best-effort rather than a normal managed service
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: uses-pkg-for-system-packages
  text: uses pkg for system packages
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: creates-the-venv-with-python--m-venv
  text: creates the venv with `python -m venv`
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: installs-termux-with-pip
  text: installs `.[termux]` with pip
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: links-hermes-into-prefixbin-so-it-stays-on-your-termux-p
  text: links hermes into `$PREFIX/bin` so it stays on your Termux PATH
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: skips-the-untested-browser-whatsapp-bootstrap
  text: skips the untested browser / WhatsApp bootstrap
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: python-runtime-venv-support
  text: "python \u2014 runtime + venv support"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: git-cloneupdate-the-repo
  text: "git \u2014 clone/update the repo"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: clang-rust-make-pkg-config-libffi-openssl-needed-to-b
  text: "clang, rust, make, pkg-config, libffi, openssl \u2014 needed to build a few\
    \ Python dependencies on Android"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: nodejs-optional-node-runtime-for-experiments-beyond-the-te
  text: "nodejs \u2014 optional Node runtime for experiments beyond the tested core\
    \ path"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: ripgrep-fast-file-search
  text: "ripgrep \u2014 fast file search"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: ffmpeg-media-tts-conversions
  text: "ffmpeg \u2014 media / TTS conversions"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: voice-pulls-faster-whisper
  text: voice pulls faster-whisper
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: faster-whisper-depends-on-ctranslate2
  text: faster-whisper depends on ctranslate2
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: ctranslate2-does-not-publish-android-wheels
  text: ctranslate2 does not publish Android wheels
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: docker-backend-is-unavailable
  text: Docker backend is unavailable
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: local-voice-transcription-via-faster-whisper-is-unavailable
  text: local voice transcription via faster-whisper is unavailable in the tested
    path
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: browser-automation-setup-is-intentionally-skipped-by-the-ins
  text: browser automation setup is intentionally skipped by the installer
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: some-optional-extras-may-work-but-only-termux-is-curre
  text: some optional extras may work, but only `.[termux]` is currently documented
    as the tested Android bundle
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: your-android-version
  text: your Android version
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: termux-info
  text: termux-info
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: python---version
  text: python --version
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: hermes-doctor
  text: hermes doctor
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: the-exact-install-command-and-full-error-output
  text: the exact install command and full error output
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.android-termux
    path: entities/android-termux.md
- id: type-35l-v6-dohc-24v-vvt-iw
  text: Type:** 3.5L V6 DOHC 24V VVT-iW
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: horsepower-295-hp-6300-rpm
  text: Horsepower:** 295 hp @ 6,300 RPM
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: torque-267-lb-ft-4700-rpm
  text: Torque:** 267 lb-ft @ 4,700 RPM
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: type-0w-20-full-synthetic-oem-recommended
  text: Type:** 0W-20 full synthetic (OEM recommended)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: capacity-5760-quarts-5457-liters-confirm-with
  text: "Capacity:** ~5.7\u20136.0 quarts (~5.4\u20135.7 liters) \u2014 confirm with\
    \ dealer manual"
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: drive-front-wheel-drive-fwd
  text: Drive:** Front-wheel drive (FWD)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: transmission-automatic-8-speed
  text: Transmission:** Automatic 8-speed
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: steering-left-hand-drive-us-market
  text: Steering:** Left-hand drive (US market)
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: owner-randomstixs-wife
  text: 'Owner: randomstix''s wife'
  status: supported
  confidence: null
  evidence:
  - sourceId: entity.2017-lexus-rx-350
    path: entities/2017-lexus-rx-350.md
- id: 9-cli-methods-basic-advanced-recommended-aggressive
  text: '9 CLI methods**: basic, advanced (recommended), aggressive, spectral_cascade,
    informed, surgical, optimized, inverted, nuclear'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: 116-model-presets-across-5-compute-tiers
  text: 116 model presets** across 5 compute tiers
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: license-agpl-30-never-import-as-python-library-always
  text: "License**: AGPL-3.0 \u2014 NEVER import as Python library. Always invoke\
    \ via CLI or subprocess to keep Hermes Agent's MIT license clean."
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: models-under-1b-params-respond-poorly-to-abliteration-3b
  text: Models under ~1B params** respond poorly to abliteration. 3B+ works well.
    7-8B is the practical minimum for useful results.
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: qwen-25-7b-uncensored-coding-logic
  text: "Qwen 2.5 7B Uncensored \u2014 coding & logic"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: deepseek-r1-distill-7b-abliterated-reasoning-model
  text: "DeepSeek R1 Distill 7B (abliterated) \u2014 reasoning model"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: gemma-3-4b-heretic-ultra-compact
  text: "Gemma 3 4B Heretic \u2014 ultra-compact"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: llama-31-8b-various-uncensored-variants
  text: Llama 3.1 8B (various uncensored variants)
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: mistral-7b-various-uncensored-variants
  text: Mistral 7B (various uncensored variants)
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: gpt-oss-20b-heretic-creative-writing-roleplay
  text: "GPT-OSS 20B Heretic \u2014 creative writing & roleplay"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: gemma-3-27b-abliterated-frequently-cited-as-best-all-aroun
  text: "Gemma 3 27B Abliterated \u2014 frequently cited as best all-around"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: mistral-nemo-12b-uncensored-balanced-generalist
  text: "Mistral Nemo 12B Uncensored \u2014 balanced generalist"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: qwen3-30b-abliterated-rivals-larger-models
  text: "Qwen3 30B Abliterated \u2014 rivals larger models"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: llama-32-8x3b-moe-dark-champion-moe-speed-20b-quality
  text: "Llama 3.2 8X3B MoE Dark Champion \u2014 MoE speed, ~20B-quality"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: llama-4-70b-abliterated-near-gpt-4-level
  text: "Llama 4 70B Abliterated \u2014 near GPT-4 level"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: dolphin-30-llama-70b
  text: Dolphin 3.0 Llama 70B
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: loki-70b-heretic-v2-narrative-depth
  text: "Loki 70B Heretic V2 \u2014 narrative depth"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: nous-hermes-3-llama-31-405b-frontier-open-weights
  text: "Nous Hermes 3 Llama 3.1 405B \u2014 frontier open-weights"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: dolphin-cognitive-computations-high-compliance-fine-tu
  text: "Dolphin** (Cognitive Computations) \u2014 high-compliance fine-tuning"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: heretic-davidau-mradermacher-aggressively-de-aligned
  text: "Heretic** (DavidAU / mradermacher) \u2014 aggressively de-aligned"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: dark-champion-davidau-moe-abliterated
  text: "Dark Champion** (DavidAU) \u2014 MoE abliterated"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: wizard-vicuna-thebloke-classic-uncensored-most-downlo
  text: "Wizard-Vicuna** (TheBloke) \u2014 classic uncensored, most downloaded"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: nous-hermes-nousresearch-creative-writing-roleplay
  text: "Nous Hermes** (NousResearch) \u2014 creative writing & roleplay"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: juggernaut-xl-all-around-photorealism-69gb-safetensors
  text: "Juggernaut XL \u2014 all-around photorealism (~6.9GB safetensors)"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: realistic-vision-xl-photorealistic-people
  text: "Realistic Vision XL \u2014 photorealistic people"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: pony-diffusion-xl-character-art-huge-lora-ecosystem
  text: "Pony Diffusion XL \u2014 character art, huge LoRA ecosystem"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: dreamshaper-xl-artistic-fantasy
  text: "DreamShaper XL \u2014 artistic, fantasy"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: sdxl-unstable-diffusers-nsfw-focus
  text: "SDXL Unstable Diffusers \u2014 NSFW focus"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: comfortable-llama-32-3b-3gb-gemma-3-4b-4gb-qwen
  text: 'Comfortable**: Llama 3.2 3B (~3GB), Gemma 3 4B (~4GB), Qwen 2.5 7B (~6-8GB),
    Llama 3.1 8B (~7-8GB), DeepSeek R1 Distill 7B (~7GB)'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: tight-but-possible-mistral-nemo-12b-10gb-gemma-3-12b
  text: 'Tight but possible**: Mistral Nemo 12B (~10GB), Gemma 3 12B (~10GB)'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: not-viable-gpt-oss-20b-gemma-3-27b-qwen3-30b-anything
  text: 'Not viable**: GPT-OSS 20B, Gemma 3 27B, Qwen3 30B, anything 70B+'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: sd-15-10-20-secimage-low-ram-pressure
  text: 'SD 1.5**: 10-20 sec/image, low RAM pressure'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: sdxl-30-90-secimage-medium-high-ram-pressure
  text: 'SDXL**: 30-90 sec/image, medium-high RAM pressure'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: flux-not-viable-oom-on-16gb
  text: 'Flux**: Not viable (OOM on 16GB)'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: llm-uncensoring-abliterate-with-obliteratus-need-gpu-or-d
  text: 'LLM uncensoring: abliterate with OBLITERATUS (need GPU) OR download pre-abliterated
    GGUFs'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: image-gen-uncensoring-just-disable-safety-checker-use-com
  text: 'Image gen uncensoring: just disable safety checker + use community checkpoints'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: mac-with-16gb-7-8b-llms-max-sdxl-for-images-max
  text: 'Mac with 16GB: 7-8B LLMs max, SDXL for images max'
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: for-low-spec-machines-downloading-pre-built-models-is-smart
  text: For low-spec machines, downloading pre-built models is smarter than running
    abliteration
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.uncensored-ai-models
    path: concepts/uncensored-ai-models.md
- id: doe-argonne-greet-model-corn-ethanol-reduces-life-cycle-g
  text: DOE Argonne GREET model:** Corn ethanol reduces life-cycle GHG emissions by
    ~40-46% compared to gasoline
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: lark-et-al-2022-pnas-corn-ethanol-is-at-least-24-more
  text: Lark et al. (2022) PNAS:** Corn ethanol is at least 24% more carbon-intensive
    than gasoline when land-use change is accounted for
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: the-empirical-camp-lark-et-al-uses-satellite-data-showing
  text: The empirical camp (Lark et al.) uses satellite data showing actual conversion
    of grasslands and conservation land to corn, releasing stored carbon
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: the-modeling-camp-doeargonne-uses-economic-models-that-as
  text: The modeling camp (DOE/Argonne) uses economic models that assume less land-use
    change
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: this-is-the-single-largest-driver-of-the-difference-between
  text: This is the single largest driver of the difference between estimates
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: industry-critics-argue-the-lark-study-understates-yield-gain
  text: Industry critics argue the Lark study understates yield gains, meaning fewer
    acres are needed for the same corn output
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: lark-et-al-respond-that-their-satellite-data-captures-actua
  text: Lark et al. respond that their satellite data captures actual land-use change,
    not modeled projections
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: ethanol-production-creates-distillers-grains-that-replace-an
  text: Ethanol production creates distillers grains that replace animal feed, offsetting
    some emissions
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: the-value-of-this-credit-is-disputed-between-the-two-camps
  text: The value of this credit is disputed between the two camps
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: what-would-farmers-have-planted-if-not-corn-for-ethanol-the
  text: What would farmers have planted if not corn for ethanol? The answer dramatically
    affects the net GHG calculation
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: different-assumptions-produce-wildly-different-results
  text: Different assumptions produce wildly different results
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: both-sides-have-published-in-peer-reviewed-journals
  text: Both sides have published in peer-reviewed journals
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: lark-et-al-were-funded-by-national-wildlife-federation-env
  text: Lark et al. were funded by National Wildlife Federation (environmental advocacy)
    and DOE
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: industry-funded-studies-are-funded-by-groups-with-a-financia
  text: Industry-funded studies are funded by groups with a financial interest in
    ethanol policy
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: the-scientific-community-remains-genuinely-split-this-is-n
  text: "The scientific community remains genuinely split \u2014 this is not settled\
    \ science"
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: reuters-feb-14-2022-reported-the-lark-studys-findings-t
  text: Reuters (Feb 14, 2022) reported the Lark study's findings; the reporting was
    generally accurate and not overdramatized
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: the-article-sparked-significant-pushback-from-the-ethanol-in
  text: The article sparked significant pushback from the ethanol industry
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: multiple-outlets-axios-cleantechnica-cnet-des-moines-reg
  text: Multiple outlets (Axios, CleanTechnica, CNET, Des Moines Register) covered
    the study and subsequent debate
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: us-renewable-fuel-standard-rfs
  text: US Renewable Fuel Standard (RFS)
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: biofuel-lifecycle-analysis
  text: Biofuel lifecycle analysis
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
- id: indirect-land-use-change-iluc
  text: Indirect land-use change (ILUC)
  status: supported
  confidence: null
  evidence:
  - sourceId: concept.corn-ethanol-climate-impact-debate
    path: concepts/corn-ethanol-climate-impact-debate.md
updatedAt: '2026-04-29T13:58:33.090882+00:00'
---

<!-- openclaw:wiki:generated:start -->

This synthesis covers: [[entities/randomstix]].

## Claims

### Supported

- Web application running in Docker container
  - Sources: [[entities/lolok-site|lolok Site]]
- Live container at port 5001
  - Sources: [[entities/lolok-site|lolok Site]]
- CI/CD via GitHub Actions + self-hosted runner (lolok-runner)
  - Sources: [[entities/lolok-site|lolok Site]]
- Static file server was on port 8080, may need restart
  - Sources: [[entities/lolok-site|lolok Site]]
- September 18-20, 2026
  - Sources: [[entities/lost-lands-2026|Lost Lands 2026]]
- Legend Valley, OH
  - Sources: [[entities/lost-lands-2026|Lost Lands 2026]]
- GA Tier 4 ($512.91) + Thursday Early Entry ($107.02) + shipping ($16.49) - promo ($25) = $611.42 total
  - Sources: [[entities/lost-lands-2026|Lost Lands 2026]]
- GA Tier 4 with Thursday Early Entry
  - Sources: [[entities/lost-lands-2026|Lost Lands 2026]]
- Name is randomstix
  - Sources: [[entities/randomstix|Quoc Vu]]
- Email is quocvu2640@gmail.com
  - Sources: [[entities/randomstix|Quoc Vu]]
- Contact via Discord #general
  - Sources: [[entities/randomstix|Quoc Vu]]
- America/New_York (EDT/EST)
  - Sources: [[entities/randomstix|Quoc Vu]]
- Running at /opt/stacks/hindsight_memory/
  - Sources: [[entities/hindsight-memory-server|Hindsight Memory Server]]
- API on port 8888, Control Plane on port 9999
  - Sources: [[entities/hindsight-memory-server|Hindsight Memory Server]]
- Uses pgvector/pgvector:pg18 (PostgreSQL with pgvector extension)
  - Sources: [[entities/hindsight-memory-server|Hindsight Memory Server]]
- Uses MiniMax-M2.7 via HINDSIGHT_API_LLM_PROVIDER=minimax
  - Sources: [[entities/hindsight-memory-server|Hindsight Memory Server]]
- HINDSIGHT_API_KEY is set in .env but API key auth is not enforced in this version (v0.5.4)
  - Sources: [[entities/hindsight-memory-server|Hindsight Memory Server]]
- Data persisted at ./db (pgvector data) and ./hindsight-data (embedded pg0 fallback)
  - Sources: [[entities/hindsight-memory-server|Hindsight Memory Server]]
- compose.yaml had two bugs: (1) wrong env_file syntax 'path: .env' should be '.env', (2) volume mount ./db:/var/lib/postgresql/data wrong — pgvector image stores at /var/lib/postgresql not /var/lib/postgresql/data
  - Sources: [[entities/hindsight-memory-server|Hindsight Memory Server]]
- add a new provider** (OpenRouter, Anthropic, Copilot, DeepSeek, custom, etc.)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- log into OAuth-backed providers (Anthropic, Copilot, Codex, Nous Portal)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- enter or update API keys
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- pick from provider-specific model lists
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- configure a custom/self-hosted endpoint
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- save the new default into config
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- hermes dump ---version:          0.8.0 (2026.4.8) [af4abd2f]os:               Linux 6.14.0-37-generic x86_64python:           3.11.14openai_sdk:       2.24.0profile:          defaulthermes_home:      ~/.hermesmodel:            anthropic/claude-opus-4.6provider:         openrouterterminal:         localapi_keys:  openrouter           set  openai               not set  anthropic            set  nous                 not set  firecrawl            set  ...features:  toolsets:           all  mcp_servers:        0  memory_provider:    built-in  gateway:            running (systemd)  platforms:          telegram, discord  cron_jobs:          3 active / 5 total  skills:             42config_overrides:  agent.max_turns: 250  compression.threshold: 0.85  display.streaming: True--- end dump ---
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- Reporting a bug on GitHub — paste the dump into your issue
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- Asking for help in Discord — share it in a code block
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- Comparing your setup to someone else&#x27;s
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- Quick sanity check when something isn&#x27;t working
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- `--force` can override non-dangerous policy blocks for third-party/community skills.
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- `--force` does not override a `dangerous` scan verdict.
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- `--source skills-sh` searches the public `skills.sh` directory.
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- `--source well-known` lets you point Hermes at a site exposing `/.well-known/skills/index.json`.
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- General Plugins** — multi-select checkboxes to enable/disable installed plugins
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- Provider Plugins** — single-select configuration for Memory Provider and Context Engine. Press ENTER on a category to open a radio picker.
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- `memory.provider` — active memory provider (empty = built-in only)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- `context.engine` — active context engine (`&quot;compressor&quot;` = built-in default)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- [Slash Commands Reference](/docs/reference/slash-commands)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]], [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [CLI Interface](/docs/user-guide/cli)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- [Sessions](/docs/user-guide/sessions)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]], [[entities/learning-path|Learning Path]]
- [Skills System](/docs/user-guide/features/skills)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- [Skins &amp; Themes](/docs/user-guide/features/skins)
  - Sources: [[entities/cli-commands-reference|CLI Commands Reference]]
- Bug fixes** — crashes, incorrect behavior, data loss
  - Sources: [[entities/contributing|Contributing]]
- Cross-platform compatibility** — macOS, different Linux distros, WSL2
  - Sources: [[entities/contributing|Contributing]]
- Security hardening** — shell injection, prompt injection, path traversal
  - Sources: [[entities/contributing|Contributing]]
- Performance and robustness** — retry logic, error handling, graceful degradation
  - Sources: [[entities/contributing|Contributing]]
- New skills** — broadly useful ones (see [Creating Skills](/docs/developer-guide/creating-skills))
  - Sources: [[entities/contributing|Contributing]]
- New tools** — rarely needed; most capabilities should be skills
  - Sources: [[entities/contributing|Contributing]]
- Documentation** — fixes, clarifications, new examples
  - Sources: [[entities/contributing|Contributing]]
- Building a new tool? Start with [Adding Tools](/docs/developer-guide/adding-tools)
  - Sources: [[entities/contributing|Contributing]]
- Building a new skill? Start with [Creating Skills](/docs/developer-guide/creating-skills)
  - Sources: [[entities/contributing|Contributing]]
- Building a new inference provider? Start with [Adding Providers](/docs/developer-guide/adding-providers)
  - Sources: [[entities/contributing|Contributing]]
- PEP 8** with practical exceptions (no strict line length enforcement)
  - Sources: [[entities/contributing|Contributing]]
- Comments**: Only when explaining non-obvious intent, trade-offs, or API quirks
  - Sources: [[entities/contributing|Contributing]]
- Error handling**: Catch specific exceptions. Use `logger.warning()`/`logger.error()` with `exc_info=True` for unexpected errors
  - Sources: [[entities/contributing|Contributing]]
- Cross-platform**: Never assume Unix (see below)
  - Sources: [[entities/contributing|Contributing]]
- Profile-safe paths**: Never hardcode `~/.hermes` — use `get_hermes_home()` from `hermes_constants` for code paths and `display_hermes_home()` for user-facing messages. See [AGENTS.md](https://github.com/NousResearch/hermes-agent/blob/main/AGENTS.md#profiles-multi-instance-support) for full rules.
  - Sources: [[entities/contributing|Contributing]]
- Always use `shlex.quote()` when interpolating user input into shell commands
  - Sources: [[entities/contributing|Contributing]]
- Resolve symlinks with `os.path.realpath()` before access control checks
  - Sources: [[entities/contributing|Contributing]]
- Don&#x27;t log secrets
  - Sources: [[entities/contributing|Contributing]]
- Catch broad exceptions around tool execution
  - Sources: [[entities/contributing|Contributing]]
- Test on all platforms if your change touches file paths or processes
  - Sources: [[entities/contributing|Contributing]]
- Run tests**: `pytest tests/ -v`
  - Sources: [[entities/contributing|Contributing]]
- Test manually**: Run `hermes` and exercise the code path you changed
  - Sources: [[entities/contributing|Contributing]]
- Check cross-platform impact**: Consider macOS and different Linux distros
  - Sources: [[entities/contributing|Contributing]]
- Keep PRs focused**: One logical change per PR
  - Sources: [[entities/contributing|Contributing]]
- What** changed and **why**
  - Sources: [[entities/contributing|Contributing]]
- How to test** it
  - Sources: [[entities/contributing|Contributing]]
- What platforms** you tested on
  - Sources: [[entities/contributing|Contributing]]
- Reference any related issues
  - Sources: [[entities/contributing|Contributing]]
- Use [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)
  - Sources: [[entities/contributing|Contributing]]
- Include: OS, Python version, Hermes version (`hermes version`), full error traceback
  - Sources: [[entities/contributing|Contributing]]
- Include steps to reproduce
  - Sources: [[entities/contributing|Contributing]]
- Check existing issues before creating duplicates
  - Sources: [[entities/contributing|Contributing]]
- For security vulnerabilities, please report privately
  - Sources: [[entities/contributing|Contributing]]
- Discord**: [discord.gg/NousResearch](https://discord.gg/NousResearch)
  - Sources: [[entities/contributing|Contributing]]
- GitHub Discussions**: For design proposals and architecture discussions
  - Sources: [[entities/contributing|Contributing]]
- Skills Hub**: Upload specialized skills and share with the community
  - Sources: [[entities/contributing|Contributing]]
- This page** — orient yourself
  - Sources: [[entities/architecture|Architecture]]
- [Agent Loop Internals](/docs/developer-guide/agent-loop)** — how AIAgent works
  - Sources: [[entities/architecture|Architecture]]
- [Prompt Assembly](/docs/developer-guide/prompt-assembly)** — system prompt construction
  - Sources: [[entities/architecture|Architecture]]
- [Provider Runtime Resolution](/docs/developer-guide/provider-runtime)** — how providers are selected
  - Sources: [[entities/architecture|Architecture]]
- [Adding Providers](/docs/developer-guide/adding-providers)** — practical guide to adding a new provider
  - Sources: [[entities/architecture|Architecture]]
- [Tools Runtime](/docs/developer-guide/tools-runtime)** — tool registry, dispatch, environments
  - Sources: [[entities/architecture|Architecture]]
- [Session Storage](/docs/developer-guide/session-storage)** — SQLite schema, FTS5, session lineage
  - Sources: [[entities/architecture|Architecture]]
- [Gateway Internals](/docs/developer-guide/gateway-internals)** — messaging platform gateway
  - Sources: [[entities/architecture|Architecture]]
- [Context Compression &amp; Prompt Caching](/docs/developer-guide/context-compression-and-caching)** — compression and caching
  - Sources: [[entities/architecture|Architecture]]
- [ACP Internals](/docs/developer-guide/acp-internals)** — IDE integration
  - Sources: [[entities/architecture|Architecture]]
- [Environments, Benchmarks &amp; Data Generation](/docs/developer-guide/environments)** — RL training
  - Sources: [[entities/architecture|Architecture]]
- `prompt_builder.py`** — Assembles the system prompt from: personality (SOUL.md), memory (MEMORY.md, USER.md), skills, context files (AGENTS.md, .hermes.md), tool-use guidance, and model-specific instructions
  - Sources: [[entities/architecture|Architecture]]
- `prompt_caching.py`** — Applies Anthropic cache breakpoints for prefix caching
  - Sources: [[entities/architecture|Architecture]]
- `context_compressor.py`** — Summarizes middle conversation turns when context exceeds thresholds
  - Sources: [[entities/architecture|Architecture]]
- PKCE Authorization Code flow against accounts.google.com
  - Sources: [[entities/ai-providers|AI Providers]]
- Browser callback at http://127.0.0.1:8085/oauth2callback (with ephemeral-port fallback if busy)
  - Sources: [[entities/ai-providers|AI Providers]]
- Tokens stored at ~/.hermes/auth/google_oauth.json (chmod 0600, atomic write, cross-process fcntl lock)
  - Sources: [[entities/ai-providers|AI Providers]]
- Automatic refresh 60 s before expiry
  - Sources: [[entities/ai-providers|AI Providers]]
- Headless environments (SSH, HERMES_HEADLESS=1) → paste-mode fallback
  - Sources: [[entities/ai-providers|AI Providers]]
- Inflight refresh deduplication — two concurrent requests won't double-refresh
  - Sources: [[entities/ai-providers|AI Providers]]
- invalid_grant (revoked refresh) → credential file wiped, user prompted to re-login
  - Sources: [[entities/ai-providers|AI Providers]]
- Traffic goes to https://cloudcode-pa.googleapis.com/v1internal:generateContent
  - Sources: [[entities/ai-providers|AI Providers]]
- Request body wrapped {project, model, user_prompt_id, request}
  - Sources: [[entities/ai-providers|AI Providers]]
- OpenAI-shaped messages[], tools[], tool_choice are translated to Gemini's native
  - Sources: [[entities/ai-providers|AI Providers]]
- Responses translated back to OpenAI shape so the rest of Hermes works unchanged
  - Sources: [[entities/ai-providers|AI Providers]]
- provider claude and --provider claude-code also work as shorthand for --provider anthropic.
  - Sources: [[entities/ai-providers|AI Providers]]
- port 8000 \
  - Sources: [[entities/ai-providers|AI Providers]]
- max-model-len 65536 \
  - Sources: [[entities/ai-providers|AI Providers]]
- tensor-parallel-size 2 \
  - Sources: [[entities/ai-providers|AI Providers]]
- enable-auto-tool-choice \
  - Sources: [[entities/ai-providers|AI Providers]]
- tool-call-parser hermes
  - Sources: [[entities/ai-providers|AI Providers]]
- model meta-llama/Llama-3.1-70B-Instruct \
  - Sources: [[entities/ai-providers|AI Providers]]
- port 30000 \
  - Sources: [[entities/ai-providers|AI Providers]]
- context-length 65536 \
  - Sources: [[entities/ai-providers|AI Providers]]
- tool-call-parser qwen
  - Sources: [[entities/ai-providers|AI Providers]]
- jinja -fa \
  - Sources: [[entities/ai-providers|AI Providers]]
- m models/qwen2.5-coder-32b-instruct-Q4_K_M.gguf \
  - Sources: [[entities/ai-providers|AI Providers]]
- port 8080 --host 0.0.0.0
  - Sources: [[entities/ai-providers|AI Providers]]
- jinja is required for tool calling
  - Sources: [[entities/ai-providers|AI Providers]]
- model_name: "best"
  - Sources: [[entities/ai-providers|AI Providers]], [[entities/ai-providers|AI Providers]]
- name: "My Local LLM"
  - Sources: [[entities/ai-providers|AI Providers]]
- You're using Ollama with a custom num_ctx that's lower than the model's maximum
  - Sources: [[entities/ai-providers|AI Providers]]
- You want to limit context below the model's maximum (e.g., 8k on a 128k model to save VRAM)
  - Sources: [[entities/ai-providers|AI Providers]]
- You're running behind a proxy that doesn't expose /v1/models
  - Sources: [[entities/ai-providers|AI Providers]]
- name: local
  - Sources: [[entities/ai-providers|AI Providers]]
- name: work
  - Sources: [[entities/ai-providers|AI Providers]]
- name: anthropic-proxy
  - Sources: [[entities/ai-providers|AI Providers]]
- Configuration — General configuration (directory structure, config precedence, terminal backends, memory, compression, and more)
  - Sources: [[entities/ai-providers|AI Providers]]
- Environment Variables — Complete reference of all environment variables
  - Sources: [[entities/ai-providers|AI Providers]]
- Google Gemini via OAuth (google-gemini-cli)
  - Sources: [[entities/ai-providers|AI Providers]]
- Two Commands for Model Management
  - Sources: [[entities/ai-providers|AI Providers]]
- Anthropic (Native)
  - Sources: [[entities/ai-providers|AI Providers]]
- GitHub Copilot
  - Sources: [[entities/ai-providers|AI Providers]]
- First-Class Chinese AI Providers
  - Sources: [[entities/ai-providers|AI Providers]]
- xAI (Grok) — Responses API + Prompt Caching
  - Sources: [[entities/ai-providers|AI Providers]]
- Ollama Cloud — Managed Ollama Models, OAuth + API Key
  - Sources: [[entities/ai-providers|AI Providers]]
- AWS Bedrock
  - Sources: [[entities/ai-providers|AI Providers]]
- Qwen Portal (OAuth)
  - Sources: [[entities/ai-providers|AI Providers]]
- NVIDIA NIM
  - Sources: [[entities/ai-providers|AI Providers]]
- Hugging Face Inference Providers
  - Sources: [[entities/ai-providers|AI Providers]]
- [Custom & Self-Hosted LLM Providers](#custom--self-hosted-llm-providers)[](#general-setup)[](#switching-models-with-model)[](#ollama--local-models-zero-config)[](#vllm--high-performance-gpu-inference)[](#sglang--fast-serving-with-radixattention)[](#llamacpp--llama-server--cpu--metal-inference)[](#lm-studio--desktop-app-with-local-models)[](#wsl2-networking-windows-users)[](#troubleshooting-local-models)[](#litellm-proxy--multi-provider-gateway)[](#clawrouter--cost-optimized-routing)[](#other-compatible-providers)[](#context-length-detection)[](#named-custom-providers)[](#choosing-the-right-setup)
  - Sources: [[entities/ai-providers|AI Providers]]
- General Setup
  - Sources: [[entities/ai-providers|AI Providers]]
- Switching Models with /model
  - Sources: [[entities/ai-providers|AI Providers]]
- Ollama — Local Models, Zero Config
  - Sources: [[entities/ai-providers|AI Providers]]
- vLLM — High-Performance GPU Inference
  - Sources: [[entities/ai-providers|AI Providers]]
- SGLang — Fast Serving with RadixAttention
  - Sources: [[entities/ai-providers|AI Providers]]
- llama.cpp / llama-server — CPU & Metal Inference
  - Sources: [[entities/ai-providers|AI Providers]]
- LM Studio — Desktop App with Local Models
  - Sources: [[entities/ai-providers|AI Providers]]
- WSL2 Networking (Windows Users)
  - Sources: [[entities/ai-providers|AI Providers]]
- Troubleshooting Local Models
  - Sources: [[entities/ai-providers|AI Providers]]
- LiteLLM Proxy — Multi-Provider Gateway
  - Sources: [[entities/ai-providers|AI Providers]]
- ClawRouter — Cost-Optimized Routing
  - Sources: [[entities/ai-providers|AI Providers]]
- Other Compatible Providers
  - Sources: [[entities/ai-providers|AI Providers]]
- Context Length Detection
  - Sources: [[entities/ai-providers|AI Providers]]
- Named Custom Providers
  - Sources: [[entities/ai-providers|AI Providers]]
- Choosing the Right Setup
  - Sources: [[entities/ai-providers|AI Providers]]
- [Optional API Keys](#optional-api-keys)[](#self-hosting-firecrawl)
  - Sources: [[entities/ai-providers|AI Providers]]
- Self-Hosting Firecrawl
  - Sources: [[entities/ai-providers|AI Providers]]
- [OpenRouter Provider Routing](#openrouter-provider-routing)
  - Sources: [[entities/ai-providers|AI Providers]]
- [Fallback Model](#fallback-model)
  - Sources: [[entities/ai-providers|AI Providers]]
- [See Also](#see-also)
  - Sources: [[entities/ai-providers|AI Providers]]
- {pull_request.title} resolves to payload["pull_request"]["title"]
  - Sources: [[entities/webhooks|Webhooks]]
- {repository.full_name} resolves to payload["repository"]["full_name"]
  - Sources: [[entities/webhooks|Webhooks]]
- {__raw__} — special token that dumps the entire payload as indented JSON (truncated at 4000 characters). Useful for monitoring alerts or generic webhooks where the agent needs the full context.
  - Sources: [[entities/webhooks|Webhooks]]
- Missing keys are left as the literal {key} string (no error)
  - Sources: [[entities/webhooks|Webhooks]]
- Nested dicts and lists are JSON-serialized and truncated at 2000 characters
  - Sources: [[entities/webhooks|Webhooks]]
- External service push — Supabase/Firebase webhook fires on a database change → notify a user in Telegram instantly
  - Sources: [[entities/webhooks|Webhooks]]
- Monitoring alerts — Datadog/Grafana alert webhook → push to a Discord channel
  - Sources: [[entities/webhooks|Webhooks]]
- Inter-agent pings — Agent A notifies Agent B's user that a long-running task finished
  - Sources: [[entities/webhooks|Webhooks]]
- Background job completion — Cron job finishes → post result to Slack
  - Sources: [[entities/webhooks|Webhooks]]
- Zero LLM tokens — the agent is never invoked
  - Sources: [[entities/webhooks|Webhooks]]
- Sub-second delivery — a single adapter call, no reasoning loop
  - Sources: [[entities/webhooks|Webhooks]]
- Same security as agent mode — HMAC auth, rate limits, idempotency, and body-size limits all still apply
  - Sources: [[entities/webhooks|Webhooks]]
- Synchronous response — the POST returns 200 OK once delivery succeeds, or 502 if the target rejects it, so your upstream service can retry intelligently
  - Sources: [[entities/webhooks|Webhooks]]
- deliver telegram \
  - Sources: [[entities/webhooks|Webhooks]], [[entities/webhooks|Webhooks]]
- deliver-chat-id "123456789" \
  - Sources: [[entities/webhooks|Webhooks]]
- deliver-only \
  - Sources: [[entities/webhooks|Webhooks]]
- prompt "🎉 New match: {match.user_name} matched with you!" \
  - Sources: [[entities/webhooks|Webhooks]]
- description "Antenna match notifications"
  - Sources: [[entities/webhooks|Webhooks]]
- deliver_only: true requires deliver to be a real target. deliver: log (or omitting deliver) is rejected at startup — the adapter refuses to start if it finds a misconfigured route.
  - Sources: [[entities/webhooks|Webhooks]]
- The skills field is ignored in direct delivery mode (no agent runs, so there's nothing to inject skills into).
  - Sources: [[entities/webhooks|Webhooks]]
- Template rendering uses the same {dot.notation} syntax as agent mode, including the {__raw__} token.
  - Sources: [[entities/webhooks|Webhooks]]
- Idempotency uses the same X-GitHub-Delivery / X-Request-ID header — retries with the same ID return status=duplicate and do NOT re-deliver.
  - Sources: [[entities/webhooks|Webhooks]]
- events "issues" \
  - Sources: [[entities/webhooks|Webhooks]]
- prompt "New issue #{issue.number}: {issue.title}\nBy: {issue.user.login}\n\n{issue.body}" \
  - Sources: [[entities/webhooks|Webhooks]]
- deliver-chat-id "-100123456789" \
  - Sources: [[entities/webhooks|Webhooks]]
- description "Triage new GitHub issues"
  - Sources: [[entities/webhooks|Webhooks]]
- Subscriptions are stored in ~/.hermes/webhook_subscriptions.json
  - Sources: [[entities/webhooks|Webhooks]]
- The webhook adapter hot-reloads this file on each incoming request (mtime-gated, negligible overhead)
  - Sources: [[entities/webhooks|Webhooks]]
- Static routes from config.yaml always take precedence over dynamic ones with the same name
  - Sources: [[entities/webhooks|Webhooks]]
- Dynamic subscriptions use the same route format and capabilities as static routes (events, prompt templates, skills, delivery)
  - Sources: [[entities/webhooks|Webhooks]]
- No gateway restart required — subscribe and it's immediately live
  - Sources: [[entities/webhooks|Webhooks]]
- GitHub: X-Hub-Signature-256 header — HMAC-SHA256 hex digest prefixed with sha256=
  - Sources: [[entities/webhooks|Webhooks]]
- GitLab: X-Gitlab-Token header — plain secret string match
  - Sources: [[entities/webhooks|Webhooks]]
- Generic: X-Webhook-Signature header — raw HMAC-SHA256 hex digest
  - Sources: [[entities/webhooks|Webhooks]]
- Verify the port is exposed and accessible from the webhook source
  - Sources: [[entities/webhooks|Webhooks]]
- Check firewall rules — port 8644 (or your configured port) must be open
  - Sources: [[entities/webhooks|Webhooks]]
- Verify the URL path matches: http://your-server:8644/webhooks/<route-name>
  - Sources: [[entities/webhooks|Webhooks]]
- Use the /health endpoint to confirm the server is running
  - Sources: [[entities/webhooks|Webhooks]]
- Ensure the secret in your route config exactly matches the secret configured in the webhook source
  - Sources: [[entities/webhooks|Webhooks]]
- For GitHub, the secret is HMAC-based — check X-Hub-Signature-256
  - Sources: [[entities/webhooks|Webhooks]]
- For GitLab, the secret is a plain token match — check X-Gitlab-Token
  - Sources: [[entities/webhooks|Webhooks]]
- Check gateway logs for Invalid signature warnings
  - Sources: [[entities/webhooks|Webhooks]]
- Check that the event type is in your route's events list
  - Sources: [[entities/webhooks|Webhooks]]
- GitHub events use values like pull_request, push, issues (the X-GitHub-Event header value)
  - Sources: [[entities/webhooks|Webhooks]]
- GitLab events use values like merge_request, push (the X-GitLab-Event header value)
  - Sources: [[entities/webhooks|Webhooks]]
- If events is empty or not set, all events are accepted
  - Sources: [[entities/webhooks|Webhooks]]
- Run the gateway in foreground to see logs: hermes gateway run
  - Sources: [[entities/webhooks|Webhooks]]
- Check that the prompt template is rendering correctly
  - Sources: [[entities/webhooks|Webhooks]]
- Verify the delivery target is configured and connected
  - Sources: [[entities/webhooks|Webhooks]]
- The idempotency cache should prevent this — check that the webhook source is sending a delivery ID header (X-GitHub-Delivery or X-Request-ID)
  - Sources: [[entities/webhooks|Webhooks]]
- Delivery IDs are cached for 1 hour
  - Sources: [[entities/webhooks|Webhooks]]
- Run gh auth login on the gateway host
  - Sources: [[entities/webhooks|Webhooks]]
- Ensure the authenticated GitHub user has write access to the repository
  - Sources: [[entities/webhooks|Webhooks]]
- Check that gh is installed and on the PATH
  - Sources: [[entities/webhooks|Webhooks]]
- Via setup wizard
  - Sources: [[entities/webhooks|Webhooks]]
- Via environment variables
  - Sources: [[entities/webhooks|Webhooks]]
- Verify the server
  - Sources: [[entities/webhooks|Webhooks]]
- [Configuring Routes](#configuring-routes)[](#route-properties)[](#full-example)[](#prompt-templates)[](#forum-topic-delivery)
  - Sources: [[entities/webhooks|Webhooks]]
- Route properties
  - Sources: [[entities/webhooks|Webhooks]]
- Full example
  - Sources: [[entities/webhooks|Webhooks]], [[entities/slack-setup|Slack Setup]]
- Prompt Templates
  - Sources: [[entities/webhooks|Webhooks]]
- Forum Topic Delivery
  - Sources: [[entities/webhooks|Webhooks]]
- [GitHub PR Review (Step by Step)](#github-pr-review)[](#1-create-the-webhook-in-github)[](#2-add-the-route-config)[](#3-ensure-gh-cli-is-authenticated)[](#4-test-it)
  - Sources: [[entities/webhooks|Webhooks]]
- 1. Create the webhook in GitHub
  - Sources: [[entities/webhooks|Webhooks]]
- 2. Add the route config
  - Sources: [[entities/webhooks|Webhooks]], [[entities/webhooks|Webhooks]]
- 3. Ensure gh CLI is authenticated
  - Sources: [[entities/webhooks|Webhooks]]
- 4. Test it
  - Sources: [[entities/webhooks|Webhooks]]
- [GitLab Webhook Setup](#gitlab-webhook-setup)[](#1-create-the-webhook-in-gitlab)[](#2-add-the-route-config-1)
  - Sources: [[entities/webhooks|Webhooks]]
- 1. Create the webhook in GitLab
  - Sources: [[entities/webhooks|Webhooks]]
- [Delivery Options](#delivery-options)
  - Sources: [[entities/webhooks|Webhooks]]
- [Direct Delivery Mode](#direct-delivery-mode)[](#when-to-use-direct-delivery)[](#example-telegram-push-from-supabase)[](#example-dynamic-subscription-via-cli)[](#response-codes)[](#configuration-gotchas)
  - Sources: [[entities/webhooks|Webhooks]]
- When to use direct delivery
  - Sources: [[entities/webhooks|Webhooks]]
- Example: Telegram push from Supabase
  - Sources: [[entities/webhooks|Webhooks]]
- Example: Dynamic subscription via CLI
  - Sources: [[entities/webhooks|Webhooks]]
- Response codes
  - Sources: [[entities/webhooks|Webhooks]]
- Configuration gotchas
  - Sources: [[entities/webhooks|Webhooks]]
- [Dynamic Subscriptions (CLI)](#dynamic-subscriptions)[](#create-a-subscription)[](#list-subscriptions)[](#remove-a-subscription)[](#test-a-subscription)[](#how-dynamic-subscriptions-work)[](#agent-driven-subscriptions)
  - Sources: [[entities/webhooks|Webhooks]]
- Create a subscription
  - Sources: [[entities/webhooks|Webhooks]]
- List subscriptions
  - Sources: [[entities/webhooks|Webhooks]]
- Remove a subscription
  - Sources: [[entities/webhooks|Webhooks]]
- Test a subscription
  - Sources: [[entities/webhooks|Webhooks]]
- How dynamic subscriptions work
  - Sources: [[entities/webhooks|Webhooks]]
- Agent-driven subscriptions
  - Sources: [[entities/webhooks|Webhooks]]
- [Security](#security)[](#hmac-signature-validation)[](#secret-is-required)[](#rate-limiting)[](#idempotency)[](#body-size-limits)[](#prompt-injection-risk)
  - Sources: [[entities/webhooks|Webhooks]]
- HMAC signature validation
  - Sources: [[entities/webhooks|Webhooks]]
- Secret is required
  - Sources: [[entities/webhooks|Webhooks]]
- Rate limiting
  - Sources: [[entities/webhooks|Webhooks]]
- Idempotency
  - Sources: [[entities/webhooks|Webhooks]]
- Body size limits
  - Sources: [[entities/webhooks|Webhooks]]
- Prompt injection risk
  - Sources: [[entities/webhooks|Webhooks]]
- [Troubleshooting](#troubleshooting)[](#webhook-not-arriving)[](#signature-validation-failing)[](#event-being-ignored)[](#agent-not-responding)[](#duplicate-responses)[](#gh-cli-errors-github-comment-delivery)
  - Sources: [[entities/webhooks|Webhooks]]
- Webhook not arriving
  - Sources: [[entities/webhooks|Webhooks]]
- Signature validation failing
  - Sources: [[entities/webhooks|Webhooks]]
- Event being ignored
  - Sources: [[entities/webhooks|Webhooks]]
- Agent not responding
  - Sources: [[entities/webhooks|Webhooks]]
- Duplicate responses
  - Sources: [[entities/webhooks|Webhooks]]
- gh CLI errors (GitHub comment delivery)
  - Sources: [[entities/webhooks|Webhooks]]
- [Environment Variables](#environment-variables)
  - Sources: [[entities/webhooks|Webhooks]], [[entities/qq-bot|QQ Bot]], [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]], [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- e OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1 \
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- e OPENAI_API_KEY=your-secret-key \
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- add-host=host.docker.internal:host-gateway \
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- v open-webui:/app/backend/data \
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- name open-webui \
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- restart always \
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- "3000:8080"
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- open-webui:/app/backend/data
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- OPENAI_API_KEY=your-secret-key
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- "host.docker.internal:host-gateway"
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- URL: http://host.docker.internal:8642/v1
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- API Key: your key or any non-empty value (e.g., not-needed)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Click the **checkmark** to verify the connection
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Check the URL has /v1 suffix: http://host.docker.internal:8642/v1 (not just :8642)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Verify the gateway is running: curl http://localhost:8642/health should return {"status": "ok"}
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Check model listing: curl http://localhost:8642/v1/models should return a list with hermes-agent
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Docker networking: From inside Docker, localhost means the container, not your host. Use host.docker.internal or --network=host.
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- 1. Enable the API server
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- 2. Start Hermes Agent gateway
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- 3. Start Open WebUI
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- 4. Open the UI
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- [Docker Compose Setup](#docker-compose-setup)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- [Configuring via the Admin UI](#configuring-via-the-admin-ui)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- [API Type: Chat Completions vs Responses](#api-type-chat-completions-vs-responses)[](#using-chat-completions-recommended)[](#using-responses-api)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Using Chat Completions (recommended)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Using Responses API
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- [How It Works](#how-it-works)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]], [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- [Configuration Reference](#configuration-reference)[](#hermes-agent-api-server)[](#open-webui)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Hermes Agent (API server)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Open WebUI
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- [Troubleshooting](#troubleshooting)[](#no-models-appear-in-the-dropdown)[](#connection-test-passes-but-no-models-load)[](#response-takes-a-long-time)[](#invalid-api-key-errors)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- No models appear in the dropdown
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Connection test passes but no models load
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Response takes a long time
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- "Invalid API key" errors
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- [Multi-User Setup with Profiles](#multi-user-setup-with-profiles)[](#1-create-profiles-and-configure-api-servers)[](#2-start-each-gateway)[](#3-add-connections-in-open-webui)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- 1. Create profiles and configure API servers
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- 2. Start each gateway
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- 3. Add connections in Open WebUI
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- [Linux Docker (no Docker Desktop)](#linux-docker-no-docker-desktop)
  - Sources: [[entities/open-webui-integration|Open WebUI Integration]]
- Receive messages via a persistent WebSocket connection to the QQ Gateway
  - Sources: [[entities/qq-bot|QQ Bot]]
- Send text and markdown replies via the REST API
  - Sources: [[entities/qq-bot|QQ Bot]]
- Download and process images, voice messages, and file attachments
  - Sources: [[entities/qq-bot|QQ Bot]]
- Transcribe voice messages using Tencent's built-in ASR or a configurable STT provider
  - Sources: [[entities/qq-bot|QQ Bot]]
- Create a new application and note your App ID and App Secret
  - Sources: [[entities/qq-bot|QQ Bot]]
- Enable the required intents: C2C messages, Group @-messages, Guild messages
  - Sources: [[entities/qq-bot|QQ Bot]]
- Configure your bot in sandbox mode for testing, or publish for production
  - Sources: [[entities/qq-bot|QQ Bot]]
- "user_openid_1"
  - Sources: [[entities/qq-bot|QQ Bot]]
- "group_openid_1"
  - Sources: [[entities/qq-bot|QQ Bot]]
- Zhipu/GLM (zai): Default provider, uses glm-asr model
  - Sources: [[entities/qq-bot|QQ Bot]]
- OpenAI Whisper: Set QQ_STT_BASE_URL and QQ_STT_MODEL
  - Sources: [[entities/qq-bot|QQ Bot]]
- Any OpenAI-compatible STT endpoint
  - Sources: [[entities/qq-bot|QQ Bot]]
- Invalid App ID / Secret — Double-check your credentials at q.qq.com
  - Sources: [[entities/qq-bot|QQ Bot]]
- Missing permissions — Ensure the bot has the required intents enabled
  - Sources: [[entities/qq-bot|QQ Bot]]
- Sandbox-only bot — If the bot is in sandbox mode, it can only receive messages from QQ's sandbox test channel
  - Sources: [[entities/qq-bot|QQ Bot]]
- Verify the bot's intents are enabled at q.qq.com
  - Sources: [[entities/qq-bot|QQ Bot]]
- Check QQ_ALLOWED_USERS if DM access is restricted
  - Sources: [[entities/qq-bot|QQ Bot]]
- For group messages, ensure the bot is @mentioned (group policy may require allowlisting)
  - Sources: [[entities/qq-bot|QQ Bot]]
- Check QQBOT_HOME_CHANNEL for cron/notification delivery
  - Sources: [[entities/qq-bot|QQ Bot]]
- Ensure aiohttp and httpx are installed: pip install aiohttp httpx
  - Sources: [[entities/qq-bot|QQ Bot]]
- Check network connectivity to api.sgroup.qq.com and the WebSocket gateway
  - Sources: [[entities/qq-bot|QQ Bot]]
- Review gateway logs for detailed error messages and reconnect behavior
  - Sources: [[entities/qq-bot|QQ Bot]]
- Interactive setup
  - Sources: [[entities/qq-bot|QQ Bot]]
- Manual configuration
  - Sources: [[entities/qq-bot|QQ Bot]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/email-setup|Email Setup]], [[entities/signal-setup|Signal Setup]], [[entities/discord-setup|Discord Setup]]
- [Advanced Configuration](#advanced-configuration)
  - Sources: [[entities/qq-bot|QQ Bot]]
- [Voice Messages (STT)](#voice-messages-stt)
  - Sources: [[entities/qq-bot|QQ Bot]]
- [Troubleshooting](#troubleshooting)[](#bot-disconnects-immediately-quick-disconnect)[](#voice-messages-not-transcribed)[](#messages-not-delivered)[](#connection-errors)
  - Sources: [[entities/qq-bot|QQ Bot]]
- Bot disconnects immediately (quick disconnect)
  - Sources: [[entities/qq-bot|QQ Bot]]
- Voice messages not transcribed
  - Sources: [[entities/qq-bot|QQ Bot]]
- Messages not delivered
  - Sources: [[entities/qq-bot|QQ Bot]]
- Connection errors
  - Sources: [[entities/qq-bot|QQ Bot]]
- A Mac (always on) running BlueBubbles Server
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Apple ID signed into Messages.app on that Mac
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- BlueBubbles Server v1.0.0+ (webhooks require this version)
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Network connectivity between Hermes and the BlueBubbles server
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Server URL (e.g., http://192.168.1.10:1234)
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Server Password
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Inbound: BlueBubbles sends webhook events to a local listener when new messages arrive. No polling — instant delivery.
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Outbound: Hermes sends messages via the BlueBubbles REST API.
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Media: Images, voice messages, videos, and documents are supported in both directions. Inbound attachments are downloaded and cached locally for the agent to process.
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Images: Photos appear natively in the iMessage conversation
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Voice messages: Audio files sent as iMessage voice messages
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Videos: Video attachments
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Documents: Files sent as iMessage attachments
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Tapback reactions
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]], [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Typing indicators
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]], [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]], [[entities/signal-setup|Signal Setup]]
- Read receipts
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]], [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Creating new chats by address
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Verify the server URL is correct and the Mac is on
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Check that BlueBubbles Server is running
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Ensure network connectivity (firewall, port forwarding)
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Check that the webhook is registered in BlueBubbles Server → Settings → API → Webhooks
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Verify the webhook URL is reachable from the Mac
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Check hermes logs gateway for webhook errors (or hermes logs -f to follow in real-time)
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Install the Private API helper: docs.bluebubbles.app
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Basic messaging works without it — only reactions, typing, and read receipts require it
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- 1. Install BlueBubbles Server
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- 2. Get your Server URL and Password
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- 3. Configure Hermes
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- 4. Authorize Users
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- 5. Start the Gateway
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- [Features](#features)[](#text-messaging)[](#rich-media)[](#tapback-reactions)[](#typing-indicators)[](#read-receipts)[](#chat-addressing)
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Text Messaging
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Rich Media
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Chat Addressing
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- [Private API](#private-api)
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- [Troubleshooting](#troubleshooting)[](#cannot-reach-server)[](#messages-not-arriving)[](#private-api-helper-not-connected)
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- "Cannot reach server"
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- Messages not arriving
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]], [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- "Private API helper not connected"
  - Sources: [[entities/bluebubbles-imessage|BlueBubbles (iMessage)]]
- A personal WeChat account
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Python packages: aiohttp and cryptography
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Terminal QR rendering is included when Hermes is installed with the messaging extra
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Long-poll transport — no public endpoint, webhook, or WebSocket needed
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- QR code login — scan-to-connect setup via hermes gateway setup
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- DM and group messaging — configurable access policies
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Media support — images, video, files, and voice messages
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- AES-128-ECB encrypted CDN — automatic encryption/decryption for all media transfers
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Context token persistence — disk-backed reply continuity across restarts
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Markdown formatting — preserves Markdown, including headers, tables, and code blocks, so WeChat clients that support Markdown can render it natively
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Smart message chunking — messages stay as a single bubble when under the limit; only oversized payloads split at logical boundaries
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Typing indicators — shows "typing…" status in the WeChat client while the agent processes
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- SSRF protection — outbound media URLs are validated before download
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Message deduplication — 5-minute sliding window prevents double-processing
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Automatic retry with backoff — recovers from transient API errors
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Inbound: Encrypted media is downloaded from the CDN using encrypted_query_param URLs, then decrypted with AES-128-ECB using the per-file key provided in the message payload.
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Outbound: Files are encrypted locally with a random AES-128-ECB key, uploaded to the CDN, and the encrypted reference is included in the outbound message.
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- The AES key is 16 bytes (128-bit). Keys may arrive as raw base64 or hex-encoded — the adapter handles both formats.
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- This requires the cryptography Python package.
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Tokens are saved per account+peer to ~/.hermes/weixin/accounts/<account_id>.context-tokens.json
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- On startup, previously saved tokens are restored
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Every inbound message updates the stored token for that sender
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Outbound messages automatically include the latest context token
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Headers stay as Markdown headings (#, ##, ...)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Tables stay as Markdown tables
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Code fences stay as fenced code blocks
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Excessive blank lines are collapsed to double newlines outside fenced code blocks
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Maximum message length: 4000 characters
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Messages under the limit stay intact even when they contain multiple paragraphs or line breaks
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Oversized messages split at logical boundaries (paragraphs, blank lines, code fences)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Code fences are kept intact whenever possible (never split mid-block unless the fence itself exceeds the limit)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Oversized individual blocks fall back to the base adapter's truncation logic
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- A 0.3 s inter-chunk delay prevents WeChat rate-limit drops when multiple chunks are sent
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- 1. Run the Setup Wizard
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- 2. Configure Environment Variables
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/home-assistant-integration|Home Assistant Integration]]
- 3. Start the Gateway
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/home-assistant-integration|Home Assistant Integration]]
- [Features](#features)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- [Configuration Options](#configuration-options)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- [Access Policies](#access-policies)[](#dm-policy)[](#group-policy)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Group Policy
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- [Media Support](#media-support)[](#inbound-receiving)[](#aes-128-ecb-encrypted-cdn)[](#outbound-sending)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Inbound (receiving)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]], [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- AES-128-ECB Encrypted CDN
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Outbound (sending)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]], [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Context Token Persistence](#context-token-persistence)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- [Markdown Formatting](#markdown-formatting)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- [Message Chunking](#message-chunking)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- [Typing Indicators](#typing-indicators)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- [Long-Poll Connection](#long-poll-connection)[](#how-it-works)[](#retry-behavior)[](#deduplication)[](#token-lock)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- How It Works
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/matrix-setup|Matrix Setup]], [[entities/slack-setup|Slack Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/messaging-gateway|Messaging Gateway]]
- Retry Behavior
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- Deduplication
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Token Lock
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]]
- [All Environment Variables](#all-environment-variables)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]], [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Troubleshooting](#troubleshooting)
  - Sources: [[entities/weixin-wechat|Weixin (WeChat)]], [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]], [[entities/feishu-lark-setup|Feishu / Lark Setup]], [[entities/email-setup|Email Setup]], [[entities/signal-setup|Signal Setup]], [[entities/whatsapp-setup|WhatsApp Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/installation|Installation]]
- A WeCom organization account
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- An AI Bot created in the WeCom Admin Console
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- The Bot ID and Secret from the bot's credentials page
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Python packages: aiohttp and httpx
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Bot credentials (via QR scan or manual entry)
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Access control settings (allowlist, pairing mode, or open access)
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Home channel for notifications
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- WebSocket transport — persistent connection, no public endpoint needed
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Per-group sender allowlists — fine-grained control over who can interact in each group
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Media support — images, files, voice, video upload and download
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- AES-encrypted media — automatic decryption for inbound attachments
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Quote context — preserves reply threading
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Markdown rendering — rich text responses
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Reply-mode streaming — correlates responses to inbound message context
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Auto-reconnect — exponential backoff on connection drops
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- "group_id_1"
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- "group_id_2"
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- "user_alice"
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- "user_bob"
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- "user_charlie"
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- "user_admin"
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- When an inbound media item includes an aeskey field, the adapter downloads the encrypted bytes and decrypts them using AES-256-CBC with PKCS#7 padding.
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- The AES key is the base64-decoded value of the aeskey field (must be exactly 32 bytes).
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- The IV is derived from the first 16 bytes of the key.
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- This requires the cryptography Python package (pip install cryptography).
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Images > 10 MB → sent as file
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Videos > 10 MB → sent as file
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Voice > 2 MB → sent as file
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Non-AMR audio → sent as file (WeCom only supports AMR for native voice)
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Step 1: Create an AI Bot
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Step 2: Configure Hermes
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Step 3: Start the gateway
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- [Access Policies](#access-policies)[](#dm-policy)[](#group-policy)[](#per-group-sender-allowlists)
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Per-Group Sender Allowlists
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- [Media Support](#media-support)[](#inbound-receiving)[](#aes-encrypted-media-decryption)[](#outbound-sending)
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- AES-Encrypted Media Decryption
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- [Reply-Mode Stream Responses](#reply-mode-stream-responses)
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- [Connection and Reconnection](#connection-and-reconnection)[](#connection-lifecycle)[](#reconnection-behavior)[](#deduplication)
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Connection Lifecycle
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- Reconnection Behavior
  - Sources: [[entities/wecom-enterprise-wechat|WeCom (Enterprise WeChat)]]
- websocket — recommended; Hermes opens the outbound connection and you do not need a public webhook endpoint
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- webhook — useful when you want Feishu/Lark to push events into your gateway over HTTP
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Feishu: https://open.feishu.cn/
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Lark: https://open.larksuite.com/
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Create a new app.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- In **Credentials & Basic Info**, copy the **App ID** and **App Secret**.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Enable the **Bot** capability for the app.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Run hermes gateway setup, select **Feishu / Lark**, and enter the credentials when prompted.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- feishu for Feishu China
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- lark for Lark international
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Button clicks become: /card button {"key": "value", ...}
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- The action's value payload from the card definition is included as JSON.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Card actions are deduplicated with a 15-minute window to prevent double processing.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Fetches the document content and comment timeline in parallel (20 messages for whole-doc threads, 12 for local-selection threads).
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Runs the agent with the feishu_doc + feishu_drive toolsets scoped to that single comment session.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Chunks replies at 4000 chars and posts them back as threaded replies.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Caches per-document sessions for 1 hour with a 50-message cap so follow-up comments on the same doc keep context.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- allowlist — a static list of users / tenants.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- pairing — static list ∪ runtime-approved store. Useful for rollouts where moderators can grant access live.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Subscribe to drive.notice.comment_add_v1 in Event Subscriptions.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Grant the docs:doc:readonly and drive:drive:readonly scopes so the handler can read document content.
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- .ogg, .opus → uploaded as opus audio
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- .mp4, .mov, .avi, .m4v → uploaded as mp4 media
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- .pdf, .doc(x), .xls(x), .ppt(x) → uploaded with their document type
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Everything else → uploaded as a generic stream file
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Window: 60-second sliding window
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Limit: 120 requests per window per (app_id, path, IP) triple
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Tracking cap: Up to 4096 unique keys tracked (prevents unbounded memory growth)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Body size limit: 1 MB maximum
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Body read timeout: 30 seconds
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Content-Type enforcement: Only application/json is accepted
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- "ou_admin_open_id"
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- "ou_user_open_id_1"
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- "ou_user_open_id_2"
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- "ou_blocked_user"
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Recommended: Scan-to-Create (one command)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Alternative: Manual Setup
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Step 2: Choose a Connection Mode](#step-2-choose-a-connection-mode)[](#recommended-websocket-mode)[](#optional-webhook-mode)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Recommended: WebSocket mode
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Optional: Webhook mode
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Step 3: Configure Hermes](#step-3-configure-hermes)[](#option-a-interactive-setup)[](#option-b-manual-configuration)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Option A: Interactive Setup
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Option B: Manual Configuration
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]], [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]], [[entities/telegram-setup|Telegram Setup]]
- [Step 4: Start the Gateway](#step-4-start-the-gateway)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]], [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- [Home Chat](#home-chat)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Security](#security)[](#user-allowlist)[](#webhook-encryption-key)[](#verification-token)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- User Allowlist
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Webhook Encryption Key
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Verification Token
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Group Message Policy](#group-message-policy)[](#bot-identity-for-mention-gating)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Bot Identity for @Mention Gating
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Interactive Card Actions](#interactive-card-actions)[](#required-feishu-app-configuration)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Required Feishu App Configuration
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]], [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Document Comment Intelligent Reply](#document-comment-intelligent-reply)[](#3-tier-access-control)[](#required-feishu-app-configuration-1)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- 3-Tier Access Control
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Media Support](#media-support)[](#inbound-receiving)[](#outbound-sending)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Markdown Rendering and Post Fallback](#markdown-rendering-and-post-fallback)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Processing Status Reactions](#processing-status-reactions)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Burst Protection and Batching](#burst-protection-and-batching)[](#text-batching)[](#media-batching)[](#per-chat-serialization)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Text Batching
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Media Batching
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Per-Chat Serialization
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Rate Limiting (Webhook Mode)](#rate-limiting-webhook-mode)[](#webhook-anomaly-tracking)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- Webhook Anomaly Tracking
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [WebSocket Tuning](#websocket-tuning)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Per-Group Access Control](#per-group-access-control)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Deduplication](#deduplication)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- [Toolset](#toolset)
  - Sources: [[entities/feishu-lark-setup|Feishu / Lark Setup]]
- each DM gets its own session
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- each user in a shared group chat gets their own session inside that group
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- dingtalk-stream — DingTalk's official SDK for Stream Mode (WebSocket-based real-time messaging)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- alibabacloud-dingtalk — DingTalk OpenAPI SDK for AI Cards, emoji reactions, and media downloads
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- App Name: e.g., Hermes Agent
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Description: optional
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/mattermost-setup|Mattermost Setup]]
- After creating, navigate to **Credentials & Basic Info** to find your **Client ID** (AppKey) and **Client Secret** (AppSecret). Copy both.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- QR-code device flow (recommended). Scan the QR that prints in your terminal with the DingTalk mobile app — your Client ID and Client Secret are returned automatically and written to ~/.hermes/.env. No developer-console trip needed.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Manual paste. If you already have credentials (or QR scanning isn't convenient), paste your Client ID, Client Secret, and allowed user IDs when prompted.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- group_sessions_per_user: true keeps each participant's context isolated inside shared group chats
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- 🤔Thinking — added when the bot starts processing your message
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- 🥳Done — added when the response is complete (replaces the Thinking reaction)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Stream Mode: No public URL, domain name, or webhook server needed. The connection is initiated from your machine via WebSocket, so it works behind NAT and firewalls.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- AI Cards: Optionally reply with rich AI Cards instead of plain markdown. Configure via card_template_id.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Emoji Reactions: Automatic 🤔Thinking/🥳Done reactions for processing status.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Markdown responses: Replies are formatted in DingTalk's markdown format for rich text display.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Media support: Images and files in incoming messages are automatically resolved and can be processed by vision tools.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Message deduplication: The adapter deduplicates messages with a 5-minute window to prevent processing the same message twice.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Auto-reconnection: If the stream connection drops, the adapter automatically reconnects with exponential backoff.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Message length limit: Responses are capped at 20,000 characters per message. Longer responses are truncated.
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Session Model in DingTalk
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- [Prerequisites](#prerequisites)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/installation|Installation]]
- [Step 1: Create a DingTalk App](#step-1-create-a-dingtalk-app)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- [Step 2: Enable the Robot Capability](#step-2-enable-the-robot-capability)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- [Step 3: Find Your DingTalk User ID](#step-3-find-your-dingtalk-user-id)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- [Step 4: Configure Hermes Agent](#step-4-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]]
- Option A: Interactive Setup (Recommended)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]], [[entities/telegram-setup|Telegram Setup]]
- Start the Gateway
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/telegram-setup|Telegram Setup]]
- [Features](#features)[](#ai-cards)[](#emoji-reactions)[](#display-settings)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Emoji Reactions
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Display Settings
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#dingtalk-stream-not-installed-error)[](#dingtalk_client_id-and-dingtalk_client_secret-required)[](#stream-disconnects--reconnection-loops)[](#bot-is-offline)[](#no-session_webhook-available)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Bot is not responding to messages
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]]
- "dingtalk-stream not installed" error
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- "DINGTALK_CLIENT_ID and DINGTALK_CLIENT_SECRET required"
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Stream disconnects / reconnection loops
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- Bot is offline
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- "No session_webhook available"
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]]
- [Security](#security)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/home-assistant-integration|Home Assistant Integration]], [[entities/email-setup|Email Setup]], [[entities/signal-setup|Signal Setup]], [[entities/whatsapp-setup|WhatsApp Setup]], [[entities/slack-setup|Slack Setup]]
- [Notes](#notes)
  - Sources: [[entities/dingtalk-setup|DingTalk Setup]], [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]]
- each thread gets its own session namespace
  - Sources: [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]]
- each user in a shared room gets their own session inside that room
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- users share context growth and token costs
  - Sources: [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- one person's long tool-heavy task can bloat everyone else's context
  - Sources: [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- one person's in-flight run can interrupt another person's follow-up in the same room
  - Sources: [[entities/matrix-setup|Matrix Setup]], [[entities/discord-setup|Discord Setup]]
- "!abc123:matrix.org"
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- H "Content-Type: application/json" \
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- group_sessions_per_user: true keeps each participant's context isolated inside shared rooms
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Stores encryption keys in ~/.hermes/platforms/matrix/store/ (legacy installs: ~/.hermes/matrix/store/)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Uploads device keys on first connection
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Decrypts incoming messages and encrypts outgoing messages automatically
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Auto-joins encrypted rooms when invited
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- API_SERVER_HOST=0.0.0.0 binds to all interfaces so the Docker container can reach it.
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- API_SERVER_KEY is required for non-loopback binding. Pick a strong random string.
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- The API server runs on port 8642 by default (change with API_SERVER_PORT if needed).
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- ./matrix-store:/root/.hermes/platforms/matrix/store
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Any homeserver: Works with Synapse, Conduit, Dendrite, matrix.org, or any spec-compliant Matrix homeserver. No specific homeserver software required.
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Federation: If you're on a federated homeserver, the bot can communicate with users from other servers — just add their full @user:server IDs to MATRIX_ALLOWED_USERS.
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Auto-join: The bot automatically accepts room invites and joins. It starts responding immediately after joining.
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Media support: Hermes can send and receive images, audio, video, and file attachments. Media is uploaded to your homeserver using the Matrix content repository API.
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Native voice messages (MSC3245): The Matrix adapter automatically tags outgoing voice messages with the org.matrix.msc3245.voice flag. This means TTS responses and voice audio are rendered as native voice bubbles in Element and other clients that support MSC3245, rather than as generic audio file attachments. Incoming voice messages with the MSC3245 flag are also correctly identified and routed to speech-to-text transcription. No configuration is needed — this works automatically.
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Session Model in Matrix
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Mention and Threading Configuration
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- [Step 1: Create a Bot Account](#step-1-create-a-bot-account)[](#option-a-register-on-your-homeserver-recommended)[](#option-b-use-matrixorg-or-another-public-homeserver)[](#option-c-use-your-own-account)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Option A: Register on Your Homeserver (Recommended)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Option B: Use matrix.org or Another Public Homeserver
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Option C: Use Your Own Account
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- [Step 2: Get an Access Token](#step-2-get-an-access-token)[](#option-a-access-token-recommended)[](#option-b-password-login)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Option A: Access Token (Recommended)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Option B: Password Login
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- [Step 3: Find Your Matrix User ID](#step-3-find-your-matrix-user-id)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- [End-to-End Encryption (E2EE)](#end-to-end-encryption-e2ee)[](#requirements)[](#enable-e2ee)[](#cross-signing-verification-recommended)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Requirements
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Enable E2EE
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Cross-Signing Verification (Recommended)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- [Home Room](#home-room)[](#using-the-slash-command)[](#manual-configuration)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Using the Slash Command
  - Sources: [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#failed-to-authenticate--whoami-failed-on-startup)[](#mautrix-not-installed-error)[](#encryption-errors--could-not-decrypt-event)[](#upgrading-from-a-previous-version-with-e2ee)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- "Failed to authenticate" / "whoami failed" on startup
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- "mautrix not installed" error
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Encryption errors / "could not decrypt event"
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Upgrading from a previous version with E2EE
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- [Proxy Mode (E2EE on macOS)](#proxy-mode-e2ee-on-macos)[](#how-it-works)[](#step-1-configure-the-host-macos)[](#step-2-configure-the-docker-container-linux-vm)[](#step-3-start-both)[](#configuration-reference)[](#works-for-any-platform)[](#sync-issues--bot-falls-behind)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Step 1: Configure the Host (macOS)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Step 2: Configure the Docker Container (Linux VM)
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Step 3: Start Both
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Configuration Reference
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Works for Any Platform
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- Sync issues / bot falls behind
  - Sources: [[entities/matrix-setup|Matrix Setup]]
- "User not allowed" / Bot ignores you
  - Sources: [[entities/matrix-setup|Matrix Setup]], [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- each user in a shared channel gets their own session inside that channel
  - Sources: [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- one person's in-flight run can interrupt another person's follow-up in the same channel
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Username: e.g., hermes
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Display Name: e.g., Hermes Agent
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Role: Member is sufficient
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Click **Create Bot Account**.
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Mattermost will display the **bot token**. **Copy it immediately.**
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- group_sessions_per_user: true keeps each participant's context isolated inside shared channels and threads
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Self-hosted friendly: Works with any self-hosted Mattermost instance. No Mattermost Cloud account or subscription required.
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- No extra dependencies: The adapter uses aiohttp for HTTP and WebSocket, which is already included with Hermes Agent.
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Team Edition compatible: Works with both Mattermost Team Edition (free) and Enterprise Edition.
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- Session Model in Mattermost
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Step 1: Enable Bot Accounts](#step-1-enable-bot-accounts)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Step 2: Create a Bot Account](#step-2-create-a-bot-account)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Step 3: Add the Bot to Channels](#step-3-add-the-bot-to-channels)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Step 4: Find Your Mattermost User ID](#step-4-find-your-mattermost-user-id)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Step 5: Configure Hermes Agent](#step-5-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Home Channel](#home-channel)[](#using-the-slash-command)[](#manual-configuration)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- [Reply Mode](#reply-mode)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Mention Behavior](#mention-behavior)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#403-forbidden-errors)[](#websocket-disconnects--reconnection-loops)[](#failed-to-authenticate-on-startup)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- 403 Forbidden errors
  - Sources: [[entities/mattermost-setup|Mattermost Setup]], [[entities/discord-setup|Discord Setup]]
- WebSocket disconnects / reconnection loops
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- "Failed to authenticate" on startup
  - Sources: [[entities/mattermost-setup|Mattermost Setup]]
- [Per-Channel Prompts](#per-channel-prompts)
  - Sources: [[entities/mattermost-setup|Mattermost Setup]], [[entities/slack-setup|Slack Setup]], [[entities/telegram-setup|Telegram Setup]]
- domain (optional) — Filter by entity domain: light, switch, climate, sensor, binary_sensor, cover, fan, media_player, etc.
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- area (optional) — Filter by area/room name (matches against friendly names): living room, kitchen, bedroom, etc.
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- entity_id (required) — The entity to query, e.g., light.living_room, climate.thermostat, sensor.temperature
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- domain (optional) — Filter by domain, e.g., light, climate, switch
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- domain (required) — Service domain: light, switch, climate, cover, media_player, fan, scene, script
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- service (required) — Service name: turn_on, turn_off, toggle, set_temperature, set_hvac_mode, open_cover, close_cover, set_volume_level
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- entity_id (optional) — Target entity, e.g., light.living_room
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- data (optional) — Additional parameters as a JSON object
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- binary_sensor
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- alarm_control_panel
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- sensor.front_door_battery
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- sensor.uptime
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- sensor.cpu_usage
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- sensor.memory_usage
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- WebSocket with 30-second heartbeat for real-time events
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Automatic reconnection with backoff: 5s → 10s → 30s → 60s
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- REST API for outbound notifications (separate session to avoid WebSocket conflicts)
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Authorization — HA events are always authorized (no user allowlist needed, since the HASS_TOKEN authenticates the connection)
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- shell_command — arbitrary shell commands
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- command_line — sensors/switches that execute commands
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- python_script — scripted Python execution
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- pyscript — broader scripting integration
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- hassio — addon control, host shutdown/reboot
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- rest_command — HTTP requests from HA server (SSRF vector)
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- 1. Create a Long-Lived Access Token
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- [Available Tools](#available-tools)[](#ha_list_entities)[](#ha_get_state)[](#ha_list_services)[](#ha_call_service)
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- ha_list_entities
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- ha_get_state
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- ha_list_services
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- ha_call_service
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- [Gateway Platform: Real-Time Events](#gateway-platform-real-time-events)[](#event-filtering)[](#event-formatting)[](#agent-responses)[](#connection-management)
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Event Filtering
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Event Formatting
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Agent Responses
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Connection Management
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- [Example Automations](#example-automations)[](#morning-routine)[](#security-check)[](#reactive-automation-via-gateway-events)
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Morning Routine
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Security Check
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Reactive Automation (via Gateway Events)
  - Sources: [[entities/home-assistant-integration|Home Assistant Integration]]
- Twilio account — Sign up at twilio.com (free trial available)
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- A Twilio phone number with SMS capability
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- A publicly accessible server — Twilio sends webhooks to your server when SMS arrives
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- aiohttp — pip install 'hermes-agent[sms]'
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Webhook: https://your-server:8080/webhooks/twilio
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- HTTP Method: POST
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Plain text only — Markdown is automatically stripped since SMS renders it as literal characters
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- 1600 character limit — Longer responses are split across multiple messages at natural boundaries (newlines, then spaces)
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Echo prevention — Messages from your own Twilio number are ignored to prevent loops
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Phone number redaction — Phone numbers are redacted in logs for privacy
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Interactive setup (recommended)
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Manual setup
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- [Step 3: Configure Twilio Webhook](#step-3-configure-twilio-webhook)
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- [SMS-Specific Behavior](#sms-specific-behavior)
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- [Security](#security)[](#webhook-signature-validation)[](#user-allowlists)
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Webhook signature validation
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- User allowlists
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- [Troubleshooting](#troubleshooting)[](#messages-not-arriving)[](#replies-not-sending)[](#webhook-port-conflicts)
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Replies not sending
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- Webhook port conflicts
  - Sources: [[entities/sms-setup-twilio|SMS Setup (Twilio)]]
- A dedicated email account for your Hermes agent (don't use your personal email)
  - Sources: [[entities/email-setup|Email Setup]]
- IMAP enabled on the email account
  - Sources: [[entities/email-setup|Email Setup]]
- An app password if using Gmail or another provider with 2FA
  - Sources: [[entities/email-setup|Email Setup]]
- IMAP host and port (usually port 993 with SSL)
  - Sources: [[entities/email-setup|Email Setup]]
- SMTP host and port (usually port 587 with STARTTLS)
  - Sources: [[entities/email-setup|Email Setup]]
- Whether app passwords are required
  - Sources: [[entities/email-setup|Email Setup]]
- Images (JPEG, PNG, GIF, WebP) → available to the vision tool
  - Sources: [[entities/email-setup|Email Setup]]
- Documents (PDF, ZIP, etc.) → available for file access
  - Sources: [[entities/email-setup|Email Setup]]
- HTML-only emails** have tags stripped for plain text extraction
  - Sources: [[entities/email-setup|Email Setup]]
- Self-messages** are filtered out to prevent reply loops
  - Sources: [[entities/email-setup|Email Setup]]
- Automated/noreply senders** are silently ignored — noreply@, mailer-daemon@, bounce@, no-reply@, and emails with Auto-Submitted, Precedence: bulk, or List-Unsubscribe headers
  - Sources: [[entities/email-setup|Email Setup]]
- In-Reply-To and References headers maintain the thread
  - Sources: [[entities/email-setup|Email Setup]]
- Subject line preserved with Re: prefix (no double Re: Re:)
  - Sources: [[entities/email-setup|Email Setup]]
- Message-ID generated with the agent's domain
  - Sources: [[entities/email-setup|Email Setup]]
- Responses are sent as plain text (UTF-8)
  - Sources: [[entities/email-setup|Email Setup]]
- Use App Passwords instead of your main password (required for Gmail with 2FA)
  - Sources: [[entities/email-setup|Email Setup]]
- Set EMAIL_ALLOWED_USERS to restrict who can interact with the agent
  - Sources: [[entities/email-setup|Email Setup]]
- The password is stored in ~/.hermes/.env — protect this file (chmod 600)
  - Sources: [[entities/email-setup|Email Setup]]
- IMAP uses SSL (port 993) and SMTP uses STARTTLS (port 587) by default — connections are encrypted
  - Sources: [[entities/email-setup|Email Setup]]
- Gmail Setup
  - Sources: [[entities/email-setup|Email Setup]]
- Outlook / Microsoft 365
  - Sources: [[entities/email-setup|Email Setup]]
- Other Providers
  - Sources: [[entities/email-setup|Email Setup]]
- [Step 1: Configure Hermes](#step-1-configure-hermes)[](#manual-configuration)
  - Sources: [[entities/email-setup|Email Setup]]
- [Step 2: Start the Gateway](#step-2-start-the-gateway)
  - Sources: [[entities/email-setup|Email Setup]]
- [How It Works](#how-it-works)[](#receiving-messages)[](#sending-replies)[](#file-attachments)[](#skipping-attachments)
  - Sources: [[entities/email-setup|Email Setup]]
- Receiving Messages
  - Sources: [[entities/email-setup|Email Setup]]
- Sending Replies
  - Sources: [[entities/email-setup|Email Setup]]
- File Attachments
  - Sources: [[entities/email-setup|Email Setup]]
- Skipping Attachments
  - Sources: [[entities/email-setup|Email Setup]]
- [Access Control](#access-control)
  - Sources: [[entities/email-setup|Email Setup]]
- [Environment Variables Reference](#environment-variables-reference)
  - Sources: [[entities/email-setup|Email Setup]], [[entities/signal-setup|Signal Setup]]
- signal-cli — Java-based Signal client (GitHub)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Java 17+ runtime — required by signal-cli
  - Sources: [[entities/signal-setup|Signal Setup]]
- A phone number with Signal installed (for linking as a secondary device)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Images — PNG, JPEG, GIF, WebP (auto-detected via magic bytes)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Audio — MP3, OGG, WAV, M4A (voice messages transcribed if Whisper is configured)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Documents — PDF, ZIP, and other file types
  - Sources: [[entities/signal-setup|Signal Setup]]
- Images — send_image_file sends PNG, JPEG, GIF, WebP as native Signal attachments
  - Sources: [[entities/signal-setup|Signal Setup]]
- Voice — send_voice sends audio files (OGG, MP3, WAV, M4A, AAC) as attachments
  - Sources: [[entities/signal-setup|Signal Setup]]
- Video — send_video sends MP4 video files
  - Sources: [[entities/signal-setup|Signal Setup]]
- Documents — send_document sends any file type (PDF, ZIP, etc.)
  - Sources: [[entities/signal-setup|Signal Setup]]
- +15551234567 → +155****4567
  - Sources: [[entities/signal-setup|Signal Setup]]
- This applies to both Hermes gateway logs and the global redaction system
  - Sources: [[entities/signal-setup|Signal Setup]]
- "Note to Self" messages arrive as syncMessage.sentMessage envelopes
  - Sources: [[entities/signal-setup|Signal Setup]]
- The adapter detects when these are addressed to the bot's own account and processes them as regular inbound messages
  - Sources: [[entities/signal-setup|Signal Setup]]
- Echo-back protection (sent-timestamp tracking) prevents infinite loops — the bot's own replies are filtered out automatically
  - Sources: [[entities/signal-setup|Signal Setup]]
- The connection drops (with exponential backoff: 2s → 60s)
  - Sources: [[entities/signal-setup|Signal Setup]]
- No activity is detected for 120 seconds (pings signal-cli to verify)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Phone numbers are redacted in all log output
  - Sources: [[entities/signal-setup|Signal Setup]]
- Use DM pairing or explicit allowlists for safe onboarding of new users
  - Sources: [[entities/signal-setup|Signal Setup]]
- Keep groups disabled unless you specifically need group support, or allowlist only the groups you trust
  - Sources: [[entities/signal-setup|Signal Setup]]
- Signal's end-to-end encryption protects message content in transit
  - Sources: [[entities/signal-setup|Signal Setup]]
- The signal-cli session data in ~/.local/share/signal-cli/ contains account credentials — protect it like a password
  - Sources: [[entities/signal-setup|Signal Setup]]
- Installing signal-cli
  - Sources: [[entities/signal-setup|Signal Setup]]
- [Step 1: Link Your Signal Account](#step-1-link-your-signal-account)
  - Sources: [[entities/signal-setup|Signal Setup]]
- [Step 2: Start the signal-cli Daemon](#step-2-start-the-signal-cli-daemon)
  - Sources: [[entities/signal-setup|Signal Setup]]
- [Step 3: Configure Hermes](#step-3-configure-hermes)[](#manual-configuration)
  - Sources: [[entities/signal-setup|Signal Setup]]
- [Access Control](#access-control)[](#dm-access)[](#group-access)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Group Access
  - Sources: [[entities/signal-setup|Signal Setup]]
- [Features](#features)[](#attachments)[](#typing-indicators)[](#phone-number-redaction)[](#note-to-self-single-number-setup)[](#health-monitoring)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Attachments
  - Sources: [[entities/signal-setup|Signal Setup]]
- Phone Number Redaction
  - Sources: [[entities/signal-setup|Signal Setup]]
- Note to Self (Single-Number Setup)
  - Sources: [[entities/signal-setup|Signal Setup]]
- Health Monitoring
  - Sources: [[entities/signal-setup|Signal Setup]]
- Use a dedicated phone number for the bot (not your personal number)
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Don't send bulk/spam messages — keep usage conversational
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Don't automate outbound messaging to people who haven't messaged first
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Node.js v18+ and npm — the WhatsApp bridge runs as a Node.js process
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- A phone with WhatsApp installed (for scanning the QR code)
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- unauthorized_dm_behavior: pair is the global default. Unknown DM senders get a pairing code.
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- whatsapp.unauthorized_dm_behavior: ignore makes WhatsApp stay silent for unauthorized DMs, which is usually the better choice for a private number.
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Sessions survive restarts — you don't need to re-scan the QR code every time
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- The session data includes encryption keys and device credentials
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Do not share or commit this session directory — it grants full access to the WhatsApp account
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Incoming: Voice messages (.ogg opus) are automatically transcribed using the configured STT provider: local faster-whisper, Groq Whisper (GROQ_API_KEY), or OpenAI Whisper (VOICE_TOOLS_OPENAI_KEY)
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Outgoing: TTS responses are sent as MP3 audio file attachments
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Agent responses are prefixed with "⚕ Hermes Agent" by default. You can customize or disable this in config.yaml:
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- The ~/.hermes/platforms/whatsapp/session directory contains full session credentials — protect it like a password
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Set file permissions: chmod 700 ~/.hermes/platforms/whatsapp/session
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Use a dedicated phone number for the bot to isolate risk from your personal account
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- If you suspect compromise, unlink the device from WhatsApp → Settings → Linked Devices
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Phone numbers in logs are partially redacted, but review your log retention policy
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- WhatsApp-Compatible Markdown
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Tool Progress
  - Sources: [[entities/whatsapp-setup|WhatsApp Setup]]
- Name it something like hermes-socket (the name doesn't matter)
  - Sources: [[entities/slack-setup|Slack Setup]]
- Add the connections:write scope
  - Sources: [[entities/slack-setup|Slack Setup]]
- Click Generate
  - Sources: [[entities/slack-setup|Slack Setup]]
- Copy the token** — it starts with xapp-. This is your SLACK_APP_TOKEN
  - Sources: [[entities/slack-setup|Slack Setup]]
- "hey hermes"
  - Sources: [[entities/slack-setup|Slack Setup]]
- The first token in the list is the primary token, used for the Socket Mode connection (AsyncApp).
  - Sources: [[entities/slack-setup|Slack Setup]]
- Each token is authenticated via auth.test on startup. The gateway maps each team_id to its own WebClient and bot_user_id.
  - Sources: [[entities/slack-setup|Slack Setup]]
- When a message arrives, Hermes uses the correct workspace-specific client to respond.
  - Sources: [[entities/slack-setup|Slack Setup]]
- The primary bot_user_id (from the first token) is used for backward compatibility with features that expect a single bot identity.
  - Sources: [[entities/slack-setup|Slack Setup]]
- Incoming: Voice/audio messages are automatically transcribed using the configured STT provider: local faster-whisper, Groq Whisper (GROQ_API_KEY), or OpenAI Whisper (VOICE_TOOLS_OPENAI_KEY)
  - Sources: [[entities/slack-setup|Slack Setup]]
- Outgoing: TTS responses are sent as audio file attachments
  - Sources: [[entities/slack-setup|Slack Setup]]
- Tokens should be stored in ~/.hermes/.env (file permissions 600)
  - Sources: [[entities/slack-setup|Slack Setup]]
- Rotate tokens periodically via the Slack app settings
  - Sources: [[entities/slack-setup|Slack Setup]]
- Audit who has access to your Hermes config directory
  - Sources: [[entities/slack-setup|Slack Setup]]
- Socket Mode means no public endpoint is exposed — one less attack surface
  - Sources: [[entities/slack-setup|Slack Setup]]
- Thread & Reply Behavior
  - Sources: [[entities/slack-setup|Slack Setup]]
- Session Isolation
  - Sources: [[entities/slack-setup|Slack Setup]]
- Mention & Trigger Behavior
  - Sources: [[entities/slack-setup|Slack Setup]]
- Unauthorized User Handling
  - Sources: [[entities/slack-setup|Slack Setup]]
- Voice Transcription
  - Sources: [[entities/slack-setup|Slack Setup]]
- [Home Channel](#home-channel)
  - Sources: [[entities/slack-setup|Slack Setup]], [[entities/telegram-setup|Telegram Setup]]
- [Multi-Workspace Support](#multi-workspace-support)[](#configuration)[](#oauth-token-file)[](#how-it-works)
  - Sources: [[entities/slack-setup|Slack Setup]]
- Configuration
  - Sources: [[entities/slack-setup|Slack Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]]
- OAuth Token File
  - Sources: [[entities/slack-setup|Slack Setup]]
- [Voice Messages](#voice-messages)
  - Sources: [[entities/slack-setup|Slack Setup]], [[entities/discord-setup|Discord Setup]]
- [Troubleshooting](#troubleshooting)[](#quick-checklist)
  - Sources: [[entities/slack-setup|Slack Setup]]
- Quick Checklist
  - Sources: [[entities/slack-setup|Slack Setup]]
- each server thread gets its own session namespace
  - Sources: [[entities/discord-setup|Discord Setup]]
- Alice interrupting her own in-flight request only affects Alice's session in that channel
  - Sources: [[entities/discord-setup|Discord Setup]]
- Bob can keep talking in the same channel without inheriting Alice's history or interrupting Alice's run
  - Sources: [[entities/discord-setup|Discord Setup]]
- the whole room shares one running-agent slot for that channel/thread
  - Sources: [[entities/discord-setup|Discord Setup]]
- follow-up messages from different people can interrupt or queue behind each other
  - Sources: [[entities/discord-setup|Discord Setup]]
- Set Public Bot to ON — required to use the Discord-provided invite link (recommended). This allows the Installation tab to generate a default authorization URL.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Leave Require OAuth2 Code Grant set to OFF.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Without Message Content Intent, your bot receives message events but the message text is empty — the bot literally cannot see what you typed.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Without Server Members Intent, the bot cannot resolve usernames for the allowed users list and may fail to identify who is messaging it.
  - Sources: [[entities/discord-setup|Discord Setup]]
- If your bot is in fewer than 100 servers, you can simply toggle intents on and off freely.
  - Sources: [[entities/discord-setup|Discord Setup]]
- If your bot is in 100 or more servers, Discord requires you to submit a verification application to use privileged intents. For personal use, this is not a concern.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Scopes: select bot and applications.commands
  - Sources: [[entities/discord-setup|Discord Setup]]
- Permissions: select the permissions listed below.
  - Sources: [[entities/discord-setup|Discord Setup]]
- View Channels — see the channels it has access to
  - Sources: [[entities/discord-setup|Discord Setup]]
- Send Messages — respond to your messages
  - Sources: [[entities/discord-setup|Discord Setup]]
- Embed Links — format rich responses
  - Sources: [[entities/discord-setup|Discord Setup]]
- Attach Files — send images, audio, and file outputs
  - Sources: [[entities/discord-setup|Discord Setup]]
- Read Message History — maintain conversation context
  - Sources: [[entities/discord-setup|Discord Setup]]
- Send Messages in Threads — respond in thread conversations
  - Sources: [[entities/discord-setup|Discord Setup]]
- Add Reactions — react to messages for acknowledgment
  - Sources: [[entities/discord-setup|Discord Setup]]
- 1234567890
  - Sources: [[entities/discord-setup|Discord Setup]], [[entities/discord-setup|Discord Setup]]
- 9876543210
  - Sources: [[entities/discord-setup|Discord Setup]], [[entities/discord-setup|Discord Setup]]
- 👀 added when the bot starts processing your message
  - Sources: [[entities/discord-setup|Discord Setup]]
- ✅ added when the response is delivered successfully
  - Sources: [[entities/discord-setup|Discord Setup]]
- ❌ added if an error occurs during processing
  - Sources: [[entities/discord-setup|Discord Setup]]
- 1234567890 # Bot responds inline here
  - Sources: [[entities/discord-setup|Discord Setup]]
- Exact thread/channel ID matches win.
  - Sources: [[entities/discord-setup|Discord Setup]]
- If a message arrives inside a thread or forum post and that thread has no explicit entry, Hermes falls back to the parent channel/forum ID.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Prompts are applied ephemerally at runtime, so changing them affects future turns immediately without rewriting past session history.
  - Sources: [[entities/discord-setup|Discord Setup]]
- off — no progress messages
  - Sources: [[entities/discord-setup|Discord Setup]]
- new — only show the first tool call per turn
  - Sources: [[entities/discord-setup|Discord Setup]]
- all — show all tool calls (truncated to 40 characters in gateway messages)
  - Sources: [[entities/discord-setup|Discord Setup]]
- verbose — show full tool call details (can produce long messages)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Each skill becomes a Discord slash command (e.g., /code-review, /ascii-art)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Skills accept an optional args string parameter
  - Sources: [[entities/discord-setup|Discord Setup]]
- Discord has a limit of 100 application commands per bot — if you have more skills than available slots, extra skills are skipped with a warning in the logs
  - Sources: [[entities/discord-setup|Discord Setup]]
- Skills are registered during bot startup alongside built-in commands like /model, /reset, and /background
  - Sources: [[entities/discord-setup|Discord Setup]]
- Incoming voice messages are automatically transcribed using the configured STT provider: local faster-whisper (no key), Groq Whisper (GROQ_API_KEY), or OpenAI Whisper (VOICE_TOOLS_OPENAI_KEY).
  - Sources: [[entities/discord-setup|Discord Setup]]
- Text-to-speech: Use /voice tts to have the bot send spoken audio responses alongside text replies.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Discord voice channels: Hermes can also join a voice channel, listen to users speaking, and talk back in the channel.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Voice Mode
  - Sources: [[entities/discord-setup|Discord Setup]]
- Use Voice Mode with Hermes
  - Sources: [[entities/discord-setup|Discord Setup]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Thread name is derived from the first line of the message (markdown heading prefix stripped, capped at 100 chars). When the message is attachment-only, the filename is used as the fallback thread name.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Attachments ride along on the starter message of the new thread — no separate upload step, no partial sends.
  - Sources: [[entities/discord-setup|Discord Setup]]
- One call, one thread: each forum send creates a new thread. Successive sends to the same forum will therefore produce separate threads.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Detection is three-layered: the channel directory cache first, a process-local probe cache second, and a live GET /channels/{id} probe as a last resort (whose result is then memoized for the life of the process).
  - Sources: [[entities/discord-setup|Discord Setup]]
- OR with user allowlist. A user is authorized if their ID is in DISCORD_ALLOWED_USERS or they have any role in DISCORD_ALLOWED_ROLES.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Server Members Intent auto-enabled. When DISCORD_ALLOWED_ROLES is set, the bot enables the Members intent on connect — required for Discord to send role information with member records.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Role IDs, not names. Grab them from Discord: User Settings → Advanced → Developer Mode ON, then right-click any role → Copy Role ID.
  - Sources: [[entities/discord-setup|Discord Setup]]
- DM fallback. In DMs the role check scans mutual guilds; a user with an allowed role in any shared server is authorized in DMs too.
  - Sources: [[entities/discord-setup|Discord Setup]]
- Discord Gateway Model
  - Sources: [[entities/discord-setup|Discord Setup]]
- Session Model in Discord
  - Sources: [[entities/discord-setup|Discord Setup]]
- Interrupts and Concurrency
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 1: Create a Discord Application](#step-1-create-a-discord-application)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 2: Create the Bot](#step-2-create-the-bot)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 3: Enable Privileged Gateway Intents](#step-3-enable-privileged-gateway-intents)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 4: Get the Bot Token](#step-4-get-the-bot-token)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 5: Generate the Invite URL](#step-5-generate-the-invite-url)[](#option-a-using-the-installation-tab-recommended)[](#option-b-manual-url)[](#required-permissions)[](#recommended-additional-permissions)[](#permission-integers)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Option A: Using the Installation Tab (Recommended)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Option B: Manual URL
  - Sources: [[entities/discord-setup|Discord Setup]]
- Required Permissions
  - Sources: [[entities/discord-setup|Discord Setup]]
- Recommended Additional Permissions
  - Sources: [[entities/discord-setup|Discord Setup]]
- Permission Integers
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 6: Invite to Your Server](#step-6-invite-to-your-server)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 7: Find Your Discord User ID](#step-7-find-your-discord-user-id)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Step 8: Configure Hermes Agent](#step-8-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Configuration Reference](#configuration-reference)[](#environment-variables-env)[](#config-file-configyaml)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Environment Variables (.env)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Config File (config.yaml)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Interactive Model Picker](#interactive-model-picker)
  - Sources: [[entities/discord-setup|Discord Setup]], [[entities/telegram-setup|Telegram Setup]]
- [Native Slash Commands for Skills](#native-slash-commands-for-skills)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Forum Channels](#forum-channels)
  - Sources: [[entities/discord-setup|Discord Setup]]
- [Troubleshooting](#troubleshooting)[](#bot-is-online-but-not-responding-to-messages)[](#disallowed-intents-error-on-startup)[](#bot-cant-see-messages-in-a-specific-channel)[](#403-forbidden-errors)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)[](#people-in-the-same-channel-are-sharing-context-unexpectedly)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Bot is online but not responding to messages
  - Sources: [[entities/discord-setup|Discord Setup]]
- "Disallowed Intents" error on startup
  - Sources: [[entities/discord-setup|Discord Setup]]
- Bot can't see messages in a specific channel
  - Sources: [[entities/discord-setup|Discord Setup]]
- People in the same channel are sharing context unexpectedly
  - Sources: [[entities/discord-setup|Discord Setup]]
- [[[entity.security|Security]]](#[[entity.security|Security]])[](#role-based-access-control)[](#mention-control)
  - Sources: [[entities/discord-setup|Discord Setup]]
- Role-Based Access Control
  - Sources: [[entities/discord-setup|Discord Setup]]
- Mention Control
  - Sources: [[entities/discord-setup|Discord Setup]]
- Messages that start with a / command
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Replies directly to the bot's own messages
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Service messages (member joins/leaves, pinned messages, etc.)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Messages in channels where the bot is an admin
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- the agent writes a file inside Docker to /workspace/report.txt
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- the model emits MEDIA:/workspace/report.txt
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Telegram delivery fails because /workspace/report.txt only exists inside the
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- "/home/user/.hermes/cache/documents:/output"
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- write files inside Docker to /output/...
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- emit the host-visible path in MEDIA:, for example:
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- local uses faster-whisper on the machine running Hermes — no API key required
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- groq uses Groq Whisper and requires GROQ_API_KEY
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- openai uses OpenAI Whisper and requires VOICE_TOOLS_OPENAI_KEY
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- OpenAI and ElevenLabs produce Opus natively — no extra setup needed
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Edge TTS (the default free provider) outputs MP3 and requires ffmpeg to convert to Opus:
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- slash commands
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- replies to one of the bot's messages
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- @botusername mentions
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- matches for one of your configured regex wake words in telegram.mention_patterns
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Use telegram.ignored_threads to keep Hermes silent in specific Telegram forum topics, even when the group would otherwise allow free responses or mention-triggered replies
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- If telegram.require_mention is left unset or false, Hermes keeps the previous open-group behavior and responds to normal group messages it can see
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- "^\\s*chompy\\b"
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Patterns use Python regular expressions
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Matching is case-insensitive
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Patterns are checked against both text messages and media captions
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Invalid regex patterns are ignored with a warning in the gateway logs rather than crashing the bot
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- If you want a pattern to match only at the start of a message, anchor it with ^
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Topic "Website" — work on your production web service
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Topic "Research" — literature review and paper exploration
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Topic "General" — miscellaneous tasks and quick questions
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- chat_id: 123456789 # Your Telegram user ID
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- name: General
  - Sources: [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]]
- name: Website
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- name: Research
  - Sources: [[entities/telegram-setup|Telegram Setup]], [[entities/telegram-setup|Telegram Setup]]
- Engineering topic → auto-loads the software-development skill
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Research topic → auto-loads the arxiv skill
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- General topic → no skill, general-purpose assistant
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- chat_id: -1001234567890 # Supergroup ID
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- name: Engineering
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Bot API 9.4 (Feb 2026): Private Chat Topics — bots can create forum topics in 1-on-1 DM chats via createForumTopic. See Private Chat Topics above.
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Privacy policy: Telegram now requires bots to have a privacy policy. Set one via BotFather with /setprivacy_policy, or Telegram may auto-generate a placeholder. This is particularly important if your bot is public-facing.
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Message streaming: Bot API 9.x added support for streaming long responses, which can improve perceived latency for lengthy agent replies.
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- "149.154.167.220"
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- 👀 when the bot starts processing your message
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- ✅ when the response is delivered successfully
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- ❌ if an error occurs during processing
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Message in topic 42 inside group -1001234567890 → uses topic 42's prompt
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Message in topic 99 (no explicit entry) → falls back to group -1001234567890's prompt
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Message in a group with no entry → no channel prompt applied
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- How to disable privacy mode
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Step 4: Find Your User ID](#step-4-find-your-user-id)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Step 5: Configure Hermes](#step-5-configure-hermes)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Sending Generated Files from Docker-backed Terminals](#sending-generated-files-from-docker-backed-terminals)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Webhook Mode](#webhook-mode)[](#configuration)[](#cloud-deployment-example-flyio)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Cloud deployment example (Fly.io)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Proxy Support](#proxy-support)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Voice Messages](#voice-messages)[](#incoming-voice-speech-to-text)[](#outgoing-voice-text-to-speech)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Incoming Voice (Speech-to-Text)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Outgoing Voice (Text-to-Speech)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Group Chat Usage](#group-chat-usage)[](#example-group-trigger-configuration)[](#notes-on-mention_patterns)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Example group trigger configuration
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Notes on mention_patterns
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Private Chat Topics (Bot API 9.4)](#private-chat-topics-bot-api-94)[](#use-case)[](#configuration-1)[](#how-it-works)[](#skill-binding)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Skill binding
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Group Forum Topic Skill Binding](#group-forum-topic-skill-binding)[](#use-case-1)[](#configuration-2)[](#how-it-works-1)[](#differences-from-dm-topics)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Differences from DM Topics
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Recent Bot API Features](#recent-bot-api-features)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [DNS-over-HTTPS Fallback IPs](#dns-over-https-fallback-ips)[](#how-it-works-2)[](#configuration-3)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Proxy Support](#proxy-support-1)[](#supported-variables)[](#configuration-4)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- Supported variables
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Message Reactions](#message-reactions)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [Exec Approval](#exec-approval)
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- [[[entity.security|Security]]](#[[entity.security|Security]])
  - Sources: [[entities/telegram-setup|Telegram Setup]]
- In-progress terminal commands are killed immediately (SIGTERM, then SIGKILL after 1s)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Tool calls are cancelled — only the currently-executing one runs, the rest are skipped
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Multiple messages are combined — messages sent during interruption are joined into one prompt
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- /stop command — interrupts without queuing a follow-up message
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Isolated session — the background agent has its own session with its own conversation history. It has no knowledge of your current chat context and receives only the prompt you provide.
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Same configuration — inherits your model, provider, toolsets, reasoning settings, and provider routing from the current gateway setup.
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Non-blocking — your main chat stays fully interactive. Send messages, run other commands, or start more background tasks while it works.
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Result delivery — when the task finishes, the result is sent back to the same chat or channel where you issued the command, prefixed with "✅ Background task complete". If it fails, you'll see "❌ Background task failed" with the error.
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Server monitoring — "/background Check the health of all services and alert me if anything is down"
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Long builds — "/background Build and deploy the staging environment" while you continue chatting
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Research tasks — "/background Research competitor pricing and summarize in a table"
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- File operations — "/background Organize the photos in ~/Downloads by date into folders"
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- PATH — your full shell PATH at install time, with the venv bin/ and node_modules/.bin prepended. This ensures user-installed tools (Node.js, ffmpeg, etc.) are available to gateway subprocesses like the WhatsApp bridge.
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- VIRTUAL_ENV — points to the Python virtualenv so tools can resolve packages correctly.
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- HERMES_HOME — scopes the gateway to your Hermes installation.
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Slack Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- WhatsApp Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Signal Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- SMS Setup (Twilio)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Email Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Home Assistant Integration
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Mattermost Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Matrix Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- DingTalk Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Feishu/Lark Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- WeCom Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- WeCom Callback Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Weixin Setup (WeChat)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- BlueBubbles Setup (iMessage)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- QQBot Setup
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Open WebUI + API Server
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Session Persistence
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Reset Policies
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- [[[entity.security|Security]]](#[[entity.security|Security]])[](#dm-pairing-alternative-to-allowlists)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- DM Pairing (Alternative to Allowlists)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- [Interrupting the Agent](#interrupting-the-agent)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- [Tool Progress Notifications](#tool-progress-notifications)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- [Background Sessions](#background-sessions)[](#how-it-works)[](#background-process-notifications)[](#use-cases)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Background Process Notifications
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- [Service Management](#service-management)[](#linux-systemd)[](#macos-launchd)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- Linux (systemd)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- macOS (launchd)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- [Platform-Specific Toolsets](#platform-specific-toolsets)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]]
- [Next Steps](#next-steps)
  - Sources: [[entities/messaging-gateway|Messaging Gateway]], [[entities/quickstart|Quickstart]]
- Mode**: Behavior
  - Sources: [[entities/security|Security]]
- manual** (default)**: Always prompt the user for approval on dangerous commands
  - Sources: [[entities/security|Security]]
- smart****: Use an auxiliary LLM to assess risk. Low-risk commands (e.g., `python -c "print('hello')"`) are auto-approved. Genuinely dangerous commands are auto-denied. Uncertain cases escalate to a manual prompt.
  - Sources: [[entities/security|Security]]
- off****: Disable all approval checks — equivalent to running with `--yolo`. All commands execute without prompts.
  - Sources: [[entities/security|Security]]
- Pattern**: Description
  - Sources: [[entities/security|Security]]
- `rm -r` / `rm --recursive`**: Recursive delete
  - Sources: [[entities/security|Security]]
- `rm ... /`**: Delete in root path
  - Sources: [[entities/security|Security]]
- `chmod 777/666` / `o+w` / `a+w`**: World/other-writable permissions
  - Sources: [[entities/security|Security]]
- `chmod --recursive` with unsafe perms**: Recursive world/other-writable (long flag)
  - Sources: [[entities/security|Security]]
- `chown -R root` / `chown --recursive root`**: Recursive chown to root
  - Sources: [[entities/security|Security]]
- `mkfs`**: Format filesystem
  - Sources: [[entities/security|Security]]
- `dd if=`**: Disk copy
  - Sources: [[entities/security|Security]]
- `> /dev/sd`**: Write to block device
  - Sources: [[entities/security|Security]]
- `DROP TABLE/DATABASE`**: SQL DROP
  - Sources: [[entities/security|Security]]
- `DELETE FROM` (without WHERE)**: SQL DELETE without WHERE
  - Sources: [[entities/security|Security]]
- `TRUNCATE TABLE`**: SQL TRUNCATE
  - Sources: [[entities/security|Security]]
- `> /etc/`**: Overwrite system config
  - Sources: [[entities/security|Security]]
- `systemctl stop/disable/mask`**: Stop/disable system services
  - Sources: [[entities/security|Security]]
- `kill -9 -1`**: Kill all processes
  - Sources: [[entities/security|Security]]
- `pkill -9`**: Force kill processes
  - Sources: [[entities/security|Security]]
- Fork bomb patterns**: Fork bombs
  - Sources: [[entities/security|Security]]
- `bash -c` / `sh -c` / `zsh -c` / `ksh -c`**: Shell command execution via `-c` flag (including combined flags like `-lc`)
  - Sources: [[entities/security|Security]]
- `python -e` / `perl -e` / `ruby -e` / `node -c`**: Script execution via `-e`/`-c` flag
  - Sources: [[entities/security|Security]]
- `curl ...**: sh` / `wget ...
  - Sources: [[entities/security|Security]]
- `bash <(curl ...)` / `sh <(wget ...)`**: Execute remote script via process substitution
  - Sources: [[entities/security|Security]]
- `tee` to `/etc/`, `~/.ssh/`, `~/.hermes/.env`**: Overwrite sensitive file via tee
  - Sources: [[entities/security|Security]]
- `>` / `>>` to `/etc/`, `~/.ssh/`, `~/.hermes/.env`**: Overwrite sensitive file via redirection
  - Sources: [[entities/security|Security]]
- `xargs rm`**: xargs with rm
  - Sources: [[entities/security|Security]]
- `find -exec rm` / `find -delete`**: Find with destructive actions
  - Sources: [[entities/security|Security]]
- `cp`/`mv`/`install` to `/etc/`**: Copy/move file into system config
  - Sources: [[entities/security|Security]]
- `sed -i` / `sed --in-place` on `/etc/`**: In-place edit of system config
  - Sources: [[entities/security|Security]]
- `pkill`/`killall` hermes/gateway**: Self-termination prevention
  - Sources: [[entities/security|Security]]
- `gateway run` with `&`/`disown`/`nohup`/`setsid`**: Prevents starting gateway outside service manager
  - Sources: [[entities/security|Security]]
- once** — allow this single execution
  - Sources: [[entities/security|Security]]
- session** — allow this pattern for the rest of the session
  - Sources: [[entities/security|Security]]
- always** — add to permanent allowlist (saved to `config.yaml`)
  - Sources: [[entities/security|Security]]
- deny** (default) — block the command
  - Sources: [[entities/security|Security]]
- Reply **yes**, **y**, **approve**, **ok**, or **go** to approve
  - Sources: [[entities/security|Security]]
- Reply **no**, **n**, **deny**, or **cancel** to deny
  - Sources: [[entities/security|Security]]
- `pair` is the default. Unauthorized DMs get a pairing code reply.
  - Sources: [[entities/security|Security]]
- `ignore` silently drops unauthorized DMs.
  - Sources: [[entities/security|Security]]
- Platform sections override the global default, so you can keep pairing on Telegram while keeping WhatsApp silent.
  - Sources: [[entities/security|Security]]
- Feature**: Details
  - Sources: [[entities/security|Security]]
- Code format**: 8-char from 32-char unambiguous alphabet (no 0/O/1/I)
  - Sources: [[entities/security|Security]]
- Randomness**: Cryptographic (`secrets.choice()`)
  - Sources: [[entities/security|Security]]
- Code TTL**: 1 hour expiry
  - Sources: [[entities/security|Security]]
- Rate limiting**: 1 request per user per 10 minutes
  - Sources: [[entities/security|Security]]
- Pending limit**: Max 3 pending codes per platform
  - Sources: [[entities/security|Security]]
- Lockout**: 5 failed approval attempts → 1-hour lockout
  - Sources: [[entities/security|Security]]
- File security**: `chmod 0600` on all pairing data files
  - Sources: [[entities/security|Security]]
- Logging**: Codes are never logged to stdout
  - Sources: [[entities/security|Security]]
- `{platform}-pending.json` — pending pairing requests
  - Sources: [[entities/security|Security]]
- `{platform}-approved.json` — approved users
  - Sources: [[entities/security|Security]]
- `_rate_limits.json` — rate limit and lockout tracking
  - Sources: [[entities/security|Security]]
- Persistent mode** (`container_persistent: true`): Bind-mounts `/workspace` and `/root` from `~/.hermes/sandboxes/docker/<task_id>/`
  - Sources: [[entities/security|Security]]
- Ephemeral mode** (`container_persistent: false`): Uses tmpfs for workspace — everything is lost on cleanup
  - Sources: [[entities/security|Security]]
- Backend**, **Isolation**, **Dangerous Cmd Check**, **Best For**
  - Sources: [[entities/security|Security]]
- Backend**: **local**, **Isolation**: None — runs on host, **Dangerous Cmd Check**: ✅ Yes, **Best For**: Development, trusted users
  - Sources: [[entities/security|Security]]
- Backend**: **ssh**, **Isolation**: Remote machine, **Dangerous Cmd Check**: ✅ Yes, **Best For**: Running on a separate server
  - Sources: [[entities/security|Security]]
- Backend**: **docker**, **Isolation**: Container, **Dangerous Cmd Check**: ❌ Skipped (container is boundary), **Best For**: Production gateway
  - Sources: [[entities/security|Security]]
- Backend**: **singularity**, **Isolation**: Container, **Dangerous Cmd Check**: ❌ Skipped, **Best For**: HPC environments
  - Sources: [[entities/security|Security]]
- Backend**: **modal**, **Isolation**: Cloud sandbox, **Dangerous Cmd Check**: ❌ Skipped, **Best For**: Scalable cloud isolation
  - Sources: [[entities/security|Security]]
- Backend**: **daytona**, **Isolation**: Cloud sandbox, **Dangerous Cmd Check**: ❌ Skipped, **Best For**: Persistent cloud workspaces
  - Sources: [[entities/security|Security]]
- name: TENOR_API_KEY
  - Sources: [[entities/security|Security]], [[entities/features-skills|Features: Skills]]
- MY_CUSTOM_KEY
  - Sources: [[entities/security|Security]]
- ANOTHER_TOKEN
  - Sources: [[entities/security|Security]]
- path: google_token.json
  - Sources: [[entities/security|Security]]
- path: google_client_secret.json
  - Sources: [[entities/security|Security]]
- Docker**: Read-only bind mounts (`-v host:container:ro`)
  - Sources: [[entities/security|Security]]
- Modal**: Mounted at sandbox creation + synced before each command (handles mid-session OAuth setup)
  - Sources: [[entities/security|Security]]
- Local**: No action needed (files already accessible)
  - Sources: [[entities/security|Security]]
- google_token.json
  - Sources: [[entities/security|Security]]
- my_custom_oauth_token.json
  - Sources: [[entities/security|Security]]
- Sandbox**, **Default Filter**, **Passthrough Override**
  - Sources: [[entities/security|Security]]
- Sandbox**: **execute\_code**, **Default Filter**: Blocks vars containing `KEY`, `TOKEN`, `SECRET`, `PASSWORD`, `CREDENTIAL`, `PASSWD`, `AUTH` in name; only allows safe-prefix vars through, **Passthrough Override**: ✅ Passthrough vars bypass both checks
  - Sources: [[entities/security|Security]]
- Sandbox**: **terminal** (local), **Default Filter**: Blocks explicit Hermes infrastructure vars (provider keys, gateway tokens, tool API keys), **Passthrough Override**: ✅ Passthrough vars bypass the blocklist
  - Sources: [[entities/security|Security]]
- Sandbox**: **terminal** (Docker), **Default Filter**: No host env vars by default, **Passthrough Override**: ✅ Passthrough vars + `docker_forward_env` forwarded via `-e`
  - Sources: [[entities/security|Security]]
- Sandbox**: **terminal** (Modal), **Default Filter**: No host env/files by default, **Passthrough Override**: ✅ Credential files mounted; env passthrough via sync
  - Sources: [[entities/security|Security]]
- Sandbox**: **MCP**, **Default Filter**: Blocks everything except safe system vars + explicitly configured `env`, **Passthrough Override**: ❌ Not affected by passthrough (use MCP `env` config instead)
  - Sources: [[entities/security|Security]]
- The passthrough only affects vars you or your skills explicitly declare — the default security posture is unchanged for arbitrary LLM-generated code
  - Sources: [[entities/security|Security]]
- Credential files are mounted **read-only** into Docker containers
  - Sources: [[entities/security|Security]]
- Skills Guard scans skill content for suspicious env access patterns before installation
  - Sources: [[entities/security|Security]]
- Missing/unset vars are never registered (you can't leak what doesn't exist)
  - Sources: [[entities/security|Security]]
- Hermes infrastructure secrets (provider API keys, gateway tokens) should never be added to `env_passthrough` — they have dedicated mechanisms
  - Sources: [[entities/security|Security]]
- GitHub PATs (`ghp_...`)
  - Sources: [[entities/security|Security]]
- OpenAI-style keys (`sk-...`)
  - Sources: [[entities/security|Security]]
- Bearer tokens
  - Sources: [[entities/security|Security]]
- `token=`, `key=`, `API_KEY=`, `password=`, `secret=` parameters
  - Sources: [[entities/security|Security]]
- "*.internal.company.com"
  - Sources: [[entities/security|Security]]
- "admin.example.com"
  - Sources: [[entities/security|Security]]
- "/etc/hermes/blocked-sites.txt"
  - Sources: [[entities/security|Security]]
- Private networks** (RFC 1918): `10.0.0.0/8`, `172.16.0.0/12`, `192.168.0.0/16`
  - Sources: [[entities/security|Security]]
- Loopback**: `127.0.0.0/8`, `::1`
  - Sources: [[entities/security|Security]]
- Link-local**: `169.254.0.0/16` (includes cloud metadata at `169.254.169.254`)
  - Sources: [[entities/security|Security]]
- CGNAT / shared address space** (RFC 6598): `100.64.0.0/10` (Tailscale, WireGuard VPNs)
  - Sources: [[entities/security|Security]]
- Cloud metadata hostnames**: `metadata.google.internal`, `metadata.goog`
  - Sources: [[entities/security|Security]]
- Reserved, multicast, and unspecified addresses**
  - Sources: [[entities/security|Security]]
- Homograph URL spoofing (internationalized domain attacks)
  - Sources: [[entities/security|Security]]
- Pipe-to-interpreter patterns (`curl | bash`, `wget | sh`)
  - Sources: [[entities/security|Security]]
- Terminal injection attacks
  - Sources: [[entities/security|Security]]
- Instructions to ignore/disregard prior instructions
  - Sources: [[entities/security|Security]]
- Hidden HTML comments with suspicious keywords
  - Sources: [[entities/security|Security]]
- Attempts to read secrets (`.env`, `credentials`, `.netrc`)
  - Sources: [[entities/security|Security]]
- Credential exfiltration via `curl`
  - Sources: [[entities/security|Security]]
- Invisible Unicode characters (zero-width spaces, bidirectional overrides)
  - Sources: [[entities/security|Security]]
- File**, **Purpose**, **Discovery**
  - Sources: [[entities/features-context-files|Features: Context Files]]
- File**: **.hermes.md** / **HERMES.md**, **Purpose**: Project instructions (highest priority), **Discovery**: Walks to git root
  - Sources: [[entities/features-context-files|Features: Context Files]]
- File**: **AGENTS.md**, **Purpose**: Project instructions, conventions, architecture, **Discovery**: CWD at startup + subdirectories progressively
  - Sources: [[entities/features-context-files|Features: Context Files]]
- File**: **CLAUDE.md**, **Purpose**: Claude Code context files (also detected), **Discovery**: CWD at startup + subdirectories progressively
  - Sources: [[entities/features-context-files|Features: Context Files]]
- File**: **SOUL.md**, **Purpose**: Global personality and tone customization for this Hermes instance, **Discovery**: `HERMES_HOME/SOUL.md` only
  - Sources: [[entities/features-context-files|Features: Context Files]]
- File**: **.cursorrules**, **Purpose**: Cursor IDE coding conventions, **Discovery**: CWD only
  - Sources: [[entities/features-context-files|Features: Context Files]]
- File**: **.cursor/rules/\*.mdc**, **Purpose**: Cursor IDE rule modules, **Discovery**: CWD only
  - Sources: [[entities/features-context-files|Features: Context Files]]
- No system prompt bloat** — subdirectory hints only appear when needed
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Prompt cache preservation** — the system prompt stays stable across turns
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Frontend: Next.js 14 with App Router in `/frontend`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Backend: FastAPI in `/backend`, uses SQLAlchemy ORM
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Database: PostgreSQL 16
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Deployment: Docker Compose on a Hetzner VPS
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Use TypeScript strict mode for all frontend code
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Python code follows PEP 8, use type hints everywhere
  - Sources: [[entities/features-context-files|Features: Context Files]]
- All API endpoints return JSON with `{data, error, meta}` shape
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Tests go in `__tests__/` directories (frontend) or `tests/` (backend)
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Never modify migration files directly — use Alembic commands
  - Sources: [[entities/features-context-files|Features: Context Files]]
- The `.env.local` file has real API keys, don't commit it
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Frontend port is 3000, backend is 8000, DB is 5432
  - Sources: [[entities/features-context-files|Features: Context Files]]
- `~/.hermes/SOUL.md`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- or `$HERMES_HOME/SOUL.md` if you run Hermes with a custom home directory
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Hermes seeds a default `SOUL.md` automatically if one does not exist yet
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Hermes loads `SOUL.md` only from `HERMES_HOME`
  - Sources: [[entities/features-context-files|Features: Context Files]], [[entities/features-personality|Features: Personality]]
- Hermes does not probe the working directory for `SOUL.md`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- If the file is empty, nothing from `SOUL.md` is added to the prompt
  - Sources: [[entities/features-context-files|Features: Context Files]]
- If the file has content, the content is injected verbatim after scanning and truncation
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Instruction override attempts**: "ignore previous instructions", "disregard your rules"
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Deception patterns**: "do not tell the user"
  - Sources: [[entities/features-context-files|Features: Context Files]]
- System prompt overrides**: "system prompt override"
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Hidden HTML comments**: `<!-- ignore instructions -->`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Hidden div elements**: `<div style="display:none">`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Credential exfiltration**: `curl ... $API_KEY`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Secret file access**: `cat .env`, `cat credentials`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Invisible characters**: zero-width spaces, bidirectional overrides, word joiners
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Limit**: Value
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Max chars per file**: 20,000 (~7,000 tokens)
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Head truncation ratio**: 70%
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Tail truncation ratio**: 20%
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Truncation marker**: 10% (shows char counts and suggests using file tools)
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Use `pnpm` not `npm` for package management
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Components go in `src/components/`, pages in `src/app/`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Use Tailwind CSS, never inline styles
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Run tests with `pnpm test`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Use `poetry` for dependency management
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Run the dev server with `poetry run uvicorn main:app --reload`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- All endpoints need OpenAPI docstrings
  - Sources: [[entities/features-context-files|Features: Context Files]]
- Database models are in `models/`, schemas in `schemas/`
  - Sources: [[entities/features-context-files|Features: Context Files]]
- `SOUL.md` — a durable persona file that lives in `HERMES_HOME` and serves as the agent's identity (slot #1 in the system prompt)
  - Sources: [[entities/features-personality|Features: Personality]]
- built-in or custom `/personality` presets — session-level system-prompt overlays
  - Sources: [[entities/features-personality|Features: Personality]]
- SOUL.md is the agent's primary identity.** It occupies slot #1 in the system prompt, replacing the hardcoded default identity.
  - Sources: [[entities/features-personality|Features: Personality]]
- Hermes creates a starter `SOUL.md` automatically if one does not exist yet
  - Sources: [[entities/features-personality|Features: Personality]]
- Existing user `SOUL.md` files are never overwritten
  - Sources: [[entities/features-personality|Features: Personality]]
- Hermes does not look in the current working directory for `SOUL.md`
  - Sources: [[entities/features-personality|Features: Personality]]
- If `SOUL.md` exists but is empty, or cannot be loaded, Hermes falls back to a built-in default identity
  - Sources: [[entities/features-personality|Features: Personality]]
- If `SOUL.md` has content, that content is injected verbatim after security scanning and truncation
  - Sources: [[entities/features-personality|Features: Personality]]
- SOUL.md is **not** duplicated in the context files section — it appears only once, as the identity
  - Sources: [[entities/features-personality|Features: Personality]]
- "Edit `~/.hermes/SOUL.md` to change Hermes' default personality."
  - Sources: [[entities/features-personality|Features: Personality]]
- communication style
  - Sources: [[entities/features-personality|Features: Personality]]
- level of directness
  - Sources: [[entities/features-personality|Features: Personality]]
- default interaction style
  - Sources: [[entities/features-personality|Features: Personality]]
- what to avoid stylistically
  - Sources: [[entities/features-personality|Features: Personality]]
- how Hermes should handle uncertainty, disagreement, or ambiguity
  - Sources: [[entities/features-personality|Features: Personality]]
- one-off project instructions
  - Sources: [[entities/features-personality|Features: Personality]]
- file paths
  - Sources: [[entities/features-personality|Features: Personality]]
- repo conventions
  - Sources: [[entities/features-personality|Features: Personality]]
- temporary workflow details
  - Sources: [[entities/features-personality|Features: Personality]]
- stable across contexts
  - Sources: [[entities/features-personality|Features: Personality]]
- broad enough to apply in many conversations
  - Sources: [[entities/features-personality|Features: Personality]]
- specific enough to materially shape the voice
  - Sources: [[entities/features-personality|Features: Personality]]
- focused on communication and identity, not task-specific instructions
  - Sources: [[entities/features-personality|Features: Personality]]
- Be direct without being cold
  - Sources: [[entities/features-personality|Features: Personality]]
- Prefer substance over filler
  - Sources: [[entities/features-personality|Features: Personality]]
- Push back when something is a bad idea
  - Sources: [[entities/features-personality|Features: Personality]]
- Admit uncertainty plainly
  - Sources: [[entities/features-personality|Features: Personality]]
- Keep explanations compact unless depth is useful
  - Sources: [[entities/features-personality|Features: Personality]]
- Sycophancy
  - Sources: [[entities/features-personality|Features: Personality]]
- Hype language
  - Sources: [[entities/features-personality|Features: Personality]]
- Repeating the user's framing if it's wrong
  - Sources: [[entities/features-personality|Features: Personality]]
- Overexplaining obvious things
  - Sources: [[entities/features-personality|Features: Personality]]
- Prefer simple systems over clever systems
  - Sources: [[entities/features-personality|Features: Personality]]
- Care about operational reality, not idealized architecture
  - Sources: [[entities/features-personality|Features: Personality]]
- Treat edge cases as part of the design, not cleanup
  - Sources: [[entities/features-personality|Features: Personality]]
- prompt-injection scanning
  - Sources: [[entities/features-personality|Features: Personality]]
- truncation if it is too large
  - Sources: [[entities/features-personality|Features: Personality]]
- communication defaults
  - Sources: [[entities/features-personality|Features: Personality]]
- personality-level behavior
  - Sources: [[entities/features-personality|Features: Personality]]
- project architecture
  - Sources: [[entities/features-personality|Features: Personality]]
- coding conventions
  - Sources: [[entities/features-personality|Features: Personality]]
- tool preferences
  - Sources: [[entities/features-personality|Features: Personality]]
- repo-specific workflows
  - Sources: [[entities/features-personality|Features: Personality]]
- commands, ports, paths, deployment notes
  - Sources: [[entities/features-personality|Features: Personality]]
- if it should follow you everywhere, it belongs in `SOUL.md`
  - Sources: [[entities/features-personality|Features: Personality]]
- if it belongs to a project, it belongs in `AGENTS.md`
  - Sources: [[entities/features-personality|Features: Personality]]
- `SOUL.md` = baseline voice
  - Sources: [[entities/features-personality|Features: Personality]]
- `/personality` = temporary mode switch
  - Sources: [[entities/features-personality|Features: Personality]]
- keep a pragmatic default SOUL, then use `/personality teacher` for a tutoring conversation
  - Sources: [[entities/features-personality|Features: Personality]]
- keep a concise SOUL, then use `/personality creative` for brainstorming
  - Sources: [[entities/features-personality|Features: Personality]]
- Name**: Description
  - Sources: [[entities/features-personality|Features: Personality]]
- helpful****: Friendly, general-purpose assistant
  - Sources: [[entities/features-personality|Features: Personality]]
- concise****: Brief, to-the-point responses
  - Sources: [[entities/features-personality|Features: Personality]]
- technical****: Detailed, accurate technical expert
  - Sources: [[entities/features-personality|Features: Personality]]
- creative****: Innovative, outside-the-box thinking
  - Sources: [[entities/features-personality|Features: Personality]]
- teacher****: Patient educator with clear examples
  - Sources: [[entities/features-personality|Features: Personality]]
- kawaii****: Cute expressions, sparkles, and enthusiasm ★
  - Sources: [[entities/features-personality|Features: Personality]]
- catgirl****: Neko-chan with cat-like expressions, nya~
  - Sources: [[entities/features-personality|Features: Personality]]
- pirate****: Captain Hermes, tech-savvy buccaneer
  - Sources: [[entities/features-personality|Features: Personality]]
- shakespeare****: Bardic prose with dramatic flair
  - Sources: [[entities/features-personality|Features: Personality]]
- surfer****: Totally chill bro vibes
  - Sources: [[entities/features-personality|Features: Personality]]
- noir****: Hard-boiled detective narration
  - Sources: [[entities/features-personality|Features: Personality]]
- uwu****: Maximum cute with uwu-speak
  - Sources: [[entities/features-personality|Features: Personality]]
- philosopher****: Deep contemplation on every query
  - Sources: [[entities/features-personality|Features: Personality]]
- hype****: MAXIMUM ENERGY AND ENTHUSIASM!!!
  - Sources: [[entities/features-personality|Features: Personality]]
- a stable voice
  - Sources: [[entities/features-personality|Features: Personality]]
- project-specific behavior where it belongs
  - Sources: [[entities/features-personality|Features: Personality]]
- temporary control when needed
  - Sources: [[entities/features-personality|Features: Personality]]
- [Context Files](/docs/user-guide/features/context-files)
  - Sources: [[entities/features-personality|Features: Personality]], [[entities/learning-path|Learning Path]]
- [Configuration](/docs/user-guide/configuration)
  - Sources: [[entities/features-personality|Features: Personality]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]]
- [Tips & Best Practices](/docs/guides/tips)
  - Sources: [[entities/features-personality|Features: Personality]]
- [SOUL.md Guide](/docs/guides/use-soul-with-hermes)
  - Sources: [[entities/features-personality|Features: Personality]]
- `SOUL.md`, `agent.system_prompt`, and `/personality` affect how Hermes speaks
  - Sources: [[entities/features-personality|Features: Personality]]
- `display.skin` and `/skin` affect how Hermes looks in the terminal
  - Sources: [[entities/features-personality|Features: Personality]]
- Feature**, **Platform**, **Description**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Feature**: **Interactive Voice**, **Platform**: CLI, **Description**: Press Ctrl+B to record, agent auto-detects silence and responds
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Feature**: **Auto Voice Reply**, **Platform**: Telegram, Discord, **Description**: Agent sends spoken audio alongside text responses
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Feature**: **Voice Channel**, **Platform**: Discord, **Description**: Bot joins VC, listens to users speaking, speaks replies back
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Extra**, **Packages**, **Required For**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Extra**: `voice`, **Packages**: `sounddevice`, `numpy`, **Required For**: CLI voice mode
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Extra**: `messaging`, **Packages**: `discord.py[voice]`, `python-telegram-bot`, `aiohttp`, **Required For**: Discord & Telegram bots
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Extra**: `tts-premium`, **Packages**: `elevenlabs`, **Required For**: ElevenLabs TTS provider
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Dependency**, **Purpose**, **Required For**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Dependency**: **PortAudio**, **Purpose**: Microphone input and audio playback, **Required For**: CLI voice mode
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Dependency**: **ffmpeg**, **Purpose**: Audio format conversion (MP3 → Opus, PCM → WAV), **Required For**: All platforms
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Dependency**: **Opus**, **Purpose**: Discord voice codec, **Required For**: Discord voice channels
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Dependency**: **espeak-ng**, **Purpose**: Phonemizer backend, **Required For**: Local NeuTTS provider
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- [Telegram Setup Guide](/docs/user-guide/messaging/telegram)
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- [Discord Setup Guide](/docs/user-guide/messaging/discord)
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Mode**, **How to Talk**, **Mention Required**, **Setup**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Mode**: **Direct Message (DM)**, **How to Talk**: Open the bot's profile → "Message", **Mention Required**: No, **Setup**: Works immediately
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Mode**: **Server Channel**, **How to Talk**: Type in a text channel where the bot is present, **Mention Required**: Yes (`@botname`), **Setup**: Bot must be invited to the server
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Mode**, **Command**, **Behavior**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Mode**: `off`, **Command**: `/voice off`, **Behavior**: Text only (default)
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Mode**: `voice_only`, **Command**: `/voice on`, **Behavior**: Speaks reply only when you send a voice message
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Mode**: `all`, **Command**: `/voice tts`, **Behavior**: Speaks reply to every message
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Platform**, **Format**, **Notes**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Platform**: **Telegram**, **Format**: Voice bubble (Opus/OGG), **Notes**: Plays inline in chat. ffmpeg converts MP3 → Opus if needed
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Platform**: **Discord**, **Format**: Native voice bubble (Opus/OGG), **Notes**: Plays inline like a user voice message. Falls back to file attachment if voice bubble API fails
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Permission**, **Purpose**, **Required**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Permission**: **Connect**, **Purpose**: Join voice channels, **Required**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Permission**: **Speak**, **Purpose**: Play TTS audio in voice channels, **Required**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Permission**: **Use Voice Activity**, **Purpose**: Detect when users are speaking, **Required**: Recommended
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Level**, **Integer**, **What's Included**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Level**: Text only, **Integer**: `274878286912`, **What's Included**: View Channels, Send Messages, Read History, Embeds, Attachments, Threads, Reactions
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Level**: Text + Voice, **Integer**: `274881432640`, **What's Included**: All above + Connect, Speak
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Intent**: Purpose
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Presence Intent****: Detect user online/offline status
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Server Members Intent****: Map voice SSRC identifiers to Discord user IDs
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Message Content Intent****: Read text message content in channels
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- macOS:** `/opt/homebrew/lib/libopus.dylib`
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Linux:** `libopus.so.0`
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Transcripts appear in the text channel: `[Voice] @user: what you said`
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Agent responses are sent as text in the channel AND spoken in the VC
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- The text channel is the one where `/voice join` was issued
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Provider**, **Model**, **Speed**, **Quality**, **Cost**, **API Key**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **Local**, **Model**: `base`, **Speed**: Fast (depends on CPU/GPU), **Quality**: Good, **Cost**: Free, **API Key**: No
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **Local**, **Model**: `small`, **Speed**: Medium, **Quality**: Better, **Cost**: Free, **API Key**: No
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **Local**, **Model**: `large-v3`, **Speed**: Slow, **Quality**: Best, **Cost**: Free, **API Key**: No
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **Groq**, **Model**: `whisper-large-v3-turbo`, **Speed**: Very fast (~0.5s), **Quality**: Good, **Cost**: Free tier, **API Key**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **Groq**, **Model**: `whisper-large-v3`, **Speed**: Fast (~1s), **Quality**: Better, **Cost**: Free tier, **API Key**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **OpenAI**, **Model**: `whisper-1`, **Speed**: Fast (~1s), **Quality**: Good, **Cost**: Paid, **API Key**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **OpenAI**, **Model**: `gpt-4o-transcribe`, **Speed**: Medium (~2s), **Quality**: Best, **Cost**: Paid, **API Key**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**, **Quality**, **Cost**, **Latency**, **Key Required**
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **Edge TTS**, **Quality**: Good, **Cost**: Free, **Latency**: ~1s, **Key Required**: No
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **ElevenLabs**, **Quality**: Excellent, **Cost**: Paid, **Latency**: ~2s, **Key Required**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **OpenAI TTS**, **Quality**: Good, **Cost**: Paid, **Latency**: ~1.5s, **Key Required**: Yes
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Provider**: **NeuTTS**, **Quality**: Good, **Cost**: Free, **Latency**: Depends on CPU/GPU, **Key Required**: No
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Check your Discord user ID is in `DISCORD_ALLOWED_USERS`
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Make sure you're not muted in Discord
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- The bot needs a SPEAKING event from Discord before it can map your audio — start speaking within a few seconds of joining
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Verify STT is available: install `faster-whisper` (no key needed) or set `GROQ_API_KEY` / `VOICE_TOOLS_OPENAI_KEY`
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Check the LLM model is configured and accessible
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Review gateway logs: `tail -f ~/.hermes/logs/gateway.log`
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- TTS provider may be failing — check API key and quota
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Edge TTS (free, no key) is the default fallback
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Check logs for TTS errors
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Use a quieter environment
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Adjust `silence_threshold` in config (higher = less sensitive)
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Try a different STT model
  - Sources: [[entities/features-voice-mode|Features: Voice Mode]]
- Access to external tool ecosystems without writing a native Hermes tool first
  - Sources: [[entities/features-mcp|Features: MCP]]
- Local stdio servers and remote HTTP MCP servers in the same config
  - Sources: [[entities/features-mcp|Features: MCP]]
- Automatic tool discovery and registration at startup
  - Sources: [[entities/features-mcp|Features: MCP]]
- Utility wrappers for MCP resources and prompts when supported by the server
  - Sources: [[entities/features-mcp|Features: MCP]]
- Per-server filtering so you can expose only the MCP tools you actually want Hermes to see
  - Sources: [[entities/features-mcp|Features: MCP]]
- the server is installed locally
  - Sources: [[entities/features-mcp|Features: MCP]]
- you want low-latency access to local resources
  - Sources: [[entities/features-mcp|Features: MCP]]
- you are following MCP server docs that show `command`, `args`, and `env`
  - Sources: [[entities/features-mcp|Features: MCP]]
- the MCP server is hosted elsewhere
  - Sources: [[entities/features-mcp|Features: MCP]]
- your organization exposes internal MCP endpoints
  - Sources: [[entities/features-mcp|Features: MCP]]
- you do not want Hermes spawning a local subprocess for that integration
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**, **Type**, **Meaning**
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `command`, **Type**: string, **Meaning**: Executable for a stdio MCP server
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `args`, **Type**: list, **Meaning**: Arguments for the stdio server
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `env`, **Type**: mapping, **Meaning**: Environment variables passed to the stdio server
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `url`, **Type**: string, **Meaning**: HTTP MCP endpoint
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `headers`, **Type**: mapping, **Meaning**: HTTP headers for remote servers
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `timeout`, **Type**: number, **Meaning**: Tool call timeout
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `connect_timeout`, **Type**: number, **Meaning**: Initial connection timeout
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `enabled`, **Type**: bool, **Meaning**: If `false`, Hermes skips the server entirely
  - Sources: [[entities/features-mcp|Features: MCP]]
- Key**: `tools`, **Type**: mapping, **Meaning**: Per-server tool filtering and utility policy
  - Sources: [[entities/features-mcp|Features: MCP]]
- Server**, **MCP tool**, **Registered name**
  - Sources: [[entities/features-mcp|Features: MCP]]
- Server**: `filesystem`, **MCP tool**: `read_file`, **Registered name**: `mcp_filesystem_read_file`
  - Sources: [[entities/features-mcp|Features: MCP]]
- Server**: `github`, **MCP tool**: `create-issue`, **Registered name**: `mcp_github_create_issue`
  - Sources: [[entities/features-mcp|Features: MCP]]
- Server**: `my-api`, **MCP tool**: `query.data`, **Registered name**: `mcp_my_api_query_data`
  - Sources: [[entities/features-mcp|Features: MCP]]
- `list_resources`
  - Sources: [[entities/features-mcp|Features: MCP]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- `read_resource`
  - Sources: [[entities/features-mcp|Features: MCP]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- `list_prompts`
  - Sources: [[entities/features-mcp|Features: MCP]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- `get_prompt`
  - Sources: [[entities/features-mcp|Features: MCP]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- `mcp_github_list_resources`
  - Sources: [[entities/features-mcp|Features: MCP]]
- `mcp_github_get_prompt`
  - Sources: [[entities/features-mcp|Features: MCP]]
- Hermes only registers resource utilities if the MCP session actually supports resource operations
  - Sources: [[entities/features-mcp|Features: MCP]]
- Hermes only registers prompt utilities if the MCP session actually supports prompt operations
  - Sources: [[entities/features-mcp|Features: MCP]]
- `tools.resources: false` disables `list_resources` and `read_resource`
  - Sources: [[entities/features-mcp|Features: MCP]]
- `tools.prompts: false` disables `list_prompts` and `get_prompt`
  - Sources: [[entities/features-mcp|Features: MCP]]
- disable dangerous tools you do not want the model to see
  - Sources: [[entities/features-mcp|Features: MCP]]
- expose only a minimal whitelist for a sensitive server
  - Sources: [[entities/features-mcp|Features: MCP]]
- disable resource/prompt wrappers when you do not want that surface exposed
  - Sources: [[entities/features-mcp|Features: MCP]]
- the server failed to connect
  - Sources: [[entities/features-mcp|Features: MCP]]
- discovery failed
  - Sources: [[entities/features-mcp|Features: MCP]]
- your filter config excluded the tools
  - Sources: [[entities/features-mcp|Features: MCP]]
- the utility capability does not exist on that server
  - Sources: [[entities/features-mcp|Features: MCP]]
- the server is disabled with `enabled: false`
  - Sources: [[entities/features-mcp|Features: MCP]]
- You want Claude Code, Cursor, or another coding agent to send and read Telegram/Discord/Slack messages through Hermes
  - Sources: [[entities/features-mcp|Features: MCP]]
- You want a single MCP server that bridges to all of Hermes's connected messaging platforms at once
  - Sources: [[entities/features-mcp|Features: MCP]]
- You already have a running Hermes gateway with connected platforms
  - Sources: [[entities/features-mcp|Features: MCP]]
- Tool**: Description
  - Sources: [[entities/features-mcp|Features: MCP]]
- `conversations_list`**: List active messaging conversations. Filter by platform or search by name.
  - Sources: [[entities/features-mcp|Features: MCP]]
- `conversation_get`**: Get detailed info about one conversation by session key.
  - Sources: [[entities/features-mcp|Features: MCP]]
- `messages_read`**: Read recent message history for a conversation.
  - Sources: [[entities/features-mcp|Features: MCP]]
- `attachments_fetch`**: Extract non-text attachments (images, media) from a specific message.
  - Sources: [[entities/features-mcp|Features: MCP]]
- `events_poll`**: Poll for new conversation events since a cursor position.
  - Sources: [[entities/features-mcp|Features: MCP]]
- `events_wait`**: Long-poll / block until the next event arrives (near-real-time).
  - Sources: [[entities/features-mcp|Features: MCP]]
- `messages_send`**: Send a message through a platform (e.g. `telegram:123456`, `discord:#general`).
  - Sources: [[entities/features-mcp|Features: MCP]]
- `channels_list`**: List available messaging targets across all platforms.
  - Sources: [[entities/features-mcp|Features: MCP]]
- `permissions_list_open`**: List pending approval requests observed during this bridge session.
  - Sources: [[entities/features-mcp|Features: MCP]]
- `permissions_respond`**: Allow or deny a pending approval request.
  - Sources: [[entities/features-mcp|Features: MCP]]
- Stdio transport only (no HTTP MCP transport yet)
  - Sources: [[entities/features-mcp|Features: MCP]]
- Event polling at ~200ms intervals via mtime-optimized DB polling (skips work when files are unchanged)
  - Sources: [[entities/features-mcp|Features: MCP]]
- No `claude/channel` push notification protocol yet
  - Sources: [[entities/features-mcp|Features: MCP]]
- Text-only sends (no media/attachment sending through `messages_send`)
  - Sources: [[entities/features-mcp|Features: MCP]]
- [Use MCP with Hermes](/docs/guides/use-mcp-with-hermes)
  - Sources: [[entities/features-mcp|Features: MCP]], [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [CLI Commands](/docs/reference/cli-commands)
  - Sources: [[entities/features-mcp|Features: MCP]]
- [Slash Commands](/docs/reference/slash-commands)
  - Sources: [[entities/features-mcp|Features: MCP]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [FAQ](/docs/reference/faq)
  - Sources: [[entities/features-mcp|Features: MCP]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Bundled Skills Catalog](/docs/reference/skills-catalog)
  - Sources: [[entities/features-skills|Features: Skills]], [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Official Optional Skills Catalog](/docs/reference/optional-skills-catalog)
  - Sources: [[entities/features-skills|Features: Skills]]
- key: my.setting
  - Sources: [[entities/features-skills|Features: Skills]]
- Known failure modes and fixes
  - Sources: [[entities/features-skills|Features: Skills]]
- Value**: Matches
  - Sources: [[entities/features-skills|Features: Skills]]
- `macos`**: macOS (Darwin)
  - Sources: [[entities/features-skills|Features: Skills]]
- `linux`**: Linux
  - Sources: [[entities/features-skills|Features: Skills]]
- `windows`**: Windows
  - Sources: [[entities/features-skills|Features: Skills]]
- Field**: Behavior
  - Sources: [[entities/features-skills|Features: Skills]]
- `fallback_for_toolsets`**: Skill is **hidden** when the listed toolsets are available. Shown when they're missing.
  - Sources: [[entities/features-skills|Features: Skills]]
- `fallback_for_tools`**: Same, but checks individual tools instead of toolsets.
  - Sources: [[entities/features-skills|Features: Skills]]
- `requires_toolsets`**: Skill is **hidden** when the listed toolsets are unavailable. Shown when they're present.
  - Sources: [[entities/features-skills|Features: Skills]]
- `requires_tools`**: Same, but checks individual tools.
  - Sources: [[entities/features-skills|Features: Skills]]
- key: myplugin.path
  - Sources: [[entities/features-skills|Features: Skills]]
- ~/.agents/skills
  - Sources: [[entities/features-skills|Features: Skills]]
- /home/shared/team-skills
  - Sources: [[entities/features-skills|Features: Skills]]
- ${SKILLS_REPO}/skills
  - Sources: [[entities/features-skills|Features: Skills]]
- Read-only**: External dirs are only scanned for skill discovery. When the agent creates or edits a skill, it always writes to `~/.hermes/skills/`.
  - Sources: [[entities/features-skills|Features: Skills]]
- Local precedence**: If the same skill name exists in both the local dir and an external dir, the local version wins.
  - Sources: [[entities/features-skills|Features: Skills]]
- Full integration**: External skills appear in the system prompt index, `skills_list`, `skill_view`, and as `/skill-name` slash commands — no different from local skills.
  - Sources: [[entities/features-skills|Features: Skills]]
- Non-existent paths are silently skipped**: If a configured directory doesn't exist, Hermes ignores it without errors. Useful for optional shared directories that may not be present on every machine.
  - Sources: [[entities/features-skills|Features: Skills]]
- After completing a complex task (5+ tool calls) successfully
  - Sources: [[entities/features-skills|Features: Skills]]
- When it hit errors or dead ends and found the working path
  - Sources: [[entities/features-skills|Features: Skills]]
- When the user corrected its approach
  - Sources: [[entities/features-skills|Features: Skills]]
- When it discovered a non-trivial workflow
  - Sources: [[entities/features-skills|Features: Skills]]
- Action**, **Use for**, **Key params**
  - Sources: [[entities/features-skills|Features: Skills]]
- Action**: `create`, **Use for**: New skill from scratch, **Key params**: `name`, `content` (full SKILL.md), optional `category`
  - Sources: [[entities/features-skills|Features: Skills]]
- Action**: `patch`, **Use for**: Targeted fixes (preferred), **Key params**: `name`, `old_string`, `new_string`
  - Sources: [[entities/features-skills|Features: Skills]]
- Action**: `edit`, **Use for**: Major structural rewrites, **Key params**: `name`, `content` (full SKILL.md replacement)
  - Sources: [[entities/features-skills|Features: Skills]]
- Action**: `delete`, **Use for**: Remove a skill entirely, **Key params**: `name`
  - Sources: [[entities/features-skills|Features: Skills]]
- Action**: `write_file`, **Use for**: Add/update supporting files, **Key params**: `name`, `file_path`, `file_content`
  - Sources: [[entities/features-skills|Features: Skills]]
- Action**: `remove_file`, **Use for**: Remove a supporting file, **Key params**: `name`, `file_path`
  - Sources: [[entities/features-skills|Features: Skills]]
- Source**, **Example**, **Notes**
  - Sources: [[entities/features-skills|Features: Skills]]
- Source**: `official`, **Example**: `official/security/1password`, **Notes**: Optional skills shipped with Hermes.
  - Sources: [[entities/features-skills|Features: Skills]]
- Source**: `skills-sh`, **Example**: `skills-sh/vercel-labs/agent-skills/vercel-react-best-practices`, **Notes**: Searchable via `hermes skills search <query> --source skills-sh`. Hermes resolves alias-style skills when the skills.sh slug differs from the repo folder.
  - Sources: [[entities/features-skills|Features: Skills]]
- Source**: `well-known`, **Example**: `well-known:https://mintlify.com/docs/.well-known/skills/mintlify`, **Notes**: Skills served directly from `/.well-known/skills/index.json` on a website. Search using the site or docs URL.
  - Sources: [[entities/features-skills|Features: Skills]]
- Source**: `github`, **Example**: `openai/skills/k8s`, **Notes**: Direct GitHub repo/path installs and custom taps.
  - Sources: [[entities/features-skills|Features: Skills]]
- Source**: `clawhub`, `lobehub`, `claude-marketplace`, **Example**: Source-specific identifiers, **Notes**: Community or marketplace integrations.
  - Sources: [[entities/features-skills|Features: Skills]]
- Catalog: [Official Optional Skills Catalog](/docs/reference/optional-skills-catalog)
  - Sources: [[entities/features-skills|Features: Skills]]
- Source in repo: `optional-skills/`
  - Sources: [[entities/features-skills|Features: Skills]]
- Directory: [skills.sh](https://skills.sh/)
  - Sources: [[entities/features-skills|Features: Skills]]
- CLI/tooling repo: [vercel-labs/skills](https://github.com/vercel-labs/skills)
  - Sources: [[entities/features-skills|Features: Skills]]
- Official Vercel skills repo: [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills)
  - Sources: [[entities/features-skills|Features: Skills]]
- Example live endpoint: [Mintlify docs skills index](https://mintlify.com/docs/.well-known/skills/index.json)
  - Sources: [[entities/features-skills|Features: Skills]]
- Reference server implementation: [vercel-labs/skills-handler](https://github.com/vercel-labs/skills-handler)
  - Sources: [[entities/features-skills|Features: Skills]]
- [openai/skills](https://github.com/openai/skills)
  - Sources: [[entities/features-skills|Features: Skills]]
- [anthropics/skills](https://github.com/anthropics/skills)
  - Sources: [[entities/features-skills|Features: Skills]], [[entities/features-skills|Features: Skills]]
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)
  - Sources: [[entities/features-skills|Features: Skills]]
- [garrytan/gstack](https://github.com/garrytan/gstack)
  - Sources: [[entities/features-skills|Features: Skills]]
- Site: [clawhub.ai](https://clawhub.ai/)
  - Sources: [[entities/features-skills|Features: Skills]]
- Hermes source id: `clawhub`
  - Sources: [[entities/features-skills|Features: Skills]]
- [aiskillstore/marketplace](https://github.com/aiskillstore/marketplace)
  - Sources: [[entities/features-skills|Features: Skills]]
- Site: [LobeHub](https://lobehub.com/)
  - Sources: [[entities/features-skills|Features: Skills]]
- Public agents index: [chat-agents.lobehub.com](https://chat-agents.lobehub.com/)
  - Sources: [[entities/features-skills|Features: Skills]]
- Backing repo: [lobehub/lobe-chat-agents](https://github.com/lobehub/lobe-chat-agents)
  - Sources: [[entities/features-skills|Features: Skills]]
- Hermes source id: `lobehub`
  - Sources: [[entities/features-skills|Features: Skills]]
- skills.sh detail page URL
  - Sources: [[entities/features-skills|Features: Skills]]
- install command
  - Sources: [[entities/features-skills|Features: Skills]]
- weekly installs
  - Sources: [[entities/features-skills|Features: Skills]]
- upstream security audit statuses
  - Sources: [[entities/features-skills|Features: Skills]]
- well-known index/endpoint URLs
  - Sources: [[entities/features-skills|Features: Skills]]
- `--force` can override policy blocks for caution/warn-style findings.
  - Sources: [[entities/features-skills|Features: Skills]]
- `--force` does **not** override a `dangerous` scan verdict.
  - Sources: [[entities/features-skills|Features: Skills]]
- Official optional skills (`official/...`) are treated as builtin trust and do not show the third-party warning panel.
  - Sources: [[entities/features-skills|Features: Skills]]
- Level**, **Source**, **Policy**
  - Sources: [[entities/features-skills|Features: Skills]]
- Level**: `builtin`, **Source**: Ships with Hermes, **Policy**: Always trusted
  - Sources: [[entities/features-skills|Features: Skills]]
- Level**: `official`, **Source**: `optional-skills/` in the repo, **Policy**: Builtin trust, no third-party warning
  - Sources: [[entities/features-skills|Features: Skills]]
- Level**: `trusted`, **Source**: Trusted registries/repos such as `openai/skills`, `anthropics/skills`, **Policy**: More permissive policy than community sources
  - Sources: [[entities/features-skills|Features: Skills]]
- Level**: `community`, **Source**: Everything else (`skills.sh`, well-known endpoints, custom GitHub repos, most marketplaces), **Policy**: Non-dangerous findings can be overridden with `--force`; `dangerous` verdicts stay blocked
  - Sources: [[entities/features-skills|Features: Skills]]
- Unchanged** → safe to pull upstream changes, copy the new bundled version in, record the new origin hash.
  - Sources: [[entities/features-skills|Features: Skills]]
- Changed** → treated as **user-modified** and skipped forever, so your edits never get stomped.
  - Sources: [[entities/features-skills|Features: Skills]]
- File**, **Purpose**, **Char Limit**
  - Sources: [[entities/features-memory|Features: Memory]]
- File**: **MEMORY.md**, **Purpose**: Agent's personal notes — environment facts, conventions, things learned, **Char Limit**: 2,200 chars (~800 tokens)
  - Sources: [[entities/features-memory|Features: Memory]]
- File**: **USER.md**, **Purpose**: User profile — your preferences, communication style, expectations, **Char Limit**: 1,375 chars (~500 tokens)
  - Sources: [[entities/features-memory|Features: Memory]]
- A header showing which store (MEMORY or USER PROFILE)
  - Sources: [[entities/features-memory|Features: Memory]]
- Usage percentage and character counts so the agent knows capacity
  - Sources: [[entities/features-memory|Features: Memory]]
- Individual entries separated by `§` (section sign) delimiters
  - Sources: [[entities/features-memory|Features: Memory]]
- Entries can be multiline
  - Sources: [[entities/features-memory|Features: Memory]]
- add** — Add a new memory entry
  - Sources: [[entities/features-memory|Features: Memory]]
- replace** — Replace an existing entry with updated content (uses substring matching via `old_text`)
  - Sources: [[entities/features-memory|Features: Memory]]
- remove** — Remove an entry that's no longer relevant (uses substring matching via `old_text`)
  - Sources: [[entities/features-memory|Features: Memory]]
- Environment facts (OS, tools, project structure)
  - Sources: [[entities/features-memory|Features: Memory]]
- Project conventions and configuration
  - Sources: [[entities/features-memory|Features: Memory]]
- Tool quirks and workarounds discovered
  - Sources: [[entities/features-memory|Features: Memory]]
- Completed task diary entries
  - Sources: [[entities/features-memory|Features: Memory]]
- Skills and techniques that worked
  - Sources: [[entities/features-memory|Features: Memory]]
- Name, role, timezone
  - Sources: [[entities/features-memory|Features: Memory]]
- Communication preferences (concise vs detailed, format preferences)
  - Sources: [[entities/features-memory|Features: Memory]]
- Pet peeves and things to avoid
  - Sources: [[entities/features-memory|Features: Memory]]
- Workflow habits
  - Sources: [[entities/features-memory|Features: Memory]]
- Technical skill level
  - Sources: [[entities/features-memory|Features: Memory]]
- User preferences:** "I prefer TypeScript over JavaScript" → save to `user`
  - Sources: [[entities/features-memory|Features: Memory]]
- Environment facts:** "This server runs Debian 12 with PostgreSQL 16" → save to `memory`
  - Sources: [[entities/features-memory|Features: Memory]]
- Corrections:** "Don't use `sudo` for Docker commands, user is in docker group" → save to `memory`
  - Sources: [[entities/features-memory|Features: Memory]]
- Conventions:** "Project uses tabs, 120-char line width, Google-style docstrings" → save to `memory`
  - Sources: [[entities/features-memory|Features: Memory]]
- Completed work:** "Migrated database from MySQL to PostgreSQL on 2026-01-15" → save to `memory`
  - Sources: [[entities/features-memory|Features: Memory]]
- Explicit requests:** "Remember that my API key rotation happens monthly" → save to `memory`
  - Sources: [[entities/features-memory|Features: Memory]]
- Trivial/obvious info:** "User asked about Python" — too vague to be useful
  - Sources: [[entities/features-memory|Features: Memory]]
- Easily re-discovered facts:** "Python 3.12 supports f-string nesting" — can web search this
  - Sources: [[entities/features-memory|Features: Memory]]
- Raw data dumps:** Large code blocks, log files, data tables — too big for memory
  - Sources: [[entities/features-memory|Features: Memory]]
- Session-specific ephemera:** Temporary file paths, one-off debugging context
  - Sources: [[entities/features-memory|Features: Memory]]
- Information already in context files:** SOUL.md and AGENTS.md content
  - Sources: [[entities/features-memory|Features: Memory]]
- Store**, **Limit**, **Typical entries**
  - Sources: [[entities/features-memory|Features: Memory]]
- Store**: memory, **Limit**: 2,200 chars, **Typical entries**: 8-15 entries
  - Sources: [[entities/features-memory|Features: Memory]]
- Store**: user, **Limit**: 1,375 chars, **Typical entries**: 5-10 entries
  - Sources: [[entities/features-memory|Features: Memory]]
- All CLI and messaging sessions are stored in SQLite (`~/.hermes/state.db`) with FTS5 full-text search
  - Sources: [[entities/features-memory|Features: Memory]]
- Search queries return relevant past conversations with Gemini Flash summarization
  - Sources: [[entities/features-memory|Features: Memory]]
- The agent can find things it discussed weeks ago, even if they're not in its active memory
  - Sources: [[entities/features-memory|Features: Memory]]
- Feature**, **Persistent Memory**, **Session Search**
  - Sources: [[entities/features-memory|Features: Memory]]
- Feature**: **Capacity**, **Persistent Memory**: ~1,300 tokens total, **Session Search**: Unlimited (all sessions)
  - Sources: [[entities/features-memory|Features: Memory]]
- Feature**: **Speed**, **Persistent Memory**: Instant (in system prompt), **Session Search**: Requires search + LLM summarization
  - Sources: [[entities/features-memory|Features: Memory]]
- Feature**: **Use case**, **Persistent Memory**: Key facts always available, **Session Search**: Finding specific past conversations
  - Sources: [[entities/features-memory|Features: Memory]]
- Feature**: **Management**, **Persistent Memory**: Manually curated by agent, **Session Search**: Automatic — all sessions stored
  - Sources: [[entities/features-memory|Features: Memory]]
- Feature**: **Token cost**, **Persistent Memory**: Fixed per session (~1,300 tokens), **Session Search**: On-demand (searched when needed)
  - Sources: [[entities/features-memory|Features: Memory]]
- Category**, **Examples**, **Description**
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Web**, **Examples**: `web_search`, `web_extract`, **Description**: Search the web and extract page content.
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Terminal & Files**, **Examples**: `terminal`, `process`, `read_file`, `patch`, **Description**: Execute commands and manipulate files.
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Browser**, **Examples**: `browser_navigate`, `browser_snapshot`, `browser_vision`, **Description**: Interactive browser automation with text and vision support.
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Media**, **Examples**: `vision_analyze`, `image_generate`, `text_to_speech`, **Description**: Multimodal analysis and generation.
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Agent orchestration**, **Examples**: `todo`, `clarify`, `execute_code`, `delegate_task`, **Description**: Planning, clarification, code execution, and subagent delegation.
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Memory & recall**, **Examples**: `memory`, `session_search`, **Description**: Persistent memory and session search.
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Automation & delivery**, **Examples**: `cronjob`, `send_message`, **Description**: Scheduled tasks with create/list/update/pause/resume/run/remove actions, plus outbound messaging delivery.
  - Sources: [[entities/features-tools|Features: Tools]]
- Category**: **Integrations**, **Examples**: `ha_*`, MCP server tools, `rl_*`, **Description**: Home Assistant, MCP, RL training, and other integrations.
  - Sources: [[entities/features-tools|Features: Tools]]
- Backend**, **Description**, **Use Case**
  - Sources: [[entities/features-tools|Features: Tools]]
- Backend**: `local`, **Description**: Run on your machine (default), **Use Case**: Development, trusted tasks
  - Sources: [[entities/features-tools|Features: Tools]]
- Backend**: `docker`, **Description**: Isolated containers, **Use Case**: Security, reproducibility
  - Sources: [[entities/features-tools|Features: Tools]]
- Backend**: `ssh`, **Description**: Remote server, **Use Case**: Sandboxing, keep agent away from its own code
  - Sources: [[entities/features-tools|Features: Tools]]
- Backend**: `singularity`, **Description**: HPC containers, **Use Case**: Cluster computing, rootless
  - Sources: [[entities/features-tools|Features: Tools]]
- Backend**: `modal`, **Description**: Cloud execution, **Use Case**: Serverless, scale
  - Sources: [[entities/features-tools|Features: Tools]]
- Backend**: `daytona`, **Description**: Cloud sandbox workspace, **Use Case**: Persistent remote dev environments
  - Sources: [[entities/features-tools|Features: Tools]]
- Read-only root filesystem (Docker)
  - Sources: [[entities/features-tools|Features: Tools]]
- All Linux capabilities dropped
  - Sources: [[entities/features-tools|Features: Tools]]
- No privilege escalation
  - Sources: [[entities/features-tools|Features: Tools]]
- PID limits (256 processes)
  - Sources: [[entities/features-tools|Features: Tools]]
- Full namespace isolation
  - Sources: [[entities/features-tools|Features: Tools]]
- Persistent workspace via volumes, not writable root layer
  - Sources: [[entities/features-tools|Features: Tools]]
- Model name** — Current model (truncated if longer than 26 chars)
  - Sources: [[entities/cli-interface|CLI Interface]]
- Token count** — Context tokens used / max context window
  - Sources: [[entities/cli-interface|CLI Interface]]
- Context bar** — Visual fill indicator with color-coded thresholds
  - Sources: [[entities/cli-interface|CLI Interface]]
- Cost** — Estimated session cost (or n/a for unknown/zero-priced models)
  - Sources: [[entities/cli-interface|CLI Interface]]
- Duration** — Elapsed session time
  - Sources: [[entities/cli-interface|CLI Interface]]
- Full layout at ≥ 76 columns
  - Sources: [[entities/cli-interface|CLI Interface]]
- Compact at 52–75 columns
  - Sources: [[entities/cli-interface|CLI Interface]]
- Minimal (model + duration only) below 52 columns
  - Sources: [[entities/cli-interface|CLI Interface]]
- Green** < 50% — Plenty of room
  - Sources: [[entities/cli-interface|CLI Interface]]
- Yellow** 50–80% — Getting full
  - Sources: [[entities/cli-interface|CLI Interface]]
- Orange** 80–95% — Approaching limit
  - Sources: [[entities/cli-interface|CLI Interface]]
- Red** ≥ 95% — Near overflow — consider `/compress`
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/help` — Show command help
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/model` — Show or change the current model
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/tools` — List currently available tools
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/skills browse` — Browse the skills hub and official optional skills
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/background <prompt>` — Run a prompt in a separate background session
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/skin` — Show or switch the active CLI skin
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/voice on` — Enable CLI voice mode (press Ctrl+B to record)
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/voice tts` — Toggle spoken playback for Hermes replies
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/reasoning high` — Increase reasoning effort
  - Sources: [[entities/cli-interface|CLI Interface]]
- `/title My Session` — Name the current session
  - Sources: [[entities/cli-interface|CLI Interface]]
- Type a new message + Enter while the agent is working — it interrupts and processes your new instructions
  - Sources: [[entities/cli-interface|CLI Interface]]
- Ctrl+C** — interrupt the current operation (press twice within 2s to force exit)
  - Sources: [[entities/cli-interface|CLI Interface]]
- "interrupt"** (default) — Your message interrupts the current operation and is processed immediately
  - Sources: [[entities/cli-interface|CLI Interface]]
- "queue"** — Your message is silently queued and sent as the next turn after the agent finishes
  - Sources: [[entities/cli-interface|CLI Interface]]
- session metadata (ID, title, timestamps, token counters)
  - Sources: [[entities/cli-interface|CLI Interface]]
- message history
  - Sources: [[entities/cli-interface|CLI Interface]]
- lineage across compressed/resumed sessions
  - Sources: [[entities/cli-interface|CLI Interface]]
- full-text search indexes used by session_search
  - Sources: [[entities/cli-interface|CLI Interface]]
- Isolated conversation** — the background agent has no knowledge of your current session's history. It receives only the prompt you provide.
  - Sources: [[entities/cli-interface|CLI Interface]]
- Same configuration** — the background agent inherits your model, provider, toolsets, reasoning settings, and fallback model from the current session.
  - Sources: [[entities/cli-interface|CLI Interface]]
- Non-blocking** — your foreground session stays fully interactive. You can chat, run commands, or even start more background tasks.
  - Sources: [[entities/cli-interface|CLI Interface]]
- Multiple tasks** — you can run several background tasks simultaneously. Each gets a numbered ID.
  - Sources: [[entities/cli-interface|CLI Interface]]
- Long-running research** — "/background research the latest developments in quantum error correction" while you work on code
  - Sources: [[entities/cli-interface|CLI Interface]]
- File processing** — "/background analyze all Python files in this repo and list any security issues" while you continue a conversation
  - Sources: [[entities/cli-interface|CLI Interface]]
- Parallel investigations** — start multiple background tasks to explore different angles simultaneously
  - Sources: [[entities/cli-interface|CLI Interface]]
- Suppresses verbose logging from tools
  - Sources: [[entities/cli-interface|CLI Interface]]
- Enables kawaii-style animated feedback
  - Sources: [[entities/cli-interface|CLI Interface]]
- Keeps output clean and user-friendly
  - Sources: [[entities/cli-interface|CLI Interface]]
- [Using Hermes](/docs/user-guide/cli)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Features](/docs/user-guide/features/overview)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Messaging Platforms](/docs/user-guide/messaging/)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Integrations](/docs/integrations/)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Guides & Tutorials](/docs/guides/tips)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Developer Guide](/docs/developer-guide/contributing)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Reference](/docs/reference/cli-commands)[CLI Commands Reference](/docs/reference/cli-commands)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Profile Commands Reference](/docs/reference/profile-commands)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Environment Variables](/docs/reference/environment-variables)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Built-in Tools Reference](/docs/reference/tools-reference)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Toolsets Reference](/docs/reference/toolsets-reference)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [MCP Config Reference](/docs/reference/mcp-config-reference)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Optional Skills Catalog](/docs/reference/optional-skills-catalog)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [FAQ & Troubleshooting](/docs/reference/faq)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [](/docs/)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- FAQ & Troubleshooting
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [OpenRouter](https://openrouter.ai/) — access hundreds of models through one API key (recommended for flexibility)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Nous Portal — Nous Research's own inference endpoint
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- OpenAI — GPT-4o, o1, o3, etc.
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Anthropic — Claude models (via OpenRouter or compatible proxy)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Google — Gemini models (via OpenRouter or compatible proxy)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- z.ai / ZhipuAI — GLM models
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Kimi / Moonshot AI — Kimi models
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- MiniMax — global and China endpoints
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Local models — via [Ollama](https://ollama.com/), [vLLM](https://docs.vllm.ai/), [llama.cpp](https://github.com/ggerganov/llama.cpp), [SGLang](https://github.com/sgl-project/sglang), or any OpenAI-compatible server
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Memory stores facts — things the agent knows about you, your projects, and preferences. Memories are retrieved automatically based on relevance.
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Skills store procedures — step-by-step instructions for how to do things. Skills are recalled when the agent encounters a similar task.
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Upgrading your provider plan
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Switching to a different model or provider
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Using `hermes chat --provider ` to route to a different backend
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Ask the agent to use a safer alternative
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- See the full list of dangerous patterns in the [[[entity.security|Security]] docs](/docs/user-guide/[[entity.security|Security]])
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Avoid `sudo` in messaging — ask the agent to find alternatives
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- If you must use `sudo`, configure passwordless sudo for specific commands in `/etc/sudoers`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Or switch to the terminal interface for administrative tasks: `hermes chat`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Verify your bot token is valid with `hermes gateway setup`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Check gateway logs: `cat ~/.hermes/logs/gateway.log | tail -50`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- For webhook-based platforms (Slack, WhatsApp), ensure your server is publicly accessible
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Open `/etc/wsl.conf` (create it if it doesn't exist)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- From PowerShell: `wsl --shutdown`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Reopen your WSL terminal
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Verify: `systemctl is-system-running` should say "running" or "degraded"
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Create a task that runs `wsl -d Ubuntu -- bash -lc 'hermes gateway run'`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Set it to trigger on user logon
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Try a faster/smaller model: `hermes chat --model openrouter/meta-llama/llama-3.1-8b-instruct`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Reduce active toolsets: `hermes chat -t "terminal"`
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Check your network latency to the provider
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- For local models, ensure you have enough GPU VRAM
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Check gateway/agent logs for MCP connection errors
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Ensure the server responds to the `tools/list` RPC method
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Review any `tools.include`, `tools.exclude`, `tools.resources`, `tools.prompts`, or `enabled` settings under that server
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Remember that resource/prompt utility tools are only registered when the session actually supports those capabilities
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Use `/reload-mcp` after changing config
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [MCP (Model Context Protocol)](/docs/user-guide/features/mcp)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/learning-path|Learning Path]]
- Increase the timeout in your MCP server config if supported
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Check if the MCP server process is still running
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- For remote HTTP MCP servers, check network connectivity
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- `off` — Only the final response. No tool calls, no reasoning, no logs.
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- `new` — Shows new tool calls as they happen (brief one-liners).
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- `all` — Shows all tool activity including results.
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- `verbose` — Full detail including tool arguments and outputs.
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Search existing issues: [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- Ask the community: [Nous Research Discord](https://discord.gg/nousresearch)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- File a bug report: Include your OS, Python version (`python3 --version`), Hermes version (`hermes --version`), and the full error message
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Does it work on Windows?](#does-it-work-on-windows)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Does it work on Android / Termux?](#does-it-work-on-android--termux)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Is my data sent anywhere?](#is-my-data-sent-anywhere)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Can I use it offline / with local models?](#can-i-use-it-offline--with-local-models)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [How much does it cost?](#how-much-does-it-cost)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Can multiple people use one instance?](#can-multiple-people-use-one-instance)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [What&#39;s the difference between memory and skills?](#whats-the-difference-between-memory-and-skills)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Can I use it in my own Python project?](#can-i-use-it-in-my-own-python-project)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Troubleshooting](#troubleshooting)[Installation Issues](#installation-issues)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Provider & Model Issues](#provider--model-issues)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Terminal Issues](#terminal-issues)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Messaging Issues](#messaging-issues)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Performance Issues](#performance-issues)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [MCP Issues](#mcp-issues)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Profiles](#profiles)[How do profiles differ from just setting HERMES_HOME?](#how-do-profiles-differ-from-just-setting-hermes_home)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Can two profiles share the same bot token?](#can-two-profiles-share-the-same-bot-token)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Do profiles share memory or sessions?](#do-profiles-share-memory-or-sessions)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [What happens when I run `hermes update`?](#what-happens-when-i-run-hermes-update)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Can I move a profile to a different machine?](#can-i-move-a-profile-to-a-different-machine)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [How many profiles can I run?](#how-many-profiles-can-i-run)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Workflows & Patterns](#workflows--patterns)[Using different models for different tasks (multi-model workflows)](#using-different-models-for-different-tasks-multi-model-workflows)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Running multiple agents on one WhatsApp number (per-chat binding)](#running-multiple-agents-on-one-whatsapp-number-per-chat-binding)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Controlling what shows up in Telegram (hiding logs and reasoning)](#controlling-what-shows-up-in-telegram-hiding-logs-and-reasoning)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Managing skills on Telegram (slash command limit)](#managing-skills-on-telegram-slash-command-limit)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Shared thread sessions (multiple users, one conversation)](#shared-thread-sessions-multiple-users-one-conversation)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Exporting Hermes to another machine](#exporting-hermes-to-another-machine)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Permission denied when reloading shell after install](#permission-denied-when-reloading-shell-after-install)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Error 400 on first agent run](#error-400-on-first-agent-run)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [Still Stuck?](#still-stuck)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [User Guide](/docs/user-guide/cli)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Developer Guide](/docs/developer-guide/architecture)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Reference](/docs/reference/cli-commands)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]], [[entities/quickstart|Quickstart]]
- [GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Skills Hub](https://agentskills.io)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Nous Research](https://nousresearch.com)
  - Sources: [[entities/faq-troubleshooting|FAQ & Troubleshooting]], [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Guides & Tutorials](/docs/guides/tips)[Tips & Best Practices](/docs/guides/tips)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Run Local LLMs on Mac](/docs/guides/local-llm-on-mac)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Tutorial: Daily Briefing Bot](/docs/guides/daily-briefing-bot)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Tutorial: Team Telegram Assistant](/docs/guides/team-telegram-assistant)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Using Hermes as a Python Library](/docs/guides/python-library)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Use SOUL.md with Hermes](/docs/guides/use-soul-with-hermes)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Use Voice Mode with Hermes](/docs/guides/use-voice-mode-with-hermes)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]], [[entities/learning-path|Learning Path]]
- [Build a Plugin](/docs/guides/build-a-hermes-plugin)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Automate Anything with Cron](/docs/guides/automate-with-cron)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Automation Templates](/docs/guides/automation-templates)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Cron Troubleshooting](/docs/guides/cron-troubleshooting)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Working with Skills](/docs/guides/work-with-skills)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Delegation & Parallel Work](/docs/guides/delegation-patterns)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Tutorial: GitHub PR Review Agent](/docs/guides/github-pr-review-agent)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [GitHub PR Reviews via Webhook](/docs/guides/webhook-github-pr-review)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [Migrate from OpenClaw](/docs/guides/migrate-from-openclaw)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- [AWS Bedrock](/docs/guides/aws-bedrock)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- Guides & Tutorials
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/tips-best-practices|Tips & Best Practices]]
- you want a hands-free CLI workflow
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- you want spoken responses in Telegram or Discord
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- you want Hermes sitting in a Discord voice channel for live conversation
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- you want quick idea capture, debugging, or back-and-forth while walking around instead of typing
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- get text working first
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- enable voice replies second
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- move to Discord voice channels last if you want the full experience
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Hermes starts
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- your provider is configured
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- the agent can answer text prompts normally
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `portaudio` → microphone input / playback for CLI voice mode
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `ffmpeg` → audio conversion for TTS and messaging delivery
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `opus` → Discord voice codec support
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `espeak-ng` → phonemizer backend for NeuTTS
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- STT provider: `local`
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- TTS provider: `edge`
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `local` → best default for privacy and zero-cost use
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `groq` → very fast cloud transcription
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `openai` → good paid fallback
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `edge` → free and good enough for most users
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `neutts` → free local/on-device TTS
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `elevenlabs` → best quality
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `openai` → good middle ground
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `mistral` → multilingual, native Opus
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- press `Ctrl+B`
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- wait for silence detection to stop recording automatically
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Hermes transcribes and responds
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- if TTS is on, it speaks the answer
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- the loop can automatically restart for continuous use
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- "Read the last error again"
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- "Explain the root cause in simpler terms"
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- "Now give me the exact fix"
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- walking around while thinking
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- dictating half-formed ideas
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- asking Hermes to structure your thoughts in real time
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `/voice on` if you want spoken replies only for voice-originating messages
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `/voice tts` if you want a full spoken assistant all the time
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- you are away from your machine
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- you want to send voice notes and get quick spoken replies
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- you want Hermes to function like a portable research or ops assistant
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- preferably Use Voice Activity
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Presence Intent
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Server Members Intent
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Message Content Intent
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- users speak in the VC
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Hermes detects speech boundaries
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- transcripts are posted in the associated text channel
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Hermes responds in text and audio
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- keep `DISCORD_ALLOWED_USERS` tight
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- use a dedicated bot/testing channel at first
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- verify STT and TTS work in ordinary text-chat voice mode before trying VC mode
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- STT: local `large-v3` or Groq `whisper-large-v3`
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- TTS: ElevenLabs
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- STT: local `base` or Groq
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- STT: local
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- your Discord user ID is in `DISCORD_ALLOWED_USERS`
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- you are not muted
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- privileged intents are enabled
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- the bot has Connect/Speak permissions
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- TTS provider config
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- API key / quota for ElevenLabs or OpenAI
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- `ffmpeg` install for Edge conversion paths
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- quieter environment
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- higher `silence_threshold`
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- different STT provider/model
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- shorter, clearer utterances
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- get text Hermes working
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- install `hermes-agent[voice]`
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- use CLI voice mode with local STT + Edge TTS
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- then enable `/voice on` in Telegram or Discord
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- only after that, try Discord VC mode
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Voice Mode feature reference](/docs/user-guide/features/voice-mode)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Messaging Gateway](/docs/user-guide/messaging)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [[[entity.discord-setup|Discord Setup]]](/docs/user-guide/messaging/discord)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [[[entity.telegram-setup|Telegram Setup]]](/docs/user-guide/messaging/telegram)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Choose your voice mode setup](#choose-your-voice-mode-setup)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Step 1: make sure normal Hermes works first](#step-1-make-sure-normal-hermes-works-first)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Step 2: install the right extras](#step-2-install-the-right-extras)[CLI microphone + playback](#cli-microphone--playback)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Messaging platforms](#messaging-platforms)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Premium ElevenLabs TTS](#premium-elevenlabs-tts)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Local NeuTTS (optional)](#local-neutts-optional)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Everything](#everything)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Step 3: install system dependencies](#step-3-install-system-dependencies)[macOS](#macos)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Ubuntu / Debian](#ubuntu--debian)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Step 4: choose STT and TTS providers](#step-4-choose-stt-and-tts-providers)[Easiest / cheapest setup](#easiest--cheapest-setup)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Environment file example](#environment-file-example)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Provider recommendations](#provider-recommendations)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [If you use `hermes setup`](#if-you-use-hermes-setup)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Step 5: recommended config](#step-5-recommended-config)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Use case 1: CLI voice mode](#use-case-1-cli-voice-mode)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Turn it on](#turn-it-on)[Recording flow](#recording-flow)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Useful commands](#useful-commands)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Good CLI workflows](#good-cli-workflows)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Tuning CLI behavior](#tuning-cli-behavior)[Silence threshold](#silence-threshold)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Silence duration](#silence-duration)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Record key](#record-key)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Use case 2: voice replies in Telegram or Discord](#use-case-2-voice-replies-in-telegram-or-discord)[Start the gateway](#start-the-gateway)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Turn on voice replies](#turn-on-voice-replies)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Modes](#modes)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [When to use which mode](#when-to-use-which-mode)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Good messaging workflows](#good-messaging-workflows)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Use case 3: Discord voice channels](#use-case-3-discord-voice-channels)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Required Discord permissions](#required-discord-permissions)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Join and leave](#join-and-leave)[What happens when joined](#what-happens-when-joined)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Best practices for Discord VC use](#best-practices-for-discord-vc-use)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Voice quality recommendations](#voice-quality-recommendations)[Best quality setup](#best-quality-setup)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Best speed / convenience setup](#best-speed--convenience-setup)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Best zero-cost setup](#best-zero-cost-setup)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Common failure modes](#common-failure-modes)["No audio device found"](#no-audio-device-found)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- ["Bot joins but hears nothing"](#bot-joins-but-hears-nothing)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- ["It transcribes but does not speak"](#it-transcribes-but-does-not-speak)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- ["Whisper outputs garbage"](#whisper-outputs-garbage)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- ["It works in DMs but not in server channels"](#it-works-in-dms-but-not-in-server-channels)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Suggested first-week setup](#suggested-first-week-setup)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [Where to read next](#where-to-read-next)
  - Sources: [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- Use MCP with Hermes
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- a tool already exists in MCP form and you do not want to build a native Hermes tool
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- you want Hermes to operate against a local or remote system through a clean RPC layer
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- you want fine-grained per-server exposure control
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- you want to connect Hermes to internal APIs, databases, or company systems without modifying Hermes core
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- a built-in Hermes tool already solves the job well
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- the server exposes a huge dangerous tool surface and you are not prepared to filter it
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- you only need one very narrow integration and a native tool would be simpler and safer
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- Hermes remains the agent
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- MCP servers contribute tools
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- Hermes discovers those tools at startup or reload time
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- the model can use them like normal tools
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- you control how much of each server is visible
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- Hermes banner/status should show MCP integration when configured
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- ask Hermes what tools it has available
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- use `/reload-mcp` after config changes
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- check logs if the server failed to connect
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- Server-native MCP tools
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- filtered with:
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]], [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- `tools.exclude`
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- Hermes-added utility wrappers
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- `tools.prompts`
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- your config allows them, and
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- the MCP server session actually supports those capabilities
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- use `tools.include`
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- start with the smallest set possible
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- filesystem server rooted to one project dir, not your whole home directory
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- git server pointed at one repo
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- internal API server with read-heavy tool exposure by default
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- include/exclude lists
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- enabled flags
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- resources/prompts toggles
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- auth headers / env
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- filtered by `tools.include`
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- excluded by `tools.exclude`
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- utility wrappers disabled via `resources: false` or `prompts: false`
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- server does not actually support resources/prompts
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- `enabled: false` was not left in config
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- command/runtime exists (`npx`, `uvx`, etc.)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- HTTP endpoint is reachable
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- auth env or headers are correct
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- filesystem
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- fetch / documentation MCP servers
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- one narrow internal API
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- giant business systems with lots of destructive actions and no filtering
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- anything you do not understand well enough to constrain
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Mental model](#mental-model)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Step 1: install MCP support](#step-1-install-mcp-support)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Step 2: add one server first](#step-2-add-one-server-first)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Step 3: verify MCP loaded](#step-3-verify-mcp-loaded)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Step 4: start filtering immediately](#step-4-start-filtering-immediately)[Example: whitelist only what you want](#example-whitelist-only-what-you-want)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Example: blacklist dangerous actions](#example-blacklist-dangerous-actions)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Example: disable utility wrappers too](#example-disable-utility-wrappers-too)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [What does filtering actually affect?](#what-does-filtering-actually-affect)[Utility wrappers you may see](#utility-wrappers-you-may-see)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Common patterns](#common-patterns)[Pattern 1: local project assistant](#pattern-1-local-project-assistant)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Pattern 2: GitHub triage assistant](#pattern-2-github-triage-assistant)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Pattern 3: internal API assistant](#pattern-3-internal-api-assistant)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Pattern 4: documentation / knowledge servers](#pattern-4-documentation--knowledge-servers)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Tutorial: end-to-end setup with filtering](#tutorial-end-to-end-setup-with-filtering)[Phase 1: add GitHub MCP with a tight whitelist](#phase-1-add-github-mcp-with-a-tight-whitelist)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Phase 2: expand only when needed](#phase-2-expand-only-when-needed)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Phase 3: add a second server with different policy](#phase-3-add-a-second-server-with-different-policy)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Safe usage recommendations](#safe-usage-recommendations)[Prefer allowlists for dangerous systems](#prefer-allowlists-for-dangerous-systems)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Disable unused utilities](#disable-unused-utilities)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Keep servers scoped narrowly](#keep-servers-scoped-narrowly)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Reload after config changes](#reload-after-config-changes)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Troubleshooting by symptom](#troubleshooting-by-symptom)["The server connects but the tools I expected are missing"](#the-server-connects-but-the-tools-i-expected-are-missing)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- ["The server is configured but nothing loads"](#the-server-is-configured-but-nothing-loads)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- ["Why do I see fewer tools than the MCP server advertises?"](#why-do-i-see-fewer-tools-than-the-mcp-server-advertises)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- ["How do I remove an MCP server without deleting the config?"](#how-do-i-remove-an-mcp-server-without-deleting-the-config)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Recommended first MCP setups](#recommended-first-mcp-setups)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [Related docs](#related-docs)
  - Sources: [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- Tips & Best Practices
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- Prefer opening files with an explicit UTF-8 encoding:
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- In PowerShell, you can also switch the current session to UTF-8 for console and native command output:
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Provide Context Up Front](#provide-context-up-front)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Use Context Files for Recurring Instructions](#use-context-files-for-recurring-instructions)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Let the Agent Use Its Tools](#let-the-agent-use-its-tools)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Use Skills for Complex Workflows](#use-skills-for-complex-workflows)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [CLI Power User Tips](#cli-power-user-tips)[Multi-Line Input](#multi-line-input)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Paste Detection](#paste-detection)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Interrupt and Redirect](#interrupt-and-redirect)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Resume Sessions with `-c`](#resume-sessions-with--c)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Clipboard Image Paste](#clipboard-image-paste)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Slash Command Autocomplete](#slash-command-autocomplete)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Context Files](#context-files)[AGENTS.md: Your Project&#39;s Brain](#agentsmd-your-projects-brain)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [SOUL.md: Customize Personality](#soulmd-customize-personality)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [.cursorrules Compatibility](#cursorrules-compatibility)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Discovery](#discovery)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Memory & Skills](#memory--skills)[Memory vs. Skills: What Goes Where](#memory-vs-skills-what-goes-where)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [When to Create Skills](#when-to-create-skills)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Managing Memory Capacity](#managing-memory-capacity)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Let the Agent Remember](#let-the-agent-remember)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Performance & Cost](#performance--cost)[Don&#39;t Break the Prompt Cache](#dont-break-the-prompt-cache)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Use /compress Before Hitting Limits](#use-compress-before-hitting-limits)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Delegate for Parallel Work](#delegate-for-parallel-work)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Use execute_code for Batch Operations](#use-execute_code-for-batch-operations)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Choose the Right Model](#choose-the-right-model)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Messaging Tips](#messaging-tips)[Set a Home Channel](#set-a-home-channel)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Use /title to Organize Sessions](#use-title-to-organize-sessions)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [DM Pairing for Team Access](#dm-pairing-for-team-access)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Tool Progress Display Modes](#tool-progress-display-modes)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Security](#security)[Use Docker for Untrusted Code](#use-docker-for-untrusted-code)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Avoid Windows Encoding Pitfalls](#avoid-windows-encoding-pitfalls)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Review Before Choosing "Always"](#review-before-choosing-always)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Command Approval Is Your Safety Net](#command-approval-is-your-safety-net)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [Use Allowlists for Messaging Bots](#use-allowlists-for-messaging-bots)
  - Sources: [[entities/tips-best-practices|Tips & Best Practices]]
- [[[entity.installation|Installation]]](/docs/getting-started/[[entity.installation|Installation]])
  - Sources: [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]], [[entities/quickstart|Quickstart]]
- [Android / Termux](/docs/getting-started/termux)
  - Sources: [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Nix & NixOS Setup](/docs/getting-started/nix-setup)
  - Sources: [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Updating & Uninstalling](/docs/getting-started/updating)
  - Sources: [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- [Learning Path](/docs/getting-started/learning-path)
  - Sources: [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- Getting Started
  - Sources: [[entities/learning-path|Learning Path]], [[entities/installation|Installation]], [[entities/quickstart|Quickstart]]
- Learning Path
  - Sources: [[entities/learning-path|Learning Path]]
- Know your level? Jump to the [experience-level table](#by-experience-level) and follow the reading order for your tier.
  - Sources: [[entities/learning-path|Learning Path]]
- Have a specific goal? Skip to [By Use Case](#by-use-case) and find the scenario that matches.
  - Sources: [[entities/learning-path|Learning Path]]
- Just browsing? Check the [Key Features](#key-features-at-a-glance) table for a quick overview of everything Hermes Agent can do.
  - Sources: [[entities/learning-path|Learning Path]]
- [[[entity.quickstart|Quickstart]]](/docs/getting-started/[[entity.quickstart|Quickstart]])
  - Sources: [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]]
- [CLI Usage](/docs/user-guide/cli)
  - Sources: [[entities/learning-path|Learning Path]]
- [Code Execution](/docs/user-guide/features/code-execution)
  - Sources: [[entities/learning-path|Learning Path]]
- [Tips & Tricks](/docs/guides/tips)
  - Sources: [[entities/learning-path|Learning Path]]
- [Messaging Overview](/docs/user-guide/messaging)
  - Sources: [[entities/learning-path|Learning Path]]
- [Telegram Setup](/docs/user-guide/messaging/telegram)
  - Sources: [[entities/learning-path|Learning Path]]
- [Discord Setup](/docs/user-guide/messaging/discord)
  - Sources: [[entities/learning-path|Learning Path]]
- [Voice Mode](/docs/user-guide/features/voice-mode)
  - Sources: [[entities/learning-path|Learning Path]]
- [Security](/docs/user-guide/security)
  - Sources: [[entities/learning-path|Learning Path]]
- [Daily Briefing Bot](/docs/guides/daily-briefing-bot)
  - Sources: [[entities/learning-path|Learning Path]]
- [Team Telegram Assistant](/docs/guides/team-telegram-assistant)
  - Sources: [[entities/learning-path|Learning Path]]
- [Cron Scheduling](/docs/user-guide/features/cron)
  - Sources: [[entities/learning-path|Learning Path]]
- [Batch Processing](/docs/user-guide/features/batch-processing)
  - Sources: [[entities/learning-path|Learning Path]]
- [Delegation](/docs/user-guide/features/delegation)
  - Sources: [[entities/learning-path|Learning Path]]
- [Hooks](/docs/user-guide/features/hooks)
  - Sources: [[entities/learning-path|Learning Path]]
- [Tools Overview](/docs/user-guide/features/tools)
  - Sources: [[entities/learning-path|Learning Path]]
- [Skills Overview](/docs/user-guide/features/skills)
  - Sources: [[entities/learning-path|Learning Path]]
- [Architecture](/docs/developer-guide/architecture)
  - Sources: [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]], [[entities/learning-path|Learning Path]]
- [Adding Tools](/docs/developer-guide/adding-tools)
  - Sources: [[entities/learning-path|Learning Path]]
- [Creating Skills](/docs/developer-guide/creating-skills)
  - Sources: [[entities/learning-path|Learning Path]]
- [RL Training](/docs/user-guide/features/rl-training)
  - Sources: [[entities/learning-path|Learning Path]]
- [Provider Routing](/docs/user-guide/features/provider-routing)
  - Sources: [[entities/learning-path|Learning Path]]
- [Python Library Guide](/docs/guides/python-library)
  - Sources: [[entities/learning-path|Learning Path]]
- [Tools](/docs/user-guide/features/tools)
  - Sources: [[entities/learning-path|Learning Path]]
- Just finished installing? → Head to the [[[entity.quickstart|Quickstart]]](/docs/getting-started/[[entity.quickstart|Quickstart]]) to run your first conversation.
  - Sources: [[entities/learning-path|Learning Path]]
- Completed the [[entity.quickstart|Quickstart]]? → Read [CLI Usage](/docs/user-guide/cli) and [Configuration](/docs/user-guide/configuration) to customize your setup.
  - Sources: [[entities/learning-path|Learning Path]]
- Comfortable with the basics? → Explore [Tools](/docs/user-guide/features/tools), [Skills](/docs/user-guide/features/skills), and [Memory](/docs/user-guide/features/memory) to unlock the full power of the agent.
  - Sources: [[entities/learning-path|Learning Path]]
- Setting up for a team? → Read [Security](/docs/user-guide/security) and [Sessions](/docs/user-guide/sessions) to understand access control and conversation management.
  - Sources: [[entities/learning-path|Learning Path]]
- Ready to build? → Jump into the [Developer Guide](/docs/developer-guide/architecture) to understand the internals and start contributing.
  - Sources: [[entities/learning-path|Learning Path]]
- Want practical examples? → Check out the [Guides](/docs/guides/tips) section for real-world projects and tips.
  - Sources: [[entities/learning-path|Learning Path]]
- [By Experience Level](#by-experience-level)
  - Sources: [[entities/learning-path|Learning Path]]
- [By Use Case](#by-use-case)["I want a CLI coding assistant"](#i-want-a-cli-coding-assistant)
  - Sources: [[entities/learning-path|Learning Path]]
- ["I want a Telegram/Discord bot"](#i-want-a-telegramdiscord-bot)
  - Sources: [[entities/learning-path|Learning Path]]
- ["I want to automate tasks"](#i-want-to-automate-tasks)
  - Sources: [[entities/learning-path|Learning Path]]
- ["I want to build custom tools/skills"](#i-want-to-build-custom-toolsskills)
  - Sources: [[entities/learning-path|Learning Path]]
- ["I want to train models"](#i-want-to-train-models)
  - Sources: [[entities/learning-path|Learning Path]]
- ["I want to use it as a Python library"](#i-want-to-use-it-as-a-python-library)
  - Sources: [[entities/learning-path|Learning Path]]
- [Key Features at a Glance](#key-features-at-a-glance)
  - Sources: [[entities/learning-path|Learning Path]]
- [What to Read Next](#what-to-read-next)
  - Sources: [[entities/learning-path|Learning Path]]
- [Installation](/docs/getting-started/installation)
  - Sources: [[entities/installation|Installation]]
- Installation
  - Sources: [[entities/installation|Installation]]
- uses Termux `pkg` for system dependencies (`git`, `python`, `nodejs`, `ripgrep`, `ffmpeg`, build tools)
  - Sources: [[entities/installation|Installation]]
- creates the virtualenv with `python -m venv`
  - Sources: [[entities/installation|Installation]]
- exports `ANDROID_API_LEVEL` automatically for Android wheel builds
  - Sources: [[entities/installation|Installation]]
- installs a curated `.[termux]` extra with `pip`
  - Sources: [[entities/installation|Installation]]
- skips the untested browser / WhatsApp bootstrap by default
  - Sources: [[entities/installation|Installation]]
- uv (fast Python package manager)
  - Sources: [[entities/installation|Installation]]
- Python 3.11 (via uv, no sudo needed)
  - Sources: [[entities/installation|Installation]]
- Node.js v22 (for browser automation and WhatsApp bridge)
  - Sources: [[entities/installation|Installation]]
- ripgrep (fast file search)
  - Sources: [[entities/installation|Installation]]
- ffmpeg (audio format conversion for TTS)
  - Sources: [[entities/installation|Installation]]
- [Android / Termux](#android--termux)
  - Sources: [[entities/installation|Installation]]
- [What the Installer Does](#what-the-installer-does)
  - Sources: [[entities/installation|Installation]]
- [After Installation](#after-installation)
  - Sources: [[entities/installation|Installation]]
- [Manual / Developer Installation](#manual--developer-installation)
  - Sources: [[entities/installation|Installation]]
- Quickstart
  - Sources: [[entities/quickstart|Quickstart]]
- Brand new and want the shortest path to a working setup
  - Sources: [[entities/quickstart|Quickstart]]
- Switching providers and don't want to lose time to config mistakes
  - Sources: [[entities/quickstart|Quickstart]]
- Setting up Hermes for a team, bot, or always-on workflow
  - Sources: [[entities/quickstart|Quickstart]]
- Tired of "it installed, but it still does nothing"
  - Sources: [[entities/quickstart|Quickstart]]
- Secrets and tokens → `~/.hermes/.env`
  - Sources: [[entities/quickstart|Quickstart]]
- Non-secret settings → `~/.hermes/config.yaml`
  - Sources: [[entities/quickstart|Quickstart]]
- The banner shows your chosen model/provider
  - Sources: [[entities/quickstart|Quickstart]]
- Hermes replies without error
  - Sources: [[entities/quickstart|Quickstart]]
- It can use a tool if needed (terminal, file read, web search)
  - Sources: [[entities/quickstart|Quickstart]]
- The conversation continues normally for more than one turn
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes tools` — tune tool access per platform
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes skills` — browse and install reusable workflows
  - Sources: [[entities/quickstart|Quickstart]]
- Cron — only after your bot or CLI setup is stable
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes doctor`
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes model`
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes setup`
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes sessions list`
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes --continue`
  - Sources: [[entities/quickstart|Quickstart]]
- `hermes gateway status`
  - Sources: [[entities/quickstart|Quickstart]]
- [CLI Guide](/docs/user-guide/cli) — Master the terminal interface
  - Sources: [[entities/quickstart|Quickstart]]
- [Configuration](/docs/user-guide/configuration) — Customize your setup
  - Sources: [[entities/quickstart|Quickstart]]
- [Messaging Gateway](/docs/user-guide/messaging/) — Connect Telegram, Discord, Slack, WhatsApp, Signal, Email, or Home Assistant
  - Sources: [[entities/quickstart|Quickstart]]
- [Tools & Toolsets](/docs/user-guide/features/tools) — Explore available capabilities
  - Sources: [[entities/quickstart|Quickstart]]
- [AI Providers](/docs/integrations/providers) — Full provider list and setup details
  - Sources: [[entities/quickstart|Quickstart]]
- [Skills System](/docs/user-guide/features/skills) — Reusable workflows and knowledge
  - Sources: [[entities/quickstart|Quickstart]]
- [Tips & Best Practices](/docs/guides/tips) — Power user tips
  - Sources: [[entities/quickstart|Quickstart]]
- [The fastest path](#the-fastest-path)
  - Sources: [[entities/quickstart|Quickstart]]
- [1. Install Hermes Agent](#1-install-hermes-agent)
  - Sources: [[entities/quickstart|Quickstart]]
- [2. Choose a Provider](#2-choose-a-provider)[How settings are stored](#how-settings-are-stored)
  - Sources: [[entities/quickstart|Quickstart]]
- [3. Run Your First Chat](#3-run-your-first-chat)
  - Sources: [[entities/quickstart|Quickstart]]
- [4. Verify Sessions Work](#4-verify-sessions-work)
  - Sources: [[entities/quickstart|Quickstart]]
- [5. Try Key Features](#5-try-key-features)[Use the terminal](#use-the-terminal)
  - Sources: [[entities/quickstart|Quickstart]]
- [Slash commands](#slash-commands)
  - Sources: [[entities/quickstart|Quickstart]]
- [Multi-line input](#multi-line-input)
  - Sources: [[entities/quickstart|Quickstart]]
- [Interrupt the agent](#interrupt-the-agent)
  - Sources: [[entities/quickstart|Quickstart]]
- [6. Add the Next Layer](#6-add-the-next-layer)[Bot or shared assistant](#bot-or-shared-assistant)
  - Sources: [[entities/quickstart|Quickstart]]
- [Automation and tools](#automation-and-tools)
  - Sources: [[entities/quickstart|Quickstart]]
- [Sandboxed terminal](#sandboxed-terminal)
  - Sources: [[entities/quickstart|Quickstart]]
- [Voice mode](#voice-mode)
  - Sources: [[entities/quickstart|Quickstart]]
- [Skills](#skills)
  - Sources: [[entities/quickstart|Quickstart]]
- [MCP servers](#mcp-servers)
  - Sources: [[entities/quickstart|Quickstart]]
- [Editor integration (ACP)](#editor-integration-acp)
  - Sources: [[entities/quickstart|Quickstart]]
- [Common Failure Modes](#common-failure-modes)
  - Sources: [[entities/quickstart|Quickstart]]
- [Recovery Toolkit](#recovery-toolkit)
  - Sources: [[entities/quickstart|Quickstart]]
- [Quick Reference](#quick-reference)
  - Sources: [[entities/quickstart|Quickstart]]
- The update ignores SIGHUP, so closing your SSH session or terminal window no longer kills it mid-install
  - Sources: [[entities/updating-uninstalling|Updating & Uninstalling]]
- All output is mirrored to `~/.hermes/logs/update.log` while the update runs
  - Sources: [[entities/updating-uninstalling|Updating & Uninstalling]]
- Ctrl-C (SIGINT) and system shutdown (SIGTERM) are still honored
  - Sources: [[entities/updating-uninstalling|Updating & Uninstalling]]
- Pre-built binary with all deps — then use the standard CLI workflow
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Declarative config, hardened systemd service, managed secrets
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Everything above, plus a persistent Ubuntu container where the agent can apt/pip/npm install
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Nix with flakes enabled — Determinate Nix recommended (enables flakes by default)
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- API keys for the services you want to use (at minimum: an OpenRouter or Anthropic key)
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Hardened systemd service on the host
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- NoNewPrivileges, ProtectSystem=strict, PrivateTmp
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Agent cannot self-install packages
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Persistent Ubuntu container with /nix/store bind-mounted
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Container isolation, runs as unprivileged user inside
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Agent CAN self-install packages (apt, pip, npm installs persist across restarts)
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Change the LLM model:** `settings.model.default` = "anthropic/claude-sonnet-4"
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Use a different provider endpoint:** `settings.model.base_url` = "https://openrouter.ai/api/v1"
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Add API keys:** `environmentFiles` with sops-nix or agenix
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Give the agent a personality:** Manage ${stateDir}/.hermes/SOUL.md directly
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Add MCP tool servers:** `mcpServers.<name>`
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Mount host directories into container:** `container.extraVolumes`
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Pass GPU access to container:** `container.extraOptions` with "--gpus" "all"
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Use Podman instead of Docker:** `container.backend` = "podman"
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Share state between host CLI and container:** `container.hostUsers`
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `hermes setup` — Config is declarative
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `hermes config edit` — Config is generated from settings
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `hermes config set <key> <value>` — Config is generated from settings
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `hermes gateway install` — The systemd service is managed by NixOS
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `hermes gateway uninstall` — The systemd service is managed by NixOS
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `systemctl restart hermes-agent`: Container NOT recreated, all state persists
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `nixos-rebuild switch` (code change): Container NOT recreated (symlink updated), all state persists
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `Host reboot`: Container NOT recreated, all state persists
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `nix-collect-garbage`: Container NOT recreated (GC root), all state persists
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `Image change (container.image)`: Container IS recreated, /data and /home/hermes persist, writable layer LOST
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- `environment/environmentFiles change`: Container NOT recreated, all state persists
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Cannot save configuration: managed by NixOS** — Edit configuration.nix and nixos-rebuild switch
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Container recreated unexpectedly** — Expected — writable layer resets. Reinstall packages or use a custom image
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- hermes version shows old version** — Container not restarted — systemctl restart hermes-agent
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- Permission denied on /var/lib/hermes** — Use docker exec or sudo -u hermes
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- nix-collect-garbage removed hermes** — GC root missing — Restart the service
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- no container with name or ID "hermes-agent" (Podman)** — Add passwordless sudo for podman
  - Sources: [[entities/nix-nixos-setup|Nix & NixOS Setup]]
- the Hermes CLI
  - Sources: [[entities/android-termux|Android / Termux]]
- cron support
  - Sources: [[entities/android-termux|Android / Termux]]
- PTY/background terminal support
  - Sources: [[entities/android-termux|Android / Termux]]
- Telegram gateway support (manual / best-effort background runs)
  - Sources: [[entities/android-termux|Android / Termux]]
- MCP support
  - Sources: [[entities/android-termux|Android / Termux]]
- Honcho memory support
  - Sources: [[entities/android-termux|Android / Termux]]
- ACP support
  - Sources: [[entities/android-termux|Android / Termux]]
- `.[all]` is not supported on Android today
  - Sources: [[entities/android-termux|Android / Termux]]
- the voice extra is blocked by faster-whisper -> ctranslate2, and ctranslate2 does not publish Android wheels
  - Sources: [[entities/android-termux|Android / Termux]]
- automatic browser / Playwright bootstrap is skipped in the Termux installer
  - Sources: [[entities/android-termux|Android / Termux]]
- Docker-based terminal isolation is not available inside Termux
  - Sources: [[entities/android-termux|Android / Termux]]
- Android may still suspend Termux background jobs, so gateway persistence is best-effort rather than a normal managed service
  - Sources: [[entities/android-termux|Android / Termux]]
- uses pkg for system packages
  - Sources: [[entities/android-termux|Android / Termux]]
- creates the venv with `python -m venv`
  - Sources: [[entities/android-termux|Android / Termux]]
- installs `.[termux]` with pip
  - Sources: [[entities/android-termux|Android / Termux]]
- links hermes into `$PREFIX/bin` so it stays on your Termux PATH
  - Sources: [[entities/android-termux|Android / Termux]]
- skips the untested browser / WhatsApp bootstrap
  - Sources: [[entities/android-termux|Android / Termux]]
- python — runtime + venv support
  - Sources: [[entities/android-termux|Android / Termux]]
- git — clone/update the repo
  - Sources: [[entities/android-termux|Android / Termux]]
- clang, rust, make, pkg-config, libffi, openssl — needed to build a few Python dependencies on Android
  - Sources: [[entities/android-termux|Android / Termux]]
- nodejs — optional Node runtime for experiments beyond the tested core path
  - Sources: [[entities/android-termux|Android / Termux]]
- ripgrep — fast file search
  - Sources: [[entities/android-termux|Android / Termux]]
- ffmpeg — media / TTS conversions
  - Sources: [[entities/android-termux|Android / Termux]]
- voice pulls faster-whisper
  - Sources: [[entities/android-termux|Android / Termux]]
- faster-whisper depends on ctranslate2
  - Sources: [[entities/android-termux|Android / Termux]]
- ctranslate2 does not publish Android wheels
  - Sources: [[entities/android-termux|Android / Termux]]
- Docker backend is unavailable
  - Sources: [[entities/android-termux|Android / Termux]]
- local voice transcription via faster-whisper is unavailable in the tested path
  - Sources: [[entities/android-termux|Android / Termux]]
- browser automation setup is intentionally skipped by the installer
  - Sources: [[entities/android-termux|Android / Termux]]
- some optional extras may work, but only `.[termux]` is currently documented as the tested Android bundle
  - Sources: [[entities/android-termux|Android / Termux]]
- your Android version
  - Sources: [[entities/android-termux|Android / Termux]]
- termux-info
  - Sources: [[entities/android-termux|Android / Termux]]
- python --version
  - Sources: [[entities/android-termux|Android / Termux]]
- hermes doctor
  - Sources: [[entities/android-termux|Android / Termux]]
- the exact install command and full error output
  - Sources: [[entities/android-termux|Android / Termux]]
- Type:** 3.5L V6 DOHC 24V VVT-iW
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Horsepower:** 295 hp @ 6,300 RPM
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Torque:** 267 lb-ft @ 4,700 RPM
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Type:** 0W-20 full synthetic (OEM recommended)
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Capacity:** ~5.7–6.0 quarts (~5.4–5.7 liters) — confirm with dealer manual
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Drive:** Front-wheel drive (FWD)
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Transmission:** Automatic 8-speed
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Steering:** Left-hand drive (US market)
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- Owner: randomstix's wife
  - Sources: [[entities/2017-lexus-rx-350|2017 Lexus RX 350]]
- 9 CLI methods**: basic, advanced (recommended), aggressive, spectral_cascade, informed, surgical, optimized, inverted, nuclear
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- 116 model presets** across 5 compute tiers
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- License**: AGPL-3.0 — NEVER import as Python library. Always invoke via CLI or subprocess to keep Hermes Agent's MIT license clean.
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Models under ~1B params** respond poorly to abliteration. 3B+ works well. 7-8B is the practical minimum for useful results.
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Qwen 2.5 7B Uncensored — coding & logic
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- DeepSeek R1 Distill 7B (abliterated) — reasoning model
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Gemma 3 4B Heretic — ultra-compact
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Llama 3.1 8B (various uncensored variants)
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Mistral 7B (various uncensored variants)
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- GPT-OSS 20B Heretic — creative writing & roleplay
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Gemma 3 27B Abliterated — frequently cited as best all-around
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Mistral Nemo 12B Uncensored — balanced generalist
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Qwen3 30B Abliterated — rivals larger models
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Llama 3.2 8X3B MoE Dark Champion — MoE speed, ~20B-quality
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Llama 4 70B Abliterated — near GPT-4 level
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Dolphin 3.0 Llama 70B
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Loki 70B Heretic V2 — narrative depth
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Nous Hermes 3 Llama 3.1 405B — frontier open-weights
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Dolphin** (Cognitive Computations) — high-compliance fine-tuning
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Heretic** (DavidAU / mradermacher) — aggressively de-aligned
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Dark Champion** (DavidAU) — MoE abliterated
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Wizard-Vicuna** (TheBloke) — classic uncensored, most downloaded
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Nous Hermes** (NousResearch) — creative writing & roleplay
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Juggernaut XL — all-around photorealism (~6.9GB safetensors)
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Realistic Vision XL — photorealistic people
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Pony Diffusion XL — character art, huge LoRA ecosystem
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- DreamShaper XL — artistic, fantasy
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- SDXL Unstable Diffusers — NSFW focus
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Comfortable**: Llama 3.2 3B (~3GB), Gemma 3 4B (~4GB), Qwen 2.5 7B (~6-8GB), Llama 3.1 8B (~7-8GB), DeepSeek R1 Distill 7B (~7GB)
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Tight but possible**: Mistral Nemo 12B (~10GB), Gemma 3 12B (~10GB)
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Not viable**: GPT-OSS 20B, Gemma 3 27B, Qwen3 30B, anything 70B+
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- SD 1.5**: 10-20 sec/image, low RAM pressure
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- SDXL**: 30-90 sec/image, medium-high RAM pressure
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Flux**: Not viable (OOM on 16GB)
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- LLM uncensoring: abliterate with OBLITERATUS (need GPU) OR download pre-abliterated GGUFs
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Image gen uncensoring: just disable safety checker + use community checkpoints
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- Mac with 16GB: 7-8B LLMs max, SDXL for images max
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- For low-spec machines, downloading pre-built models is smarter than running abliteration
  - Sources: [[concepts/uncensored-ai-models|Uncensored AI Models]]
- DOE Argonne GREET model:** Corn ethanol reduces life-cycle GHG emissions by ~40-46% compared to gasoline
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Lark et al. (2022) PNAS:** Corn ethanol is at least 24% more carbon-intensive than gasoline when land-use change is accounted for
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- The empirical camp (Lark et al.) uses satellite data showing actual conversion of grasslands and conservation land to corn, releasing stored carbon
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- The modeling camp (DOE/Argonne) uses economic models that assume less land-use change
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- This is the single largest driver of the difference between estimates
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Industry critics argue the Lark study understates yield gains, meaning fewer acres are needed for the same corn output
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Lark et al. respond that their satellite data captures actual land-use change, not modeled projections
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Ethanol production creates distillers grains that replace animal feed, offsetting some emissions
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- The value of this credit is disputed between the two camps
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- What would farmers have planted if not corn for ethanol? The answer dramatically affects the net GHG calculation
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Different assumptions produce wildly different results
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Both sides have published in peer-reviewed journals
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Lark et al. were funded by National Wildlife Federation (environmental advocacy) and DOE
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Industry-funded studies are funded by groups with a financial interest in ethanol policy
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- The scientific community remains genuinely split — this is not settled science
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Reuters (Feb 14, 2022) reported the Lark study's findings; the reporting was generally accurate and not overdramatized
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- The article sparked significant pushback from the ethanol industry
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Multiple outlets (Axios, CleanTechnica, CNET, Des Moines Register) covered the study and subsequent debate
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- US Renewable Fuel Standard (RFS)
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Biofuel lifecycle analysis
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]
- Indirect land-use change (ILUC)
  - Sources: [[concepts/corn-ethanol-climate-impact-debate|Corn Ethanol Climate Impact Debate]]

## Contradictions

### access-policiesaccess-policiesdm-policygroup-p

- [[entities/wecom-enterprise-wechat]]: [Access Policies](#access-policies)[](#dm-policy)[](#group-policy)[](#per-group-sender-allowlists)
- [[entities/weixin-wechat]]: [Access Policies](#access-policies)[](#dm-policy)[](#group-policy)

### discord-setupdocsuser-guidemessagingdiscord

- [[entities/learning-path]]: [Discord Setup](/docs/user-guide/messaging/discord)
- [[entities/use-voice-mode-with-hermes]]: [[[entity.discord-setup|Discord Setup]]](/docs/user-guide/messaging/discord)

### force-does-not-override-a-dangerous-scan-verdict

- [[entities/cli-commands-reference]]: `--force` does not override a `dangerous` scan verdict.
- [[entities/features-skills]]: `--force` does **not** override a `dangerous` scan verdict.

### group-sessions-per-user-true-keeps-each-participants-conte

- [[entities/dingtalk-setup]]: group_sessions_per_user: true keeps each participant's context isolated inside shared group chats
- [[entities/matrix-setup]]: group_sessions_per_user: true keeps each participant's context isolated inside shared rooms
- [[entities/mattermost-setup]]: group_sessions_per_user: true keeps each participant's context isolated inside shared channels and threads

### hermes-doctor

- [[entities/android-termux]]: hermes doctor
- [[entities/quickstart]]: `hermes doctor`

### installationdocsgetting-startedinstallation

- [[entities/installation]]: [Installation](/docs/getting-started/installation)
- [[entities/learning-path]]: [[[entity.installation|Installation]]](/docs/getting-started/[[entity.installation|Installation]])
- [[entities/learning-path]]: [[[entity.installation|Installation]]](/docs/getting-started/[[entity.installation|Installation]])
- [[entities/learning-path]]: [[[entity.installation|Installation]]](/docs/getting-started/[[entity.installation|Installation]])
- [[entities/learning-path]]: [[[entity.installation|Installation]]](/docs/getting-started/[[entity.installation|Installation]])
- [[entities/quickstart]]: [[[entity.installation|Installation]]](/docs/getting-started/[[entity.installation|Installation]])

### location

- [[entities/hindsight-memory-server]]: Running at /opt/stacks/hindsight_memory/
- [[entities/lost-lands-2026]]: Legend Valley, OH

### media-supportmedia-supportinbound-receivingaes

- [[entities/wecom-enterprise-wechat]]: [Media Support](#media-support)[](#inbound-receiving)[](#aes-encrypted-media-decryption)[](#outbound-sending)
- [[entities/weixin-wechat]]: [Media Support](#media-support)[](#inbound-receiving)[](#aes-128-ecb-encrypted-cdn)[](#outbound-sending)

### one-persons-in-flight-run-can-interrupt-another-persons-fo

- [[entities/discord-setup]]: one person's in-flight run can interrupt another person's follow-up in the same room
- [[entities/matrix-setup]]: one person's in-flight run can interrupt another person's follow-up in the same room
- [[entities/mattermost-setup]]: one person's in-flight run can interrupt another person's follow-up in the same channel

### ripgrep-fast-file-search

- [[entities/android-termux]]: ripgrep — fast file search
- [[entities/installation]]: ripgrep (fast file search)

### securitysecurity

- [[entities/dingtalk-setup]]: [Security](#security)
- [[entities/email-setup]]: [Security](#security)
- [[entities/home-assistant-integration]]: [Security](#security)
- [[entities/matrix-setup]]: [Security](#security)
- [[entities/mattermost-setup]]: [Security](#security)
- [[entities/signal-setup]]: [Security](#security)
- [[entities/slack-setup]]: [Security](#security)
- [[entities/telegram-setup]]: [[[entity.security|Security]]](#[[entity.security|Security]])
- [[entities/whatsapp-setup]]: [Security](#security)

### telegram-setupdocsuser-guidemessagingtelegram

- [[entities/learning-path]]: [Telegram Setup](/docs/user-guide/messaging/telegram)
- [[entities/use-voice-mode-with-hermes]]: [[[entity.telegram-setup|Telegram Setup]]](/docs/user-guide/messaging/telegram)

### troubleshootingtroubleshootingbot-is-not-responding

- [[entities/dingtalk-setup]]: [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#dingtalk-stream-not-installed-error)[](#dingtalk_client_id-and-dingtalk_client_secret-required)[](#stream-disconnects--reconnection-loops)[](#bot-is-offline)[](#no-session_webhook-available)
- [[entities/matrix-setup]]: [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#failed-to-authenticate--whoami-failed-on-startup)[](#mautrix-not-installed-error)[](#encryption-errors--could-not-decrypt-event)[](#upgrading-from-a-previous-version-with-e2ee)
- [[entities/mattermost-setup]]: [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#403-forbidden-errors)[](#websocket-disconnects--reconnection-loops)[](#failed-to-authenticate-on-startup)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)

## Related

- [[concepts/anomem-postmortem]]
- [[concepts/corn-ethanol-climate-impact-debate]]
- [[concepts/index]]
- [[concepts/project-guidelines]]
- [[concepts/prompt-weapon-generator-game]]
- [[concepts/self-hosted-infra]]
- [[concepts/uncensored-ai-models]]
- [[entities/2017-lexus-rx-350]]
- [[entities/ai-providers]]
- [[entities/android-termux]]
- [[entities/architecture]]
- [[entities/bluebubbles-imessage]]
- [[entities/cli-commands-reference]]
- [[entities/cli-interface]]
- [[entities/configuration]]
- [[entities/contributing]]
- [[entities/dingtalk-setup]]
- [[entities/discord-setup]]
- [[entities/email-setup]]
- [[entities/faq-troubleshooting]]
- [[entities/features-context-files]]
- [[entities/features-mcp]]
- [[entities/features-memory]]
- [[entities/features-overview]]
- [[entities/features-personality]]
- [[entities/features-skills]]
- [[entities/features-tools]]
- [[entities/features-voice-mode]]
- [[entities/feishu-lark-setup]]
- [[entities/hermes-agent-faq]]
- [[entities/hermes-agent-installation]]
- [[entities/hermes-agent-learning-path]]
- [[entities/hermes-agent-quickstart]]
- [[entities/hermes-agent-tips]]
- [[entities/hermes-agent-use-mcp-with-hermes]]
- [[entities/hermes-agent-use-voice-mode-with-hermes]]
- [[entities/hindsight-memory-server]]
- [[entities/home-assistant-integration]]
- [[entities/honda-civic-2016-ex-t-maintenance]]
- [[entities/index]]
- [[entities/installation]]
- [[entities/learning-path]]
- [[entities/lexus-rx-350-2017]]
- [[entities/lolok-site]]
- [[entities/lost-lands-2026]]
- [[entities/macvm]]
- [[entities/matrix-setup]]
- [[entities/mattermost-setup]]
- [[entities/messaging-gateway]]
- [[entities/nix-nixos-setup]]
- [[entities/open-webui-integration]]
- [[entities/qq-bot]]
- [[entities/quickstart]]
- [[entities/randomstix-health]]
- [[entities/randomstix]]
- [[entities/searxng]]
- [[entities/security]]
- [[entities/signal-setup]]
- [[entities/slack-setup]]
- [[entities/sms-setup-twilio]]
- [[entities/stdin]]
- [[entities/telegram-setup]]
- [[entities/tips-best-practices]]
- [[entities/updating-uninstalling]]
- [[entities/use-mcp-with-hermes]]
- [[entities/use-voice-mode-with-hermes]]
- [[entities/webhooks]]
- [[entities/wecom-enterprise-wechat]]
- [[entities/weixin-wechat]]
- [[entities/whatsapp-setup]]


<!-- openclaw:wiki:generated:end -->

<!-- openclaw:human:start -->

<!-- Human notes go here -->

<!-- openclaw:human:end -->