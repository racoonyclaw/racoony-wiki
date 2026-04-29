---
pageType: entity
id: entity.cli-commands-reference
title: CLI Commands Reference
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-cli-commands.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-cli-commands.md
updatedAt: '2026-04-24T15:05:24.370242+00:00'
sourceIds:
- githubcom
- mintlifycom
sources:
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent/edit/main/website/docs/reference/cli-commands.md
  title: '[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/reference/cli-c'
- sourceId: mintlifycom
  sourceType: web
  sourcePath: https://mintlify.com/docs
  title: mintlify.com
claims:
- id: add-a-new-provider-openrouter-anthropic-copilot-deepse
  text: add a new provider** (OpenRouter, Anthropic, Copilot, DeepSeek, custom, etc.)
  status: supported
  confidence: null
- id: log-into-oauth-backed-providers-anthropic-copilot-codex
  text: log into OAuth-backed providers (Anthropic, Copilot, Codex, Nous Portal)
  status: supported
  confidence: null
- id: enter-or-update-api-keys
  text: enter or update API keys
  status: supported
  confidence: null
- id: pick-from-provider-specific-model-lists
  text: pick from provider-specific model lists
  status: supported
  confidence: null
- id: configure-a-customself-hosted-endpoint
  text: configure a custom/self-hosted endpoint
  status: supported
  confidence: null
- id: save-the-new-default-into-config
  text: save the new default into config
  status: supported
  confidence: null
- id: hermes-dump----version-080-202648-af4abd2f
  text: 'hermes dump ---version:          0.8.0 (2026.4.8) [af4abd2f]os:               Linux
    6.14.0-37-generic x86_64python:           3.11.14openai_sdk:       2.24.0profile:          defaulthermes_home:      ~/.hermesmodel:            anthropic/claude-opus-4.6provider:         openrouterterminal:         localapi_keys:  openrouter           set  openai               not
    set  anthropic            set  nous                 not set  firecrawl            set  ...features:  toolsets:           all  mcp_servers:        0  memory_provider:    built-in  gateway:            running
    (systemd)  platforms:          telegram, discord  cron_jobs:          3 active
    / 5 total  skills:             42config_overrides:  agent.max_turns: 250  compression.threshold:
    0.85  display.streaming: True--- end dump ---'
  status: supported
  confidence: null
- id: reporting-a-bug-on-github-paste-the-dump-into-your-issue
  text: "Reporting a bug on GitHub \u2014 paste the dump into your issue"
  status: supported
  confidence: null
- id: asking-for-help-in-discord-share-it-in-a-code-block
  text: "Asking for help in Discord \u2014 share it in a code block"
  status: supported
  confidence: null
- id: comparing-your-setup-to-someone-elsex27s
  text: Comparing your setup to someone else&#x27;s
  status: supported
  confidence: null
- id: quick-sanity-check-when-something-isnx27t-working
  text: Quick sanity check when something isn&#x27;t working
  status: supported
  confidence: null
- id: force-can-override-non-dangerous-policy-blocks-for-third
  text: '`--force` can override non-dangerous policy blocks for third-party/community
    skills.'
  status: supported
  confidence: null
- id: force-does-not-override-a-dangerous-scan-verdict
  text: '`--force` does not override a `dangerous` scan verdict.'
  status: supported
  confidence: null
- id: source-skills-sh-searches-the-public-skillssh-directo
  text: '`--source skills-sh` searches the public `skills.sh` directory.'
  status: supported
  confidence: null
- id: source-well-known-lets-you-point-hermes-at-a-site-exposi
  text: '`--source well-known` lets you point Hermes at a site exposing `/.well-known/skills/index.json`.'
  status: supported
  confidence: null
- id: general-plugins-multi-select-checkboxes-to-enabledisabl
  text: "General Plugins** \u2014 multi-select checkboxes to enable/disable installed\
    \ plugins"
  status: supported
  confidence: null
- id: provider-plugins-single-select-configuration-for-memory
  text: "Provider Plugins** \u2014 single-select configuration for Memory Provider\
    \ and Context Engine. Press ENTER on a category to open a radio picker."
  status: supported
  confidence: null
- id: memoryprovider-active-memory-provider-empty-built-in
  text: "`memory.provider` \u2014 active memory provider (empty = built-in only)"
  status: supported
  confidence: null
- id: contextengine-active-context-engine-quotcompressor
  text: "`context.engine` \u2014 active context engine (`&quot;compressor&quot;` =\
    \ built-in default)"
  status: supported
  confidence: null
- id: slash-commands-referencedocsreferenceslash-commands
  text: '[Slash Commands Reference](/docs/reference/slash-commands)'
  status: supported
  confidence: null
- id: cli-interfacedocsuser-guidecli
  text: '[CLI Interface](/docs/user-guide/cli)'
  status: supported
  confidence: null
- id: sessionsdocsuser-guidesessions
  text: '[Sessions](/docs/user-guide/sessions)'
  status: supported
  confidence: null
- id: skills-systemdocsuser-guidefeaturesskills
  text: '[Skills System](/docs/user-guide/features/skills)'
  status: supported
  confidence: null
- id: skins-amp-themesdocsuser-guidefeaturesskins
  text: '[Skins &amp; Themes](/docs/user-guide/features/skins)'
  status: supported
  confidence: null
---

This page covers the **terminal commands** you run from your shell.

For in-chat slash commands, see [Slash Commands Reference](/docs/reference/slash-commands).

## Global entrypoint

```
hermes [global-options] &lt;command&gt; [subcommand/options]
```
### Global options

OptionDescription`--version`, `-V`Show version and exit.`--profile &lt;name&gt;`, `-p &lt;name&gt;`Select which Hermes profile to use for this invocation. Overrides the sticky default set by `hermes profile use`.`--resume &lt;session&gt;`, `-r &lt;session&gt;`Resume a previous session by ID or title.`--continue [name]`, `-c [name]`Resume the most recent session, or the most recent session matching a title.`--worktree`, `-w`Start in an isolated git worktree for parallel-agent workflows.`--yolo`Bypass dangerous-command approval prompts.`--pass-session-id`Include the session ID in the agent&#x27;s system prompt.`--ignore-user-config`Ignore `~/.hermes/config.yaml` and fall back to built-in defaults. Credentials in `.env` are still loaded.`--ignore-rules`Skip auto-injection of `AGENTS.md`, `SOUL.md`, `.cursorrules`, memory, and preloaded skills.`--tui`Launch the [TUI](/docs/user-guide/tui) instead of the classic CLI. Equivalent to `HERMES_TUI=1`.`--dev`With `--tui`: run the TypeScript sources directly via `tsx` instead of the prebuilt bundle (for TUI contributors).
## Top-level commands

CommandPurpose`hermes chat`Interactive or one-shot chat with the agent.`hermes model`Interactively choose the default provider and model.`hermes gateway`Run or manage the messaging gateway service.`hermes setup`Interactive setup wizard for all or part of the configuration.`hermes whatsapp`Configure and pair the WhatsApp bridge.`hermes auth`Manage credentials — add, list, remove, reset, set strategy. Handles OAuth flows for Codex/Nous/Anthropic.`hermes login` / `logout`**Deprecated** — use `hermes auth` instead.`hermes status`Show agent, auth, and platform status.`hermes cron`Inspect and tick the cron scheduler.`hermes webhook`Manage dynamic webhook subscriptions for event-driven activation.`hermes doctor`Diagnose config and dependency issues.`hermes dump`Copy-pasteable setup summary for support/debugging.`hermes debug`Debug tools — upload logs and system info for support.`hermes backup`Back up Hermes home directory to a zip file.`hermes import`Restore a Hermes backup from a zip file.`hermes logs`View, tail, and filter agent/gateway/error log files.`hermes config`Show, edit, migrate, and query configuration files.`hermes pairing`Approve or revoke messaging pairing codes.`hermes skills`Browse, install, publish, audit, and configure skills.`hermes honcho`Manage Honcho cross-session memory integration.`hermes memory`Configure external memory provider.`hermes acp`Run Hermes as an ACP server for editor integration.`hermes mcp`Manage MCP server configurations and run Hermes as an MCP server.`hermes plugins`Manage Hermes Agent plugins (install, enable, disable, remove).`hermes tools`Configure enabled tools per platform.`hermes sessions`Browse, export, prune, rename, and delete sessions.`hermes insights`Show token/cost/activity analytics.`hermes claw`OpenClaw migration helpers.`hermes dashboard`Launch the web dashboard for managing config, API keys, and sessions.`hermes profile`Manage profiles — multiple isolated Hermes instances.`hermes completion`Print shell completion scripts (bash/zsh).`hermes version`Show version information.`hermes update`Pull latest code and reinstall dependencies.`hermes uninstall`Remove Hermes from the system.
## `hermes chat`

```
hermes chat [options]
```
Common options:

OptionDescription`-q`, `--query &quot;...&quot;`One-shot, non-interactive prompt.`-m`, `--model &lt;model&gt;`Override the model for this run.`-t`, `--toolsets &lt;csv&gt;`Enable a comma-separated set of toolsets.`--provider &lt;provider&gt;`Force a provider: `auto`, `openrouter`, `nous`, `openai-codex`, `copilot-acp`, `copilot`, `anthropic`, `gemini`, `google-gemini-cli`, `huggingface`, `zai`, `kimi-coding`, `kimi-coding-cn`, `minimax`, `minimax-cn`, `kilocode`, `xiaomi`, `arcee`, `alibaba`, `deepseek`, `nvidia`, `ollama-cloud`, `xai` (alias `grok`), `qwen-oauth`, `bedrock`, `opencode-zen`, `opencode-go`, `ai-gateway`.`-s`, `--skills &lt;name&gt;`Preload one or more skills for the session (can be repeated or comma-separated).`-v`, `--verbose`Verbose output.`-Q`, `--quiet`Programmatic mode: suppress banner/spinner/tool previews.`--image &lt;path&gt;`Attach a local image to a single query.`--resume &lt;session&gt;` / `--continue [name]`Resume a session directly from `chat`.`--worktree`Create an isolated git worktree for this run.`--checkpoints`Enable filesystem checkpoints before destructive file changes.`--yolo`Skip approval prompts.`--pass-session-id`Pass the session ID into the system prompt.`--ignore-user-config`Ignore `~/.hermes/config.yaml` and use built-in defaults. Credentials in `.env` are still loaded. Useful for isolated CI runs, reproducible bug reports, and third-party integrations.`--ignore-rules`Skip auto-injection of `AGENTS.md`, `SOUL.md`, `.cursorrules`, persistent memory, and preloaded skills. Combine with `--ignore-user-config` for a fully isolated run.`--source &lt;tag&gt;`Session source tag for filtering (default: `cli`). Use `tool` for third-party integrations that should not appear in user session lists.`--max-turns &lt;N&gt;`Maximum tool-calling iterations per conversation turn (default: 90, or `agent.max_turns` in config).
Examples:

```
hermeshermes chat -q &quot;Summarize the latest PRs&quot;hermes chat --provider openrouter --model anthropic/claude-sonnet-4.6hermes chat --toolsets web,terminal,skillshermes chat --quiet -q &quot;Return only JSON&quot;hermes chat --worktree -q &quot;Review this repo and open a PR&quot;hermes chat --ignore-user-config --ignore-rules -q &quot;Repro without my personal setup&quot;
```
## `hermes model`

Interactive provider + model selector. **This is the command for adding new providers, setting up API keys, and running OAuth flows.** Run it from your terminal — not from inside an active Hermes chat session.

```
hermes model
```
Use this when you want to:

- **add a new provider** (OpenRouter, Anthropic, Copilot, DeepSeek, custom, etc.)

- log into OAuth-backed providers (Anthropic, Copilot, Codex, Nous Portal)

- enter or update API keys

- pick from provider-specific model lists

- configure a custom/self-hosted endpoint

- save the new default into config

hermes model vs /model — know the difference**`hermes model`** (run from your terminal, outside any Hermes session) is the **full provider setup wizard**. It can add new providers, run OAuth flows, prompt for API keys, and configure endpoints.
**`/model`** (typed inside an active Hermes chat session) can only **switch between providers and models you&#x27;ve already set up**. It cannot add new providers, run OAuth, or prompt for API keys.
**If you need to add a new provider:** Exit your Hermes session first (`Ctrl+C` or `/quit`), then run `hermes model` from your terminal prompt.

### `/model` slash command (mid-session)

Switch between already-configured models without leaving a session:

```
/model                              # Show current model and available options/model claude-sonnet-4              # Switch model (auto-detects provider)/model zai:glm-5                    # Switch provider and model/model custom:qwen-2.5              # Use model on your custom endpoint/model custom                       # Auto-detect model from custom endpoint/model custom:local:qwen-2.5        # Use a named custom provider/model openrouter:anthropic/claude-sonnet-4  # Switch back to cloud
```
By default, `/model` changes apply **to the current session only**. Add `--global` to persist the change to `config.yaml`:

```
/model claude-sonnet-4 --global     # Switch and save as new default
```
What if I only see OpenRouter models?If you&#x27;ve only configured OpenRouter, `/model` will only show OpenRouter models. To add another provider (Anthropic, DeepSeek, Copilot, etc.), exit your session and run `hermes model` from the terminal.

Provider and base URL changes are persisted to `config.yaml` automatically. When switching away from a custom endpoint, the stale base URL is cleared to prevent it leaking into other providers.

## `hermes gateway`

```
hermes gateway &lt;subcommand&gt;
```
Subcommands:

SubcommandDescription`run`Run the gateway in the foreground. Recommended for WSL, Docker, and Termux.`start`Start the installed systemd/launchd background service.`stop`Stop the service (or foreground process).`restart`Restart the service.`status`Show service status.`install`Install as a systemd (Linux) or launchd (macOS) background service.`uninstall`Remove the installed service.`setup`Interactive messaging-platform setup.
WSL usersUse `hermes gateway run` instead of `hermes gateway start` — WSL&#x27;s systemd support is unreliable. Wrap it in tmux for persistence: `tmux new -s hermes &#x27;hermes gateway run&#x27;`. See [WSL FAQ](/docs/reference/faq#wsl-gateway-keeps-disconnecting-or-hermes-gateway-start-fails) for details.

## `hermes setup`

```
hermes setup [model|tts|terminal|gateway|tools|agent] [--non-interactive] [--reset]
```
Use the full wizard or jump into one section:

SectionDescription`model`Provider and model setup.`terminal`Terminal backend and sandbox setup.`gateway`Messaging platform setup.`tools`Enable/disable tools per platform.`agent`Agent behavior settings.
Options:

OptionDescription`--non-interactive`Use defaults / environment values without prompts.`--reset`Reset configuration to defaults before setup.
## `hermes whatsapp`

```
hermes whatsapp
```
Runs the WhatsApp pairing/setup flow, including mode selection and QR-code pairing.

## `hermes login` / `hermes logout` *(Deprecated)*

caution`hermes login` has been removed. Use `hermes auth` to manage OAuth credentials, `hermes model` to select a provider, or `hermes setup` for full interactive setup.

## `hermes auth`

Manage credential pools for same-provider key rotation. See [Credential Pools](/docs/user-guide/features/credential-pools) for full documentation.

```
hermes auth                                              # Interactive wizardhermes auth list                                         # Show all poolshermes auth list openrouter                              # Show specific providerhermes auth add openrouter --api-key sk-or-v1-xxx        # Add API keyhermes auth add anthropic --type oauth                   # Add OAuth credentialhermes auth remove openrouter 2                          # Remove by indexhermes auth reset openrouter                             # Clear cooldowns
```
Subcommands: `add`, `list`, `remove`, `reset`. When called with no subcommand, launches the interactive management wizard.

## `hermes status`

```
hermes status [--all] [--deep]
```
OptionDescription`--all`Show all details in a shareable redacted format.`--deep`Run deeper checks that may take longer.
## `hermes cron`

```
hermes cron &lt;list|create|edit|pause|resume|run|remove|status|tick&gt;
```
SubcommandDescription`list`Show scheduled jobs.`create` / `add`Create a scheduled job from a prompt, optionally attaching one or more skills via repeated `--skill`.`edit`Update a job&#x27;s schedule, prompt, name, delivery, repeat count, or attached skills. Supports `--clear-skills`, `--add-skill`, and `--remove-skill`.`pause`Pause a job without deleting it.`resume`Resume a paused job and compute its next future run.`run`Trigger a job on the next scheduler tick.`remove`Delete a scheduled job.`status`Check whether the cron scheduler is running.`tick`Run due jobs once and exit.
## `hermes webhook`

```
hermes webhook &lt;subscribe|list|remove|test&gt;
```
Manage dynamic webhook subscriptions for event-driven agent activation. Requires the webhook platform to be enabled in config — if not configured, prints setup instructions.

SubcommandDescription`subscribe` / `add`Create a webhook route. Returns the URL and HMAC secret to configure on your service.`list` / `ls`Show all agent-created subscriptions.`remove` / `rm`Delete a dynamic subscription. Static routes from config.yaml are not affected.`test`Send a test POST to verify a subscription is working.
### `hermes webhook subscribe`

```
hermes webhook subscribe &lt;name&gt; [options]
```
OptionDescription`--prompt`Prompt template with `{dot.notation}` payload references.`--events`Comma-separated event types to accept (e.g. `issues,pull_request`). Empty = all.`--description`Human-readable description.`--skills`Comma-separated skill names to load for the agent run.`--deliver`Delivery target: `log` (default), `telegram`, `discord`, `slack`, `github_comment`.`--deliver-chat-id`Target chat/channel ID for cross-platform delivery.`--secret`Custom HMAC secret. Auto-generated if omitted.
Subscriptions persist to `~/.hermes/webhook_subscriptions.json` and are hot-reloaded by the webhook adapter without a gateway restart.

## `hermes doctor`

```
hermes doctor [--fix]
```
OptionDescription`--fix`Attempt automatic repairs where possible.
## `hermes dump`

```
hermes dump [--show-keys]
```
Outputs a compact, plain-text summary of your entire Hermes setup. Designed to be copy-pasted into Discord, GitHub issues, or Telegram when asking for support — no ANSI colors, no special formatting, just data.

OptionDescription`--show-keys`Show redacted API key prefixes (first and last 4 characters) instead of just `set`/`not set`.
### What it includes

SectionDetails**Header**Hermes version, release date, git commit hash**Environment**OS, Python version, OpenAI SDK version**Identity**Active profile name, HERMES_HOME path**Model**Configured default model and provider**Terminal**Backend type (local, docker, ssh, etc.)**API keys**Presence check for all 22 provider/tool API keys**Features**Enabled toolsets, MCP server count, memory provider**Services**Gateway status, configured messaging platforms**Workload**Cron job counts, installed skill count**Config overrides**Any config values that differ from defaults
### Example output

```
--- hermes dump ---version:          0.8.0 (2026.4.8) [af4abd2f]os:               Linux 6.14.0-37-generic x86_64python:           3.11.14openai_sdk:       2.24.0profile:          defaulthermes_home:      ~/.hermesmodel:            anthropic/claude-opus-4.6provider:         openrouterterminal:         localapi_keys:  openrouter           set  openai               not set  anthropic            set  nous                 not set  firecrawl            set  ...features:  toolsets:           all  mcp_servers:        0  memory_provider:    built-in  gateway:            running (systemd)  platforms:          telegram, discord  cron_jobs:          3 active / 5 total  skills:             42config_overrides:  agent.max_turns: 250  compression.threshold: 0.85  display.streaming: True--- end dump ---
```
### When to use

- Reporting a bug on GitHub — paste the dump into your issue

- Asking for help in Discord — share it in a code block

- Comparing your setup to someone else&#x27;s

- Quick sanity check when something isn&#x27;t working

tip`hermes dump` is specifically designed for sharing. For interactive diagnostics, use `hermes doctor`. For a visual overview, use `hermes status`.

## `hermes debug`

```
hermes debug share [options]
```
Upload a debug report (system info + recent logs) to a paste service and get a shareable URL. Useful for quick support requests — includes everything a helper needs to diagnose your issue.

OptionDescription`--lines &lt;N&gt;`Number of log lines to include per log file (default: 200).`--expire &lt;days&gt;`Paste expiry in days (default: 7).`--local`Print the report locally instead of uploading.
The report includes system info (OS, Python version, Hermes version), recent agent and gateway logs (512 KB limit per file), and redacted API key status. Keys are always redacted — no secrets are uploaded.

Paste services tried in order: paste.rs, dpaste.com.

### Examples

```
hermes debug share              # Upload debug report, print URLhermes debug share --lines 500  # Include more log lineshermes debug share --expire 30  # Keep paste for 30 dayshermes debug share --local      # Print report to terminal (no upload)
```
## `hermes backup`

```
hermes backup [options]
```
Create a zip archive of your Hermes configuration, skills, sessions, and data. The backup excludes the hermes-agent codebase itself.

OptionDescription`-o`, `--output &lt;path&gt;`Output path for the zip file (default: `~/hermes-backup-&lt;timestamp&gt;.zip`).`-q`, `--quick`Quick snapshot: only critical state files (config.yaml, state.db, .env, auth, cron jobs). Much faster than a full backup.`-l`, `--label &lt;name&gt;`Label for the snapshot (only used with `--quick`).
The backup uses SQLite&#x27;s `backup()` API for safe copying, so it works correctly even when Hermes is running (WAL-mode safe).

### Examples

```
hermes backup                           # Full backup to ~/hermes-backup-*.ziphermes backup -o /tmp/hermes.zip        # Full backup to specific pathhermes backup --quick                   # Quick state-only snapshothermes backup --quick --label &quot;pre-upgrade&quot;  # Quick snapshot with label
```
## `hermes import`

```
hermes import &lt;zipfile&gt; [options]
```
Restore a previously created Hermes backup into your Hermes home directory.

OptionDescription`-f`, `--force`Overwrite existing files without confirmation.
## `hermes logs`

```
hermes logs [log_name] [options]
```
View, tail, and filter Hermes log files. All logs are stored in `~/.hermes/logs/` (or `&lt;profile&gt;/logs/` for non-default profiles).

### Log files

NameFileWhat it captures`agent` (default)`agent.log`All agent activity — API calls, tool dispatch, session lifecycle (INFO and above)`errors``errors.log`Warnings and errors only — a filtered subset of agent.log`gateway``gateway.log`Messaging gateway activity — platform connections, message dispatch, webhook events
### Options

OptionDescription`log_name`Which log to view: `agent` (default), `errors`, `gateway`, or `list` to show available files with sizes.`-n`, `--lines &lt;N&gt;`Number of lines to show (default: 50).`-f`, `--follow`Follow the log in real time, like `tail -f`. Press Ctrl+C to stop.`--level &lt;LEVEL&gt;`Minimum log level to show: `DEBUG`, `INFO`, `WARNING`, `ERROR`, `CRITICAL`.`--session &lt;ID&gt;`Filter lines containing a session ID substring.`--since &lt;TIME&gt;`Show lines from a relative time ago: `30m`, `1h`, `2d`, etc. Supports `s` (seconds), `m` (minutes), `h` (hours), `d` (days).`--component &lt;NAME&gt;`Filter by component: `gateway`, `agent`, `tools`, `cli`, `cron`.
### Examples

```
# View the last 50 lines of agent.log (default)hermes logs# Follow agent.log in real timehermes logs -f# View the last 100 lines of gateway.loghermes logs gateway -n 100# Show only warnings and errors from the last hourhermes logs --level WARNING --since 1h# Filter by a specific sessionhermes logs --session abc123# Follow errors.log, starting from 30 minutes agohermes logs errors --since 30m -f# List all log files with their sizeshermes logs list
```
### Filtering

Filters can be combined. When multiple filters are active, a log line must pass **all** of them to be shown:

```
# WARNING+ lines from the last 2 hours containing session &quot;tg-12345&quot;hermes logs --level WARNING --since 2h --session tg-12345
```
Lines without a parseable timestamp are included when `--since` is active (they may be continuation lines from a multi-line log entry). Lines without a detectable level are included when `--level` is active.

### Log rotation

Hermes uses Python&#x27;s `RotatingFileHandler`. Old logs are rotated automatically — look for `agent.log.1`, `agent.log.2`, etc. The `hermes logs list` subcommand shows all log files including rotated ones.

## `hermes config`

```
hermes config &lt;subcommand&gt;
```
Subcommands:

SubcommandDescription`show`Show current config values.`edit`Open `config.yaml` in your editor.`set &lt;key&gt; &lt;value&gt;`Set a config value.`path`Print the config file path.`env-path`Print the `.env` file path.`check`Check for missing or stale config.`migrate`Add newly introduced options interactively.
## `hermes pairing`

```
hermes pairing &lt;list|approve|revoke|clear-pending&gt;
```
SubcommandDescription`list`Show pending and approved users.`approve &lt;platform&gt; &lt;code&gt;`Approve a pairing code.`revoke &lt;platform&gt; &lt;user-id&gt;`Revoke a user&#x27;s access.`clear-pending`Clear pending pairing codes.
## `hermes skills`

```
hermes skills &lt;subcommand&gt;
```
Subcommands:

SubcommandDescription`browse`Paginated browser for skill registries.`search`Search skill registries.`install`Install a skill.`inspect`Preview a skill without installing it.`list`List installed skills.`check`Check installed hub skills for upstream updates.`update`Reinstall hub skills with upstream changes when available.`audit`Re-scan installed hub skills.`uninstall`Remove a hub-installed skill.`publish`Publish a skill to a registry.`snapshot`Export/import skill configurations.`tap`Manage custom skill sources.`config`Interactive enable/disable configuration for skills by platform.
Common examples:

```
hermes skills browsehermes skills browse --source officialhermes skills search react --source skills-shhermes skills search https://mintlify.com/docs --source well-knownhermes skills inspect official/security/1passwordhermes skills inspect skills-sh/vercel-labs/json-render/json-render-reacthermes skills install official/migration/openclaw-migrationhermes skills install skills-sh/anthropics/skills/pdf --forcehermes skills checkhermes skills updatehermes skills config
```
Notes:

- `--force` can override non-dangerous policy blocks for third-party/community skills.

- `--force` does not override a `dangerous` scan verdict.

- `--source skills-sh` searches the public `skills.sh` directory.

- `--source well-known` lets you point Hermes at a site exposing `/.well-known/skills/index.json`.

## `hermes honcho`

```
hermes honcho [--target-profile NAME] &lt;subcommand&gt;
```
Manage Honcho cross-session memory integration. This command is provided by the Honcho memory provider plugin and is only available when `memory.provider` is set to `honcho` in your config.

The `--target-profile` flag lets you manage another profile&#x27;s Honcho config without switching to it.

Subcommands:

SubcommandDescription`setup`Redirects to `hermes memory setup` (unified setup path).`status [--all]`Show current Honcho config and connection status. `--all` shows a cross-profile overview.`peers`Show peer identities across all profiles.`sessions`List known Honcho session mappings.`map [name]`Map the current directory to a Honcho session name. Omit `name` to list current mappings.`peer`Show or update peer names and dialectic reasoning level. Options: `--user NAME`, `--ai NAME`, `--reasoning LEVEL`.`mode [mode]`Show or set recall mode: `hybrid`, `context`, or `tools`. Omit to show current.`tokens`Show or set token budgets for context and dialectic. Options: `--context N`, `--dialectic N`.`identity [file] [--show]`Seed or show the AI peer identity representation.`enable`Enable Honcho for the active profile.`disable`Disable Honcho for the active profile.`sync`Sync Honcho config to all existing profiles (creates missing host blocks).`migrate`Step-by-step migration guide from openclaw-honcho to Hermes Honcho.
## `hermes memory`

```
hermes memory &lt;subcommand&gt;
```
Set up and manage external memory provider plugins. Available providers: honcho, openviking, mem0, hindsight, holographic, retaindb, byterover, supermemory. Only one external provider can be active at a time. Built-in memory (MEMORY.md/USER.md) is always active.

Subcommands:

SubcommandDescription`setup`Interactive provider selection and configuration.`status`Show current memory provider config.`off`Disable external provider (built-in only).
## `hermes acp`

```
hermes acp
```
Starts Hermes as an ACP (Agent Client Protocol) stdio server for editor integration.

Related entrypoints:

```
hermes-acppython -m acp_adapter
```
Install support first:

```
pip install -e &#x27;.[acp]&#x27;
```
See [ACP Editor Integration](/docs/user-guide/features/acp) and [ACP Internals](/docs/developer-guide/acp-internals).

## `hermes mcp`

```
hermes mcp &lt;subcommand&gt;
```
Manage MCP (Model Context Protocol) server configurations and run Hermes as an MCP server.

SubcommandDescription`serve [-v|--verbose]`Run Hermes as an MCP server — expose conversations to other agents.`add &lt;name&gt; [--url URL] [--command CMD] [--args ...] [--auth oauth|header]`Add an MCP server with automatic tool discovery.`remove &lt;name&gt;` (alias: `rm`)Remove an MCP server from config.`list` (alias: `ls`)List configured MCP servers.`test &lt;name&gt;`Test connection to an MCP server.`configure &lt;name&gt;` (alias: `config`)Toggle tool selection for a server.
See [MCP Config Reference](/docs/reference/mcp-config-reference), [Use MCP with Hermes](/docs/guides/use-mcp-with-hermes), and [MCP Server Mode](/docs/user-guide/features/mcp#running-hermes-as-an-mcp-server).

## `hermes plugins`

```
hermes plugins [subcommand]
```
Unified plugin management — general plugins, memory providers, and context engines in one place. Running `hermes plugins` with no subcommand opens a composite interactive screen with two sections:

- **General Plugins** — multi-select checkboxes to enable/disable installed plugins

- **Provider Plugins** — single-select configuration for Memory Provider and Context Engine. Press ENTER on a category to open a radio picker.

SubcommandDescription*(none)*Composite interactive UI — general plugin toggles + provider plugin configuration.`install &lt;identifier&gt; [--force]`Install a plugin from a Git URL or `owner/repo`.`update &lt;name&gt;`Pull latest changes for an installed plugin.`remove &lt;name&gt;` (aliases: `rm`, `uninstall`)Remove an installed plugin.`enable &lt;name&gt;`Enable a disabled plugin.`disable &lt;name&gt;`Disable a plugin without removing it.`list` (alias: `ls`)List installed plugins with enabled/disabled status.
Provider plugin selections are saved to `config.yaml`:

- `memory.provider` — active memory provider (empty = built-in only)

- `context.engine` — active context engine (`&quot;compressor&quot;` = built-in default)

General plugin disabled list is stored in `config.yaml` under `plugins.disabled`.

See [Plugins](/docs/user-guide/features/plugins) and [Build a Hermes Plugin](/docs/guides/build-a-hermes-plugin).

## `hermes tools`

```
hermes tools [--summary]
```
OptionDescription`--summary`Print the current enabled-tools summary and exit.
Without `--summary`, this launches the interactive per-platform tool configuration UI.

## `hermes sessions`

```
hermes sessions &lt;subcommand&gt;
```
Subcommands:

SubcommandDescription`list`List recent sessions.`browse`Interactive session picker with search and resume.`export &lt;output&gt; [--session-id ID]`Export sessions to JSONL.`delete &lt;session-id&gt;`Delete one session.`prune`Delete old sessions.`stats`Show session-store statistics.`rename &lt;session-id&gt; &lt;title&gt;`Set or change a session title.
## `hermes insights`

```
hermes insights [--days N] [--source platform]
```
OptionDescription`--days &lt;n&gt;`Analyze the last `n` days (default: 30).`--source &lt;platform&gt;`Filter by source such as `cli`, `telegram`, or `discord`.
## `hermes claw`

```
hermes claw migrate [options]
```
Migrate your OpenClaw setup to Hermes. Reads from `~/.openclaw` (or a custom path) and writes to `~/.hermes`. Automatically detects legacy directory names (`~/.clawdbot`, `~/.moltbot`) and config filenames (`clawdbot.json`, `moltbot.json`).

OptionDescription`--dry-run`Preview what would be migrated without writing anything.`--preset &lt;name&gt;`Migration preset: `full` (default, includes secrets) or `user-data` (excludes API keys).`--overwrite`Overwrite existing Hermes files on conflicts (default: skip).`--migrate-secrets`Include API keys in migration (enabled by default with `--preset full`).`--source &lt;path&gt;`Custom OpenClaw directory (default: `~/.openclaw`).`--workspace-target &lt;path&gt;`Target directory for workspace instructions (AGENTS.md).`--skill-conflict &lt;mode&gt;`Handle skill name collisions: `skip` (default), `overwrite`, or `rename`.`--yes`Skip the confirmation prompt.
### What gets migrated

The migration covers 30+ categories across persona, memory, skills, model providers, messaging platforms, agent behavior, session policies, MCP servers, TTS, and more. Items are either **directly imported** into Hermes equivalents or **archived** for manual review.

**Directly imported:** SOUL.md, MEMORY.md, USER.md, AGENTS.md, skills (4 source directories), default model, custom providers, MCP servers, messaging platform tokens and allowlists (Telegram, Discord, Slack, WhatsApp, Signal, Matrix, Mattermost), agent defaults (reasoning effort, compression, human delay, timezone, sandbox), session reset policies, approval rules, TTS config, browser settings, tool settings, exec timeout, command allowlist, gateway config, and API keys from 3 sources.

**Archived for manual review:** Cron jobs, plugins, hooks/webhooks, memory backend (QMD), skills registry config, UI/identity, logging, multi-agent setup, channel bindings, IDENTITY.md, TOOLS.md, HEARTBEAT.md, BOOTSTRAP.md.

**API key resolution** checks three sources in priority order: config values → `~/.openclaw/.env` → `auth-profiles.json`. All token fields handle plain strings, env templates (`${VAR}`), and SecretRef objects.

For the complete config key mapping, SecretRef handling details, and post-migration checklist, see the **[full migration guide](/docs/guides/migrate-from-openclaw)**.

### Examples

```
# Preview what would be migratedhermes claw migrate --dry-run# Full migration including API keyshermes claw migrate --preset full# Migrate user data only (no secrets), overwrite conflictshermes claw migrate --preset user-data --overwrite# Migrate from a custom OpenClaw pathhermes claw migrate --source /home/user/old-openclaw
```
## `hermes dashboard`

```
hermes dashboard [options]
```
Launch the web dashboard — a browser-based UI for managing configuration, API keys, and monitoring sessions. Requires `pip install hermes-agent[web]` (FastAPI + Uvicorn). See [Web Dashboard](/docs/user-guide/features/web-dashboard) for full documentation.

OptionDefaultDescription`--port``9119`Port to run the web server on`--host``127.0.0.1`Bind address`--no-open`—Don&#x27;t auto-open the browser
```
# Default — opens browser to http://127.0.0.1:9119hermes dashboard# Custom port, no browserhermes dashboard --port 8080 --no-open
```
## `hermes profile`

```
hermes profile &lt;subcommand&gt;
```
Manage profiles — multiple isolated Hermes instances, each with its own config, sessions, skills, and home directory.

SubcommandDescription`list`List all profiles.`use &lt;name&gt;`Set a sticky default profile.`create &lt;name&gt; [--clone] [--clone-all] [--clone-from &lt;source&gt;] [--no-alias]`Create a new profile. `--clone` copies config, `.env`, and `SOUL.md` from the active profile. `--clone-all` copies all state. `--clone-from` specifies a source profile.`delete &lt;name&gt; [-y]`Delete a profile.`show &lt;name&gt;`Show profile details (home directory, config, etc.).`alias &lt;name&gt; [--remove] [--name NAME]`Manage wrapper scripts for quick profile access.`rename &lt;old&gt; &lt;new&gt;`Rename a profile.`export &lt;name&gt; [-o FILE]`Export a profile to a `.tar.gz` archive.`import &lt;archive&gt; [--name NAME]`Import a profile from a `.tar.gz` archive.
Examples:

```
hermes profile listhermes profile create work --clonehermes profile use workhermes profile alias work --name h-workhermes profile export work -o work-backup.tar.gzhermes profile import work-backup.tar.gz --name restoredhermes -p work chat -q &quot;Hello from work profile&quot;
```
## `hermes completion`

```
hermes completion [bash|zsh]
```
Print a shell completion script to stdout. Source the output in your shell profile for tab-completion of Hermes commands, subcommands, and profile names.

Examples:

```
# Bashhermes completion bash &gt;&gt; ~/.bashrc# Zshhermes completion zsh &gt;&gt; ~/.zshrc
```
## Maintenance commands

CommandDescription`hermes version`Print version information.`hermes update`Pull latest changes and reinstall dependencies.`hermes uninstall [--full] [--yes]`Remove Hermes, optionally deleting all config/data.
## See also

- [Slash Commands Reference](/docs/reference/slash-commands)

- [CLI Interface](/docs/user-guide/cli)

- [Sessions](/docs/user-guide/sessions)

- [Skills System](/docs/user-guide/features/skills)

- [Skins &amp; Themes](/docs/user-guide/features/skins)

[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/reference/cli-commands.md)