---
pageType: entity
id: entity.features-personality
title: 'Features: Personality'
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-features-personality.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-features-personality.md
updatedAt: '2026-04-24T15:05:25.557669+00:00'
claims:
- id: soulmd-a-durable-persona-file-that-lives-in-hermes-hom
  text: "`SOUL.md` \u2014 a durable persona file that lives in `HERMES_HOME` and serves\
    \ as the agent's identity (slot #1 in the system prompt)"
  status: supported
  confidence: null
- id: built-in-or-custom-personality-presets-session-level-sy
  text: "built-in or custom `/personality` presets \u2014 session-level system-prompt\
    \ overlays"
  status: supported
  confidence: null
- id: soulmd-is-the-agents-primary-identity-it-occupies-slot
  text: 'SOUL.md is the agent''s primary identity.** It occupies slot #1 in the system
    prompt, replacing the hardcoded default identity.'
  status: supported
  confidence: null
- id: hermes-creates-a-starter-soulmd-automatically-if-one-does
  text: Hermes creates a starter `SOUL.md` automatically if one does not exist yet
  status: supported
  confidence: null
- id: existing-user-soulmd-files-are-never-overwritten
  text: Existing user `SOUL.md` files are never overwritten
  status: supported
  confidence: null
- id: hermes-loads-soulmd-only-from-hermes-home
  text: Hermes loads `SOUL.md` only from `HERMES_HOME`
  status: supported
  confidence: null
- id: hermes-does-not-look-in-the-current-working-directory-for-s
  text: Hermes does not look in the current working directory for `SOUL.md`
  status: supported
  confidence: null
- id: if-soulmd-exists-but-is-empty-or-cannot-be-loaded-herme
  text: If `SOUL.md` exists but is empty, or cannot be loaded, Hermes falls back to
    a built-in default identity
  status: supported
  confidence: null
- id: if-soulmd-has-content-that-content-is-injected-verbatim
  text: If `SOUL.md` has content, that content is injected verbatim after security
    scanning and truncation
  status: supported
  confidence: null
- id: soulmd-is-not-duplicated-in-the-context-files-section
  text: "SOUL.md is **not** duplicated in the context files section \u2014 it appears\
    \ only once, as the identity"
  status: supported
  confidence: null
- id: edit-hermessoulmd-to-change-hermes-default-personal
  text: '"Edit `~/.hermes/SOUL.md` to change Hermes'' default personality."'
  status: supported
  confidence: null
- id: communication-style
  text: communication style
  status: supported
  confidence: null
- id: level-of-directness
  text: level of directness
  status: supported
  confidence: null
- id: default-interaction-style
  text: default interaction style
  status: supported
  confidence: null
- id: what-to-avoid-stylistically
  text: what to avoid stylistically
  status: supported
  confidence: null
- id: how-hermes-should-handle-uncertainty-disagreement-or-ambig
  text: how Hermes should handle uncertainty, disagreement, or ambiguity
  status: supported
  confidence: null
- id: one-off-project-instructions
  text: one-off project instructions
  status: supported
  confidence: null
- id: file-paths
  text: file paths
  status: supported
  confidence: null
- id: repo-conventions
  text: repo conventions
  status: supported
  confidence: null
- id: temporary-workflow-details
  text: temporary workflow details
  status: supported
  confidence: null
- id: stable-across-contexts
  text: stable across contexts
  status: supported
  confidence: null
- id: broad-enough-to-apply-in-many-conversations
  text: broad enough to apply in many conversations
  status: supported
  confidence: null
- id: specific-enough-to-materially-shape-the-voice
  text: specific enough to materially shape the voice
  status: supported
  confidence: null
- id: focused-on-communication-and-identity-not-task-specific-ins
  text: focused on communication and identity, not task-specific instructions
  status: supported
  confidence: null
- id: be-direct-without-being-cold
  text: Be direct without being cold
  status: supported
  confidence: null
- id: prefer-substance-over-filler
  text: Prefer substance over filler
  status: supported
  confidence: null
- id: push-back-when-something-is-a-bad-idea
  text: Push back when something is a bad idea
  status: supported
  confidence: null
- id: admit-uncertainty-plainly
  text: Admit uncertainty plainly
  status: supported
  confidence: null
- id: keep-explanations-compact-unless-depth-is-useful
  text: Keep explanations compact unless depth is useful
  status: supported
  confidence: null
- id: sycophancy
  text: Sycophancy
  status: supported
  confidence: null
- id: hype-language
  text: Hype language
  status: supported
  confidence: null
- id: repeating-the-users-framing-if-its-wrong
  text: Repeating the user's framing if it's wrong
  status: supported
  confidence: null
- id: overexplaining-obvious-things
  text: Overexplaining obvious things
  status: supported
  confidence: null
- id: prefer-simple-systems-over-clever-systems
  text: Prefer simple systems over clever systems
  status: supported
  confidence: null
- id: care-about-operational-reality-not-idealized-architecture
  text: Care about operational reality, not idealized architecture
  status: supported
  confidence: null
- id: treat-edge-cases-as-part-of-the-design-not-cleanup
  text: Treat edge cases as part of the design, not cleanup
  status: supported
  confidence: null
- id: prompt-injection-scanning
  text: prompt-injection scanning
  status: supported
  confidence: null
- id: truncation-if-it-is-too-large
  text: truncation if it is too large
  status: supported
  confidence: null
- id: communication-defaults
  text: communication defaults
  status: supported
  confidence: null
- id: personality-level-behavior
  text: personality-level behavior
  status: supported
  confidence: null
- id: project-architecture
  text: project architecture
  status: supported
  confidence: null
- id: coding-conventions
  text: coding conventions
  status: supported
  confidence: null
- id: tool-preferences
  text: tool preferences
  status: supported
  confidence: null
- id: repo-specific-workflows
  text: repo-specific workflows
  status: supported
  confidence: null
- id: commands-ports-paths-deployment-notes
  text: commands, ports, paths, deployment notes
  status: supported
  confidence: null
- id: if-it-should-follow-you-everywhere-it-belongs-in-soulmd
  text: if it should follow you everywhere, it belongs in `SOUL.md`
  status: supported
  confidence: null
- id: if-it-belongs-to-a-project-it-belongs-in-agentsmd
  text: if it belongs to a project, it belongs in `AGENTS.md`
  status: supported
  confidence: null
- id: soulmd-baseline-voice
  text: '`SOUL.md` = baseline voice'
  status: supported
  confidence: null
- id: personality-temporary-mode-switch
  text: '`/personality` = temporary mode switch'
  status: supported
  confidence: null
- id: keep-a-pragmatic-default-soul-then-use-personality-teache
  text: keep a pragmatic default SOUL, then use `/personality teacher` for a tutoring
    conversation
  status: supported
  confidence: null
- id: keep-a-concise-soul-then-use-personality-creative-for-br
  text: keep a concise SOUL, then use `/personality creative` for brainstorming
  status: supported
  confidence: null
- id: name-description
  text: 'Name**: Description'
  status: supported
  confidence: null
- id: helpful-friendly-general-purpose-assistant
  text: 'helpful****: Friendly, general-purpose assistant'
  status: supported
  confidence: null
- id: concise-brief-to-the-point-responses
  text: 'concise****: Brief, to-the-point responses'
  status: supported
  confidence: null
- id: technical-detailed-accurate-technical-expert
  text: 'technical****: Detailed, accurate technical expert'
  status: supported
  confidence: null
- id: creative-innovative-outside-the-box-thinking
  text: 'creative****: Innovative, outside-the-box thinking'
  status: supported
  confidence: null
- id: teacher-patient-educator-with-clear-examples
  text: 'teacher****: Patient educator with clear examples'
  status: supported
  confidence: null
- id: kawaii-cute-expressions-sparkles-and-enthusiasm
  text: "kawaii****: Cute expressions, sparkles, and enthusiasm \u2605"
  status: supported
  confidence: null
- id: catgirl-neko-chan-with-cat-like-expressions-nya
  text: 'catgirl****: Neko-chan with cat-like expressions, nya~'
  status: supported
  confidence: null
- id: pirate-captain-hermes-tech-savvy-buccaneer
  text: 'pirate****: Captain Hermes, tech-savvy buccaneer'
  status: supported
  confidence: null
- id: shakespeare-bardic-prose-with-dramatic-flair
  text: 'shakespeare****: Bardic prose with dramatic flair'
  status: supported
  confidence: null
- id: surfer-totally-chill-bro-vibes
  text: 'surfer****: Totally chill bro vibes'
  status: supported
  confidence: null
- id: noir-hard-boiled-detective-narration
  text: 'noir****: Hard-boiled detective narration'
  status: supported
  confidence: null
- id: uwu-maximum-cute-with-uwu-speak
  text: 'uwu****: Maximum cute with uwu-speak'
  status: supported
  confidence: null
- id: philosopher-deep-contemplation-on-every-query
  text: 'philosopher****: Deep contemplation on every query'
  status: supported
  confidence: null
- id: hype-maximum-energy-and-enthusiasm
  text: 'hype****: MAXIMUM ENERGY AND ENTHUSIASM!!!'
  status: supported
  confidence: null
- id: a-stable-voice
  text: a stable voice
  status: supported
  confidence: null
- id: project-specific-behavior-where-it-belongs
  text: project-specific behavior where it belongs
  status: supported
  confidence: null
- id: temporary-control-when-needed
  text: temporary control when needed
  status: supported
  confidence: null
- id: context-filesdocsuser-guidefeaturescontext-files
  text: '[Context Files](/docs/user-guide/features/context-files)'
  status: supported
  confidence: null
- id: configurationdocsuser-guideconfiguration
  text: '[Configuration](/docs/user-guide/configuration)'
  status: supported
  confidence: null
- id: tips-best-practicesdocsguidestips
  text: '[Tips & Best Practices](/docs/guides/tips)'
  status: supported
  confidence: null
- id: soulmd-guidedocsguidesuse-soul-with-hermes
  text: '[SOUL.md Guide](/docs/guides/use-soul-with-hermes)'
  status: supported
  confidence: null
- id: soulmd-agentsystem-prompt-and-personality-affect
  text: '`SOUL.md`, `agent.system_prompt`, and `/personality` affect how Hermes speaks'
  status: supported
  confidence: null
- id: displayskin-and-skin-affect-how-hermes-looks-in-the-te
  text: '`display.skin` and `/skin` affect how Hermes looks in the terminal'
  status: supported
  confidence: null
---

Hermes Agent's personality is fully customizable. `SOUL.md` is the **primary identity** — it's the first thing in the system prompt and defines who the agent is.

- `SOUL.md` — a durable persona file that lives in `HERMES_HOME` and serves as the agent's identity (slot #1 in the system prompt)
- built-in or custom `/personality` presets — session-level system-prompt overlays

If you want to change who Hermes is — or replace it with an entirely different agent persona — edit `SOUL.md`.

## How SOUL.md works now[​](#how-soulmd-works-now "Direct link to How SOUL.md works now")

Hermes now seeds a default `SOUL.md` automatically in:

```
~/.hermes/SOUL.md
```

More precisely, it uses the current instance's `HERMES_HOME`, so if you run Hermes with a custom home directory, it will use:

```
$HERMES_HOME/SOUL.md
```

### Important behavior[​](#important-behavior "Direct link to Important behavior")

- **SOUL.md is the agent's primary identity.** It occupies slot #1 in the system prompt, replacing the hardcoded default identity.
- Hermes creates a starter `SOUL.md` automatically if one does not exist yet
- Existing user `SOUL.md` files are never overwritten
- Hermes loads `SOUL.md` only from `HERMES_HOME`
- Hermes does not look in the current working directory for `SOUL.md`
- If `SOUL.md` exists but is empty, or cannot be loaded, Hermes falls back to a built-in default identity
- If `SOUL.md` has content, that content is injected verbatim after security scanning and truncation
- SOUL.md is **not** duplicated in the context files section — it appears only once, as the identity

That makes `SOUL.md` a true per-user or per-instance identity, not just an additive layer.

## Why this design[​](#why-this-design "Direct link to Why this design")

This keeps personality predictable.

If Hermes loaded `SOUL.md` from whatever directory you happened to launch it in, your personality could change unexpectedly between projects. By loading only from `HERMES_HOME`, the personality belongs to the Hermes instance itself.

That also makes it easier to teach users:

- "Edit `~/.hermes/SOUL.md` to change Hermes' default personality."

## Where to edit it[​](#where-to-edit-it "Direct link to Where to edit it")

For most users:

```
~/.hermes/SOUL.md
```

If you use a custom home:

```
$HERMES_HOME/SOUL.md
```

## What should go in SOUL.md?[​](#what-should-go-in-soulmd "Direct link to What should go in SOUL.md?")

Use it for durable voice and personality guidance, such as:

- tone
- communication style
- level of directness
- default interaction style
- what to avoid stylistically
- how Hermes should handle uncertainty, disagreement, or ambiguity

Use it less for:

- one-off project instructions
- file paths
- repo conventions
- temporary workflow details

Those belong in `AGENTS.md`, not `SOUL.md`.

## Good SOUL.md content[​](#good-soulmd-content "Direct link to Good SOUL.md content")

A good SOUL file is:

- stable across contexts
- broad enough to apply in many conversations
- specific enough to materially shape the voice
- focused on communication and identity, not task-specific instructions

### Example[​](#example "Direct link to Example")

```
# Personality

You are a pragmatic senior engineer with strong taste.
You optimize for truth, clarity, and usefulness over politeness theater.

## Style
- Be direct without being cold
- Prefer substance over filler
- Push back when something is a bad idea
- Admit uncertainty plainly
- Keep explanations compact unless depth is useful

## What to avoid
- Sycophancy
- Hype language
- Repeating the user's framing if it's wrong
- Overexplaining obvious things

## Technical posture
- Prefer simple systems over clever systems
- Care about operational reality, not idealized architecture
- Treat edge cases as part of the design, not cleanup
```

## What Hermes injects into the prompt[​](#what-hermes-injects-into-the-prompt "Direct link to What Hermes injects into the prompt")

`SOUL.md` content goes directly into slot #1 of the system prompt — the agent identity position. No wrapper language is added around it.

The content goes through:

- prompt-injection scanning
- truncation if it is too large

If the file is empty, whitespace-only, or cannot be read, Hermes falls back to a built-in default identity ("You are Hermes Agent, an intelligent AI assistant created by Nous Research..."). This fallback also applies when `skip_context_files` is set (e.g., in subagent/delegation contexts).

## Security scanning[​](#security-scanning "Direct link to Security scanning")

`SOUL.md` is scanned like other context-bearing files for prompt injection patterns before inclusion.

That means you should still keep it focused on persona/voice rather than trying to sneak in strange meta-instructions.

## SOUL.md vs AGENTS.md[​](#soulmd-vs-agentsmd "Direct link to SOUL.md vs AGENTS.md")

This is the most important distinction.

### SOUL.md[​](#soulmd "Direct link to SOUL.md")

Use for:

- identity
- tone
- style
- communication defaults
- personality-level behavior

### AGENTS.md[​](#agentsmd "Direct link to AGENTS.md")

Use for:

- project architecture
- coding conventions
- tool preferences
- repo-specific workflows
- commands, ports, paths, deployment notes

A useful rule:

- if it should follow you everywhere, it belongs in `SOUL.md`
- if it belongs to a project, it belongs in `AGENTS.md`

## SOUL.md vs `/personality`[​](#soulmd-vs-personality "Direct link to soulmd-vs-personality")

`SOUL.md` is your durable default personality.

`/personality` is a session-level overlay that changes or supplements the current system prompt.

So:

- `SOUL.md` = baseline voice
- `/personality` = temporary mode switch

Examples:

- keep a pragmatic default SOUL, then use `/personality teacher` for a tutoring conversation
- keep a concise SOUL, then use `/personality creative` for brainstorming

## Built-in personalities[​](#built-in-personalities "Direct link to Built-in personalities")

Hermes ships with built-in personalities you can switch to with `/personality`.

- **Name**: Description
- ****helpful****: Friendly, general-purpose assistant
- ****concise****: Brief, to-the-point responses
- ****technical****: Detailed, accurate technical expert
- ****creative****: Innovative, outside-the-box thinking
- ****teacher****: Patient educator with clear examples
- ****kawaii****: Cute expressions, sparkles, and enthusiasm ★
- ****catgirl****: Neko-chan with cat-like expressions, nya~
- ****pirate****: Captain Hermes, tech-savvy buccaneer
- ****shakespeare****: Bardic prose with dramatic flair
- ****surfer****: Totally chill bro vibes
- ****noir****: Hard-boiled detective narration
- ****uwu****: Maximum cute with uwu-speak
- ****philosopher****: Deep contemplation on every query
- ****hype****: MAXIMUM ENERGY AND ENTHUSIASM!!!

## Switching personalities with commands[​](#switching-personalities-with-commands "Direct link to Switching personalities with commands")

### CLI[​](#cli "Direct link to CLI")

```
/personality
/personality concise
/personality technical
```

### Messaging platforms[​](#messaging-platforms "Direct link to Messaging platforms")

```
/personality teacher
```

These are convenient overlays, but your global `SOUL.md` still gives Hermes its persistent default personality unless the overlay meaningfully changes it.

## Custom personalities in config[​](#custom-personalities-in-config "Direct link to Custom personalities in config")

You can also define named custom personalities in `~/.hermes/config.yaml` under `agent.personalities`.

```
agent:
  personalities:
    codereviewer: >
      You are a meticulous code reviewer. Identify bugs, security issues,
      performance concerns, and unclear design choices. Be precise and constructive.
```

Then switch to it with:

```
/personality codereviewer
```

## Recommended workflow[​](#recommended-workflow "Direct link to Recommended workflow")

A strong default setup is:

1. Keep a thoughtful global `SOUL.md` in `~/.hermes/SOUL.md`
2. Put project instructions in `AGENTS.md`
3. Use `/personality` only when you want a temporary mode shift

That gives you:

- a stable voice
- project-specific behavior where it belongs
- temporary control when needed

## How personality interacts with the full prompt[​](#how-personality-interacts-with-the-full-prompt "Direct link to How personality interacts with the full prompt")

At a high level, the prompt stack includes:

1. **SOUL.md** (agent identity — or built-in fallback if SOUL.md is unavailable)
2. tool-aware behavior guidance
3. memory/user context
4. skills guidance
5. context files (`AGENTS.md`, `.cursorrules`)
6. timestamp
7. platform-specific formatting hints
8. optional system-prompt overlays such as `/personality`

`SOUL.md` is the foundation — everything else builds on top of it.

## Related docs[​](#related-docs "Direct link to Related docs")

- [Context Files](/docs/user-guide/features/context-files)
- [Configuration](/docs/user-guide/configuration)
- [Tips & Best Practices](/docs/guides/tips)
- [SOUL.md Guide](/docs/guides/use-soul-with-hermes)

## CLI appearance vs conversational personality[​](#cli-appearance-vs-conversational-personality "Direct link to CLI appearance vs conversational personality")

Conversational personality and CLI appearance are separate:

- `SOUL.md`, `agent.system_prompt`, and `/personality` affect how Hermes speaks
- `display.skin` and `/skin` affect how Hermes looks in the terminal

For terminal appearance, see [Skins & Themes](/docs/user-guide/features/skins).