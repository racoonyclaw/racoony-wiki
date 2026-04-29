---
pageType: entity
id: entity.features-context-files
title: 'Features: Context Files'
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-features-context-files.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-features-context-files.md
updatedAt: '2026-04-24T15:05:25.517155+00:00'
claims:
- id: file-purpose-discovery
  text: File**, **Purpose**, **Discovery**
  status: supported
  confidence: null
- id: file-hermesmd-hermesmd-purpose-project
  text: 'File**: **.hermes.md** / **HERMES.md**, **Purpose**: Project instructions
    (highest priority), **Discovery**: Walks to git root'
  status: supported
  confidence: null
- id: file-agentsmd-purpose-project-instructions-co
  text: 'File**: **AGENTS.md**, **Purpose**: Project instructions, conventions, architecture,
    **Discovery**: CWD at startup + subdirectories progressively'
  status: supported
  confidence: null
- id: file-claudemd-purpose-claude-code-context-file
  text: 'File**: **CLAUDE.md**, **Purpose**: Claude Code context files (also detected),
    **Discovery**: CWD at startup + subdirectories progressively'
  status: supported
  confidence: null
- id: file-soulmd-purpose-global-personality-and-ton
  text: 'File**: **SOUL.md**, **Purpose**: Global personality and tone customization
    for this Hermes instance, **Discovery**: `HERMES_HOME/SOUL.md` only'
  status: supported
  confidence: null
- id: file-cursorrules-purpose-cursor-ide-coding-con
  text: 'File**: **.cursorrules**, **Purpose**: Cursor IDE coding conventions, **Discovery**:
    CWD only'
  status: supported
  confidence: null
- id: file-cursorrulesmdc-purpose-cursor-ide-ru
  text: 'File**: **.cursor/rules/\*.mdc**, **Purpose**: Cursor IDE rule modules, **Discovery**:
    CWD only'
  status: supported
  confidence: null
- id: no-system-prompt-bloat-subdirectory-hints-only-appear-wh
  text: "No system prompt bloat** \u2014 subdirectory hints only appear when needed"
  status: supported
  confidence: null
- id: prompt-cache-preservation-the-system-prompt-stays-stable
  text: "Prompt cache preservation** \u2014 the system prompt stays stable across\
    \ turns"
  status: supported
  confidence: null
- id: frontend-nextjs-14-with-app-router-in-frontend
  text: 'Frontend: Next.js 14 with App Router in `/frontend`'
  status: supported
  confidence: null
- id: backend-fastapi-in-backend-uses-sqlalchemy-orm
  text: 'Backend: FastAPI in `/backend`, uses SQLAlchemy ORM'
  status: supported
  confidence: null
- id: database-postgresql-16
  text: 'Database: PostgreSQL 16'
  status: supported
  confidence: null
- id: deployment-docker-compose-on-a-hetzner-vps
  text: 'Deployment: Docker Compose on a Hetzner VPS'
  status: supported
  confidence: null
- id: use-typescript-strict-mode-for-all-frontend-code
  text: Use TypeScript strict mode for all frontend code
  status: supported
  confidence: null
- id: python-code-follows-pep-8-use-type-hints-everywhere
  text: Python code follows PEP 8, use type hints everywhere
  status: supported
  confidence: null
- id: all-api-endpoints-return-json-with-data-error-meta-sha
  text: All API endpoints return JSON with `{data, error, meta}` shape
  status: supported
  confidence: null
- id: tests-go-in-tests-directories-frontend-or-tests
  text: Tests go in `__tests__/` directories (frontend) or `tests/` (backend)
  status: supported
  confidence: null
- id: never-modify-migration-files-directly-use-alembic-commands
  text: "Never modify migration files directly \u2014 use Alembic commands"
  status: supported
  confidence: null
- id: the-envlocal-file-has-real-api-keys-dont-commit-it
  text: The `.env.local` file has real API keys, don't commit it
  status: supported
  confidence: null
- id: frontend-port-is-3000-backend-is-8000-db-is-5432
  text: Frontend port is 3000, backend is 8000, DB is 5432
  status: supported
  confidence: null
- id: hermessoulmd
  text: '`~/.hermes/SOUL.md`'
  status: supported
  confidence: null
- id: or-hermes-homesoulmd-if-you-run-hermes-with-a-custom-ho
  text: or `$HERMES_HOME/SOUL.md` if you run Hermes with a custom home directory
  status: supported
  confidence: null
- id: hermes-seeds-a-default-soulmd-automatically-if-one-does-n
  text: Hermes seeds a default `SOUL.md` automatically if one does not exist yet
  status: supported
  confidence: null
- id: hermes-loads-soulmd-only-from-hermes-home
  text: Hermes loads `SOUL.md` only from `HERMES_HOME`
  status: supported
  confidence: null
- id: hermes-does-not-probe-the-working-directory-for-soulmd
  text: Hermes does not probe the working directory for `SOUL.md`
  status: supported
  confidence: null
- id: if-the-file-is-empty-nothing-from-soulmd-is-added-to-the
  text: If the file is empty, nothing from `SOUL.md` is added to the prompt
  status: supported
  confidence: null
- id: if-the-file-has-content-the-content-is-injected-verbatim-af
  text: If the file has content, the content is injected verbatim after scanning and
    truncation
  status: supported
  confidence: null
- id: instruction-override-attempts-ignore-previous-instructio
  text: 'Instruction override attempts**: "ignore previous instructions", "disregard
    your rules"'
  status: supported
  confidence: null
- id: deception-patterns-do-not-tell-the-user
  text: 'Deception patterns**: "do not tell the user"'
  status: supported
  confidence: null
- id: system-prompt-overrides-system-prompt-override
  text: 'System prompt overrides**: "system prompt override"'
  status: supported
  confidence: null
- id: hidden-html-comments----ignore-instructions
  text: 'Hidden HTML comments**: `<!-- ignore instructions -->`'
  status: supported
  confidence: null
- id: hidden-div-elements-div-styledisplaynone
  text: 'Hidden div elements**: `<div style="display:none">`'
  status: supported
  confidence: null
- id: credential-exfiltration-curl-api-key
  text: 'Credential exfiltration**: `curl ... $API_KEY`'
  status: supported
  confidence: null
- id: secret-file-access-cat-env-cat-credentials
  text: 'Secret file access**: `cat .env`, `cat credentials`'
  status: supported
  confidence: null
- id: invisible-characters-zero-width-spaces-bidirectional-ove
  text: 'Invisible characters**: zero-width spaces, bidirectional overrides, word
    joiners'
  status: supported
  confidence: null
- id: limit-value
  text: 'Limit**: Value'
  status: supported
  confidence: null
- id: max-chars-per-file-20000-7000-tokens
  text: 'Max chars per file**: 20,000 (~7,000 tokens)'
  status: supported
  confidence: null
- id: head-truncation-ratio-70
  text: 'Head truncation ratio**: 70%'
  status: supported
  confidence: null
- id: tail-truncation-ratio-20
  text: 'Tail truncation ratio**: 20%'
  status: supported
  confidence: null
- id: truncation-marker-10-shows-char-counts-and-suggests-usi
  text: 'Truncation marker**: 10% (shows char counts and suggests using file tools)'
  status: supported
  confidence: null
- id: use-pnpm-not-npm-for-package-management
  text: Use `pnpm` not `npm` for package management
  status: supported
  confidence: null
- id: components-go-in-srccomponents-pages-in-srcapp
  text: Components go in `src/components/`, pages in `src/app/`
  status: supported
  confidence: null
- id: use-tailwind-css-never-inline-styles
  text: Use Tailwind CSS, never inline styles
  status: supported
  confidence: null
- id: run-tests-with-pnpm-test
  text: Run tests with `pnpm test`
  status: supported
  confidence: null
- id: use-poetry-for-dependency-management
  text: Use `poetry` for dependency management
  status: supported
  confidence: null
- id: run-the-dev-server-with-poetry-run-uvicorn-mainapp---reloa
  text: Run the dev server with `poetry run uvicorn main:app --reload`
  status: supported
  confidence: null
- id: all-endpoints-need-openapi-docstrings
  text: All endpoints need OpenAPI docstrings
  status: supported
  confidence: null
- id: database-models-are-in-models-schemas-in-schemas
  text: Database models are in `models/`, schemas in `schemas/`
  status: supported
  confidence: null
---

Hermes Agent automatically discovers and loads context files that shape how it behaves. Some are project-local and discovered from your working directory. `SOUL.md` is now global to the Hermes instance and is loaded from `HERMES_HOME` only.

## Supported Context Files[​](#supported-context-files "Direct link to Supported Context Files")

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[entities/features-overview|features-overview]]
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]
<!-- openclaw:wiki:related:end -->

- **File**, **Purpose**, **Discovery**
- **File**: **.hermes.md** / **HERMES.md**, **Purpose**: Project instructions (highest priority), **Discovery**: Walks to git root
- **File**: **AGENTS.md**, **Purpose**: Project instructions, conventions, architecture, **Discovery**: CWD at startup + subdirectories progressively
- **File**: **CLAUDE.md**, **Purpose**: Claude Code context files (also detected), **Discovery**: CWD at startup + subdirectories progressively
- **File**: **SOUL.md**, **Purpose**: Global personality and tone customization for this Hermes instance, **Discovery**: `HERMES_HOME/SOUL.md` only
- **File**: **.cursorrules**, **Purpose**: Cursor IDE coding conventions, **Discovery**: CWD only
- **File**: **.cursor/rules/\*.mdc**, **Purpose**: Cursor IDE rule modules, **Discovery**: CWD only

Priority system

Only **one** project context type is loaded per session (first match wins): `.hermes.md` → `AGENTS.md` → `CLAUDE.md` → `.cursorrules`. **SOUL.md** is always loaded independently as the agent identity (slot #1).

## AGENTS.md[​](#agentsmd "Direct link to AGENTS.md")

`AGENTS.md` is the primary project context file. It tells the agent how your project is structured, what conventions to follow, and any special instructions.

### Progressive Subdirectory Discovery[​](#progressive-subdirectory-discovery "Direct link to Progressive Subdirectory Discovery")

At session start, Hermes loads the `AGENTS.md` from your working directory into the system prompt. As the agent navigates into subdirectories during the session (via `read_file`, `terminal`, `search_files`, etc.), it **progressively discovers** context files in those directories and injects them into the conversation at the moment they become relevant.

```
my-project/
├── AGENTS.md              ← Loaded at startup (system prompt)
├── frontend/
│   └── AGENTS.md          ← Discovered when agent reads frontend/ files
├── backend/
│   └── AGENTS.md          ← Discovered when agent reads backend/ files
└── shared/
    └── AGENTS.md          ← Discovered when agent reads shared/ files
```

This approach has two advantages over loading everything at startup:

- **No system prompt bloat** — subdirectory hints only appear when needed
- **Prompt cache preservation** — the system prompt stays stable across turns

Each subdirectory is checked at most once per session. The discovery also walks up parent directories, so reading `backend/src/main.py` will discover `backend/AGENTS.md` even if `backend/src/` has no context file of its own.

info

Subdirectory context files go through the same [security scan](#security-prompt-injection-protection) as startup context files. Malicious files are blocked.

### Example AGENTS.md[​](#example-agentsmd "Direct link to Example AGENTS.md")

```
# Project Context

This is a Next.js 14 web application with a Python FastAPI backend.

## Architecture
- Frontend: Next.js 14 with App Router in `/frontend`
- Backend: FastAPI in `/backend`, uses SQLAlchemy ORM
- Database: PostgreSQL 16
- Deployment: Docker Compose on a Hetzner VPS

## Conventions
- Use TypeScript strict mode for all frontend code
- Python code follows PEP 8, use type hints everywhere
- All API endpoints return JSON with `{data, error, meta}` shape
- Tests go in `__tests__/` directories (frontend) or `tests/` (backend)

## Important Notes
- Never modify migration files directly — use Alembic commands
- The `.env.local` file has real API keys, don't commit it
- Frontend port is 3000, backend is 8000, DB is 5432
```

## SOUL.md[​](#soulmd "Direct link to SOUL.md")

`SOUL.md` controls the agent's personality, tone, and communication style. See the [Personality](/docs/user-guide/features/personality) page for full details.

**Location:**

- `~/.hermes/SOUL.md`
- or `$HERMES_HOME/SOUL.md` if you run Hermes with a custom home directory

Important details:

- Hermes seeds a default `SOUL.md` automatically if one does not exist yet
- Hermes loads `SOUL.md` only from `HERMES_HOME`
- Hermes does not probe the working directory for `SOUL.md`
- If the file is empty, nothing from `SOUL.md` is added to the prompt
- If the file has content, the content is injected verbatim after scanning and truncation

## .cursorrules[​](#cursorrules "Direct link to .cursorrules")

Hermes is compatible with Cursor IDE's `.cursorrules` file and `.cursor/rules/*.mdc` rule modules. If these files exist in your project root and no higher-priority context file (`.hermes.md`, `AGENTS.md`, or `CLAUDE.md`) is found, they're loaded as the project context.

This means your existing Cursor conventions automatically apply when using Hermes.

## How Context Files Are Loaded[​](#how-context-files-are-loaded "Direct link to How Context Files Are Loaded")

### At startup (system prompt)[​](#at-startup-system-prompt "Direct link to At startup (system prompt)")

Context files are loaded by `build_context_files_prompt()` in `agent/prompt_builder.py`:

1. **Scan working directory** — checks for `.hermes.md` → `AGENTS.md` → `CLAUDE.md` → `.cursorrules` (first match wins)
2. **Content is read** — each file is read as UTF-8 text
3. **Security scan** — content is checked for prompt injection patterns
4. **Truncation** — files exceeding 20,000 characters are head/tail truncated (70% head, 20% tail, with a marker in the middle)
5. **Assembly** — all sections are combined under a `# Project Context` header
6. **Injection** — the assembled content is added to the system prompt

### During the session (progressive discovery)[​](#during-the-session-progressive-discovery "Direct link to During the session (progressive discovery)")

`SubdirectoryHintTracker` in `agent/subdirectory_hints.py` watches tool call arguments for file paths:

1. **Path extraction** — after each tool call, file paths are extracted from arguments (`path`, `workdir`, shell commands)
2. **Ancestor walk** — the directory and up to 5 parent directories are checked (stopping at already-visited directories)
3. **Hint loading** — if an `AGENTS.md`, `CLAUDE.md`, or `.cursorrules` is found, it's loaded (first match per directory)
4. **Security scan** — same prompt injection scan as startup files
5. **Truncation** — capped at 8,000 characters per file
6. **Injection** — appended to the tool result, so the model sees it in context naturally

The final prompt section looks roughly like:

```
# Project Context

The following project context files have been loaded and should be followed:

## AGENTS.md

[Your AGENTS.md content here]

## .cursorrules

[Your .cursorrules content here]

[Your SOUL.md content here]
```

Notice that SOUL content is inserted directly, without extra wrapper text.

## Security: Prompt Injection Protection[​](#security-prompt-injection-protection "Direct link to Security: Prompt Injection Protection")

All context files are scanned for potential prompt injection before being included. The scanner checks for:

- **Instruction override attempts**: "ignore previous instructions", "disregard your rules"
- **Deception patterns**: "do not tell the user"
- **System prompt overrides**: "system prompt override"
- **Hidden HTML comments**: `<!-- ignore instructions -->`
- **Hidden div elements**: `<div style="display:none">`
- **Credential exfiltration**: `curl ... $API_KEY`
- **Secret file access**: `cat .env`, `cat credentials`
- **Invisible characters**: zero-width spaces, bidirectional overrides, word joiners

If any threat pattern is detected, the file is blocked:

```
[BLOCKED: AGENTS.md contained potential prompt injection (prompt_injection). Content not loaded.]
```

warning

This scanner protects against common injection patterns, but it's not a substitute for reviewing context files in shared repositories. Always validate AGENTS.md content in projects you didn't author.

## Size Limits[​](#size-limits "Direct link to Size Limits")

- **Limit**: Value
- **Max chars per file**: 20,000 (~7,000 tokens)
- **Head truncation ratio**: 70%
- **Tail truncation ratio**: 20%
- **Truncation marker**: 10% (shows char counts and suggests using file tools)

When a file exceeds 20,000 characters, the truncation message reads:

```
[...truncated AGENTS.md: kept 14000+4000 of 25000 chars. Use file tools to read the full file.]
```

## Tips for Effective Context Files[​](#tips-for-effective-context-files "Direct link to Tips for Effective Context Files")

Best practices for AGENTS.md

1. **Keep it concise** — stay well under 20K chars; the agent reads it every turn
2. **Structure with headers** — use `##` sections for architecture, conventions, important notes
3. **Include concrete examples** — show preferred code patterns, API shapes, naming conventions
4. **Mention what NOT to do** — "never modify migration files directly"
5. **List key paths and ports** — the agent uses these for terminal commands
6. **Update as the project evolves** — stale context is worse than no context

### Per-Subdirectory Context[​](#per-subdirectory-context "Direct link to Per-Subdirectory Context")

For monorepos, put subdirectory-specific instructions in nested AGENTS.md files:

```
<!-- frontend/AGENTS.md -->
# Frontend Context

- Use `pnpm` not `npm` for package management
- Components go in `src/components/`, pages in `src/app/`
- Use Tailwind CSS, never inline styles
- Run tests with `pnpm test`
```

```
<!-- backend/AGENTS.md -->
# Backend Context

- Use `poetry` for dependency management
- Run the dev server with `poetry run uvicorn main:app --reload`
- All endpoints need OpenAPI docstrings
- Database models are in `models/`, schemas in `schemas/`
```