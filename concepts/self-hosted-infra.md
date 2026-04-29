---
title: Self Hosted Infra
id: concept.self-hosted-infra
pageType: concept
sourceIds:
  - MEMORY.md
updatedAt: 2026-04-22
claims:
  - id: environments
---
# Self-Hosted Infrastructure

Concepts and patterns for the self-hosted setup.

## Active Services

| Service | Port | Notes |
|---------|------|-------|
| lolok site | 5001 | Docker container, CI/CD via GitHub Actions |
| Static files | 8080 | python http.server, may need restart |

## GitHub Runners
- `lolok-runner` — for lolok site deployment

## Networking
- LXC container running on Proxmox (unprivileged)
- SMB server at 10.0.7.227 (UniFi) — personal drive accessible
- Can't mount CIFS directly in LXC (unprivileged container restriction)

## Related
- [[entities/lolok-site]]

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[concepts/index|Concepts]]
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]

### Related Pages
- [[entities/honda-civic-2016-ex-t-maintenance|Honda Civic 2016 EX-T Maintenance]]
- [[entities/lolok-site|lolok Site]]
- [[entities/lost-lands-2026|Lost Lands 2026]]
- [[entities/macvm|macvm]]
- [[entities/randomstix-health|Randomstix Health]]
- [[entities/randomstix|Quoc Vu]]
- [[concepts/anomem-postmortem|Anomem Postmortem]]
- [[concepts/project-guidelines|Project Guidelines]]
- [[concepts/prompt-weapon-generator-game|Prompt Weapon Generator Game]]
<!-- openclaw:wiki:related:end -->
