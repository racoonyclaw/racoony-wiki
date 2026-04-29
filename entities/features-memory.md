---
pageType: entity
id: entity.features-memory
title: 'Features: Memory'
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-features-memory.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-features-memory.md
updatedAt: '2026-04-24T15:05:25.753741+00:00'
claims:
- id: file-purpose-char-limit
  text: File**, **Purpose**, **Char Limit**
  status: supported
  confidence: null
- id: file-memorymd-purpose-agents-personal-notes
  text: "File**: **MEMORY.md**, **Purpose**: Agent's personal notes \u2014 environment\
    \ facts, conventions, things learned, **Char Limit**: 2,200 chars (~800 tokens)"
  status: supported
  confidence: null
- id: file-usermd-purpose-user-profile-your-prefer
  text: "File**: **USER.md**, **Purpose**: User profile \u2014 your preferences, communication\
    \ style, expectations, **Char Limit**: 1,375 chars (~500 tokens)"
  status: supported
  confidence: null
- id: a-header-showing-which-store-memory-or-user-profile
  text: A header showing which store (MEMORY or USER PROFILE)
  status: supported
  confidence: null
- id: usage-percentage-and-character-counts-so-the-agent-knows-cap
  text: Usage percentage and character counts so the agent knows capacity
  status: supported
  confidence: null
- id: individual-entries-separated-by-section-sign-delimiter
  text: "Individual entries separated by `\xA7` (section sign) delimiters"
  status: supported
  confidence: null
- id: entries-can-be-multiline
  text: Entries can be multiline
  status: supported
  confidence: null
- id: add-add-a-new-memory-entry
  text: "add** \u2014 Add a new memory entry"
  status: supported
  confidence: null
- id: replace-replace-an-existing-entry-with-updated-content
  text: "replace** \u2014 Replace an existing entry with updated content (uses substring\
    \ matching via `old_text`)"
  status: supported
  confidence: null
- id: remove-remove-an-entry-thats-no-longer-relevant-uses-s
  text: "remove** \u2014 Remove an entry that's no longer relevant (uses substring\
    \ matching via `old_text`)"
  status: supported
  confidence: null
- id: environment-facts-os-tools-project-structure
  text: Environment facts (OS, tools, project structure)
  status: supported
  confidence: null
- id: project-conventions-and-configuration
  text: Project conventions and configuration
  status: supported
  confidence: null
- id: tool-quirks-and-workarounds-discovered
  text: Tool quirks and workarounds discovered
  status: supported
  confidence: null
- id: completed-task-diary-entries
  text: Completed task diary entries
  status: supported
  confidence: null
- id: skills-and-techniques-that-worked
  text: Skills and techniques that worked
  status: supported
  confidence: null
- id: name-role-timezone
  text: Name, role, timezone
  status: supported
  confidence: null
- id: communication-preferences-concise-vs-detailed-format-prefe
  text: Communication preferences (concise vs detailed, format preferences)
  status: supported
  confidence: null
- id: pet-peeves-and-things-to-avoid
  text: Pet peeves and things to avoid
  status: supported
  confidence: null
- id: workflow-habits
  text: Workflow habits
  status: supported
  confidence: null
- id: technical-skill-level
  text: Technical skill level
  status: supported
  confidence: null
- id: user-preferences-i-prefer-typescript-over-javascript
  text: "User preferences:** \"I prefer TypeScript over JavaScript\" \u2192 save to\
    \ `user`"
  status: supported
  confidence: null
- id: environment-facts-this-server-runs-debian-12-with-postgr
  text: "Environment facts:** \"This server runs Debian 12 with PostgreSQL 16\" \u2192\
    \ save to `memory`"
  status: supported
  confidence: null
- id: corrections-dont-use-sudo-for-docker-commands-user-i
  text: "Corrections:** \"Don't use `sudo` for Docker commands, user is in docker\
    \ group\" \u2192 save to `memory`"
  status: supported
  confidence: null
- id: conventions-project-uses-tabs-120-char-line-width-goog
  text: "Conventions:** \"Project uses tabs, 120-char line width, Google-style docstrings\"\
    \ \u2192 save to `memory`"
  status: supported
  confidence: null
- id: completed-work-migrated-database-from-mysql-to-postgresq
  text: "Completed work:** \"Migrated database from MySQL to PostgreSQL on 2026-01-15\"\
    \ \u2192 save to `memory`"
  status: supported
  confidence: null
- id: explicit-requests-remember-that-my-api-key-rotation-happ
  text: "Explicit requests:** \"Remember that my API key rotation happens monthly\"\
    \ \u2192 save to `memory`"
  status: supported
  confidence: null
- id: trivialobvious-info-user-asked-about-python-too-vagu
  text: "Trivial/obvious info:** \"User asked about Python\" \u2014 too vague to be\
    \ useful"
  status: supported
  confidence: null
- id: easily-re-discovered-facts-python-312-supports-f-string
  text: "Easily re-discovered facts:** \"Python 3.12 supports f-string nesting\" \u2014\
    \ can web search this"
  status: supported
  confidence: null
- id: raw-data-dumps-large-code-blocks-log-files-data-tables
  text: "Raw data dumps:** Large code blocks, log files, data tables \u2014 too big\
    \ for memory"
  status: supported
  confidence: null
- id: session-specific-ephemera-temporary-file-paths-one-off-d
  text: Session-specific ephemera:** Temporary file paths, one-off debugging context
  status: supported
  confidence: null
- id: information-already-in-context-files-soulmd-and-agentsm
  text: Information already in context files:** SOUL.md and AGENTS.md content
  status: supported
  confidence: null
- id: store-limit-typical-entries
  text: Store**, **Limit**, **Typical entries**
  status: supported
  confidence: null
- id: store-memory-limit-2200-chars-typical-entries
  text: 'Store**: memory, **Limit**: 2,200 chars, **Typical entries**: 8-15 entries'
  status: supported
  confidence: null
- id: store-user-limit-1375-chars-typical-entries
  text: 'Store**: user, **Limit**: 1,375 chars, **Typical entries**: 5-10 entries'
  status: supported
  confidence: null
- id: all-cli-and-messaging-sessions-are-stored-in-sqlite-her
  text: All CLI and messaging sessions are stored in SQLite (`~/.hermes/state.db`)
    with FTS5 full-text search
  status: supported
  confidence: null
- id: search-queries-return-relevant-past-conversations-with-gemin
  text: Search queries return relevant past conversations with Gemini Flash summarization
  status: supported
  confidence: null
- id: the-agent-can-find-things-it-discussed-weeks-ago-even-if-th
  text: The agent can find things it discussed weeks ago, even if they're not in its
    active memory
  status: supported
  confidence: null
- id: feature-persistent-memory-session-search
  text: Feature**, **Persistent Memory**, **Session Search**
  status: supported
  confidence: null
- id: feature-capacity-persistent-memory-1300-token
  text: 'Feature**: **Capacity**, **Persistent Memory**: ~1,300 tokens total, **Session
    Search**: Unlimited (all sessions)'
  status: supported
  confidence: null
- id: feature-speed-persistent-memory-instant-in-sys
  text: 'Feature**: **Speed**, **Persistent Memory**: Instant (in system prompt),
    **Session Search**: Requires search + LLM summarization'
  status: supported
  confidence: null
- id: feature-use-case-persistent-memory-key-facts-al
  text: 'Feature**: **Use case**, **Persistent Memory**: Key facts always available,
    **Session Search**: Finding specific past conversations'
  status: supported
  confidence: null
- id: feature-management-persistent-memory-manually-c
  text: "Feature**: **Management**, **Persistent Memory**: Manually curated by agent,\
    \ **Session Search**: Automatic \u2014 all sessions stored"
  status: supported
  confidence: null
- id: feature-token-cost-persistent-memory-fixed-per
  text: 'Feature**: **Token cost**, **Persistent Memory**: Fixed per session (~1,300
    tokens), **Session Search**: On-demand (searched when needed)'
  status: supported
  confidence: null
---

Hermes Agent has bounded, curated memory that persists across sessions. This lets it remember your preferences, your projects, your environment, and things it has learned.

## How It Works[​](#how-it-works "Direct link to How It Works")

Two files make up the agent's memory:

- **File**, **Purpose**, **Char Limit**
- **File**: **MEMORY.md**, **Purpose**: Agent's personal notes — environment facts, conventions, things learned, **Char Limit**: 2,200 chars (~800 tokens)
- **File**: **USER.md**, **Purpose**: User profile — your preferences, communication style, expectations, **Char Limit**: 1,375 chars (~500 tokens)

Both are stored in `~/.hermes/memories/` and are injected into the system prompt as a frozen snapshot at session start. The agent manages its own memory via the `memory` tool — it can add, replace, or remove entries.

info

Character limits keep memory focused. When memory is full, the agent consolidates or replaces entries to make room for new information.

## How Memory Appears in the System Prompt[​](#how-memory-appears-in-the-system-prompt "Direct link to How Memory Appears in the System Prompt")

At the start of every session, memory entries are loaded from disk and rendered into the system prompt as a frozen block:

```
══════════════════════════════════════════════
MEMORY (your personal notes) [67% — 1,474/2,200 chars]
══════════════════════════════════════════════
User's project is a Rust web service at ~/code/myapi using Axum + SQLx
§
This machine runs Ubuntu 22.04, has Docker and Podman installed
§
User prefers concise responses, dislikes verbose explanations
```

The format includes:

- A header showing which store (MEMORY or USER PROFILE)
- Usage percentage and character counts so the agent knows capacity
- Individual entries separated by `§` (section sign) delimiters
- Entries can be multiline

**Frozen snapshot pattern:** The system prompt injection is captured once at session start and never changes mid-session. This is intentional — it preserves the LLM's prefix cache for performance. When the agent adds/removes memory entries during a session, the changes are persisted to disk immediately but won't appear in the system prompt until the next session starts. Tool responses always show the live state.

## Memory Tool Actions[​](#memory-tool-actions "Direct link to Memory Tool Actions")

The agent uses the `memory` tool with these actions:

- **add** — Add a new memory entry
- **replace** — Replace an existing entry with updated content (uses substring matching via `old_text`)
- **remove** — Remove an entry that's no longer relevant (uses substring matching via `old_text`)

There is no `read` action — memory content is automatically injected into the system prompt at session start. The agent sees its memories as part of its conversation context.

### Substring Matching[​](#substring-matching "Direct link to Substring Matching")

The `replace` and `remove` actions use short unique substring matching — you don't need the full entry text. The `old_text` parameter just needs to be a unique substring that identifies exactly one entry:

```
# If memory contains "User prefers dark mode in all editors"
memory(action="replace", target="memory",
       old_text="dark mode",
       content="User prefers light mode in VS Code, dark mode in terminal")
```

If the substring matches multiple entries, an error is returned asking for a more specific match.

## Two Targets Explained[​](#two-targets-explained "Direct link to Two Targets Explained")

### `memory` — Agent's Personal Notes[​](#memory--agents-personal-notes "Direct link to memory--agents-personal-notes")

For information the agent needs to remember about the environment, workflows, and lessons learned:

- Environment facts (OS, tools, project structure)
- Project conventions and configuration
- Tool quirks and workarounds discovered
- Completed task diary entries
- Skills and techniques that worked

### `user` — User Profile[​](#user--user-profile "Direct link to user--user-profile")

For information about the user's identity, preferences, and communication style:

- Name, role, timezone
- Communication preferences (concise vs detailed, format preferences)
- Pet peeves and things to avoid
- Workflow habits
- Technical skill level

## What to Save vs Skip[​](#what-to-save-vs-skip "Direct link to What to Save vs Skip")

### Save These (Proactively)[​](#save-these-proactively "Direct link to Save These (Proactively)")

The agent saves automatically — you don't need to ask. It saves when it learns:

- **User preferences:** "I prefer TypeScript over JavaScript" → save to `user`
- **Environment facts:** "This server runs Debian 12 with PostgreSQL 16" → save to `memory`
- **Corrections:** "Don't use `sudo` for Docker commands, user is in docker group" → save to `memory`
- **Conventions:** "Project uses tabs, 120-char line width, Google-style docstrings" → save to `memory`
- **Completed work:** "Migrated database from MySQL to PostgreSQL on 2026-01-15" → save to `memory`
- **Explicit requests:** "Remember that my API key rotation happens monthly" → save to `memory`

### Skip These[​](#skip-these "Direct link to Skip These")

- **Trivial/obvious info:** "User asked about Python" — too vague to be useful
- **Easily re-discovered facts:** "Python 3.12 supports f-string nesting" — can web search this
- **Raw data dumps:** Large code blocks, log files, data tables — too big for memory
- **Session-specific ephemera:** Temporary file paths, one-off debugging context
- **Information already in context files:** SOUL.md and AGENTS.md content

## Capacity Management[​](#capacity-management "Direct link to Capacity Management")

Memory has strict character limits to keep system prompts bounded:

- **Store**, **Limit**, **Typical entries**
- **Store**: memory, **Limit**: 2,200 chars, **Typical entries**: 8-15 entries
- **Store**: user, **Limit**: 1,375 chars, **Typical entries**: 5-10 entries

### What Happens When Memory is Full[​](#what-happens-when-memory-is-full "Direct link to What Happens When Memory is Full")

When you try to add an entry that would exceed the limit, the tool returns an error:

```
{
  "success": false,
  "error": "Memory at 2,100/2,200 chars. Adding this entry (250 chars) would exceed the limit. Replace or remove existing entries first.",
  "current_entries": ["..."],
  "usage": "2,100/2,200"
}
```

The agent should then:

1. Read the current entries (shown in the error response)
2. Identify entries that can be removed or consolidated
3. Use `replace` to merge related entries into shorter versions
4. Then `add` the new entry

**Best practice:** When memory is above 80% capacity (visible in the system prompt header), consolidate entries before adding new ones. For example, merge three separate "project uses X" entries into one comprehensive project description entry.

### Practical Examples of Good Memory Entries[​](#practical-examples-of-good-memory-entries "Direct link to Practical Examples of Good Memory Entries")

**Compact, information-dense entries work best:**

```
# Good: Packs multiple related facts
User runs macOS 14 Sonoma, uses Homebrew, has Docker Desktop and Podman. Shell: zsh with oh-my-zsh. Editor: VS Code with Vim keybindings.

# Good: Specific, actionable convention
Project ~/code/api uses Go 1.22, sqlc for DB queries, chi router. Run tests with 'make test'. CI via GitHub Actions.

# Good: Lesson learned with context
The staging server (10.0.1.50) needs SSH port 2222, not 22. Key is at ~/.ssh/staging_ed25519.

# Bad: Too vague
User has a project.

# Bad: Too verbose
On January 5th, 2026, the user asked me to look at their project which is
located at ~/code/api. I discovered it uses Go version 1.22 and...
```

## Duplicate Prevention[​](#duplicate-prevention "Direct link to Duplicate Prevention")

The memory system automatically rejects exact duplicate entries. If you try to add content that already exists, it returns success with a "no duplicate added" message.

## Security Scanning[​](#security-scanning "Direct link to Security Scanning")

Memory entries are scanned for injection and exfiltration patterns before being accepted, since they're injected into the system prompt. Content matching threat patterns (prompt injection, credential exfiltration, SSH backdoors) or containing invisible Unicode characters is blocked.

## Session Search[​](#session-search "Direct link to Session Search")

Beyond MEMORY.md and USER.md, the agent can search its past conversations using the `session_search` tool:

- All CLI and messaging sessions are stored in SQLite (`~/.hermes/state.db`) with FTS5 full-text search
- Search queries return relevant past conversations with Gemini Flash summarization
- The agent can find things it discussed weeks ago, even if they're not in its active memory

```
hermes sessions list    # Browse past sessions
```

### session\_search vs memory[​](#session_search-vs-memory "Direct link to session_search vs memory")

- **Feature**, **Persistent Memory**, **Session Search**
- **Feature**: **Capacity**, **Persistent Memory**: ~1,300 tokens total, **Session Search**: Unlimited (all sessions)
- **Feature**: **Speed**, **Persistent Memory**: Instant (in system prompt), **Session Search**: Requires search + LLM summarization
- **Feature**: **Use case**, **Persistent Memory**: Key facts always available, **Session Search**: Finding specific past conversations
- **Feature**: **Management**, **Persistent Memory**: Manually curated by agent, **Session Search**: Automatic — all sessions stored
- **Feature**: **Token cost**, **Persistent Memory**: Fixed per session (~1,300 tokens), **Session Search**: On-demand (searched when needed)

**Memory** is for critical facts that should always be in context. **Session search** is for "did we discuss X last week?" queries where the agent needs to recall specifics from past conversations.

## Configuration[​](#configuration "Direct link to Configuration")

```
# In ~/.hermes/config.yaml
memory:
  memory_enabled: true
  user_profile_enabled: true
  memory_char_limit: 2200   # ~800 tokens
  user_char_limit: 1375     # ~500 tokens
```

## External Memory Providers[​](#external-memory-providers "Direct link to External Memory Providers")

For deeper, persistent memory that goes beyond MEMORY.md and USER.md, Hermes ships with 8 external memory provider plugins — including Honcho, OpenViking, Mem0, Hindsight, Holographic, RetainDB, ByteRover, and Supermemory.

External providers run **alongside** built-in memory (never replacing it) and add capabilities like knowledge graphs, semantic search, automatic fact extraction, and cross-session user modeling.

```
hermes memory setup      # pick a provider and configure it
hermes memory status     # check what's active
```

See the [Memory Providers](/docs/user-guide/features/memory-providers) guide for full details on each provider, setup instructions, and comparison.