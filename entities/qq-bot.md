---
pageType: entity
id: entity.qq-bot
title: QQ Bot
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/qqbot.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/qqbot.md
updatedAt: '2026-04-24T15:05:24.691875+00:00'
sourceIds:
- botqqqcom
- openbigmodelcn
sources:
- sourceId: botqqqcom
  sourceType: web
  sourcePath: https://bot.q.qq.com/wiki/develop/api-v2/
  title: '[Official QQ Bot API](https://bot.q.qq.com/wiki/develop/api-v2/)'
- sourceId: openbigmodelcn
  sourceType: web
  sourcePath: https://open.bigmodel.cn/api/coding/paas/v4
  title: open.bigmodel.cn
claims:
- id: receive-messages-via-a-persistent-websocket-connection-to-th
  text: Receive messages via a persistent WebSocket connection to the QQ Gateway
  status: supported
  confidence: null
- id: send-text-and-markdown-replies-via-the-rest-api
  text: Send text and markdown replies via the REST API
  status: supported
  confidence: null
- id: download-and-process-images-voice-messages-and-file-attach
  text: Download and process images, voice messages, and file attachments
  status: supported
  confidence: null
- id: transcribe-voice-messages-using-tencents-built-in-asr-or-a
  text: Transcribe voice messages using Tencent's built-in ASR or a configurable STT
    provider
  status: supported
  confidence: null
- id: create-a-new-application-and-note-your-app-id-and-app-secret
  text: Create a new application and note your App ID and App Secret
  status: supported
  confidence: null
- id: enable-the-required-intents-c2c-messages-group--messages
  text: 'Enable the required intents: C2C messages, Group @-messages, Guild messages'
  status: supported
  confidence: null
- id: configure-your-bot-in-sandbox-mode-for-testing-or-publish-f
  text: Configure your bot in sandbox mode for testing, or publish for production
  status: supported
  confidence: null
- id: user-openid-1
  text: '"user_openid_1"'
  status: supported
  confidence: null
- id: group-openid-1
  text: '"group_openid_1"'
  status: supported
  confidence: null
- id: zhipuglm-zai-default-provider-uses-glm-asr-model
  text: 'Zhipu/GLM (zai): Default provider, uses glm-asr model'
  status: supported
  confidence: null
- id: openai-whisper-set-qq-stt-base-url-and-qq-stt-model
  text: 'OpenAI Whisper: Set QQ_STT_BASE_URL and QQ_STT_MODEL'
  status: supported
  confidence: null
- id: any-openai-compatible-stt-endpoint
  text: Any OpenAI-compatible STT endpoint
  status: supported
  confidence: null
- id: invalid-app-id-secret-double-check-your-credentials-at-q
  text: "Invalid App ID / Secret \u2014 Double-check your credentials at q.qq.com"
  status: supported
  confidence: null
- id: missing-permissions-ensure-the-bot-has-the-required-intent
  text: "Missing permissions \u2014 Ensure the bot has the required intents enabled"
  status: supported
  confidence: null
- id: sandbox-only-bot-if-the-bot-is-in-sandbox-mode-it-can-onl
  text: "Sandbox-only bot \u2014 If the bot is in sandbox mode, it can only receive\
    \ messages from QQ's sandbox test channel"
  status: supported
  confidence: null
- id: verify-the-bots-intents-are-enabled-at-qqqcom
  text: Verify the bot's intents are enabled at q.qq.com
  status: supported
  confidence: null
- id: check-qq-allowed-users-if-dm-access-is-restricted
  text: Check QQ_ALLOWED_USERS if DM access is restricted
  status: supported
  confidence: null
- id: for-group-messages-ensure-the-bot-is-mentioned-group-poli
  text: For group messages, ensure the bot is @mentioned (group policy may require
    allowlisting)
  status: supported
  confidence: null
- id: check-qqbot-home-channel-for-cronnotification-delivery
  text: Check QQBOT_HOME_CHANNEL for cron/notification delivery
  status: supported
  confidence: null
- id: ensure-aiohttp-and-httpx-are-installed-pip-install-aiohttp
  text: 'Ensure aiohttp and httpx are installed: pip install aiohttp httpx'
  status: supported
  confidence: null
- id: check-network-connectivity-to-apisgroupqqcom-and-the-webs
  text: Check network connectivity to api.sgroup.qq.com and the WebSocket gateway
  status: supported
  confidence: null
- id: review-gateway-logs-for-detailed-error-messages-and-reconnec
  text: Review gateway logs for detailed error messages and reconnect behavior
  status: supported
  confidence: null
- id: interactive-setup
  text: Interactive setup
  status: supported
  confidence: null
- id: manual-configuration
  text: Manual configuration
  status: supported
  confidence: null
- id: environment-variablesenvironment-variables
  text: '[Environment Variables](#environment-variables)'
  status: supported
  confidence: null
- id: advanced-configurationadvanced-configuration
  text: '[Advanced Configuration](#advanced-configuration)'
  status: supported
  confidence: null
- id: voice-messages-sttvoice-messages-stt
  text: '[Voice Messages (STT)](#voice-messages-stt)'
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingbot-disconnects-immed
  text: '[Troubleshooting](#troubleshooting)[](#bot-disconnects-immediately-quick-disconnect)[](#voice-messages-not-transcribed)[](#messages-not-delivered)[](#connection-errors)'
  status: supported
  confidence: null
- id: bot-disconnects-immediately-quick-disconnect
  text: Bot disconnects immediately (quick disconnect)
  status: supported
  confidence: null
- id: voice-messages-not-transcribed
  text: Voice messages not transcribed
  status: supported
  confidence: null
- id: messages-not-delivered
  text: Messages not delivered
  status: supported
  confidence: null
- id: connection-errors
  text: Connection errors
  status: supported
  confidence: null
---

On this page

Connect Hermes to QQ via the **Official QQ Bot API (v2)** — supporting private (C2C), group @-mentions, guild, and direct messages with voice transcription.

## Overview[​](#overview)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

The QQ Bot adapter uses the [Official QQ Bot API](https://bot.q.qq.com/wiki/develop/api-v2/) to:

********
- Receive messages via a persistent WebSocket connection to the QQ Gateway

- Send text and markdown replies via the REST API

- Download and process images, voice messages, and file attachments

- Transcribe voice messages using Tencent's built-in ASR or a configurable STT provider

## Prerequisites[​](#prerequisites)

****[](https://q.qq.com)
********
- Create a new application and note your App ID and App Secret

- Enable the required intents: C2C messages, Group @-messages, Guild messages

- Configure your bot in sandbox mode for testing, or publish for production

-

**Dependencies** — The adapter requires aiohttp and httpx:

```prism-code bash codeBlock_bY9V thin-scrollbar
pip install aiohttp httpx

```

## Configuration[​](#configuration)

### Interactive setup[​](#interactive-setup)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **QQ Bot** from the platform list and follow the prompts.

### Manual configuration[​](#manual-configuration)

Set the required environment variables in ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
QQ_APP_ID=your-app-id
QQ_CLIENT_SECRET=your-app-secret

```

## Environment Variables[​](#environment-variables)

## Advanced Configuration[​](#advanced-configuration)

For fine-grained control, add platform settings to ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 qq:
 enabled: true
 extra:
 app_id: "your-app-id"
 client_secret: "your-secret"
 markdown_support: true # enable QQ markdown (msg_type 2). Config-only; no env-var equivalent.
 dm_policy: "open" # open | allowlist | disabled
 allow_from:
 - "user_openid_1"
 group_policy: "open" # open | allowlist | disabled
 group_allow_from:
 - "group_openid_1"
 stt:
 provider: "zai" # zai (GLM-ASR), openai (Whisper), etc.
 baseUrl: "https://open.bigmodel.cn/api/coding/paas/v4"
 apiKey: "your-stt-key"
 model: "glm-asr"

```

## Voice Messages (STT)[​](#voice-messages-stt)

Voice transcription works in two stages:

****

****
********
- Zhipu/GLM (zai): Default provider, uses glm-asr model

- OpenAI Whisper: Set QQ_STT_BASE_URL and QQ_STT_MODEL

- Any OpenAI-compatible STT endpoint

## Troubleshooting[​](#troubleshooting)

### Bot disconnects immediately (quick disconnect)[​](#bot-disconnects-immediately-quick-disconnect)

This usually means:

************
- Invalid App ID / Secret — Double-check your credentials at q.qq.com

- Missing permissions — Ensure the bot has the required intents enabled

- Sandbox-only bot — If the bot is in sandbox mode, it can only receive messages from QQ's sandbox test channel

### Voice messages not transcribed[​](#voice-messages-not-transcribed)

1. Check if QQ's built-in asr_refer_text is present in the attachment data

2. If using a custom STT provider, verify QQ_STT_API_KEY is set correctly

3. Check gateway logs for STT error messages

### Messages not delivered[​](#messages-not-delivered)

********
- Verify the bot's intents are enabled at q.qq.com

- Check QQ_ALLOWED_USERS if DM access is restricted

- For group messages, ensure the bot is @mentioned (group policy may require allowlisting)

- Check QQBOT_HOME_CHANNEL for cron/notification delivery

### Connection errors[​](#connection-errors)

- Ensure aiohttp and httpx are installed: pip install aiohttp httpx

- Check network connectivity to api.sgroup.qq.com and the WebSocket gateway

- Review gateway logs for detailed error messages and reconnect behavior
[](#overview)[](#prerequisites)[](#configuration)[](#interactive-setup)[](#manual-configuration)
- Interactive setup
- Manual configuration
- [Environment Variables](#environment-variables)
- [Advanced Configuration](#advanced-configuration)
- [Voice Messages (STT)](#voice-messages-stt)
- [Troubleshooting](#troubleshooting)[](#bot-disconnects-immediately-quick-disconnect)[](#voice-messages-not-transcribed)[](#messages-not-delivered)[](#connection-errors)
- Bot disconnects immediately (quick disconnect)
- Voice messages not transcribed
- Messages not delivered
- Connection errors