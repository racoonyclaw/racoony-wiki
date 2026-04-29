---
pageType: entity
id: entity.mattermost-setup
title: Mattermost Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/mattermost.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/mattermost.md
updatedAt: '2026-04-24T15:05:25.025511+00:00'
sourceIds:
- your-mattermost-serv
- mmexamplecom
- mattermost-backend
- your-server
sources:
- sourceId: your-mattermost-serv
  sourceType: web
  sourcePath: https://your-mattermost-server/api/v4/users/me
  title: your-mattermost-server
- sourceId: mmexamplecom
  sourceType: web
  sourcePath: https://mm.example.com
  title: mm.example.com
- sourceId: mattermost-backend
  sourceType: web
  sourcePath: http://mattermost-backend;
  title: mattermost-backend;
- sourceId: ''
  sourceType: web
  sourcePath: https://,
  title: ','
- sourceId: your-server
  sourceType: web
  sourcePath: https://your-server/api/v4/users/me
  title: your-server
claims:
- id: each-dm-gets-its-own-session
  text: each DM gets its own session
  status: supported
  confidence: null
- id: each-thread-gets-its-own-session-namespace
  text: each thread gets its own session namespace
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
    same channel
  status: supported
  confidence: null
- id: username-eg-hermes
  text: 'Username: e.g., hermes'
  status: supported
  confidence: null
- id: display-name-eg-hermes-agent
  text: 'Display Name: e.g., Hermes Agent'
  status: supported
  confidence: null
- id: description-optional
  text: 'Description: optional'
  status: supported
  confidence: null
- id: role-member-is-sufficient
  text: 'Role: Member is sufficient'
  status: supported
  confidence: null
- id: click-create-bot-account
  text: Click **Create Bot Account**.
  status: supported
  confidence: null
- id: mattermost-will-display-the-bot-token-copy-it-immedia
  text: Mattermost will display the **bot token**. **Copy it immediately.**
  status: supported
  confidence: null
- id: group-sessions-per-user-true-keeps-each-participants-conte
  text: 'group_sessions_per_user: true keeps each participant''s context isolated
    inside shared channels and threads'
  status: supported
  confidence: null
- id: self-hosted-friendly-works-with-any-self-hosted-mattermost
  text: 'Self-hosted friendly: Works with any self-hosted Mattermost instance. No
    Mattermost Cloud account or subscription required.'
  status: supported
  confidence: null
- id: no-extra-dependencies-the-adapter-uses-aiohttp-for-http-and
  text: 'No extra dependencies: The adapter uses aiohttp for HTTP and WebSocket, which
    is already included with Hermes Agent.'
  status: supported
  confidence: null
- id: team-edition-compatible-works-with-both-mattermost-team-edi
  text: 'Team Edition compatible: Works with both Mattermost Team Edition (free) and
    Enterprise Edition.'
  status: supported
  confidence: null
- id: session-model-in-mattermost
  text: Session Model in Mattermost
  status: supported
  confidence: null
- id: step-1-enable-bot-accountsstep-1-enable-bot-accounts
  text: '[Step 1: Enable Bot Accounts](#step-1-enable-bot-accounts)'
  status: supported
  confidence: null
- id: step-2-create-a-bot-accountstep-2-create-a-bot-account
  text: '[Step 2: Create a Bot Account](#step-2-create-a-bot-account)'
  status: supported
  confidence: null
- id: step-3-add-the-bot-to-channelsstep-3-add-the-bot-to-cha
  text: '[Step 3: Add the Bot to Channels](#step-3-add-the-bot-to-channels)'
  status: supported
  confidence: null
- id: step-4-find-your-mattermost-user-idstep-4-find-your-mat
  text: '[Step 4: Find Your Mattermost User ID](#step-4-find-your-mattermost-user-id)'
  status: supported
  confidence: null
- id: step-5-configure-hermes-agentstep-5-configure-hermes-ag
  text: '[Step 5: Configure Hermes Agent](#step-5-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)'
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
- id: reply-modereply-mode
  text: '[Reply Mode](#reply-mode)'
  status: supported
  confidence: null
- id: mention-behaviormention-behavior
  text: '[Mention Behavior](#mention-behavior)'
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingbot-is-not-responding
  text: '[Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#403-forbidden-errors)[](#websocket-disconnects--reconnection-loops)[](#failed-to-authenticate-on-startup)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)'
  status: supported
  confidence: null
- id: bot-is-not-responding-to-messages
  text: Bot is not responding to messages
  status: supported
  confidence: null
- id: 403-forbidden-errors
  text: 403 Forbidden errors
  status: supported
  confidence: null
- id: websocket-disconnects-reconnection-loops
  text: WebSocket disconnects / reconnection loops
  status: supported
  confidence: null
- id: failed-to-authenticate-on-startup
  text: '"Failed to authenticate" on startup'
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
- id: per-channel-promptsper-channel-prompts
  text: '[Per-Channel Prompts](#per-channel-prompts)'
  status: supported
  confidence: null
- id: securitysecurity
  text: '[Security](#security)'
  status: supported
  confidence: null
- id: notesnotes
  text: '[Notes](#notes)'
  status: supported
  confidence: null
---

On this page

Hermes Agent integrates with Mattermost as a bot, letting you chat with your AI assistant through direct messages or team channels. Mattermost is a self-hosted, open-source Slack alternative — you run it on your own infrastructure, keeping full control of your data. The bot connects via Mattermost's REST API (v4) and WebSocket for real-time events, processes messages through the Hermes Agent pipeline (including tool use, memory, and reasoning), and responds in real time. It supports text, file attachments, images, and slash commands.

No external Mattermost library is required — the adapter uses aiohttp, which is already a Hermes dependency.

Before setup, here's the part most people want to know: how Hermes behaves once it's in your Mattermost instance.

## How Hermes Behaves[​](#how-hermes-behaves)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]

### Related Pages
- [[entities/matrix-setup|Matrix Setup]]
<!-- openclaw:wiki:related:end -->

****************
tip

If you want Hermes to reply as threaded conversations (nested under your original message), set MATTERMOST_REPLY_MODE=thread. The default is off, which sends flat messages in the channel.

### Session Model in Mattermost[​](#session-model-in-mattermost)

By default:

- each DM gets its own session

- each thread gets its own session namespace

- each user in a shared channel gets their own session inside that channel

This is controlled by config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

Set it to false only if you explicitly want one shared conversation for the entire channel:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: false

```

Shared sessions can be useful for a collaborative channel, but they also mean:

- users share context growth and token costs

- one person's long tool-heavy task can bloat everyone else's context

- one person's in-flight run can interrupt another person's follow-up in the same channel

This guide walks you through the full setup process — from creating your bot on Mattermost to sending your first message.

## Step 1: Enable Bot Accounts[​](#step-1-enable-bot-accounts)

Bot accounts must be enabled on your Mattermost server before you can create one.

****************************
1. Log in to Mattermost as a System Admin.

2. Go to System Console → Integrations → Bot Accounts.

3. Set Enable Bot Account Creation to true.

4. Click Save.

info

If you don't have System Admin access, ask your Mattermost administrator to enable bot accounts and create one for you.

## Step 2: Create a Bot Account[​](#step-2-create-a-bot-account)

********************************
- Username: e.g., hermes

- Display Name: e.g., Hermes Agent

- Description: optional

- Role: Member is sufficient

- Click **Create Bot Account**.

- Mattermost will display the **bot token**. **Copy it immediately.**

Token shown only once

The bot token is only displayed once when you create the bot account. If you lose it, you'll need to regenerate it from the bot account settings. Never share your token publicly or commit it to Git — anyone with this token has full control of the bot.

Store the token somewhere safe (a password manager, for example). You'll need it in Step 5.

tip

You can also use a **personal access token** instead of a bot account. Go to **Profile** → **Security** → **Personal Access Tokens** → **Create Token**. This is useful if you want Hermes to post as your own user rather than a separate bot user.

## Step 3: Add the Bot to Channels[​](#step-3-add-the-bot-to-channels)

The bot needs to be a member of any channel where you want it to respond:

****
1. Open the channel where you want the bot.

2. Click the channel name → Add Members.

3. Search for your bot username (e.g., hermes) and add it.

For DMs, simply open a direct message with the bot — it will be able to respond immediately.

## Step 4: Find Your Mattermost User ID[​](#step-4-find-your-mattermost-user-id)

Hermes Agent uses your Mattermost User ID to control who can interact with the bot. To find it:

********
1. Click your avatar (top-left corner) → Profile.

2. Your User ID is displayed in the profile dialog — click it to copy.

Your User ID is a 26-character alphanumeric string like 3uo8dkh1p7g1mfk49ear5fzs5c.

warning

Your User ID is **not** your username. The username is what appears after @ (e.g., @alice). The User ID is a long alphanumeric identifier that Mattermost uses internally.

**Alternative**: You can also get your User ID via the API:

```prism-code bash codeBlock_bY9V thin-scrollbar
curl -H "Authorization: Bearer YOUR_TOKEN" \
 https://your-mattermost-server/api/v4/users/me | jq .id

```

tip

To get a **Channel ID**: click the channel name → **View Info**. The Channel ID is shown in the info panel. You'll need this if you want to set a home channel manually.

## Step 5: Configure Hermes Agent[​](#step-5-configure-hermes-agent)

### Option A: Interactive Setup (Recommended)[​](#option-a-interactive-setup-recommended)

Run the guided setup command:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Mattermost** when prompted, then paste your server URL, bot token, and user ID when asked.

### Option B: Manual Configuration[​](#option-b-manual-configuration)

Add the following to your ~/.hermes/.env file:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Required
MATTERMOST_URL=https://mm.example.com
MATTERMOST_TOKEN=***
MATTERMOST_ALLOWED_USERS=3uo8dkh1p7g1mfk49ear5fzs5c

# Multiple allowed users (comma-separated)
# MATTERMOST_ALLOWED_USERS=3uo8dkh1p7g1mfk49ear5fzs5c,8fk2jd9s0a7bncm1xqw4tp6r3e

# Optional: reply mode (thread or off, default: off)
# MATTERMOST_REPLY_MODE=thread

# Optional: respond without @mention (default: true = require mention)
# MATTERMOST_REQUIRE_MENTION=false

# Optional: channels where bot responds without @mention (comma-separated channel IDs)
# MATTERMOST_FREE_RESPONSE_CHANNELS=channel_id_1,channel_id_2

```

Optional behavior settings in ~/.hermes/config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
group_sessions_per_user: true

```

- group_sessions_per_user: true keeps each participant's context isolated inside shared channels and threads

### Start the Gateway[​](#start-the-gateway)

Once configured, start the Mattermost gateway:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

The bot should connect to your Mattermost server within a few seconds. Send it a message — either a DM or in a channel where it's been added — to test.

tip

You can run hermes gateway in the background or as a systemd service for persistent operation. See the deployment docs for details.

## Home Channel[​](#home-channel)

You can designate a "home channel" where the bot sends proactive messages (such as cron job output, reminders, and notifications). There are two ways to set it:

### Using the Slash Command[​](#using-the-slash-command)

Type /sethome in any Mattermost channel where the bot is present. That channel becomes the home channel.

### Manual Configuration[​](#manual-configuration)

Add this to your ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
MATTERMOST_HOME_CHANNEL=abc123def456ghi789jkl012mn

```

Replace the ID with the actual channel ID (click the channel name → View Info → copy the ID).

## Reply Mode[​](#reply-mode)

The MATTERMOST_REPLY_MODE setting controls how Hermes posts responses:

Set it in your ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
MATTERMOST_REPLY_MODE=thread

```

## Mention Behavior[​](#mention-behavior)

By default, the bot only responds in channels when @mentioned. You can change this:

**

To find a channel ID in Mattermost: open the channel, click the channel name header, and look for the ID in the URL or channel details.

When the bot is @mentioned, the mention is automatically stripped from the message before processing.

## Troubleshooting[​](#troubleshooting)

### Bot is not responding to messages[​](#bot-is-not-responding-to-messages)

**Cause**: The bot is not a member of the channel, or MATTERMOST_ALLOWED_USERS doesn't include your User ID.

**Fix**: Add the bot to the channel (channel name → Add Members → search for the bot). Verify your User ID is in MATTERMOST_ALLOWED_USERS. Restart the gateway.

### 403 Forbidden errors[​](#403-forbidden-errors)

**Cause**: The bot token is invalid, or the bot doesn't have permission to post in the channel.

**Fix**: Check that MATTERMOST_TOKEN in your .env file is correct. Make sure the bot account hasn't been deactivated. Verify the bot has been added to the channel. If using a personal access token, ensure your account has the required permissions.

### WebSocket disconnects / reconnection loops[​](#websocket-disconnects--reconnection-loops)

**Cause**: Network instability, Mattermost server restarts, or firewall/proxy issues with WebSocket connections.

**Fix**: The adapter automatically reconnects with exponential backoff (2s → 60s). Check your server's WebSocket configuration — reverse proxies (nginx, Apache) need WebSocket upgrade headers configured. Verify no firewall is blocking WebSocket connections on your Mattermost server.

For nginx, ensure your config includes:

```prism-code nginx codeBlock_bY9V thin-scrollbar
location /api/v4/websocket {
 proxy_pass http://mattermost-backend;
 proxy_set_header Upgrade $http_upgrade;
 proxy_set_header Connection "upgrade";
 proxy_read_timeout 600s;
}

```

### "Failed to authenticate" on startup[​](#failed-to-authenticate-on-startup)

**Cause**: The token or server URL is incorrect.

**Fix**: Verify MATTERMOST_URL points to your Mattermost server (include https://, no trailing slash). Check that MATTERMOST_TOKEN is valid — try it with curl:

```prism-code bash codeBlock_bY9V thin-scrollbar
curl -H "Authorization: Bearer YOUR_TOKEN" \
 https://your-server/api/v4/users/me

```

If this returns your bot's user info, the token is valid. If it returns an error, regenerate the token.

### Bot is offline[​](#bot-is-offline)

**Cause**: The Hermes gateway isn't running, or it failed to connect.

**Fix**: Check that hermes gateway is running. Look at the terminal output for error messages. Common issues: wrong URL, expired token, Mattermost server unreachable.

### "User not allowed" / Bot ignores you[​](#user-not-allowed--bot-ignores-you)

**Cause**: Your User ID isn't in MATTERMOST_ALLOWED_USERS.

**Fix**: Add your User ID to MATTERMOST_ALLOWED_USERS in ~/.hermes/.env and restart the gateway. Remember: the User ID is a 26-character alphanumeric string, not your @username.

## Per-Channel Prompts[​](#per-channel-prompts)

Assign ephemeral system prompts to specific Mattermost channels. The prompt is injected at runtime on every turn — never persisted to transcript history — so changes take effect immediately.

```prism-code yaml codeBlock_bY9V thin-scrollbar
mattermost:
 channel_prompts:
 "channel_id_abc123": |
 You are a research assistant. Focus on academic sources,
 citations, and concise synthesis.
 "channel_id_def456": |
 Code review mode. Be precise about edge cases and
 performance implications.

```

Keys are Mattermost channel IDs (find them in the channel URL or via the API). All messages in the matching channel get the prompt injected as an ephemeral system instruction.

## Security[​](#security)

warning

Always set MATTERMOST_ALLOWED_USERS to restrict who can interact with the bot. Without it, the gateway denies all users by default as a safety measure. Only add User IDs of people you trust — authorized users have full access to the agent's capabilities, including tool use and system access.

For more information on securing your Hermes Agent deployment, see the [Security Guide](/docs/user-guide/security).

## Notes[​](#notes)

************
- Self-hosted friendly: Works with any self-hosted Mattermost instance. No Mattermost Cloud account or subscription required.

- No extra dependencies: The adapter uses aiohttp for HTTP and WebSocket, which is already included with Hermes Agent.

- Team Edition compatible: Works with both Mattermost Team Edition (free) and Enterprise Edition.
[](#how-hermes-behaves)[](#session-model-in-mattermost)
- Session Model in Mattermost
- [Step 1: Enable Bot Accounts](#step-1-enable-bot-accounts)
- [Step 2: Create a Bot Account](#step-2-create-a-bot-account)
- [Step 3: Add the Bot to Channels](#step-3-add-the-bot-to-channels)
- [Step 4: Find Your Mattermost User ID](#step-4-find-your-mattermost-user-id)
- [Step 5: Configure Hermes Agent](#step-5-configure-hermes-agent)[](#option-a-interactive-setup-recommended)[](#option-b-manual-configuration)[](#start-the-gateway)
- Option A: Interactive Setup (Recommended)
- Option B: Manual Configuration
- Start the Gateway
- [Home Channel](#home-channel)[](#using-the-slash-command)[](#manual-configuration)
- Using the Slash Command
- Manual Configuration
- [Reply Mode](#reply-mode)
- [Mention Behavior](#mention-behavior)
- [Troubleshooting](#troubleshooting)[](#bot-is-not-responding-to-messages)[](#403-forbidden-errors)[](#websocket-disconnects--reconnection-loops)[](#failed-to-authenticate-on-startup)[](#bot-is-offline)[](#user-not-allowed--bot-ignores-you)
- Bot is not responding to messages
- 403 Forbidden errors
- WebSocket disconnects / reconnection loops
- "Failed to authenticate" on startup
- Bot is offline
- "User not allowed" / Bot ignores you
- [Per-Channel Prompts](#per-channel-prompts)
- [Security](#security)
- [Notes](#notes)