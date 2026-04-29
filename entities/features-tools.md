---
pageType: entity
id: entity.features-tools
title: 'Features: Tools'
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-features-tools.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-features-tools.md
updatedAt: '2026-04-24T15:05:25.791056+00:00'
sourceIds:
- portalnousresearchco
sources:
- sourceId: portalnousresearchco
  sourceType: web
  sourcePath: https://portal.nousresearch.com
  title: '[Nous Portal](https://portal.nousresearch.com)'
claims:
- id: category-examples-description
  text: Category**, **Examples**, **Description**
  status: supported
  confidence: null
- id: category-web-examples-web-search-web-extrac
  text: 'Category**: **Web**, **Examples**: `web_search`, `web_extract`, **Description**:
    Search the web and extract page content.'
  status: supported
  confidence: null
- id: category-terminal-files-examples-terminal
  text: 'Category**: **Terminal & Files**, **Examples**: `terminal`, `process`, `read_file`,
    `patch`, **Description**: Execute commands and manipulate files.'
  status: supported
  confidence: null
- id: category-browser-examples-browser-navigate
  text: 'Category**: **Browser**, **Examples**: `browser_navigate`, `browser_snapshot`,
    `browser_vision`, **Description**: Interactive browser automation with text and
    vision support.'
  status: supported
  confidence: null
- id: category-media-examples-vision-analyze-imag
  text: 'Category**: **Media**, **Examples**: `vision_analyze`, `image_generate`,
    `text_to_speech`, **Description**: Multimodal analysis and generation.'
  status: supported
  confidence: null
- id: category-agent-orchestration-examples-todo
  text: 'Category**: **Agent orchestration**, **Examples**: `todo`, `clarify`, `execute_code`,
    `delegate_task`, **Description**: Planning, clarification, code execution, and
    subagent delegation.'
  status: supported
  confidence: null
- id: category-memory-recall-examples-memory-se
  text: 'Category**: **Memory & recall**, **Examples**: `memory`, `session_search`,
    **Description**: Persistent memory and session search.'
  status: supported
  confidence: null
- id: category-automation-delivery-examples-cronjo
  text: 'Category**: **Automation & delivery**, **Examples**: `cronjob`, `send_message`,
    **Description**: Scheduled tasks with create/list/update/pause/resume/run/remove
    actions, plus outbound messaging delivery.'
  status: supported
  confidence: null
- id: category-integrations-examples-ha-mcp-serv
  text: 'Category**: **Integrations**, **Examples**: `ha_*`, MCP server tools, `rl_*`,
    **Description**: Home Assistant, MCP, RL training, and other integrations.'
  status: supported
  confidence: null
- id: backend-description-use-case
  text: Backend**, **Description**, **Use Case**
  status: supported
  confidence: null
- id: backend-local-description-run-on-your-machine-de
  text: 'Backend**: `local`, **Description**: Run on your machine (default), **Use
    Case**: Development, trusted tasks'
  status: supported
  confidence: null
- id: backend-docker-description-isolated-containers
  text: 'Backend**: `docker`, **Description**: Isolated containers, **Use Case**:
    Security, reproducibility'
  status: supported
  confidence: null
- id: backend-ssh-description-remote-server-use-case
  text: 'Backend**: `ssh`, **Description**: Remote server, **Use Case**: Sandboxing,
    keep agent away from its own code'
  status: supported
  confidence: null
- id: backend-singularity-description-hpc-containers
  text: 'Backend**: `singularity`, **Description**: HPC containers, **Use Case**:
    Cluster computing, rootless'
  status: supported
  confidence: null
- id: backend-modal-description-cloud-execution-use
  text: 'Backend**: `modal`, **Description**: Cloud execution, **Use Case**: Serverless,
    scale'
  status: supported
  confidence: null
- id: backend-daytona-description-cloud-sandbox-workspa
  text: 'Backend**: `daytona`, **Description**: Cloud sandbox workspace, **Use Case**:
    Persistent remote dev environments'
  status: supported
  confidence: null
- id: read-only-root-filesystem-docker
  text: Read-only root filesystem (Docker)
  status: supported
  confidence: null
- id: all-linux-capabilities-dropped
  text: All Linux capabilities dropped
  status: supported
  confidence: null
- id: no-privilege-escalation
  text: No privilege escalation
  status: supported
  confidence: null
- id: pid-limits-256-processes
  text: PID limits (256 processes)
  status: supported
  confidence: null
- id: full-namespace-isolation
  text: Full namespace isolation
  status: supported
  confidence: null
- id: persistent-workspace-via-volumes-not-writable-root-layer
  text: Persistent workspace via volumes, not writable root layer
  status: supported
  confidence: null
---

Tools are functions that extend the agent's capabilities. They're organized into logical **toolsets** that can be enabled or disabled per platform.

## Available Tools[​](#available-tools "Direct link to Available Tools")

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[entities/features-overview|features-overview]]
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

Hermes ships with a broad built-in tool registry covering web search, browser automation, terminal execution, file editing, memory, delegation, RL training, messaging delivery, Home Assistant, and more.

note

**Honcho cross-session memory** is available as a memory provider plugin (`plugins/memory/honcho/`), not as a built-in toolset. See [Plugins](/docs/user-guide/features/plugins) for installation.

High-level categories:

- **Category**, **Examples**, **Description**
- **Category**: **Web**, **Examples**: `web_search`, `web_extract`, **Description**: Search the web and extract page content.
- **Category**: **Terminal & Files**, **Examples**: `terminal`, `process`, `read_file`, `patch`, **Description**: Execute commands and manipulate files.
- **Category**: **Browser**, **Examples**: `browser_navigate`, `browser_snapshot`, `browser_vision`, **Description**: Interactive browser automation with text and vision support.
- **Category**: **Media**, **Examples**: `vision_analyze`, `image_generate`, `text_to_speech`, **Description**: Multimodal analysis and generation.
- **Category**: **Agent orchestration**, **Examples**: `todo`, `clarify`, `execute_code`, `delegate_task`, **Description**: Planning, clarification, code execution, and subagent delegation.
- **Category**: **Memory & recall**, **Examples**: `memory`, `session_search`, **Description**: Persistent memory and session search.
- **Category**: **Automation & delivery**, **Examples**: `cronjob`, `send_message`, **Description**: Scheduled tasks with create/list/update/pause/resume/run/remove actions, plus outbound messaging delivery.
- **Category**: **Integrations**, **Examples**: `ha_*`, MCP server tools, `rl_*`, **Description**: Home Assistant, MCP, RL training, and other integrations.

For the authoritative code-derived registry, see [Built-in Tools Reference](/docs/reference/tools-reference) and [Toolsets Reference](/docs/reference/toolsets-reference).

Nous Tool Gateway

Paid [Nous Portal](https://portal.nousresearch.com) subscribers can use web search, image generation, TTS, and browser automation through the **[Tool Gateway](/docs/user-guide/features/tool-gateway)** — no separate API keys needed. Run `hermes model` to enable it, or configure individual tools with `hermes tools`.

## Using Toolsets[​](#using-toolsets "Direct link to Using Toolsets")

```
# Use specific toolsets
hermes chat --toolsets "web,terminal"

# See all available tools
hermes tools

# Configure tools per platform (interactive)
hermes tools
```

Common toolsets include `web`, `terminal`, `file`, `browser`, `vision`, `image_gen`, `moa`, `skills`, `tts`, `todo`, `memory`, `session_search`, `cronjob`, `code_execution`, `delegation`, `clarify`, `homeassistant`, and `rl`.

See [Toolsets Reference](/docs/reference/toolsets-reference) for the full set, including platform presets such as `hermes-cli`, `hermes-telegram`, and dynamic MCP toolsets like `mcp-<server>`.

## Terminal Backends[​](#terminal-backends "Direct link to Terminal Backends")

The terminal tool can execute commands in different environments:

- **Backend**, **Description**, **Use Case**
- **Backend**: `local`, **Description**: Run on your machine (default), **Use Case**: Development, trusted tasks
- **Backend**: `docker`, **Description**: Isolated containers, **Use Case**: Security, reproducibility
- **Backend**: `ssh`, **Description**: Remote server, **Use Case**: Sandboxing, keep agent away from its own code
- **Backend**: `singularity`, **Description**: HPC containers, **Use Case**: Cluster computing, rootless
- **Backend**: `modal`, **Description**: Cloud execution, **Use Case**: Serverless, scale
- **Backend**: `daytona`, **Description**: Cloud sandbox workspace, **Use Case**: Persistent remote dev environments

### Configuration[​](#configuration "Direct link to Configuration")

```
# In ~/.hermes/config.yaml
terminal:
  backend: local    # or: docker, ssh, singularity, modal, daytona
  cwd: "."          # Working directory
  timeout: 180      # Command timeout in seconds
```

### Docker Backend[​](#docker-backend "Direct link to Docker Backend")

```
terminal:
  backend: docker
  docker_image: python:3.11-slim
```

### SSH Backend[​](#ssh-backend "Direct link to SSH Backend")

Recommended for security — agent can't modify its own code:

```
terminal:
  backend: ssh
```

```
# Set credentials in ~/.hermes/.env
TERMINAL_SSH_HOST=my-server.example.com
TERMINAL_SSH_USER=myuser
TERMINAL_SSH_KEY=~/.ssh/id_rsa
```

### Singularity/Apptainer[​](#singularityapptainer "Direct link to Singularity/Apptainer")

```
# Pre-build SIF for parallel workers
apptainer build ~/python.sif docker://python:3.11-slim

# Configure
hermes config set terminal.backend singularity
hermes config set terminal.singularity_image ~/python.sif
```

### Modal (Serverless Cloud)[​](#modal-serverless-cloud "Direct link to Modal (Serverless Cloud)")

```
uv pip install modal
modal setup
hermes config set terminal.backend modal
```

### Container Resources[​](#container-resources "Direct link to Container Resources")

Configure CPU, memory, disk, and persistence for all container backends:

```
terminal:
  backend: docker  # or singularity, modal, daytona
  container_cpu: 1              # CPU cores (default: 1)
  container_memory: 5120        # Memory in MB (default: 5GB)
  container_disk: 51200         # Disk in MB (default: 50GB)
  container_persistent: true    # Persist filesystem across sessions (default: true)
```

When `container_persistent: true`, installed packages, files, and config survive across sessions.

### Container Security[​](#container-security "Direct link to Container Security")

All container backends run with security hardening:

- Read-only root filesystem (Docker)
- All Linux capabilities dropped
- No privilege escalation
- PID limits (256 processes)
- Full namespace isolation
- Persistent workspace via volumes, not writable root layer

Docker can optionally receive an explicit env allowlist via `terminal.docker_forward_env`, but forwarded variables are visible to commands inside the container and should be treated as exposed to that session.

## Background Process Management[​](#background-process-management "Direct link to Background Process Management")

Start background processes and manage them:

```
terminal(command="pytest -v tests/", background=true)
# Returns: {"session_id": "proc_abc123", "pid": 12345}

# Then manage with the process tool:
process(action="list")       # Show all running processes
process(action="poll", session_id="proc_abc123")   # Check status
process(action="wait", session_id="proc_abc123")   # Block until done
process(action="log", session_id="proc_abc123")    # Full output
process(action="kill", session_id="proc_abc123")   # Terminate
process(action="write", session_id="proc_abc123", data="y")  # Send input
```

PTY mode (`pty=true`) enables interactive CLI tools like Codex and Claude Code.

## Sudo Support[​](#sudo-support "Direct link to Sudo Support")

If a command needs sudo, you'll be prompted for your password (cached for the session). Or set `SUDO_PASSWORD` in `~/.hermes/.env`.

warning

On messaging platforms, if sudo fails, the output includes a tip to add `SUDO_PASSWORD` to `~/.hermes/.env`.