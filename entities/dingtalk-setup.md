---
pageType: entity
id: entity.dingtalk-setup
title: DingTalk Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/dingtalk.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/dingtalk.md
updatedAt: '2026-04-24T15:05:24.937120+00:00'
claims:
- id: each-dm-gets-its-own-session
  text: each DM gets its own session
  status: supported
  confidence: null
- id: each-user-in-a-shared-group-chat-gets-their-own-session-insi
  text: each user in a shared group chat gets their own session inside that group
  status: supported
  confidence: null
- id: dingtalk-stream-dingtalks-official-sdk-for-stream-mode-w
  text: "dingtalk-stream \u2014 DingTalk's official SDK for Stream Mode (WebSocket-based\
    \ real-time messaging)"
  status: supported
  confidence: null
- id: alibabacloud-dingtalk-dingtalk-openapi-sdk-for-ai-cards-e
  text: "alibabacloud-dingtalk \u2014 DingTalk OpenAPI SDK for AI Cards, emoji reactions,\
    \ and media downloads"
  status: supported
  confidence: null
- id: app-name-eg-hermes-agent
  text: 'App Name: e.g., Hermes Agent'
  status: supported
  confidence: null
- id: description-optional
  text: 'Description: optional'
  status: supported
  confidence: null
- id: after-creating-navigate-to-credentials-basic-info-to
  text: After creating, navigate to **Credentials & Basic Info** to find your **Client
    ID** (AppKey) and **Client Secret** (AppSecret). Copy both.
  status: supported
  confidence: null
- id: qr-code-device-flow-recommended-scan-the-qr-that-prints-i
  text: "QR-code device flow (recommended). Scan the QR that prints in your terminal\
    \ with the DingTalk mobile app \u2014 your Client ID and Client Secret are returned\
    \ automatically and written to ~/.hermes/.env. No developer-console trip needed."
  status: supported
  confidence: null
- id: manual-paste-if-you-already-have-credentials-or-qr-scannin
  text: Manual paste. If you already have credentials (or QR scanning isn't convenient),
    paste your Client ID, Client Secret, and allowed user IDs when prompted.
  status: supported
  confidence: null
- id: group-sessions-per-user-true-keeps-each-participants-conte
  text: 'group_sessions_per_user: true keeps each participant''s context isolated
    inside shared group chats'
  status: supported
  confidence: null
- id: thinking-added-when-the-bot-starts-processing-your-messag
  text: "\U0001F914Thinking \u2014 added when the bot starts processing your message"
  status: supported
  confidence: null
- id: done-added-when-the-response-is-complete-replaces-the-th
  text: "\U0001F973Done \u2014 added when the response is complete (replaces the Thinking\
    \ reaction)"
  status: supported
  confidence: null
- id: stream-mode-no-public-url-domain-name-or-webhook-server-n
  text: 'Stream Mode: No public URL, domain name, or webhook server needed. The connection
    is initiated from your machine via WebSocket, so it works behind NAT and firewalls.'
  status: supported
  confidence: null
- id: ai-cards-optionally-reply-with-rich-ai-cards-instead-of-pla
  text: 'AI Cards: Optionally reply with rich AI Cards instead of plain markdown.
    Configure via card_template_id.'
  status: supported
  confidence: null
- id: emoji-reactions-automatic-thinkingdone-reactions-for-pro
  text: "Emoji Reactions: Automatic \U0001F914Thinking/\U0001F973Done reactions for\
    \ processing status."
  status: supported
  confidence: null
- id: markdown-responses-replies-are-formatted-in-dingtalks-mark
  text: 'Markdown responses: Replies are formatted in DingTalk''s markdown format
    for rich text display.'
  status: supported
  confidence: null
- id: media-support-images-and-files-in-incoming-messages-are-aut
  text: 'Media support: Images and files in incoming messages are automatically resolved
    and can be processed by vision tools.'
  status: supported
  confidence: null
- id: message-deduplication-the-adapter-deduplicates-messages-wit
  text: 'Message deduplication: The adapter deduplicates messages with a 5-minute
    window to prevent processing the same message twice.'
  status: supported
  confidence: null
- id: auto-reconnection-if-the-stream-connection-drops-the-adapt
  text: 'Auto-reconnection: If the stream connection drops, the adapter automatically
    reconnects with exponential backoff.'
  status: supported
  confidence: null
- id: message-length-limit-responses-are-capped-at-20000-charact
  text: 'Message length limit: Responses are capped at 20,000 characters per message.
    Longer responses are truncated.'
  status: supported
  confidence: null
- id: session-model-in-dingtalk
  text: Session Model in DingTalk
  status: supported
  confidence: null
- id: prerequisitesprerequisites
  text: '[Prerequisites](#prerequisites)'
  status: supported
  confidence: null
- id: step-1-create-a-dingtalk-appstep-1-create-a-dingtalk-ap
  text: '[Step 1: Create a DingTalk App](#step-1-create-a-dingtalk-app)'
  status: supported
  confidence: null
- id: step-2-enable-the-robot-capabilitystep-2-enable-the-rob
  text: '[Step 2: Enable the Robot Capability](#step-2-enable-the-robot-capability)'
  status: supported
  confidence: null
- id: step-3-find-your-dingtalk-user-idstep-3-find-your-dingt
  text: '[Step 3: Find Your DingTalk User ID](#step-3-find-your-dingtalk-user-id)'
  status: supported
  confidence: null
- id: step-4-configure-hermes-agentstep-4-configure-hermes-ag
  text: '[Step 4: Configure Hermes Agent](#step-4-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)'
  status: supported
  confidence: null
- id: option-a-interactive-setup-recommended
  text: 'Option A: Interactive Setup (Recommended)'
  status: supported
  confidence: null
- id: option-b-manual-configuration
  text: 'Option B: Manual Configuration'
  status: supported
  confidence: null
- id: start-the-gateway
  text: Start the Gateway
  status: supported
  confidence: null
- id: featuresfeaturesai-cardsemoji-reactionsdi
  text: '[Features](#features)[](#ai-cards)[](#emoji-reactions)[](#display-settings)'
  status: supported
  confidence: null
- id: emoji-reactions
  text: Emoji Reactions
  status: supported
  confidence: null
- id: display-settings
  text: Display Settings
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingbot-is-not-responding
  text: '[Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#dingtalk-stream-not-installed-error)[](#dingtalk_client_id-and-dingtalk_client_secret-required)[](#stream-disconnects--reconnection-loops)[](#bot-is-offline)[](#no-session_webhook-available)'
  status: supported
  confidence: null
- id: bot-is-not-responding-to-messages
  text: Bot is not responding to messages
  status: supported
  confidence: null
- id: dingtalk-stream-not-installed-error
  text: '"dingtalk-stream not installed" error'
  status: supported
  confidence: null
- id: dingtalk-client-id-and-dingtalk-client-secret-required
  text: '"DINGTALK_CLIENT_ID and DINGTALK_CLIENT_SECRET required"'
  status: supported
  confidence: null
- id: stream-disconnects-reconnection-loops
  text: Stream disconnects / reconnection loops
  status: supported
  confidence: null
- id: bot-is-offline
  text: Bot is offline
  status: supported
  confidence: null
- id: no-session-webhook-available
  text: '"No session_webhook available"'
  status: supported
  confidence: null
- id: securitysecurity
  text: '[Security](#security)'
  status: supported
  confidence: null
- id: notesnotes
  text: '[Notes](#notes)'
  status: supported
  confidence: null
---

On this page

Hermes Agent integrates with DingTalk (钉钉) as a chatbot, letting you chat with your AI assistant through direct messages or group chats. The bot connects via DingTalk's Stream Mode — a long-lived WebSocket connection that requires no public URL or webhook server — and replies using markdown-formatted messages through DingTalk's session webhook API.

Before setup, here's the part most people want to know: how Hermes behaves once it's in your DingTalk workspace.

## How Hermes Behaves[​](#how-hermes-behaves)

************

### Session Model in DingTalk[​](#session-model-in-dingtalk)

By default:

- each DM gets its own session

- each user in a shared group chat gets their own session inside that group

This is controlled by config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

Set it to false only if you explicitly want one shared conversation for the entire group:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: false

```

This guide walks you through the full setup process — from creating your DingTalk bot to sending your first message.

## Prerequisites[​](#prerequisites)

Install the required Python packages:

```prism-code bash codeBlock_bY9V thin-scrollbar
pip install "hermes-agent[dingtalk]"

```

Or individually:

```prism-code bash codeBlock_bY9V thin-scrollbar
pip install dingtalk-stream httpx alibabacloud-dingtalk

```

- dingtalk-stream — DingTalk's official SDK for Stream Mode (WebSocket-based real-time messaging)

- httpx — async HTTP client used for sending replies via session webhooks

- alibabacloud-dingtalk — DingTalk OpenAPI SDK for AI Cards, emoji reactions, and media downloads

## Step 1: Create a DingTalk App[​](#step-1-create-a-dingtalk-app)

[](https://open-dev.dingtalk.com/)************************
- App Name: e.g., Hermes Agent

- Description: optional

- After creating, navigate to **Credentials & Basic Info** to find your **Client ID** (AppKey) and **Client Secret** (AppSecret). Copy both.

Credentials shown only once

The Client Secret is only displayed once when you create the app. If you lose it, you'll need to regenerate it. Never share these credentials publicly or commit them to Git.

## Step 2: Enable the Robot Capability[​](#step-2-enable-the-robot-capability)

****************
1. In your app's settings page, go to Add Capability → Robot.

2. Enable the robot capability.

3. Under Message Reception Mode, select Stream Mode (recommended — no public URL needed).

tip

Stream Mode is the recommended setup. It uses a long-lived WebSocket connection initiated from your machine, so you don't need a public IP, domain name, or webhook endpoint. This works behind NAT, firewalls, and on local machines.

## Step 3: Find Your DingTalk User ID[​](#step-3-find-your-dingtalk-user-id)

Hermes Agent uses your DingTalk User ID to control who can interact with the bot. DingTalk User IDs are alphanumeric strings set by your organization's admin.

To find yours:

********
1. Ask your DingTalk organization admin — User IDs are configured in the DingTalk admin console under Contacts → Members.

2. Alternatively, the bot logs the sender_id for each incoming message. Start the gateway, send the bot a message, then check the logs for your ID.

## Step 4: Configure Hermes Agent[​](#step-4-configure-hermes-agent)

### Option A: Interactive Setup (Recommended)[​](#option-a-interactive-setup-recommended)

Run the guided setup command:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **DingTalk** when prompted. The setup wizard can authorize via one of two paths:

********
- QR-code device flow (recommended). Scan the QR that prints in your terminal with the DingTalk mobile app — your Client ID and Client Secret are returned automatically and written to ~/.hermes/.env. No developer-console trip needed.

- Manual paste. If you already have credentials (or QR scanning isn't convenient), paste your Client ID, Client Secret, and allowed user IDs when prompted.

openClaw branding disclosure

Because DingTalk's verification_uri_complete is hardcoded to the openClaw identity at the API layer, the QR currently authorizes under an openClaw source string until Alibaba / DingTalk-Real-AI registers a Hermes-specific template server-side. This is purely how DingTalk presents the consent screen — the bot you create is fully yours and private to your tenant.

### Option B: Manual Configuration[​](#option-b-manual-configuration)

Add the following to your ~/.hermes/.env file:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Required
DINGTALK_CLIENT_ID=your-app-key
DINGTALK_CLIENT_SECRET=your-app-secret

# Security: restrict who can interact with the bot
DINGTALK_ALLOWED_USERS=user-id-1

# Multiple allowed users (comma-separated)
# DINGTALK_ALLOWED_USERS=user-id-1,user-id-2

```

Optional behavior settings in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

- group_sessions_per_user: true keeps each participant's context isolated inside shared group chats

### Start the Gateway[​](#start-the-gateway)

Once configured, start the DingTalk gateway:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

The bot should connect to DingTalk's Stream Mode within a few seconds. Send it a message — either a DM or in a group where it's been added — to test.

tip

You can run hermes gateway in the background or as a systemd service for persistent operation. See the deployment docs for details.

## Features[​](#features)

### AI Cards[​](#ai-cards)

Hermes can reply using DingTalk AI Cards instead of plain markdown messages. Cards provide a richer, more structured display and support streaming updates as the agent generates its response.

To enable AI Cards, configure a card template ID in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 dingtalk:
 enabled: true
 extra:
 card_template_id: "your-card-template-id"

```

You can find your card template ID in the DingTalk Developer Console under your app's AI Card settings. When AI Cards are enabled, all replies are sent as cards with streaming text updates.

### Emoji Reactions[​](#emoji-reactions)

Hermes automatically adds emoji reactions to your messages to show processing status:

- 🤔Thinking — added when the bot starts processing your message

- 🥳Done — added when the response is complete (replaces the Thinking reaction)

These reactions work in both DMs and group chats.

### Display Settings[​](#display-settings)

You can customize DingTalk's display behavior independently from other platforms:

```prism-code yaml codeBlock_bY9V thin-scrollbar
display:
 platforms:
 dingtalk:
 show_reasoning: false # Show model reasoning/thinking in replies
 streaming: true # Enable streaming responses (works with AI Cards)
 tool_progress: all # Show tool execution progress (all/new/off)
 interim_assistant_messages: true # Show intermediate commentary messages

```

To disable tool progress and intermediate messages for a cleaner experience:

```prism-code yaml codeBlock_bY9V thin-scrollbar
display:
 platforms:
 dingtalk:
 tool_progress: off
 interim_assistant_messages: false

```

## Troubleshooting[​](#troubleshooting)

### Bot is not responding to messages[​](#bot-is-not-responding-to-messages)

**Cause**: The robot capability isn't enabled, or DINGTALK_ALLOWED_USERS doesn't include your User ID.

**Fix**: Verify the robot capability is enabled in your app settings and that Stream Mode is selected. Check that your User ID is in DINGTALK_ALLOWED_USERS. Restart the gateway.

### "dingtalk-stream not installed" error[​](#dingtalk-stream-not-installed-error)

**Cause**: The dingtalk-stream Python package is not installed.

**Fix**: Install it:

```prism-code bash codeBlock_bY9V thin-scrollbar
pip install dingtalk-stream httpx

```

### "DINGTALK_CLIENT_ID and DINGTALK_CLIENT_SECRET required"[​](#dingtalk_client_id-and-dingtalk_client_secret-required)

**Cause**: The credentials aren't set in your environment or .env file.

**Fix**: Verify DINGTALK_CLIENT_ID and DINGTALK_CLIENT_SECRET are set correctly in ~/.hermes/.env. The Client ID is your AppKey, and the Client Secret is your AppSecret from the DingTalk Developer Console.

### Stream disconnects / reconnection loops[​](#stream-disconnects--reconnection-loops)

**Cause**: Network instability, DingTalk platform maintenance, or credential issues.

**Fix**: The adapter automatically reconnects with exponential backoff (2s → 5s → 10s → 30s → 60s). Check that your credentials are valid and your app hasn't been deactivated. Verify your network allows outbound WebSocket connections.

### Bot is offline[​](#bot-is-offline)

**Cause**: The Hermes gateway isn't running, or it failed to connect.

**Fix**: Check that hermes gateway is running. Look at the terminal output for error messages. Common issues: wrong credentials, app deactivated, dingtalk-stream or httpx not installed.

### "No session_webhook available"[​](#no-session_webhook-available)

**Cause**: The bot tried to reply but doesn't have a session webhook URL. This typically happens if the webhook expired or the bot was restarted between receiving the message and sending the reply.

**Fix**: Send a new message to the bot — each incoming message provides a fresh session webhook for replies. This is a normal DingTalk limitation; the bot can only reply to messages it has received recently.

## Security[​](#security)

warning

Always set DINGTALK_ALLOWED_USERS to restrict who can interact with the bot. Without it, the gateway denies all users by default as a safety measure. Only add User IDs of people you trust — authorized users have full access to the agent's capabilities, including tool use and system access.

For more information on securing your Hermes Agent deployment, see the [Security Guide](/docs/user-guide/security).

## Notes[​](#notes)

********************************
- Stream Mode: No public URL, domain name, or webhook server needed. The connection is initiated from your machine via WebSocket, so it works behind NAT and firewalls.

- AI Cards: Optionally reply with rich AI Cards instead of plain markdown. Configure via card_template_id.

- Emoji Reactions: Automatic 🤔Thinking/🥳Done reactions for processing status.

- Markdown responses: Replies are formatted in DingTalk's markdown format for rich text display.

- Media support: Images and files in incoming messages are automatically resolved and can be processed by vision tools.

- Message deduplication: The adapter deduplicates messages with a 5-minute window to prevent processing the same message twice.

- Auto-reconnection: If the stream connection drops, the adapter automatically reconnects with exponential backoff.

- Message length limit: Responses are capped at 20,000 characters per message. Longer responses are truncated.
[](#how-hermes-behaves)[](#session-model-in-dingtalk)
- Session Model in DingTalk
- [Prerequisites](#prerequisites)
- [Step 1: Create a DingTalk App](#step-1-create-a-dingtalk-app)
- [Step 2: Enable the Robot Capability](#step-2-enable-the-robot-capability)
- [Step 3: Find Your DingTalk User ID](#step-3-find-your-dingtalk-user-id)
- [Step 4: Configure Hermes Agent](#step-4-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)
- Option A: Interactive Setup (Recommended)
- Option B: Manual Configuration
- Start the Gateway
- [Features](#features)[](#ai-cards)[](#emoji-reactions)[](#display-settings)
- AI Cards
- Emoji Reactions
- Display Settings
- [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#dingtalk-stream-not-installed-error)[](#dingtalk_client_id-and-dingtalk_client_secret-required)[](#stream-disconnects--reconnection-loops)[](#bot-is-offline)[](#no-session_webhook-available)
- Bot is not responding to messages
- "dingtalk-stream not installed" error
- "DINGTALK_CLIENT_ID and DINGTALK_CLIENT_SECRET required"
- Stream disconnects / reconnection loops
- Bot is offline
- "No session_webhook available"
- [Security](#security)
- [Notes](#notes)