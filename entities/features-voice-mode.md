---
pageType: entity
id: entity.features-voice-mode
title: 'Features: Voice Mode'
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-features-voice-mode.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-features-voice-mode.md
updatedAt: '2026-04-24T15:05:25.594329+00:00'
sourceIds:
- discordcom
- discordcom
- discordcom
- apiopenaicom
- apigroqcom
sources:
- sourceId: discordcom
  sourceType: web
  sourcePath: https://discord.com/developers/applications
  title: '[Discord Developer Portal](https://discord.com/developers/applications)'
- sourceId: discordcom
  sourceType: web
  sourcePath: https://discord.com/developers/applications
  title: '[Developer Portal](https://discord.com/developers/applications)'
- sourceId: discordcom
  sourceType: web
  sourcePath: https://discord.com/oauth2/authorize?client_id=YOUR_APP_ID&scope=bot+applications.commands&permissions=274881432640
  title: discord.com
- sourceId: apiopenaicom
  sourceType: web
  sourcePath: https://api.openai.com/v1
  title: api.openai.com
- sourceId: apigroqcom
  sourceType: web
  sourcePath: https://api.groq.com/openai/v1
  title: api.groq.com
claims:
- id: feature-platform-description
  text: Feature**, **Platform**, **Description**
  status: supported
  confidence: null
- id: feature-interactive-voice-platform-cli-descr
  text: 'Feature**: **Interactive Voice**, **Platform**: CLI, **Description**: Press
    Ctrl+B to record, agent auto-detects silence and responds'
  status: supported
  confidence: null
- id: feature-auto-voice-reply-platform-telegram-dis
  text: 'Feature**: **Auto Voice Reply**, **Platform**: Telegram, Discord, **Description**:
    Agent sends spoken audio alongside text responses'
  status: supported
  confidence: null
- id: feature-voice-channel-platform-discord-descr
  text: 'Feature**: **Voice Channel**, **Platform**: Discord, **Description**: Bot
    joins VC, listens to users speaking, speaks replies back'
  status: supported
  confidence: null
- id: extra-packages-required-for
  text: Extra**, **Packages**, **Required For**
  status: supported
  confidence: null
- id: extra-voice-packages-sounddevice-numpy-re
  text: 'Extra**: `voice`, **Packages**: `sounddevice`, `numpy`, **Required For**:
    CLI voice mode'
  status: supported
  confidence: null
- id: extra-messaging-packages-discordpyvoice-py
  text: 'Extra**: `messaging`, **Packages**: `discord.py[voice]`, `python-telegram-bot`,
    `aiohttp`, **Required For**: Discord & Telegram bots'
  status: supported
  confidence: null
- id: extra-tts-premium-packages-elevenlabs-requir
  text: 'Extra**: `tts-premium`, **Packages**: `elevenlabs`, **Required For**: ElevenLabs
    TTS provider'
  status: supported
  confidence: null
- id: dependency-purpose-required-for
  text: Dependency**, **Purpose**, **Required For**
  status: supported
  confidence: null
- id: dependency-portaudio-purpose-microphone-input-a
  text: 'Dependency**: **PortAudio**, **Purpose**: Microphone input and audio playback,
    **Required For**: CLI voice mode'
  status: supported
  confidence: null
- id: dependency-ffmpeg-purpose-audio-format-conversi
  text: "Dependency**: **ffmpeg**, **Purpose**: Audio format conversion (MP3 \u2192\
    \ Opus, PCM \u2192 WAV), **Required For**: All platforms"
  status: supported
  confidence: null
- id: dependency-opus-purpose-discord-voice-codec
  text: 'Dependency**: **Opus**, **Purpose**: Discord voice codec, **Required For**:
    Discord voice channels'
  status: supported
  confidence: null
- id: dependency-espeak-ng-purpose-phonemizer-backend
  text: 'Dependency**: **espeak-ng**, **Purpose**: Phonemizer backend, **Required
    For**: Local NeuTTS provider'
  status: supported
  confidence: null
- id: telegram-setup-guidedocsuser-guidemessagingtelegram
  text: '[Telegram Setup Guide](/docs/user-guide/messaging/telegram)'
  status: supported
  confidence: null
- id: discord-setup-guidedocsuser-guidemessagingdiscord
  text: '[Discord Setup Guide](/docs/user-guide/messaging/discord)'
  status: supported
  confidence: null
- id: mode-how-to-talk-mention-required-setup
  text: Mode**, **How to Talk**, **Mention Required**, **Setup**
  status: supported
  confidence: null
- id: mode-direct-message-dm-how-to-talk-open-the-b
  text: "Mode**: **Direct Message (DM)**, **How to Talk**: Open the bot's profile\
    \ \u2192 \"Message\", **Mention Required**: No, **Setup**: Works immediately"
  status: supported
  confidence: null
- id: mode-server-channel-how-to-talk-type-in-a-text
  text: 'Mode**: **Server Channel**, **How to Talk**: Type in a text channel where
    the bot is present, **Mention Required**: Yes (`@botname`), **Setup**: Bot must
    be invited to the server'
  status: supported
  confidence: null
- id: mode-command-behavior
  text: Mode**, **Command**, **Behavior**
  status: supported
  confidence: null
- id: mode-off-command-voice-off-behavior-text
  text: 'Mode**: `off`, **Command**: `/voice off`, **Behavior**: Text only (default)'
  status: supported
  confidence: null
- id: mode-voice-only-command-voice-on-behavior
  text: 'Mode**: `voice_only`, **Command**: `/voice on`, **Behavior**: Speaks reply
    only when you send a voice message'
  status: supported
  confidence: null
- id: mode-all-command-voice-tts-behavior-spea
  text: 'Mode**: `all`, **Command**: `/voice tts`, **Behavior**: Speaks reply to every
    message'
  status: supported
  confidence: null
- id: platform-format-notes
  text: Platform**, **Format**, **Notes**
  status: supported
  confidence: null
- id: platform-telegram-format-voice-bubble-opusogg
  text: "Platform**: **Telegram**, **Format**: Voice bubble (Opus/OGG), **Notes**:\
    \ Plays inline in chat. ffmpeg converts MP3 \u2192 Opus if needed"
  status: supported
  confidence: null
- id: platform-discord-format-native-voice-bubble-op
  text: 'Platform**: **Discord**, **Format**: Native voice bubble (Opus/OGG), **Notes**:
    Plays inline like a user voice message. Falls back to file attachment if voice
    bubble API fails'
  status: supported
  confidence: null
- id: permission-purpose-required
  text: Permission**, **Purpose**, **Required**
  status: supported
  confidence: null
- id: permission-connect-purpose-join-voice-channels
  text: 'Permission**: **Connect**, **Purpose**: Join voice channels, **Required**:
    Yes'
  status: supported
  confidence: null
- id: permission-speak-purpose-play-tts-audio-in-voic
  text: 'Permission**: **Speak**, **Purpose**: Play TTS audio in voice channels, **Required**:
    Yes'
  status: supported
  confidence: null
- id: permission-use-voice-activity-purpose-detect-wh
  text: 'Permission**: **Use Voice Activity**, **Purpose**: Detect when users are
    speaking, **Required**: Recommended'
  status: supported
  confidence: null
- id: level-integer-whats-included
  text: Level**, **Integer**, **What's Included**
  status: supported
  confidence: null
- id: level-text-only-integer-274878286912-whats-in
  text: 'Level**: Text only, **Integer**: `274878286912`, **What''s Included**: View
    Channels, Send Messages, Read History, Embeds, Attachments, Threads, Reactions'
  status: supported
  confidence: null
- id: level-text-voice-integer-274881432640-whats
  text: 'Level**: Text + Voice, **Integer**: `274881432640`, **What''s Included**:
    All above + Connect, Speak'
  status: supported
  confidence: null
- id: intent-purpose
  text: 'Intent**: Purpose'
  status: supported
  confidence: null
- id: presence-intent-detect-user-onlineoffline-status
  text: 'Presence Intent****: Detect user online/offline status'
  status: supported
  confidence: null
- id: server-members-intent-map-voice-ssrc-identifiers-to-dis
  text: 'Server Members Intent****: Map voice SSRC identifiers to Discord user IDs'
  status: supported
  confidence: null
- id: message-content-intent-read-text-message-content-in-cha
  text: 'Message Content Intent****: Read text message content in channels'
  status: supported
  confidence: null
- id: macos-opthomebrewliblibopusdylib
  text: macOS:** `/opt/homebrew/lib/libopus.dylib`
  status: supported
  confidence: null
- id: linux-libopusso0
  text: Linux:** `libopus.so.0`
  status: supported
  confidence: null
- id: transcripts-appear-in-the-text-channel-voice-user-what
  text: 'Transcripts appear in the text channel: `[Voice] @user: what you said`'
  status: supported
  confidence: null
- id: agent-responses-are-sent-as-text-in-the-channel-and-spoken-i
  text: Agent responses are sent as text in the channel AND spoken in the VC
  status: supported
  confidence: null
- id: the-text-channel-is-the-one-where-voice-join-was-issued
  text: The text channel is the one where `/voice join` was issued
  status: supported
  confidence: null
- id: provider-model-speed-quality-cost-a
  text: Provider**, **Model**, **Speed**, **Quality**, **Cost**, **API Key**
  status: supported
  confidence: null
- id: provider-local-model-base-speed-fast-d
  text: 'Provider**: **Local**, **Model**: `base`, **Speed**: Fast (depends on CPU/GPU),
    **Quality**: Good, **Cost**: Free, **API Key**: No'
  status: supported
  confidence: null
- id: provider-local-model-small-speed-medium
  text: 'Provider**: **Local**, **Model**: `small`, **Speed**: Medium, **Quality**:
    Better, **Cost**: Free, **API Key**: No'
  status: supported
  confidence: null
- id: provider-local-model-large-v3-speed-slo
  text: 'Provider**: **Local**, **Model**: `large-v3`, **Speed**: Slow, **Quality**:
    Best, **Cost**: Free, **API Key**: No'
  status: supported
  confidence: null
- id: provider-groq-model-whisper-large-v3-turbo
  text: 'Provider**: **Groq**, **Model**: `whisper-large-v3-turbo`, **Speed**: Very
    fast (~0.5s), **Quality**: Good, **Cost**: Free tier, **API Key**: Yes'
  status: supported
  confidence: null
- id: provider-groq-model-whisper-large-v3-speed
  text: 'Provider**: **Groq**, **Model**: `whisper-large-v3`, **Speed**: Fast (~1s),
    **Quality**: Better, **Cost**: Free tier, **API Key**: Yes'
  status: supported
  confidence: null
- id: provider-openai-model-whisper-1-speed-f
  text: 'Provider**: **OpenAI**, **Model**: `whisper-1`, **Speed**: Fast (~1s), **Quality**:
    Good, **Cost**: Paid, **API Key**: Yes'
  status: supported
  confidence: null
- id: provider-openai-model-gpt-4o-transcribe-sp
  text: 'Provider**: **OpenAI**, **Model**: `gpt-4o-transcribe`, **Speed**: Medium
    (~2s), **Quality**: Best, **Cost**: Paid, **API Key**: Yes'
  status: supported
  confidence: null
- id: provider-quality-cost-latency-key-requir
  text: Provider**, **Quality**, **Cost**, **Latency**, **Key Required**
  status: supported
  confidence: null
- id: provider-edge-tts-quality-good-cost-free
  text: 'Provider**: **Edge TTS**, **Quality**: Good, **Cost**: Free, **Latency**:
    ~1s, **Key Required**: No'
  status: supported
  confidence: null
- id: provider-elevenlabs-quality-excellent-cost
  text: 'Provider**: **ElevenLabs**, **Quality**: Excellent, **Cost**: Paid, **Latency**:
    ~2s, **Key Required**: Yes'
  status: supported
  confidence: null
- id: provider-openai-tts-quality-good-cost-pai
  text: 'Provider**: **OpenAI TTS**, **Quality**: Good, **Cost**: Paid, **Latency**:
    ~1.5s, **Key Required**: Yes'
  status: supported
  confidence: null
- id: provider-neutts-quality-good-cost-free
  text: 'Provider**: **NeuTTS**, **Quality**: Good, **Cost**: Free, **Latency**: Depends
    on CPU/GPU, **Key Required**: No'
  status: supported
  confidence: null
- id: check-your-discord-user-id-is-in-discord-allowed-users
  text: Check your Discord user ID is in `DISCORD_ALLOWED_USERS`
  status: supported
  confidence: null
- id: make-sure-youre-not-muted-in-discord
  text: Make sure you're not muted in Discord
  status: supported
  confidence: null
- id: the-bot-needs-a-speaking-event-from-discord-before-it-can-ma
  text: "The bot needs a SPEAKING event from Discord before it can map your audio\
    \ \u2014 start speaking within a few seconds of joining"
  status: supported
  confidence: null
- id: verify-stt-is-available-install-faster-whisper-no-key-ne
  text: 'Verify STT is available: install `faster-whisper` (no key needed) or set
    `GROQ_API_KEY` / `VOICE_TOOLS_OPENAI_KEY`'
  status: supported
  confidence: null
- id: check-the-llm-model-is-configured-and-accessible
  text: Check the LLM model is configured and accessible
  status: supported
  confidence: null
- id: review-gateway-logs-tail--f-hermeslogsgatewaylog
  text: 'Review gateway logs: `tail -f ~/.hermes/logs/gateway.log`'
  status: supported
  confidence: null
- id: tts-provider-may-be-failing-check-api-key-and-quota
  text: "TTS provider may be failing \u2014 check API key and quota"
  status: supported
  confidence: null
- id: edge-tts-free-no-key-is-the-default-fallback
  text: Edge TTS (free, no key) is the default fallback
  status: supported
  confidence: null
- id: check-logs-for-tts-errors
  text: Check logs for TTS errors
  status: supported
  confidence: null
- id: use-a-quieter-environment
  text: Use a quieter environment
  status: supported
  confidence: null
- id: adjust-silence-threshold-in-config-higher-less-sensitiv
  text: Adjust `silence_threshold` in config (higher = less sensitive)
  status: supported
  confidence: null
- id: try-a-different-stt-model
  text: Try a different STT model
  status: supported
  confidence: null
---

Hermes Agent supports full voice interaction across CLI and messaging platforms. Talk to the agent using your microphone, hear spoken replies, and have live voice conversations in Discord voice channels.

If you want a practical setup walkthrough with recommended configurations and real usage patterns, see [Use Voice Mode with Hermes](/docs/guides/use-voice-mode-with-hermes).

## Prerequisites[​](#prerequisites "Direct link to Prerequisites")

Before using voice features, make sure you have:

1. **Hermes Agent installed** — `pip install hermes-agent` (see [Installation](/docs/getting-started/installation))
2. **An LLM provider configured** — run `hermes model` or set your preferred provider credentials in `~/.hermes/.env`
3. **A working base setup** — run `hermes` to verify the agent responds to text before enabling voice

tip

The `~/.hermes/` directory and default `config.yaml` are created automatically the first time you run `hermes`. You only need to create `~/.hermes/.env` manually for API keys.

## Overview[​](#overview "Direct link to Overview")

- **Feature**, **Platform**, **Description**
- **Feature**: **Interactive Voice**, **Platform**: CLI, **Description**: Press Ctrl+B to record, agent auto-detects silence and responds
- **Feature**: **Auto Voice Reply**, **Platform**: Telegram, Discord, **Description**: Agent sends spoken audio alongside text responses
- **Feature**: **Voice Channel**, **Platform**: Discord, **Description**: Bot joins VC, listens to users speaking, speaks replies back

## Requirements[​](#requirements "Direct link to Requirements")

### Python Packages[​](#python-packages "Direct link to Python Packages")

```
# CLI voice mode (microphone + audio playback)
pip install "hermes-agent[voice]"

# Discord + Telegram messaging (includes discord.py[voice] for VC support)
pip install "hermes-agent[messaging]"

# Premium TTS (ElevenLabs)
pip install "hermes-agent[tts-premium]"

# Local TTS (NeuTTS, optional)
python -m pip install -U neutts[all]

# Everything at once
pip install "hermes-agent[all]"
```

- **Extra**, **Packages**, **Required For**
- **Extra**: `voice`, **Packages**: `sounddevice`, `numpy`, **Required For**: CLI voice mode
- **Extra**: `messaging`, **Packages**: `discord.py[voice]`, `python-telegram-bot`, `aiohttp`, **Required For**: Discord & Telegram bots
- **Extra**: `tts-premium`, **Packages**: `elevenlabs`, **Required For**: ElevenLabs TTS provider

Optional local TTS provider: install `neutts` separately with `python -m pip install -U neutts[all]`. On first use it downloads the model automatically.

info

`discord.py[voice]` installs **PyNaCl** (for voice encryption) and **opus bindings** automatically. This is required for Discord voice channel support.

### System Dependencies[​](#system-dependencies "Direct link to System Dependencies")

```
# macOS
brew install portaudio ffmpeg opus
brew install espeak-ng   # for NeuTTS

# Ubuntu/Debian
sudo apt install portaudio19-dev ffmpeg libopus0
sudo apt install espeak-ng   # for NeuTTS
```

- **Dependency**, **Purpose**, **Required For**
- **Dependency**: **PortAudio**, **Purpose**: Microphone input and audio playback, **Required For**: CLI voice mode
- **Dependency**: **ffmpeg**, **Purpose**: Audio format conversion (MP3 → Opus, PCM → WAV), **Required For**: All platforms
- **Dependency**: **Opus**, **Purpose**: Discord voice codec, **Required For**: Discord voice channels
- **Dependency**: **espeak-ng**, **Purpose**: Phonemizer backend, **Required For**: Local NeuTTS provider

### API Keys[​](#api-keys "Direct link to API Keys")

Add to `~/.hermes/.env`:

```
# Speech-to-Text — local provider needs NO key at all
# pip install faster-whisper          # Free, runs locally, recommended
GROQ_API_KEY=your-key                 # Groq Whisper — fast, free tier (cloud)
VOICE_TOOLS_OPENAI_KEY=your-key       # OpenAI Whisper — paid (cloud)

# Text-to-Speech (optional — Edge TTS and NeuTTS work without any key)
ELEVENLABS_API_KEY=***           # ElevenLabs — premium quality
# VOICE_TOOLS_OPENAI_KEY above also enables OpenAI TTS
```

tip

If `faster-whisper` is installed, voice mode works with **zero API keys** for STT. The model (~150 MB for `base`) downloads automatically on first use.

---

## CLI Voice Mode[​](#cli-voice-mode "Direct link to CLI Voice Mode")

### Quick Start[​](#quick-start "Direct link to Quick Start")

Start the CLI and enable voice mode:

```
hermes                # Start the interactive CLI
```

Then use these commands inside the CLI:

```
/voice          Toggle voice mode on/off
/voice on       Enable voice mode
/voice off      Disable voice mode
/voice tts      Toggle TTS output
/voice status   Show current state
```

### How It Works[​](#how-it-works "Direct link to How It Works")

1. Start the CLI with `hermes` and enable voice mode with `/voice on`
2. **Press Ctrl+B** — a beep plays (880Hz), recording starts
3. **Speak** — a live audio level bar shows your input: `● [▁▂▃▅▇▇▅▂] ❯`
4. **Stop speaking** — after 3 seconds of silence, recording auto-stops
5. **Two beeps** play (660Hz) confirming the recording ended
6. Audio is transcribed via Whisper and sent to the agent
7. If TTS is enabled, the agent's reply is spoken aloud
8. Recording **automatically restarts** — speak again without pressing any key

This loop continues until you press **Ctrl+B** during recording (exits continuous mode) or 3 consecutive recordings detect no speech.

tip

The record key is configurable via `voice.record_key` in `~/.hermes/config.yaml` (default: `ctrl+b`).

### Silence Detection[​](#silence-detection "Direct link to Silence Detection")

Two-stage algorithm detects when you've finished speaking:

1. **Speech confirmation** — waits for audio above the RMS threshold (200) for at least 0.3s, tolerating brief dips between syllables
2. **End detection** — once speech is confirmed, triggers after 3.0 seconds of continuous silence

If no speech is detected at all for 15 seconds, recording stops automatically.

Both `silence_threshold` and `silence_duration` are configurable in `config.yaml`. You can also disable the record start/stop beeps with `voice.beep_enabled: false`.

### Streaming TTS[​](#streaming-tts "Direct link to Streaming TTS")

When TTS is enabled, the agent speaks its reply **sentence-by-sentence** as it generates text — you don't wait for the full response:

1. Buffers text deltas into complete sentences (min 20 chars)
2. Strips markdown formatting and `<think>` blocks
3. Generates and plays audio per sentence in real-time

### Hallucination Filter[​](#hallucination-filter "Direct link to Hallucination Filter")

Whisper sometimes generates phantom text from silence or background noise ("Thank you for watching", "Subscribe", etc.). The agent filters these out using a set of 26 known hallucination phrases across multiple languages, plus a regex pattern that catches repetitive variations.

---

## Gateway Voice Reply (Telegram & Discord)[​](#gateway-voice-reply-telegram--discord "Direct link to Gateway Voice Reply (Telegram & Discord)")

If you haven't set up your messaging bots yet, see the platform-specific guides:

- [Telegram Setup Guide](/docs/user-guide/messaging/telegram)
- [Discord Setup Guide](/docs/user-guide/messaging/discord)

Start the gateway to connect to your messaging platforms:

```
hermes gateway        # Start the gateway (connects to configured platforms)
hermes gateway setup  # Interactive setup wizard for first-time configuration
```

### Discord: Channels vs DMs[​](#discord-channels-vs-dms "Direct link to Discord: Channels vs DMs")

The bot supports two interaction modes on Discord:

- **Mode**, **How to Talk**, **Mention Required**, **Setup**
- **Mode**: **Direct Message (DM)**, **How to Talk**: Open the bot's profile → "Message", **Mention Required**: No, **Setup**: Works immediately
- **Mode**: **Server Channel**, **How to Talk**: Type in a text channel where the bot is present, **Mention Required**: Yes (`@botname`), **Setup**: Bot must be invited to the server

**DM (recommended for personal use):** Just open a DM with the bot and type — no @mention needed. Voice replies and all commands work the same as in channels.

**Server channels:** The bot only responds when you @mention it (e.g. `@hermesbyt4 hello`). Make sure you select the **bot user** from the mention popup, not the role with the same name.

tip

To disable the mention requirement in server channels, add to `~/.hermes/.env`:

```
DISCORD_REQUIRE_MENTION=false
```

Or set specific channels as free-response (no mention needed):

```
DISCORD_FREE_RESPONSE_CHANNELS=123456789,987654321
```

### Commands[​](#commands "Direct link to Commands")

These work in both Telegram and Discord (DMs and text channels):

```
/voice          Toggle voice mode on/off
/voice on       Voice replies only when you send a voice message
/voice tts      Voice replies for ALL messages
/voice off      Disable voice replies
/voice status   Show current setting
```

### Modes[​](#modes "Direct link to Modes")

- **Mode**, **Command**, **Behavior**
- **Mode**: `off`, **Command**: `/voice off`, **Behavior**: Text only (default)
- **Mode**: `voice_only`, **Command**: `/voice on`, **Behavior**: Speaks reply only when you send a voice message
- **Mode**: `all`, **Command**: `/voice tts`, **Behavior**: Speaks reply to every message

Voice mode setting is persisted across gateway restarts.

### Platform Delivery[​](#platform-delivery "Direct link to Platform Delivery")

- **Platform**, **Format**, **Notes**
- **Platform**: **Telegram**, **Format**: Voice bubble (Opus/OGG), **Notes**: Plays inline in chat. ffmpeg converts MP3 → Opus if needed
- **Platform**: **Discord**, **Format**: Native voice bubble (Opus/OGG), **Notes**: Plays inline like a user voice message. Falls back to file attachment if voice bubble API fails

---

## Discord Voice Channels[​](#discord-voice-channels "Direct link to Discord Voice Channels")

The most immersive voice feature: the bot joins a Discord voice channel, listens to users speaking, transcribes their speech, processes through the agent, and speaks the reply back in the voice channel.

### Setup[​](#setup "Direct link to Setup")

#### 1. Discord Bot Permissions[​](#1-discord-bot-permissions "Direct link to 1. Discord Bot Permissions")

If you already have a Discord bot set up for text (see [Discord Setup Guide](/docs/user-guide/messaging/discord)), you need to add voice permissions.

Go to the [Discord Developer Portal](https://discord.com/developers/applications) → your application → **Installation** → **Default Install Settings** → **Guild Install**:

**Add these permissions to the existing text permissions:**

- **Permission**, **Purpose**, **Required**
- **Permission**: **Connect**, **Purpose**: Join voice channels, **Required**: Yes
- **Permission**: **Speak**, **Purpose**: Play TTS audio in voice channels, **Required**: Yes
- **Permission**: **Use Voice Activity**, **Purpose**: Detect when users are speaking, **Required**: Recommended

**Updated Permissions Integer:**

- **Level**, **Integer**, **What's Included**
- **Level**: Text only, **Integer**: `274878286912`, **What's Included**: View Channels, Send Messages, Read History, Embeds, Attachments, Threads, Reactions
- **Level**: Text + Voice, **Integer**: `274881432640`, **What's Included**: All above + Connect, Speak

**Re-invite the bot** with the updated permissions URL:

```
https://discord.com/oauth2/authorize?client_id=YOUR_APP_ID&scope=bot+applications.commands&permissions=274881432640
```

Replace `YOUR_APP_ID` with your Application ID from the Developer Portal.

warning

Re-inviting the bot to a server it's already in will update its permissions without removing it. You won't lose any data or configuration.

#### 2. Privileged Gateway Intents[​](#2-privileged-gateway-intents "Direct link to 2. Privileged Gateway Intents")

In the [Developer Portal](https://discord.com/developers/applications) → your application → **Bot** → **Privileged Gateway Intents**, enable all three:

- **Intent**: Purpose
- ****Presence Intent****: Detect user online/offline status
- ****Server Members Intent****: Map voice SSRC identifiers to Discord user IDs
- ****Message Content Intent****: Read text message content in channels

All three are required for full voice channel functionality. **Server Members Intent** is especially critical — without it, the bot cannot identify who is speaking in the voice channel.

#### 3. Opus Codec[​](#3-opus-codec "Direct link to 3. Opus Codec")

The Opus codec library must be installed on the machine running the gateway:

```
# macOS (Homebrew)
brew install opus

# Ubuntu/Debian
sudo apt install libopus0
```

The bot auto-loads the codec from:

- **macOS:** `/opt/homebrew/lib/libopus.dylib`
- **Linux:** `libopus.so.0`

#### 4. Environment Variables[​](#4-environment-variables "Direct link to 4. Environment Variables")

```
# ~/.hermes/.env

# Discord bot (already configured for text)
DISCORD_BOT_TOKEN=your-bot-token
DISCORD_ALLOWED_USERS=your-user-id

# STT — local provider needs no key (pip install faster-whisper)
# GROQ_API_KEY=your-key            # Alternative: cloud-based, fast, free tier

# TTS — optional. Edge TTS and NeuTTS need no key.
# ELEVENLABS_API_KEY=***      # Premium quality
# VOICE_TOOLS_OPENAI_KEY=***  # OpenAI TTS / Whisper
```

### Start the Gateway[​](#start-the-gateway "Direct link to Start the Gateway")

```
hermes gateway        # Start with existing configuration
```

The bot should come online in Discord within a few seconds.

### Commands[​](#commands-1 "Direct link to Commands")

Use these in the Discord text channel where the bot is present:

```
/voice join      Bot joins your current voice channel
/voice channel   Alias for /voice join
/voice leave     Bot disconnects from voice channel
/voice status    Show voice mode and connected channel
```

info

You must be in a voice channel before running `/voice join`. The bot joins the same VC you're in.

### How It Works[​](#how-it-works-1 "Direct link to How It Works")

When the bot joins a voice channel, it:

1. **Listens** to each user's audio stream independently
2. **Detects silence** — 1.5s of silence after at least 0.5s of speech triggers processing
3. **Transcribes** the audio via Whisper STT (local, Groq, or OpenAI)
4. **Processes** through the full agent pipeline (session, tools, memory)
5. **Speaks** the reply back in the voice channel via TTS

### Text Channel Integration[​](#text-channel-integration "Direct link to Text Channel Integration")

When the bot is in a voice channel:

- Transcripts appear in the text channel: `[Voice] @user: what you said`
- Agent responses are sent as text in the channel AND spoken in the VC
- The text channel is the one where `/voice join` was issued

### Echo Prevention[​](#echo-prevention "Direct link to Echo Prevention")

The bot automatically pauses its audio listener while playing TTS replies, preventing it from hearing and re-processing its own output.

### Access Control[​](#access-control "Direct link to Access Control")

Only users listed in `DISCORD_ALLOWED_USERS` can interact via voice. Other users' audio is silently ignored.

```
# ~/.hermes/.env
DISCORD_ALLOWED_USERS=284102345871466496
```

---

## Configuration Reference[​](#configuration-reference "Direct link to Configuration Reference")

### config.yaml[​](#configyaml "Direct link to config.yaml")

```
# Voice recording (CLI)
voice:
  record_key: "ctrl+b"            # Key to start/stop recording
  max_recording_seconds: 120       # Maximum recording length
  auto_tts: false                  # Auto-enable TTS when voice mode starts
  beep_enabled: true               # Play record start/stop beeps
  silence_threshold: 200           # RMS level (0-32767) below which counts as silence
  silence_duration: 3.0            # Seconds of silence before auto-stop

# Speech-to-Text
stt:
  provider: "local"                  # "local" (free) | "groq" | "openai"
  local:
    model: "base"                    # tiny, base, small, medium, large-v3
  # model: "whisper-1"              # Legacy: used when provider is not set

# Text-to-Speech
tts:
  provider: "edge"                 # "edge" (free) | "elevenlabs" | "openai" | "neutts" | "minimax"
  edge:
    voice: "en-US-AriaNeural"      # 322 voices, 74 languages
  elevenlabs:
    voice_id: "pNInz6obpgDQGcFmaJgB"    # Adam
    model_id: "eleven_multilingual_v2"
  openai:
    model: "gpt-4o-mini-tts"
    voice: "alloy"                 # alloy, echo, fable, onyx, nova, shimmer
    base_url: "https://api.openai.com/v1"  # optional: override for self-hosted or OpenAI-compatible endpoints
  neutts:
    ref_audio: ''
    ref_text: ''
    model: neuphonic/neutts-air-q4-gguf
    device: cpu
```

### Environment Variables[​](#environment-variables "Direct link to Environment Variables")

```
# Speech-to-Text providers (local needs no key)
# pip install faster-whisper        # Free local STT — no API key needed
GROQ_API_KEY=...                    # Groq Whisper (fast, free tier)
VOICE_TOOLS_OPENAI_KEY=...         # OpenAI Whisper (paid)

# STT advanced overrides (optional)
STT_GROQ_MODEL=whisper-large-v3-turbo    # Override default Groq STT model
STT_OPENAI_MODEL=whisper-1               # Override default OpenAI STT model
GROQ_BASE_URL=https://api.groq.com/openai/v1     # Custom Groq endpoint
STT_OPENAI_BASE_URL=https://api.openai.com/v1    # Custom OpenAI STT endpoint

# Text-to-Speech providers (Edge TTS and NeuTTS need no key)
ELEVENLABS_API_KEY=***             # ElevenLabs (premium quality)
# VOICE_TOOLS_OPENAI_KEY above also enables OpenAI TTS

# Discord voice channel
DISCORD_BOT_TOKEN=...
DISCORD_ALLOWED_USERS=...
```

### STT Provider Comparison[​](#stt-provider-comparison "Direct link to STT Provider Comparison")

- **Provider**, **Model**, **Speed**, **Quality**, **Cost**, **API Key**
- **Provider**: **Local**, **Model**: `base`, **Speed**: Fast (depends on CPU/GPU), **Quality**: Good, **Cost**: Free, **API Key**: No
- **Provider**: **Local**, **Model**: `small`, **Speed**: Medium, **Quality**: Better, **Cost**: Free, **API Key**: No
- **Provider**: **Local**, **Model**: `large-v3`, **Speed**: Slow, **Quality**: Best, **Cost**: Free, **API Key**: No
- **Provider**: **Groq**, **Model**: `whisper-large-v3-turbo`, **Speed**: Very fast (~0.5s), **Quality**: Good, **Cost**: Free tier, **API Key**: Yes
- **Provider**: **Groq**, **Model**: `whisper-large-v3`, **Speed**: Fast (~1s), **Quality**: Better, **Cost**: Free tier, **API Key**: Yes
- **Provider**: **OpenAI**, **Model**: `whisper-1`, **Speed**: Fast (~1s), **Quality**: Good, **Cost**: Paid, **API Key**: Yes
- **Provider**: **OpenAI**, **Model**: `gpt-4o-transcribe`, **Speed**: Medium (~2s), **Quality**: Best, **Cost**: Paid, **API Key**: Yes

Provider priority (automatic fallback): **local** > **groq** > **openai**

### TTS Provider Comparison[​](#tts-provider-comparison "Direct link to TTS Provider Comparison")

- **Provider**, **Quality**, **Cost**, **Latency**, **Key Required**
- **Provider**: **Edge TTS**, **Quality**: Good, **Cost**: Free, **Latency**: ~1s, **Key Required**: No
- **Provider**: **ElevenLabs**, **Quality**: Excellent, **Cost**: Paid, **Latency**: ~2s, **Key Required**: Yes
- **Provider**: **OpenAI TTS**, **Quality**: Good, **Cost**: Paid, **Latency**: ~1.5s, **Key Required**: Yes
- **Provider**: **NeuTTS**, **Quality**: Good, **Cost**: Free, **Latency**: Depends on CPU/GPU, **Key Required**: No

NeuTTS uses the `tts.neutts` config block above.

---

## Troubleshooting[​](#troubleshooting "Direct link to Troubleshooting")

### "No audio device found" (CLI)[​](#no-audio-device-found-cli "Direct link to \"No audio device found\" (CLI)")

PortAudio is not installed:

```
brew install portaudio    # macOS
sudo apt install portaudio19-dev  # Ubuntu
```

### Bot doesn't respond in Discord server channels[​](#bot-doesnt-respond-in-discord-server-channels "Direct link to Bot doesn't respond in Discord server channels")

The bot requires an @mention by default in server channels. Make sure you:

1. Type `@` and select the **bot user** (with the #discriminator), not the **role** with the same name
2. Or use DMs instead — no mention needed
3. Or set `DISCORD_REQUIRE_MENTION=false` in `~/.hermes/.env`

### Bot joins VC but doesn't hear me[​](#bot-joins-vc-but-doesnt-hear-me "Direct link to Bot joins VC but doesn't hear me")

- Check your Discord user ID is in `DISCORD_ALLOWED_USERS`
- Make sure you're not muted in Discord
- The bot needs a SPEAKING event from Discord before it can map your audio — start speaking within a few seconds of joining

### Bot hears me but doesn't respond[​](#bot-hears-me-but-doesnt-respond "Direct link to Bot hears me but doesn't respond")

- Verify STT is available: install `faster-whisper` (no key needed) or set `GROQ_API_KEY` / `VOICE_TOOLS_OPENAI_KEY`
- Check the LLM model is configured and accessible
- Review gateway logs: `tail -f ~/.hermes/logs/gateway.log`

### Bot responds in text but not in voice channel[​](#bot-responds-in-text-but-not-in-voice-channel "Direct link to Bot responds in text but not in voice channel")

- TTS provider may be failing — check API key and quota
- Edge TTS (free, no key) is the default fallback
- Check logs for TTS errors

### Whisper returns garbage text[​](#whisper-returns-garbage-text "Direct link to Whisper returns garbage text")

The hallucination filter catches most cases automatically. If you're still getting phantom transcripts:

- Use a quieter environment
- Adjust `silence_threshold` in config (higher = less sensitive)
- Try a different STT model