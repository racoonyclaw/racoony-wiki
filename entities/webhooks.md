---
pageType: entity
id: entity.webhooks
title: Webhooks
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/webhooks.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/webhooks.md
updatedAt: '2026-04-24T15:05:24.570412+00:00'
sourceIds:
- your-server8644
- your-server8644
- your-server8644
- your-server8644
sources:
- sourceId: your-server8644
  sourceType: web
  sourcePath: http://your-server:8644/webhooks/<route-name>
  title: your-server:8644
- sourceId: your-server8644
  sourceType: web
  sourcePath: http://your-server:8644/webhooks/github-pr
  title: your-server:8644
- sourceId: your-server8644
  sourceType: web
  sourcePath: http://your-server:8644/webhooks/gitlab-mr
  title: your-server:8644
- sourceId: your-server8644
  sourceType: web
  sourcePath: https://your-server:8644/webhooks/antenna-matches.
  title: your-server:8644
claims:
- id: pull-requesttitle-resolves-to-payloadpull-requestti
  text: '{pull_request.title} resolves to payload["pull_request"]["title"]'
  status: supported
  confidence: null
- id: repositoryfull-name-resolves-to-payloadrepositoryfu
  text: '{repository.full_name} resolves to payload["repository"]["full_name"]'
  status: supported
  confidence: null
- id: raw-special-token-that-dumps-the-entire-payload-as-i
  text: "{__raw__} \u2014 special token that dumps the entire payload as indented\
    \ JSON (truncated at 4000 characters). Useful for monitoring alerts or generic\
    \ webhooks where the agent needs the full context."
  status: supported
  confidence: null
- id: missing-keys-are-left-as-the-literal-key-string-no-error
  text: Missing keys are left as the literal {key} string (no error)
  status: supported
  confidence: null
- id: nested-dicts-and-lists-are-json-serialized-and-truncated-at
  text: Nested dicts and lists are JSON-serialized and truncated at 2000 characters
  status: supported
  confidence: null
- id: external-service-push-supabasefirebase-webhook-fires-on-a
  text: "External service push \u2014 Supabase/Firebase webhook fires on a database\
    \ change \u2192 notify a user in Telegram instantly"
  status: supported
  confidence: null
- id: monitoring-alerts-datadoggrafana-alert-webhook-push-to
  text: "Monitoring alerts \u2014 Datadog/Grafana alert webhook \u2192 push to a Discord\
    \ channel"
  status: supported
  confidence: null
- id: inter-agent-pings-agent-a-notifies-agent-bs-user-that-a-l
  text: "Inter-agent pings \u2014 Agent A notifies Agent B's user that a long-running\
    \ task finished"
  status: supported
  confidence: null
- id: background-job-completion-cron-job-finishes-post-result
  text: "Background job completion \u2014 Cron job finishes \u2192 post result to\
    \ Slack"
  status: supported
  confidence: null
- id: zero-llm-tokens-the-agent-is-never-invoked
  text: "Zero LLM tokens \u2014 the agent is never invoked"
  status: supported
  confidence: null
- id: sub-second-delivery-a-single-adapter-call-no-reasoning-lo
  text: "Sub-second delivery \u2014 a single adapter call, no reasoning loop"
  status: supported
  confidence: null
- id: same-security-as-agent-mode-hmac-auth-rate-limits-idempo
  text: "Same security as agent mode \u2014 HMAC auth, rate limits, idempotency, and\
    \ body-size limits all still apply"
  status: supported
  confidence: null
- id: synchronous-response-the-post-returns-200-ok-once-delivery
  text: "Synchronous response \u2014 the POST returns 200 OK once delivery succeeds,\
    \ or 502 if the target rejects it, so your upstream service can retry intelligently"
  status: supported
  confidence: null
- id: deliver-telegram
  text: deliver telegram \
  status: supported
  confidence: null
- id: deliver-chat-id-123456789
  text: deliver-chat-id "123456789" \
  status: supported
  confidence: null
- id: deliver-only
  text: deliver-only \
  status: supported
  confidence: null
- id: prompt-new-match-matchuser-name-matched-with-you
  text: "prompt \"\U0001F389 New match: {match.user_name} matched with you!\" \\"
  status: supported
  confidence: null
- id: description-antenna-match-notifications
  text: description "Antenna match notifications"
  status: supported
  confidence: null
- id: deliver-only-true-requires-deliver-to-be-a-real-target-del
  text: "deliver_only: true requires deliver to be a real target. deliver: log (or\
    \ omitting deliver) is rejected at startup \u2014 the adapter refuses to start\
    \ if it finds a misconfigured route."
  status: supported
  confidence: null
- id: the-skills-field-is-ignored-in-direct-delivery-mode-no-agen
  text: The skills field is ignored in direct delivery mode (no agent runs, so there's
    nothing to inject skills into).
  status: supported
  confidence: null
- id: template-rendering-uses-the-same-dotnotation-syntax-as-ag
  text: Template rendering uses the same {dot.notation} syntax as agent mode, including
    the {__raw__} token.
  status: supported
  confidence: null
- id: idempotency-uses-the-same-x-github-delivery-x-request-id-h
  text: "Idempotency uses the same X-GitHub-Delivery / X-Request-ID header \u2014\
    \ retries with the same ID return status=duplicate and do NOT re-deliver."
  status: supported
  confidence: null
- id: events-issues
  text: events "issues" \
  status: supported
  confidence: null
- id: prompt-new-issue-issuenumber-issuetitlenby-issue
  text: 'prompt "New issue #{issue.number}: {issue.title}\nBy: {issue.user.login}\n\n{issue.body}"
    \'
  status: supported
  confidence: null
- id: deliver-telegram
  text: deliver telegram \
  status: supported
  confidence: null
- id: deliver-chat-id--100123456789
  text: deliver-chat-id "-100123456789" \
  status: supported
  confidence: null
- id: description-triage-new-github-issues
  text: description "Triage new GitHub issues"
  status: supported
  confidence: null
- id: subscriptions-are-stored-in-hermeswebhook-subscriptions
  text: Subscriptions are stored in ~/.hermes/webhook_subscriptions.json
  status: supported
  confidence: null
- id: the-webhook-adapter-hot-reloads-this-file-on-each-incoming-r
  text: The webhook adapter hot-reloads this file on each incoming request (mtime-gated,
    negligible overhead)
  status: supported
  confidence: null
- id: static-routes-from-configyaml-always-take-precedence-over-d
  text: Static routes from config.yaml always take precedence over dynamic ones with
    the same name
  status: supported
  confidence: null
- id: dynamic-subscriptions-use-the-same-route-format-and-capabili
  text: Dynamic subscriptions use the same route format and capabilities as static
    routes (events, prompt templates, skills, delivery)
  status: supported
  confidence: null
- id: no-gateway-restart-required-subscribe-and-its-immediately
  text: "No gateway restart required \u2014 subscribe and it's immediately live"
  status: supported
  confidence: null
- id: github-x-hub-signature-256-header-hmac-sha256-hex-digest
  text: "GitHub: X-Hub-Signature-256 header \u2014 HMAC-SHA256 hex digest prefixed\
    \ with sha256="
  status: supported
  confidence: null
- id: gitlab-x-gitlab-token-header-plain-secret-string-match
  text: "GitLab: X-Gitlab-Token header \u2014 plain secret string match"
  status: supported
  confidence: null
- id: generic-x-webhook-signature-header-raw-hmac-sha256-hex-di
  text: "Generic: X-Webhook-Signature header \u2014 raw HMAC-SHA256 hex digest"
  status: supported
  confidence: null
- id: verify-the-port-is-exposed-and-accessible-from-the-webhook-s
  text: Verify the port is exposed and accessible from the webhook source
  status: supported
  confidence: null
- id: check-firewall-rules-port-8644-or-your-configured-port-m
  text: "Check firewall rules \u2014 port 8644 (or your configured port) must be open"
  status: supported
  confidence: null
- id: verify-the-url-path-matches-httpyour-server8644webhook
  text: 'Verify the URL path matches: http://your-server:8644/webhooks/<route-name>'
  status: supported
  confidence: null
- id: use-the-health-endpoint-to-confirm-the-server-is-running
  text: Use the /health endpoint to confirm the server is running
  status: supported
  confidence: null
- id: ensure-the-secret-in-your-route-config-exactly-matches-the-s
  text: Ensure the secret in your route config exactly matches the secret configured
    in the webhook source
  status: supported
  confidence: null
- id: for-github-the-secret-is-hmac-based-check-x-hub-signature
  text: "For GitHub, the secret is HMAC-based \u2014 check X-Hub-Signature-256"
  status: supported
  confidence: null
- id: for-gitlab-the-secret-is-a-plain-token-match-check-x-gitl
  text: "For GitLab, the secret is a plain token match \u2014 check X-Gitlab-Token"
  status: supported
  confidence: null
- id: check-gateway-logs-for-invalid-signature-warnings
  text: Check gateway logs for Invalid signature warnings
  status: supported
  confidence: null
- id: check-that-the-event-type-is-in-your-routes-events-list
  text: Check that the event type is in your route's events list
  status: supported
  confidence: null
- id: github-events-use-values-like-pull-request-push-issues-th
  text: GitHub events use values like pull_request, push, issues (the X-GitHub-Event
    header value)
  status: supported
  confidence: null
- id: gitlab-events-use-values-like-merge-request-push-the-x-git
  text: GitLab events use values like merge_request, push (the X-GitLab-Event header
    value)
  status: supported
  confidence: null
- id: if-events-is-empty-or-not-set-all-events-are-accepted
  text: If events is empty or not set, all events are accepted
  status: supported
  confidence: null
- id: run-the-gateway-in-foreground-to-see-logs-hermes-gateway-ru
  text: 'Run the gateway in foreground to see logs: hermes gateway run'
  status: supported
  confidence: null
- id: check-that-the-prompt-template-is-rendering-correctly
  text: Check that the prompt template is rendering correctly
  status: supported
  confidence: null
- id: verify-the-delivery-target-is-configured-and-connected
  text: Verify the delivery target is configured and connected
  status: supported
  confidence: null
- id: the-idempotency-cache-should-prevent-this-check-that-the-w
  text: "The idempotency cache should prevent this \u2014 check that the webhook source\
    \ is sending a delivery ID header (X-GitHub-Delivery or X-Request-ID)"
  status: supported
  confidence: null
- id: delivery-ids-are-cached-for-1-hour
  text: Delivery IDs are cached for 1 hour
  status: supported
  confidence: null
- id: run-gh-auth-login-on-the-gateway-host
  text: Run gh auth login on the gateway host
  status: supported
  confidence: null
- id: ensure-the-authenticated-github-user-has-write-access-to-the
  text: Ensure the authenticated GitHub user has write access to the repository
  status: supported
  confidence: null
- id: check-that-gh-is-installed-and-on-the-path
  text: Check that gh is installed and on the PATH
  status: supported
  confidence: null
- id: via-setup-wizard
  text: Via setup wizard
  status: supported
  confidence: null
- id: via-environment-variables
  text: Via environment variables
  status: supported
  confidence: null
- id: verify-the-server
  text: Verify the server
  status: supported
  confidence: null
- id: configuring-routesconfiguring-routesroute-propertie
  text: '[Configuring Routes](#configuring-routes)[](#route-properties)[](#full-example)[](#prompt-templates)[](#forum-topic-delivery)'
  status: supported
  confidence: null
- id: route-properties
  text: Route properties
  status: supported
  confidence: null
- id: full-example
  text: Full example
  status: supported
  confidence: null
- id: prompt-templates
  text: Prompt Templates
  status: supported
  confidence: null
- id: forum-topic-delivery
  text: Forum Topic Delivery
  status: supported
  confidence: null
- id: github-pr-review-step-by-stepgithub-pr-review1-cr
  text: '[GitHub PR Review (Step by Step)](#github-pr-review)[](#1-create-the-webhook-in-github)[](#2-add-the-route-config)[](#3-ensure-gh-cli-is-authenticated)[](#4-test-it)'
  status: supported
  confidence: null
- id: 1-create-the-webhook-in-github
  text: 1. Create the webhook in GitHub
  status: supported
  confidence: null
- id: 2-add-the-route-config
  text: 2. Add the route config
  status: supported
  confidence: null
- id: 3-ensure-gh-cli-is-authenticated
  text: 3. Ensure gh CLI is authenticated
  status: supported
  confidence: null
- id: 4-test-it
  text: 4. Test it
  status: supported
  confidence: null
- id: gitlab-webhook-setupgitlab-webhook-setup1-create-th
  text: '[GitLab Webhook Setup](#gitlab-webhook-setup)[](#1-create-the-webhook-in-gitlab)[](#2-add-the-route-config-1)'
  status: supported
  confidence: null
- id: 1-create-the-webhook-in-gitlab
  text: 1. Create the webhook in GitLab
  status: supported
  confidence: null
- id: 2-add-the-route-config
  text: 2. Add the route config
  status: supported
  confidence: null
- id: delivery-optionsdelivery-options
  text: '[Delivery Options](#delivery-options)'
  status: supported
  confidence: null
- id: direct-delivery-modedirect-delivery-modewhen-to-use
  text: '[Direct Delivery Mode](#direct-delivery-mode)[](#when-to-use-direct-delivery)[](#example-telegram-push-from-supabase)[](#example-dynamic-subscription-via-cli)[](#response-codes)[](#configuration-gotchas)'
  status: supported
  confidence: null
- id: when-to-use-direct-delivery
  text: When to use direct delivery
  status: supported
  confidence: null
- id: example-telegram-push-from-supabase
  text: 'Example: Telegram push from Supabase'
  status: supported
  confidence: null
- id: example-dynamic-subscription-via-cli
  text: 'Example: Dynamic subscription via CLI'
  status: supported
  confidence: null
- id: response-codes
  text: Response codes
  status: supported
  confidence: null
- id: configuration-gotchas
  text: Configuration gotchas
  status: supported
  confidence: null
- id: dynamic-subscriptions-clidynamic-subscriptionscre
  text: '[Dynamic Subscriptions (CLI)](#dynamic-subscriptions)[](#create-a-subscription)[](#list-subscriptions)[](#remove-a-subscription)[](#test-a-subscription)[](#how-dynamic-subscriptions-work)[](#agent-driven-subscriptions)'
  status: supported
  confidence: null
- id: create-a-subscription
  text: Create a subscription
  status: supported
  confidence: null
- id: list-subscriptions
  text: List subscriptions
  status: supported
  confidence: null
- id: remove-a-subscription
  text: Remove a subscription
  status: supported
  confidence: null
- id: test-a-subscription
  text: Test a subscription
  status: supported
  confidence: null
- id: how-dynamic-subscriptions-work
  text: How dynamic subscriptions work
  status: supported
  confidence: null
- id: agent-driven-subscriptions
  text: Agent-driven subscriptions
  status: supported
  confidence: null
- id: securitysecurityhmac-signature-validationsecre
  text: '[Security](#security)[](#hmac-signature-validation)[](#secret-is-required)[](#rate-limiting)[](#idempotency)[](#body-size-limits)[](#prompt-injection-risk)'
  status: supported
  confidence: null
- id: hmac-signature-validation
  text: HMAC signature validation
  status: supported
  confidence: null
- id: secret-is-required
  text: Secret is required
  status: supported
  confidence: null
- id: rate-limiting
  text: Rate limiting
  status: supported
  confidence: null
- id: idempotency
  text: Idempotency
  status: supported
  confidence: null
- id: body-size-limits
  text: Body size limits
  status: supported
  confidence: null
- id: prompt-injection-risk
  text: Prompt injection risk
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingwebhook-not-arriving
  text: '[Troubleshooting](#troubleshooting)[](#webhook-not-arriving)[](#signature-validation-failing)[](#event-being-ignored)[](#agent-not-responding)[](#duplicate-responses)[](#gh-cli-errors-github-comment-delivery)'
  status: supported
  confidence: null
- id: webhook-not-arriving
  text: Webhook not arriving
  status: supported
  confidence: null
- id: signature-validation-failing
  text: Signature validation failing
  status: supported
  confidence: null
- id: event-being-ignored
  text: Event being ignored
  status: supported
  confidence: null
- id: agent-not-responding
  text: Agent not responding
  status: supported
  confidence: null
- id: duplicate-responses
  text: Duplicate responses
  status: supported
  confidence: null
- id: gh-cli-errors-github-comment-delivery
  text: gh CLI errors (GitHub comment delivery)
  status: supported
  confidence: null
- id: environment-variablesenvironment-variables
  text: '[Environment Variables](#environment-variables)'
  status: supported
  confidence: null
---

On this page

Receive events from external services (GitHub, GitLab, JIRA, Stripe, etc.) and trigger Hermes agent runs automatically. The webhook adapter runs an HTTP server that accepts POST requests, validates HMAC signatures, transforms payloads into agent prompts, and routes responses back to the source or to another configured platform.

The agent processes the event and can respond by posting comments on PRs, sending messages to Telegram/Discord, or logging the result.

---

## Quick Start[​](#quick-start)

****
1. Enable via hermes gateway setup or environment variables

2. Define routes in config.yaml or create them dynamically with hermes webhook subscribe

3. Point your service at http://your-server:8644/webhooks/<route-name>

---

## Setup[​](#setup)

There are two ways to enable the webhook adapter.

### Via setup wizard[​](#via-setup-wizard)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway setup

```

Follow the prompts to enable webhooks, set the port, and set a global HMAC secret.

### Via environment variables[​](#via-environment-variables)

Add to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
WEBHOOK_ENABLED=true
WEBHOOK_PORT=8644 # default
WEBHOOK_SECRET=your-global-secret

```

### Verify the server[​](#verify-the-server)

Once the gateway is running:

```prism-code bash codeBlock_bY9V thin-scrollbar
curl http://localhost:8644/health

```

Expected response:

```prism-code json codeBlock_bY9V thin-scrollbar
{"status": "ok", "platform": "webhook"}

```

---

## Configuring Routes[​](#configuring-routes)

Routes define how different webhook sources are handled. Each route is a named entry under platforms.webhook.extra.routes in your config.yaml.

### Route properties[​](#route-properties)

****[](#direct-delivery-mode)

### Full example[​](#full-example)

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 webhook:
 enabled: true
 extra:
 port: 8644
 secret: "global-fallback-secret"
 routes:
 github-pr:
 events: ["pull_request"]
 secret: "github-webhook-secret"
 prompt: |
 Review this pull request:
 Repository: {repository.full_name}
 PR #{number}: {pull_request.title}
 Author: {pull_request.user.login}
 URL: {pull_request.html_url}
 Diff URL: {pull_request.diff_url}
 Action: {action}
 skills: ["github-code-review"]
 deliver: "github_comment"
 deliver_extra:
 repo: "{repository.full_name}"
 pr_number: "{number}"
 deploy-notify:
 events: ["push"]
 secret: "deploy-secret"
 prompt: "New push to {repository.full_name} branch {ref}: {head_commit.message}"
 deliver: "telegram"

```

### Prompt Templates[​](#prompt-templates)

Prompts use dot-notation to access nested fields in the webhook payload:

****
- {pull_request.title} resolves to payload["pull_request"]["title"]

- {repository.full_name} resolves to payload["repository"]["full_name"]

- {__raw__} — special token that dumps the entire payload as indented JSON (truncated at 4000 characters). Useful for monitoring alerts or generic webhooks where the agent needs the full context.

- Missing keys are left as the literal {key} string (no error)

- Nested dicts and lists are JSON-serialized and truncated at 2000 characters

You can mix {__raw__} with regular template variables:

```prism-code yaml codeBlock_bY9V thin-scrollbar
prompt: "PR #{pull_request.number} by {pull_request.user.login}: {__raw__}"

```

If no prompt template is configured for a route, the entire payload is dumped as indented JSON (truncated at 4000 characters).

The same dot-notation templates work in deliver_extra values.

### Forum Topic Delivery[​](#forum-topic-delivery)

When delivering webhook responses to Telegram, you can target a specific forum topic by including message_thread_id (or thread_id) in deliver_extra:

```prism-code yaml codeBlock_bY9V thin-scrollbar
webhooks:
 routes:
 alerts:
 events: ["alert"]
 prompt: "Alert: {__raw__}"
 deliver: "telegram"
 deliver_extra:
 chat_id: "-1001234567890"
 message_thread_id: "42"

```

If chat_id is not provided in deliver_extra, the delivery falls back to the home channel configured for the target platform.

---

## GitHub PR Review (Step by Step)[​](#github-pr-review)

This walkthrough sets up automatic code review on every pull request.

### 1. Create the webhook in GitHub[​](#1-create-the-webhook-in-github)

****************************************
1. Go to your repository → Settings → Webhooks → Add webhook

2. Set Payload URL to http://your-server:8644/webhooks/github-pr

3. Set Content type to application/json

4. Set Secret to match your route config (e.g. github-webhook-secret)

5. Under Which events?, select Let me select individual events and check Pull requests

6. Click Add webhook

### 2. Add the route config[​](#2-add-the-route-config)

Add the github-pr route to your ~/.hermes/config.yaml as shown in the example above.

### 3. Ensure gh CLI is authenticated[​](#3-ensure-gh-cli-is-authenticated)

The github_comment delivery type uses the GitHub CLI to post comments:

```prism-code bash codeBlock_bY9V thin-scrollbar
gh auth login

```

### 4. Test it[​](#4-test-it)

Open a pull request on the repository. The webhook fires, Hermes processes the event, and posts a review comment on the PR.

---

## GitLab Webhook Setup[​](#gitlab-webhook-setup)

GitLab webhooks work similarly but use a different authentication mechanism. GitLab sends the secret as a plain X-Gitlab-Token header (exact string match, not HMAC).

### 1. Create the webhook in GitLab[​](#1-create-the-webhook-in-gitlab)

************************
1. Go to your project → Settings → Webhooks

2. Set the URL to http://your-server:8644/webhooks/gitlab-mr

3. Enter your Secret token

4. Select Merge request events (and any other events you want)

5. Click Add webhook

### 2. Add the route config[​](#2-add-the-route-config-1)

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 webhook:
 enabled: true
 extra:
 routes:
 gitlab-mr:
 events: ["merge_request"]
 secret: "your-gitlab-secret-token"
 prompt: |
 Review this merge request:
 Project: {project.path_with_namespace}
 MR !{object_attributes.iid}: {object_attributes.title}
 Author: {object_attributes.last_commit.author.name}
 URL: {object_attributes.url}
 Action: {object_attributes.action}
 deliver: "log"

```

---

## Delivery Options[​](#delivery-options)

The deliver field controls where the agent's response goes after processing the webhook event.

For cross-platform delivery, the target platform must also be enabled and connected in the gateway. If no chat_id is provided in deliver_extra, the response is sent to that platform's configured home channel.

---

## Direct Delivery Mode[​](#direct-delivery-mode)

By default, every webhook POST triggers an agent run — the payload becomes a prompt, the agent processes it, and the agent's response is delivered. This costs LLM tokens on every event.

For use cases where you just want to **push a plain notification** — no reasoning, no agent loop, just deliver the message — set deliver_only: true on the route. The rendered prompt template becomes the literal message body, and the adapter dispatches it directly to the configured delivery target.

### When to use direct delivery[​](#when-to-use-direct-delivery)

****************
- External service push — Supabase/Firebase webhook fires on a database change → notify a user in Telegram instantly

- Monitoring alerts — Datadog/Grafana alert webhook → push to a Discord channel

- Inter-agent pings — Agent A notifies Agent B's user that a long-running task finished

- Background job completion — Cron job finishes → post result to Slack

Benefits:

****************
- Zero LLM tokens — the agent is never invoked

- Sub-second delivery — a single adapter call, no reasoning loop

- Same security as agent mode — HMAC auth, rate limits, idempotency, and body-size limits all still apply

- Synchronous response — the POST returns 200 OK once delivery succeeds, or 502 if the target rejects it, so your upstream service can retry intelligently

### Example: Telegram push from Supabase[​](#example-telegram-push-from-supabase)

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 webhook:
 enabled: true
 extra:
 port: 8644
 secret: "global-secret"
 routes:
 antenna-matches:
 secret: "antenna-webhook-secret"
 deliver: "telegram"
 deliver_only: true
 prompt: "🎉 New match: {match.user_name} matched with you!"
 deliver_extra:
 chat_id: "{match.telegram_chat_id}"

```

Your Supabase edge function signs the payload with HMAC-SHA256 and POSTs to https://your-server:8644/webhooks/antenna-matches. The webhook adapter validates the signature, renders the template from the payload, delivers to Telegram, and returns 200 OK.

### Example: Dynamic subscription via CLI[​](#example-dynamic-subscription-via-cli)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes webhook subscribe antenna-matches \
 --deliver telegram \
 --deliver-chat-id "123456789" \
 --deliver-only \
 --prompt "🎉 New match: {match.user_name} matched with you!" \
 --description "Antenna match notifications"

```

### Response codes[​](#response-codes)

### Configuration gotchas[​](#configuration-gotchas)

- deliver_only: true requires deliver to be a real target. deliver: log (or omitting deliver) is rejected at startup — the adapter refuses to start if it finds a misconfigured route.

- The skills field is ignored in direct delivery mode (no agent runs, so there's nothing to inject skills into).

- Template rendering uses the same {dot.notation} syntax as agent mode, including the {__raw__} token.

- Idempotency uses the same X-GitHub-Delivery / X-Request-ID header — retries with the same ID return status=duplicate and do NOT re-deliver.

---

## Dynamic Subscriptions (CLI)[​](#dynamic-subscriptions)

In addition to static routes in config.yaml, you can create webhook subscriptions dynamically using the hermes webhook CLI command. This is especially useful when the agent itself needs to set up event-driven triggers.

### Create a subscription[​](#create-a-subscription)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes webhook subscribe github-issues \
 --events "issues" \
 --prompt "New issue #{issue.number}: {issue.title}\nBy: {issue.user.login}\n\n{issue.body}" \
 --deliver telegram \
 --deliver-chat-id "-100123456789" \
 --description "Triage new GitHub issues"

```

This returns the webhook URL and an auto-generated HMAC secret. Configure your service to POST to that URL.

### List subscriptions[​](#list-subscriptions)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes webhook list

```

### Remove a subscription[​](#remove-a-subscription)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes webhook remove github-issues

```

### Test a subscription[​](#test-a-subscription)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes webhook test github-issues
hermes webhook test github-issues --payload '{"issue": {"number": 42, "title": "Test"}}'

```

### How dynamic subscriptions work[​](#how-dynamic-subscriptions-work)

- Subscriptions are stored in ~/.hermes/webhook_subscriptions.json

- The webhook adapter hot-reloads this file on each incoming request (mtime-gated, negligible overhead)

- Static routes from config.yaml always take precedence over dynamic ones with the same name

- Dynamic subscriptions use the same route format and capabilities as static routes (events, prompt templates, skills, delivery)

- No gateway restart required — subscribe and it's immediately live

### Agent-driven subscriptions[​](#agent-driven-subscriptions)

The agent can create subscriptions via the terminal tool when guided by the webhook-subscriptions skill. Ask the agent to "set up a webhook for GitHub issues" and it will run the appropriate hermes webhook subscribe command.

---

## Security[​](#security)

The webhook adapter includes multiple layers of security:

### HMAC signature validation[​](#hmac-signature-validation)

The adapter validates incoming webhook signatures using the appropriate method for each source:

************
- GitHub: X-Hub-Signature-256 header — HMAC-SHA256 hex digest prefixed with sha256=

- GitLab: X-Gitlab-Token header — plain secret string match

- Generic: X-Webhook-Signature header — raw HMAC-SHA256 hex digest

If a secret is configured but no recognized signature header is present, the request is rejected.

### Secret is required[​](#secret-is-required)

Every route must have a secret — either set directly on the route or inherited from the global secret. Routes without a secret cause the adapter to fail at startup with an error. For development/testing only, you can set the secret to "INSECURE_NO_AUTH" to skip validation entirely.

### Rate limiting[​](#rate-limiting)

Each route is rate-limited to **30 requests per minute** by default (fixed-window). Configure this globally:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 webhook:
 extra:
 rate_limit: 60 # requests per minute

```

Requests exceeding the limit receive a 429 Too Many Requests response.

### Idempotency[​](#idempotency)

Delivery IDs (from X-GitHub-Delivery, X-Request-ID, or a timestamp fallback) are cached for **1 hour**. Duplicate deliveries (e.g. webhook retries) are silently skipped with a 200 response, preventing duplicate agent runs.

### Body size limits[​](#body-size-limits)

Payloads exceeding **1 MB** are rejected before the body is read. Configure this:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 webhook:
 extra:
 max_body_bytes: 2097152 # 2 MB

```

### Prompt injection risk[​](#prompt-injection-risk)

warning

Webhook payloads contain attacker-controlled data — PR titles, commit messages, issue descriptions, etc. can all contain malicious instructions. Run the gateway in a sandboxed environment (Docker, VM) when exposed to the internet. Consider using the Docker or SSH terminal backend for isolation.

---

## Troubleshooting[​](#troubleshooting)

### Webhook not arriving[​](#webhook-not-arriving)

- Verify the port is exposed and accessible from the webhook source

- Check firewall rules — port 8644 (or your configured port) must be open

- Verify the URL path matches: http://your-server:8644/webhooks/<route-name>

- Use the /health endpoint to confirm the server is running

### Signature validation failing[​](#signature-validation-failing)

- Ensure the secret in your route config exactly matches the secret configured in the webhook source

- For GitHub, the secret is HMAC-based — check X-Hub-Signature-256

- For GitLab, the secret is a plain token match — check X-Gitlab-Token

- Check gateway logs for Invalid signature warnings

### Event being ignored[​](#event-being-ignored)

- Check that the event type is in your route's events list

- GitHub events use values like pull_request, push, issues (the X-GitHub-Event header value)

- GitLab events use values like merge_request, push (the X-GitLab-Event header value)

- If events is empty or not set, all events are accepted

### Agent not responding[​](#agent-not-responding)

- Run the gateway in foreground to see logs: hermes gateway run

- Check that the prompt template is rendering correctly

- Verify the delivery target is configured and connected

### Duplicate responses[​](#duplicate-responses)

- The idempotency cache should prevent this — check that the webhook source is sending a delivery ID header (X-GitHub-Delivery or X-Request-ID)

- Delivery IDs are cached for 1 hour

### gh CLI errors (GitHub comment delivery)[​](#gh-cli-errors-github-comment-delivery)

- Run gh auth login on the gateway host

- Ensure the authenticated GitHub user has write access to the repository

- Check that gh is installed and on the PATH

---

## Environment Variables[​](#environment-variables)

**[](#quick-start)[](#setup)[](#via-setup-wizard)[](#via-environment-variables)[](#verify-the-server)
- Via setup wizard
- Via environment variables
- Verify the server
- [Configuring Routes](#configuring-routes)[](#route-properties)[](#full-example)[](#prompt-templates)[](#forum-topic-delivery)
- Route properties
- Full example
- Prompt Templates
- Forum Topic Delivery
- [GitHub PR Review (Step by Step)](#github-pr-review)[](#1-create-the-webhook-in-github)[](#2-add-the-route-config)[](#3-ensure-gh-cli-is-authenticated)[](#4-test-it)
- 1. Create the webhook in GitHub
- 2. Add the route config
- 3. Ensure gh CLI is authenticated
- 4. Test it
- [GitLab Webhook Setup](#gitlab-webhook-setup)[](#1-create-the-webhook-in-gitlab)[](#2-add-the-route-config-1)
- 1. Create the webhook in GitLab
- 2. Add the route config
- [Delivery Options](#delivery-options)
- [Direct Delivery Mode](#direct-delivery-mode)[](#when-to-use-direct-delivery)[](#example-telegram-push-from-supabase)[](#example-dynamic-subscription-via-cli)[](#response-codes)[](#configuration-gotchas)
- When to use direct delivery
- Example: Telegram push from Supabase
- Example: Dynamic subscription via CLI
- Response codes
- Configuration gotchas
- [Dynamic Subscriptions (CLI)](#dynamic-subscriptions)[](#create-a-subscription)[](#list-subscriptions)[](#remove-a-subscription)[](#test-a-subscription)[](#how-dynamic-subscriptions-work)[](#agent-driven-subscriptions)
- Create a subscription
- List subscriptions
- Remove a subscription
- Test a subscription
- How dynamic subscriptions work
- Agent-driven subscriptions
- [Security](#security)[](#hmac-signature-validation)[](#secret-is-required)[](#rate-limiting)[](#idempotency)[](#body-size-limits)[](#prompt-injection-risk)
- HMAC signature validation
- Secret is required
- Rate limiting
- Idempotency
- Body size limits
- Prompt injection risk
- [Troubleshooting](#troubleshooting)[](#webhook-not-arriving)[](#signature-validation-failing)[](#event-being-ignored)[](#agent-not-responding)[](#duplicate-responses)[](#gh-cli-errors-github-comment-delivery)
- Webhook not arriving
- Signature validation failing
- Event being ignored
- Agent not responding
- Duplicate responses
- gh CLI errors (GitHub comment delivery)
- [Environment Variables](#environment-variables)