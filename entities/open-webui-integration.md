---
pageType: entity
id: entity.open-webui-integration
title: Open WebUI Integration
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/open-webui.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/open-webui.md
updatedAt: '2026-04-24T15:05:24.621628+00:00'
sourceIds:
- githubcom
- hostdockerinternal86
- '17217018642'
sources:
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/open-webui/open-webui
  title: '[Open WebUI](https://github.com/open-webui/open-webui)'
- sourceId: hostdockerinternal86
  sourceType: web
  sourcePath: http://host.docker.internal:8642/v1
  title: host.docker.internal:8642
- sourceId: '17217018642'
  sourceType: web
  sourcePath: http://172.17.0.1:8642/v1
  title: 172.17.0.1:8642
claims:
- id: e-openai-api-base-urlhttphostdockerinternal8642v1
  text: e OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1 \
  status: supported
  confidence: null
- id: e-openai-api-keyyour-secret-key
  text: e OPENAI_API_KEY=your-secret-key \
  status: supported
  confidence: null
- id: add-hosthostdockerinternalhost-gateway
  text: add-host=host.docker.internal:host-gateway \
  status: supported
  confidence: null
- id: v-open-webuiappbackenddata
  text: v open-webui:/app/backend/data \
  status: supported
  confidence: null
- id: name-open-webui
  text: name open-webui \
  status: supported
  confidence: null
- id: restart-always
  text: restart always \
  status: supported
  confidence: null
- id: '30008080'
  text: '"3000:8080"'
  status: supported
  confidence: null
- id: open-webuiappbackenddata
  text: open-webui:/app/backend/data
  status: supported
  confidence: null
- id: openai-api-base-urlhttphostdockerinternal8642v1
  text: OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1
  status: supported
  confidence: null
- id: openai-api-keyyour-secret-key
  text: OPENAI_API_KEY=your-secret-key
  status: supported
  confidence: null
- id: hostdockerinternalhost-gateway
  text: '"host.docker.internal:host-gateway"'
  status: supported
  confidence: null
- id: url-httphostdockerinternal8642v1
  text: 'URL: http://host.docker.internal:8642/v1'
  status: supported
  confidence: null
- id: api-key-your-key-or-any-non-empty-value-eg-not-needed
  text: 'API Key: your key or any non-empty value (e.g., not-needed)'
  status: supported
  confidence: null
- id: click-the-checkmark-to-verify-the-connection
  text: Click the **checkmark** to verify the connection
  status: supported
  confidence: null
- id: check-the-url-has-v1-suffix-httphostdockerinternal86
  text: 'Check the URL has /v1 suffix: http://host.docker.internal:8642/v1 (not just
    :8642)'
  status: supported
  confidence: null
- id: verify-the-gateway-is-running-curl-httplocalhost8642he
  text: 'Verify the gateway is running: curl http://localhost:8642/health should return
    {"status": "ok"}'
  status: supported
  confidence: null
- id: check-model-listing-curl-httplocalhost8642v1models-sh
  text: 'Check model listing: curl http://localhost:8642/v1/models should return a
    list with hermes-agent'
  status: supported
  confidence: null
- id: docker-networking-from-inside-docker-localhost-means-the-c
  text: 'Docker networking: From inside Docker, localhost means the container, not
    your host. Use host.docker.internal or --network=host.'
  status: supported
  confidence: null
- id: 1-enable-the-api-server
  text: 1. Enable the API server
  status: supported
  confidence: null
- id: 2-start-hermes-agent-gateway
  text: 2. Start Hermes Agent gateway
  status: supported
  confidence: null
- id: 3-start-open-webui
  text: 3. Start Open WebUI
  status: supported
  confidence: null
- id: 4-open-the-ui
  text: 4. Open the UI
  status: supported
  confidence: null
- id: docker-compose-setupdocker-compose-setup
  text: '[Docker Compose Setup](#docker-compose-setup)'
  status: supported
  confidence: null
- id: configuring-via-the-admin-uiconfiguring-via-the-admin-ui
  text: '[Configuring via the Admin UI](#configuring-via-the-admin-ui)'
  status: supported
  confidence: null
- id: api-type-chat-completions-vs-responsesapi-type-chat-com
  text: '[API Type: Chat Completions vs Responses](#api-type-chat-completions-vs-responses)[](#using-chat-completions-recommended)[](#using-responses-api)'
  status: supported
  confidence: null
- id: using-chat-completions-recommended
  text: Using Chat Completions (recommended)
  status: supported
  confidence: null
- id: using-responses-api
  text: Using Responses API
  status: supported
  confidence: null
- id: how-it-workshow-it-works
  text: '[How It Works](#how-it-works)'
  status: supported
  confidence: null
- id: configuration-referenceconfiguration-referenceherme
  text: '[Configuration Reference](#configuration-reference)[](#hermes-agent-api-server)[](#open-webui)'
  status: supported
  confidence: null
- id: hermes-agent-api-server
  text: Hermes Agent (API server)
  status: supported
  confidence: null
- id: open-webui
  text: Open WebUI
  status: supported
  confidence: null
- id: troubleshootingtroubleshootingno-models-appear-in-t
  text: '[Troubleshooting](#troubleshooting)[](#no-models-appear-in-the-dropdown)[](#connection-test-passes-but-no-models-load)[](#response-takes-a-long-time)[](#invalid-api-key-errors)'
  status: supported
  confidence: null
- id: no-models-appear-in-the-dropdown
  text: No models appear in the dropdown
  status: supported
  confidence: null
- id: connection-test-passes-but-no-models-load
  text: Connection test passes but no models load
  status: supported
  confidence: null
- id: response-takes-a-long-time
  text: Response takes a long time
  status: supported
  confidence: null
- id: invalid-api-key-errors
  text: '"Invalid API key" errors'
  status: supported
  confidence: null
- id: multi-user-setup-with-profilesmulti-user-setup-with-prof
  text: '[Multi-User Setup with Profiles](#multi-user-setup-with-profiles)[](#1-create-profiles-and-configure-api-servers)[](#2-start-each-gateway)[](#3-add-connections-in-open-webui)'
  status: supported
  confidence: null
- id: 1-create-profiles-and-configure-api-servers
  text: 1. Create profiles and configure API servers
  status: supported
  confidence: null
- id: 2-start-each-gateway
  text: 2. Start each gateway
  status: supported
  confidence: null
- id: 3-add-connections-in-open-webui
  text: 3. Add connections in Open WebUI
  status: supported
  confidence: null
- id: linux-docker-no-docker-desktoplinux-docker-no-docker-d
  text: '[Linux Docker (no Docker Desktop)](#linux-docker-no-docker-desktop)'
  status: supported
  confidence: null
---

On this page

[Open WebUI](https://github.com/open-webui/open-webui) (126k★) is the most popular self-hosted chat interface for AI. With Hermes Agent's built-in API server, you can use Open WebUI as a polished web frontend for your agent — complete with conversation management, user accounts, and a modern chat interface.

## Architecture[​](#architecture)

Open WebUI connects to Hermes Agent's API server just like it would connect to OpenAI. Your agent handles the requests with its full toolset — terminal, file operations, web search, memory, skills — and returns the final response.

Open WebUI talks to Hermes server-to-server, so you do not need API_SERVER_CORS_ORIGINS for this integration.

## Quick Setup[​](#quick-setup)

### 1. Enable the API server[​](#1-enable-the-api-server)

Add to ~/.hermes/.env:

```prism-code bash codeBlock_bY9V thin-scrollbar
API_SERVER_ENABLED=true
API_SERVER_KEY=your-secret-key

```

### 2. Start Hermes Agent gateway[​](#2-start-hermes-agent-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

You should see:

```prism-code text codeBlock_bY9V thin-scrollbar
[API Server] API server listening on http://127.0.0.1:8642

```

### 3. Start Open WebUI[​](#3-start-open-webui)

```prism-code bash codeBlock_bY9V thin-scrollbar
docker run -d -p 3000:8080 \
 -e OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1 \
 -e OPENAI_API_KEY=your-secret-key \
 --add-host=host.docker.internal:host-gateway \
 -v open-webui:/app/backend/data \
 --name open-webui \
 --restart always \
 ghcr.io/open-webui/open-webui:main

```

### 4. Open the UI[​](#4-open-the-ui)

Go to **[http://localhost:3000](http://localhost:3000)**. Create your admin account (the first user becomes admin). You should see your agent in the model dropdown (named after your profile, or **hermes-agent** for the default profile). Start chatting!

## Docker Compose Setup[​](#docker-compose-setup)

For a more permanent setup, create a docker-compose.yml:

```prism-code yaml codeBlock_bY9V thin-scrollbar
services:
 open-webui:
 image: ghcr.io/open-webui/open-webui:main
 ports:
 - "3000:8080"
 volumes:
 - open-webui:/app/backend/data
 environment:
 - OPENAI_API_BASE_URL=http://host.docker.internal:8642/v1
 - OPENAI_API_KEY=your-secret-key
 extra_hosts:
 - "host.docker.internal:host-gateway"
 restart: always

volumes:
 open-webui:

```

Then:

```prism-code bash codeBlock_bY9V thin-scrollbar
docker compose up -d

```

## Configuring via the Admin UI[​](#configuring-via-the-admin-ui)

If you prefer to configure the connection through the UI instead of environment variables:

**[](http://localhost:3000)**********************************
- URL: http://host.docker.internal:8642/v1

- API Key: your key or any non-empty value (e.g., not-needed)

- Click the **checkmark** to verify the connection

- **Save**

Your agent model should now appear in the model dropdown (named after your profile, or **hermes-agent** for the default profile).

warning

Environment variables only take effect on Open WebUI's **first launch**. After that, connection settings are stored in its internal database. To change them later, use the Admin UI or delete the Docker volume and start fresh.

## API Type: Chat Completions vs Responses[​](#api-type-chat-completions-vs-responses)

Open WebUI supports two API modes when connecting to a backend:

********

### Using Chat Completions (recommended)[​](#using-chat-completions-recommended)

This is the default and requires no extra configuration. Open WebUI sends standard OpenAI-format requests and Hermes Agent responds accordingly. Each request includes the full conversation history.

### Using Responses API[​](#using-responses-api)

To use the Responses API mode:

************************
1. Go to Admin Settings → Connections → OpenAI → Manage

2. Edit your hermes-agent connection

3. Change API Type from "Chat Completions" to "Responses (Experimental)"

4. Save

With the Responses API, Open WebUI sends requests in the Responses format (input array + instructions), and Hermes Agent can preserve full tool call history across turns via previous_response_id. When stream: true, Hermes also streams spec-native function_call and function_call_output items, which enables custom structured tool-call UI in clients that render Responses events.

note

Open WebUI currently manages conversation history client-side even in Responses mode — it sends the full message history in each request rather than using previous_response_id. The main advantage of Responses mode today is the structured event stream: text deltas, function_call, and function_call_output items arrive as OpenAI Responses SSE events instead of Chat Completions chunks.

## How It Works[​](#how-it-works)

When you send a message in Open WebUI:

****
1. Open WebUI sends a POST /v1/chat/completions request with your message and conversation history

2. Hermes Agent creates an AIAgent instance with its full toolset

3. The agent processes your request — it may call tools (terminal, file operations, web search, etc.)

4. As tools execute, inline progress messages stream to the UI so you can see what the agent is doing (e.g. `💻 ls -la`, `🔍 Python 3.12 release`)

5. The agent's final text response streams back to Open WebUI

6. Open WebUI displays the response in its chat interface

Your agent has access to all the same tools and capabilities as when using the CLI or Telegram — the only difference is the frontend.

Tool Progress

With streaming enabled (the default), you'll see brief inline indicators as tools run — the tool emoji and its key argument. These appear in the response stream before the agent's final answer, giving you visibility into what's happening behind the scenes.

## Configuration Reference[​](#configuration-reference)

### Hermes Agent (API server)[​](#hermes-agent-api-server)

**

### Open WebUI[​](#open-webui)

## Troubleshooting[​](#troubleshooting)

### No models appear in the dropdown[​](#no-models-appear-in-the-dropdown)

****************
- Check the URL has /v1 suffix: http://host.docker.internal:8642/v1 (not just :8642)

- Verify the gateway is running: curl http://localhost:8642/health should return {"status": "ok"}

- Check model listing: curl http://localhost:8642/v1/models should return a list with hermes-agent

- Docker networking: From inside Docker, localhost means the container, not your host. Use host.docker.internal or --network=host.

### Connection test passes but no models load[​](#connection-test-passes-but-no-models-load)

This is almost always the missing /v1 suffix. Open WebUI's connection test is a basic connectivity check — it doesn't verify model listing works.

### Response takes a long time[​](#response-takes-a-long-time)

Hermes Agent may be executing multiple tool calls (reading files, running commands, searching the web) before producing its final response. This is normal for complex queries. The response appears all at once when the agent finishes.

### "Invalid API key" errors[​](#invalid-api-key-errors)

Make sure your OPENAI_API_KEY in Open WebUI matches the API_SERVER_KEY in Hermes Agent.

## Multi-User Setup with Profiles[​](#multi-user-setup-with-profiles)

To run separate Hermes instances per user — each with their own config, memory, and skills — use [profiles](/docs/user-guide/profiles). Each profile runs its own API server on a different port and automatically advertises the profile name as the model in Open WebUI.

### 1. Create profiles and configure API servers[​](#1-create-profiles-and-configure-api-servers)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes profile create alice
hermes -p alice config set API_SERVER_ENABLED true
hermes -p alice config set API_SERVER_PORT 8643
hermes -p alice config set API_SERVER_KEY alice-secret

hermes profile create bob
hermes -p bob config set API_SERVER_ENABLED true
hermes -p bob config set API_SERVER_PORT 8644
hermes -p bob config set API_SERVER_KEY bob-secret

```

### 2. Start each gateway[​](#2-start-each-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes -p alice gateway &
hermes -p bob gateway &

```

### 3. Add connections in Open WebUI[​](#3-add-connections-in-open-webui)

In **Admin Settings** → **Connections** → **OpenAI API** → **Manage**, add one connection per profile:

The model dropdown will show alice and bob as distinct models. You can assign models to Open WebUI users via the admin panel, giving each user their own isolated Hermes agent.

Custom Model Names

The model name defaults to the profile name. To override it, set API_SERVER_MODEL_NAME in the profile's .env:

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes -p alice config set API_SERVER_MODEL_NAME "Alice's Agent"

```

## Linux Docker (no Docker Desktop)[​](#linux-docker-no-docker-desktop)

On Linux without Docker Desktop, host.docker.internal doesn't resolve by default. Options:

```prism-code bash codeBlock_bY9V thin-scrollbar
# Option 1: Add host mapping
docker run --add-host=host.docker.internal:host-gateway ...

# Option 2: Use host networking
docker run --network=host -e OPENAI_API_BASE_URL=http://localhost:8642/v1 ...

# Option 3: Use Docker bridge IP
docker run -e OPENAI_API_BASE_URL=http://172.17.0.1:8642/v1 ...

```
[](#architecture)[](#quick-setup)[](#1-enable-the-api-server)[](#2-start-hermes-agent-gateway)[](#3-start-open-webui)[](#4-open-the-ui)
- 1. Enable the API server
- 2. Start Hermes Agent gateway
- 3. Start Open WebUI
- 4. Open the UI
- [Docker Compose Setup](#docker-compose-setup)
- [Configuring via the Admin UI](#configuring-via-the-admin-ui)
- [API Type: Chat Completions vs Responses](#api-type-chat-completions-vs-responses)[](#using-chat-completions-recommended)[](#using-responses-api)
- Using Chat Completions (recommended)
- Using Responses API
- [How It Works](#how-it-works)
- [Configuration Reference](#configuration-reference)[](#hermes-agent-api-server)[](#open-webui)
- Hermes Agent (API server)
- Open WebUI
- [Troubleshooting](#troubleshooting)[](#no-models-appear-in-the-dropdown)[](#connection-test-passes-but-no-models-load)[](#response-takes-a-long-time)[](#invalid-api-key-errors)
- No models appear in the dropdown
- Connection test passes but no models load
- Response takes a long time
- "Invalid API key" errors
- [Multi-User Setup with Profiles](#multi-user-setup-with-profiles)[](#1-create-profiles-and-configure-api-servers)[](#2-start-each-gateway)[](#3-add-connections-in-open-webui)
- 1. Create profiles and configure API servers
- 2. Start each gateway
- 3. Add connections in Open WebUI
- [Linux Docker (no Docker Desktop)](#linux-docker-no-docker-desktop)