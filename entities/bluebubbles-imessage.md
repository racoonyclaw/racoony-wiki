---
pageType: entity
id: entity.bluebubbles-imessage
title: BlueBubbles (iMessage)
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/bluebubbles.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/bluebubbles.md
updatedAt: '2026-04-24T15:05:24.747391+00:00'
sourceIds:
- bluebubblesapp
- bluebubblesapp
- docsbluebubblesapp
- docsbluebubblesapp
- '1921681101234'
sources:
- sourceId: bluebubblesapp
  sourceType: web
  sourcePath: https://bluebubbles.app/
  title: '[BlueBubbles](https://bluebubbles.app/)'
- sourceId: bluebubblesapp
  sourceType: web
  sourcePath: https://bluebubbles.app/
  title: '[bluebubbles.app](https://bluebubbles.app/)'
- sourceId: docsbluebubblesapp
  sourceType: web
  sourcePath: https://docs.bluebubbles.app/helper-bundle/installation
  title: '[Private API helper](https://docs.bluebubbles.app/helper-bundle/installation)'
- sourceId: docsbluebubblesapp
  sourceType: web
  sourcePath: https://docs.bluebubbles.app/helper-bundle/installation
  title: '[Private API helper](https://docs.bluebubbles.app/helper-bundle/installation)'
- sourceId: '1921681101234'
  sourceType: web
  sourcePath: http://192.168.1.10:1234
  title: 192.168.1.10:1234
claims:
- id: a-mac-always-on-running-bluebubbles-server
  text: A Mac (always on) running BlueBubbles Server
  status: supported
  confidence: null
- id: apple-id-signed-into-messagesapp-on-that-mac
  text: Apple ID signed into Messages.app on that Mac
  status: supported
  confidence: null
- id: bluebubbles-server-v100-webhooks-require-this-version
  text: BlueBubbles Server v1.0.0+ (webhooks require this version)
  status: supported
  confidence: null
- id: network-connectivity-between-hermes-and-the-bluebubbles-serv
  text: Network connectivity between Hermes and the BlueBubbles server
  status: supported
  confidence: null
- id: server-url-eg-http1921681101234
  text: Server URL (e.g., http://192.168.1.10:1234)
  status: supported
  confidence: null
- id: server-password
  text: Server Password
  status: supported
  confidence: null
- id: inbound-bluebubbles-sends-webhook-events-to-a-local-listene
  text: "Inbound: BlueBubbles sends webhook events to a local listener when new messages\
    \ arrive. No polling \u2014 instant delivery."
  status: supported
  confidence: null
- id: outbound-hermes-sends-messages-via-the-bluebubbles-rest-api
  text: 'Outbound: Hermes sends messages via the BlueBubbles REST API.'
  status: supported
  confidence: null
- id: media-images-voice-messages-videos-and-documents-are-sup
  text: 'Media: Images, voice messages, videos, and documents are supported in both
    directions. Inbound attachments are downloaded and cached locally for the agent
    to process.'
  status: supported
  confidence: null
- id: images-photos-appear-natively-in-the-imessage-conversation
  text: 'Images: Photos appear natively in the iMessage conversation'
  status: supported
  confidence: null
- id: voice-messages-audio-files-sent-as-imessage-voice-messages
  text: 'Voice messages: Audio files sent as iMessage voice messages'
  status: supported
  confidence: null
- id: videos-video-attachments
  text: 'Videos: Video attachments'
  status: supported
  confidence: null
- id: documents-files-sent-as-imessage-attachments
  text: 'Documents: Files sent as iMessage attachments'
  status: supported
  confidence: null
- id: tapback-reactions
  text: Tapback reactions
  status: supported
  confidence: null
- id: typing-indicators
  text: Typing indicators
  status: supported
  confidence: null
- id: read-receipts
  text: Read receipts
  status: supported
  confidence: null
- id: creating-new-chats-by-address
  text: Creating new chats by address
  status: supported
  confidence: null
- id: verify-the-server-url-is-correct-and-the-mac-is-on
  text: Verify the server URL is correct and the Mac is on
  status: supported
  confidence: null
- id: check-that-bluebubbles-server-is-running
  text: Check that BlueBubbles Server is running
  status: supported
  confidence: null
- id: ensure-network-connectivity-firewall-port-forwarding
  text: Ensure network connectivity (firewall, port forwarding)
  status: supported
  confidence: null
- id: check-that-the-webhook-is-registered-in-bluebubbles-server
  text: "Check that the webhook is registered in BlueBubbles Server \u2192 Settings\
    \ \u2192 API \u2192 Webhooks"
  status: supported
  confidence: null
- id: verify-the-webhook-url-is-reachable-from-the-mac
  text: Verify the webhook URL is reachable from the Mac
  status: supported
  confidence: null
- id: check-hermes-logs-gateway-for-webhook-errors-or-hermes-logs
  text: Check hermes logs gateway for webhook errors (or hermes logs -f to follow
    in real-time)
  status: supported
  confidence: null
- id: install-the-private-api-helper-docsbluebubblesapp
  text: 'Install the Private API helper: docs.bluebubbles.app'
  status: supported
  confidence: null
- id: basic-messaging-works-without-it-only-reactions-typing-a
  text: "Basic messaging works without it \u2014 only reactions, typing, and read\
    \ receipts require it"
  status: supported
  confidence: null
- id: 1-install-bluebubbles-server
  text: 1. Install BlueBubbles Server
  status: supported
  confidence: null
- id: 2-get-your-server-url-and-password
  text: 2. Get your Server URL and Password
  status: supported
  confidence: null
- id: 3-configure-hermes
  text: 3. Configure Hermes
  status: supported
  confidence: null
- id: 4-authorize-users
  text: 4. Authorize Users
  status: supported
  confidence: null
- id: 5-start-the-gateway
  text: 5. Start the Gateway
  status: supported
  confidence: null
- id: how-it-workshow-it-works
  text: '[How It Works](#how-it-works)'
  status: supported
  confidence: null
- id: environment-variablesenvironment-variables
  text: '[Environment Variables](#environment-variables)'
  status: supported
  confidence: null
- id: featuresfeaturestext-messagingrich-mediat
  text: '[Features](#features)[](#text-messaging)[](#rich-media)[](#tapback-reactions)[](#typing-indicators)[](#read-receipts)[](#chat-addressing)'
  status: supported
  confidence: null
- id: text-messaging
  text: Text Messaging
  status: supported
  confidence: null
- id: rich-media
  text: Rich Media
  status: supported
  confidence: null
- id: tapback-reactions
  text: Tapback Reactions
  status: supported
  confidence: null
- id: typing-indicators
  text: Typing Indicators
  status: supported
  confidence: null
- id: read-receipts
  text: Read Receipts
  status: supported
  confidence: null
- id: chat-addressing
  text: Chat Addressing
  status: supported
  confidence: null
- id: private-apiprivate-api
  text: '[Private API](#private-api)'
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingcannot-reach-server
  text: '[Troubleshooting](#troubleshooting)[](#cannot-reach-server)[](#messages-not-arriving)[](#private-api-helper-not-connected)'
  status: supported
  confidence: null
- id: cannot-reach-server
  text: '"Cannot reach server"'
  status: supported
  confidence: null
- id: messages-not-arriving
  text: Messages not arriving
  status: supported
  confidence: null
- id: private-api-helper-not-connected
  text: '"Private API helper not connected"'
  status: supported
  confidence: null
---

On this page

Connect Hermes to Apple iMessage via [BlueBubbles](https://bluebubbles.app/) — a free, open-source macOS server that bridges iMessage to any device.

## Prerequisites[​](#prerequisites)

****[](https://bluebubbles.app/)
- A Mac (always on) running BlueBubbles Server

- Apple ID signed into Messages.app on that Mac

- BlueBubbles Server v1.0.0+ (webhooks require this version)

- Network connectivity between Hermes and the BlueBubbles server

## Setup[​](#setup)

### 1. Install BlueBubbles Server[​](#1-install-bluebubbles-server)

Download and install from [bluebubbles.app](https://bluebubbles.app/). Complete the setup wizard — sign in with your Apple ID and configure a connection method (local network, Ngrok, Cloudflare, or Dynamic DNS).

### 2. Get your Server URL and Password[​](#2-get-your-server-url-and-password)

In BlueBubbles Server → **Settings → API**, note:

********
- Server URL (e.g., http://192.168.1.10:1234)

- Server Password

### 3. Configure Hermes[​](#3-configure-hermes)

Run the setup wizard:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **BlueBubbles (iMessage)** and enter your server URL and password.

Or set environment variables directly in ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
BLUEBUBBLES_SERVER_URL=http://192.168.1.10:1234
BLUEBUBBLES_PASSWORD=your-server-password

```

### 4. Authorize Users[​](#4-authorize-users)

Choose one approach:

**DM Pairing (recommended):**
When someone messages your iMessage, Hermes automatically sends them a pairing code. Approve it with:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes pairing approve bluebubbles <CODE>

```

Use hermes pairing list to see pending codes and approved users.

**Pre-authorize specific users** (in ~/.hermes/.env):

```prism-code bash codeBlock_bY9V thin-scrollbar
BLUEBUBBLES_ALLOWED_USERS=user@icloud.com,+15551234567

```

**Open access** (in ~/.hermes/.env):

```prism-code bash codeBlock_bY9V thin-scrollbar
BLUEBUBBLES_ALLOW_ALL_USERS=true

```

### 5. Start the Gateway[​](#5-start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway run

```

Hermes will connect to your BlueBubbles server, register a webhook, and start listening for iMessage messages.

## How It Works[​](#how-it-works)

```prism-code text codeBlock_bY9V thin-scrollbar
iMessage → Messages.app → BlueBubbles Server → Webhook → Hermes
Hermes → BlueBubbles REST API → Messages.app → iMessage

```

************
- Inbound: BlueBubbles sends webhook events to a local listener when new messages arrive. No polling — instant delivery.

- Outbound: Hermes sends messages via the BlueBubbles REST API.

- Media: Images, voice messages, videos, and documents are supported in both directions. Inbound attachments are downloaded and cached locally for the agent to process.

## Environment Variables[​](#environment-variables)

## Features[​](#features)

### Text Messaging[​](#text-messaging)

Send and receive iMessages. Markdown is automatically stripped for clean plain-text delivery.

### Rich Media[​](#rich-media)

****************
- Images: Photos appear natively in the iMessage conversation

- Voice messages: Audio files sent as iMessage voice messages

- Videos: Video attachments

- Documents: Files sent as iMessage attachments

### Tapback Reactions[​](#tapback-reactions)

Love, like, dislike, laugh, emphasize, and question reactions. Requires the BlueBubbles [Private API helper](https://docs.bluebubbles.app/helper-bundle/installation).

### Typing Indicators[​](#typing-indicators)

Shows "typing..." in the iMessage conversation while the agent is processing. Requires Private API.

### Read Receipts[​](#read-receipts)

Automatically marks messages as read after processing. Requires Private API.

### Chat Addressing[​](#chat-addressing)

You can address chats by email or phone number — Hermes resolves them to BlueBubbles chat GUIDs automatically. No need to use raw GUID format.

## Private API[​](#private-api)

Some features require the BlueBubbles [Private API helper](https://docs.bluebubbles.app/helper-bundle/installation):

- Tapback reactions

- Typing indicators

- Read receipts

- Creating new chats by address

Without the Private API, basic text messaging and media still work.

## Troubleshooting[​](#troubleshooting)

### "Cannot reach server"[​](#cannot-reach-server)

- Verify the server URL is correct and the Mac is on

- Check that BlueBubbles Server is running

- Ensure network connectivity (firewall, port forwarding)

### Messages not arriving[​](#messages-not-arriving)

- Check that the webhook is registered in BlueBubbles Server → Settings → API → Webhooks

- Verify the webhook URL is reachable from the Mac

- Check hermes logs gateway for webhook errors (or hermes logs -f to follow in real-time)

### "Private API helper not connected"[​](#private-api-helper-not-connected)

[](https://docs.bluebubbles.app/helper-bundle/installation)
- Install the Private API helper: docs.bluebubbles.app

- Basic messaging works without it — only reactions, typing, and read receipts require it
[](#prerequisites)[](#setup)[](#1-install-bluebubbles-server)[](#2-get-your-server-url-and-password)[](#3-configure-hermes)[](#4-authorize-users)[](#5-start-the-gateway)
- 1. Install BlueBubbles Server
- 2. Get your Server URL and Password
- 3. Configure Hermes
- 4. Authorize Users
- 5. Start the Gateway
- [How It Works](#how-it-works)
- [Environment Variables](#environment-variables)
- [Features](#features)[](#text-messaging)[](#rich-media)[](#tapback-reactions)[](#typing-indicators)[](#read-receipts)[](#chat-addressing)
- Text Messaging
- Rich Media
- Tapback Reactions
- Typing Indicators
- Read Receipts
- Chat Addressing
- [Private API](#private-api)
- [Troubleshooting](#troubleshooting)[](#cannot-reach-server)[](#messages-not-arriving)[](#private-api-helper-not-connected)
- "Cannot reach server"
- Messages not arriving
- "Private API helper not connected"