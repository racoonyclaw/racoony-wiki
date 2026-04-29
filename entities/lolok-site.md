---
title: lolok Site
id: entity.lolok-site
pageType: entity
sourceIds:
  - MEMORY.md
updatedAt: 2026-04-22
claims:
  - id: type
    text: "Web application running in Docker container"
    confidence: high
    evidence:
      - sourceId: MEMORY.md
        path: workspace/MEMORY.md
  - id: port
    text: "Live container at port 5001"
    confidence: high
    evidence:
      - sourceId: MEMORY.md
        path: workspace/MEMORY.md
  - id: deployment
    text: "CI/CD via GitHub Actions + self-hosted runner (lolok-runner)"
    confidence: high
    evidence:
      - sourceId: MEMORY.md
        path: workspace/MEMORY.md
  - id: static-server
    text: "Static file server was on port 8080, may need restart"
    confidence: medium
    evidence:
      - sourceId: MEMORY.md
        path: workspace/MEMORY.md
---

# lolok Site

Web application deployed via GitHub Actions to a self-hosted runner.

## Infrastructure
- **Container**: Docker, port 5001
- **CI/CD**: GitHub Actions + self-hosted runner (`lolok-runner`)
- **Static files**: port 8080 (python http.server — may be killed)

## Status
Active deployment. Static file server may need restart if serving files is needed.

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[entities/index|Entities]]
- [[entities/randomstix|Quoc Vu]]
- [[concepts/self-hosted-infra|Self Hosted Infra]]
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]

### Related Pages
- [[entities/honda-civic-2016-ex-t-maintenance|Honda Civic 2016 EX-T Maintenance]]
- [[entities/lost-lands-2026|Lost Lands 2026]]
- [[entities/macvm|macvm]]
- [[entities/randomstix-health|Randomstix Health]]
- [[concepts/anomem-postmortem|Anomem Postmortem]]
- [[concepts/project-guidelines|Project Guidelines]]
- [[concepts/prompt-weapon-generator-game|Prompt Weapon Generator Game]]
<!-- openclaw:wiki:related:end -->
