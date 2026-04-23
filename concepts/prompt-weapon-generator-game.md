---
title: Prompt Weapon Generator Game
id: concept.prompt-weapon-generator-game
pageType: concept
sourceIds:
  - MEMORY.md
updatedAt: 2026-04-22
claims:
  - id: core-mechanic
---
# Prompt Weapon Generator Game

## Concept
A game where players write prompts to generate tools/weapons and use them to complete objectives. The goal is to tap into creative minds (especially kids) by letting them describe literally anything.

**Core Mechanic:** Player writes a freeform prompt → AI interprets it → generates a described item with stat modifiers and side effects.

## Game Modes

### Single Player / Level-Based
- Navigate a character (2D scroller or 3D third-person) to reach an objective
- Objective: reach a location, kill X monsters, solve a puzzle
- Levels have **constraints** that limit what can be created
- Creativity is the puzzle-solving mechanism

### PvP Rounds
- Each player writes a weapon prompt secretly
- Both weapons spawn and players fight
- "Designer Deathmatch" variant: each player writes a weapon FOR their opponent
- "Trust Fall" variant: one player writes, other must use it

## Stat System

| Stat | What it Affects |
|---|---|
| Damage | Raw hit power |
| Speed | Attack frequency / swing speed |
| Range | How far it reaches |
| Accuracy | Hit chance |
| Critical | Crit damage / chance |
| Durability | Uses before breaking |
| Weight | Movement speed penalty |
| Stealth | Detection radius |
| Area | Single target vs AoE |
| Status | Burning, poison, slow, etc. |

## Word → Stat Mapping (Thesaurus-Based)

| Category | Words (synonyms) | Positive Effect | Negative Effect |
|---|---|---|---|
| Weight | heavy, massive, bulky | Damage, Knockback ↑ | Speed, Mobility ↓ |
| Hardness | hard, solid, steel, reinforced | Durability, Damage ↑ | Brittleness ↑ |
| Sharpness | sharp, keen, pointed, slicing | Piercing, Crit ↑ | Blunt Force ↓ |
| Speed | fast, quick, rapid, swift | Attack Speed, Dodge ↑ | Damage, Accuracy ↓ |
| Range | long, extended, far-reaching | Range ↑ | Speed, Stealth ↓ |
| Lightness | light, featherweight, airy | Speed, Mobility ↑ | Damage, Knockback ↓ |
| Size | giant, enormous, massive | Area Effect, Fear ↑ | Speed, Precision ↓ |
| Magic | enchanted, arcane, mystical | Special Effects ↑ | Reliability ↓ |
| Heat | flaming, fiery, burning | DOT, Fear ↑ | Can't use near flammable |
| Cold | freezing, icy, frozen | Slow, DOT ↑ | Self-slow |

**Material words** also feed durability/break chance:
- Steel, titanium, diamond → High durability
- Wood, plastic, glass → Low durability, brittle

**Negation handling:** "not heavy" / "lightweight" inverts weight penalty

## Side Effects

### Trigger-Based Side Effects

| Side Effect | Trigger | Effect |
|---|---|---|
| Proximity Burn | Fire/Ice + Large size | You take damage on close swings |
| Friendly Fire | Explosive + Ranged | Projectiles hurt you too |
| Weight Drag | Over weight threshold | Movement speed drops while held |
| Overheat | "infinite" / "endless" / "non-stop" | Weapon jams after sustained use |
| Attention Grab | "loud" / "explosive" / "bright" | Enemies alerted |
| Skill Drain | "heavy" / "requires two hands" | Stamina depletes faster |
| Fading Core | "unstable" / "temporary" / "made of light" | Weapon disappears after X seconds |
| Backfire | "powerful" / "unstable" without balance | Chance to hurt wielder on crit fail |
| Slippery Grip | "wet" / "oily" / "made of ice" | Reduced accuracy while moving |

### Severity Scaling
More extreme description = more extreme side effect.

### Category Types
- **Passive** — always on
- **Conditional** — triggers on specific actions
- **Temporal** — fades over time
- **Environmental** — affects the battlefield

## Example Weapons

| Prompt | Outcome |
|---|---|
| "A sword made of glass" | Massive crit, shatters on first hard hit |
| "A gun that shoots rubber ducks" | Non-lethal, enemies slip on them |
| "Infinite ammo minigun" | Overheats after 10 seconds |
| "Boots that make you run at the speed of sound" | So fast you can't stop, might run off cliffs |
| "A shield that's a trampoline" | Deflects projectiles but bounces enemies toward you |
| "Sword that cuts through anything" | So sharp it cuts wielder too |
| "An invisibility cloak that's slightly transparent" | Stealth but enemies can kinda see you |

## AI Output Schema

```json
{
  "name": "Inferno Blade",
  "description": "A massive two-handed sword wreathed in ever-burning flames. The heat radiates outward, scorching the air itself. Whichever fool wields it had better have asbestos gloves.",
  "damage": 85,
  "speed": -30,
  "range": 25,
  "weight": 40,
  "accuracy": 70,
  "crit": 30,
  "durability": 60,
  "stealth": -20,
  "area": 15,
  "status": ["Burning", "Fear"],
  "side_effects": ["Proximity Burn", "Attention Grab"],
  "balance_warning": "Extremely powerful, consider reducing range",
  "flavor": ["The blade screams when swung", "Leaves a trail of scorched earth"]
}
```

## Level Constraints Ideas

**Exploration-Focused:**
- Deep Ocean — high pressure, crushes large objects
- The Void — no atmosphere, no combustion, no sound
- Cramped Cave — only thin/long objects fit

**Sensory/Perception:**
- Blind Zone — no light, enemies also blind
- Noisy Room — sound-based tools don't work
- Radar Jamming — no electronics

**Material/Physics:**
- Rust Zone — metal degrades rapidly
- Sticky Zone — rubber/flexible things get stuck
- Superconducting — electronics short out

**Anti-Genre:**
- No Violence — no weapons, puzzle only
- No Flight — blocks anything lifting off ground
- No Living Things — only inanimate objects

## Caching
Cache common prompts for optimization.

## Brainstorm Session Summary

**Core concept validated:** Weapon generation loop is the heart of the game — test this first before building full game.

**Decision: Web app first.** Rationale:
- Faster iteration, instant shipping
- AI API integration is straightforward
- Lower build scope, no game engine needed
- Validate core loop (write prompt → get weapon → fight) before investing in 3D/2D engine
- Web app becomes proof-of-concept, then rebuild in Unity/Unreal if it catches

**MVP scope:**
1. Player enters prompt
2. AI returns weapon stats + description
3. Simple 2D arena or turn-based duel
4. Two players, same weapon, first to win
5. Display stats and side effects visually

Then iterate: more weapon slots, PvP rounds, level constraints, side effect management, weapon caching.

## Platform
Brainstorming stage — web app or traditional game TBD.

## Related
<!-- openclaw:wiki:related:start -->
### Related Pages

- [[concepts/anomem-postmortem|Anomem Postmortem]]
- [[entities/honda-civic-2016-ex-t-maintenance|Honda Civic 2016 EX-T Maintenance]]
- [[entities/lolok-site|lolok Site]]
- [[entities/lost-lands-2026|Lost Lands 2026]]
- [[entities/macvm|macvm]]
- [[concepts/project-guidelines|Project Guidelines]]
- [[entities/randomstix|Quoc Vu]]
- [[entities/randomstix-health|Randomstix Health]]
- [[concepts/self-hosted-infra|Self Hosted Infra]]
<!-- openclaw:wiki:related:end -->
