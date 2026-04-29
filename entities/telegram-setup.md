---
pageType: entity
id: entity.telegram-setup
title: Telegram Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/telegram.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/telegram.md
updatedAt: '2026-04-24T15:05:25.358230+00:00'
sourceIds:
- python-telegram-boto
- tme
- tme
- tme
- my-appflydev
- tme
- proxyexamplecom8080
sources:
- sourceId: python-telegram-boto
  sourceType: web
  sourcePath: https://python-telegram-bot.org/
  title: '[python-telegram-bot](https://python-telegram-bot.org/)'
- sourceId: tme
  sourceType: web
  sourcePath: https://t.me/BotFather
  title: '[@BotFather](https://t.me/BotFather)'
- sourceId: tme
  sourceType: web
  sourcePath: https://t.me/userinfobot
  title: '[@userinfobot](https://t.me/userinfobot)'
- sourceId: tme
  sourceType: web
  sourcePath: https://t.me/get_id_bot
  title: '[@get_id_bot](https://t.me/get_id_bot)'
- sourceId: my-appflydev
  sourceType: web
  sourcePath: https://my-app.fly.dev/telegram
  title: my-app.fly.dev
- sourceId: ''
  sourceType: web
  sourcePath: http://,
  title: ','
- sourceId: ''
  sourceType: web
  sourcePath: https://,
  title: ','
- sourceId: tme
  sourceType: web
  sourcePath: https://t.me/c/1234567890/5
  title: t.me
- sourceId: proxyexamplecom8080
  sourceType: web
  sourcePath: http://proxy.example.com:8080
  title: proxy.example.com:8080
claims:
- id: messages-that-start-with-a-command
  text: Messages that start with a / command
  status: supported
  confidence: null
- id: replies-directly-to-the-bots-own-messages
  text: Replies directly to the bot's own messages
  status: supported
  confidence: null
- id: service-messages-member-joinsleaves-pinned-messages-etc
  text: Service messages (member joins/leaves, pinned messages, etc.)
  status: supported
  confidence: null
- id: messages-in-channels-where-the-bot-is-an-admin
  text: Messages in channels where the bot is an admin
  status: supported
  confidence: null
- id: the-agent-writes-a-file-inside-docker-to-workspacereportt
  text: the agent writes a file inside Docker to /workspace/report.txt
  status: supported
  confidence: null
- id: the-model-emits-mediaworkspacereporttxt
  text: the model emits MEDIA:/workspace/report.txt
  status: supported
  confidence: null
- id: telegram-delivery-fails-because-workspacereporttxt-only-e
  text: Telegram delivery fails because /workspace/report.txt only exists inside the
  status: supported
  confidence: null
- id: homeuserhermescachedocumentsoutput
  text: '"/home/user/.hermes/cache/documents:/output"'
  status: supported
  confidence: null
- id: write-files-inside-docker-to-output
  text: write files inside Docker to /output/...
  status: supported
  confidence: null
- id: emit-the-host-visible-path-in-media-for-example
  text: 'emit the host-visible path in MEDIA:, for example:'
  status: supported
  confidence: null
- id: local-uses-faster-whisper-on-the-machine-running-hermes-no
  text: "local uses faster-whisper on the machine running Hermes \u2014 no API key\
    \ required"
  status: supported
  confidence: null
- id: groq-uses-groq-whisper-and-requires-groq-api-key
  text: groq uses Groq Whisper and requires GROQ_API_KEY
  status: supported
  confidence: null
- id: openai-uses-openai-whisper-and-requires-voice-tools-openai-k
  text: openai uses OpenAI Whisper and requires VOICE_TOOLS_OPENAI_KEY
  status: supported
  confidence: null
- id: openai-and-elevenlabs-produce-opus-natively-no-extra-setup
  text: "OpenAI and ElevenLabs produce Opus natively \u2014 no extra setup needed"
  status: supported
  confidence: null
- id: edge-tts-the-default-free-provider-outputs-mp3-and-require
  text: 'Edge TTS (the default free provider) outputs MP3 and requires ffmpeg to convert
    to Opus:'
  status: supported
  confidence: null
- id: slash-commands
  text: slash commands
  status: supported
  confidence: null
- id: replies-to-one-of-the-bots-messages
  text: replies to one of the bot's messages
  status: supported
  confidence: null
- id: botusername-mentions
  text: '@botusername mentions'
  status: supported
  confidence: null
- id: matches-for-one-of-your-configured-regex-wake-words-in-teleg
  text: matches for one of your configured regex wake words in telegram.mention_patterns
  status: supported
  confidence: null
- id: use-telegramignored-threads-to-keep-hermes-silent-in-specif
  text: Use telegram.ignored_threads to keep Hermes silent in specific Telegram forum
    topics, even when the group would otherwise allow free responses or mention-triggered
    replies
  status: supported
  confidence: null
- id: if-telegramrequire-mention-is-left-unset-or-false-hermes-k
  text: If telegram.require_mention is left unset or false, Hermes keeps the previous
    open-group behavior and responds to normal group messages it can see
  status: supported
  confidence: null
- id: schompyb
  text: '"^\\s*chompy\\b"'
  status: supported
  confidence: null
- id: patterns-use-python-regular-expressions
  text: Patterns use Python regular expressions
  status: supported
  confidence: null
- id: matching-is-case-insensitive
  text: Matching is case-insensitive
  status: supported
  confidence: null
- id: patterns-are-checked-against-both-text-messages-and-media-ca
  text: Patterns are checked against both text messages and media captions
  status: supported
  confidence: null
- id: invalid-regex-patterns-are-ignored-with-a-warning-in-the-gat
  text: Invalid regex patterns are ignored with a warning in the gateway logs rather
    than crashing the bot
  status: supported
  confidence: null
- id: if-you-want-a-pattern-to-match-only-at-the-start-of-a-messag
  text: If you want a pattern to match only at the start of a message, anchor it with
    ^
  status: supported
  confidence: null
- id: topic-website-work-on-your-production-web-service
  text: "Topic \"Website\" \u2014 work on your production web service"
  status: supported
  confidence: null
- id: topic-research-literature-review-and-paper-exploration
  text: "Topic \"Research\" \u2014 literature review and paper exploration"
  status: supported
  confidence: null
- id: topic-general-miscellaneous-tasks-and-quick-questions
  text: "Topic \"General\" \u2014 miscellaneous tasks and quick questions"
  status: supported
  confidence: null
- id: chat-id-123456789-your-telegram-user-id
  text: 'chat_id: 123456789 # Your Telegram user ID'
  status: supported
  confidence: null
- id: name-general
  text: 'name: General'
  status: supported
  confidence: null
- id: name-website
  text: 'name: Website'
  status: supported
  confidence: null
- id: name-research
  text: 'name: Research'
  status: supported
  confidence: null
- id: engineering-topic-auto-loads-the-software-development-skil
  text: "Engineering topic \u2192 auto-loads the software-development skill"
  status: supported
  confidence: null
- id: research-topic-auto-loads-the-arxiv-skill
  text: "Research topic \u2192 auto-loads the arxiv skill"
  status: supported
  confidence: null
- id: general-topic-no-skill-general-purpose-assistant
  text: "General topic \u2192 no skill, general-purpose assistant"
  status: supported
  confidence: null
- id: chat-id--1001234567890-supergroup-id
  text: 'chat_id: -1001234567890 # Supergroup ID'
  status: supported
  confidence: null
- id: name-engineering
  text: 'name: Engineering'
  status: supported
  confidence: null
- id: name-research
  text: 'name: Research'
  status: supported
  confidence: null
- id: name-general
  text: 'name: General'
  status: supported
  confidence: null
- id: bot-api-94-feb-2026-private-chat-topics-bots-can-creat
  text: "Bot API 9.4 (Feb 2026): Private Chat Topics \u2014 bots can create forum\
    \ topics in 1-on-1 DM chats via createForumTopic. See Private Chat Topics above."
  status: supported
  confidence: null
- id: privacy-policy-telegram-now-requires-bots-to-have-a-privacy
  text: 'Privacy policy: Telegram now requires bots to have a privacy policy. Set
    one via BotFather with /setprivacy_policy, or Telegram may auto-generate a placeholder.
    This is particularly important if your bot is public-facing.'
  status: supported
  confidence: null
- id: message-streaming-bot-api-9x-added-support-for-streaming-l
  text: 'Message streaming: Bot API 9.x added support for streaming long responses,
    which can improve perceived latency for lengthy agent replies.'
  status: supported
  confidence: null
- id: '149154167220'
  text: '"149.154.167.220"'
  status: supported
  confidence: null
- id: when-the-bot-starts-processing-your-message
  text: "\U0001F440 when the bot starts processing your message"
  status: supported
  confidence: null
- id: when-the-response-is-delivered-successfully
  text: "\u2705 when the response is delivered successfully"
  status: supported
  confidence: null
- id: if-an-error-occurs-during-processing
  text: "\u274C if an error occurs during processing"
  status: supported
  confidence: null
- id: message-in-topic-42-inside-group--1001234567890-uses-topic
  text: "Message in topic 42 inside group -1001234567890 \u2192 uses topic 42's prompt"
  status: supported
  confidence: null
- id: message-in-topic-99-no-explicit-entry-falls-back-to-grou
  text: "Message in topic 99 (no explicit entry) \u2192 falls back to group -1001234567890's\
    \ prompt"
  status: supported
  confidence: null
- id: message-in-a-group-with-no-entry-no-channel-prompt-applied
  text: "Message in a group with no entry \u2192 no channel prompt applied"
  status: supported
  confidence: null
- id: how-to-disable-privacy-mode
  text: How to disable privacy mode
  status: supported
  confidence: null
- id: step-4-find-your-user-idstep-4-find-your-user-id
  text: '[Step 4: Find Your User ID](#step-4-find-your-user-id)'
  status: supported
  confidence: null
- id: step-5-configure-hermesstep-5-configure-hermesopti
  text: '[Step 5: Configure Hermes](#step-5-configure-hermes)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)'
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
- id: sending-generated-files-from-docker-backed-terminalssend
  text: '[Sending Generated Files from Docker-backed Terminals](#sending-generated-files-from-docker-backed-terminals)'
  status: supported
  confidence: null
- id: webhook-modewebhook-modeconfigurationcloud-dep
  text: '[Webhook Mode](#webhook-mode)[](#configuration)[](#cloud-deployment-example-flyio)'
  status: supported
  confidence: null
- id: configuration
  text: Configuration
  status: supported
  confidence: null
- id: cloud-deployment-example-flyio
  text: Cloud deployment example (Fly.io)
  status: supported
  confidence: null
- id: proxy-supportproxy-support
  text: '[Proxy Support](#proxy-support)'
  status: supported
  confidence: null
- id: home-channelhome-channel
  text: '[Home Channel](#home-channel)'
  status: supported
  confidence: null
- id: voice-messagesvoice-messagesincoming-voice-speech-t
  text: '[Voice Messages](#voice-messages)[](#incoming-voice-speech-to-text)[](#outgoing-voice-text-to-speech)'
  status: supported
  confidence: null
- id: incoming-voice-speech-to-text
  text: Incoming Voice (Speech-to-Text)
  status: supported
  confidence: null
- id: outgoing-voice-text-to-speech
  text: Outgoing Voice (Text-to-Speech)
  status: supported
  confidence: null
- id: group-chat-usagegroup-chat-usageexample-group-trigg
  text: '[Group Chat Usage](#group-chat-usage)[](#example-group-trigger-configuration)[](#notes-on-mention_patterns)'
  status: supported
  confidence: null
- id: example-group-trigger-configuration
  text: Example group trigger configuration
  status: supported
  confidence: null
- id: notes-on-mention-patterns
  text: Notes on mention_patterns
  status: supported
  confidence: null
- id: private-chat-topics-bot-api-94private-chat-topics-bot
  text: '[Private Chat Topics (Bot API 9.4)](#private-chat-topics-bot-api-94)[](#use-case)[](#configuration-1)[](#how-it-works)[](#skill-binding)'
  status: supported
  confidence: null
- id: configuration
  text: Configuration
  status: supported
  confidence: null
- id: how-it-works
  text: How it works
  status: supported
  confidence: null
- id: skill-binding
  text: Skill binding
  status: supported
  confidence: null
- id: group-forum-topic-skill-bindinggroup-forum-topic-skill-b
  text: '[Group Forum Topic Skill Binding](#group-forum-topic-skill-binding)[](#use-case-1)[](#configuration-2)[](#how-it-works-1)[](#differences-from-dm-topics)'
  status: supported
  confidence: null
- id: configuration
  text: Configuration
  status: supported
  confidence: null
- id: how-it-works
  text: How it works
  status: supported
  confidence: null
- id: differences-from-dm-topics
  text: Differences from DM Topics
  status: supported
  confidence: null
- id: recent-bot-api-featuresrecent-bot-api-features
  text: '[Recent Bot API Features](#recent-bot-api-features)'
  status: supported
  confidence: null
- id: interactive-model-pickerinteractive-model-picker
  text: '[Interactive Model Picker](#interactive-model-picker)'
  status: supported
  confidence: null
- id: dns-over-https-fallback-ipsdns-over-https-fallback-ips
  text: '[DNS-over-HTTPS Fallback IPs](#dns-over-https-fallback-ips)[](#how-it-works-2)[](#configuration-3)'
  status: supported
  confidence: null
- id: how-it-works
  text: How it works
  status: supported
  confidence: null
- id: configuration
  text: Configuration
  status: supported
  confidence: null
- id: proxy-supportproxy-support-1supported-variables
  text: '[Proxy Support](#proxy-support-1)[](#supported-variables)[](#configuration-4)'
  status: supported
  confidence: null
- id: supported-variables
  text: Supported variables
  status: supported
  confidence: null
- id: configuration
  text: Configuration
  status: supported
  confidence: null
- id: message-reactionsmessage-reactions
  text: '[Message Reactions](#message-reactions)'
  status: supported
  confidence: null
- id: per-channel-promptsper-channel-prompts
  text: '[Per-Channel Prompts](#per-channel-prompts)'
  status: supported
  confidence: null
- id: troubleshootingtroubleshooting
  text: '[Troubleshooting](#troubleshooting)'
  status: supported
  confidence: null
- id: exec-approvalexec-approval
  text: '[Exec Approval](#exec-approval)'
  status: supported
  confidence: null
- id: securitysecurity
  text: '[[[entity.security|Security]]](#[[entity.security|Security]])'
  status: supported
  confidence: null
---

On this page

Hermes Agent integrates with Telegram as a full-featured conversational bot. Once connected, you can chat with your agent from any device, send voice memos that get auto-transcribed, receive scheduled task results, and use the agent in group chats. The integration is built on [python-telegram-bot](https://python-telegram-bot.org/) and supports text, voice, images, and file attachments.

## Step 1: Create a Bot via BotFather[​](#step-1-create-a-bot-via-botfather)

Every Telegram bot requires an API token issued by [@BotFather](https://t.me/BotFather), Telegram's official bot management tool.

****[](https://t.me/BotFather)************
1. Open Telegram and search for @BotFather, or visit t.me/BotFather

2. Send /newbot

3. Choose a display name (e.g., "Hermes Agent") — this can be anything

4. Choose a username — this must be unique and end in bot (e.g., my_hermes_bot)

5. BotFather replies with your API token. It looks like this:

```prism-code text codeBlock_bY9V thin-scrollbar
123456789:ABCdefGHIjklMNOpqrSTUvwxYZ

```

warning

Keep your bot token secret. Anyone with this token can control your bot. If it leaks, revoke it immediately via /revoke in BotFather.

## Step 2: Customize Your Bot (Optional)[​](#step-2-customize-your-bot-optional)

These BotFather commands improve the user experience. Message @BotFather and use:

tip

For /setcommands, a useful starting set:

```prism-code text codeBlock_bY9V thin-scrollbar
help - Show help information
new - Start a new conversation
sethome - Set this chat as the home channel

```

## Step 3: Privacy Mode (Critical for Groups)[​](#step-3-privacy-mode-critical-for-groups)

Telegram bots have a **privacy mode** that is **enabled by default**. This is the single most common source of confusion when using bots in groups.

**With privacy mode ON**, your bot can only see:

- Messages that start with a / command

- Replies directly to the bot's own messages

- Service messages (member joins/leaves, pinned messages, etc.)

- Messages in channels where the bot is an admin

**With privacy mode OFF**, the bot receives every message in the group.

### How to disable privacy mode[​](#how-to-disable-privacy-mode)

********
1. Message @BotFather

2. Send /mybots

3. Select your bot

4. Go to Bot Settings → Group Privacy → Turn off

warning

**You must remove and re-add the bot to any group** after changing the privacy setting. Telegram caches the privacy state when a bot joins a group, and it will not update until the bot is removed and re-added.

tip

An alternative to disabling privacy mode: promote the bot to **group admin**. Admin bots always receive all messages regardless of the privacy setting, and this avoids needing to toggle the global privacy mode.

## Step 4: Find Your User ID[​](#step-4-find-your-user-id)

Hermes Agent uses numeric Telegram user IDs to control access. Your user ID is **not** your username — it's a number like 123456789.

**Method 1 (recommended):** Message [@userinfobot](https://t.me/userinfobot) — it instantly replies with your user ID.

**Method 2:** Message [@get_id_bot](https://t.me/get_id_bot) — another reliable option.

Save this number; you'll need it for the next step.

## Step 5: Configure Hermes[​](#step-5-configure-hermes)

### Option A: Interactive Setup (Recommended)[​](#option-a-interactive-setup-recommended)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Telegram** when prompted. The wizard asks for your bot token and allowed user IDs, then writes the configuration for you.

### Option B: Manual Configuration[​](#option-b-manual-configuration)

Add the following to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
TELEGRAM_BOT_TOKEN=123456789:ABCdefGHIjklMNOpqrSTUvwxYZ
TELEGRAM_ALLOWED_USERS=123456789 # Comma-separated for multiple users

```

### Start the Gateway[​](#start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

The bot should come online within seconds. Send it a message on Telegram to verify.

## Sending Generated Files from Docker-backed Terminals[​](#sending-generated-files-from-docker-backed-terminals)

If your terminal backend is docker, keep in mind that Telegram attachments are
sent by the **gateway process**, not from inside the container. That means the
final MEDIA:/... path must be readable on the host where the gateway is
running.

Common pitfall:

- the agent writes a file inside Docker to /workspace/report.txt

- the model emits MEDIA:/workspace/report.txt

- Telegram delivery fails because /workspace/report.txt only exists inside the
container, not on the host

Recommended pattern:

```prism-code yaml codeBlock_bY9V thin-scrollbar
terminal:
 backend: docker
 docker_volumes:
 - "/home/user/.hermes/cache/documents:/output"

```

Then:

****
- write files inside Docker to /output/...

- emit the host-visible path in MEDIA:, for example:
MEDIA:/home/user/.hermes/cache/documents/report.txt

If you already have a docker_volumes: section, add the new mount to the same
list. YAML duplicate keys silently override earlier ones.

## Webhook Mode[​](#webhook-mode)

By default, Hermes connects to Telegram using **long polling** — the gateway makes outbound requests to Telegram's servers to fetch new updates. This works well for local and always-on deployments.

For **cloud deployments** (Fly.io, Railway, Render, etc.), **webhook mode** is more cost-effective. These platforms can auto-wake suspended machines on inbound HTTP traffic, but not on outbound connections. Since polling is outbound, a polling bot can never sleep. Webhook mode flips the direction — Telegram pushes updates to your bot's HTTPS URL, enabling sleep-when-idle deployments.

### Configuration[​](#configuration)

Add the following to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
TELEGRAM_WEBHOOK_URL=https://my-app.fly.dev/telegram
# TELEGRAM_WEBHOOK_PORT=8443 # optional, default 8443
# TELEGRAM_WEBHOOK_SECRET=mysecret # optional, recommended

```

****

When TELEGRAM_WEBHOOK_URL is set, the gateway starts an HTTP webhook server instead of polling. When unset, polling mode is used — no behavior change from previous versions.

### Cloud deployment example (Fly.io)[​](#cloud-deployment-example-flyio)

1. Add the env vars to your Fly.io app secrets:

```prism-code bash codeBlock_bY9V thin-scrollbar
fly secrets set TELEGRAM_WEBHOOK_URL=https://my-app.fly.dev/telegram
fly secrets set TELEGRAM_WEBHOOK_SECRET=$(openssl rand -hex 32)

```

1. Expose the webhook port in your fly.toml:

```prism-code toml codeBlock_bY9V thin-scrollbar
[[services]]
 internal_port = 8443
 protocol = "tcp"

 [[services.ports]]
 handlers = ["tls", "http"]
 port = 443

```

1. Deploy:

```prism-code bash codeBlock_bY9V thin-scrollbar
fly deploy

```

The gateway log should show: [telegram] Connected to Telegram (webhook mode).

## Proxy Support[​](#proxy-support)

If Telegram's API is blocked or you need to route traffic through a proxy, set a Telegram-specific proxy URL. This takes priority over the generic HTTPS_PROXY / HTTP_PROXY env vars.

**Option 1: config.yaml (recommended)**

```prism-code yaml codeBlock_bY9V thin-scrollbar
telegram:
 proxy_url: "socks5://127.0.0.1:1080"

```

**Option 2: environment variable**

```prism-code bash codeBlock_bY9V thin-scrollbar
TELEGRAM_PROXY=socks5://127.0.0.1:1080

```

Supported schemes: http://, https://, socks5://.

The proxy applies to both the main Telegram connection and the fallback IP transport. If no Telegram-specific proxy is set, the gateway falls back to HTTPS_PROXY / HTTP_PROXY / ALL_PROXY (or macOS system proxy auto-detection).

## Home Channel[​](#home-channel)

Use the /sethome command in any Telegram chat (DM or group) to designate it as the **home channel**. Scheduled tasks (cron jobs) deliver their results to this channel.

You can also set it manually in ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
TELEGRAM_HOME_CHANNEL=-1001234567890
TELEGRAM_HOME_CHANNEL_NAME="My Notes"

```

tip

Group chat IDs are negative numbers (e.g., -1001234567890). Your personal DM chat ID is the same as your user ID.

## Voice Messages[​](#voice-messages)

### Incoming Voice (Speech-to-Text)[​](#incoming-voice-speech-to-text)

Voice messages you send on Telegram are automatically transcribed by Hermes's configured STT provider and injected as text into the conversation.

- local uses faster-whisper on the machine running Hermes — no API key required

- groq uses Groq Whisper and requires GROQ_API_KEY

- openai uses OpenAI Whisper and requires VOICE_TOOLS_OPENAI_KEY

### Outgoing Voice (Text-to-Speech)[​](#outgoing-voice-text-to-speech)

When the agent generates audio via TTS, it's delivered as native Telegram **voice bubbles** — the round, inline-playable kind.

************
- OpenAI and ElevenLabs produce Opus natively — no extra setup needed

- Edge TTS (the default free provider) outputs MP3 and requires ffmpeg to convert to Opus:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Ubuntu/Debian
sudo apt install ffmpeg

# macOS
brew install ffmpeg

```

Without ffmpeg, Edge TTS audio is sent as a regular audio file (still playable, but uses the rectangular player instead of a voice bubble).

Configure the TTS provider in your config.yaml under the tts.provider key.

## Group Chat Usage[​](#group-chat-usage)

Hermes Agent works in Telegram group chats with a few considerations:

****[](#step-3-privacy-mode-critical-for-groups)
- slash commands

- replies to one of the bot's messages

- @botusername mentions

- matches for one of your configured regex wake words in telegram.mention_patterns

- Use telegram.ignored_threads to keep Hermes silent in specific Telegram forum topics, even when the group would otherwise allow free responses or mention-triggered replies

- If telegram.require_mention is left unset or false, Hermes keeps the previous open-group behavior and responds to normal group messages it can see

### Example group trigger configuration[​](#example-group-trigger-configuration)

Add this to ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
telegram:
 require_mention: true
 mention_patterns:
 - "^\\s*chompy\\b"
 ignored_threads:
 - 31
 - "42"

```

This example allows all the usual direct triggers plus messages that begin with chompy, even if they do not use an @mention.
Messages in Telegram topics 31 and 42 are always ignored before the mention and free-response checks run.

### Notes on mention_patterns[​](#notes-on-mention_patterns)

- Patterns use Python regular expressions

- Matching is case-insensitive

- Patterns are checked against both text messages and media captions

- Invalid regex patterns are ignored with a warning in the gateway logs rather than crashing the bot

- If you want a pattern to match only at the start of a message, anchor it with ^

## Private Chat Topics (Bot API 9.4)[​](#private-chat-topics-bot-api-94)

Telegram Bot API 9.4 (February 2026) introduced **Private Chat Topics** — bots can create forum-style topic threads directly in 1-on-1 DM chats, no supergroup needed. This lets you run multiple isolated workspaces within your existing DM with Hermes.

### Use case[​](#use-case)

If you work on several long-running projects, topics keep their context separate:

************
- Topic "Website" — work on your production web service

- Topic "Research" — literature review and paper exploration

- Topic "General" — miscellaneous tasks and quick questions

Each topic gets its own conversation session, history, and context — completely isolated from the others.

### Configuration[​](#configuration-1)

Prerequisites

Before adding topics to your config, the user must **enable Topics mode** in the DM chat with the bot:

****
1. Open your private chat with the Hermes bot in Telegram

2. Tap the bot's name at the top to open chat info

3. Enable Topics (the toggle to turn the chat into a forum)

Without this, Hermes will log The chat is not a forum on startup and skip topic creation. This is a Telegram client-side setting — the bot cannot enable it programmatically.

Add topics under platforms.telegram.extra.dm_topics in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 telegram:
 extra:
 dm_topics:
 - chat_id: 123456789 # Your Telegram user ID
 topics:
 - name: General
 icon_color: 7322096
 - name: Website
 icon_color: 9367192
 - name: Research
 icon_color: 16766590
 skill: arxiv # Auto-load a skill in this topic

```

**Fields:**

### How it works[​](#how-it-works)

1. On gateway startup, Hermes calls createForumTopic for each topic that doesn't have a thread_id yet

2. The thread_id is saved back to config.yaml automatically — subsequent restarts skip the API call

3. Each topic maps to an isolated session key: agent:main:telegram:dm:{chat_id}:{thread_id}

4. Messages in each topic have their own conversation history, memory flush, and context window

### Skill binding[​](#skill-binding)

Topics with a skill field automatically load that skill when a new session starts in the topic. This works exactly like typing /skill-name at the start of a conversation — the skill content is injected into the first message, and subsequent messages see it in the conversation history.

For example, a topic with skill: arxiv will have the arxiv skill pre-loaded whenever its session resets (due to idle timeout, daily reset, or manual /reset).

tip

Topics created outside of the config (e.g., by manually calling the Telegram API) are discovered automatically when a forum_topic_created service message arrives. You can also add topics to the config while the gateway is running — they'll be picked up on the next cache miss.

## Group Forum Topic Skill Binding[​](#group-forum-topic-skill-binding)

Supergroups with **Topics mode** enabled (also called "forum topics") already get session isolation per topic — each thread_id maps to its own conversation. But you may want to **auto-load a skill** when messages arrive in a specific group topic, just like DM topic skill binding works.

### Use case[​](#use-case-1)

A team supergroup with forum topics for different workstreams:

************
- Engineering topic → auto-loads the software-development skill

- Research topic → auto-loads the arxiv skill

- General topic → no skill, general-purpose assistant

### Configuration[​](#configuration-2)

Add topic bindings under platforms.telegram.extra.group_topics in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 telegram:
 extra:
 group_topics:
 - chat_id: -1001234567890 # Supergroup ID
 topics:
 - name: Engineering
 thread_id: 5
 skill: software-development
 - name: Research
 thread_id: 12
 skill: arxiv
 - name: General
 thread_id: 1
 # No skill — general purpose

```

**Fields:**

### How it works[​](#how-it-works-1)

1. When a message arrives in a mapped group topic, Hermes looks up the chat_id and thread_id in group_topics config

2. If a matching entry has a skill field, that skill is auto-loaded for the session — identical to DM topic skill binding

3. Topics without a skill key get session isolation only (existing behavior, unchanged)

4. Unmapped thread_id values or chat_id values fall through silently — no error, no skill

### Differences from DM Topics[​](#differences-from-dm-topics)

tip

To find a topic's thread_id, open the topic in Telegram Web or Desktop and look at the URL: https://t.me/c/1234567890/5 — the last number (5) is the thread_id. The chat_id for supergroups is the group ID prefixed with -100 (e.g., group 1234567890 becomes -1001234567890).

## Recent Bot API Features[​](#recent-bot-api-features)

****[](#private-chat-topics-bot-api-94)********
- Bot API 9.4 (Feb 2026): Private Chat Topics — bots can create forum topics in 1-on-1 DM chats via createForumTopic. See Private Chat Topics above.

- Privacy policy: Telegram now requires bots to have a privacy policy. Set one via BotFather with /setprivacy_policy, or Telegram may auto-generate a placeholder. This is particularly important if your bot is public-facing.

- Message streaming: Bot API 9.x added support for streaming long responses, which can improve perceived latency for lengthy agent replies.

## Interactive Model Picker[​](#interactive-model-picker)

When you send /model with no arguments in a Telegram chat, Hermes shows an interactive inline keyboard for switching models:

************************
1. Provider selection — buttons showing each available provider with model counts (e.g., "OpenAI (15)", "✓ Anthropic (12)" for the current provider).

2. Model selection — paginated model list with Prev/Next navigation, a Back button to return to providers, and Cancel.

The current model and provider are displayed at the top. All navigation happens by editing the same message in-place (no chat clutter).

tip

If you know the exact model name, type /model <name> directly to skip the picker. You can also type /model <name> --global to persist the change across sessions.

## DNS-over-HTTPS Fallback IPs[​](#dns-over-https-fallback-ips)

In some restricted networks, api.telegram.org may resolve to an IP that is unreachable. The Telegram adapter includes a **fallback IP** mechanism that transparently retries connections against alternative IPs while preserving the correct TLS hostname and SNI.

### How it works[​](#how-it-works-2)

********
1. If TELEGRAM_FALLBACK_IPS is set, those IPs are used directly.

2. Otherwise, the adapter automatically queries Google DNS and Cloudflare DNS via DNS-over-HTTPS (DoH) to discover alternative IPs for api.telegram.org.

3. IPs returned by DoH that differ from the system DNS result are used as fallbacks.

4. If DoH is also blocked, a hardcoded seed IP (149.154.167.220) is used as a last resort.

5. Once a fallback IP succeeds, it becomes "sticky" — subsequent requests use it directly without retrying the primary path first.

### Configuration[​](#configuration-3)

```prism-code bash codeBlock_bY9V thin-scrollbar
# Explicit fallback IPs (comma-separated)
TELEGRAM_FALLBACK_IPS=149.154.167.220,149.154.167.221

```

Or in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 telegram:
 extra:
 fallback_ips:
 - "149.154.167.220"

```

tip

You usually don't need to configure this manually. The auto-discovery via DoH handles most restricted-network scenarios. The TELEGRAM_FALLBACK_IPS env var is only needed if DoH is also blocked on your network.

## Proxy Support[​](#proxy-support-1)

If your network requires an HTTP proxy to reach the internet (common in corporate environments), the Telegram adapter automatically reads standard proxy environment variables and routes all connections through the proxy.

### Supported variables[​](#supported-variables)

The adapter checks these environment variables in order, using the first one that is set:

1. HTTPS_PROXY

2. HTTP_PROXY

3. ALL_PROXY

4. https_proxy / http_proxy / all_proxy (lowercase variants)

### Configuration[​](#configuration-4)

Set the proxy in your environment before starting the gateway:

```prism-code bash codeBlock_bY9V thin-scrollbar
export HTTPS_PROXY=http://proxy.example.com:8080
hermes gateway

```

Or add it to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
HTTPS_PROXY=http://proxy.example.com:8080

```

The proxy applies to both the primary transport and all fallback IP transports. No additional Hermes configuration is needed — if the environment variable is set, it's used automatically.

note

This covers the custom fallback transport layer that Hermes uses for Telegram connections. The standard httpx client used elsewhere already respects proxy env vars natively.

## Message Reactions[​](#message-reactions)

The bot can add emoji reactions to messages as visual processing feedback:

- 👀 when the bot starts processing your message

- ✅ when the response is delivered successfully

- ❌ if an error occurs during processing

Reactions are **disabled by default**. Enable them in config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
telegram:
 reactions: true

```

Or via environment variable:

```prism-code bash codeBlock_bY9V thin-scrollbar
TELEGRAM_REACTIONS=true

```

note

Unlike Discord (where reactions are additive), Telegram's Bot API replaces all bot reactions in a single call. The transition from 👀 to ✅/❌ happens atomically — you won't see both at once.

tip

If the bot doesn't have permission to add reactions in a group, the reaction calls fail silently and message processing continues normally.

## Per-Channel Prompts[​](#per-channel-prompts)

Assign ephemeral system prompts to specific Telegram groups or forum topics. The prompt is injected at runtime on every turn — never persisted to transcript history — so changes take effect immediately.

```prism-code yaml codeBlock_bY9V thin-scrollbar
telegram:
 channel_prompts:
 "-1001234567890": |
 You are a research assistant. Focus on academic sources,
 citations, and concise synthesis.
 "42": |
 This topic is for creative writing feedback. Be warm and
 constructive.

```

Keys are chat IDs (groups/supergroups) or forum topic IDs. For forum groups, topic-level prompts override the group-level prompt:

- Message in topic 42 inside group -1001234567890 → uses topic 42's prompt

- Message in topic 99 (no explicit entry) → falls back to group -1001234567890's prompt

- Message in a group with no entry → no channel prompt applied

Numeric YAML keys are automatically normalized to strings.

## Troubleshooting[​](#troubleshooting)

****

## Exec Approval[​](#exec-approval)

When the agent tries to run a potentially dangerous command, it asks you for approval in the chat:

>

⚠️ This command is potentially dangerous (recursive delete). Reply "yes" to approve.

Reply "yes"/"y" to approve or "no"/"n" to deny.

## [[entity.security|Security]][​](#[[entity.security|Security]])

warning

Always set TELEGRAM_ALLOWED_USERS to restrict who can interact with your bot. Without it, the gateway denies all users by default as a safety measure.

Never share your bot token publicly. If compromised, revoke it immediately via BotFather's /revoke command.

For more details, see the [[[entity.security|Security]] documentation](/docs/user-guide/[[entity.security|Security]]). You can also use [DM pairing](/docs/user-guide/messaging#dm-pairing-alternative-to-allowlists) for a more dynamic approach to user authorization.
[](#step-1-create-a-bot-via-botfather)[](#step-2-customize-your-bot-optional)[](#step-3-privacy-mode-critical-for-groups)[](#how-to-disable-privacy-mode)
- How to disable privacy mode
- [Step 4: Find Your User ID](#step-4-find-your-user-id)
- [Step 5: Configure Hermes](#step-5-configure-hermes)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)
- Option A: Interactive Setup (Recommended)
- Option B: Manual Configuration
- Start the Gateway
- [Sending Generated Files from Docker-backed Terminals](#sending-generated-files-from-docker-backed-terminals)
- [Webhook Mode](#webhook-mode)[](#configuration)[](#cloud-deployment-example-flyio)
- Configuration
- Cloud deployment example (Fly.io)
- [Proxy Support](#proxy-support)
- [Home Channel](#home-channel)
- [Voice Messages](#voice-messages)[](#incoming-voice-speech-to-text)[](#outgoing-voice-text-to-speech)
- Incoming Voice (Speech-to-Text)
- Outgoing Voice (Text-to-Speech)
- [Group Chat Usage](#group-chat-usage)[](#example-group-trigger-configuration)[](#notes-on-mention_patterns)
- Example group trigger configuration
- Notes on mention_patterns
- [Private Chat Topics (Bot API 9.4)](#private-chat-topics-bot-api-94)[](#use-case)[](#configuration-1)[](#how-it-works)[](#skill-binding)
- Use case
- Configuration
- How it works
- Skill binding
- [Group Forum Topic Skill Binding](#group-forum-topic-skill-binding)[](#use-case-1)[](#configuration-2)[](#how-it-works-1)[](#differences-from-dm-topics)
- Use case
- Configuration
- How it works
- Differences from DM Topics
- [Recent Bot API Features](#recent-bot-api-features)
- [Interactive Model Picker](#interactive-model-picker)
- [DNS-over-HTTPS Fallback IPs](#dns-over-https-fallback-ips)[](#how-it-works-2)[](#configuration-3)
- How it works
- Configuration
- [Proxy Support](#proxy-support-1)[](#supported-variables)[](#configuration-4)
- Supported variables
- Configuration
- [Message Reactions](#message-reactions)
- [Per-Channel Prompts](#per-channel-prompts)
- [Troubleshooting](#troubleshooting)
- [Exec Approval](#exec-approval)
- [[[entity.security|Security]]](#[[entity.security|Security]])