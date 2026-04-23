---
title: Quoc Vu
id: entity.randomstix
pageType: entity
sourceIds:
  - USER.md
  - MEMORY.md
updatedAt: 2026-04-22
claims:
  - id: name
    text: "Name is randomstix"
    confidence: high
    evidence:
      - sourceId: USER.md
        path: workspace/USER.md
  - id: email
    text: "Email is quocvu2640@gmail.com"
    confidence: high
    evidence:
      - sourceId: USER.md
        path: workspace/USER.md
  - id: discord-handle
    text: "Contact via Discord #general"
    confidence: high
    evidence:
      - sourceId: USER.md
        path: workspace/USER.md
  - id: timezone
    text: "America/New_York (EDT/EST)"
    confidence: high
    evidence:
      - sourceId: USER.md
        path: workspace/USER.md
---

# Randomstix

The human I'm assisting. Contact via Discord for general communication.

## Wiki Behavior
- **Proactive documentation**: Racoony updates wiki/MEMORY.md proactively without being asked when notable things come up in conversation
- Racoony shows the user exactly what changed in the files when documenting
- Racoony lets the user know when something has been saved to the wiki
- **File storage**: Documents ≤100MB → wiki vault `_attachments/`. Larger → media folder + file proxy.

## Monitoring Tasks
- **Bridge mode fix**: Watch GitHub issues #65976, #63092, #65092. When resolved, switch to QMD + bridge mode and verify it works. Remind user of the switch.
- **Email summaries**: subject + short body summary + sender
- **Meme shorthand**: "Find Meme: <query>" → fetch GIF results
- **File URLs**: served from https://openclaw.plainrandom.com/file/ → maps to workspace/media/

## Projects
- [[entities/lolok-site]]

## Assets
- [[entities/honda-civic-2016-ex-t-maintenance|Honda Civic 2016 EX-T]] — license plate KEH7484, ~150k miles, oil recently changed

## Interests
- Music festivals (Lost Lands 2026 confirmed)
- Self-hosted infrastructure

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By

- [[concepts/anomem-postmortem|Anomem Postmortem]]
- [[entities/lost-lands-2026|Lost Lands 2026]]
- [[syntheses/racoony-ops|Raccoony Operations]]

### Related Pages

- [[entities/honda-civic-2016-ex-t-maintenance|Honda Civic 2016 EX-T Maintenance]]
- [[entities/lexus-rx-350-2017|Lexus RX 350 2017]]
- [[entities/lolok-site|lolok Site]]
- [[entities/macvm|macvm]]
- [[concepts/project-guidelines|Project Guidelines]]
- [[concepts/prompt-weapon-generator-game|Prompt Weapon Generator Game]]
- [[entities/randomstix-health|Randomstix Health]]
- [[concepts/self-hosted-infra|Self Hosted Infra]]
<!-- openclaw:wiki:related:end -->
