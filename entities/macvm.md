---
title: macvm
id: entity.macvm
pageType: entity
sourceIds:
  - MEMORY.md
updatedAt: 2026-04-22
claims: []
---

**Hostname:** littlevm
**IP:** 10.0.3.202
**Type:** macOS VM (Darwin 24.6.0, x86_64)
**Credentials:** user `littlevm`, password `1234`

## Specs
- 4 cores, 8GB RAM, 80GB disk
- Homebrew installed (/usr/local/bin/brew — v5.1.7)
- tmux available at /usr/local/bin/tmux

## Software Installed
- **Obsidian** (1.12.7) — installed via Homebrew cask, app at /Applications/Obsidian.app, CLI at /usr/local/bin/obsidian
- **tmux** session `racoony` — running (created Wed Apr 22 10:20:58 2026)

## Role in Setup
- Migration target for the OpenClaw agent (from Proxmox LXC 10.0.3.130)
- When migration happens: copy ~/.openclaw workspace, credentials, config, install skills, re-register cron jobs

## Notes
- Do NOT access Passwords app / keychain — user explicitly blocked this
- Shell is zsh, not bash
- tmux session `racoony` persists and can be used for user visibility

## Connection
```bash
sshpass -p '1234' ssh littlevm@10.0.3.202
# Then use: /usr/local/bin/tmux send-keys -t racoony 'command' Enter
# And: /usr/local/bin/tmux capture-pane -t racoony -p
```

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[entities/index|Entities]]
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]

### Related Pages
- [[entities/honda-civic-2016-ex-t-maintenance|Honda Civic 2016 EX-T Maintenance]]
- [[entities/lolok-site|lolok Site]]
- [[entities/lost-lands-2026|Lost Lands 2026]]
- [[entities/randomstix-health|Randomstix Health]]
- [[entities/randomstix|Quoc Vu]]
- [[concepts/anomem-postmortem|Anomem Postmortem]]
- [[concepts/project-guidelines|Project Guidelines]]
- [[concepts/prompt-weapon-generator-game|Prompt Weapon Generator Game]]
- [[concepts/self-hosted-infra|Self Hosted Infra]]
<!-- openclaw:wiki:related:end -->
