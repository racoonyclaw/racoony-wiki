---
title: "Use Voice Mode with Hermes"
id: hermes-agent-use-voice-mode-with-hermes
pageType: entity
tags:
  - hermes-agent
  - documentation
hermes-source: https://hermes-agent.nousresearch.com/docs
---

Use Voice Mode with Hermes | Hermes Agent-
[Skip to main content](#__docusaurus_skipToContent_fallback)[Hermes Agent](/docs/)[Docs](/docs/getting-started/quickstart)[Skills](/docs/skills)[Home](https://hermes-agent.nousresearch.com)[GitHub](https://github.com/NousResearch/hermes-agent)[Discord](https://discord.gg/NousResearch)[Getting Started](/docs/getting-started/quickstart)
- [Using Hermes](/docs/user-guide/cli)
- [Features](/docs/user-guide/features/overview)
- [Messaging Platforms](/docs/user-guide/messaging/)
- [Integrations](/docs/integrations/)
- [Guides & Tutorials](/docs/guides/tips)[Tips & Best Practices](/docs/guides/tips)
- [Run Local LLMs on Mac](/docs/guides/local-llm-on-mac)
- [Tutorial: Daily Briefing Bot](/docs/guides/daily-briefing-bot)
- [Tutorial: Team Telegram Assistant](/docs/guides/team-telegram-assistant)
- [Using Hermes as a Python Library](/docs/guides/python-library)
- [Use MCP with Hermes](/docs/guides/use-mcp-with-hermes)
- [Use SOUL.md with Hermes](/docs/guides/use-soul-with-hermes)
- [Use Voice Mode with Hermes](/docs/guides/use-voice-mode-with-hermes)
- [Build a Plugin](/docs/guides/build-a-hermes-plugin)
- [Automate Anything with Cron](/docs/guides/automate-with-cron)
- [Automation Templates](/docs/guides/automation-templates)
- [Cron Troubleshooting](/docs/guides/cron-troubleshooting)
- [Working with Skills](/docs/guides/work-with-skills)
- [Delegation & Parallel Work](/docs/guides/delegation-patterns)
- [Tutorial: GitHub PR Review Agent](/docs/guides/github-pr-review-agent)
- [GitHub PR Reviews via Webhook](/docs/guides/webhook-github-pr-review)
- [Migrate from OpenClaw](/docs/guides/migrate-from-openclaw)
- [AWS Bedrock](/docs/guides/aws-bedrock)
- [Developer Guide](/docs/developer-guide/contributing)
- [Reference](/docs/reference/cli-commands)
- [](/docs/)
- Guides & Tutorials
- Use Voice Mode with Hermes
On this page# Use Voice Mode with Hermes
This guide is the practical companion to the [Voice Mode feature reference](/docs/user-guide/features/voice-mode).
If the feature page explains what voice mode can do, this guide shows how to actually use it well.
## What voice mode is good for[​](#what-voice-mode-is-good-for)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->
Voice mode is especially useful when:
- you want a hands-free CLI workflow
- you want spoken responses in Telegram or Discord
- you want Hermes sitting in a Discord voice channel for live conversation
- you want quick idea capture, debugging, or back-and-forth while walking around instead of typing
## Choose your voice mode setup[​](#choose-your-voice-mode-setup)
There are really three different voice experiences in Hermes.
ModeBest forPlatformInteractive microphone loopPersonal hands-free use while coding or researchingCLIVoice replies in chatSpoken responses alongside normal messagingTelegram, DiscordLive voice channel botGroup or personal live conversation in a VCDiscord voice channels
A good path is:
- get text working first
- enable voice replies second
- move to Discord voice channels last if you want the full experience
## Step 1: make sure normal Hermes works first[​](#step-1-make-sure-normal-hermes-works-first)
Before touching voice mode, verify that:
- Hermes starts
- your provider is configured
- the agent can answer text prompts normally
```
hermes
```
Ask something simple:
```
What tools do you have available?
```
If that is not solid yet, fix text mode first.
## Step 2: install the right extras[​](#step-2-install-the-right-extras)
### CLI microphone + playback[​](#cli-microphone--playback)
```
pip install "hermes-agent[voice]"
```
### Messaging platforms[​](#messaging-platforms)
```
pip install "hermes-agent[messaging]"
```
### Premium ElevenLabs TTS[​](#premium-elevenlabs-tts)
```
pip install "hermes-agent[tts-premium]"
```
### Local NeuTTS (optional)[​](#local-neutts-optional)
```
python -m pip install -U neutts[all]
```
### Everything[​](#everything)
```
pip install "hermes-agent[all]"
```
## Step 3: install system dependencies[​](#step-3-install-system-dependencies)
### macOS[​](#macos)
```
brew install portaudio ffmpeg opusbrew install espeak-ng
```
### Ubuntu / Debian[​](#ubuntu--debian)
```
sudo apt install portaudio19-dev ffmpeg libopus0sudo apt install espeak-ng
```
Why these matter:
- `portaudio` → microphone input / playback for CLI voice mode
- `ffmpeg` → audio conversion for TTS and messaging delivery
- `opus` → Discord voice codec support
- `espeak-ng` → phonemizer backend for NeuTTS
## Step 4: choose STT and TTS providers[​](#step-4-choose-stt-and-tts-providers)
Hermes supports both local and cloud speech stacks.
### Easiest / cheapest setup[​](#easiest--cheapest-setup)
Use local STT and free Edge TTS:
- STT provider: `local`
- TTS provider: `edge`
This is usually the best place to start.
### Environment file example[​](#environment-file-example)
Add to `~/.hermes/.env`:
```
# Cloud STT options (local needs no key)GROQ_API_KEY=***VOICE_TOOLS_OPENAI_KEY=***# Premium TTS (optional)ELEVENLABS_API_KEY=***
```
### Provider recommendations[​](#provider-recommendations)
#### Speech-to-text[​](#speech-to-text)
- `local` → best default for privacy and zero-cost use
- `groq` → very fast cloud transcription
- `openai` → good paid fallback
#### Text-to-speech[​](#text-to-speech)
- `edge` → free and good enough for most users
- `neutts` → free local/on-device TTS
- `elevenlabs` → best quality
- `openai` → good middle ground
- `mistral` → multilingual, native Opus
### If you use `hermes setup`[​](#if-you-use-hermes-setup)
If you choose NeuTTS in the setup wizard, Hermes checks whether `neutts` is already installed. If it is missing, the wizard tells you NeuTTS needs the Python package `neutts` and the system package `espeak-ng`, offers to install them for you, installs `espeak-ng` with your platform package manager, and then runs:
```
python -m pip install -U neutts[all]
```
If you skip that install or it fails, the wizard falls back to Edge TTS.
## Step 5: recommended config[​](#step-5-recommended-config)
```
voice:  record_key: "ctrl+b"  max_recording_seconds: 120  auto_tts: false  beep_enabled: true  silence_threshold: 200  silence_duration: 3.0stt:  provider: "local"  local:    model: "base"tts:  provider: "edge"  edge:    voice: "en-US-AriaNeural"
```
This is a good conservative default for most people.
If you want local TTS instead, switch the `tts` block to:
```
tts:  provider: "neutts"  neutts:    ref_audio: ''    ref_text: ''    model: neuphonic/neutts-air-q4-gguf    device: cpu
```
## Use case 1: CLI voice mode[​](#use-case-1-cli-voice-mode)
## Turn it on[​](#turn-it-on)
Start Hermes:
```
hermes
```
Inside the CLI:
```
/voice on
```
### Recording flow[​](#recording-flow)
Default key:
- `Ctrl+B`
Workflow:
- press `Ctrl+B`
- speak
- wait for silence detection to stop recording automatically
- Hermes transcribes and responds
- if TTS is on, it speaks the answer
- the loop can automatically restart for continuous use
### Useful commands[​](#useful-commands)
```
/voice/voice on/voice off/voice tts/voice status
```
### Good CLI workflows[​](#good-cli-workflows)
#### Walk-up debugging[​](#walk-up-debugging)
Say:
```
I keep getting a docker permission error. Help me debug it.
```
Then continue hands-free:
- "Read the last error again"
- "Explain the root cause in simpler terms"
- "Now give me the exact fix"
#### Research / brainstorming[​](#research--brainstorming)
Great for:
- walking around while thinking
- dictating half-formed ideas
- asking Hermes to structure your thoughts in real time
#### Accessibility / low-typing sessions[​](#accessibility--low-typing-sessions)
If typing is inconvenient, voice mode is one of the fastest ways to stay in the full Hermes loop.
## Tuning CLI behavior[​](#tuning-cli-behavior)
### Silence threshold[​](#silence-threshold)
If Hermes starts/stops too aggressively, tune:
```
voice:  silence_threshold: 250
```
Higher threshold = less sensitive.
### Silence duration[​](#silence-duration)
If you pause a lot between sentences, increase:
```
voice:  silence_duration: 4.0
```
### Record key[​](#record-key)
If `Ctrl+B` conflicts with your terminal or tmux habits:
```
voice:  record_key: "ctrl+space"
```
## Use case 2: voice replies in Telegram or Discord[​](#use-case-2-voice-replies-in-telegram-or-discord)
This mode is simpler than full voice channels.
Hermes stays a normal chat bot, but can speak replies.
### Start the gateway[​](#start-the-gateway)
```
hermes gateway
```
### Turn on voice replies[​](#turn-on-voice-replies)
Inside Telegram or Discord:
```
/voice on
```
or
```
/voice tts
```
### Modes[​](#modes)
ModeMeaning`off`text only`voice_only`speak only when the user sent voice`all`speak every reply
### When to use which mode[​](#when-to-use-which-mode)
- `/voice on` if you want spoken replies only for voice-originating messages
- `/voice tts` if you want a full spoken assistant all the time
### Good messaging workflows[​](#good-messaging-workflows)
#### Telegram assistant on your phone[​](#telegram-assistant-on-your-phone)
Use when:
- you are away from your machine
- you want to send voice notes and get quick spoken replies
- you want Hermes to function like a portable research or ops assistant
#### Discord DMs with spoken output[​](#discord-dms-with-spoken-output)
Useful when you want private interaction without server-channel mention behavior.
## Use case 3: Discord voice channels[​](#use-case-3-discord-voice-channels)
This is the most advanced mode.
Hermes joins a Discord VC, listens to user speech, transcribes it, runs the normal agent pipeline, and speaks replies back into the channel.
## Required Discord permissions[​](#required-discord-permissions)
In addition to the normal text-bot setup, make sure the bot has:
- Connect
- Speak
- preferably Use Voice Activity
Also enable privileged intents in the Developer Portal:
- Presence Intent
- Server Members Intent
- Message Content Intent
## Join and leave[​](#join-and-leave)
In a Discord text channel where the bot is present:
```
/voice join/voice leave/voice status
```
### What happens when joined[​](#what-happens-when-joined)
- users speak in the VC
- Hermes detects speech boundaries
- transcripts are posted in the associated text channel
- Hermes responds in text and audio
- the text channel is the one where `/voice join` was issued
### Best practices for Discord VC use[​](#best-practices-for-discord-vc-use)
- keep `DISCORD_ALLOWED_USERS` tight
- use a dedicated bot/testing channel at first
- verify STT and TTS work in ordinary text-chat voice mode before trying VC mode
## Voice quality recommendations[​](#voice-quality-recommendations)
### Best quality setup[​](#best-quality-setup)
- STT: local `large-v3` or Groq `whisper-large-v3`
- TTS: ElevenLabs
### Best speed / convenience setup[​](#best-speed--convenience-setup)
- STT: local `base` or Groq
- TTS: Edge
### Best zero-cost setup[​](#best-zero-cost-setup)
- STT: local
- TTS: Edge
## Common failure modes[​](#common-failure-modes)
### "No audio device found"[​](#no-audio-device-found)
Install `portaudio`.
### "Bot joins but hears nothing"[​](#bot-joins-but-hears-nothing)
Check:
- your Discord user ID is in `DISCORD_ALLOWED_USERS`
- you are not muted
- privileged intents are enabled
- the bot has Connect/Speak permissions
### "It transcribes but does not speak"[​](#it-transcribes-but-does-not-speak)
Check:
- TTS provider config
- API key / quota for ElevenLabs or OpenAI
- `ffmpeg` install for Edge conversion paths
### "Whisper outputs garbage"[​](#whisper-outputs-garbage)
Try:
- quieter environment
- higher `silence_threshold`
- different STT provider/model
- shorter, clearer utterances
### "It works in DMs but not in server channels"[​](#it-works-in-dms-but-not-in-server-channels)
That is often mention policy.
By default, the bot needs an `@mention` in Discord server text channels unless configured otherwise.
## Suggested first-week setup[​](#suggested-first-week-setup)
If you want the shortest path to success:
- get text Hermes working
- install `hermes-agent[voice]`
- use CLI voice mode with local STT + Edge TTS
- then enable `/voice on` in Telegram or Discord
- only after that, try Discord VC mode
That progression keeps the debugging surface small.
## Where to read next[​](#where-to-read-next)
- [Voice Mode feature reference](/docs/user-guide/features/voice-mode)
- [Messaging Gateway](/docs/user-guide/messaging)
- [Discord setup](/docs/user-guide/messaging/discord)
- [Telegram setup](/docs/user-guide/messaging/telegram)
- [Configuration](/docs/user-guide/configuration)
[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/guides/use-voice-mode-with-hermes.md)[PreviousUse SOUL.md with Hermes](/docs/guides/use-soul-with-hermes)[NextBuild a Plugin](/docs/guides/build-a-hermes-plugin)- [What voice mode is good for](#what-voice-mode-is-good-for)
- [Choose your voice mode setup](#choose-your-voice-mode-setup)
- [Step 1: make sure normal Hermes works first](#step-1-make-sure-normal-hermes-works-first)
- [Step 2: install the right extras](#step-2-install-the-right-extras)[CLI microphone + playback](#cli-microphone--playback)
- [Messaging platforms](#messaging-platforms)
- [Premium ElevenLabs TTS](#premium-elevenlabs-tts)
- [Local NeuTTS (optional)](#local-neutts-optional)
- [Everything](#everything)
- [Step 3: install system dependencies](#step-3-install-system-dependencies)[macOS](#macos)
- [Ubuntu / Debian](#ubuntu--debian)
- [Step 4: choose STT and TTS providers](#step-4-choose-stt-and-tts-providers)[Easiest / cheapest setup](#easiest--cheapest-setup)
- [Environment file example](#environment-file-example)
- [Provider recommendations](#provider-recommendations)
- [If you use `hermes setup`](#if-you-use-hermes-setup)
- [Step 5: recommended config](#step-5-recommended-config)
- [Use case 1: CLI voice mode](#use-case-1-cli-voice-mode)
- [Turn it on](#turn-it-on)[Recording flow](#recording-flow)
- [Useful commands](#useful-commands)
- [Good CLI workflows](#good-cli-workflows)
- [Tuning CLI behavior](#tuning-cli-behavior)[Silence threshold](#silence-threshold)
- [Silence duration](#silence-duration)
- [Record key](#record-key)
- [Use case 2: voice replies in Telegram or Discord](#use-case-2-voice-replies-in-telegram-or-discord)[Start the gateway](#start-the-gateway)
- [Turn on voice replies](#turn-on-voice-replies)
- [Modes](#modes)
- [When to use which mode](#when-to-use-which-mode)
- [Good messaging workflows](#good-messaging-workflows)
- [Use case 3: Discord voice channels](#use-case-3-discord-voice-channels)
- [Required Discord permissions](#required-discord-permissions)
- [Join and leave](#join-and-leave)[What happens when joined](#what-happens-when-joined)
- [Best practices for Discord VC use](#best-practices-for-discord-vc-use)
- [Voice quality recommendations](#voice-quality-recommendations)[Best quality setup](#best-quality-setup)
- [Best speed / convenience setup](#best-speed--convenience-setup)
- [Best zero-cost setup](#best-zero-cost-setup)
- [Common failure modes](#common-failure-modes)["No audio device found"](#no-audio-device-found)
- ["Bot joins but hears nothing"](#bot-joins-but-hears-nothing)
- ["It transcribes but does not speak"](#it-transcribes-but-does-not-speak)
- ["Whisper outputs garbage"](#whisper-outputs-garbage)
- ["It works in DMs but not in server channels"](#it-works-in-dms-but-not-in-server-channels)
- [Suggested first-week setup](#suggested-first-week-setup)
- [Where to read next](#where-to-read-next)
Docs- [Getting Started](/docs/getting-started/quickstart)
- [User Guide](/docs/user-guide/cli)
- [Developer Guide](/docs/developer-guide/architecture)
- [Reference](/docs/reference/cli-commands)
Community- [Discord](https://discord.gg/NousResearch)
- [GitHub Discussions](https://github.com/NousResearch/hermes-agent/discussions)
- [Skills Hub](https://agentskills.io)
More- [GitHub](https://github.com/NousResearch/hermes-agent)
- [Nous Research](https://nousresearch.com)
Built by [Nous Research](https://nousresearch.com) · MIT License · 2026
