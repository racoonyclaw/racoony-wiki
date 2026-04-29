---
pageType: entity
id: entity.wecom-enterprise-wechat
title: WeCom (Enterprise WeChat)
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/wecom.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/wecom.md
updatedAt: '2026-04-24T15:05:24.840446+00:00'
sourceIds:
- workweixinqqcom
sources:
- sourceId: workweixinqqcom
  sourceType: web
  sourcePath: https://work.weixin.qq.com/
  title: '[WeCom](https://work.weixin.qq.com/)'
claims:
- id: a-wecom-organization-account
  text: A WeCom organization account
  status: supported
  confidence: null
- id: an-ai-bot-created-in-the-wecom-admin-console
  text: An AI Bot created in the WeCom Admin Console
  status: supported
  confidence: null
- id: the-bot-id-and-secret-from-the-bots-credentials-page
  text: The Bot ID and Secret from the bot's credentials page
  status: supported
  confidence: null
- id: python-packages-aiohttp-and-httpx
  text: 'Python packages: aiohttp and httpx'
  status: supported
  confidence: null
- id: bot-credentials-via-qr-scan-or-manual-entry
  text: Bot credentials (via QR scan or manual entry)
  status: supported
  confidence: null
- id: access-control-settings-allowlist-pairing-mode-or-open-ac
  text: Access control settings (allowlist, pairing mode, or open access)
  status: supported
  confidence: null
- id: home-channel-for-notifications
  text: Home channel for notifications
  status: supported
  confidence: null
- id: websocket-transport-persistent-connection-no-public-endpo
  text: "WebSocket transport \u2014 persistent connection, no public endpoint needed"
  status: supported
  confidence: null
- id: dm-and-group-messaging-configurable-access-policies
  text: "DM and group messaging \u2014 configurable access policies"
  status: supported
  confidence: null
- id: per-group-sender-allowlists-fine-grained-control-over-who
  text: "Per-group sender allowlists \u2014 fine-grained control over who can interact\
    \ in each group"
  status: supported
  confidence: null
- id: media-support-images-files-voice-video-upload-and-downl
  text: "Media support \u2014 images, files, voice, video upload and download"
  status: supported
  confidence: null
- id: aes-encrypted-media-automatic-decryption-for-inbound-attac
  text: "AES-encrypted media \u2014 automatic decryption for inbound attachments"
  status: supported
  confidence: null
- id: quote-context-preserves-reply-threading
  text: "Quote context \u2014 preserves reply threading"
  status: supported
  confidence: null
- id: markdown-rendering-rich-text-responses
  text: "Markdown rendering \u2014 rich text responses"
  status: supported
  confidence: null
- id: reply-mode-streaming-correlates-responses-to-inbound-messa
  text: "Reply-mode streaming \u2014 correlates responses to inbound message context"
  status: supported
  confidence: null
- id: auto-reconnect-exponential-backoff-on-connection-drops
  text: "Auto-reconnect \u2014 exponential backoff on connection drops"
  status: supported
  confidence: null
- id: group-id-1
  text: '"group_id_1"'
  status: supported
  confidence: null
- id: group-id-2
  text: '"group_id_2"'
  status: supported
  confidence: null
- id: user-alice
  text: '"user_alice"'
  status: supported
  confidence: null
- id: user-bob
  text: '"user_bob"'
  status: supported
  confidence: null
- id: user-charlie
  text: '"user_charlie"'
  status: supported
  confidence: null
- id: user-admin
  text: '"user_admin"'
  status: supported
  confidence: null
- id: when-an-inbound-media-item-includes-an-aeskey-field-the-ada
  text: When an inbound media item includes an aeskey field, the adapter downloads
    the encrypted bytes and decrypts them using AES-256-CBC with PKCS#7 padding.
  status: supported
  confidence: null
- id: the-aes-key-is-the-base64-decoded-value-of-the-aeskey-field
  text: The AES key is the base64-decoded value of the aeskey field (must be exactly
    32 bytes).
  status: supported
  confidence: null
- id: the-iv-is-derived-from-the-first-16-bytes-of-the-key
  text: The IV is derived from the first 16 bytes of the key.
  status: supported
  confidence: null
- id: this-requires-the-cryptography-python-package-pip-install-c
  text: This requires the cryptography Python package (pip install cryptography).
  status: supported
  confidence: null
- id: images-10-mb-sent-as-file
  text: "Images > 10 MB \u2192 sent as file"
  status: supported
  confidence: null
- id: videos-10-mb-sent-as-file
  text: "Videos > 10 MB \u2192 sent as file"
  status: supported
  confidence: null
- id: voice-2-mb-sent-as-file
  text: "Voice > 2 MB \u2192 sent as file"
  status: supported
  confidence: null
- id: non-amr-audio-sent-as-file-wecom-only-supports-amr-for-na
  text: "Non-AMR audio \u2192 sent as file (WeCom only supports AMR for native voice)"
  status: supported
  confidence: null
- id: step-1-create-an-ai-bot
  text: 'Step 1: Create an AI Bot'
  status: supported
  confidence: null
- id: step-2-configure-hermes
  text: 'Step 2: Configure Hermes'
  status: supported
  confidence: null
- id: step-3-start-the-gateway
  text: 'Step 3: Start the gateway'
  status: supported
  confidence: null
- id: featuresfeatures
  text: '[Features](#features)'
  status: supported
  confidence: null
- id: configuration-optionsconfiguration-options
  text: '[Configuration Options](#configuration-options)'
  status: supported
  confidence: null
- id: access-policiesaccess-policiesdm-policygroup-p
  text: '[Access Policies](#access-policies)[](#dm-policy)[](#group-policy)[](#per-group-sender-allowlists)'
  status: supported
  confidence: null
- id: group-policy
  text: Group Policy
  status: supported
  confidence: null
- id: per-group-sender-allowlists
  text: Per-Group Sender Allowlists
  status: supported
  confidence: null
- id: media-supportmedia-supportinbound-receivingaes
  text: '[Media Support](#media-support)[](#inbound-receiving)[](#aes-encrypted-media-decryption)[](#outbound-sending)'
  status: supported
  confidence: null
- id: inbound-receiving
  text: Inbound (receiving)
  status: supported
  confidence: null
- id: aes-encrypted-media-decryption
  text: AES-Encrypted Media Decryption
  status: supported
  confidence: null
- id: outbound-sending
  text: Outbound (sending)
  status: supported
  confidence: null
- id: reply-mode-stream-responsesreply-mode-stream-responses
  text: '[Reply-Mode Stream Responses](#reply-mode-stream-responses)'
  status: supported
  confidence: null
- id: connection-and-reconnectionconnection-and-reconnection
  text: '[Connection and Reconnection](#connection-and-reconnection)[](#connection-lifecycle)[](#reconnection-behavior)[](#deduplication)'
  status: supported
  confidence: null
- id: connection-lifecycle
  text: Connection Lifecycle
  status: supported
  confidence: null
- id: reconnection-behavior
  text: Reconnection Behavior
  status: supported
  confidence: null
- id: deduplication
  text: Deduplication
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
---

On this page

Connect Hermes to [WeCom](https://work.weixin.qq.com/) (企业微信), Tencent's enterprise messaging platform. The adapter uses WeCom's AI Bot WebSocket gateway for real-time bidirectional communication — no public endpoint or webhook needed.

## Prerequisites[​](#prerequisites)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

- A WeCom organization account

- An AI Bot created in the WeCom Admin Console

- The Bot ID and Secret from the bot's credentials page

- Python packages: aiohttp and httpx

## Setup[​](#setup)

### Step 1: Create an AI Bot[​](#step-1-create-an-ai-bot)

#### Recommended: Scan-to-Create (one command)[​](#recommended-scan-to-create-one-command)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **WeCom** and scan the QR code with your WeCom mobile app. Hermes will automatically create a bot application with the correct permissions and save the credentials.

The setup wizard will:

1. Display a QR code in your terminal

2. Wait for you to scan it with the WeCom mobile app

3. Automatically retrieve the Bot ID and Secret

4. Guide you through access control configuration

#### Alternative: Manual Setup[​](#alternative-manual-setup)

If scan-to-create is not available, the wizard falls back to manual input:

[](https://work.weixin.qq.com/wework_admin/frame)************************
1. Log in to the WeCom Admin Console

2. Navigate to Applications → Create Application → AI Bot

3. Configure the bot name and description

4. Copy the Bot ID and Secret from the credentials page

5. Run hermes gateway setup, select WeCom, and enter the credentials when prompted

warning

Keep the Bot Secret private. Anyone with it can impersonate your bot.

### Step 2: Configure Hermes[​](#step-2-configure-hermes)

#### Option A: Interactive Setup (Recommended)[​](#option-a-interactive-setup-recommended)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **WeCom** and follow the prompts. The wizard will guide you through:

- Bot credentials (via QR scan or manual entry)

- Access control settings (allowlist, pairing mode, or open access)

- Home channel for notifications

#### Option B: Manual Configuration[​](#option-b-manual-configuration)

Add the following to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
WECOM_BOT_ID=your-bot-id
WECOM_SECRET=your-secret

# Optional: restrict access
WECOM_ALLOWED_USERS=user_id_1,user_id_2

# Optional: home channel for cron/notifications
WECOM_HOME_CHANNEL=chat_id

```

### Step 3: Start the gateway[​](#step-3-start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

## Features[​](#features)

************************************
- WebSocket transport — persistent connection, no public endpoint needed

- DM and group messaging — configurable access policies

- Per-group sender allowlists — fine-grained control over who can interact in each group

- Media support — images, files, voice, video upload and download

- AES-encrypted media — automatic decryption for inbound attachments

- Quote context — preserves reply threading

- Markdown rendering — rich text responses

- Reply-mode streaming — correlates responses to inbound message context

- Auto-reconnect — exponential backoff on connection drops

## Configuration Options[​](#configuration-options)

Set these in config.yaml under platforms.wecom.extra:

## Access Policies[​](#access-policies)

### DM Policy[​](#dm-policy)

Controls who can send direct messages to the bot:

```prism-code bash codeBlock_bY9V thin-scrollbar
WECOM_DM_POLICY=allowlist

```

### Group Policy[​](#group-policy)

Controls which groups the bot responds in:

```prism-code bash codeBlock_bY9V thin-scrollbar
WECOM_GROUP_POLICY=allowlist

```

### Per-Group Sender Allowlists[​](#per-group-sender-allowlists)

For fine-grained control, you can restrict which users are allowed to interact with the bot within specific groups. This is configured in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 wecom:
 enabled: true
 extra:
 bot_id: "your-bot-id"
 secret: "your-secret"
 group_policy: "allowlist"
 group_allow_from:
 - "group_id_1"
 - "group_id_2"
 groups:
 group_id_1:
 allow_from:
 - "user_alice"
 - "user_bob"
 group_id_2:
 allow_from:
 - "user_charlie"
 "*":
 allow_from:
 - "user_admin"

```

**How it works:**

1. The group_policy and group_allow_from controls determine whether a group is allowed at all.

2. If a group passes the top-level check, the groups.<group_id>.allow_from list (if present) further restricts which senders within that group can interact with the bot.

3. A wildcard "*" group entry serves as a default for groups not explicitly listed.

4. Allowlist entries support the * wildcard to allow all users, and entries are case-insensitive.

5. Entries can optionally use the wecom:user: or wecom:group: prefix format — the prefix is stripped automatically.

If no allow_from is configured for a group, all users in that group are allowed (assuming the group itself passes the top-level policy check).

## Media Support[​](#media-support)

### Inbound (receiving)[​](#inbound-receiving)

The adapter receives media attachments from users and caches them locally for agent processing:

****************

**Quoted messages:** Media from quoted (replied-to) messages is also extracted, so the agent has context about what the user is replying to.

### AES-Encrypted Media Decryption[​](#aes-encrypted-media-decryption)

WeCom encrypts some inbound media attachments with AES-256-CBC. The adapter handles this automatically:

- When an inbound media item includes an aeskey field, the adapter downloads the encrypted bytes and decrypts them using AES-256-CBC with PKCS#7 padding.

- The AES key is the base64-decoded value of the aeskey field (must be exactly 32 bytes).

- The IV is derived from the first 16 bytes of the key.

- This requires the cryptography Python package (pip install cryptography).

No configuration is needed — decryption happens transparently when encrypted media is received.

### Outbound (sending)[​](#outbound-sending)

**Chunked upload:** Files are uploaded in 512 KB chunks through a three-step protocol (init → chunks → finish). The adapter handles this automatically.

**Automatic downgrade:** When media exceeds the native type's size limit but is under the absolute 20 MB file limit, it is automatically sent as a generic file attachment instead:

- Images > 10 MB → sent as file

- Videos > 10 MB → sent as file

- Voice > 2 MB → sent as file

- Non-AMR audio → sent as file (WeCom only supports AMR for native voice)

Files exceeding the absolute 20 MB limit are rejected with an informational message sent to the chat.

## Reply-Mode Stream Responses[​](#reply-mode-stream-responses)

When the bot receives a message via the WeCom callback, the adapter remembers the inbound request ID. If a response is sent while the request context is still active, the adapter uses WeCom's reply-mode (aibot_respond_msg) with streaming to correlate the response directly to the inbound message. This provides a more natural conversation experience in the WeCom client.

If the inbound request context has expired or is unavailable, the adapter falls back to proactive message sending via aibot_send_msg.

Reply-mode also works for media: uploaded media can be sent as a reply to the originating message.

## Connection and Reconnection[​](#connection-and-reconnection)

The adapter maintains a persistent WebSocket connection to WeCom's gateway at wss://openws.work.weixin.qq.com.

### Connection Lifecycle[​](#connection-lifecycle)

************
1. Connect: Opens a WebSocket connection and sends an aibot_subscribe authentication frame with the bot_id and secret.

2. Heartbeat: Sends application-level ping frames every 30 seconds to keep the connection alive.

3. Listen: Continuously reads inbound frames and dispatches message callbacks.

### Reconnection Behavior[​](#reconnection-behavior)

On connection loss, the adapter uses exponential backoff to reconnect:

After each successful reconnection, the backoff counter resets to zero. All pending request futures are failed on disconnect so callers don't hang indefinitely.

### Deduplication[​](#deduplication)

Inbound messages are deduplicated using message IDs with a 5-minute window and a maximum cache of 1000 entries. This prevents double-processing of messages during reconnection or network hiccups.

## All Environment Variables[​](#all-environment-variables)

**

## Troubleshooting[​](#troubleshooting)

[](#prerequisites)[](#setup)[](#step-1-create-an-ai-bot)[](#step-2-configure-hermes)[](#step-3-start-the-gateway)
- Step 1: Create an AI Bot
- Step 2: Configure Hermes
- Step 3: Start the gateway
- [Features](#features)
- [Configuration Options](#configuration-options)
- [Access Policies](#access-policies)[](#dm-policy)[](#group-policy)[](#per-group-sender-allowlists)
- DM Policy
- Group Policy
- Per-Group Sender Allowlists
- [Media Support](#media-support)[](#inbound-receiving)[](#aes-encrypted-media-decryption)[](#outbound-sending)
- Inbound (receiving)
- AES-Encrypted Media Decryption
- Outbound (sending)
- [Reply-Mode Stream Responses](#reply-mode-stream-responses)
- [Connection and Reconnection](#connection-and-reconnection)[](#connection-lifecycle)[](#reconnection-behavior)[](#deduplication)
- Connection Lifecycle
- Reconnection Behavior
- Deduplication
- [All Environment Variables](#all-environment-variables)
- [Troubleshooting](#troubleshooting)