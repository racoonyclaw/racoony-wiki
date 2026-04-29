---
pageType: entity
id: entity.sms-setup-twilio
title: SMS Setup (Twilio)
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/sms.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/sms.md
updatedAt: '2026-04-24T15:05:25.124561+00:00'
sourceIds:
- wwwtwiliocom
- consoletwiliocom
- your-server8080
sources:
- sourceId: wwwtwiliocom
  sourceType: web
  sourcePath: https://www.twilio.com/
  title: '[Twilio](https://www.twilio.com/)'
- sourceId: consoletwiliocom
  sourceType: web
  sourcePath: https://console.twilio.com/
  title: '[Twilio Console](https://console.twilio.com/)'
- sourceId: your-server8080
  sourceType: web
  sourcePath: https://your-server:8080/webhooks/twilio
  title: your-server:8080
claims:
- id: twilio-account-sign-up-at-twiliocom-free-trial-available
  text: "Twilio account \u2014 Sign up at twilio.com (free trial available)"
  status: supported
  confidence: null
- id: a-twilio-phone-number-with-sms-capability
  text: A Twilio phone number with SMS capability
  status: supported
  confidence: null
- id: a-publicly-accessible-server-twilio-sends-webhooks-to-your
  text: "A publicly accessible server \u2014 Twilio sends webhooks to your server\
    \ when SMS arrives"
  status: supported
  confidence: null
- id: aiohttp-pip-install-hermes-agentsms
  text: "aiohttp \u2014 pip install 'hermes-agent[sms]'"
  status: supported
  confidence: null
- id: webhook-httpsyour-server8080webhookstwilio
  text: 'Webhook: https://your-server:8080/webhooks/twilio'
  status: supported
  confidence: null
- id: http-method-post
  text: 'HTTP Method: POST'
  status: supported
  confidence: null
- id: plain-text-only-markdown-is-automatically-stripped-since-s
  text: "Plain text only \u2014 Markdown is automatically stripped since SMS renders\
    \ it as literal characters"
  status: supported
  confidence: null
- id: 1600-character-limit-longer-responses-are-split-across-mul
  text: "1600 character limit \u2014 Longer responses are split across multiple messages\
    \ at natural boundaries (newlines, then spaces)"
  status: supported
  confidence: null
- id: echo-prevention-messages-from-your-own-twilio-number-are-i
  text: "Echo prevention \u2014 Messages from your own Twilio number are ignored to\
    \ prevent loops"
  status: supported
  confidence: null
- id: phone-number-redaction-phone-numbers-are-redacted-in-logs
  text: "Phone number redaction \u2014 Phone numbers are redacted in logs for privacy"
  status: supported
  confidence: null
- id: interactive-setup-recommended
  text: Interactive setup (recommended)
  status: supported
  confidence: null
- id: manual-setup
  text: Manual setup
  status: supported
  confidence: null
- id: step-3-configure-twilio-webhookstep-3-configure-twilio
  text: '[Step 3: Configure Twilio Webhook](#step-3-configure-twilio-webhook)'
  status: supported
  confidence: null
- id: step-4-start-the-gatewaystep-4-start-the-gateway
  text: '[Step 4: Start the Gateway](#step-4-start-the-gateway)'
  status: supported
  confidence: null
- id: environment-variablesenvironment-variables
  text: '[Environment Variables](#environment-variables)'
  status: supported
  confidence: null
- id: sms-specific-behaviorsms-specific-behavior
  text: '[SMS-Specific Behavior](#sms-specific-behavior)'
  status: supported
  confidence: null
- id: securitysecuritywebhook-signature-validationus
  text: '[Security](#security)[](#webhook-signature-validation)[](#user-allowlists)'
  status: supported
  confidence: null
- id: webhook-signature-validation
  text: Webhook signature validation
  status: supported
  confidence: null
- id: user-allowlists
  text: User allowlists
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingmessages-not-arriving
  text: '[Troubleshooting](#troubleshooting)[](#messages-not-arriving)[](#replies-not-sending)[](#webhook-port-conflicts)'
  status: supported
  confidence: null
- id: messages-not-arriving
  text: Messages not arriving
  status: supported
  confidence: null
- id: replies-not-sending
  text: Replies not sending
  status: supported
  confidence: null
- id: webhook-port-conflicts
  text: Webhook port conflicts
  status: supported
  confidence: null
---

On this page

Hermes connects to SMS through the [Twilio](https://www.twilio.com/) API. People text your Twilio phone number and get AI responses back — same conversational experience as Telegram or Discord, but over standard text messages.

Shared Credentials

The SMS gateway shares credentials with the optional [telephony skill](/docs/reference/skills-catalog). If you've already set up Twilio for voice calls or one-off SMS, the gateway works with the same TWILIO_ACCOUNT_SID, TWILIO_AUTH_TOKEN, and TWILIO_PHONE_NUMBER.

---

## Prerequisites[​](#prerequisites)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

****[](https://www.twilio.com/try-twilio)************
- Twilio account — Sign up at twilio.com (free trial available)

- A Twilio phone number with SMS capability

- A publicly accessible server — Twilio sends webhooks to your server when SMS arrives

- aiohttp — pip install 'hermes-agent[sms]'

---

## Step 1: Get Your Twilio Credentials[​](#step-1-get-your-twilio-credentials)

[](https://console.twilio.com/)************
1. Go to the Twilio Console

2. Copy your Account SID and Auth Token from the dashboard

3. Go to Phone Numbers → Manage → Active Numbers — note your phone number in E.164 format (e.g., +15551234567)

---

## Step 2: Configure Hermes[​](#step-2-configure-hermes)

### Interactive setup (recommended)[​](#interactive-setup-recommended)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **SMS (Twilio)** from the platform list. The wizard will prompt for your credentials.

### Manual setup[​](#manual-setup)

Add to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
TWILIO_ACCOUNT_SID=ACxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_AUTH_TOKEN=your_auth_token_here
TWILIO_PHONE_NUMBER=+15551234567

# Security: restrict to specific phone numbers (recommended)
SMS_ALLOWED_USERS=+15559876543,+15551112222

# Optional: set a home channel for cron job delivery
SMS_HOME_CHANNEL=+15559876543

```

---

## Step 3: Configure Twilio Webhook[​](#step-3-configure-twilio-webhook)

Twilio needs to know where to send incoming messages. In the [Twilio Console](https://console.twilio.com/):

****************
- Webhook: https://your-server:8080/webhooks/twilio

- HTTP Method: POST

Exposing Your Webhook

If you're running Hermes locally, use a tunnel to expose the webhook:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Using cloudflared
cloudflared tunnel --url http://localhost:8080

# Using ngrok
ngrok http 8080

```

Set the resulting public URL as your Twilio webhook.

**Set SMS_WEBHOOK_URL to the same URL you configured in Twilio.** This is required for Twilio signature validation — the adapter will refuse to start without it:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Must match the webhook URL in your Twilio Console
SMS_WEBHOOK_URL=https://your-server:8080/webhooks/twilio

```

The webhook port defaults to 8080. Override with:

```prism-code bash codeBlock_bY9V thin-scrollbar
SMS_WEBHOOK_PORT=3000

```

---

## Step 4: Start the Gateway[​](#step-4-start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

You should see:

```prism-code text codeBlock_bY9V thin-scrollbar
[sms] Twilio webhook server listening on 0.0.0.0:8080, from: +1555***4567

```

If you see Refusing to start: SMS_WEBHOOK_URL is required, set SMS_WEBHOOK_URL to the public URL configured in your Twilio Console (see Step 3).

Text your Twilio number — Hermes will respond via SMS.

---

## Environment Variables[​](#environment-variables)

****

---

## SMS-Specific Behavior[​](#sms-specific-behavior)

****************
- Plain text only — Markdown is automatically stripped since SMS renders it as literal characters

- 1600 character limit — Longer responses are split across multiple messages at natural boundaries (newlines, then spaces)

- Echo prevention — Messages from your own Twilio number are ignored to prevent loops

- Phone number redaction — Phone numbers are redacted in logs for privacy

---

## Security[​](#security)

### Webhook signature validation[​](#webhook-signature-validation)

Hermes validates that inbound webhooks genuinely originate from Twilio by verifying the X-Twilio-Signature header (HMAC-SHA1). This prevents attackers from injecting forged messages.

**SMS_WEBHOOK_URL is required.** Set it to the public URL configured in your Twilio Console. The adapter will refuse to start without it.

For local development without a public URL, you can disable validation:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Local dev only — NOT for production
SMS_INSECURE_NO_SIGNATURE=true

```

### User allowlists[​](#user-allowlists)

**The gateway denies all users by default.** Configure an allowlist:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Recommended: restrict to specific phone numbers
SMS_ALLOWED_USERS=+15559876543,+15551112222

# Or allow all (NOT recommended for bots with terminal access)
SMS_ALLOW_ALL_USERS=true

```

warning

SMS has no built-in encryption. Don't use SMS for sensitive operations unless you understand the security implications. For sensitive use cases, prefer Signal or Telegram.

---

## Troubleshooting[​](#troubleshooting)

### Messages not arriving[​](#messages-not-arriving)

****
1. Check your Twilio webhook URL is correct and publicly accessible

2. Verify TWILIO_ACCOUNT_SID and TWILIO_AUTH_TOKEN are correct

3. Check the Twilio Console → Monitor → Logs → Messaging for delivery errors

4. Ensure your phone number is in SMS_ALLOWED_USERS (or SMS_ALLOW_ALL_USERS=true)

### Replies not sending[​](#replies-not-sending)

1. Check TWILIO_PHONE_NUMBER is set correctly (E.164 format with +)

2. Verify your Twilio account has SMS-capable numbers

3. Check Hermes gateway logs for Twilio API errors

### Webhook port conflicts[​](#webhook-port-conflicts)

If port 8080 is already in use, change it:

```prism-code bash codeBlock_bY9V thin-scrollbar
SMS_WEBHOOK_PORT=3001

```

Update the webhook URL in Twilio Console to match.
[](#prerequisites)[](#step-1-get-your-twilio-credentials)[](#step-2-configure-hermes)[](#interactive-setup-recommended)[](#manual-setup)
- Interactive setup (recommended)
- Manual setup
- [Step 3: Configure Twilio Webhook](#step-3-configure-twilio-webhook)
- [Step 4: Start the Gateway](#step-4-start-the-gateway)
- [Environment Variables](#environment-variables)
- [SMS-Specific Behavior](#sms-specific-behavior)
- [Security](#security)[](#webhook-signature-validation)[](#user-allowlists)
- Webhook signature validation
- User allowlists
- [Troubleshooting](#troubleshooting)[](#messages-not-arriving)[](#replies-not-sending)[](#webhook-port-conflicts)
- Messages not arriving
- Replies not sending
- Webhook port conflicts