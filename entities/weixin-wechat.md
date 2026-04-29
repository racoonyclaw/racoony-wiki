---
pageType: entity
id: entity.weixin-wechat
title: Weixin (WeChat)
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/weixin.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/weixin.md
updatedAt: '2026-04-24T15:05:24.784980+00:00'
sourceIds:
- weixinqqcom
sources:
- sourceId: weixinqqcom
  sourceType: web
  sourcePath: https://weixin.qq.com/
  title: '[WeChat](https://weixin.qq.com/)'
claims:
- id: a-personal-wechat-account
  text: A personal WeChat account
  status: supported
  confidence: null
- id: python-packages-aiohttp-and-cryptography
  text: 'Python packages: aiohttp and cryptography'
  status: supported
  confidence: null
- id: terminal-qr-rendering-is-included-when-hermes-is-installed-w
  text: Terminal QR rendering is included when Hermes is installed with the messaging
    extra
  status: supported
  confidence: null
- id: long-poll-transport-no-public-endpoint-webhook-or-websoc
  text: "Long-poll transport \u2014 no public endpoint, webhook, or WebSocket needed"
  status: supported
  confidence: null
- id: qr-code-login-scan-to-connect-setup-via-hermes-gateway-set
  text: "QR code login \u2014 scan-to-connect setup via hermes gateway setup"
  status: supported
  confidence: null
- id: dm-and-group-messaging-configurable-access-policies
  text: "DM and group messaging \u2014 configurable access policies"
  status: supported
  confidence: null
- id: media-support-images-video-files-and-voice-messages
  text: "Media support \u2014 images, video, files, and voice messages"
  status: supported
  confidence: null
- id: aes-128-ecb-encrypted-cdn-automatic-encryptiondecryption
  text: "AES-128-ECB encrypted CDN \u2014 automatic encryption/decryption for all\
    \ media transfers"
  status: supported
  confidence: null
- id: context-token-persistence-disk-backed-reply-continuity-acr
  text: "Context token persistence \u2014 disk-backed reply continuity across restarts"
  status: supported
  confidence: null
- id: markdown-formatting-preserves-markdown-including-headers
  text: "Markdown formatting \u2014 preserves Markdown, including headers, tables,\
    \ and code blocks, so WeChat clients that support Markdown can render it natively"
  status: supported
  confidence: null
- id: smart-message-chunking-messages-stay-as-a-single-bubble-wh
  text: "Smart message chunking \u2014 messages stay as a single bubble when under\
    \ the limit; only oversized payloads split at logical boundaries"
  status: supported
  confidence: null
- id: typing-indicators-shows-typing-status-in-the-wechat-cli
  text: "Typing indicators \u2014 shows \"typing\u2026\" status in the WeChat client\
    \ while the agent processes"
  status: supported
  confidence: null
- id: ssrf-protection-outbound-media-urls-are-validated-before-d
  text: "SSRF protection \u2014 outbound media URLs are validated before download"
  status: supported
  confidence: null
- id: message-deduplication-5-minute-sliding-window-prevents-dou
  text: "Message deduplication \u2014 5-minute sliding window prevents double-processing"
  status: supported
  confidence: null
- id: automatic-retry-with-backoff-recovers-from-transient-api-e
  text: "Automatic retry with backoff \u2014 recovers from transient API errors"
  status: supported
  confidence: null
- id: inbound-encrypted-media-is-downloaded-from-the-cdn-using-en
  text: 'Inbound: Encrypted media is downloaded from the CDN using encrypted_query_param
    URLs, then decrypted with AES-128-ECB using the per-file key provided in the message
    payload.'
  status: supported
  confidence: null
- id: outbound-files-are-encrypted-locally-with-a-random-aes-128
  text: 'Outbound: Files are encrypted locally with a random AES-128-ECB key, uploaded
    to the CDN, and the encrypted reference is included in the outbound message.'
  status: supported
  confidence: null
- id: the-aes-key-is-16-bytes-128-bit-keys-may-arrive-as-raw-ba
  text: "The AES key is 16 bytes (128-bit). Keys may arrive as raw base64 or hex-encoded\
    \ \u2014 the adapter handles both formats."
  status: supported
  confidence: null
- id: this-requires-the-cryptography-python-package
  text: This requires the cryptography Python package.
  status: supported
  confidence: null
- id: tokens-are-saved-per-accountpeer-to-hermesweixinaccoun
  text: Tokens are saved per account+peer to ~/.hermes/weixin/accounts/<account_id>.context-tokens.json
  status: supported
  confidence: null
- id: on-startup-previously-saved-tokens-are-restored
  text: On startup, previously saved tokens are restored
  status: supported
  confidence: null
- id: every-inbound-message-updates-the-stored-token-for-that-send
  text: Every inbound message updates the stored token for that sender
  status: supported
  confidence: null
- id: outbound-messages-automatically-include-the-latest-context-t
  text: Outbound messages automatically include the latest context token
  status: supported
  confidence: null
- id: headers-stay-as-markdown-headings
  text: 'Headers stay as Markdown headings (#, ##, ...)'
  status: supported
  confidence: null
- id: tables-stay-as-markdown-tables
  text: Tables stay as Markdown tables
  status: supported
  confidence: null
- id: code-fences-stay-as-fenced-code-blocks
  text: Code fences stay as fenced code blocks
  status: supported
  confidence: null
- id: excessive-blank-lines-are-collapsed-to-double-newlines-outsi
  text: Excessive blank lines are collapsed to double newlines outside fenced code
    blocks
  status: supported
  confidence: null
- id: maximum-message-length-4000-characters
  text: 'Maximum message length: 4000 characters'
  status: supported
  confidence: null
- id: messages-under-the-limit-stay-intact-even-when-they-contain
  text: Messages under the limit stay intact even when they contain multiple paragraphs
    or line breaks
  status: supported
  confidence: null
- id: oversized-messages-split-at-logical-boundaries-paragraphs
  text: Oversized messages split at logical boundaries (paragraphs, blank lines, code
    fences)
  status: supported
  confidence: null
- id: code-fences-are-kept-intact-whenever-possible-never-split-m
  text: Code fences are kept intact whenever possible (never split mid-block unless
    the fence itself exceeds the limit)
  status: supported
  confidence: null
- id: oversized-individual-blocks-fall-back-to-the-base-adapters
  text: Oversized individual blocks fall back to the base adapter's truncation logic
  status: supported
  confidence: null
- id: a-03-s-inter-chunk-delay-prevents-wechat-rate-limit-drops-w
  text: A 0.3 s inter-chunk delay prevents WeChat rate-limit drops when multiple chunks
    are sent
  status: supported
  confidence: null
- id: 1-run-the-setup-wizard
  text: 1. Run the Setup Wizard
  status: supported
  confidence: null
- id: 2-configure-environment-variables
  text: 2. Configure Environment Variables
  status: supported
  confidence: null
- id: 3-start-the-gateway
  text: 3. Start the Gateway
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
  text: '[Access Policies](#access-policies)[](#dm-policy)[](#group-policy)'
  status: supported
  confidence: null
- id: group-policy
  text: Group Policy
  status: supported
  confidence: null
- id: media-supportmedia-supportinbound-receivingaes
  text: '[Media Support](#media-support)[](#inbound-receiving)[](#aes-128-ecb-encrypted-cdn)[](#outbound-sending)'
  status: supported
  confidence: null
- id: inbound-receiving
  text: Inbound (receiving)
  status: supported
  confidence: null
- id: aes-128-ecb-encrypted-cdn
  text: AES-128-ECB Encrypted CDN
  status: supported
  confidence: null
- id: outbound-sending
  text: Outbound (sending)
  status: supported
  confidence: null
- id: context-token-persistencecontext-token-persistence
  text: '[Context Token Persistence](#context-token-persistence)'
  status: supported
  confidence: null
- id: markdown-formattingmarkdown-formatting
  text: '[Markdown Formatting](#markdown-formatting)'
  status: supported
  confidence: null
- id: message-chunkingmessage-chunking
  text: '[Message Chunking](#message-chunking)'
  status: supported
  confidence: null
- id: typing-indicatorstyping-indicators
  text: '[Typing Indicators](#typing-indicators)'
  status: supported
  confidence: null
- id: long-poll-connectionlong-poll-connectionhow-it-work
  text: '[Long-Poll Connection](#long-poll-connection)[](#how-it-works)[](#retry-behavior)[](#deduplication)[](#token-lock)'
  status: supported
  confidence: null
- id: how-it-works
  text: How It Works
  status: supported
  confidence: null
- id: retry-behavior
  text: Retry Behavior
  status: supported
  confidence: null
- id: deduplication
  text: Deduplication
  status: supported
  confidence: null
- id: token-lock
  text: Token Lock
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

Connect Hermes to [WeChat](https://weixin.qq.com/) (微信), Tencent's personal messaging platform. The adapter uses Tencent's **iLink Bot API** for personal WeChat accounts — this is distinct from WeCom (Enterprise WeChat). Messages are delivered via long-polling, so no public endpoint or webhook is required.

info

This adapter is for **personal WeChat accounts** (微信). If you need enterprise/corporate WeChat, see the [WeCom adapter](/docs/user-guide/messaging/wecom) instead.

## Prerequisites[​](#prerequisites)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

- A personal WeChat account

- Python packages: aiohttp and cryptography

- Terminal QR rendering is included when Hermes is installed with the messaging extra

Install the required dependencies:

```prism-code bash codeBlock_bY9V thin-scrollbar
pip install aiohttp cryptography
# Optional: for terminal QR code display
pip install hermes-agent[messaging]

```

## Setup[​](#setup)

### 1. Run the Setup Wizard[​](#1-run-the-setup-wizard)

The easiest way to connect your WeChat account is through the interactive setup:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Weixin** when prompted. The wizard will:

1. Request a QR code from the iLink Bot API

2. Display the QR code in your terminal (or provide a URL)

3. Wait for you to scan the QR code with the WeChat mobile app

4. Prompt you to confirm the login on your phone

5. Save the account credentials automatically to ~/.hermes/weixin/accounts/

Once confirmed, you'll see a message like:

```prism-code text codeBlock_bY9V thin-scrollbar
微信连接成功，account_id=your-account-id

```

The wizard stores the account_id, token, and base_url so you don't need to configure them manually.

### 2. Configure Environment Variables[​](#2-configure-environment-variables)

After initial QR login, set at minimum the account ID in ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
WEIXIN_ACCOUNT_ID=your-account-id

# Optional: override the token (normally auto-saved from QR login)
# WEIXIN_TOKEN=your-bot-token

# Optional: restrict access
WEIXIN_DM_POLICY=open
WEIXIN_ALLOWED_USERS=user_id_1,user_id_2

# Optional: restore legacy multiline splitting behavior
# WEIXIN_SPLIT_MULTILINE_MESSAGES=true

# Optional: home channel for cron/notifications
WEIXIN_HOME_CHANNEL=chat_id
WEIXIN_HOME_CHANNEL_NAME=Home

```

### 3. Start the Gateway[​](#3-start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

The adapter will restore saved credentials, connect to the iLink API, and begin long-polling for messages.

## Features[​](#features)

************************************************
- Long-poll transport — no public endpoint, webhook, or WebSocket needed

- QR code login — scan-to-connect setup via hermes gateway setup

- DM and group messaging — configurable access policies

- Media support — images, video, files, and voice messages

- AES-128-ECB encrypted CDN — automatic encryption/decryption for all media transfers

- Context token persistence — disk-backed reply continuity across restarts

- Markdown formatting — preserves Markdown, including headers, tables, and code blocks, so WeChat clients that support Markdown can render it natively

- Smart message chunking — messages stay as a single bubble when under the limit; only oversized payloads split at logical boundaries

- Typing indicators — shows "typing…" status in the WeChat client while the agent processes

- SSRF protection — outbound media URLs are validated before download

- Message deduplication — 5-minute sliding window prevents double-processing

- Automatic retry with backoff — recovers from transient API errors

## Configuration Options[​](#configuration-options)

Set these in config.yaml under platforms.weixin.extra:

## Access Policies[​](#access-policies)

### DM Policy[​](#dm-policy)

Controls who can send direct messages to the bot:

```prism-code bash codeBlock_bY9V thin-scrollbar
WEIXIN_DM_POLICY=allowlist
WEIXIN_ALLOWED_USERS=user_id_1,user_id_2

```

### Group Policy[​](#group-policy)

Controls which groups the bot responds in:

```prism-code bash codeBlock_bY9V thin-scrollbar
WEIXIN_GROUP_POLICY=allowlist
WEIXIN_GROUP_ALLOWED_USERS=group_id_1,group_id_2

```

note

The default group policy is disabled for Weixin (unlike WeCom where it defaults to open). This is intentional since personal WeChat accounts may be in many groups.

## Media Support[​](#media-support)

### Inbound (receiving)[​](#inbound-receiving)

The adapter receives media attachments from users, downloads them from the WeChat CDN, decrypts them, and caches them locally for agent processing:

****************

**Quoted messages:** Media from quoted (replied-to) messages is also extracted, so the agent has context about what the user is replying to.

### AES-128-ECB Encrypted CDN[​](#aes-128-ecb-encrypted-cdn)

WeChat media files are transferred through an encrypted CDN. The adapter handles this transparently:

********
- Inbound: Encrypted media is downloaded from the CDN using encrypted_query_param URLs, then decrypted with AES-128-ECB using the per-file key provided in the message payload.

- Outbound: Files are encrypted locally with a random AES-128-ECB key, uploaded to the CDN, and the encrypted reference is included in the outbound message.

- The AES key is 16 bytes (128-bit). Keys may arrive as raw base64 or hex-encoded — the adapter handles both formats.

- This requires the cryptography Python package.

No configuration is needed — encryption and decryption happen automatically.

### Outbound (sending)[​](#outbound-sending)

All outbound media goes through the encrypted CDN upload flow:

1. Generate a random AES-128 key

2. Encrypt the file with AES-128-ECB + PKCS#7 padding

3. Request an upload URL from the iLink API (getuploadurl)

4. Upload the ciphertext to the CDN

5. Send the message with the encrypted media reference

## Context Token Persistence[​](#context-token-persistence)

The iLink Bot API requires a context_token to be echoed back with each outbound message for a given peer. The adapter maintains a disk-backed context token store:

- Tokens are saved per account+peer to ~/.hermes/weixin/accounts/<account_id>.context-tokens.json

- On startup, previously saved tokens are restored

- Every inbound message updates the stored token for that sender

- Outbound messages automatically include the latest context token

This ensures reply continuity even after gateway restarts.

## Markdown Formatting[​](#markdown-formatting)

WeChat clients connected through the iLink Bot API can render Markdown directly, so the adapter preserves Markdown instead of rewriting it:

****************
- Headers stay as Markdown headings (#, ##, ...)

- Tables stay as Markdown tables

- Code fences stay as fenced code blocks

- Excessive blank lines are collapsed to double newlines outside fenced code blocks

## Message Chunking[​](#message-chunking)

Messages are delivered as a single chat message whenever they fit within the platform limit. Only oversized payloads are split for delivery:

****
- Maximum message length: 4000 characters

- Messages under the limit stay intact even when they contain multiple paragraphs or line breaks

- Oversized messages split at logical boundaries (paragraphs, blank lines, code fences)

- Code fences are kept intact whenever possible (never split mid-block unless the fence itself exceeds the limit)

- Oversized individual blocks fall back to the base adapter's truncation logic

- A 0.3 s inter-chunk delay prevents WeChat rate-limit drops when multiple chunks are sent

## Typing Indicators[​](#typing-indicators)

The adapter shows typing status in the WeChat client:

1. When a message arrives, the adapter fetches a typing_ticket via the getconfig API

2. Typing tickets are cached for 10 minutes per user

3. send_typing sends a typing-start signal; stop_typing sends a typing-stop signal

4. The gateway automatically triggers typing indicators while the agent processes a message

## Long-Poll Connection[​](#long-poll-connection)

The adapter uses HTTP long-polling (not WebSocket) to receive messages:

### How It Works[​](#how-it-works)

****************
1. Connect: Validates credentials and starts the poll loop

2. Poll: Calls getupdates with a 35-second timeout; the server holds the request until messages arrive or the timeout expires

3. Dispatch: Inbound messages are dispatched concurrently via asyncio.create_task

4. Sync buffer: A persistent sync cursor (get_updates_buf) is saved to disk so the adapter resumes from the correct position after restarts

### Retry Behavior[​](#retry-behavior)

On API errors, the adapter uses a simple retry strategy:

### Deduplication[​](#deduplication)

Inbound messages are deduplicated using message IDs with a 5-minute window. This prevents double-processing during network hiccups or overlapping poll responses.

### Token Lock[​](#token-lock)

Only one Weixin gateway instance can use a given token at a time. The adapter acquires a scoped lock on startup and releases it on shutdown. If another gateway is already using the same token, startup fails with an informative error message.

## All Environment Variables[​](#all-environment-variables)

****

## Troubleshooting[​](#troubleshooting)

[](#prerequisites)[](#setup)[](#1-run-the-setup-wizard)[](#2-configure-environment-variables)[](#3-start-the-gateway)
- 1. Run the Setup Wizard
- 2. Configure Environment Variables
- 3. Start the Gateway
- [Features](#features)
- [Configuration Options](#configuration-options)
- [Access Policies](#access-policies)[](#dm-policy)[](#group-policy)
- DM Policy
- Group Policy
- [Media Support](#media-support)[](#inbound-receiving)[](#aes-128-ecb-encrypted-cdn)[](#outbound-sending)
- Inbound (receiving)
- AES-128-ECB Encrypted CDN
- Outbound (sending)
- [Context Token Persistence](#context-token-persistence)
- [Markdown Formatting](#markdown-formatting)
- [Message Chunking](#message-chunking)
- [Typing Indicators](#typing-indicators)
- [Long-Poll Connection](#long-poll-connection)[](#how-it-works)[](#retry-behavior)[](#deduplication)[](#token-lock)
- How It Works
- Retry Behavior
- Deduplication
- Token Lock
- [All Environment Variables](#all-environment-variables)
- [Troubleshooting](#troubleshooting)