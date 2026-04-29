---
pageType: entity
id: entity.messaging-gateway
title: Messaging Gateway
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/messaging.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/messaging.md
updatedAt: '2026-04-24T15:05:25.401749+00:00'
claims:
- id: in-progress-terminal-commands-are-killed-immediately-sigter
  text: In-progress terminal commands are killed immediately (SIGTERM, then SIGKILL
    after 1s)
  status: supported
  confidence: null
- id: tool-calls-are-cancelled-only-the-currently-executing-one
  text: "Tool calls are cancelled \u2014 only the currently-executing one runs, the\
    \ rest are skipped"
  status: supported
  confidence: null
- id: multiple-messages-are-combined-messages-sent-during-interr
  text: "Multiple messages are combined \u2014 messages sent during interruption are\
    \ joined into one prompt"
  status: supported
  confidence: null
- id: stop-command-interrupts-without-queuing-a-follow-up-messa
  text: "/stop command \u2014 interrupts without queuing a follow-up message"
  status: supported
  confidence: null
- id: isolated-session-the-background-agent-has-its-own-session
  text: "Isolated session \u2014 the background agent has its own session with its\
    \ own conversation history. It has no knowledge of your current chat context and\
    \ receives only the prompt you provide."
  status: supported
  confidence: null
- id: same-configuration-inherits-your-model-provider-toolsets
  text: "Same configuration \u2014 inherits your model, provider, toolsets, reasoning\
    \ settings, and provider routing from the current gateway setup."
  status: supported
  confidence: null
- id: non-blocking-your-main-chat-stays-fully-interactive-send
  text: "Non-blocking \u2014 your main chat stays fully interactive. Send messages,\
    \ run other commands, or start more background tasks while it works."
  status: supported
  confidence: null
- id: result-delivery-when-the-task-finishes-the-result-is-sent
  text: "Result delivery \u2014 when the task finishes, the result is sent back to\
    \ the same chat or channel where you issued the command, prefixed with \"\u2705\
    \ Background task complete\". If it fails, you'll see \"\u274C Background task\
    \ failed\" with the error."
  status: supported
  confidence: null
- id: server-monitoring-background-check-the-health-of-all-ser
  text: "Server monitoring \u2014 \"/background Check the health of all services and\
    \ alert me if anything is down\""
  status: supported
  confidence: null
- id: long-builds-background-build-and-deploy-the-staging-envi
  text: "Long builds \u2014 \"/background Build and deploy the staging environment\"\
    \ while you continue chatting"
  status: supported
  confidence: null
- id: research-tasks-background-research-competitor-pricing-an
  text: "Research tasks \u2014 \"/background Research competitor pricing and summarize\
    \ in a table\""
  status: supported
  confidence: null
- id: file-operations-background-organize-the-photos-in-down
  text: "File operations \u2014 \"/background Organize the photos in ~/Downloads by\
    \ date into folders\""
  status: supported
  confidence: null
- id: path-your-full-shell-path-at-install-time-with-the-venv-b
  text: "PATH \u2014 your full shell PATH at install time, with the venv bin/ and\
    \ node_modules/.bin prepended. This ensures user-installed tools (Node.js, ffmpeg,\
    \ etc.) are available to gateway subprocesses like the WhatsApp bridge."
  status: supported
  confidence: null
- id: virtual-env-points-to-the-python-virtualenv-so-tools-can-r
  text: "VIRTUAL_ENV \u2014 points to the Python virtualenv so tools can resolve packages\
    \ correctly."
  status: supported
  confidence: null
- id: hermes-home-scopes-the-gateway-to-your-hermes-installation
  text: "HERMES_HOME \u2014 scopes the gateway to your Hermes installation."
  status: supported
  confidence: null
- id: telegram-setup
  text:
  - - entity.telegram-setup|Telegram Setup
  status: supported
  confidence: null
- id: discord-setup
  text:
  - - entity.discord-setup|Discord Setup
  status: supported
  confidence: null
- id: slack-setup
  text: Slack Setup
  status: supported
  confidence: null
- id: whatsapp-setup
  text: WhatsApp Setup
  status: supported
  confidence: null
- id: signal-setup
  text: Signal Setup
  status: supported
  confidence: null
- id: sms-setup-twilio
  text: SMS Setup (Twilio)
  status: supported
  confidence: null
- id: email-setup
  text: Email Setup
  status: supported
  confidence: null
- id: home-assistant-integration
  text: Home Assistant Integration
  status: supported
  confidence: null
- id: mattermost-setup
  text: Mattermost Setup
  status: supported
  confidence: null
- id: matrix-setup
  text: Matrix Setup
  status: supported
  confidence: null
- id: dingtalk-setup
  text: DingTalk Setup
  status: supported
  confidence: null
- id: feishulark-setup
  text: Feishu/Lark Setup
  status: supported
  confidence: null
- id: wecom-setup
  text: WeCom Setup
  status: supported
  confidence: null
- id: wecom-callback-setup
  text: WeCom Callback Setup
  status: supported
  confidence: null
- id: weixin-setup-wechat
  text: Weixin Setup (WeChat)
  status: supported
  confidence: null
- id: bluebubbles-setup-imessage
  text: BlueBubbles Setup (iMessage)
  status: supported
  confidence: null
- id: qqbot-setup
  text: QQBot Setup
  status: supported
  confidence: null
- id: open-webui-api-server
  text: Open WebUI + API Server
  status: supported
  confidence: null
- id: session-persistence
  text: Session Persistence
  status: supported
  confidence: null
- id: reset-policies
  text: Reset Policies
  status: supported
  confidence: null
- id: securitysecuritydm-pairing-alternative-to-allowlist
  text: '[[[entity.security|Security]]](#[[entity.security|Security]])[](#dm-pairing-alternative-to-allowlists)'
  status: supported
  confidence: null
- id: dm-pairing-alternative-to-allowlists
  text: DM Pairing (Alternative to Allowlists)
  status: supported
  confidence: null
- id: interrupting-the-agentinterrupting-the-agent
  text: '[Interrupting the Agent](#interrupting-the-agent)'
  status: supported
  confidence: null
- id: tool-progress-notificationstool-progress-notifications
  text: '[Tool Progress Notifications](#tool-progress-notifications)'
  status: supported
  confidence: null
- id: background-sessionsbackground-sessionshow-it-works
  text: '[Background Sessions](#background-sessions)[](#how-it-works)[](#background-process-notifications)[](#use-cases)'
  status: supported
  confidence: null
- id: how-it-works
  text: How It Works
  status: supported
  confidence: null
- id: background-process-notifications
  text: Background Process Notifications
  status: supported
  confidence: null
- id: service-managementservice-managementlinux-systemd
  text: '[Service Management](#service-management)[](#linux-systemd)[](#macos-launchd)'
  status: supported
  confidence: null
- id: linux-systemd
  text: Linux (systemd)
  status: supported
  confidence: null
- id: macos-launchd
  text: macOS (launchd)
  status: supported
  confidence: null
- id: platform-specific-toolsetsplatform-specific-toolsets
  text: '[Platform-Specific Toolsets](#platform-specific-toolsets)'
  status: supported
  confidence: null
- id: next-stepsnext-steps
  text: '[Next Steps](#next-steps)'
  status: supported
  confidence: null
---

On this page

Chat with Hermes from Telegram, Discord, Slack, WhatsApp, Signal, SMS, Email, Home Assistant, Mattermost, Matrix, DingTalk, Feishu/Lark, WeCom, Weixin, BlueBubbles (iMessage), QQ, or your browser. The gateway is a single background process that connects to all your configured platforms, handles sessions, runs cron jobs, and delivers voice messages.

For the full voice feature set — including CLI microphone mode, spoken replies in messaging, and Discord voice-channel conversations — see [Voice Mode](/docs/user-guide/features/voice-mode) and [Use Voice Mode with Hermes](/docs/guides/use-voice-mode-with-hermes).

## Platform Comparison[​](#platform-comparison)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[entities/discord-setup|Discord Setup]]
- [[entities/security|Security]]
- [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

**Voice** = TTS audio replies and/or voice message transcription. **Images** = send/receive images. **Files** = send/receive file attachments. **Threads** = threaded conversations. **Reactions** = emoji reactions on messages. **Typing** = typing indicator while processing. **Streaming** = progressive message updates via editing.

## Architecture[​](#architecture)

Each platform adapter receives messages, routes them through a per-chat session store, and dispatches them to the AIAgent for processing. The gateway also runs the cron scheduler, ticking every 60 seconds to execute any due jobs.

## Quick Setup[​](#quick-setup)

The easiest way to configure messaging platforms is the interactive wizard:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup # Interactive setup for all messaging platforms

```

This walks you through configuring each platform with arrow-key selection, shows which platforms are already configured, and offers to start/restart the gateway when done.

## Gateway Commands[​](#gateway-commands)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway # Run in foreground
hermes gateway setup # Configure messaging platforms interactively
hermes gateway install # Install as a user service (Linux) / launchd service (macOS)
sudo hermes gateway install --system # Linux only: install a boot-time system service
hermes gateway start # Start the default service
hermes gateway stop # Stop the default service
hermes gateway status # Check default service status
hermes gateway status --system # Linux only: inspect the system service explicitly

```

## Chat Commands (Inside Messaging)[​](#chat-commands-inside-messaging)

## Session Management[​](#session-management)

### Session Persistence[​](#session-persistence)

Sessions persist across messages until they reset. The agent remembers your conversation context.

### Reset Policies[​](#reset-policies)

Sessions reset based on configurable policies:

Configure per-platform overrides in ~/.hermes/gateway.json:

```prism-code json codeBlock_bY9V thin-scrollbar
{
 "reset_by_platform": {
 "telegram": { "mode": "idle", "idle_minutes": 240 },
 "discord": { "mode": "idle", "idle_minutes": 60 }
 }
}

```

## [[entities/security|Security]][​](#[[entities/security|Security]])

**By default, the gateway denies all users who are not in an allowlist or paired via DM.** This is the safe default for a bot with terminal access.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Restrict to specific users (recommended):
TELEGRAM_ALLOWED_USERS=123456789,987654321
DISCORD_ALLOWED_USERS=123456789012345678
SIGNAL_ALLOWED_USERS=+155****4567,+155****6543
SMS_ALLOWED_USERS=+155****4567,+155****6543
EMAIL_ALLOWED_USERS=trusted@example.com,colleague@work.com
MATTERMOST_ALLOWED_USERS=3uo8dkh1p7g1mfk49ear5fzs5c
MATRIX_ALLOWED_USERS=@alice:matrix.org
DINGTALK_ALLOWED_USERS=user-id-1
FEISHU_ALLOWED_USERS=ou_xxxxxxxx,ou_yyyyyyyy
WECOM_ALLOWED_USERS=user-id-1,user-id-2
WECOM_CALLBACK_ALLOWED_USERS=user-id-1,user-id-2

# Or allow
GATEWAY_ALLOWED_USERS=123456789,987654321

# Or explicitly allow all users (NOT recommended for bots with terminal access):
GATEWAY_ALLOW_ALL_USERS=true

```

### DM Pairing (Alternative to Allowlists)[​](#dm-pairing-alternative-to-allowlists)

Instead of manually configuring user IDs, unknown users receive a one-time pairing code when they DM the bot:

```prism-code bash codeBlock_bY9V thin-scrollbar
# The user sees: "Pairing code: XKGH5N7P"
# You approve them with:
hermes pairing approve telegram XKGH5N7P

# Other pairing commands:
hermes pairing list # View pending + approved users
hermes pairing revoke telegram 123456789 # Remove access

```

Pairing codes expire after 1 hour, are rate-limited, and use cryptographic randomness.

## Interrupting the Agent[​](#interrupting-the-agent)

Send any message while the agent is working to interrupt it. Key behaviors:

****************
- In-progress terminal commands are killed immediately (SIGTERM, then SIGKILL after 1s)

- Tool calls are cancelled — only the currently-executing one runs, the rest are skipped

- Multiple messages are combined — messages sent during interruption are joined into one prompt

- /stop command — interrupts without queuing a follow-up message

## Tool Progress Notifications[​](#tool-progress-notifications)

Control how much tool activity is displayed in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
display:
 tool_progress: all # off | new | all | verbose
 tool_progress_command: false # set to true to enable /verbose in messaging

```

When enabled, the bot sends status messages as it works:

```prism-code text codeBlock_bY9V thin-scrollbar
💻 `ls -la`...
🔍 web_search...
📄 web_extract...
🐍 execute_code...

```

## Background Sessions[​](#background-sessions)

Run a prompt in a separate background session so the agent works on it independently while your main chat stays responsive:

```prism-code text codeBlock_bY9V thin-scrollbar
/background Check all servers in the cluster and report any that are down

```

Hermes confirms immediately:

```prism-code text codeBlock_bY9V thin-scrollbar
🔄 Background task started: "Check all servers in the cluster..."
 Task ID: bg_143022_a1b2c3

```

### How It Works[​](#how-it-works)

Each /background prompt spawns a **separate agent instance** that runs asynchronously:

********************
- Isolated session — the background agent has its own session with its own conversation history. It has no knowledge of your current chat context and receives only the prompt you provide.

- Same configuration — inherits your model, provider, toolsets, reasoning settings, and provider routing from the current gateway setup.

- Non-blocking — your main chat stays fully interactive. Send messages, run other commands, or start more background tasks while it works.

- Result delivery — when the task finishes, the result is sent back to the same chat or channel where you issued the command, prefixed with "✅ Background task complete". If it fails, you'll see "❌ Background task failed" with the error.

### Background Process Notifications[​](#background-process-notifications)

When the agent running a background session uses terminal(background=true) to start long-running processes (servers, builds, etc.), the gateway can push status updates to your chat. Control this with display.background_process_notifications in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
display:
 background_process_notifications: all # all | result | error | off

```

****

You can also set this via environment variable:

```prism-code bash codeBlock_bY9V thin-scrollbar
HERMES_BACKGROUND_NOTIFICATIONS=result

```

### Use Cases[​](#use-cases)

****************
- Server monitoring — "/background Check the health of all services and alert me if anything is down"

- Long builds — "/background Build and deploy the staging environment" while you continue chatting

- Research tasks — "/background Research competitor pricing and summarize in a table"

- File operations — "/background Organize the photos in ~/Downloads by date into folders"

tip

Background tasks on messaging platforms are fire-and-forget — you don't need to wait or check on them. Results arrive in the same chat automatically when the task finishes.

## Service Management[​](#service-management)

### Linux (systemd)[​](#linux-systemd)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway install # Install as user service
hermes gateway start # Start the service
hermes gateway stop # Stop the service
hermes gateway status # Check status
journalctl --user -u hermes-gateway -f # View logs

# Enable lingering (keeps running after logout)
sudo loginctl enable-linger $USER

# Or install a boot-time system service that still runs as your user
sudo hermes gateway install --system
sudo hermes gateway start --system
sudo hermes gateway status --system
journalctl -u hermes-gateway -f

```

Use the user service on laptops and dev boxes. Use the system service on VPS or headless hosts that should come back at boot without relying on systemd linger.

Avoid keeping both the user and system gateway units installed at once unless you really mean to. Hermes will warn if it detects both because start/stop/status behavior gets ambiguous.

Multiple installations

If you run multiple Hermes installations on the same machine (with different HERMES_HOME directories), each gets its own systemd service name. The default ~/.hermes uses hermes-gateway; other installations use hermes-gateway-<hash>. The hermes gateway commands automatically target the correct service for your current HERMES_HOME.

### macOS (launchd)[​](#macos-launchd)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway install # Install as launchd agent
hermes gateway start # Start the service
hermes gateway stop # Stop the service
hermes gateway status # Check status
tail -f ~/.hermes/logs/gateway.log # View logs

```

The generated plist lives at ~/Library/LaunchAgents/ai.hermes.gateway.plist. It includes three environment variables:

************
- PATH — your full shell PATH at install time, with the venv bin/ and node_modules/.bin prepended. This ensures user-installed tools (Node.js, ffmpeg, etc.) are available to gateway subprocesses like the WhatsApp bridge.

- VIRTUAL_ENV — points to the Python virtualenv so tools can resolve packages correctly.

- HERMES_HOME — scopes the gateway to your Hermes installation.

PATH changes after install

launchd plists are static — if you install new tools (e.g. a new Node.js version via nvm, or ffmpeg via Homebrew) after setting up the gateway, run hermes gateway install again to capture the updated PATH. The gateway will detect the stale plist and reload automatically.

Multiple installations

Like the Linux systemd service, each HERMES_HOME directory gets its own launchd label. The default ~/.hermes uses ai.hermes.gateway; other installations use ai.hermes.gateway-<suffix>.

## Platform-Specific Toolsets[​](#platform-specific-toolsets)

Each platform has its own toolset:

## Next Steps[​](#next-steps)

[](/docs/user-guide/messaging/telegram)[](/docs/user-guide/messaging/discord)[](/docs/user-guide/messaging/slack)[](/docs/user-guide/messaging/whatsapp)[](/docs/user-guide/messaging/signal)[](/docs/user-guide/messaging/sms)[](/docs/user-guide/messaging/email)[](/docs/user-guide/messaging/homeassistant)[](/docs/user-guide/messaging/mattermost)[](/docs/user-guide/messaging/matrix)[](/docs/user-guide/messaging/dingtalk)[](/docs/user-guide/messaging/feishu)[](/docs/user-guide/messaging/wecom)[](/docs/user-guide/messaging/wecom-callback)[](/docs/user-guide/messaging/weixin)[](/docs/user-guide/messaging/bluebubbles)[](/docs/user-guide/messaging/qqbot)[](/docs/user-guide/messaging/open-webui)[](/docs/user-guide/messaging/webhooks)
- [[entities/telegram-setup|Telegram Setup]]

- [[entities/discord-setup|Discord Setup]]

- Slack Setup

- WhatsApp Setup

- Signal Setup

- SMS Setup (Twilio)

- Email Setup

- Home Assistant Integration

- Mattermost Setup

- Matrix Setup

- DingTalk Setup

- Feishu/Lark Setup

- WeCom Setup

- WeCom Callback Setup

- Weixin Setup (WeChat)

- BlueBubbles Setup (iMessage)

- QQBot Setup

- Open WebUI + API Server

- Webhooks
[](#platform-comparison)[](#architecture)[](#quick-setup)[](#gateway-commands)[](#chat-commands-inside-messaging)[](#session-management)[](#session-persistence)[](#reset-policies)
- Session Persistence
- Reset Policies
- [[entities/security|Security]]](#[[entities/security|Security]])[](#dm-pairing-alternative-to-allowlists)
- DM Pairing (Alternative to Allowlists)
- [Interrupting the Agent](#interrupting-the-agent)
- [Tool Progress Notifications](#tool-progress-notifications)
- [Background Sessions](#background-sessions)[](#how-it-works)[](#background-process-notifications)[](#use-cases)
- How It Works
- Background Process Notifications
- Use Cases
- [Service Management](#service-management)[](#linux-systemd)[](#macos-launchd)
- Linux (systemd)
- macOS (launchd)
- [Platform-Specific Toolsets](#platform-specific-toolsets)
- [Next Steps](#next-steps)