---
pageType: entity
id: entity.whatsapp-setup
title: WhatsApp Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/whatsapp.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/whatsapp.md
updatedAt: '2026-04-24T15:05:25.230255+00:00'
claims:
- id: use-a-dedicated-phone-number-for-the-bot-not-your-personal
  text: Use a dedicated phone number for the bot (not your personal number)
  status: supported
  confidence: null
- id: dont-send-bulkspam-messages-keep-usage-conversational
  text: "Don't send bulk/spam messages \u2014 keep usage conversational"
  status: supported
  confidence: null
- id: dont-automate-outbound-messaging-to-people-who-havent-mess
  text: Don't automate outbound messaging to people who haven't messaged first
  status: supported
  confidence: null
- id: nodejs-v18-and-npm-the-whatsapp-bridge-runs-as-a-nodejs
  text: "Node.js v18+ and npm \u2014 the WhatsApp bridge runs as a Node.js process"
  status: supported
  confidence: null
- id: a-phone-with-whatsapp-installed-for-scanning-the-qr-code
  text: A phone with WhatsApp installed (for scanning the QR code)
  status: supported
  confidence: null
- id: unauthorized-dm-behavior-pair-is-the-global-default-unknow
  text: 'unauthorized_dm_behavior: pair is the global default. Unknown DM senders
    get a pairing code.'
  status: supported
  confidence: null
- id: whatsappunauthorized-dm-behavior-ignore-makes-whatsapp-sta
  text: 'whatsapp.unauthorized_dm_behavior: ignore makes WhatsApp stay silent for
    unauthorized DMs, which is usually the better choice for a private number.'
  status: supported
  confidence: null
- id: sessions-survive-restarts-you-dont-need-to-re-scan-the-qr
  text: "Sessions survive restarts \u2014 you don't need to re-scan the QR code every\
    \ time"
  status: supported
  confidence: null
- id: the-session-data-includes-encryption-keys-and-device-credent
  text: The session data includes encryption keys and device credentials
  status: supported
  confidence: null
- id: do-not-share-or-commit-this-session-directory-it-grants-fu
  text: "Do not share or commit this session directory \u2014 it grants full access\
    \ to the WhatsApp account"
  status: supported
  confidence: null
- id: incoming-voice-messages-ogg-opus-are-automatically-trans
  text: 'Incoming: Voice messages (.ogg opus) are automatically transcribed using
    the configured STT provider: local faster-whisper, Groq Whisper (GROQ_API_KEY),
    or OpenAI Whisper (VOICE_TOOLS_OPENAI_KEY)'
  status: supported
  confidence: null
- id: outgoing-tts-responses-are-sent-as-mp3-audio-file-attachmen
  text: 'Outgoing: TTS responses are sent as MP3 audio file attachments'
  status: supported
  confidence: null
- id: agent-responses-are-prefixed-with-hermes-agent-by-defaul
  text: "Agent responses are prefixed with \"\u2695 Hermes Agent\" by default. You\
    \ can customize or disable this in config.yaml:"
  status: supported
  confidence: null
- id: the-hermesplatformswhatsappsession-directory-contains
  text: "The ~/.hermes/platforms/whatsapp/session directory contains full session\
    \ credentials \u2014 protect it like a password"
  status: supported
  confidence: null
- id: set-file-permissions-chmod-700-hermesplatformswhatsapp
  text: 'Set file permissions: chmod 700 ~/.hermes/platforms/whatsapp/session'
  status: supported
  confidence: null
- id: use-a-dedicated-phone-number-for-the-bot-to-isolate-risk-fro
  text: Use a dedicated phone number for the bot to isolate risk from your personal
    account
  status: supported
  confidence: null
- id: if-you-suspect-compromise-unlink-the-device-from-whatsapp
  text: "If you suspect compromise, unlink the device from WhatsApp \u2192 Settings\
    \ \u2192 Linked Devices"
  status: supported
  confidence: null
- id: phone-numbers-in-logs-are-partially-redacted-but-review-you
  text: Phone numbers in logs are partially redacted, but review your log retention
    policy
  status: supported
  confidence: null
- id: whatsapp-compatible-markdown
  text: WhatsApp-Compatible Markdown
  status: supported
  confidence: null
- id: tool-progress
  text: Tool Progress
  status: supported
  confidence: null
- id: troubleshootingtroubleshooting
  text: '[Troubleshooting](#troubleshooting)'
  status: supported
  confidence: null
- id: securitysecurity
  text: '[Security](#security)'
  status: supported
  confidence: null
---

On this page

Hermes connects to WhatsApp through a built-in bridge based on **Baileys**. This works by emulating a WhatsApp Web session — **not** through the official WhatsApp Business API. No Meta developer account or Business verification is required.

Unofficial API — Ban Risk

WhatsApp does **not** officially support third-party bots outside the Business API. Using a third-party bridge carries a small risk of account restrictions. To minimize risk:
************
- Use a dedicated phone number for the bot (not your personal number)

- Don't send bulk/spam messages — keep usage conversational

- Don't automate outbound messaging to people who haven't messaged first

WhatsApp Web Protocol Updates

WhatsApp periodically updates their Web protocol, which can temporarily break compatibility
with third-party bridges. When this happens, Hermes will update the bridge dependency. If the
bot stops working after a WhatsApp update, pull the latest Hermes version and re-pair.

## Two Modes[​](#two-modes)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

********

---

## Prerequisites[​](#prerequisites)

************
- Node.js v18+ and npm — the WhatsApp bridge runs as a Node.js process

- A phone with WhatsApp installed (for scanning the QR code)

Unlike older browser-driven bridges, the current Baileys-based bridge does **not** require a local Chromium or Puppeteer dependency stack.

---

## Step 1: Run the Setup Wizard[​](#step-1-run-the-setup-wizard)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes whatsapp

```

The wizard will:

************
1. Ask which mode you want (bot or self-chat)

2. Install bridge dependencies if needed

3. Display a QR code in your terminal

4. Wait for you to scan it

**To scan the QR code:**

********
1. Open WhatsApp on your phone

2. Go to Settings → Linked Devices

3. Tap Link a Device

4. Point your camera at the terminal QR code

Once paired, the wizard confirms the connection and exits. Your session is saved automatically.

tip

If the QR code looks garbled, make sure your terminal is at least 60 columns wide and supports
Unicode. You can also try a different terminal emulator.

---

## Step 2: Getting a Second Phone Number (Bot Mode)[​](#step-2-getting-a-second-phone-number-bot-mode)

For bot mode, you need a phone number that isn't already registered with WhatsApp. Three options:

****[](https://voice.google.com)********

After getting the number:

1. Install WhatsApp on a phone (or use WhatsApp Business app with dual-SIM)

2. Register the new number with WhatsApp

3. Run hermes whatsapp and scan the QR code from that WhatsApp account

---

## Step 3: Configure Hermes[​](#step-3-configure-hermes)

Add the following to your ~/.hermes/.env file:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Required
WHATSAPP_ENABLED=true
WHATSAPP_MODE=bot # "bot" or "self-chat"

# Access control — pick ONE of these options:
WHATSAPP_ALLOWED_USERS=15551234567 # Comma-separated phone numbers (with country code, no +)
# WHATSAPP_ALLOWED_USERS=* # OR use * to allow everyone
# WHATSAPP_ALLOW_ALL_USERS=true # OR set this flag instead (same effect as *)

```

Allow-all shorthand

Setting WHATSAPP_ALLOWED_USERS=* allows **all** senders (equivalent to WHATSAPP_ALLOW_ALL_USERS=true).
This is consistent with [Signal group allowlists](/docs/reference/environment-variables).
To use the pairing flow instead, remove both variables and rely on the
[DM pairing system](/docs/user-guide/security#dm-pairing-system).

Optional behavior settings in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
unauthorized_dm_behavior: pair

whatsapp:
 unauthorized_dm_behavior: ignore

```

- unauthorized_dm_behavior: pair is the global default. Unknown DM senders get a pairing code.

- whatsapp.unauthorized_dm_behavior: ignore makes WhatsApp stay silent for unauthorized DMs, which is usually the better choice for a private number.

Then start the gateway:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway # Foreground
hermes gateway install # Install as a user service
sudo hermes gateway install --system # Linux only: boot-time system service

```

The gateway starts the WhatsApp bridge automatically using the saved session.

---

## Session Persistence[​](#session-persistence)

The Baileys bridge saves its session under ~/.hermes/platforms/whatsapp/session. This means:

********
- Sessions survive restarts — you don't need to re-scan the QR code every time

- The session data includes encryption keys and device credentials

- Do not share or commit this session directory — it grants full access to the WhatsApp account

---

## Re-pairing[​](#re-pairing)

If the session breaks (phone reset, WhatsApp update, manually unlinked), you'll see connection
errors in the gateway logs. To fix it:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes whatsapp

```

This generates a fresh QR code. Scan it again and the session is re-established. The gateway
handles **temporary** disconnections (network blips, phone going offline briefly) automatically
with reconnection logic.

---

## Voice Messages[​](#voice-messages)

Hermes supports voice on WhatsApp:

************
- Incoming: Voice messages (.ogg opus) are automatically transcribed using the configured STT provider: local faster-whisper, Groq Whisper (GROQ_API_KEY), or OpenAI Whisper (VOICE_TOOLS_OPENAI_KEY)

- Outgoing: TTS responses are sent as MP3 audio file attachments

- Agent responses are prefixed with "⚕ Hermes Agent" by default. You can customize or disable this in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
# ~/.hermes/config.yaml
whatsapp:
 reply_prefix: "" # Empty string disables the header
 # reply_prefix: "🤖 *My Bot*\n──────\n" # Custom prefix (supports \n for newlines)

```

---

## Message Formatting & Delivery[​](#message-formatting--delivery)

WhatsApp supports **streaming (progressive) responses** — the bot edits its message in real-time as the AI generates text, just like Discord and Telegram. Internally, WhatsApp is classified as a TIER_MEDIUM platform for delivery capabilities.

### Chunking[​](#chunking)

Long responses are automatically split into multiple messages at **4,096 characters** per chunk (WhatsApp's practical display limit). You don't need to configure anything — the gateway handles splitting and sends chunks sequentially.

### WhatsApp-Compatible Markdown[​](#whatsapp-compatible-markdown)

Standard Markdown in AI responses is automatically converted to WhatsApp's native formatting:

****

Code blocks and inline code are preserved as-is since WhatsApp supports triple-backtick formatting natively.

### Tool Progress[​](#tool-progress)

When the agent calls tools (web search, file operations, etc.), WhatsApp displays real-time progress indicators showing which tool is running. This is enabled by default — no configuration needed.

---

## Troubleshooting[​](#troubleshooting)

****************************[](/docs/user-guide/messaging/#macos-launchd)********

---

## Security[​](#security)

warning

**Configure access control** before going live. Set WHATSAPP_ALLOWED_USERS with specific
phone numbers (including country code, without the +), use * to allow everyone, or set
WHATSAPP_ALLOW_ALL_USERS=true. Without any of these, the gateway **denies all incoming
messages** as a safety measure.

By default, unauthorized DMs still receive a pairing code reply. If you want a private WhatsApp number to stay completely silent to strangers, set:

```prism-code yaml codeBlock_bY9V thin-scrollbar
whatsapp:
 unauthorized_dm_behavior: ignore

```

****
- The ~/.hermes/platforms/whatsapp/session directory contains full session credentials — protect it like a password

- Set file permissions: chmod 700 ~/.hermes/platforms/whatsapp/session

- Use a dedicated phone number for the bot to isolate risk from your personal account

- If you suspect compromise, unlink the device from WhatsApp → Settings → Linked Devices

- Phone numbers in logs are partially redacted, but review your log retention policy
[](#two-modes)[](#prerequisites)[](#step-1-run-the-setup-wizard)[](#step-2-getting-a-second-phone-number-bot-mode)[](#step-3-configure-hermes)[](#session-persistence)[](#re-pairing)[](#voice-messages)[](#message-formatting--delivery)[](#chunking)[](#whatsapp-compatible-markdown)[](#tool-progress)
- Chunking
- WhatsApp-Compatible Markdown
- Tool Progress
- [Troubleshooting](#troubleshooting)
- [Security](#security)