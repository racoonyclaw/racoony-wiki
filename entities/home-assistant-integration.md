---
pageType: entity
id: entity.home-assistant-integration
title: Home Assistant Integration
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/homeassistant.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/homeassistant.md
updatedAt: '2026-04-24T15:05:25.073368+00:00'
sourceIds:
- wwwhome-assistantio
- homeassistantlocal81
- '19216811008123'
sources:
- sourceId: wwwhome-assistantio
  sourceType: web
  sourcePath: https://www.home-assistant.io/
  title: '[Home Assistant](https://www.home-assistant.io/)'
- sourceId: homeassistantlocal81
  sourceType: web
  sourcePath: http://homeassistant.local:8123
  title: homeassistant.local:8123
- sourceId: '19216811008123'
  sourceType: web
  sourcePath: http://192.168.1.100:8123
  title: 192.168.1.100:8123
claims:
- id: domain-optional-filter-by-entity-domain-light-switch
  text: "domain (optional) \u2014 Filter by entity domain: light, switch, climate,\
    \ sensor, binary_sensor, cover, fan, media_player, etc."
  status: supported
  confidence: null
- id: area-optional-filter-by-arearoom-name-matches-against
  text: "area (optional) \u2014 Filter by area/room name (matches against friendly\
    \ names): living room, kitchen, bedroom, etc."
  status: supported
  confidence: null
- id: entity-id-required-the-entity-to-query-eg-lightlivi
  text: "entity_id (required) \u2014 The entity to query, e.g., light.living_room,\
    \ climate.thermostat, sensor.temperature"
  status: supported
  confidence: null
- id: domain-optional-filter-by-domain-eg-light-climate
  text: "domain (optional) \u2014 Filter by domain, e.g., light, climate, switch"
  status: supported
  confidence: null
- id: domain-required-service-domain-light-switch-climate
  text: "domain (required) \u2014 Service domain: light, switch, climate, cover, media_player,\
    \ fan, scene, script"
  status: supported
  confidence: null
- id: service-required-service-name-turn-on-turn-off-toggle
  text: "service (required) \u2014 Service name: turn_on, turn_off, toggle, set_temperature,\
    \ set_hvac_mode, open_cover, close_cover, set_volume_level"
  status: supported
  confidence: null
- id: entity-id-optional-target-entity-eg-lightliving-roo
  text: "entity_id (optional) \u2014 Target entity, e.g., light.living_room"
  status: supported
  confidence: null
- id: data-optional-additional-parameters-as-a-json-object
  text: "data (optional) \u2014 Additional parameters as a JSON object"
  status: supported
  confidence: null
- id: binary-sensor
  text: binary_sensor
  status: supported
  confidence: null
- id: alarm-control-panel
  text: alarm_control_panel
  status: supported
  confidence: null
- id: sensorfront-door-battery
  text: sensor.front_door_battery
  status: supported
  confidence: null
- id: sensoruptime
  text: sensor.uptime
  status: supported
  confidence: null
- id: sensorcpu-usage
  text: sensor.cpu_usage
  status: supported
  confidence: null
- id: sensormemory-usage
  text: sensor.memory_usage
  status: supported
  confidence: null
- id: websocket-with-30-second-heartbeat-for-real-time-events
  text: WebSocket with 30-second heartbeat for real-time events
  status: supported
  confidence: null
- id: automatic-reconnection-with-backoff-5s-10s-30s-60s
  text: "Automatic reconnection with backoff: 5s \u2192 10s \u2192 30s \u2192 60s"
  status: supported
  confidence: null
- id: rest-api-for-outbound-notifications-separate-session-to-avo
  text: REST API for outbound notifications (separate session to avoid WebSocket conflicts)
  status: supported
  confidence: null
- id: authorization-ha-events-are-always-authorized-no-user-all
  text: "Authorization \u2014 HA events are always authorized (no user allowlist needed,\
    \ since the HASS_TOKEN authenticates the connection)"
  status: supported
  confidence: null
- id: shell-command-arbitrary-shell-commands
  text: "shell_command \u2014 arbitrary shell commands"
  status: supported
  confidence: null
- id: command-line-sensorsswitches-that-execute-commands
  text: "command_line \u2014 sensors/switches that execute commands"
  status: supported
  confidence: null
- id: python-script-scripted-python-execution
  text: "python_script \u2014 scripted Python execution"
  status: supported
  confidence: null
- id: pyscript-broader-scripting-integration
  text: "pyscript \u2014 broader scripting integration"
  status: supported
  confidence: null
- id: hassio-addon-control-host-shutdownreboot
  text: "hassio \u2014 addon control, host shutdown/reboot"
  status: supported
  confidence: null
- id: rest-command-http-requests-from-ha-server-ssrf-vector
  text: "rest_command \u2014 HTTP requests from HA server (SSRF vector)"
  status: supported
  confidence: null
- id: 1-create-a-long-lived-access-token
  text: 1. Create a Long-Lived Access Token
  status: supported
  confidence: null
- id: 2-configure-environment-variables
  text: 2. Configure Environment Variables
  status: supported
  confidence: null
- id: 3-start-the-gateway
  text: 3. Start the Gateway
  status: supported
  confidence: null
- id: available-toolsavailable-toolsha-list-entities
  text: '[Available Tools](#available-tools)[](#ha_list_entities)[](#ha_get_state)[](#ha_list_services)[](#ha_call_service)'
  status: supported
  confidence: null
- id: ha-list-entities
  text: ha_list_entities
  status: supported
  confidence: null
- id: ha-get-state
  text: ha_get_state
  status: supported
  confidence: null
- id: ha-list-services
  text: ha_list_services
  status: supported
  confidence: null
- id: ha-call-service
  text: ha_call_service
  status: supported
  confidence: null
- id: gateway-platform-real-time-eventsgateway-platform-real
  text: '[Gateway Platform: Real-Time Events](#gateway-platform-real-time-events)[](#event-filtering)[](#event-formatting)[](#agent-responses)[](#connection-management)'
  status: supported
  confidence: null
- id: event-filtering
  text: Event Filtering
  status: supported
  confidence: null
- id: event-formatting
  text: Event Formatting
  status: supported
  confidence: null
- id: agent-responses
  text: Agent Responses
  status: supported
  confidence: null
- id: connection-management
  text: Connection Management
  status: supported
  confidence: null
- id: securitysecurity
  text: '[Security](#security)'
  status: supported
  confidence: null
- id: example-automationsexample-automationsmorning-routi
  text: '[Example Automations](#example-automations)[](#morning-routine)[](#security-check)[](#reactive-automation-via-gateway-events)'
  status: supported
  confidence: null
- id: morning-routine
  text: Morning Routine
  status: supported
  confidence: null
- id: security-check
  text: Security Check
  status: supported
  confidence: null
- id: reactive-automation-via-gateway-events
  text: Reactive Automation (via Gateway Events)
  status: supported
  confidence: null
---

On this page

Hermes Agent integrates with [Home Assistant](https://www.home-assistant.io/) in two ways:

********
1. Gateway platform — subscribes to real-time state changes via WebSocket and responds to events

2. Smart home tools — four LLM-callable tools for querying and controlling devices via the REST API

## Setup[​](#setup)

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

### 1. Create a Long-Lived Access Token[​](#1-create-a-long-lived-access-token)

************
1. Open your Home Assistant instance

2. Go to your Profile (click your name in the sidebar)

3. Scroll to Long-Lived Access Tokens

4. Click Create Token, give it a name like "Hermes Agent"

5. Copy the token

### 2. Configure Environment Variables[​](#2-configure-environment-variables)

```prism-code bash codeBlock_bY9V thin-scrollbar
# Add to ~/.hermes/.env

# Required: your Long-Lived Access Token
HASS_TOKEN=your-long-lived-access-token

# Optional: HA URL (default: http://homeassistant.local:8123)
HASS_URL=http://192.168.1.100:8123

```

info

The homeassistant toolset is automatically enabled when HASS_TOKEN is set. Both the gateway platform and the device control tools activate from this single token.

### 3. Start the Gateway[​](#3-start-the-gateway)

```prism-code bash codeBlock_bY9V thin-scrollbar
hermes gateway

```

Home Assistant will appear as a connected platform alongside any other messaging platforms (Telegram, Discord, etc.).

## Available Tools[​](#available-tools)

Hermes Agent registers four tools for smart home control:

### ha_list_entities[​](#ha_list_entities)

List Home Assistant entities, optionally filtered by domain or area.

**Parameters:**

****
- domain (optional) — Filter by entity domain: light, switch, climate, sensor, binary_sensor, cover, fan, media_player, etc.

- area (optional) — Filter by area/room name (matches against friendly names): living room, kitchen, bedroom, etc.

**Example:**

```prism-code text codeBlock_bY9V thin-scrollbar
List all lights in the living room

```

Returns entity IDs, states, and friendly names.

### ha_get_state[​](#ha_get_state)

Get detailed state of a single entity, including all attributes (brightness, color, temperature setpoint, sensor readings, etc.).

**Parameters:**

**
- entity_id (required) — The entity to query, e.g., light.living_room, climate.thermostat, sensor.temperature

**Example:**

```prism-code text codeBlock_bY9V thin-scrollbar
What's the current state of climate.thermostat?

```

Returns: state, all attributes, last changed/updated timestamps.

### ha_list_services[​](#ha_list_services)

List available services (actions) for device control. Shows what actions can be performed on each device type and what parameters they accept.

**Parameters:**

**
- domain (optional) — Filter by domain, e.g., light, climate, switch

**Example:**

```prism-code text codeBlock_bY9V thin-scrollbar
What services are available for climate devices?

```

### ha_call_service[​](#ha_call_service)

Call a Home Assistant service to control a device.

**Parameters:**

********
- domain (required) — Service domain: light, switch, climate, cover, media_player, fan, scene, script

- service (required) — Service name: turn_on, turn_off, toggle, set_temperature, set_hvac_mode, open_cover, close_cover, set_volume_level

- entity_id (optional) — Target entity, e.g., light.living_room

- data (optional) — Additional parameters as a JSON object

**Examples:**

```prism-code text codeBlock_bY9V thin-scrollbar
Turn on the living room lights
→ ha_call_service(domain="light", service="turn_on", entity_id="light.living_room")

```

```prism-code text codeBlock_bY9V thin-scrollbar
Set the thermostat to 22 degrees in heat mode
→ ha_call_service(domain="climate", service="set_temperature",
 entity_id="climate.thermostat", data={"temperature": 22, "hvac_mode": "heat"})

```

```prism-code text codeBlock_bY9V thin-scrollbar
Set living room lights to blue at 50% brightness
→ ha_call_service(domain="light", service="turn_on",
 entity_id="light.living_room", data={"brightness": 128, "color_name": "blue"})

```

## Gateway Platform: Real-Time Events[​](#gateway-platform-real-time-events)

The Home Assistant gateway adapter connects via WebSocket and subscribes to state_changed events. When a device state changes and matches your filters, it's forwarded to the agent as a message.

### Event Filtering[​](#event-filtering)

Required Configuration

By default, **no events are forwarded**. You must configure at least one of watch_domains, watch_entities, or watch_all to receive events. Without filters, a warning is logged at startup and all state changes are silently dropped.

Configure which events the agent sees in ~/.hermes/config.yaml under the Home Assistant platform's extra section:

```prism-code yaml codeBlock_bY9V thin-scrollbar
platforms:
 homeassistant:
 enabled: true
 extra:
 watch_domains:
 - climate
 - binary_sensor
 - alarm_control_panel
 - light
 watch_entities:
 - sensor.front_door_battery
 ignore_entities:
 - sensor.uptime
 - sensor.cpu_usage
 - sensor.memory_usage
 cooldown_seconds: 30

```

**********
tip

Start with a focused set of domains — climate, binary_sensor, and alarm_control_panel cover the most useful automations. Add more as needed. Use ignore_entities to suppress noisy sensors like CPU temperature or uptime counters.

### Event Formatting[​](#event-formatting)

State changes are formatted as human-readable messages based on domain:

**

### Agent Responses[​](#agent-responses)

Outbound messages from the agent are delivered as **Home Assistant persistent notifications** (via persistent_notification.create). These appear in the HA notification panel with the title "Hermes Agent".

### Connection Management[​](#connection-management)

****************
- WebSocket with 30-second heartbeat for real-time events

- Automatic reconnection with backoff: 5s → 10s → 30s → 60s

- REST API for outbound notifications (separate session to avoid WebSocket conflicts)

- Authorization — HA events are always authorized (no user allowlist needed, since the HASS_TOKEN authenticates the connection)

## Security[​](#security)

The Home Assistant tools enforce security restrictions:

Blocked Domains

The following service domains are **blocked** to prevent arbitrary code execution on the HA host:

- shell_command — arbitrary shell commands

- command_line — sensors/switches that execute commands

- python_script — scripted Python execution

- pyscript — broader scripting integration

- hassio — addon control, host shutdown/reboot

- rest_command — HTTP requests from HA server (SSRF vector)

Attempting to call services in these domains returns an error.

Entity IDs are validated against the pattern ^[a-z_][a-z0-9_]*\.[a-z0-9_]+$ to prevent injection attacks.

## Example Automations[​](#example-automations)

### Morning Routine[​](#morning-routine)

```prism-code text codeBlock_bY9V thin-scrollbar
User: Start my morning routine

Agent:
1. ha_call_service(domain="light", service="turn_on",
 entity_id="light.bedroom", data={"brightness": 128})
2. ha_call_service(domain="climate", service="set_temperature",
 entity_id="climate.thermostat", data={"temperature": 22})
3. ha_call_service(domain="media_player", service="turn_on",
 entity_id="media_player.kitchen_speaker")

```

### Security Check[​](#security-check)

```prism-code text codeBlock_bY9V thin-scrollbar
User: Is the house secure?

Agent:
1. ha_list_entities(domain="binary_sensor")
 → checks door/window sensors
2. ha_get_state(entity_id="alarm_control_panel.home")
 → checks alarm status
3. ha_list_entities(domain="lock")
 → checks lock states
4. Reports: "All doors closed, alarm is armed_away, all locks engaged."

```

### Reactive Automation (via Gateway Events)[​](#reactive-automation-via-gateway-events)

When connected as a gateway platform, the agent can react to events:

```prism-code text codeBlock_bY9V thin-scrollbar
[Home Assistant] Front Door: triggered (was cleared)

Agent automatically:
1. ha_get_state(entity_id="binary_sensor.front_door")
2. ha_call_service(domain="light", service="turn_on",
 entity_id="light.hallway")
3. Sends notification: "Front door opened. Hallway lights turned on."

```
[](#setup)[](#1-create-a-long-lived-access-token)[](#2-configure-environment-variables)[](#3-start-the-gateway)
- 1. Create a Long-Lived Access Token
- 2. Configure Environment Variables
- 3. Start the Gateway
- [Available Tools](#available-tools)[](#ha_list_entities)[](#ha_get_state)[](#ha_list_services)[](#ha_call_service)
- ha_list_entities
- ha_get_state
- ha_list_services
- ha_call_service
- [Gateway Platform: Real-Time Events](#gateway-platform-real-time-events)[](#event-filtering)[](#event-formatting)[](#agent-responses)[](#connection-management)
- Event Filtering
- Event Formatting
- Agent Responses
- Connection Management
- [Security](#security)
- [Example Automations](#example-automations)[](#morning-routine)[](#security-check)[](#reactive-automation-via-gateway-events)
- Morning Routine
- Security Check
- Reactive Automation (via Gateway Events)