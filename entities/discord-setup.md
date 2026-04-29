---
pageType: entity
id: entity.discord-setup
title: Discord Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/discord.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/discord.md
updatedAt: '2026-04-24T15:05:25.310369+00:00'
sourceIds:
- discordcom
- discordcom
- discordcom
sources:
- sourceId: discordcom
  sourceType: web
  sourcePath: https://discord.com/developers/applications
  title: '[Developer Portal](https://discord.com/developers/applications)'
- sourceId: discordcom
  sourceType: web
  sourcePath: https://discord.com/developers/applications
  title: '[Developer Portal](https://discord.com/developers/applications)'
- sourceId: discordcom
  sourceType: web
  sourcePath: https://discord.com/oauth2/authorize?client_id=YOUR_APP_ID&scope=bot+applications.commands&permissions=274878286912
  title: discord.com
claims:
- id: each-dm-gets-its-own-session
  text: each DM gets its own session
  status: supported
  confidence: null
- id: each-server-thread-gets-its-own-session-namespace
  text: each server thread gets its own session namespace
  status: supported
  confidence: null
- id: each-user-in-a-shared-channel-gets-their-own-session-inside
  text: each user in a shared channel gets their own session inside that channel
  status: supported
  confidence: null
- id: users-share-context-growth-and-token-costs
  text: users share context growth and token costs
  status: supported
  confidence: null
- id: one-persons-long-tool-heavy-task-can-bloat-everyone-elses
  text: one person's long tool-heavy task can bloat everyone else's context
  status: supported
  confidence: null
- id: one-persons-in-flight-run-can-interrupt-another-persons-fo
  text: one person's in-flight run can interrupt another person's follow-up in the
    same room
  status: supported
  confidence: null
- id: alice-interrupting-her-own-in-flight-request-only-affects-al
  text: Alice interrupting her own in-flight request only affects Alice's session
    in that channel
  status: supported
  confidence: null
- id: bob-can-keep-talking-in-the-same-channel-without-inheriting
  text: Bob can keep talking in the same channel without inheriting Alice's history
    or interrupting Alice's run
  status: supported
  confidence: null
- id: the-whole-room-shares-one-running-agent-slot-for-that-channe
  text: the whole room shares one running-agent slot for that channel/thread
  status: supported
  confidence: null
- id: follow-up-messages-from-different-people-can-interrupt-or-qu
  text: follow-up messages from different people can interrupt or queue behind each
    other
  status: supported
  confidence: null
- id: set-public-bot-to-on-required-to-use-the-discord-provided
  text: "Set Public Bot to ON \u2014 required to use the Discord-provided invite link\
    \ (recommended). This allows the Installation tab to generate a default authorization\
    \ URL."
  status: supported
  confidence: null
- id: leave-require-oauth2-code-grant-set-to-off
  text: Leave Require OAuth2 Code Grant set to OFF.
  status: supported
  confidence: null
- id: without-message-content-intent-your-bot-receives-message-ev
  text: "Without Message Content Intent, your bot receives message events but the\
    \ message text is empty \u2014 the bot literally cannot see what you typed."
  status: supported
  confidence: null
- id: without-server-members-intent-the-bot-cannot-resolve-userna
  text: Without Server Members Intent, the bot cannot resolve usernames for the allowed
    users list and may fail to identify who is messaging it.
  status: supported
  confidence: null
- id: if-your-bot-is-in-fewer-than-100-servers-you-can-simply-tog
  text: If your bot is in fewer than 100 servers, you can simply toggle intents on
    and off freely.
  status: supported
  confidence: null
- id: if-your-bot-is-in-100-or-more-servers-discord-requires-you
  text: If your bot is in 100 or more servers, Discord requires you to submit a verification
    application to use privileged intents. For personal use, this is not a concern.
  status: supported
  confidence: null
- id: scopes-select-bot-and-applicationscommands
  text: 'Scopes: select bot and applications.commands'
  status: supported
  confidence: null
- id: permissions-select-the-permissions-listed-below
  text: 'Permissions: select the permissions listed below.'
  status: supported
  confidence: null
- id: view-channels-see-the-channels-it-has-access-to
  text: "View Channels \u2014 see the channels it has access to"
  status: supported
  confidence: null
- id: send-messages-respond-to-your-messages
  text: "Send Messages \u2014 respond to your messages"
  status: supported
  confidence: null
- id: embed-links-format-rich-responses
  text: "Embed Links \u2014 format rich responses"
  status: supported
  confidence: null
- id: attach-files-send-images-audio-and-file-outputs
  text: "Attach Files \u2014 send images, audio, and file outputs"
  status: supported
  confidence: null
- id: read-message-history-maintain-conversation-context
  text: "Read Message History \u2014 maintain conversation context"
  status: supported
  confidence: null
- id: send-messages-in-threads-respond-in-thread-conversations
  text: "Send Messages in Threads \u2014 respond in thread conversations"
  status: supported
  confidence: null
- id: add-reactions-react-to-messages-for-acknowledgment
  text: "Add Reactions \u2014 react to messages for acknowledgment"
  status: supported
  confidence: null
- id: '1234567890'
  text: '1234567890'
  status: supported
  confidence: null
- id: '9876543210'
  text: '9876543210'
  status: supported
  confidence: null
- id: added-when-the-bot-starts-processing-your-message
  text: "\U0001F440 added when the bot starts processing your message"
  status: supported
  confidence: null
- id: added-when-the-response-is-delivered-successfully
  text: "\u2705 added when the response is delivered successfully"
  status: supported
  confidence: null
- id: added-if-an-error-occurs-during-processing
  text: "\u274C added if an error occurs during processing"
  status: supported
  confidence: null
- id: '1234567890'
  text: '1234567890'
  status: supported
  confidence: null
- id: '9876543210'
  text: '9876543210'
  status: supported
  confidence: null
- id: 1234567890-bot-responds-inline-here
  text: '1234567890 # Bot responds inline here'
  status: supported
  confidence: null
- id: exact-threadchannel-id-matches-win
  text: Exact thread/channel ID matches win.
  status: supported
  confidence: null
- id: if-a-message-arrives-inside-a-thread-or-forum-post-and-that
  text: If a message arrives inside a thread or forum post and that thread has no
    explicit entry, Hermes falls back to the parent channel/forum ID.
  status: supported
  confidence: null
- id: prompts-are-applied-ephemerally-at-runtime-so-changing-them
  text: Prompts are applied ephemerally at runtime, so changing them affects future
    turns immediately without rewriting past session history.
  status: supported
  confidence: null
- id: off-no-progress-messages
  text: "off \u2014 no progress messages"
  status: supported
  confidence: null
- id: new-only-show-the-first-tool-call-per-turn
  text: "new \u2014 only show the first tool call per turn"
  status: supported
  confidence: null
- id: all-show-all-tool-calls-truncated-to-40-characters-in-gat
  text: "all \u2014 show all tool calls (truncated to 40 characters in gateway messages)"
  status: supported
  confidence: null
- id: verbose-show-full-tool-call-details-can-produce-long-mess
  text: "verbose \u2014 show full tool call details (can produce long messages)"
  status: supported
  confidence: null
- id: each-skill-becomes-a-discord-slash-command-eg-code-revi
  text: Each skill becomes a Discord slash command (e.g., /code-review, /ascii-art)
  status: supported
  confidence: null
- id: skills-accept-an-optional-args-string-parameter
  text: Skills accept an optional args string parameter
  status: supported
  confidence: null
- id: discord-has-a-limit-of-100-application-commands-per-bot-if
  text: "Discord has a limit of 100 application commands per bot \u2014 if you have\
    \ more skills than available slots, extra skills are skipped with a warning in\
    \ the logs"
  status: supported
  confidence: null
- id: skills-are-registered-during-bot-startup-alongside-built-in
  text: Skills are registered during bot startup alongside built-in commands like
    /model, /reset, and /background
  status: supported
  confidence: null
- id: incoming-voice-messages-are-automatically-transcribed-using
  text: 'Incoming voice messages are automatically transcribed using the configured
    STT provider: local faster-whisper (no key), Groq Whisper (GROQ_API_KEY), or OpenAI
    Whisper (VOICE_TOOLS_OPENAI_KEY).'
  status: supported
  confidence: null
- id: text-to-speech-use-voice-tts-to-have-the-bot-send-spoken-a
  text: 'Text-to-speech: Use /voice tts to have the bot send spoken audio responses
    alongside text replies.'
  status: supported
  confidence: null
- id: discord-voice-channels-hermes-can-also-join-a-voice-channel
  text: 'Discord voice channels: Hermes can also join a voice channel, listen to users
    speaking, and talk back in the channel.'
  status: supported
  confidence: null
- id: voice-mode
  text: Voice Mode
  status: supported
  confidence: null
- id: use-voice-mode-with-hermes
  text: Use Voice Mode with Hermes
  status: supported
  confidence: null
- id: thread-name-is-derived-from-the-first-line-of-the-message-m
  text: Thread name is derived from the first line of the message (markdown heading
    prefix stripped, capped at 100 chars). When the message is attachment-only, the
    filename is used as the fallback thread name.
  status: supported
  confidence: null
- id: attachments-ride-along-on-the-starter-message-of-the-new-thr
  text: "Attachments ride along on the starter message of the new thread \u2014 no\
    \ separate upload step, no partial sends."
  status: supported
  confidence: null
- id: one-call-one-thread-each-forum-send-creates-a-new-thread
  text: 'One call, one thread: each forum send creates a new thread. Successive sends
    to the same forum will therefore produce separate threads.'
  status: supported
  confidence: null
- id: detection-is-three-layered-the-channel-directory-cache-firs
  text: 'Detection is three-layered: the channel directory cache first, a process-local
    probe cache second, and a live GET /channels/{id} probe as a last resort (whose
    result is then memoized for the life of the process).'
  status: supported
  confidence: null
- id: or-with-user-allowlist-a-user-is-authorized-if-their-id-is
  text: OR with user allowlist. A user is authorized if their ID is in DISCORD_ALLOWED_USERS
    or they have any role in DISCORD_ALLOWED_ROLES.
  status: supported
  confidence: null
- id: server-members-intent-auto-enabled-when-discord-allowed-rol
  text: "Server Members Intent auto-enabled. When DISCORD_ALLOWED_ROLES is set, the\
    \ bot enables the Members intent on connect \u2014 required for Discord to send\
    \ role information with member records."
  status: supported
  confidence: null
- id: role-ids-not-names-grab-them-from-discord-user-settings
  text: "Role IDs, not names. Grab them from Discord: User Settings \u2192 Advanced\
    \ \u2192 Developer Mode ON, then right-click any role \u2192 Copy Role ID."
  status: supported
  confidence: null
- id: dm-fallback-in-dms-the-role-check-scans-mutual-guilds-a-us
  text: DM fallback. In DMs the role check scans mutual guilds; a user with an allowed
    role in any shared server is authorized in DMs too.
  status: supported
  confidence: null
- id: discord-gateway-model
  text: Discord Gateway Model
  status: supported
  confidence: null
- id: session-model-in-discord
  text: Session Model in Discord
  status: supported
  confidence: null
- id: interrupts-and-concurrency
  text: Interrupts and Concurrency
  status: supported
  confidence: null
- id: step-1-create-a-discord-applicationstep-1-create-a-disc
  text: '[Step 1: Create a Discord Application](#step-1-create-a-discord-application)'
  status: supported
  confidence: null
- id: step-2-create-the-botstep-2-create-the-bot
  text: '[Step 2: Create the Bot](#step-2-create-the-bot)'
  status: supported
  confidence: null
- id: step-3-enable-privileged-gateway-intentsstep-3-enable-p
  text: '[Step 3: Enable Privileged Gateway Intents](#step-3-enable-privileged-gateway-intents)'
  status: supported
  confidence: null
- id: step-4-get-the-bot-tokenstep-4-get-the-bot-token
  text: '[Step 4: Get the Bot Token](#step-4-get-the-bot-token)'
  status: supported
  confidence: null
- id: step-5-generate-the-invite-urlstep-5-generate-the-invit
  text: '[Step 5: Generate the Invite URL](#step-5-generate-the-invite-url)[](#option-a-using-the-installation-tab-recommended)[](#option-b-manual-url)[](#required-permissions)[](#recommended-additional-permissions)[](#permission-integers)'
  status: supported
  confidence: null
- id: option-a-using-the-installation-tab-recommended
  text: 'Option A: Using the Installation Tab (Recommended)'
  status: supported
  confidence: null
- id: option-b-manual-url
  text: 'Option B: Manual URL'
  status: supported
  confidence: null
- id: required-permissions
  text: Required Permissions
  status: supported
  confidence: null
- id: recommended-additional-permissions
  text: Recommended Additional Permissions
  status: supported
  confidence: null
- id: permission-integers
  text: Permission Integers
  status: supported
  confidence: null
- id: step-6-invite-to-your-serverstep-6-invite-to-your-serve
  text: '[Step 6: Invite to Your Server](#step-6-invite-to-your-server)'
  status: supported
  confidence: null
- id: step-7-find-your-discord-user-idstep-7-find-your-discor
  text: '[Step 7: Find Your Discord User ID](#step-7-find-your-discord-user-id)'
  status: supported
  confidence: null
- id: step-8-configure-hermes-agentstep-8-configure-hermes-ag
  text: '[Step 8: Configure Hermes Agent](#step-8-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)'
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
- id: configuration-referenceconfiguration-referenceenvir
  text: '[Configuration Reference](#configuration-reference)[](#environment-variables-env)[](#config-file-configyaml)'
  status: supported
  confidence: null
- id: environment-variables-env
  text: Environment Variables (.env)
  status: supported
  confidence: null
- id: config-file-configyaml
  text: Config File (config.yaml)
  status: supported
  confidence: null
- id: interactive-model-pickerinteractive-model-picker
  text: '[Interactive Model Picker](#interactive-model-picker)'
  status: supported
  confidence: null
- id: native-slash-commands-for-skillsnative-slash-commands-fo
  text: '[Native Slash Commands for Skills](#native-slash-commands-for-skills)'
  status: supported
  confidence: null
- id: home-channelhome-channelusing-the-slash-command
  text: '[Home Channel](#home-channel)[](#using-the-slash-command)[](#manual-configuration)'
  status: supported
  confidence: null
- id: using-the-slash-command
  text: Using the Slash Command
  status: supported
  confidence: null
- id: manual-configuration
  text: Manual Configuration
  status: supported
  confidence: null
- id: voice-messagesvoice-messages
  text: '[Voice Messages](#voice-messages)'
  status: supported
  confidence: null
- id: forum-channelsforum-channels
  text: '[Forum Channels](#forum-channels)'
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingbot-is-online-but-not
  text: '[Troubleshooting](#troubleshooting)[](#bot-is-online-but-not-responding-to-messages)[](#disallowed-intents-error-on-startup)[](#bot-cant-see-messages-in-a-specific-channel)[](#403-forbidden-errors)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)[](#people-in-the-same-channel-are-sharing-context-unexpectedly)'
  status: supported
  confidence: null
- id: bot-is-online-but-not-responding-to-messages
  text: Bot is online but not responding to messages
  status: supported
  confidence: null
- id: disallowed-intents-error-on-startup
  text: '"Disallowed Intents" error on startup'
  status: supported
  confidence: null
- id: bot-cant-see-messages-in-a-specific-channel
  text: Bot can't see messages in a specific channel
  status: supported
  confidence: null
- id: 403-forbidden-errors
  text: 403 Forbidden errors
  status: supported
  confidence: null
- id: bot-is-offline
  text: Bot is offline
  status: supported
  confidence: null
- id: user-not-allowed-bot-ignores-you
  text: '"User not allowed" / Bot ignores you'
  status: supported
  confidence: null
- id: people-in-the-same-channel-are-sharing-context-unexpectedly
  text: People in the same channel are sharing context unexpectedly
  status: supported
  confidence: null
- id: securitysecurityrole-based-access-controlmenti
  text: '[[[entity.security|Security]]](#[[entity.security|Security]])[](#role-based-access-control)[](#mention-control)'
  status: supported
  confidence: null
- id: role-based-access-control
  text: Role-Based Access Control
  status: supported
  confidence: null
- id: mention-control
  text: Mention Control
  status: supported
  confidence: null
---

On this page

Hermes Agent integrates with Discord as a bot, letting you chat with your AI assistant through direct messages or server channels. The bot receives your messages, processes them through the Hermes Agent pipeline (including tool use, memory, and reasoning), and responds in real time. It supports text, voice messages, file attachments, and slash commands.

Before setup, here's the part most people want to know: how Hermes behaves once it's in your server.

## How Hermes Behaves[​](#how-hermes-behaves)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[entities/messaging-gateway|Messaging Gateway]]
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]

### Related Pages
- [[entities/features-voice-mode|Features: Voice Mode]]
<!-- openclaw:wiki:related:end -->

****************************
tip

If you want a normal bot-help channel where people can talk to Hermes without tagging it every time, add that channel to DISCORD_FREE_RESPONSE_CHANNELS.

### Discord Gateway Model[​](#discord-gateway-model)

Hermes on Discord is not a webhook that replies statelessly. It runs through the full [[entities/messaging-gateway|Messaging Gateway]], which means each incoming message goes through:

1. authorization (DISCORD_ALLOWED_USERS)

2. mention / free-response checks

3. session lookup

4. session transcript loading

5. normal Hermes agent execution, including tools, memory, and slash commands

6. response delivery back to Discord

That matters because behavior in a busy server depends on both Discord routing and Hermes session policy.

### Session Model in Discord[​](#session-model-in-discord)

By default:

- each DM gets its own session

- each server thread gets its own session namespace

- each user in a shared channel gets their own session inside that channel

So if Alice and Bob both talk to Hermes in #research, Hermes treats those as separate conversations by default even though they are using the same visible Discord channel.

This is controlled by config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

Set it to false only if you explicitly want one shared conversation for the entire room:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: false

```

Shared sessions can be useful for a collaborative room, but they also mean:

- users share context growth and token costs

- one person's long tool-heavy task can bloat everyone else's context

- one person's in-flight run can interrupt another person's follow-up in the same room

### Interrupts and Concurrency[​](#interrupts-and-concurrency)

Hermes tracks running agents by session key.

With the default group_sessions_per_user: true:

- Alice interrupting her own in-flight request only affects Alice's session in that channel

- Bob can keep talking in the same channel without inheriting Alice's history or interrupting Alice's run

With group_sessions_per_user: false:

- the whole room shares one running-agent slot for that channel/thread

- follow-up messages from different people can interrupt or queue behind each other

This guide walks you through the full setup process — from creating your bot on Discord's Developer Portal to sending your first message.

## Step 1: Create a Discord Application[​](#step-1-create-a-discord-application)

[](https://discord.com/developers/applications)********
1. Go to the Discord Developer Portal and sign in with your Discord account.

2. Click New Application in the top-right corner.

3. Enter a name for your application (e.g., "Hermes Agent") and accept the Developer Terms of Service.

4. Click Create.

You'll land on the **General Information** page. Note the **Application ID** — you'll need it later to build the invite URL.

## Step 2: Create the Bot[​](#step-2-create-the-bot)

************************
- Set Public Bot to ON — required to use the Discord-provided invite link (recommended). This allows the Installation tab to generate a default authorization URL.

- Leave Require OAuth2 Code Grant set to OFF.

tip

You can set a custom avatar and banner for your bot on this page. This is what users will see in Discord.

Private Bot Alternative

If you prefer to keep your bot private (Public Bot = OFF), you **must** use the **Manual URL** method in Step 5 instead of the Installation tab. The Discord-provided link requires Public Bot to be enabled.

## Step 3: Enable Privileged Gateway Intents[​](#step-3-enable-privileged-gateway-intents)

This is the most critical step in the entire setup. Without the correct intents enabled, your bot will connect to Discord but **will not be able to read message content**.

On the **Bot** page, scroll down to **Privileged Gateway Intents**. You'll see three toggles:

********************

**Enable both Server Members Intent and Message Content Intent** by toggling them **ON**.

********
- Without Message Content Intent, your bot receives message events but the message text is empty — the bot literally cannot see what you typed.

- Without Server Members Intent, the bot cannot resolve usernames for the allowed users list and may fail to identify who is messaging it.

This is the #1 reason Discord bots don't work

If your bot is online but never responds to messages, the **Message Content Intent** is almost certainly disabled. Go back to the [Developer Portal](https://discord.com/developers/applications), select your application → Bot → Privileged Gateway Intents, and make sure **Message Content Intent** is toggled ON. Click **Save Changes**.

**Regarding server count:**

********
- If your bot is in fewer than 100 servers, you can simply toggle intents on and off freely.

- If your bot is in 100 or more servers, Discord requires you to submit a verification application to use privileged intents. For personal use, this is not a concern.

Click **Save Changes** at the bottom of the page.

## Step 4: Get the Bot Token[​](#step-4-get-the-bot-token)

The bot token is the credential Hermes Agent uses to log in as your bot. Still on the **Bot** page:

************
1. Under the Token section, click Reset Token.

2. If you have two-factor authentication enabled on your Discord account, enter your 2FA code.

3. Discord will display your new token. Copy it immediately.

Token shown only once

The token is only displayed once. If you lose it, you'll need to reset it and generate a new one. Never share your token publicly or commit it to Git — anyone with this token has full control of your bot.

Store the token somewhere safe (a password manager, for example). You'll need it in Step 8.

## Step 5: Generate the Invite URL[​](#step-5-generate-the-invite-url)

You need an OAuth2 URL to invite the bot to your server. There are two ways to do this:

### Option A: Using the Installation Tab (Recommended)[​](#option-a-using-the-installation-tab-recommended)

Requires Public Bot

This method requires **Public Bot** to be set to **ON** in Step 2. If you set Public Bot to OFF, use the Manual URL method below instead.

********************************
- Scopes: select bot and applications.commands

- Permissions: select the permissions listed below.

### Option B: Manual URL[​](#option-b-manual-url)

You can construct the invite URL directly using this format:

```prism-code text codeBlock_bY9V thin-scrollbar
https://discord.com/oauth2/authorize?client_id=YOUR_APP_ID&scope=bot+applications.commands&permissions=274878286912

```

Replace YOUR_APP_ID with the Application ID from Step 1.

### Required Permissions[​](#required-permissions)

These are the minimum permissions your bot needs:

********************
- View Channels — see the channels it has access to

- Send Messages — respond to your messages

- Embed Links — format rich responses

- Attach Files — send images, audio, and file outputs

- Read Message History — maintain conversation context

### Recommended Additional Permissions[​](#recommended-additional-permissions)

********
- Send Messages in Threads — respond in thread conversations

- Add Reactions — react to messages for acknowledgment

### Permission Integers[​](#permission-integers)

## Step 6: Invite to Your Server[​](#step-6-invite-to-your-server)

************
1. Open the invite URL in your browser (from the Installation tab or the manual URL you constructed).

2. In the Add to Server dropdown, select your server.

3. Click Continue, then Authorize.

4. Complete the CAPTCHA if prompted.

info

You need the **Manage Server** permission on the Discord server to invite a bot. If you don't see your server in the dropdown, ask a server admin to use the invite link instead.

After authorizing, the bot will appear in your server's member list (it will show as offline until you start the Hermes gateway).

## Step 7: Find Your Discord User ID[​](#step-7-find-your-discord-user-id)

Hermes Agent uses your Discord User ID to control who can interact with the bot. To find it:

********************
1. Open Discord (desktop or web app).

2. Go to Settings → Advanced → toggle Developer Mode to ON.

3. Close settings.

4. Right-click your own username (in a message, the member list, or your profile) → Copy User ID.

Your User ID is a long number like 284102345871466496.

tip

Developer Mode also lets you copy **Channel IDs** and **Server IDs** the same way — right-click the channel or server name and select Copy ID. You'll need a Channel ID if you want to set a home channel manually.

## Step 8: Configure Hermes Agent[​](#step-8-configure-hermes-agent)

### Option A: Interactive Setup (Recommended)[​](#option-a-interactive-setup-recommended)

Run the guided setup command:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Discord** when prompted, then paste your bot token and user ID when asked.

### Option B: Manual Configuration[​](#option-b-manual-configuration)

Add the following to your ~/.hermes/.env file:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Required
DISCORD_BOT_TOKEN=your-bot-token
DISCORD_ALLOWED_USERS=284102345871466496

# Multiple allowed users (comma-separated)
# DISCORD_ALLOWED_USERS=284102345871466496,198765432109876543

```

Then start the gateway:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

The bot should come online in Discord within a few seconds. Send it a message — either a DM or in a channel it can see — to test.

tip

You can run hermes gateway in the background or as a systemd service for persistent operation. See the deployment docs for details.

## Configuration Reference[​](#configuration-reference)

Discord behavior is controlled through two files: **~/.hermes/.env** for credentials and env-level toggles, and **~/.hermes/config.yaml** for structured settings. Environment variables always take precedence over config.yaml values when both are set.

### Environment Variables (.env)[​](#environment-variables-env)

****[](https://discord.com/developers/applications)************************[](#mention-control)

### Config File (config.yaml)[​](#config-file-configyaml)

The discord section in ~/.hermes/config.yaml mirrors the env vars above. Config.yaml settings are applied as defaults — if the equivalent env var is already set, the env var wins.

```prism-code yaml codeBlock_bY9V thin-scrollbar
# Discord-specific settings
discord:
 require_mention: true # Require @mention in server channels
 free_response_channels: "" # Comma-separated channel IDs (or YAML list)
 auto_thread: true # Auto-create threads on @mention
 reactions: true # Add emoji reactions during processing
 ignored_channels: [] # Channel IDs where bot never responds
 no_thread_channels: [] # Channel IDs where bot responds without threading
 channel_prompts: {} # Per-channel ephemeral system prompts
 allow_mentions: # What the bot is allowed to ping (safe defaults)
 everyone: false # @everyone / @here pings (default: false)
 roles: false # @role pings (default: false)
 users: true # @user pings (default: true)
 replied_user: true # reply-reference pings the author (default: true)

# Session isolation (applies to all gateway platforms, not just Discord)
group_sessions_per_user: true # Isolate sessions per user in shared channels

```

#### discord.require_mention[​](#discordrequire_mention)

**Type:** boolean — **Default:** true

When enabled, the bot only responds in server channels when directly @mentioned. DMs always get a response regardless of this setting.

#### discord.free_response_channels[​](#discordfree_response_channels)

**Type:** string or list — **Default:** ""

Channel IDs where the bot responds to all messages without needing an @mention. Accepts either a comma-separated string or a YAML list:

```prism-code yaml codeBlock_bY9V thin-scrollbar
# String format
discord:
 free_response_channels: "1234567890,9876543210"

# List format
discord:
 free_response_channels:
 - 1234567890
 - 9876543210

```

If a thread's parent channel is in this list, the thread also becomes mention-free.

Free-response channels also **skip auto-threading** — the bot replies inline rather than spinning off a new thread per message. This keeps the channel usable as a lightweight chat surface. If you want threading behavior, don't list the channel as free-response (use normal @mention flow instead).

#### discord.auto_thread[​](#discordauto_thread)

**Type:** boolean — **Default:** true

When enabled, every @mention in a regular text channel automatically creates a new thread for the conversation. This keeps the main channel clean and gives each conversation its own isolated session history. Once a thread is created, subsequent messages in that thread don't require @mention — the bot knows it's already participating.

Messages sent in existing threads or DMs are unaffected by this setting. Channels listed in discord.free_response_channels or discord.no_thread_channels also bypass auto-threading and get inline replies instead.

#### discord.reactions[​](#discordreactions)

**Type:** boolean — **Default:** true

Controls whether the bot adds emoji reactions to messages as visual feedback:

- 👀 added when the bot starts processing your message

- ✅ added when the response is delivered successfully

- ❌ added if an error occurs during processing

Disable this if you find the reactions distracting or if the bot's role doesn't have the **Add Reactions** permission.

#### discord.ignored_channels[​](#discordignored_channels)

**Type:** string or list — **Default:** []

Channel IDs where the bot **never** responds, even when directly @mentioned. This takes the highest priority — if a channel is in this list, the bot silently ignores all messages there, regardless of require_mention, free_response_channels, or any other setting.

```prism-code yaml codeBlock_bY9V thin-scrollbar
# String format
discord:
 ignored_channels: "1234567890,9876543210"

# List format
discord:
 ignored_channels:
 - 1234567890
 - 9876543210

```

If a thread's parent channel is in this list, messages in that thread are also ignored.

#### discord.no_thread_channels[​](#discordno_thread_channels)

**Type:** string or list — **Default:** []

Channel IDs where the bot responds directly in the channel instead of auto-creating a thread. This only has an effect when auto_thread is true (the default). In these channels, the bot responds inline like a normal message rather than spawning a new thread.

```prism-code yaml codeBlock_bY9V thin-scrollbar
discord:
 no_thread_channels:
 - 1234567890 # Bot responds inline here

```

Useful for channels dedicated to bot interaction where threads would add unnecessary noise.

#### discord.channel_prompts[​](#discordchannel_prompts)

**Type:** mapping — **Default:** {}

Per-channel ephemeral system prompts that are injected on every turn in the matching Discord channel or thread without being persisted to transcript history.

```prism-code yaml codeBlock_bY9V thin-scrollbar
discord:
 channel_prompts:
 "1234567890": |
 This channel is for research tasks. Prefer deep comparisons,
 citations, and concise synthesis.
 "9876543210": |
 This forum is for therapy-style support. Be warm, grounded,
 and non-judgmental.

```

Behavior:

- Exact thread/channel ID matches win.

- If a message arrives inside a thread or forum post and that thread has no explicit entry, Hermes falls back to the parent channel/forum ID.

- Prompts are applied ephemerally at runtime, so changing them affects future turns immediately without rewriting past session history.

#### group_sessions_per_user[​](#group_sessions_per_user)

**Type:** boolean — **Default:** true

This is a global gateway setting (not Discord-specific) that controls whether users in the same channel get isolated session histories.

When true: Alice and Bob talking in #research each have their own separate conversation with Hermes. When false: the entire channel shares one conversation transcript and one running-agent slot.

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

See the [Session Model](#session-model-in-discord) section above for the full implications of each mode.

#### display.tool_progress[​](#displaytool_progress)

**Type:** string — **Default:** "all" — **Values:** off, new, all, verbose

Controls whether the bot sends progress messages in the chat while processing (e.g., "Reading file...", "Running terminal command..."). This is a global gateway setting that applies to all platforms.

```prism-code yaml codeBlock_bY9V thin-scrollbar
display:
 tool_progress: "all" # off | new | all | verbose

```

- off — no progress messages

- new — only show the first tool call per turn

- all — show all tool calls (truncated to 40 characters in gateway messages)

- verbose — show full tool call details (can produce long messages)

#### display.tool_progress_command[​](#displaytool_progress_command)

**Type:** boolean — **Default:** false

When enabled, makes the /verbose slash command available in the gateway, letting you cycle through tool progress modes (off → new → all → verbose → off) without editing config.yaml.

```prism-code yaml codeBlock_bY9V thin-scrollbar
display:
 tool_progress_command: true

```

## Interactive Model Picker[​](#interactive-model-picker)

Send /model with no arguments in a Discord channel to open a dropdown-based model picker:

********
1. Provider selection — a Select dropdown showing available providers (up to 25).

2. Model selection — a second dropdown with models for the chosen provider (up to 25).

The picker times out after 120 seconds. Only authorized users (those in DISCORD_ALLOWED_USERS) can interact with it. If you know the model name, type /model <name> directly.

## Native Slash Commands for Skills[​](#native-slash-commands-for-skills)

Hermes automatically registers installed skills as **native Discord Application Commands**. This means skills appear in Discord's autocomplete / menu alongside built-in commands.

- Each skill becomes a Discord slash command (e.g., /code-review, /ascii-art)

- Skills accept an optional args string parameter

- Discord has a limit of 100 application commands per bot — if you have more skills than available slots, extra skills are skipped with a warning in the logs

- Skills are registered during bot startup alongside built-in commands like /model, /reset, and /background

No extra configuration is needed — any skill installed via hermes skills install is automatically registered as a Discord slash command on the next gateway restart.

## Home Channel[​](#home-channel)

You can designate a "home channel" where the bot sends proactive messages (such as cron job output, reminders, and notifications). There are two ways to set it:

### Using the Slash Command[​](#using-the-slash-command)

Type /sethome in any Discord channel where the bot is present. That channel becomes the home channel.

### Manual Configuration[​](#manual-configuration)

Add these to your ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
DISCORD_HOME_CHANNEL=123456789012345678
DISCORD_HOME_CHANNEL_NAME="#bot-updates"

```

Replace the ID with the actual channel ID (right-click → Copy Channel ID with Developer Mode on).

## Voice Messages[​](#voice-messages)

Hermes Agent supports Discord voice messages:

************
- Incoming voice messages are automatically transcribed using the configured STT provider: local faster-whisper (no key), Groq Whisper (GROQ_API_KEY), or OpenAI Whisper (VOICE_TOOLS_OPENAI_KEY).

- Text-to-speech: Use /voice tts to have the bot send spoken audio responses alongside text replies.

- Discord voice channels: Hermes can also join a voice channel, listen to users speaking, and talk back in the channel.

For the full setup and operational guide, see:

[](/docs/user-guide/features/voice-mode)[](/docs/guides/use-voice-mode-with-hermes)
- Voice Mode

- Use Voice Mode with Hermes

## Forum Channels[​](#forum-channels)

Discord forum channels (type 15) don't accept direct messages — every post in a forum must be a thread. Hermes auto-detects forum channels and creates a new thread post whenever it needs to send there, so send_message, TTS, images, voice messages, and file attachments all work without special handling from the agent.

****************
- Thread name is derived from the first line of the message (markdown heading prefix stripped, capped at 100 chars). When the message is attachment-only, the filename is used as the fallback thread name.

- Attachments ride along on the starter message of the new thread — no separate upload step, no partial sends.

- One call, one thread: each forum send creates a new thread. Successive sends to the same forum will therefore produce separate threads.

- Detection is three-layered: the channel directory cache first, a process-local probe cache second, and a live GET /channels/{id} probe as a last resort (whose result is then memoized for the life of the process).

Refreshing the directory (/channels refresh on platforms that expose it, or a gateway restart) populates the cache with any forum channels created after the bot started.

## Troubleshooting[​](#troubleshooting)

### Bot is online but not responding to messages[​](#bot-is-online-but-not-responding-to-messages)

**Cause**: Message Content Intent is disabled.

**Fix**: Go to [Developer Portal](https://discord.com/developers/applications) → your app → Bot → Privileged Gateway Intents → enable **Message Content Intent** → Save Changes. Restart the gateway.

### "Disallowed Intents" error on startup[​](#disallowed-intents-error-on-startup)

**Cause**: Your code requests intents that aren't enabled in the Developer Portal.

**Fix**: Enable all three Privileged Gateway Intents (Presence, Server Members, Message Content) in the Bot settings, then restart.

### Bot can't see messages in a specific channel[​](#bot-cant-see-messages-in-a-specific-channel)

**Cause**: The bot's role doesn't have permission to view that channel.

**Fix**: In Discord, go to the channel's settings → Permissions → add the bot's role with **View Channel** and **Read Message History** enabled.

### 403 Forbidden errors[​](#403-forbidden-errors)

**Cause**: The bot is missing required permissions.

**Fix**: Re-invite the bot with the correct permissions using the URL from Step 5, or manually adjust the bot's role permissions in Server Settings → Roles.

### Bot is offline[​](#bot-is-offline)

**Cause**: The Hermes gateway isn't running, or the token is incorrect.

**Fix**: Check that hermes gateway is running. Verify DISCORD_BOT_TOKEN in your .env file. If you recently reset the token, update it.

### "User not allowed" / Bot ignores you[​](#user-not-allowed--bot-ignores-you)

**Cause**: Your User ID isn't in DISCORD_ALLOWED_USERS.

**Fix**: Add your User ID to DISCORD_ALLOWED_USERS in ~/.hermes/.env and restart the gateway.

### People in the same channel are sharing context unexpectedly[​](#people-in-the-same-channel-are-sharing-context-unexpectedly)

**Cause**: group_sessions_per_user is disabled, or the platform cannot provide a user ID for the messages in that context.

**Fix**: Set this in ~/.hermes/config.yaml and restart the gateway:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

If you intentionally want a shared room conversation, leave it off — just expect shared transcript history and shared interrupt behavior.

## [[entities/security|Security]][​](#[[entities/security|Security]])

warning

Always set DISCORD_ALLOWED_USERS (or DISCORD_ALLOWED_ROLES) to restrict who can interact with the bot. Without either, the gateway denies all users by default as a safety measure. Only authorize people you trust — authorized users have full access to the agent's capabilities, including tool use and system access.

### Role-Based Access Control[​](#role-based-access-control)

For servers where access is managed by roles instead of individual user lists (moderator teams, support staff, internal tooling), use DISCORD_ALLOWED_ROLES — a comma-separated list of role IDs. Any member with one of those roles is authorized.

```prism-code bash codeBlock_bY9V thin-scrollbar
# ~/.hermes/.env — works alongside or instead of DISCORD_ALLOWED_USERS
DISCORD_ALLOWED_ROLES=987654321098765432,876543210987654321

```

Semantics:

****************************
- OR with user allowlist. A user is authorized if their ID is in DISCORD_ALLOWED_USERS or they have any role in DISCORD_ALLOWED_ROLES.

- Server Members Intent auto-enabled. When DISCORD_ALLOWED_ROLES is set, the bot enables the Members intent on connect — required for Discord to send role information with member records.

- Role IDs, not names. Grab them from Discord: User Settings → Advanced → Developer Mode ON, then right-click any role → Copy Role ID.

- DM fallback. In DMs the role check scans mutual guilds; a user with an allowed role in any shared server is authorized in DMs too.

This is the preferred pattern when the moderation team churns — new moderators get access the moment the role is granted, with no .env edit or gateway restart.

### Mention Control[​](#mention-control)

By default, Hermes blocks the bot from pinging @everyone, @here, and role mentions, even if its reply contains those tokens. This prevents a poorly-worded prompt or echoed user content from spamming a whole server. Individual @user pings and reply-reference pings (the little "replying to…" chip) stay enabled so normal conversation still works.

You can relax these defaults via either env vars or config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
# ~/.hermes/config.yaml
discord:
 allow_mentions:
 everyone: false # allow the bot to ping @everyone / @here
 roles: false # allow the bot to ping @role mentions
 users: true # allow the bot to ping individual @users
 replied_user: true # ping the author when replying to their message

```

```prism-code bash codeBlock_bY9V thin-scrollbar
# ~/.hermes/.env — env vars win over config.yaml
DISCORD_ALLOW_MENTION_EVERYONE=false
DISCORD_ALLOW_MENTION_ROLES=false
DISCORD_ALLOW_MENTION_USERS=true
DISCORD_ALLOW_MENTION_REPLIED_USER=true

```

tip

Leave everyone and roles at false unless you know exactly why you need them. It is very easy for an LLM to produce the string @everyone inside a normal-looking response; without this protection, that would notify every member of your server.

For more information on securing your Hermes Agent deployment, see the [[entities/security|Security]] Guide](/docs/user-guide/[[entities/security|Security]]).
[](#how-hermes-behaves)[](#discord-gateway-model)[](#session-model-in-discord)[](#interrupts-and-concurrency)
- Discord Gateway Model
- Session Model in Discord
- Interrupts and Concurrency
- [Step 1: Create a Discord Application](#step-1-create-a-discord-application)
- [Step 2: Create the Bot](#step-2-create-the-bot)
- [Step 3: Enable Privileged Gateway Intents](#step-3-enable-privileged-gateway-intents)
- [Step 4: Get the Bot Token](#step-4-get-the-bot-token)
- [Step 5: Generate the Invite URL](#step-5-generate-the-invite-url)[](#option-a-using-the-installation-tab-recommended)[](#option-b-manual-url)[](#required-permissions)[](#recommended-additional-permissions)[](#permission-integers)
- Option A: Using the Installation Tab (Recommended)
- Option B: Manual URL
- Required Permissions
- Recommended Additional Permissions
- Permission Integers
- [Step 6: Invite to Your Server](#step-6-invite-to-your-server)
- [Step 7: Find Your Discord User ID](#step-7-find-your-discord-user-id)
- [Step 8: Configure Hermes Agent](#step-8-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)
- Option A: Interactive Setup (Recommended)
- Option B: Manual Configuration
- [Configuration Reference](#configuration-reference)[](#environment-variables-env)[](#config-file-configyaml)
- Environment Variables (.env)
- Config File (config.yaml)
- [Interactive Model Picker](#interactive-model-picker)
- [Native Slash Commands for Skills](#native-slash-commands-for-skills)
- [Home Channel](#home-channel)[](#using-the-slash-command)[](#manual-configuration)
- Using the Slash Command
- Manual Configuration
- [Voice Messages](#voice-messages)
- [Forum Channels](#forum-channels)
- [Troubleshooting](#troubleshooting)[](#bot-is-online-but-not-responding-to-messages)[](#disallowed-intents-error-on-startup)[](#bot-cant-see-messages-in-a-specific-channel)[](#403-forbidden-errors)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)[](#people-in-the-same-channel-are-sharing-context-unexpectedly)
- Bot is online but not responding to messages
- "Disallowed Intents" error on startup
- Bot can't see messages in a specific channel
- 403 Forbidden errors
- Bot is offline
- "User not allowed" / Bot ignores you
- People in the same channel are sharing context unexpectedly
- [[entities/security|Security]]](#[[entities/security|Security]])[](#role-based-access-control)[](#mention-control)
- Role-Based Access Control
- Mention Control