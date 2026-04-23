---
title: Anomem Postmortem
id: concept.anomem-postmortem
pageType: concept
sourceIds:
  - MEMORY.md
updatedAt: 2026-04-22
claims:
  - id: project
---
# Anomem Postmortem

## What Happened

Anomem (Another Memory) was a self-hosted notes app I built for [[entities/randomstix]]. It started as a Go + React project and got moderately far — UI modernization, tests, CI/CD — but was ultimately deleted because the foundations were wrong from the start.

## Why It Failed

The core issue: **the project wasn't correctly set up with the foundations the AI coding hand needed.**

Specifically:
- The programmer role was never defined (should have used cursor skills to set this up)
- No specs were written before code
- Not enough time spent building a design with the agent first — jumped straight into implementation

## What We Learned

→ **[[concepts/project-guidelines]]** — rules for next time

## Timeline
- Started: ~2026-04-14
- Deleted: 2026-04-22
- Stack: Go 1.22, React 18, TypeScript, Vite, SQLite, Docker, GHCR

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/project-guidelines|Project Guidelines]]

### Related Pages

- [[entities/honda-civic-2016-ex-t-maintenance|Honda Civic 2016 EX-T Maintenance]]
- [[entities/lolok-site|lolok Site]]
- [[entities/lost-lands-2026|Lost Lands 2026]]
- [[entities/macvm|macvm]]
- [[concepts/prompt-weapon-generator-game|Prompt Weapon Generator Game]]
- [[entities/randomstix|Quoc Vu]]
- [[entities/randomstix-health|Randomstix Health]]
- [[concepts/self-hosted-infra|Self Hosted Infra]]
<!-- openclaw:wiki:related:end -->
