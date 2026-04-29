---
pageType: entity
id: entity.features-mcp
title: 'Features: MCP'
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-features-mcp.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-features-mcp.md
updatedAt: '2026-04-24T15:05:25.650821+00:00'
sourceIds:
- mcpexamplecom
- mcpinternalexampleco
- mcplegacyinternal
- mcpstripecom
- mcpdocsexamplecom
- mcpexamplecom
sources:
- sourceId: mcpexamplecom
  sourceType: web
  sourcePath: https://mcp.example.com/mcp
  title: mcp.example.com
- sourceId: mcpinternalexampleco
  sourceType: web
  sourcePath: https://mcp.internal.example.com
  title: mcp.internal.example.com
- sourceId: mcplegacyinternal
  sourceType: web
  sourcePath: https://mcp.legacy.internal
  title: mcp.legacy.internal
- sourceId: mcpstripecom
  sourceType: web
  sourcePath: https://mcp.stripe.com
  title: mcp.stripe.com
- sourceId: mcpdocsexamplecom
  sourceType: web
  sourcePath: https://mcp.docs.example.com
  title: mcp.docs.example.com
- sourceId: mcpexamplecom
  sourceType: web
  sourcePath: https://mcp.example.com
  title: mcp.example.com
claims:
- id: access-to-external-tool-ecosystems-without-writing-a-native
  text: Access to external tool ecosystems without writing a native Hermes tool first
  status: supported
  confidence: null
- id: local-stdio-servers-and-remote-http-mcp-servers-in-the-same
  text: Local stdio servers and remote HTTP MCP servers in the same config
  status: supported
  confidence: null
- id: automatic-tool-discovery-and-registration-at-startup
  text: Automatic tool discovery and registration at startup
  status: supported
  confidence: null
- id: utility-wrappers-for-mcp-resources-and-prompts-when-supporte
  text: Utility wrappers for MCP resources and prompts when supported by the server
  status: supported
  confidence: null
- id: per-server-filtering-so-you-can-expose-only-the-mcp-tools-yo
  text: Per-server filtering so you can expose only the MCP tools you actually want
    Hermes to see
  status: supported
  confidence: null
- id: the-server-is-installed-locally
  text: the server is installed locally
  status: supported
  confidence: null
- id: you-want-low-latency-access-to-local-resources
  text: you want low-latency access to local resources
  status: supported
  confidence: null
- id: you-are-following-mcp-server-docs-that-show-command-args
  text: you are following MCP server docs that show `command`, `args`, and `env`
  status: supported
  confidence: null
- id: the-mcp-server-is-hosted-elsewhere
  text: the MCP server is hosted elsewhere
  status: supported
  confidence: null
- id: your-organization-exposes-internal-mcp-endpoints
  text: your organization exposes internal MCP endpoints
  status: supported
  confidence: null
- id: you-do-not-want-hermes-spawning-a-local-subprocess-for-that
  text: you do not want Hermes spawning a local subprocess for that integration
  status: supported
  confidence: null
- id: key-type-meaning
  text: Key**, **Type**, **Meaning**
  status: supported
  confidence: null
- id: key-command-type-string-meaning-executable
  text: 'Key**: `command`, **Type**: string, **Meaning**: Executable for a stdio MCP
    server'
  status: supported
  confidence: null
- id: key-args-type-list-meaning-arguments-for-th
  text: 'Key**: `args`, **Type**: list, **Meaning**: Arguments for the stdio server'
  status: supported
  confidence: null
- id: key-env-type-mapping-meaning-environment-va
  text: 'Key**: `env`, **Type**: mapping, **Meaning**: Environment variables passed
    to the stdio server'
  status: supported
  confidence: null
- id: key-url-type-string-meaning-http-mcp-endpoi
  text: 'Key**: `url`, **Type**: string, **Meaning**: HTTP MCP endpoint'
  status: supported
  confidence: null
- id: key-headers-type-mapping-meaning-http-heade
  text: 'Key**: `headers`, **Type**: mapping, **Meaning**: HTTP headers for remote
    servers'
  status: supported
  confidence: null
- id: key-timeout-type-number-meaning-tool-call-t
  text: 'Key**: `timeout`, **Type**: number, **Meaning**: Tool call timeout'
  status: supported
  confidence: null
- id: key-connect-timeout-type-number-meaning-ini
  text: 'Key**: `connect_timeout`, **Type**: number, **Meaning**: Initial connection
    timeout'
  status: supported
  confidence: null
- id: key-enabled-type-bool-meaning-if-false-h
  text: 'Key**: `enabled`, **Type**: bool, **Meaning**: If `false`, Hermes skips the
    server entirely'
  status: supported
  confidence: null
- id: key-tools-type-mapping-meaning-per-server-t
  text: 'Key**: `tools`, **Type**: mapping, **Meaning**: Per-server tool filtering
    and utility policy'
  status: supported
  confidence: null
- id: server-mcp-tool-registered-name
  text: Server**, **MCP tool**, **Registered name**
  status: supported
  confidence: null
- id: server-filesystem-mcp-tool-read-file-registe
  text: 'Server**: `filesystem`, **MCP tool**: `read_file`, **Registered name**: `mcp_filesystem_read_file`'
  status: supported
  confidence: null
- id: server-github-mcp-tool-create-issue-register
  text: 'Server**: `github`, **MCP tool**: `create-issue`, **Registered name**: `mcp_github_create_issue`'
  status: supported
  confidence: null
- id: server-my-api-mcp-tool-querydata-registered
  text: 'Server**: `my-api`, **MCP tool**: `query.data`, **Registered name**: `mcp_my_api_query_data`'
  status: supported
  confidence: null
- id: list-resources
  text: '`list_resources`'
  status: supported
  confidence: null
- id: read-resource
  text: '`read_resource`'
  status: supported
  confidence: null
- id: list-prompts
  text: '`list_prompts`'
  status: supported
  confidence: null
- id: get-prompt
  text: '`get_prompt`'
  status: supported
  confidence: null
- id: mcp-github-list-resources
  text: '`mcp_github_list_resources`'
  status: supported
  confidence: null
- id: mcp-github-get-prompt
  text: '`mcp_github_get_prompt`'
  status: supported
  confidence: null
- id: hermes-only-registers-resource-utilities-if-the-mcp-session
  text: Hermes only registers resource utilities if the MCP session actually supports
    resource operations
  status: supported
  confidence: null
- id: hermes-only-registers-prompt-utilities-if-the-mcp-session-ac
  text: Hermes only registers prompt utilities if the MCP session actually supports
    prompt operations
  status: supported
  confidence: null
- id: toolsresources-false-disables-list-resources-and-read
  text: '`tools.resources: false` disables `list_resources` and `read_resource`'
  status: supported
  confidence: null
- id: toolsprompts-false-disables-list-prompts-and-get-prom
  text: '`tools.prompts: false` disables `list_prompts` and `get_prompt`'
  status: supported
  confidence: null
- id: disable-dangerous-tools-you-do-not-want-the-model-to-see
  text: disable dangerous tools you do not want the model to see
  status: supported
  confidence: null
- id: expose-only-a-minimal-whitelist-for-a-sensitive-server
  text: expose only a minimal whitelist for a sensitive server
  status: supported
  confidence: null
- id: disable-resourceprompt-wrappers-when-you-do-not-want-that-s
  text: disable resource/prompt wrappers when you do not want that surface exposed
  status: supported
  confidence: null
- id: the-server-failed-to-connect
  text: the server failed to connect
  status: supported
  confidence: null
- id: discovery-failed
  text: discovery failed
  status: supported
  confidence: null
- id: your-filter-config-excluded-the-tools
  text: your filter config excluded the tools
  status: supported
  confidence: null
- id: the-utility-capability-does-not-exist-on-that-server
  text: the utility capability does not exist on that server
  status: supported
  confidence: null
- id: the-server-is-disabled-with-enabled-false
  text: 'the server is disabled with `enabled: false`'
  status: supported
  confidence: null
- id: you-want-claude-code-cursor-or-another-coding-agent-to-sen
  text: You want Claude Code, Cursor, or another coding agent to send and read Telegram/Discord/Slack
    messages through Hermes
  status: supported
  confidence: null
- id: you-want-a-single-mcp-server-that-bridges-to-all-of-hermess
  text: You want a single MCP server that bridges to all of Hermes's connected messaging
    platforms at once
  status: supported
  confidence: null
- id: you-already-have-a-running-hermes-gateway-with-connected-pla
  text: You already have a running Hermes gateway with connected platforms
  status: supported
  confidence: null
- id: tool-description
  text: 'Tool**: Description'
  status: supported
  confidence: null
- id: conversations-list-list-active-messaging-conversations
  text: '`conversations_list`**: List active messaging conversations. Filter by platform
    or search by name.'
  status: supported
  confidence: null
- id: conversation-get-get-detailed-info-about-one-conversati
  text: '`conversation_get`**: Get detailed info about one conversation by session
    key.'
  status: supported
  confidence: null
- id: messages-read-read-recent-message-history-for-a-convers
  text: '`messages_read`**: Read recent message history for a conversation.'
  status: supported
  confidence: null
- id: attachments-fetch-extract-non-text-attachments-images
  text: '`attachments_fetch`**: Extract non-text attachments (images, media) from
    a specific message.'
  status: supported
  confidence: null
- id: events-poll-poll-for-new-conversation-events-since-a-cu
  text: '`events_poll`**: Poll for new conversation events since a cursor position.'
  status: supported
  confidence: null
- id: events-wait-long-poll-block-until-the-next-event-arri
  text: '`events_wait`**: Long-poll / block until the next event arrives (near-real-time).'
  status: supported
  confidence: null
- id: messages-send-send-a-message-through-a-platform-eg
  text: '`messages_send`**: Send a message through a platform (e.g. `telegram:123456`,
    `discord:#general`).'
  status: supported
  confidence: null
- id: channels-list-list-available-messaging-targets-across-a
  text: '`channels_list`**: List available messaging targets across all platforms.'
  status: supported
  confidence: null
- id: permissions-list-open-list-pending-approval-requests-ob
  text: '`permissions_list_open`**: List pending approval requests observed during
    this bridge session.'
  status: supported
  confidence: null
- id: permissions-respond-allow-or-deny-a-pending-approval-re
  text: '`permissions_respond`**: Allow or deny a pending approval request.'
  status: supported
  confidence: null
- id: stdio-transport-only-no-http-mcp-transport-yet
  text: Stdio transport only (no HTTP MCP transport yet)
  status: supported
  confidence: null
- id: event-polling-at-200ms-intervals-via-mtime-optimized-db-pol
  text: Event polling at ~200ms intervals via mtime-optimized DB polling (skips work
    when files are unchanged)
  status: supported
  confidence: null
- id: no-claudechannel-push-notification-protocol-yet
  text: No `claude/channel` push notification protocol yet
  status: supported
  confidence: null
- id: text-only-sends-no-mediaattachment-sending-through-messag
  text: Text-only sends (no media/attachment sending through `messages_send`)
  status: supported
  confidence: null
- id: use-mcp-with-hermesdocsguidesuse-mcp-with-hermes
  text: '[Use MCP with Hermes](/docs/guides/use-mcp-with-hermes)'
  status: supported
  confidence: null
- id: cli-commandsdocsreferencecli-commands
  text: '[CLI Commands](/docs/reference/cli-commands)'
  status: supported
  confidence: null
- id: slash-commandsdocsreferenceslash-commands
  text: '[Slash Commands](/docs/reference/slash-commands)'
  status: supported
  confidence: null
- id: faqdocsreferencefaq
  text: '[FAQ](/docs/reference/faq)'
  status: supported
  confidence: null
---

MCP lets Hermes Agent connect to external tool servers so the agent can use tools that live outside Hermes itself — GitHub, databases, file systems, browser stacks, internal APIs, and more.

If you have ever wanted Hermes to use a tool that already exists somewhere else, MCP is usually the cleanest way to do it.

## What MCP gives you[​](#what-mcp-gives-you "Direct link to What MCP gives you")

- Access to external tool ecosystems without writing a native Hermes tool first
- Local stdio servers and remote HTTP MCP servers in the same config
- Automatic tool discovery and registration at startup
- Utility wrappers for MCP resources and prompts when supported by the server
- Per-server filtering so you can expose only the MCP tools you actually want Hermes to see

## Quick start[​](#quick-start "Direct link to Quick start")

1. Install MCP support (already included if you used the standard install script):

```
cd ~/.hermes/hermes-agent
uv pip install -e ".[mcp]"
```

2. Add an MCP server to `~/.hermes/config.yaml`:

```
mcp_servers:
  filesystem:
    command: "npx"
    args: ["-y", "@modelcontextprotocol/server-filesystem", "/home/user/projects"]
```

3. Start Hermes:

```
hermes chat
```

4. Ask Hermes to use the MCP-backed capability.

For example:

```
List the files in /home/user/projects and summarize the repo structure.
```

Hermes will discover the MCP server's tools and use them like any other tool.

## Two kinds of MCP servers[​](#two-kinds-of-mcp-servers "Direct link to Two kinds of MCP servers")

### Stdio servers[​](#stdio-servers "Direct link to Stdio servers")

Stdio servers run as local subprocesses and talk over stdin/stdout.

```
mcp_servers:
  github:
    command: "npx"
    args: ["-y", "@modelcontextprotocol/server-github"]
    env:
      GITHUB_PERSONAL_ACCESS_TOKEN: "***"
```

Use stdio servers when:

- the server is installed locally
- you want low-latency access to local resources
- you are following MCP server docs that show `command`, `args`, and `env`

### HTTP servers[​](#http-servers "Direct link to HTTP servers")

HTTP MCP servers are remote endpoints Hermes connects to directly.

```
mcp_servers:
  remote_api:
    url: "https://mcp.example.com/mcp"
    headers:
      Authorization: "Bearer ***"
```

Use HTTP servers when:

- the MCP server is hosted elsewhere
- your organization exposes internal MCP endpoints
- you do not want Hermes spawning a local subprocess for that integration

## Basic configuration reference[​](#basic-configuration-reference "Direct link to Basic configuration reference")

Hermes reads MCP config from `~/.hermes/config.yaml` under `mcp_servers`.

### Common keys[​](#common-keys "Direct link to Common keys")

- **Key**, **Type**, **Meaning**
- **Key**: `command`, **Type**: string, **Meaning**: Executable for a stdio MCP server
- **Key**: `args`, **Type**: list, **Meaning**: Arguments for the stdio server
- **Key**: `env`, **Type**: mapping, **Meaning**: Environment variables passed to the stdio server
- **Key**: `url`, **Type**: string, **Meaning**: HTTP MCP endpoint
- **Key**: `headers`, **Type**: mapping, **Meaning**: HTTP headers for remote servers
- **Key**: `timeout`, **Type**: number, **Meaning**: Tool call timeout
- **Key**: `connect_timeout`, **Type**: number, **Meaning**: Initial connection timeout
- **Key**: `enabled`, **Type**: bool, **Meaning**: If `false`, Hermes skips the server entirely
- **Key**: `tools`, **Type**: mapping, **Meaning**: Per-server tool filtering and utility policy

### Minimal stdio example[​](#minimal-stdio-example "Direct link to Minimal stdio example")

```
mcp_servers:
  filesystem:
    command: "npx"
    args: ["-y", "@modelcontextprotocol/server-filesystem", "/tmp"]
```

### Minimal HTTP example[​](#minimal-http-example "Direct link to Minimal HTTP example")

```
mcp_servers:
  company_api:
    url: "https://mcp.internal.example.com"
    headers:
      Authorization: "Bearer ***"
```

## How Hermes registers MCP tools[​](#how-hermes-registers-mcp-tools "Direct link to How Hermes registers MCP tools")

Hermes prefixes MCP tools so they do not collide with built-in names:

```
mcp_<server_name>_<tool_name>
```

Examples:

- **Server**, **MCP tool**, **Registered name**
- **Server**: `filesystem`, **MCP tool**: `read_file`, **Registered name**: `mcp_filesystem_read_file`
- **Server**: `github`, **MCP tool**: `create-issue`, **Registered name**: `mcp_github_create_issue`
- **Server**: `my-api`, **MCP tool**: `query.data`, **Registered name**: `mcp_my_api_query_data`

In practice, you usually do not need to call the prefixed name manually — Hermes sees the tool and chooses it during normal reasoning.

## MCP utility tools[​](#mcp-utility-tools "Direct link to MCP utility tools")

When supported, Hermes also registers utility tools around MCP resources and prompts:

- `list_resources`
- `read_resource`
- `list_prompts`
- `get_prompt`

These are registered per server with the same prefix pattern, for example:

- `mcp_github_list_resources`
- `mcp_github_get_prompt`

### Important[​](#important "Direct link to Important")

These utility tools are now capability-aware:

- Hermes only registers resource utilities if the MCP session actually supports resource operations
- Hermes only registers prompt utilities if the MCP session actually supports prompt operations

So a server that exposes callable tools but no resources/prompts will not get those extra wrappers.

## Per-server filtering[​](#per-server-filtering "Direct link to Per-server filtering")

You can control which tools each MCP server contributes to Hermes, allowing fine-grained management of your tool namespace.

### Disable a server entirely[​](#disable-a-server-entirely "Direct link to Disable a server entirely")

```
mcp_servers:
  legacy:
    url: "https://mcp.legacy.internal"
    enabled: false
```

If `enabled: false`, Hermes skips the server completely and does not even attempt a connection.

### Whitelist server tools[​](#whitelist-server-tools "Direct link to Whitelist server tools")

```
mcp_servers:
  github:
    command: "npx"
    args: ["-y", "@modelcontextprotocol/server-github"]
    env:
      GITHUB_PERSONAL_ACCESS_TOKEN: "***"
    tools:
      include: [create_issue, list_issues]
```

Only those MCP server tools are registered.

### Blacklist server tools[​](#blacklist-server-tools "Direct link to Blacklist server tools")

```
mcp_servers:
  stripe:
    url: "https://mcp.stripe.com"
    tools:
      exclude: [delete_customer]
```

All server tools are registered except the excluded ones.

### Precedence rule[​](#precedence-rule "Direct link to Precedence rule")

If both are present:

```
tools:
  include: [create_issue]
  exclude: [create_issue, delete_issue]
```

`include` wins.

### Filter utility tools too[​](#filter-utility-tools-too "Direct link to Filter utility tools too")

You can also separately disable Hermes-added utility wrappers:

```
mcp_servers:
  docs:
    url: "https://mcp.docs.example.com"
    tools:
      prompts: false
      resources: false
```

That means:

- `tools.resources: false` disables `list_resources` and `read_resource`
- `tools.prompts: false` disables `list_prompts` and `get_prompt`

### Full example[​](#full-example "Direct link to Full example")

```
mcp_servers:
  github:
    command: "npx"
    args: ["-y", "@modelcontextprotocol/server-github"]
    env:
      GITHUB_PERSONAL_ACCESS_TOKEN: "***"
    tools:
      include: [create_issue, list_issues, search_code]
      prompts: false

  stripe:
    url: "https://mcp.stripe.com"
    headers:
      Authorization: "Bearer ***"
    tools:
      exclude: [delete_customer]
      resources: false

  legacy:
    url: "https://mcp.legacy.internal"
    enabled: false
```

## What happens if everything is filtered out?[​](#what-happens-if-everything-is-filtered-out "Direct link to What happens if everything is filtered out?")

If your config filters out all callable tools and disables or omits all supported utilities, Hermes does not create an empty runtime MCP toolset for that server.

That keeps the tool list clean.

## Runtime behavior[​](#runtime-behavior "Direct link to Runtime behavior")

### Discovery time[​](#discovery-time "Direct link to Discovery time")

Hermes discovers MCP servers at startup and registers their tools into the normal tool registry.

### Dynamic Tool Discovery[​](#dynamic-tool-discovery "Direct link to Dynamic Tool Discovery")

MCP servers can notify Hermes when their available tools change at runtime by sending a `notifications/tools/list_changed` notification. When Hermes receives this notification, it automatically re-fetches the server's tool list and updates the registry — no manual `/reload-mcp` required.

This is useful for MCP servers whose capabilities change dynamically (e.g. a server that adds tools when a new database schema is loaded, or removes tools when a service goes offline).

The refresh is lock-protected so rapid-fire notifications from the same server don't cause overlapping refreshes. Prompt and resource change notifications (`prompts/list_changed`, `resources/list_changed`) are received but not yet acted on.

### Reloading[​](#reloading "Direct link to Reloading")

If you change MCP config, use:

```
/reload-mcp
```

This reloads MCP servers from config and refreshes the available tool list. For runtime tool changes pushed by the server itself, see [Dynamic Tool Discovery](#dynamic-tool-discovery) above.

### Toolsets[​](#toolsets "Direct link to Toolsets")

Each configured MCP server also creates a runtime toolset when it contributes at least one registered tool:

```
mcp-<server>
```

That makes MCP servers easier to reason about at the toolset level.

## Security model[​](#security-model "Direct link to Security model")

### Stdio env filtering[​](#stdio-env-filtering "Direct link to Stdio env filtering")

For stdio servers, Hermes does not blindly pass your full shell environment.

Only explicitly configured `env` plus a safe baseline are passed through. This reduces accidental secret leakage.

### Config-level exposure control[​](#config-level-exposure-control "Direct link to Config-level exposure control")

The new filtering support is also a security control:

- disable dangerous tools you do not want the model to see
- expose only a minimal whitelist for a sensitive server
- disable resource/prompt wrappers when you do not want that surface exposed

## Example use cases[​](#example-use-cases "Direct link to Example use cases")

### GitHub server with a minimal issue-management surface[​](#github-server-with-a-minimal-issue-management-surface "Direct link to GitHub server with a minimal issue-management surface")

```
mcp_servers:
  github:
    command: "npx"
    args: ["-y", "@modelcontextprotocol/server-github"]
    env:
      GITHUB_PERSONAL_ACCESS_TOKEN: "***"
    tools:
      include: [list_issues, create_issue, update_issue]
      prompts: false
      resources: false
```

Use it like:

```
Show me open issues labeled bug, then draft a new issue for the flaky MCP reconnection behavior.
```

### Stripe server with dangerous actions removed[​](#stripe-server-with-dangerous-actions-removed "Direct link to Stripe server with dangerous actions removed")

```
mcp_servers:
  stripe:
    url: "https://mcp.stripe.com"
    headers:
      Authorization: "Bearer ***"
    tools:
      exclude: [delete_customer, refund_payment]
```

Use it like:

```
Look up the last 10 failed payments and summarize common failure reasons.
```

### Filesystem server for a single project root[​](#filesystem-server-for-a-single-project-root "Direct link to Filesystem server for a single project root")

```
mcp_servers:
  project_fs:
    command: "npx"
    args: ["-y", "@modelcontextprotocol/server-filesystem", "/home/user/my-project"]
```

Use it like:

```
Inspect the project root and explain the directory layout.
```

## Troubleshooting[​](#troubleshooting "Direct link to Troubleshooting")

### MCP server not connecting[​](#mcp-server-not-connecting "Direct link to MCP server not connecting")

Check:

```
# Verify MCP deps are installed (already included in standard install)
cd ~/.hermes/hermes-agent && uv pip install -e ".[mcp]"

node --version
npx --version
```

Then verify your config and restart Hermes.

### Tools not appearing[​](#tools-not-appearing "Direct link to Tools not appearing")

Possible causes:

- the server failed to connect
- discovery failed
- your filter config excluded the tools
- the utility capability does not exist on that server
- the server is disabled with `enabled: false`

If you are intentionally filtering, this is expected.

### Why didn't resource or prompt utilities appear?[​](#why-didnt-resource-or-prompt-utilities-appear "Direct link to Why didn't resource or prompt utilities appear?")

Because Hermes now only registers those wrappers when both are true:

1. your config allows them
2. the server session actually supports the capability

This is intentional and keeps the tool list honest.

## MCP Sampling Support[​](#mcp-sampling-support "Direct link to MCP Sampling Support")

MCP servers can request LLM inference from Hermes via the `sampling/createMessage` protocol. This allows an MCP server to ask Hermes to generate text on its behalf — useful for servers that need LLM capabilities but don't have their own model access.

Sampling is **enabled by default** for all MCP servers (when the MCP SDK supports it). Configure it per-server under the `sampling` key:

```
mcp_servers:
  my_server:
    command: "my-mcp-server"
    sampling:
      enabled: true            # Enable sampling (default: true)
      model: "openai/gpt-4o"  # Override model for sampling requests (optional)
      max_tokens_cap: 4096     # Max tokens per sampling response (default: 4096)
      timeout: 30              # Timeout in seconds per request (default: 30)
      max_rpm: 10              # Rate limit: max requests per minute (default: 10)
      max_tool_rounds: 5       # Max tool-use rounds in sampling loops (default: 5)
      allowed_models: []       # Allowlist of model names the server may request (empty = any)
      log_level: "info"        # Audit log level: debug, info, or warning (default: info)
```

The sampling handler includes a sliding-window rate limiter, per-request timeouts, and tool-loop depth limits to prevent runaway usage. Metrics (request count, errors, tokens used) are tracked per server instance.

To disable sampling for a specific server:

```
mcp_servers:
  untrusted_server:
    url: "https://mcp.example.com"
    sampling:
      enabled: false
```

## Running Hermes as an MCP server[​](#running-hermes-as-an-mcp-server "Direct link to Running Hermes as an MCP server")

In addition to connecting **to** MCP servers, Hermes can also **be** an MCP server. This lets other MCP-capable agents (Claude Code, Cursor, Codex, or any MCP client) use Hermes's messaging capabilities — list conversations, read message history, and send messages across all your connected platforms.

### When to use this[​](#when-to-use-this "Direct link to When to use this")

- You want Claude Code, Cursor, or another coding agent to send and read Telegram/Discord/Slack messages through Hermes
- You want a single MCP server that bridges to all of Hermes's connected messaging platforms at once
- You already have a running Hermes gateway with connected platforms

### Quick start[​](#quick-start-1 "Direct link to Quick start")

```
hermes mcp serve
```

This starts a stdio MCP server. The MCP client (not you) manages the process lifecycle.

### MCP client configuration[​](#mcp-client-configuration "Direct link to MCP client configuration")

Add Hermes to your MCP client config. For example, in Claude Code's `~/.claude/claude_desktop_config.json`:

```
{
  "mcpServers": {
    "hermes": {
      "command": "hermes",
      "args": ["mcp", "serve"]
    }
  }
}
```

Or if you installed Hermes in a specific location:

```
{
  "mcpServers": {
    "hermes": {
      "command": "/home/user/.hermes/hermes-agent/venv/bin/hermes",
      "args": ["mcp", "serve"]
    }
  }
}
```

### Available tools[​](#available-tools "Direct link to Available tools")

The MCP server exposes 10 tools, matching OpenClaw's channel bridge surface plus a Hermes-specific channel browser:

- **Tool**: Description
- **`conversations_list`**: List active messaging conversations. Filter by platform or search by name.
- **`conversation_get`**: Get detailed info about one conversation by session key.
- **`messages_read`**: Read recent message history for a conversation.
- **`attachments_fetch`**: Extract non-text attachments (images, media) from a specific message.
- **`events_poll`**: Poll for new conversation events since a cursor position.
- **`events_wait`**: Long-poll / block until the next event arrives (near-real-time).
- **`messages_send`**: Send a message through a platform (e.g. `telegram:123456`, `discord:#general`).
- **`channels_list`**: List available messaging targets across all platforms.
- **`permissions_list_open`**: List pending approval requests observed during this bridge session.
- **`permissions_respond`**: Allow or deny a pending approval request.

### Event system[​](#event-system "Direct link to Event system")

The MCP server includes a live event bridge that polls Hermes's session database for new messages. This gives MCP clients near-real-time awareness of incoming conversations:

```
# Poll for new events (non-blocking)
events_poll(after_cursor=0)

# Wait for next event (blocks up to timeout)
events_wait(after_cursor=42, timeout_ms=30000)
```

Event types: `message`, `approval_requested`, `approval_resolved`

The event queue is in-memory and starts when the bridge connects. Older messages are available through `messages_read`.

### Options[​](#options "Direct link to Options")

```
hermes mcp serve              # Normal mode
hermes mcp serve --verbose    # Debug logging on stderr
```

### How it works[​](#how-it-works "Direct link to How it works")

The MCP server reads conversation data directly from Hermes's session store (`~/.hermes/sessions/sessions.json` and the SQLite database). A background thread polls the database for new messages and maintains an in-memory event queue. For sending messages, it uses the same `send_message` infrastructure as the Hermes agent itself.

The gateway does NOT need to be running for read operations (listing conversations, reading history, polling events). It DOES need to be running for send operations, since the platform adapters need active connections.

### Current limits[​](#current-limits "Direct link to Current limits")

- Stdio transport only (no HTTP MCP transport yet)
- Event polling at ~200ms intervals via mtime-optimized DB polling (skips work when files are unchanged)
- No `claude/channel` push notification protocol yet
- Text-only sends (no media/attachment sending through `messages_send`)

## Related docs[​](#related-docs "Direct link to Related docs")

- [Use MCP with Hermes](/docs/guides/use-mcp-with-hermes)
- [CLI Commands](/docs/reference/cli-commands)
- [Slash Commands](/docs/reference/slash-commands)
- [FAQ](/docs/reference/faq)