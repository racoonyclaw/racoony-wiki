---
pageType: entity
id: entity.signal-setup
title: Signal Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/signal.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/signal.md
updatedAt: '2026-04-24T15:05:25.192451+00:00'
sourceIds:
- githubcom
- githubcom
- githubcom
- githubcom
sources:
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/AsamK/signal-cli
  title: '[signal-cli](https://github.com/AsamK/signal-cli)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/AsamK/signal-cli/releases
  title: '[GitHub releases](https://github.com/AsamK/signal-cli/releases)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/AsamK/signal-cli/releases/latest
  title: github.com
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/AsamK/signal-cli/releases/download/v${VERSION}/signal-cli-${VERSION}.tar.gz
  title: github.com
claims:
- id: signal-cli-java-based-signal-client-github
  text: "signal-cli \u2014 Java-based Signal client (GitHub)"
  status: supported
  confidence: null
- id: java-17-runtime-required-by-signal-cli
  text: "Java 17+ runtime \u2014 required by signal-cli"
  status: supported
  confidence: null
- id: a-phone-number-with-signal-installed-for-linking-as-a-secon
  text: A phone number with Signal installed (for linking as a secondary device)
  status: supported
  confidence: null
- id: images-png-jpeg-gif-webp-auto-detected-via-magic-bytes
  text: "Images \u2014 PNG, JPEG, GIF, WebP (auto-detected via magic bytes)"
  status: supported
  confidence: null
- id: audio-mp3-ogg-wav-m4a-voice-messages-transcribed-if-wh
  text: "Audio \u2014 MP3, OGG, WAV, M4A (voice messages transcribed if Whisper is\
    \ configured)"
  status: supported
  confidence: null
- id: documents-pdf-zip-and-other-file-types
  text: "Documents \u2014 PDF, ZIP, and other file types"
  status: supported
  confidence: null
- id: images-send-image-file-sends-png-jpeg-gif-webp-as-nativ
  text: "Images \u2014 send_image_file sends PNG, JPEG, GIF, WebP as native Signal\
    \ attachments"
  status: supported
  confidence: null
- id: voice-send-voice-sends-audio-files-ogg-mp3-wav-m4a-aa
  text: "Voice \u2014 send_voice sends audio files (OGG, MP3, WAV, M4A, AAC) as attachments"
  status: supported
  confidence: null
- id: video-send-video-sends-mp4-video-files
  text: "Video \u2014 send_video sends MP4 video files"
  status: supported
  confidence: null
- id: documents-send-document-sends-any-file-type-pdf-zip-etc
  text: "Documents \u2014 send_document sends any file type (PDF, ZIP, etc.)"
  status: supported
  confidence: null
- id: 15551234567-1554567
  text: "+15551234567 \u2192 +155****4567"
  status: supported
  confidence: null
- id: this-applies-to-both-hermes-gateway-logs-and-the-global-reda
  text: This applies to both Hermes gateway logs and the global redaction system
  status: supported
  confidence: null
- id: note-to-self-messages-arrive-as-syncmessagesentmessage-en
  text: '"Note to Self" messages arrive as syncMessage.sentMessage envelopes'
  status: supported
  confidence: null
- id: the-adapter-detects-when-these-are-addressed-to-the-bots-ow
  text: The adapter detects when these are addressed to the bot's own account and
    processes them as regular inbound messages
  status: supported
  confidence: null
- id: echo-back-protection-sent-timestamp-tracking-prevents-infi
  text: "Echo-back protection (sent-timestamp tracking) prevents infinite loops \u2014\
    \ the bot's own replies are filtered out automatically"
  status: supported
  confidence: null
- id: the-connection-drops-with-exponential-backoff-2s-60s
  text: "The connection drops (with exponential backoff: 2s \u2192 60s)"
  status: supported
  confidence: null
- id: no-activity-is-detected-for-120-seconds-pings-signal-cli-to
  text: No activity is detected for 120 seconds (pings signal-cli to verify)
  status: supported
  confidence: null
- id: phone-numbers-are-redacted-in-all-log-output
  text: Phone numbers are redacted in all log output
  status: supported
  confidence: null
- id: use-dm-pairing-or-explicit-allowlists-for-safe-onboarding-of
  text: Use DM pairing or explicit allowlists for safe onboarding of new users
  status: supported
  confidence: null
- id: keep-groups-disabled-unless-you-specifically-need-group-supp
  text: Keep groups disabled unless you specifically need group support, or allowlist
    only the groups you trust
  status: supported
  confidence: null
- id: signals-end-to-end-encryption-protects-message-content-in-t
  text: Signal's end-to-end encryption protects message content in transit
  status: supported
  confidence: null
- id: the-signal-cli-session-data-in-localsharesignal-cli-co
  text: "The signal-cli session data in ~/.local/share/signal-cli/ contains account\
    \ credentials \u2014 protect it like a password"
  status: supported
  confidence: null
- id: installing-signal-cli
  text: Installing signal-cli
  status: supported
  confidence: null
- id: step-1-link-your-signal-accountstep-1-link-your-signal
  text: '[Step 1: Link Your Signal Account](#step-1-link-your-signal-account)'
  status: supported
  confidence: null
- id: step-2-start-the-signal-cli-daemonstep-2-start-the-sign
  text: '[Step 2: Start the signal-cli Daemon](#step-2-start-the-signal-cli-daemon)'
  status: supported
  confidence: null
- id: step-3-configure-hermesstep-3-configure-hermesmanu
  text: '[Step 3: Configure Hermes](#step-3-configure-hermes)[](#manual-configuration)'
  status: supported
  confidence: null
- id: manual-configuration
  text: Manual Configuration
  status: supported
  confidence: null
- id: access-controlaccess-controldm-accessgroup-acc
  text: '[Access Control](#access-control)[](#dm-access)[](#group-access)'
  status: supported
  confidence: null
- id: group-access
  text: Group Access
  status: supported
  confidence: null
- id: featuresfeaturesattachmentstyping-indicators
  text: '[Features](#features)[](#attachments)[](#typing-indicators)[](#phone-number-redaction)[](#note-to-self-single-number-setup)[](#health-monitoring)'
  status: supported
  confidence: null
- id: attachments
  text: Attachments
  status: supported
  confidence: null
- id: typing-indicators
  text: Typing Indicators
  status: supported
  confidence: null
- id: phone-number-redaction
  text: Phone Number Redaction
  status: supported
  confidence: null
- id: note-to-self-single-number-setup
  text: Note to Self (Single-Number Setup)
  status: supported
  confidence: null
- id: health-monitoring
  text: Health Monitoring
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
- id: environment-variables-referenceenvironment-variables-ref
  text: '[Environment Variables Reference](#environment-variables-reference)'
  status: supported
  confidence: null
---

On this page

Hermes connects to Signal through the [signal-cli](https://github.com/AsamK/signal-cli) daemon running in HTTP mode. The adapter streams messages in real-time via SSE (Server-Sent Events) and sends responses via JSON-RPC.

Signal is the most privacy-focused mainstream messenger — end-to-end encrypted by default, open-source protocol, minimal metadata collection. This makes it ideal for security-sensitive agent workflows.

No New Python Dependencies

The Signal adapter uses httpx (already a core Hermes dependency) for all communication. No additional Python packages are required. You just need signal-cli installed externally.

---

## Prerequisites[​](#prerequisites)

****[](https://github.com/AsamK/signal-cli)********
- signal-cli — Java-based Signal client (GitHub)

- Java 17+ runtime — required by signal-cli

- A phone number with Signal installed (for linking as a secondary device)

### Installing signal-cli[​](#installing-signal-cli)

```prism-code bash codeBlock_bY9V thin-scrollbar
# macOS
brew install signal-cli

# Linux (download latest release)
VERSION=$(curl -Ls -o /dev/null -w %{url_effective} \
 https://github.com/AsamK/signal-cli/releases/latest | sed 's/^.*\/v//')
curl -L -O "https://github.com/AsamK/signal-cli/releases/download/v${VERSION}/signal-cli-${VERSION}.tar.gz"
sudo tar xf "signal-cli-${VERSION}.tar.gz" -C /opt
sudo ln -sf "/opt/signal-cli-${VERSION}/bin/signal-cli" /usr/local/bin/

```

caution

signal-cli is **not** in apt or snap repositories. The Linux install above downloads directly from [GitHub releases](https://github.com/AsamK/signal-cli/releases).

---

## Step 1: Link Your Signal Account[​](#step-1-link-your-signal-account)

Signal-cli works as a **linked device** — like WhatsApp Web, but for Signal. Your phone stays the primary device.

```prism-code bash codeBlock_bY9V thin-scrollbar
# Generate a linking URI (displays a QR code or link)
signal-cli link -n "HermesAgent"

```

************
1. Open Signal on your phone

2. Go to Settings → Linked Devices

3. Tap Link New Device

4. Scan the QR code or enter the URI

---

## Step 2: Start the signal-cli Daemon[​](#step-2-start-the-signal-cli-daemon)

```prism-code bash codeBlock_bY9V thin-scrollbar
# Replace +1234567890 with your Signal phone number (E.164 format)
signal-cli --account +1234567890 daemon --http 127.0.0.1:8080

```

tip

Keep this running in the background. You can use systemd, tmux, screen, or run it as a service.

Verify it's running:

```prism-code bash codeBlock_bY9V thin-scrollbar
curl http://127.0.0.1:8080/api/v1/check
# Should return: {"versions":{"signal-cli":...}}

```

---

## Step 3: Configure Hermes[​](#step-3-configure-hermes)

The easiest way:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Signal** from the platform menu. The wizard will:

1. Check if signal-cli is installed

2. Prompt for the HTTP URL (default: http://127.0.0.1:8080)

3. Test connectivity to the daemon

4. Ask for your account phone number

5. Configure allowed users and access policies

### Manual Configuration[​](#manual-configuration)

Add to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Required
SIGNAL_HTTP_URL=http://127.0.0.1:8080
SIGNAL_ACCOUNT=+1234567890

# Security (recommended)
SIGNAL_ALLOWED_USERS=+1234567890,+0987654321 # Comma-separated E.164 numbers or UUIDs

# Optional
SIGNAL_GROUP_ALLOWED_USERS=groupId1,groupId2 # Enable groups (omit to disable, * for all)
SIGNAL_HOME_CHANNEL=+1234567890 # Default delivery target for cron jobs

```

Then start the gateway:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway # Foreground
hermes gateway install # Install as a user service
sudo hermes gateway install --system # Linux only: boot-time system service

```

---

## Access Control[​](#access-control)

### DM Access[​](#dm-access)

DM access follows the same pattern as all other Hermes platforms:

************
1. SIGNAL_ALLOWED_USERS set → only those users can message

2. No allowlist set → unknown users get a DM pairing code (approve via hermes pairing approve signal CODE)

3. SIGNAL_ALLOW_ALL_USERS=true → anyone can message (use with caution)

### Group Access[​](#group-access)

Group access is controlled by the SIGNAL_GROUP_ALLOWED_USERS env var:

---

## Features[​](#features)

### Attachments[​](#attachments)

The adapter supports sending and receiving media in both directions.

**Incoming** (user → agent):

************
- Images — PNG, JPEG, GIF, WebP (auto-detected via magic bytes)

- Audio — MP3, OGG, WAV, M4A (voice messages transcribed if Whisper is configured)

- Documents — PDF, ZIP, and other file types

**Outgoing** (agent → user):

The agent can send media files via MEDIA: tags in responses. The following delivery methods are supported:

****************
- Images — send_image_file sends PNG, JPEG, GIF, WebP as native Signal attachments

- Voice — send_voice sends audio files (OGG, MP3, WAV, M4A, AAC) as attachments

- Video — send_video sends MP4 video files

- Documents — send_document sends any file type (PDF, ZIP, etc.)

All outgoing media goes through Signal's standard attachment API. Unlike some platforms, Signal does not distinguish between voice messages and file attachments at the protocol level.

Attachment size limit: **100 MB** (both directions).

### Typing Indicators[​](#typing-indicators)

The bot sends typing indicators while processing messages, refreshing every 8 seconds.

### Phone Number Redaction[​](#phone-number-redaction)

All phone numbers are automatically redacted in logs:

- +15551234567 → +155****4567

- This applies to both Hermes gateway logs and the global redaction system

### Note to Self (Single-Number Setup)[​](#note-to-self-single-number-setup)

If you run signal-cli as a **linked secondary device** on your own phone number (rather than a separate bot number), you can interact with Hermes through Signal's "Note to Self" feature.

Just send a message to yourself from your phone — signal-cli picks it up and Hermes responds in the same conversation.

**How it works:**

- "Note to Self" messages arrive as syncMessage.sentMessage envelopes

- The adapter detects when these are addressed to the bot's own account and processes them as regular inbound messages

- Echo-back protection (sent-timestamp tracking) prevents infinite loops — the bot's own replies are filtered out automatically

**No extra configuration needed.** This works automatically as long as SIGNAL_ACCOUNT matches your phone number.

### Health Monitoring[​](#health-monitoring)

The adapter monitors the SSE connection and automatically reconnects if:

- The connection drops (with exponential backoff: 2s → 60s)

- No activity is detected for 120 seconds (pings signal-cli to verify)

---

## Troubleshooting[​](#troubleshooting)

****************************

---

## Security[​](#security)

warning

**Always configure access controls.** The bot has terminal access by default. Without SIGNAL_ALLOWED_USERS or DM pairing, the gateway denies all incoming messages as a safety measure.

- Phone numbers are redacted in all log output

- Use DM pairing or explicit allowlists for safe onboarding of new users

- Keep groups disabled unless you specifically need group support, or allowlist only the groups you trust

- Signal's end-to-end encryption protects message content in transit

- The signal-cli session data in ~/.local/share/signal-cli/ contains account credentials — protect it like a password

---

## Environment Variables Reference[​](#environment-variables-reference)

[](#prerequisites)[](#installing-signal-cli)
- Installing signal-cli
- [Step 1: Link Your Signal Account](#step-1-link-your-signal-account)
- [Step 2: Start the signal-cli Daemon](#step-2-start-the-signal-cli-daemon)
- [Step 3: Configure Hermes](#step-3-configure-hermes)[](#manual-configuration)
- Manual Configuration
- [Access Control](#access-control)[](#dm-access)[](#group-access)
- DM Access
- Group Access
- [Features](#features)[](#attachments)[](#typing-indicators)[](#phone-number-redaction)[](#note-to-self-single-number-setup)[](#health-monitoring)
- Attachments
- Typing Indicators
- Phone Number Redaction
- Note to Self (Single-Number Setup)
- Health Monitoring
- [Troubleshooting](#troubleshooting)
- [Security](#security)
- [Environment Variables Reference](#environment-variables-reference)