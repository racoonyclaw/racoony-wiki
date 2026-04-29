---
pageType: entity
id: entity.nix-nixos-setup
title: Nix & NixOS Setup
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/nix-nixos-setup.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/nix-nixos-setup.md
updatedAt: '2026-04-24T15:05:26.449607+00:00'
sourceIds:
- openrouterai
- mcpexamplecom
- mcpexamplecom
sources:
- sourceId: openrouterai
  sourceType: web
  sourcePath: https://openrouter.ai/api/v1
  title: openrouter.ai
- sourceId: mcpexamplecom
  sourceType: web
  sourcePath: https://mcp.example.com/v1/mcp
  title: mcp.example.com
- sourceId: mcpexamplecom
  sourceType: web
  sourcePath: https://mcp.example.com/mcp
  title: mcp.example.com
claims:
- id: pre-built-binary-with-all-deps-then-use-the-standard-cli-w
  text: "Pre-built binary with all deps \u2014 then use the standard CLI workflow"
  status: supported
  confidence: null
- id: declarative-config-hardened-systemd-service-managed-secret
  text: Declarative config, hardened systemd service, managed secrets
  status: supported
  confidence: null
- id: everything-above-plus-a-persistent-ubuntu-container-where-t
  text: Everything above, plus a persistent Ubuntu container where the agent can apt/pip/npm
    install
  status: supported
  confidence: null
- id: nix-with-flakes-enabled-determinate-nix-recommended-enabl
  text: "Nix with flakes enabled \u2014 Determinate Nix recommended (enables flakes\
    \ by default)"
  status: supported
  confidence: null
- id: api-keys-for-the-services-you-want-to-use-at-minimum-an-op
  text: 'API keys for the services you want to use (at minimum: an OpenRouter or Anthropic
    key)'
  status: supported
  confidence: null
- id: hardened-systemd-service-on-the-host
  text: Hardened systemd service on the host
  status: supported
  confidence: null
- id: nonewprivileges-protectsystemstrict-privatetmp
  text: NoNewPrivileges, ProtectSystem=strict, PrivateTmp
  status: supported
  confidence: null
- id: agent-cannot-self-install-packages
  text: Agent cannot self-install packages
  status: supported
  confidence: null
- id: persistent-ubuntu-container-with-nixstore-bind-mounted
  text: Persistent Ubuntu container with /nix/store bind-mounted
  status: supported
  confidence: null
- id: container-isolation-runs-as-unprivileged-user-inside
  text: Container isolation, runs as unprivileged user inside
  status: supported
  confidence: null
- id: agent-can-self-install-packages-apt-pip-npm-installs-pers
  text: Agent CAN self-install packages (apt, pip, npm installs persist across restarts)
  status: supported
  confidence: null
- id: change-the-llm-model-settingsmodeldefault-anthropi
  text: Change the LLM model:** `settings.model.default` = "anthropic/claude-sonnet-4"
  status: supported
  confidence: null
- id: use-a-different-provider-endpoint-settingsmodelbase-ur
  text: Use a different provider endpoint:** `settings.model.base_url` = "https://openrouter.ai/api/v1"
  status: supported
  confidence: null
- id: add-api-keys-environmentfiles-with-sops-nix-or-agenix
  text: Add API keys:** `environmentFiles` with sops-nix or agenix
  status: supported
  confidence: null
- id: give-the-agent-a-personality-manage-statedirhermess
  text: Give the agent a personality:** Manage ${stateDir}/.hermes/SOUL.md directly
  status: supported
  confidence: null
- id: add-mcp-tool-servers-mcpserversname
  text: Add MCP tool servers:** `mcpServers.<name>`
  status: supported
  confidence: null
- id: mount-host-directories-into-container-containerextravol
  text: Mount host directories into container:** `container.extraVolumes`
  status: supported
  confidence: null
- id: pass-gpu-access-to-container-containerextraoptions-wit
  text: Pass GPU access to container:** `container.extraOptions` with "--gpus" "all"
  status: supported
  confidence: null
- id: use-podman-instead-of-docker-containerbackend-podma
  text: Use Podman instead of Docker:** `container.backend` = "podman"
  status: supported
  confidence: null
- id: share-state-between-host-cli-and-container-containerhos
  text: Share state between host CLI and container:** `container.hostUsers`
  status: supported
  confidence: null
- id: hermes-setup-config-is-declarative
  text: "`hermes setup` \u2014 Config is declarative"
  status: supported
  confidence: null
- id: hermes-config-edit-config-is-generated-from-settings
  text: "`hermes config edit` \u2014 Config is generated from settings"
  status: supported
  confidence: null
- id: hermes-config-set-key-value-config-is-generated-from
  text: "`hermes config set <key> <value>` \u2014 Config is generated from settings"
  status: supported
  confidence: null
- id: hermes-gateway-install-the-systemd-service-is-managed-by
  text: "`hermes gateway install` \u2014 The systemd service is managed by NixOS"
  status: supported
  confidence: null
- id: hermes-gateway-uninstall-the-systemd-service-is-managed
  text: "`hermes gateway uninstall` \u2014 The systemd service is managed by NixOS"
  status: supported
  confidence: null
- id: systemctl-restart-hermes-agent-container-not-recreated-a
  text: '`systemctl restart hermes-agent`: Container NOT recreated, all state persists'
  status: supported
  confidence: null
- id: nixos-rebuild-switch-code-change-container-not-recreate
  text: '`nixos-rebuild switch` (code change): Container NOT recreated (symlink updated),
    all state persists'
  status: supported
  confidence: null
- id: host-reboot-container-not-recreated-all-state-persists
  text: '`Host reboot`: Container NOT recreated, all state persists'
  status: supported
  confidence: null
- id: nix-collect-garbage-container-not-recreated-gc-root-al
  text: '`nix-collect-garbage`: Container NOT recreated (GC root), all state persists'
  status: supported
  confidence: null
- id: image-change-containerimage-container-is-recreated-d
  text: '`Image change (container.image)`: Container IS recreated, /data and /home/hermes
    persist, writable layer LOST'
  status: supported
  confidence: null
- id: environmentenvironmentfiles-change-container-not-recreat
  text: '`environment/environmentFiles change`: Container NOT recreated, all state
    persists'
  status: supported
  confidence: null
- id: cannot-save-configuration-managed-by-nixos-edit-configu
  text: "Cannot save configuration: managed by NixOS** \u2014 Edit configuration.nix\
    \ and nixos-rebuild switch"
  status: supported
  confidence: null
- id: container-recreated-unexpectedly-expected-writable-lay
  text: "Container recreated unexpectedly** \u2014 Expected \u2014 writable layer\
    \ resets. Reinstall packages or use a custom image"
  status: supported
  confidence: null
- id: hermes-version-shows-old-version-container-not-restarted
  text: "hermes version shows old version** \u2014 Container not restarted \u2014\
    \ systemctl restart hermes-agent"
  status: supported
  confidence: null
- id: permission-denied-on-varlibhermes-use-docker-exec-or
  text: "Permission denied on /var/lib/hermes** \u2014 Use docker exec or sudo -u\
    \ hermes"
  status: supported
  confidence: null
- id: nix-collect-garbage-removed-hermes-gc-root-missing-res
  text: "nix-collect-garbage removed hermes** \u2014 GC root missing \u2014 Restart\
    \ the service"
  status: supported
  confidence: null
- id: no-container-with-name-or-id-hermes-agent-podman-add
  text: "no container with name or ID \"hermes-agent\" (Podman)** \u2014 Add passwordless\
    \ sudo for podman"
  status: supported
  confidence: null
---

# Nix & NixOS Setup

Hermes Agent ships a Nix flake with three levels of integration:

**Level 1: nix run / nix profile install** (Any Nix user - macOS, Linux)
- Pre-built binary with all deps — then use the standard CLI workflow

**Level 2: NixOS module (native)** (NixOS server deployments)
- Declarative config, hardened systemd service, managed secrets

**Level 3: NixOS module (container)** (Agents that need self-modification)
- Everything above, plus a persistent Ubuntu container where the agent can apt/pip/npm install

## WHAT'S DIFFERENT FROM THE STANDARD INSTALL

The curl | bash installer manages Python, Node, and dependencies itself. The Nix flake replaces all of that — every Python dependency is a Nix derivation built by uv2nix, and runtime tools (Node.js, git, ripgrep, ffmpeg) are wrapped into the binary's PATH. There is no runtime pip, no venv activation, no npm install.

For non-NixOS users, this only changes the install step. Everything after (`hermes setup`, `hermes gateway install`, config editing) works identically to the standard install.

For NixOS module users, the entire lifecycle is different: configuration lives in configuration.nix, secrets go through sops-nix/agenix, the service is a systemd unit, and CLI config commands are blocked. You manage hermes the same way you manage any other NixOS service.

## Prerequisites

- Nix with flakes enabled — Determinate Nix recommended (enables flakes by default)
- API keys for the services you want to use (at minimum: an OpenRouter or Anthropic key)

## Quick Start (Any Nix User)

No clone needed. Nix fetches, builds, and runs everything:

```
# Run directly (builds on first use, cached after)
nix run github:NousResearch/hermes-agent -- setup
nix run github:NousResearch/hermes-agent -- chat

# Or install persistently
nix profile install github:NousResearch/hermes-agent
hermes setup
hermes chat
```

After `nix profile install`, `hermes`, `hermes-agent`, and `hermes-acp` are on your PATH. From here, the workflow is identical to the standard [[entities/installation|Installation]] — `hermes setup` walks you through provider selection, `hermes gateway install` sets up a launchd (macOS) or systemd user service, and config lives in `~/.hermes/`.

## NixOS Module

The flake exports `nixosModules.default` — a full NixOS service module that declaratively manages user creation, directories, config generation, secrets, documents, and service lifecycle.

NOTE: This module requires NixOS. For non-NixOS systems (macOS, other Linux distros), use `nix profile install` and the standard CLI workflow above.

**Add the Flake Input:**

```nix
# /etc/nixos/flake.nix (or your system flake)
{
  inputs = {
    nixpkgs.url = "github:NixOS/nixpkgs/nixos-unstable";
    hermes-agent.url = "github:NousResearch/hermes-agent";
  };

  outputs = { nixpkgs, hermes-agent, ... }: {
    nixosConfigurations.your-host = nixpkgs.lib.nixosSystem {
      system = "x86_64-linux";
      modules = [
        hermes-agent.nixosModules.default
        ./configuration.nix
      ];
    };
  };
}
```

**Minimal Configuration:**

```nix
# configuration.nix
{ config, ... }: {
  services.hermes-agent = {
    enable = true;
    settings.model.default = "anthropic/claude-sonnet-4";
    environmentFiles = [ config.sops.secrets."hermes-env".path ];
    addToSystemPackages = true;
  };
}
```

That's it. `nixos-rebuild switch` creates the hermes user, generates config.yaml, wires up secrets, and starts the gateway — a long-running service that connects the agent to messaging platforms (Telegram, Discord, etc.) and listens for incoming messages.

SECRETS ARE REQUIRED: The environmentFiles line above assumes you have sops-nix or agenix configured. The file should contain at least one LLM provider key (e.g., OPENROUTER_API_KEY=sk-or-...). See Secrets Management for full setup.

ADDTOSYSTEMPACKAGES: Setting `addToSystemPackages = true` does two things: puts the hermes CLI on your system PATH and sets HERMES_HOME system-wide so the interactive CLI shares state (sessions, skills, cron) with the gateway service. Without it, running hermes in your shell creates a separate `~/.hermes/` directory.

CONTAINER-AWARE CLI: When `container.enable = true` and `addToSystemPackages = true`, every hermes command on the host automatically routes into the managed container. This means your interactive CLI session runs inside the same environment as the gateway service.

## Verify It Works

After `nixos-rebuild switch`, check that the service is running:

```
# Check service status
systemctl status hermes-agent

# Watch logs (Ctrl+C to stop)
journalctl -u hermes-agent -f

# If addToSystemPackages is true, test the CLI
hermes version
hermes config       # shows the generated config
```

## Choosing a Deployment Mode

The module supports two modes, controlled by `container.enable`:

**Native (default):**
- Hardened systemd service on the host
- NoNewPrivileges, ProtectSystem=strict, PrivateTmp
- Agent cannot self-install packages

**Container:**
- Persistent Ubuntu container with /nix/store bind-mounted
- Container isolation, runs as unprivileged user inside
- Agent CAN self-install packages (apt, pip, npm installs persist across restarts)

To enable container mode, add one line:

```nix
{
  services.hermes-agent = {
    enable = true;
    container.enable = true;
    # ... rest of config is identical
  };
}
```

## Configuration

**Declarative Settings:** The `settings` option accepts an arbitrary attrset that is rendered as config.yaml. It supports deep merging across multiple module definitions.

**Model Naming:** `settings.model.default` uses the model identifier your provider expects. With OpenRouter (the default), these look like "anthropic/claude-sonnet-4" or "google/gemini-3-flash".

**Discovering Available Config Keys:** Run `nix build .#configKeys && cat result` to see every leaf config key extracted from Python's DEFAULT_CONFIG.

**Escape Hatch: Bring Your Own Config:** Use `configFile` to bypass settings entirely:

```nix
services.hermes-agent.configFile = /etc/hermes/config.yaml;
```

## Customization Cheatsheet

- **Change the LLM model:** `settings.model.default` = "anthropic/claude-sonnet-4"
- **Use a different provider endpoint:** `settings.model.base_url` = "https://openrouter.ai/api/v1"
- **Add API keys:** `environmentFiles` with sops-nix or agenix
- **Give the agent a personality:** Manage ${stateDir}/.hermes/SOUL.md directly
- **Add MCP tool servers:** `mcpServers.<name>`
- **Mount host directories into container:** `container.extraVolumes`
- **Pass GPU access to container:** `container.extraOptions` with "--gpus" "all"
- **Use Podman instead of Docker:** `container.backend` = "podman"
- **Share state between host CLI and container:** `container.hostUsers`

## Secrets Management

**NEVER PUT API KEYS IN settings OR environment** — Values in Nix expressions end up in /nix/store, which is world-readable. Always use environmentFiles with a secrets manager.

Both environment (non-secret vars) and environmentFiles (secret files) are merged into `$HERMES_HOME/.env` at activation time.

**sops-nix example:**

```nix
{
  sops = {
    defaultSopsFile = ./secrets/hermes.yaml;
    age.keyFile = "/home/user/.config/sops/age/keys.txt";
    secrets."hermes-env" = { format = "yaml"; };
  };

  services.hermes-agent.environmentFiles = [
    config.sops.secrets."hermes-env".path
  ];
}
```

## MCP Servers

**Stdio Transport (Local Servers):**

```nix
services.hermes-agent.mcpServers = {
  filesystem = {
    command = "npx";
    args = [ "-y" "@modelcontextprotocol/server-filesystem" "/data/workspace" ];
  };
  github = {
    command = "npx";
    args = [ "-y" "@modelcontextprotocol/server-github" ];
    env.GITHUB_PERSONAL_ACCESS_TOKEN = "\${GITHUB_TOKEN}";
  };
};
```

**HTTP Transport (Remote Servers):**

```nix
services.hermes-agent.mcpServers.remote-api = {
  url = "https://mcp.example.com/v1/mcp";
  headers.Authorization = "Bearer \${MCP_REMOTE_API_KEY}";
  timeout = 180;
};
```

**HTTP Transport with OAuth:**

```nix
services.hermes-agent.mcpServers.my-oauth-server = {
  url = "https://mcp.example.com/mcp";
  auth = "oauth";
};
```

## Managed Mode

When hermes runs via the NixOS module, the following CLI commands are blocked:

- `hermes setup` — Config is declarative
- `hermes config edit` — Config is generated from settings
- `hermes config set <key> <value>` — Config is generated from settings
- `hermes gateway install` — The systemd service is managed by NixOS
- `hermes gateway uninstall` — The systemd service is managed by NixOS

## Container Architecture

When container mode is enabled, hermes runs inside a persistent Ubuntu container with the Nix-built binary bind-mounted read-only from the host.

**What Persists Across What:**

- `systemctl restart hermes-agent`: Container NOT recreated, all state persists
- `nixos-rebuild switch` (code change): Container NOT recreated (symlink updated), all state persists
- `Host reboot`: Container NOT recreated, all state persists
- `nix-collect-garbage`: Container NOT recreated (GC root), all state persists
- `Image change (container.image)`: Container IS recreated, /data and /home/hermes persist, writable layer LOST
- `environment/environmentFiles change`: Container NOT recreated, all state persists

## Development

**Dev Shell:**

```bash
cd hermes-agent
nix develop
# Shell provides: Python 3.11 + uv, Node.js 20, ripgrep, git, openssh, ffmpeg
hermes setup
hermes chat
```

**direnv (Recommended):**

```bash
cd hermes-agent
direnv allow    # one-time
# Subsequent entries are near-instant (stamp file skips dep install)
```

**Flake Checks:**

```bash
# Run all checks
nix flake check

# Individual checks
nix build .#checks.x86_64-linux.package-contents
nix build .#checks.x86_64-linux.entry-points-sync
nix build .#checks.x86_64-linux.cli-commands
nix build .#checks.x86_64-linux.managed-guard
nix build .#checks.x86_64-linux.bundled-skills
nix build .#checks.x86_64-linux.config-roundtrip
```

## Troubleshooting

**Service Logs:**

```bash
journalctl -u hermes-agent -f
# Container mode: also available directly
docker logs -f hermes-agent
```

**Force Container Recreation:**

```bash
sudo systemctl stop hermes-agent
docker rm -f hermes-agent
sudo rm /var/lib/hermes/.container-identity
sudo systemctl start hermes-agent
```

**Verify Secrets Are Loaded:**

```bash
# Native mode
sudo -u hermes cat /var/lib/hermes/.hermes/.env

# Container mode
docker exec hermes-agent cat /data/.hermes/.env
```

**Common Issues:**

- **Cannot save configuration: managed by NixOS** — Edit configuration.nix and nixos-rebuild switch
- **Container recreated unexpectedly** — Expected — writable layer resets. Reinstall packages or use a custom image
- **hermes version shows old version** — Container not restarted — systemctl restart hermes-agent
- **Permission denied on /var/lib/hermes** — Use docker exec or sudo -u hermes
- **nix-collect-garbage removed hermes** — GC root missing — Restart the service
- **no container with name or ID "hermes-agent" (Podman)** — Add passwordless sudo for podman