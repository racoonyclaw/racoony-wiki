---
pageType: entity
id: entity.email-setup
title: Email Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/email.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/email.md
updatedAt: '2026-04-24T15:05:25.162964+00:00'
claims:
- id: a-dedicated-email-account-for-your-hermes-agent-dont-use-y
  text: A dedicated email account for your Hermes agent (don't use your personal email)
  status: supported
  confidence: null
- id: imap-enabled-on-the-email-account
  text: IMAP enabled on the email account
  status: supported
  confidence: null
- id: an-app-password-if-using-gmail-or-another-provider-with-2fa
  text: An app password if using Gmail or another provider with 2FA
  status: supported
  confidence: null
- id: imap-host-and-port-usually-port-993-with-ssl
  text: IMAP host and port (usually port 993 with SSL)
  status: supported
  confidence: null
- id: smtp-host-and-port-usually-port-587-with-starttls
  text: SMTP host and port (usually port 587 with STARTTLS)
  status: supported
  confidence: null
- id: whether-app-passwords-are-required
  text: Whether app passwords are required
  status: supported
  confidence: null
- id: images-jpeg-png-gif-webp-available-to-the-vision-tool
  text: "Images (JPEG, PNG, GIF, WebP) \u2192 available to the vision tool"
  status: supported
  confidence: null
- id: documents-pdf-zip-etc-available-for-file-access
  text: "Documents (PDF, ZIP, etc.) \u2192 available for file access"
  status: supported
  confidence: null
- id: html-only-emails-have-tags-stripped-for-plain-text-extract
  text: HTML-only emails** have tags stripped for plain text extraction
  status: supported
  confidence: null
- id: self-messages-are-filtered-out-to-prevent-reply-loops
  text: Self-messages** are filtered out to prevent reply loops
  status: supported
  confidence: null
- id: automatednoreply-senders-are-silently-ignored-noreply
  text: "Automated/noreply senders** are silently ignored \u2014 noreply@, mailer-daemon@,\
    \ bounce@, no-reply@, and emails with Auto-Submitted, Precedence: bulk, or List-Unsubscribe\
    \ headers"
  status: supported
  confidence: null
- id: in-reply-to-and-references-headers-maintain-the-thread
  text: In-Reply-To and References headers maintain the thread
  status: supported
  confidence: null
- id: subject-line-preserved-with-re-prefix-no-double-re-re
  text: 'Subject line preserved with Re: prefix (no double Re: Re:)'
  status: supported
  confidence: null
- id: message-id-generated-with-the-agents-domain
  text: Message-ID generated with the agent's domain
  status: supported
  confidence: null
- id: responses-are-sent-as-plain-text-utf-8
  text: Responses are sent as plain text (UTF-8)
  status: supported
  confidence: null
- id: use-app-passwords-instead-of-your-main-password-required-fo
  text: Use App Passwords instead of your main password (required for Gmail with 2FA)
  status: supported
  confidence: null
- id: set-email-allowed-users-to-restrict-who-can-interact-with-th
  text: Set EMAIL_ALLOWED_USERS to restrict who can interact with the agent
  status: supported
  confidence: null
- id: the-password-is-stored-in-hermesenv-protect-this-file
  text: "The password is stored in ~/.hermes/.env \u2014 protect this file (chmod\
    \ 600)"
  status: supported
  confidence: null
- id: imap-uses-ssl-port-993-and-smtp-uses-starttls-port-587-b
  text: "IMAP uses SSL (port 993) and SMTP uses STARTTLS (port 587) by default \u2014\
    \ connections are encrypted"
  status: supported
  confidence: null
- id: gmail-setup
  text: Gmail Setup
  status: supported
  confidence: null
- id: outlook-microsoft-365
  text: Outlook / Microsoft 365
  status: supported
  confidence: null
- id: other-providers
  text: Other Providers
  status: supported
  confidence: null
- id: step-1-configure-hermesstep-1-configure-hermesmanu
  text: '[Step 1: Configure Hermes](#step-1-configure-hermes)[](#manual-configuration)'
  status: supported
  confidence: null
- id: manual-configuration
  text: Manual Configuration
  status: supported
  confidence: null
- id: step-2-start-the-gatewaystep-2-start-the-gateway
  text: '[Step 2: Start the Gateway](#step-2-start-the-gateway)'
  status: supported
  confidence: null
- id: how-it-workshow-it-worksreceiving-messagessend
  text: '[How It Works](#how-it-works)[](#receiving-messages)[](#sending-replies)[](#file-attachments)[](#skipping-attachments)'
  status: supported
  confidence: null
- id: receiving-messages
  text: Receiving Messages
  status: supported
  confidence: null
- id: sending-replies
  text: Sending Replies
  status: supported
  confidence: null
- id: file-attachments
  text: File Attachments
  status: supported
  confidence: null
- id: skipping-attachments
  text: Skipping Attachments
  status: supported
  confidence: null
- id: access-controlaccess-control
  text: '[Access Control](#access-control)'
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

Hermes can receive and reply to emails using standard IMAP and SMTP protocols. Send an email to the agent's address and it replies in-thread — no special client or bot API needed. Works with Gmail, Outlook, Yahoo, Fastmail, or any provider that supports IMAP/SMTP.

No External Dependencies

The Email adapter uses Python's built-in imaplib, smtplib, and email modules. No additional packages or external services are required.

---

## Prerequisites[​](#prerequisites)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

************
- A dedicated email account for your Hermes agent (don't use your personal email)

- IMAP enabled on the email account

- An app password if using Gmail or another provider with 2FA

### Gmail Setup[​](#gmail-setup)

[](https://myaccount.google.com/apppasswords)
1. Enable 2-Factor Authentication on your Google Account

2. Go to App Passwords

3. Create a new App Password (select "Mail" or "Other")

4. Copy the 16-character password — you'll use this instead of your regular password

### Outlook / Microsoft 365[​](#outlook--microsoft-365)

[](https://account.microsoft.com/security)
1. Go to Security Settings

2. Enable 2FA if not already active

3. Create an App Password under "Additional security options"

4. IMAP host: outlook.office365.com, SMTP host: smtp.office365.com

### Other Providers[​](#other-providers)

Most email providers support IMAP/SMTP. Check your provider's documentation for:

- IMAP host and port (usually port 993 with SSL)

- SMTP host and port (usually port 587 with STARTTLS)

- Whether app passwords are required

---

## Step 1: Configure Hermes[​](#step-1-configure-hermes)

The easiest way:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Select **Email** from the platform menu. The wizard prompts for your email address, password, IMAP/SMTP hosts, and allowed senders.

### Manual Configuration[​](#manual-configuration)

Add to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Required
EMAIL_ADDRESS=hermes@gmail.com
EMAIL_PASSWORD=abcd efgh ijkl mnop # App password (not your regular password)
EMAIL_IMAP_HOST=imap.gmail.com
EMAIL_SMTP_HOST=smtp.gmail.com

# Security (recommended)
EMAIL_ALLOWED_USERS=your@email.com,colleague@work.com

# Optional
EMAIL_IMAP_PORT=993 # Default: 993 (IMAP SSL)
EMAIL_SMTP_PORT=587 # Default: 587 (SMTP STARTTLS)
EMAIL_POLL_INTERVAL=15 # Seconds between inbox checks (default: 15)
EMAIL_HOME_ADDRESS=your@email.com # Default delivery target for cron jobs

```

---

## Step 2: Start the Gateway[​](#step-2-start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway # Run in foreground
hermes gateway install # Install as a user service
sudo hermes gateway install --system # Linux only: boot-time system service

```

On startup, the adapter:

1. Tests IMAP and SMTP connections

2. Marks all existing inbox messages as "seen" (only processes new emails)

3. Starts polling for new messages

---

## How It Works[​](#how-it-works)

### Receiving Messages[​](#receiving-messages)

The adapter polls the IMAP inbox for UNSEEN messages at a configurable interval (default: 15 seconds). For each new email:

************
- Images (JPEG, PNG, GIF, WebP) → available to the vision tool

- Documents (PDF, ZIP, etc.) → available for file access

- **HTML-only emails** have tags stripped for plain text extraction

- **Self-messages** are filtered out to prevent reply loops

- **Automated/noreply senders** are silently ignored — noreply@, mailer-daemon@, bounce@, no-reply@, and emails with Auto-Submitted, Precedence: bulk, or List-Unsubscribe headers

### Sending Replies[​](#sending-replies)

Replies are sent via SMTP with proper email threading:

****************
- In-Reply-To and References headers maintain the thread

- Subject line preserved with Re: prefix (no double Re: Re:)

- Message-ID generated with the agent's domain

- Responses are sent as plain text (UTF-8)

### File Attachments[​](#file-attachments)

The agent can send file attachments in replies. Include MEDIA:/path/to/file in the response and the file is attached to the outgoing email.

### Skipping Attachments[​](#skipping-attachments)

To ignore all incoming attachments (for malware protection or bandwidth savings), add to your config.yaml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 email:
 skip_attachments: true

```

When enabled, attachment and inline parts are skipped before payload decoding. The email body text is still processed normally.

---

## Access Control[​](#access-control)

Email access follows the same pattern as all other Hermes platforms:

************
1. EMAIL_ALLOWED_USERS set → only emails from those addresses are processed

2. No allowlist set → unknown senders get a pairing code

3. EMAIL_ALLOW_ALL_USERS=true → any sender is accepted (use with caution)

warning

**Always configure EMAIL_ALLOWED_USERS.** Without it, anyone who knows the agent's email address could send commands. The agent has terminal access by default.

---

## Troubleshooting[​](#troubleshooting)

****************************

---

## Security[​](#security)

warning

**Use a dedicated email account.** Don't use your personal email — the agent stores the password in .env and has full inbox access via IMAP.

****
- Use App Passwords instead of your main password (required for Gmail with 2FA)

- Set EMAIL_ALLOWED_USERS to restrict who can interact with the agent

- The password is stored in ~/.hermes/.env — protect this file (chmod 600)

- IMAP uses SSL (port 993) and SMTP uses STARTTLS (port 587) by default — connections are encrypted

---

## Environment Variables Reference[​](#environment-variables-reference)

[](#prerequisites)[](#gmail-setup)[](#outlook--microsoft-365)[](#other-providers)
- Gmail Setup
- Outlook / Microsoft 365
- Other Providers
- [Step 1: Configure Hermes](#step-1-configure-hermes)[](#manual-configuration)
- Manual Configuration
- [Step 2: Start the Gateway](#step-2-start-the-gateway)
- [How It Works](#how-it-works)[](#receiving-messages)[](#sending-replies)[](#file-attachments)[](#skipping-attachments)
- Receiving Messages
- Sending Replies
- File Attachments
- Skipping Attachments
- [Access Control](#access-control)
- [Troubleshooting](#troubleshooting)
- [Security](#security)
- [Environment Variables Reference](#environment-variables-reference)