---
pageType: entity
id: entity.feishu-lark-setup
title: Feishu / Lark Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/feishu.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/feishu.md
updatedAt: '2026-04-24T15:05:24.897373+00:00'
sourceIds:
- openfeishucn
- openlarksuitecom
- your-server8765
sources:
- sourceId: openfeishucn
  sourceType: web
  sourcePath: https://open.feishu.cn/
  title: open.feishu.cn
- sourceId: openlarksuitecom
  sourceType: web
  sourcePath: https://open.larksuite.com/
  title: open.larksuite.com
- sourceId: your-server8765
  sourceType: web
  sourcePath: https://your-server:8765/feishu/webhook
  title: your-server:8765
claims:
- id: websocket-recommended-hermes-opens-the-outbound-connectio
  text: "websocket \u2014 recommended; Hermes opens the outbound connection and you\
    \ do not need a public webhook endpoint"
  status: supported
  confidence: null
- id: webhook-useful-when-you-want-feishulark-to-push-events-in
  text: "webhook \u2014 useful when you want Feishu/Lark to push events into your\
    \ gateway over HTTP"
  status: supported
  confidence: null
- id: feishu-httpsopenfeishucn
  text: 'Feishu: https://open.feishu.cn/'
  status: supported
  confidence: null
- id: lark-httpsopenlarksuitecom
  text: 'Lark: https://open.larksuite.com/'
  status: supported
  confidence: null
- id: create-a-new-app
  text: Create a new app.
  status: supported
  confidence: null
- id: in-credentials-basic-info-copy-the-app-id-and-a
  text: In **Credentials & Basic Info**, copy the **App ID** and **App Secret**.
  status: supported
  confidence: null
- id: enable-the-bot-capability-for-the-app
  text: Enable the **Bot** capability for the app.
  status: supported
  confidence: null
- id: run-hermes-gateway-setup-select-feishu-lark-and-ente
  text: Run hermes gateway setup, select **Feishu / Lark**, and enter the credentials
    when prompted.
  status: supported
  confidence: null
- id: feishu-for-feishu-china
  text: feishu for Feishu China
  status: supported
  confidence: null
- id: lark-for-lark-international
  text: lark for Lark international
  status: supported
  confidence: null
- id: button-clicks-become-card-button-key-value
  text: 'Button clicks become: /card button {"key": "value", ...}'
  status: supported
  confidence: null
- id: the-actions-value-payload-from-the-card-definition-is-inclu
  text: The action's value payload from the card definition is included as JSON.
  status: supported
  confidence: null
- id: card-actions-are-deduplicated-with-a-15-minute-window-to-pre
  text: Card actions are deduplicated with a 15-minute window to prevent double processing.
  status: supported
  confidence: null
- id: fetches-the-document-content-and-comment-timeline-in-paralle
  text: Fetches the document content and comment timeline in parallel (20 messages
    for whole-doc threads, 12 for local-selection threads).
  status: supported
  confidence: null
- id: runs-the-agent-with-the-feishu-doc-feishu-drive-toolsets-s
  text: Runs the agent with the feishu_doc + feishu_drive toolsets scoped to that
    single comment session.
  status: supported
  confidence: null
- id: chunks-replies-at-4000-chars-and-posts-them-back-as-threaded
  text: Chunks replies at 4000 chars and posts them back as threaded replies.
  status: supported
  confidence: null
- id: caches-per-document-sessions-for-1-hour-with-a-50-message-ca
  text: Caches per-document sessions for 1 hour with a 50-message cap so follow-up
    comments on the same doc keep context.
  status: supported
  confidence: null
- id: allowlist-a-static-list-of-users-tenants
  text: "allowlist \u2014 a static list of users / tenants."
  status: supported
  confidence: null
- id: pairing-static-list-runtime-approved-store-useful-for-r
  text: "pairing \u2014 static list \u222A runtime-approved store. Useful for rollouts\
    \ where moderators can grant access live."
  status: supported
  confidence: null
- id: subscribe-to-drivenoticecomment-add-v1-in-event-subscripti
  text: Subscribe to drive.notice.comment_add_v1 in Event Subscriptions.
  status: supported
  confidence: null
- id: grant-the-docsdocreadonly-and-drivedrivereadonly-scopes
  text: Grant the docs:doc:readonly and drive:drive:readonly scopes so the handler
    can read document content.
  status: supported
  confidence: null
- id: ogg-opus-uploaded-as-opus-audio
  text: ".ogg, .opus \u2192 uploaded as opus audio"
  status: supported
  confidence: null
- id: mp4-mov-avi-m4v-uploaded-as-mp4-media
  text: ".mp4, .mov, .avi, .m4v \u2192 uploaded as mp4 media"
  status: supported
  confidence: null
- id: pdf-docx-xlsx-pptx-uploaded-with-their-docume
  text: ".pdf, .doc(x), .xls(x), .ppt(x) \u2192 uploaded with their document type"
  status: supported
  confidence: null
- id: everything-else-uploaded-as-a-generic-stream-file
  text: "Everything else \u2192 uploaded as a generic stream file"
  status: supported
  confidence: null
- id: window-60-second-sliding-window
  text: 'Window: 60-second sliding window'
  status: supported
  confidence: null
- id: limit-120-requests-per-window-per-app-id-path-ip-triple
  text: 'Limit: 120 requests per window per (app_id, path, IP) triple'
  status: supported
  confidence: null
- id: tracking-cap-up-to-4096-unique-keys-tracked-prevents-unbou
  text: 'Tracking cap: Up to 4096 unique keys tracked (prevents unbounded memory growth)'
  status: supported
  confidence: null
- id: body-size-limit-1-mb-maximum
  text: 'Body size limit: 1 MB maximum'
  status: supported
  confidence: null
- id: body-read-timeout-30-seconds
  text: 'Body read timeout: 30 seconds'
  status: supported
  confidence: null
- id: content-type-enforcement-only-applicationjson-is-accepted
  text: 'Content-Type enforcement: Only application/json is accepted'
  status: supported
  confidence: null
- id: ou-admin-open-id
  text: '"ou_admin_open_id"'
  status: supported
  confidence: null
- id: ou-user-open-id-1
  text: '"ou_user_open_id_1"'
  status: supported
  confidence: null
- id: ou-user-open-id-2
  text: '"ou_user_open_id_2"'
  status: supported
  confidence: null
- id: ou-blocked-user
  text: '"ou_blocked_user"'
  status: supported
  confidence: null
- id: recommended-scan-to-create-one-command
  text: 'Recommended: Scan-to-Create (one command)'
  status: supported
  confidence: null
- id: alternative-manual-setup
  text: 'Alternative: Manual Setup'
  status: supported
  confidence: null
- id: step-2-choose-a-connection-modestep-2-choose-a-connecti
  text: '[Step 2: Choose a Connection Mode](#step-2-choose-a-connection-mode)[](#recommended-websocket-mode)[](#optional-webhook-mode)'
  status: supported
  confidence: null
- id: recommended-websocket-mode
  text: 'Recommended: WebSocket mode'
  status: supported
  confidence: null
- id: optional-webhook-mode
  text: 'Optional: Webhook mode'
  status: supported
  confidence: null
- id: step-3-configure-hermesstep-3-configure-hermesopti
  text: '[Step 3: Configure Hermes](#step-3-configure-hermes)[](#option-a-interactive-setup)[](#option-b-manual-configuration)'
  status: supported
  confidence: null
- id: option-a-interactive-setup
  text: 'Option A: Interactive Setup'
  status: supported
  confidence: null
- id: option-b-manual-configuration
  text: 'Option B: Manual Configuration'
  status: supported
  confidence: null
- id: step-4-start-the-gatewaystep-4-start-the-gateway
  text: '[Step 4: Start the Gateway](#step-4-start-the-gateway)'
  status: supported
  confidence: null
- id: home-chathome-chat
  text: '[Home Chat](#home-chat)'
  status: supported
  confidence: null
- id: securitysecurityuser-allowlistwebhook-encrypti
  text: '[Security](#security)[](#user-allowlist)[](#webhook-encryption-key)[](#verification-token)'
  status: supported
  confidence: null
- id: user-allowlist
  text: User Allowlist
  status: supported
  confidence: null
- id: webhook-encryption-key
  text: Webhook Encryption Key
  status: supported
  confidence: null
- id: verification-token
  text: Verification Token
  status: supported
  confidence: null
- id: group-message-policygroup-message-policybot-identit
  text: '[Group Message Policy](#group-message-policy)[](#bot-identity-for-mention-gating)'
  status: supported
  confidence: null
- id: bot-identity-for-mention-gating
  text: Bot Identity for @Mention Gating
  status: supported
  confidence: null
- id: interactive-card-actionsinteractive-card-actionsreq
  text: '[Interactive Card Actions](#interactive-card-actions)[](#required-feishu-app-configuration)'
  status: supported
  confidence: null
- id: required-feishu-app-configuration
  text: Required Feishu App Configuration
  status: supported
  confidence: null
- id: document-comment-intelligent-replydocument-comment-intel
  text: '[Document Comment Intelligent Reply](#document-comment-intelligent-reply)[](#3-tier-access-control)[](#required-feishu-app-configuration-1)'
  status: supported
  confidence: null
- id: 3-tier-access-control
  text: 3-Tier Access Control
  status: supported
  confidence: null
- id: required-feishu-app-configuration
  text: Required Feishu App Configuration
  status: supported
  confidence: null
- id: media-supportmedia-supportinbound-receivingout
  text: '[Media Support](#media-support)[](#inbound-receiving)[](#outbound-sending)'
  status: supported
  confidence: null
- id: inbound-receiving
  text: Inbound (receiving)
  status: supported
  confidence: null
- id: outbound-sending
  text: Outbound (sending)
  status: supported
  confidence: null
- id: markdown-rendering-and-post-fallbackmarkdown-rendering-a
  text: '[Markdown Rendering and Post Fallback](#markdown-rendering-and-post-fallback)'
  status: supported
  confidence: null
- id: processing-status-reactionsprocessing-status-reactions
  text: '[Processing Status Reactions](#processing-status-reactions)'
  status: supported
  confidence: null
- id: burst-protection-and-batchingburst-protection-and-batchi
  text: '[Burst Protection and Batching](#burst-protection-and-batching)[](#text-batching)[](#media-batching)[](#per-chat-serialization)'
  status: supported
  confidence: null
- id: text-batching
  text: Text Batching
  status: supported
  confidence: null
- id: media-batching
  text: Media Batching
  status: supported
  confidence: null
- id: per-chat-serialization
  text: Per-Chat Serialization
  status: supported
  confidence: null
- id: rate-limiting-webhook-moderate-limiting-webhook-mode
  text: '[Rate Limiting (Webhook Mode)](#rate-limiting-webhook-mode)[](#webhook-anomaly-tracking)'
  status: supported
  confidence: null
- id: webhook-anomaly-tracking
  text: Webhook Anomaly Tracking
  status: supported
  confidence: null
- id: websocket-tuningwebsocket-tuning
  text: '[WebSocket Tuning](#websocket-tuning)'
  status: supported
  confidence: null
- id: per-group-access-controlper-group-access-control
  text: '[Per-Group Access Control](#per-group-access-control)'
  status: supported
  confidence: null
- id: deduplicationdeduplication
  text: '[Deduplication](#deduplication)'
  status: supported
  confidence: null
- id: all-environment-variablesall-environment-variables
  text: '[All Environment Variables](#all-environment-variables)'
  status: supported
  confidence: null
- id: troubleshootingtroubleshooting
  text: '[Troubleshooting](#troubleshooting)'
  status: supported
  confidence: null
- id: toolsettoolset
  text: '[Toolset](#toolset)'
  status: supported
  confidence: null
---

On this page

Hermes Agent integrates with Feishu and Lark as a full-featured bot. Once connected, you can chat with the agent in direct messages or group chats, receive cron job results in a home chat, and send text, images, audio, and file attachments through the normal gateway flow.

The integration supports both connection modes:

- websocket — recommended; Hermes opens the outbound connection and you do not need a public webhook endpoint

- webhook — useful when you want Feishu/Lark to push events into your gateway over HTTP

## How Hermes Behaves[​](#how-hermes-behaves)

This shared-chat behavior is controlled by config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

Set it to false only if you explicitly want one shared conversation per chat.

## Step 1: Create a Feishu / Lark App[​](#step-1-create-a-feishu--lark-app)

### Recommended: Scan-to-Create (one command)[​](#recommended-scan-to-create-one-command)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Feishu / Lark** and scan the QR code with your Feishu or Lark mobile app. Hermes will automatically create a bot application with the correct permissions and save the credentials.

### Alternative: Manual Setup[​](#alternative-manual-setup)

If scan-to-create is not available, the wizard falls back to manual input:

[](https://open.feishu.cn/)[](https://open.larksuite.com/)
- Feishu: https://open.feishu.cn/

- Lark: https://open.larksuite.com/

- Create a new app.

- In **Credentials & Basic Info**, copy the **App ID** and **App Secret**.

- Enable the **Bot** capability for the app.

- Run hermes gateway setup, select **Feishu / Lark**, and enter the credentials when prompted.

warning

Keep the App Secret private. Anyone with it can impersonate your app.

## Step 2: Choose a Connection Mode[​](#step-2-choose-a-connection-mode)

### Recommended: WebSocket mode[​](#recommended-websocket-mode)

Use WebSocket mode when Hermes runs on your laptop, workstation, or a private server. No public URL is required. The official Lark SDK opens and maintains a persistent outbound WebSocket connection with automatic reconnection.

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_CONNECTION_MODE=websocket

```

**Requirements:** The websockets Python package must be installed. The SDK handles connection lifecycle, heartbeats, and auto-reconnection internally.

**How it works:** The adapter runs the Lark SDK's WebSocket client in a background executor thread. Inbound events (messages, reactions, card actions) are dispatched to the main asyncio loop. On disconnect, the SDK will attempt to reconnect automatically.

### Optional: Webhook mode[​](#optional-webhook-mode)

Use webhook mode only when you already run Hermes behind a reachable HTTP endpoint.

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_CONNECTION_MODE=webhook

```

In webhook mode, Hermes starts an HTTP server (via aiohttp) and serves a Feishu endpoint at:

```prism-code text codeBlock_bY9V thin-scrollbar
/feishu/webhook

```

**Requirements:** The aiohttp Python package must be installed.

You can customize the webhook server bind address and path:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_WEBHOOK_HOST=127.0.0.1 # default: 127.0.0.1
FEISHU_WEBHOOK_PORT=8765 # default: 8765
FEISHU_WEBHOOK_PATH=/feishu/webhook # default: /feishu/webhook

```

When Feishu sends a URL verification challenge (type: url_verification), the webhook responds automatically so you can complete the subscription setup in the Feishu developer console.

## Step 3: Configure Hermes[​](#step-3-configure-hermes)

### Option A: Interactive Setup[​](#option-a-interactive-setup)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Feishu / Lark** and fill in the prompts.

### Option B: Manual Configuration[​](#option-b-manual-configuration)

Add the following to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_APP_ID=cli_xxx
FEISHU_APP_SECRET=secret_xxx
FEISHU_DOMAIN=feishu
FEISHU_CONNECTION_MODE=websocket

# Optional but strongly recommended
FEISHU_ALLOWED_USERS=ou_xxx,ou_yyy
FEISHU_HOME_CHANNEL=oc_xxx

```

FEISHU_DOMAIN accepts:

- feishu for Feishu China

- lark for Lark international

## Step 4: Start the Gateway[​](#step-4-start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

Then message the bot from Feishu/Lark to confirm that the connection is live.

## Home Chat[​](#home-chat)

Use /set-home in a Feishu/Lark chat to mark it as the home channel for cron job results and cross-platform notifications.

You can also preconfigure it:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_HOME_CHANNEL=oc_xxx

```

## Security[​](#security)

### User Allowlist[​](#user-allowlist)

For production use, set an allowlist of Feishu Open IDs:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_ALLOWED_USERS=ou_xxx,ou_yyy

```

If you leave the allowlist empty, anyone who can reach the bot may be able to use it. In group chats, the allowlist is checked against the sender's open_id before the message is processed.

### Webhook Encryption Key[​](#webhook-encryption-key)

When running in webhook mode, set an encryption key to enable signature verification of inbound webhook payloads:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_ENCRYPT_KEY=your-encrypt-key

```

This key is found in the **Event Subscriptions** section of your Feishu app configuration. When set, the adapter verifies every webhook request using the signature algorithm:

```prism-code text codeBlock_bY9V thin-scrollbar
SHA256(timestamp + nonce + encrypt_key + body)

```

The computed hash is compared against the x-lark-signature header using timing-safe comparison. Requests with invalid or missing signatures are rejected with HTTP 401.

tip

In WebSocket mode, signature verification is handled by the SDK itself, so FEISHU_ENCRYPT_KEY is optional. In webhook mode, it is strongly recommended for production.

### Verification Token[​](#verification-token)

An additional layer of authentication that checks the token field inside webhook payloads:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_VERIFICATION_TOKEN=your-verification-token

```

This token is also found in the **Event Subscriptions** section of your Feishu app. When set, every inbound webhook payload must contain a matching token in its header object. Mismatched tokens are rejected with HTTP 401.

Both FEISHU_ENCRYPT_KEY and FEISHU_VERIFICATION_TOKEN can be used together for defense in depth.

## Group Message Policy[​](#group-message-policy)

The FEISHU_GROUP_POLICY environment variable controls whether and how Hermes responds in group chats:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_GROUP_POLICY=allowlist # default

```

In all modes, the bot must be explicitly @mentioned (or @all) in the group before the message is processed. Direct messages bypass this gate.

### Bot Identity for @Mention Gating[​](#bot-identity-for-mention-gating)

For precise @mention detection in groups, the adapter needs to know the bot's identity. It can be provided explicitly:

```prism-code bash codeBlock_bY9V thin-scrollbar
FEISHU_BOT_OPEN_ID=ou_xxx
FEISHU_BOT_USER_ID=xxx
FEISHU_BOT_NAME=MyBot

```

If none of these are set, the adapter will attempt to auto-discover the bot name via the Application Info API on startup. For this to work, grant the admin:app.info:readonly or application:application:self_manage permission scope.

## Interactive Card Actions[​](#interactive-card-actions)

When users click buttons or interact with interactive cards sent by the bot, the adapter routes these as synthetic /card command events:

- Button clicks become: /card button {"key": "value", ...}

- The action's value payload from the card definition is included as JSON.

- Card actions are deduplicated with a 15-minute window to prevent double processing.

Card action events are dispatched with MessageType.COMMAND, so they flow through the normal command processing pipeline.

This is also how **command approval** works — when the agent needs to run a dangerous command, it sends an interactive card with Allow Once / Session / Always / Deny buttons. The user clicks a button, and the card action callback delivers the approval decision back to the agent.

### Required Feishu App Configuration[​](#required-feishu-app-configuration)

Interactive cards require **three** configuration steps in the Feishu Developer Console. Missing any of them causes error **200340** when users click card buttons.

********

************

********

1.
Subscribe to the card action event:
In Event Subscriptions, add card.action.trigger to your subscribed events.

2.
Enable the Interactive Card capability:
In App Features > Bot, ensure the Interactive Card toggle is enabled. This tells Feishu that your app can receive card action callbacks.

3.
Configure the Card Request URL (webhook mode only):
In App Features > Bot > Message Card Request URL, set the URL to the same endpoint as your event webhook (e.g. https://your-server:8765/feishu/webhook). In WebSocket mode this is handled automatically by the SDK.

warning

Without all three steps, Feishu will successfully *send* interactive cards (sending only requires im:message:send permission), but clicking any button will return error 200340. The card appears to work — the error only surfaces when a user interacts with it.

## Document Comment Intelligent Reply[​](#document-comment-intelligent-reply)

Beyond chat, the adapter can also answer @-mentions left on **Feishu/Lark documents**. When a user comments on a document (local text selection or whole-doc comment) and @-mentions the bot, Hermes reads the document plus the surrounding comment thread and posts an LLM reply inline on the thread.

Powered by the drive.notice.comment_add_v1 event, the handler:

- Fetches the document content and comment timeline in parallel (20 messages for whole-doc threads, 12 for local-selection threads).

- Runs the agent with the feishu_doc + feishu_drive toolsets scoped to that single comment session.

- Chunks replies at 4000 chars and posts them back as threaded replies.

- Caches per-document sessions for 1 hour with a 50-message cap so follow-up comments on the same doc keep context.

### 3-Tier Access Control[​](#3-tier-access-control)

Document-comment replies are **explicit-grant only** — there is no implicit allow-all mode. Permissions resolve in this order (first match wins, per field):

************
1. Exact doc — rule scoped to a specific document token.

2. Wildcard — rule that matches a pattern of docs.

3. Top-level — default rule for the workspace.

Two policies are available per rule:

********
- allowlist — a static list of users / tenants.

- pairing — static list ∪ runtime-approved store. Useful for rollouts where moderators can grant access live.

Rules live in ~/.hermes/feishu_comment_rules.json (pairing grants in ~/.hermes/feishu_comment_pairing.json) with mtime-cached hot-reload — edits take effect on the next comment event without restarting the gateway.

CLI:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Inspect current rules and pairing state
python -m gateway.platforms.feishu_comment_rules status

# Simulate an access check for a specific doc + user
python -m gateway.platforms.feishu_comment_rules check <fileType:fileToken> <user_open_id>

# Manage pairing grants at runtime
python -m gateway.platforms.feishu_comment_rules pairing list
python -m gateway.platforms.feishu_comment_rules pairing add <user_open_id>
python -m gateway.platforms.feishu_comment_rules pairing remove <user_open_id>

```

### Required Feishu App Configuration[​](#required-feishu-app-configuration-1)

On top of the chat/card permissions already granted, add the drive comment event:

****
- Subscribe to drive.notice.comment_add_v1 in Event Subscriptions.

- Grant the docs:doc:readonly and drive:drive:readonly scopes so the handler can read document content.

## Media Support[​](#media-support)

### Inbound (receiving)[​](#inbound-receiving)

The adapter receives and caches the following media types from users:

****************

Media from rich-text (post) messages, including inline images and file attachments, is also extracted and cached.

For small text-based documents (.txt, .md), the file content is automatically injected into the message text so the agent can read it directly without needing tools.

### Outbound (sending)[​](#outbound-sending)

File upload routing is automatic based on extension:

- .ogg, .opus → uploaded as opus audio

- .mp4, .mov, .avi, .m4v → uploaded as mp4 media

- .pdf, .doc(x), .xls(x), .ppt(x) → uploaded with their document type

- Everything else → uploaded as a generic stream file

## Markdown Rendering and Post Fallback[​](#markdown-rendering-and-post-fallback)

When outbound text contains markdown formatting (headings, bold, lists, code blocks, links, etc.), the adapter automatically sends it as a Feishu **post** message with an embedded md tag rather than as plain text. This enables rich rendering in the Feishu client.

If the Feishu API rejects the post payload (e.g., due to unsupported markdown constructs), the adapter automatically falls back to sending as plain text with markdown stripped. This two-stage fallback ensures messages are always delivered.

Plain text messages (no markdown detected) are sent as the simple text message type.

## Processing Status Reactions[​](#processing-status-reactions)

While the agent is working, the bot shows a Typing reaction on your message. It's cleared when the reply arrives, or replaced with CrossMark if processing failed.

Set FEISHU_REACTIONS=false to turn it off.

## Burst Protection and Batching[​](#burst-protection-and-batching)

The adapter includes debouncing for rapid message bursts to avoid overwhelming the agent:

### Text Batching[​](#text-batching)

When a user sends multiple text messages in quick succession, they are merged into a single event before being dispatched:

### Media Batching[​](#media-batching)

Multiple media attachments sent in quick succession (e.g., dragging several images) are merged into a single event:

### Per-Chat Serialization[​](#per-chat-serialization)

Messages within the same chat are processed serially (one at a time) to maintain conversation coherence. Each chat has its own lock, so messages in different chats are processed concurrently.

## Rate Limiting (Webhook Mode)[​](#rate-limiting-webhook-mode)

In webhook mode, the adapter enforces per-IP rate limiting to protect against abuse:

************
- Window: 60-second sliding window

- Limit: 120 requests per window per (app_id, path, IP) triple

- Tracking cap: Up to 4096 unique keys tracked (prevents unbounded memory growth)

Requests that exceed the limit receive HTTP 429 (Too Many Requests).

### Webhook Anomaly Tracking[​](#webhook-anomaly-tracking)

The adapter tracks consecutive error responses per IP address. After 25 consecutive errors from the same IP within a 6-hour window, a warning is logged. This helps detect misconfigured clients or probing attempts.

Additional webhook protections:

************
- Body size limit: 1 MB maximum

- Body read timeout: 30 seconds

- Content-Type enforcement: Only application/json is accepted

## WebSocket Tuning[​](#websocket-tuning)

When using websocket mode, you can customize reconnect and ping behavior:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 feishu:
 extra:
 ws_reconnect_interval: 120 # Seconds between reconnect attempts (default: 120)
 ws_ping_interval: 30 # Seconds between WebSocket pings (optional; SDK default if unset)

```

**

## Per-Group Access Control[​](#per-group-access-control)

Beyond the global FEISHU_GROUP_POLICY, you can set fine-grained rules per group chat using group_rules in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 feishu:
 extra:
 default_group_policy: "open" # Default for groups not in group_rules
 admins: # Users who can manage bot settings
 - "ou_admin_open_id"
 group_rules:
 "oc_group_chat_id_1":
 policy: "allowlist" # open | allowlist | blacklist | admin_only | disabled
 allowlist:
 - "ou_user_open_id_1"
 - "ou_user_open_id_2"
 "oc_group_chat_id_2":
 policy: "admin_only"
 "oc_group_chat_id_3":
 policy: "blacklist"
 blacklist:
 - "ou_blocked_user"

```

Groups not listed in group_rules fall back to default_group_policy (defaults to the value of FEISHU_GROUP_POLICY).

## Deduplication[​](#deduplication)

Inbound messages are deduplicated using message IDs with a 24-hour TTL. The dedup state is persisted across restarts to ~/.hermes/feishu_seen_message_ids.json.

## All Environment Variables[​](#all-environment-variables)

************

WebSocket and per-group ACL settings are configured via config.yaml under platforms.feishu.extra (see [WebSocket Tuning](#websocket-tuning) and [Per-Group Access Control](#per-group-access-control) above).

## Troubleshooting[​](#troubleshooting)

********[](#required-feishu-app-configuration)

## Toolset[​](#toolset)

Feishu / Lark uses the hermes-feishu platform preset, which includes the same core tools as Telegram and other gateway-based messaging platforms.
[](#how-hermes-behaves)[](#step-1-create-a-feishu--lark-app)[](#recommended-scan-to-create-one-command)[](#alternative-manual-setup)
- Recommended: Scan-to-Create (one command)
- Alternative: Manual Setup
- [Step 2: Choose a Connection Mode](#step-2-choose-a-connection-mode)[](#recommended-websocket-mode)[](#optional-webhook-mode)
- Recommended: WebSocket mode
- Optional: Webhook mode
- [Step 3: Configure Hermes](#step-3-configure-hermes)[](#option-a-interactive-setup)[](#option-b-manual-configuration)
- Option A: Interactive Setup
- Option B: Manual Configuration
- [Step 4: Start the Gateway](#step-4-start-the-gateway)
- [Home Chat](#home-chat)
- [Security](#security)[](#user-allowlist)[](#webhook-encryption-key)[](#verification-token)
- User Allowlist
- Webhook Encryption Key
- Verification Token
- [Group Message Policy](#group-message-policy)[](#bot-identity-for-mention-gating)
- Bot Identity for @Mention Gating
- [Interactive Card Actions](#interactive-card-actions)[](#required-feishu-app-configuration)
- Required Feishu App Configuration
- [Document Comment Intelligent Reply](#document-comment-intelligent-reply)[](#3-tier-access-control)[](#required-feishu-app-configuration-1)
- 3-Tier Access Control
- Required Feishu App Configuration
- [Media Support](#media-support)[](#inbound-receiving)[](#outbound-sending)
- Inbound (receiving)
- Outbound (sending)
- [Markdown Rendering and Post Fallback](#markdown-rendering-and-post-fallback)
- [Processing Status Reactions](#processing-status-reactions)
- [Burst Protection and Batching](#burst-protection-and-batching)[](#text-batching)[](#media-batching)[](#per-chat-serialization)
- Text Batching
- Media Batching
- Per-Chat Serialization
- [Rate Limiting (Webhook Mode)](#rate-limiting-webhook-mode)[](#webhook-anomaly-tracking)
- Webhook Anomaly Tracking
- [WebSocket Tuning](#websocket-tuning)
- [Per-Group Access Control](#per-group-access-control)
- [Deduplication](#deduplication)
- [All Environment Variables](#all-environment-variables)
- [Troubleshooting](#troubleshooting)
- [Toolset](#toolset)