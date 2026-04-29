---
pageType: entity
id: entity.cli-interface
title: CLI Interface
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/cli-interface.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/cli-interface.md
updatedAt: '2026-04-24T15:05:26.350349+00:00'
claims:
- id: model-name-current-model-truncated-if-longer-than-26-ch
  text: "Model name** \u2014 Current model (truncated if longer than 26 chars)"
  status: supported
  confidence: null
- id: token-count-context-tokens-used-max-context-window
  text: "Token count** \u2014 Context tokens used / max context window"
  status: supported
  confidence: null
- id: context-bar-visual-fill-indicator-with-color-coded-thres
  text: "Context bar** \u2014 Visual fill indicator with color-coded thresholds"
  status: supported
  confidence: null
- id: cost-estimated-session-cost-or-na-for-unknownzero-pri
  text: "Cost** \u2014 Estimated session cost (or n/a for unknown/zero-priced models)"
  status: supported
  confidence: null
- id: duration-elapsed-session-time
  text: "Duration** \u2014 Elapsed session time"
  status: supported
  confidence: null
- id: full-layout-at-76-columns
  text: "Full layout at \u2265 76 columns"
  status: supported
  confidence: null
- id: compact-at-5275-columns
  text: "Compact at 52\u201375 columns"
  status: supported
  confidence: null
- id: minimal-model-duration-only-below-52-columns
  text: Minimal (model + duration only) below 52 columns
  status: supported
  confidence: null
- id: green-50-plenty-of-room
  text: "Green** < 50% \u2014 Plenty of room"
  status: supported
  confidence: null
- id: yellow-5080-getting-full
  text: "Yellow** 50\u201380% \u2014 Getting full"
  status: supported
  confidence: null
- id: orange-8095-approaching-limit
  text: "Orange** 80\u201395% \u2014 Approaching limit"
  status: supported
  confidence: null
- id: red-95-near-overflow-consider-compress
  text: "Red** \u2265 95% \u2014 Near overflow \u2014 consider `/compress`"
  status: supported
  confidence: null
- id: help-show-command-help
  text: "`/help` \u2014 Show command help"
  status: supported
  confidence: null
- id: model-show-or-change-the-current-model
  text: "`/model` \u2014 Show or change the current model"
  status: supported
  confidence: null
- id: tools-list-currently-available-tools
  text: "`/tools` \u2014 List currently available tools"
  status: supported
  confidence: null
- id: skills-browse-browse-the-skills-hub-and-official-option
  text: "`/skills browse` \u2014 Browse the skills hub and official optional skills"
  status: supported
  confidence: null
- id: background-prompt-run-a-prompt-in-a-separate-backgrou
  text: "`/background <prompt>` \u2014 Run a prompt in a separate background session"
  status: supported
  confidence: null
- id: skin-show-or-switch-the-active-cli-skin
  text: "`/skin` \u2014 Show or switch the active CLI skin"
  status: supported
  confidence: null
- id: voice-on-enable-cli-voice-mode-press-ctrlb-to-record
  text: "`/voice on` \u2014 Enable CLI voice mode (press Ctrl+B to record)"
  status: supported
  confidence: null
- id: voice-tts-toggle-spoken-playback-for-hermes-replies
  text: "`/voice tts` \u2014 Toggle spoken playback for Hermes replies"
  status: supported
  confidence: null
- id: reasoning-high-increase-reasoning-effort
  text: "`/reasoning high` \u2014 Increase reasoning effort"
  status: supported
  confidence: null
- id: title-my-session-name-the-current-session
  text: "`/title My Session` \u2014 Name the current session"
  status: supported
  confidence: null
- id: type-a-new-message-enter-while-the-agent-is-working-it-i
  text: "Type a new message + Enter while the agent is working \u2014 it interrupts\
    \ and processes your new instructions"
  status: supported
  confidence: null
- id: ctrlc-interrupt-the-current-operation-press-twice-with
  text: "Ctrl+C** \u2014 interrupt the current operation (press twice within 2s to\
    \ force exit)"
  status: supported
  confidence: null
- id: interrupt-default-your-message-interrupts-the-curren
  text: "\"interrupt\"** (default) \u2014 Your message interrupts the current operation\
    \ and is processed immediately"
  status: supported
  confidence: null
- id: queue-your-message-is-silently-queued-and-sent-as-the
  text: "\"queue\"** \u2014 Your message is silently queued and sent as the next turn\
    \ after the agent finishes"
  status: supported
  confidence: null
- id: session-metadata-id-title-timestamps-token-counters
  text: session metadata (ID, title, timestamps, token counters)
  status: supported
  confidence: null
- id: message-history
  text: message history
  status: supported
  confidence: null
- id: lineage-across-compressedresumed-sessions
  text: lineage across compressed/resumed sessions
  status: supported
  confidence: null
- id: full-text-search-indexes-used-by-session-search
  text: full-text search indexes used by session_search
  status: supported
  confidence: null
- id: isolated-conversation-the-background-agent-has-no-knowle
  text: "Isolated conversation** \u2014 the background agent has no knowledge of your\
    \ current session's history. It receives only the prompt you provide."
  status: supported
  confidence: null
- id: same-configuration-the-background-agent-inherits-your-mo
  text: "Same configuration** \u2014 the background agent inherits your model, provider,\
    \ toolsets, reasoning settings, and fallback model from the current session."
  status: supported
  confidence: null
- id: non-blocking-your-foreground-session-stays-fully-interac
  text: "Non-blocking** \u2014 your foreground session stays fully interactive. You\
    \ can chat, run commands, or even start more background tasks."
  status: supported
  confidence: null
- id: multiple-tasks-you-can-run-several-background-tasks-simu
  text: "Multiple tasks** \u2014 you can run several background tasks simultaneously.\
    \ Each gets a numbered ID."
  status: supported
  confidence: null
- id: long-running-research-background-research-the-latest-d
  text: "Long-running research** \u2014 \"/background research the latest developments\
    \ in quantum error correction\" while you work on code"
  status: supported
  confidence: null
- id: file-processing-background-analyze-all-python-files-in
  text: "File processing** \u2014 \"/background analyze all Python files in this repo\
    \ and list any security issues\" while you continue a conversation"
  status: supported
  confidence: null
- id: parallel-investigations-start-multiple-background-tasks
  text: "Parallel investigations** \u2014 start multiple background tasks to explore\
    \ different angles simultaneously"
  status: supported
  confidence: null
- id: suppresses-verbose-logging-from-tools
  text: Suppresses verbose logging from tools
  status: supported
  confidence: null
- id: enables-kawaii-style-animated-feedback
  text: Enables kawaii-style animated feedback
  status: supported
  confidence: null
- id: keeps-output-clean-and-user-friendly
  text: Keeps output clean and user-friendly
  status: supported
  confidence: null
---

# CLI Interface

Hermes Agent's CLI is a full terminal user interface (TUI) — not a web UI. It features multiline editing, slash-command autocomplete, conversation history, interrupt-and-redirect, and streaming tool output. Built for people who live in the terminal.

> **TIP:** Hermes also ships a modern TUI with modal overlays, mouse selection, and non-blocking input. Launch it with `hermes --tui` — see the [TUI](./tui) guide.

## Running the CLI

```bash
# Start an interactive session (default)
hermes

# Single query mode (non-interactive)
hermes chat -q "Hello"

# With a specific model
hermes chat --model "anthropic/claude-sonnet-4"

# With a specific provider
hermes chat --provider nous        # Use Nous Portal
hermes chat --provider openrouter  # Force OpenRouter

# With specific toolsets
hermes chat --toolsets "web,terminal,skills"

# Start with one or more skills preloaded
hermes -s hermes-agent-dev,github-auth
hermes chat -s github-pr-workflow -q "open a draft PR"

# Resume previous sessions
hermes --continue             # Resume the most recent CLI session (-c)
hermes --resume <session_id>  # Resume a specific session by ID (-r)

# Verbose mode (debug output)
hermes chat --verbose

# Isolated git worktree (for running multiple agents in parallel)
hermes -w                         # Interactive mode in worktree
hermes -w -q "Fix issue #123"     # Single query in worktree
```

## Interface Layout

The Hermes CLI banner, conversation stream, and fixed input prompt rendered as a stable docs figure instead of fragile text art.

The welcome banner shows your model, terminal backend, working directory, available tools, and installed skills at a glance.

### Status Bar

A persistent status bar sits above the input area, updating in real time:

```
⚕ claude-sonnet-4-20250514 │ 12.4K/200K │ [██████░░░░] 6% │ $0.06 │ 15m
```

**Status Bar Elements:**

- **Model name** — Current model (truncated if longer than 26 chars)
- **Token count** — Context tokens used / max context window
- **Context bar** — Visual fill indicator with color-coded thresholds
- **Cost** — Estimated session cost (or n/a for unknown/zero-priced models)
- **Duration** — Elapsed session time

The bar adapts to terminal width:
- Full layout at ≥ 76 columns
- Compact at 52–75 columns
- Minimal (model + duration only) below 52 columns

**Context color coding:**

- **Green** < 50% — Plenty of room
- **Yellow** 50–80% — Getting full
- **Orange** 80–95% — Approaching limit
- **Red** ≥ 95% — Near overflow — consider `/compress`

Use `/usage` for a detailed breakdown including per-category costs (input vs output tokens).

### Session Resume Display

When resuming a previous session (`hermes -c` or `hermes --resume <id>`), a "Previous Conversation" panel appears between the banner and the input prompt, showing a compact recap of the conversation history. See Sessions — Conversation Recap on Resume for details and configuration.

## Keybindings

| Key | Action |
|-----|--------|
| Enter | Send message |
| Alt+Enter or Ctrl+J | New line (multi-line input) |
| Alt+V | Paste an image from the clipboard when supported by the terminal |
| Ctrl+V | Paste text and opportunistically attach clipboard images |
| Ctrl+B | Start/stop voice recording when voice mode is enabled (voice.record_key, default: ctrl+b) |
| Ctrl+C | Interrupt agent (double-press within 2s to force exit) |
| Ctrl+D | Exit |
| Ctrl+Z | Suspend Hermes to background (Unix only). Run `fg` in the shell to resume. |
| Tab | Accept auto-suggestion (ghost text) or autocomplete slash commands |

## Slash Commands

Type `/` to see the autocomplete dropdown. Hermes supports a large set of CLI slash commands, dynamic skill commands, and user-defined quick commands.

**Common examples:**

- `/help` — Show command help
- `/model` — Show or change the current model
- `/tools` — List currently available tools
- `/skills browse` — Browse the skills hub and official optional skills
- `/background <prompt>` — Run a prompt in a separate background session
- `/skin` — Show or switch the active CLI skin
- `/voice on` — Enable CLI voice mode (press Ctrl+B to record)
- `/voice tts` — Toggle spoken playback for Hermes replies
- `/reasoning high` — Increase reasoning effort
- `/title My Session` — Name the current session

For the full built-in CLI and messaging lists, see Slash Commands Reference. For setup, providers, silence tuning, and messaging/Discord voice usage, see Voice Mode.

> **TIP:** Commands are case-insensitive — `/HELP` works the same as `/help`. Installed skills also become slash commands automatically.

### Quick Commands

You can define custom commands that run shell commands instantly without invoking the LLM. These work in both the CLI and messaging platforms (Telegram, Discord, etc.).

```yaml
# ~/.hermes/config.yaml
quick_commands:
  status:
    type: exec
    command: systemctl status hermes-agent
  gpu:
    type: exec
    command: nvidia-smi --query-gpu=utilization.gpu,memory.used --format=csv,noheader
```

Then type `/status` or `/gpu` in any chat. See the Configuration guide for more examples.

### Preloading Skills at Launch

If you already know which skills you want active for the session, pass them at launch time:

```bash
hermes -s hermes-agent-dev,github-auth
hermes chat -s github-pr-workflow -s github-auth
```

Hermes loads each named skill into the session prompt before the first turn. The same flag works in interactive mode and single-query mode.

### Skill Slash Commands

Every installed skill in `~/.hermes/skills/` is automatically registered as a slash command. The skill name becomes the command:

```bash
/gif-search funny cats
/axolotl help me fine-tune Llama 3 on my dataset
/github-pr-workflow create a PR for the auth refactor
# Just the skill name loads it and lets the agent ask what you need:
/excalotl
```

### Personalities

Set a predefined personality to change the agent's tone:

```bash
/personality pirate
/personality kawaii
/personality concise
```

Built-in personalities include: helpful, concise, technical, creative, teacher, kawaii, catgirl, pirate, shakespeare, surfer, noir, uwu, philosopher, hype.

You can also define custom personalities in `~/.hermes/config.yaml`:

```yaml
personalities:
  helpful: "You are a helpful, friendly AI assistant."
  kawaii: "You are a kawaii assistant! Use cute expressions..."
  pirate: "Arrr! Ye be talkin' to Captain Hermes..."
  # Add your own!
```

## Multi-line Input

There are two ways to enter multi-line messages:

1. **Alt+Enter or Ctrl+J** — inserts a new line
2. **Backslash continuation** — end a line with `\` to continue:

```
❯ Write a function that:\
  1. Takes a list of numbers\
  2. Returns the sum
```

> **INFO:** Pasting multi-line text is supported — use Alt+Enter or Ctrl+J to insert newlines, or simply paste content directly.

## Interrupting the Agent

You can interrupt the agent at any point:

- Type a new message + Enter while the agent is working — it interrupts and processes your new instructions
- **Ctrl+C** — interrupt the current operation (press twice within 2s to force exit)

In-progress terminal commands are killed immediately (SIGTERM, then SIGKILL after 1s). Multiple messages typed during interrupt are combined into one prompt.

### Busy Input Mode

The `display.busy_input_mode` config key controls what happens when you press Enter while the agent is working:

- **"interrupt"** (default) — Your message interrupts the current operation and is processed immediately
- **"queue"** — Your message is silently queued and sent as the next turn after the agent finishes

```yaml
# ~/.hermes/config.yaml
display:
  busy_input_mode: "queue"   # or "interrupt" (default)
```

Queue mode is useful when you want to prepare follow-up messages without accidentally canceling in-flight work. Unknown values fall back to "interrupt".

## Suspending to Background

On Unix systems, press **Ctrl+Z** to suspend Hermes to the background — just like any terminal process. The shell prints a confirmation:

```
Hermes Agent has been suspended. Run `fg` to bring Hermes Agent back.
```

Type `fg` in your shell to resume the session exactly where you left off. This is not supported on Windows.

## Tool Progress Display

The CLI shows animated feedback as the agent works:

**Thinking animation** (during API calls):
```
  ◜ (｡•́︿•̀｡) pondering... (1.2s)
  ◠ (⊙_⊙) contemplating... (2.4s)
  ✧٩(ˊᗜˋ*)و✧ got it! (3.1s)
```

**Tool execution feed:**
```
  ┊ 💻 terminal `ls -la` (0.3s)
  ┊ 🔍 web_search (1.2s)
  ┊ 📄 web_extract (2.1s)
```

Cycle through display modes with `/verbose: off → new → all → verbose`. This command can also be enabled for messaging platforms — see configuration.

### Tool Preview Length

The `display.tool_preview_length` config key controls the maximum number of characters shown in tool call preview lines (e.g. file paths, terminal commands). The default is 0, which means no limit — full paths and commands are shown.

```yaml
# ~/.hermes/config.yaml
display:
  tool_preview_length: 80   # Truncate tool previews to 80 chars (0 = no limit)
```

This is useful on narrow terminals or when tool arguments contain very long file paths.

## Session Management

### Resuming Sessions

When you exit a CLI session, a resume command is printed:

```
Resume this session with:
  hermes --resume 20260225_143052_a1b2c3
Session:        20260225_143052_a1b2c3
Duration:       12m 34s
Messages:       28 (5 user, 18 tool calls)
```

**Resume options:**
```bash
hermes --continue                          # Resume the most recent CLI session
hermes -c                                  # Short form
hermes -c "my project"                     # Resume a named session (latest in lineage)
hermes --resume 20260225_143052_a1b2c3     # Resume a specific session by ID
hermes --resume "refactoring auth"         # Resume by title
hermes -r 20260225_143052_a1b2c3           # Short form
```

Resuming restores the full conversation history from SQLite. The agent sees all previous messages, tool calls, and responses — just as if you never left.

Use `/title My Session Name` inside a chat to name the current session, or `hermes sessions rename <id> <title>` from the command line. Use `hermes sessions list` to browse past sessions.

### Session Storage

CLI sessions are stored in Hermes's SQLite state database under `~/.hermes/state.db`. The database keeps:

- session metadata (ID, title, timestamps, token counters)
- message history
- lineage across compressed/resumed sessions
- full-text search indexes used by session_search

Some messaging adapters also keep per-platform transcript files alongside the database, but the CLI itself resumes from the SQLite session store.

### Context Compression

Long conversations are automatically summarized when approaching context limits:

```yaml
# In ~/.hermes/config.yaml
compression:
  enabled: true
  threshold: 0.50    # Compress at 50% of context limit by default

# Summarization model configured under auxiliary:
auxiliary:
  compression:
    model: "google/gemini-3-flash-preview"  # Model used for summarization
```

When compression triggers, middle turns are summarized while the first 3 and last 4 turns are always preserved.

## Background Sessions

Run a prompt in a separate background session while continuing to use the CLI for other work:

```
/background Analyze the logs in /var/log and summarize any errors from today
```

Hermes immediately confirms the task and gives you back the prompt:

```
🔄 Background task #1 started: "Analyze the logs in /var/log and summarize..."
   Task ID: bg_143022_a1b2c3
```

### How It Works

Each `/background` prompt spawns a completely separate agent session in a daemon thread:

- **Isolated conversation** — the background agent has no knowledge of your current session's history. It receives only the prompt you provide.
- **Same configuration** — the background agent inherits your model, provider, toolsets, reasoning settings, and fallback model from the current session.
- **Non-blocking** — your foreground session stays fully interactive. You can chat, run commands, or even start more background tasks.
- **Multiple tasks** — you can run several background tasks simultaneously. Each gets a numbered ID.

### Results

When a background task finishes, the result appears as a panel in your terminal:

```
╭─ ⚕ Hermes (background #1) ──────────────────────────────────╮
│ Found 3 errors in syslog from today:                         │
│ 1. OOM killer invoked at 03:22 — killed process nginx        │
│ 2. Disk I/O error on /dev/sda1 at 07:15                      │
│ 3. Failed SSH login attempts from 192.168.1.50 at 14:30      │
╰──────────────────────────────────────────────────────────────╯
```

If the task fails, you'll see an error notification instead. If `display.bell_on_complete` is enabled in your config, the terminal bell rings when the task finishes.

### Use Cases

- **Long-running research** — "/background research the latest developments in quantum error correction" while you work on code
- **File processing** — "/background analyze all Python files in this repo and list any security issues" while you continue a conversation
- **Parallel investigations** — start multiple background tasks to explore different angles simultaneously

> **INFO:** Background sessions do not appear in your main conversation history. They are standalone sessions with their own task ID (e.g., bg_143022_a1b2c3).

## Quiet Mode

By default, the CLI runs in quiet mode which:

- Suppresses verbose logging from tools
- Enables kawaii-style animated feedback
- Keeps output clean and user-friendly

For debug output:
```bash
hermes chat --verbose
```