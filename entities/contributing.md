---
pageType: entity
id: entity.contributing
title: Contributing
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/hermes-agent-contributing.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/hermes-agent-contributing.md
updatedAt: '2026-04-24T15:05:24.425611+00:00'
sourceIds:
- docsastralsh
- githubcom
- wwwconventionalcommi
- githubcom
- discordgg
- githubcom
- githubcom
- githubcom
sources:
- sourceId: docsastralsh
  sourceType: web
  sourcePath: https://docs.astral.sh/uv/
  title: '[install](https://docs.astral.sh/uv/)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent/blob/main/AGENTS.md#profiles-multi-instance-support
  title: '[AGENTS.md](https://github.com/NousResearch/hermes-agent/blob/main/AGENTS.md#profiles-multi-instance'
- sourceId: wwwconventionalcommi
  sourceType: web
  sourcePath: https://www.conventionalcommits.org/
  title: '[Conventional Commits](https://www.conventionalcommits.org/)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent/issues
  title: '[GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)'
- sourceId: discordgg
  sourceType: web
  sourcePath: https://discord.gg/NousResearch
  title: '[discord.gg/NousResearch](https://discord.gg/NousResearch)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent/blob/main/LICENSE
  title: '[MIT License](https://github.com/NousResearch/hermes-agent/blob/main/LICENSE)'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent/edit/main/website/docs/developer-guide/contributing.md
  title: '[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/developer-guide'
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent.gitcd
  title: github.com
claims:
- id: bug-fixes-crashes-incorrect-behavior-data-loss
  text: "Bug fixes** \u2014 crashes, incorrect behavior, data loss"
  status: supported
  confidence: null
- id: cross-platform-compatibility-macos-different-linux-dist
  text: "Cross-platform compatibility** \u2014 macOS, different Linux distros, WSL2"
  status: supported
  confidence: null
- id: security-hardening-shell-injection-prompt-injection-pa
  text: "Security hardening** \u2014 shell injection, prompt injection, path traversal"
  status: supported
  confidence: null
- id: performance-and-robustness-retry-logic-error-handling
  text: "Performance and robustness** \u2014 retry logic, error handling, graceful\
    \ degradation"
  status: supported
  confidence: null
- id: new-skills-broadly-useful-ones-see-creating-skillsd
  text: "New skills** \u2014 broadly useful ones (see [Creating Skills](/docs/developer-guide/creating-skills))"
  status: supported
  confidence: null
- id: new-tools-rarely-needed-most-capabilities-should-be-ski
  text: "New tools** \u2014 rarely needed; most capabilities should be skills"
  status: supported
  confidence: null
- id: documentation-fixes-clarifications-new-examples
  text: "Documentation** \u2014 fixes, clarifications, new examples"
  status: supported
  confidence: null
- id: building-a-new-tool-start-with-adding-toolsdocsdevelop
  text: Building a new tool? Start with [Adding Tools](/docs/developer-guide/adding-tools)
  status: supported
  confidence: null
- id: building-a-new-skill-start-with-creating-skillsdocsdev
  text: Building a new skill? Start with [Creating Skills](/docs/developer-guide/creating-skills)
  status: supported
  confidence: null
- id: building-a-new-inference-provider-start-with-adding-provid
  text: Building a new inference provider? Start with [Adding Providers](/docs/developer-guide/adding-providers)
  status: supported
  confidence: null
- id: pep-8-with-practical-exceptions-no-strict-line-length-enf
  text: PEP 8** with practical exceptions (no strict line length enforcement)
  status: supported
  confidence: null
- id: comments-only-when-explaining-non-obvious-intent-trade-o
  text: 'Comments**: Only when explaining non-obvious intent, trade-offs, or API quirks'
  status: supported
  confidence: null
- id: error-handling-catch-specific-exceptions-use-loggerwar
  text: 'Error handling**: Catch specific exceptions. Use `logger.warning()`/`logger.error()`
    with `exc_info=True` for unexpected errors'
  status: supported
  confidence: null
- id: cross-platform-never-assume-unix-see-below
  text: 'Cross-platform**: Never assume Unix (see below)'
  status: supported
  confidence: null
- id: profile-safe-paths-never-hardcode-hermes-use-get
  text: "Profile-safe paths**: Never hardcode `~/.hermes` \u2014 use `get_hermes_home()`\
    \ from `hermes_constants` for code paths and `display_hermes_home()` for user-facing\
    \ messages. See [AGENTS.md](https://github.com/NousResearch/hermes-agent/blob/main/AGENTS.md#profiles-multi-instance-support)\
    \ for full rules."
  status: supported
  confidence: null
- id: always-use-shlexquote-when-interpolating-user-input-int
  text: Always use `shlex.quote()` when interpolating user input into shell commands
  status: supported
  confidence: null
- id: resolve-symlinks-with-ospathrealpath-before-access-con
  text: Resolve symlinks with `os.path.realpath()` before access control checks
  status: supported
  confidence: null
- id: donx27t-log-secrets
  text: Don&#x27;t log secrets
  status: supported
  confidence: null
- id: catch-broad-exceptions-around-tool-execution
  text: Catch broad exceptions around tool execution
  status: supported
  confidence: null
- id: test-on-all-platforms-if-your-change-touches-file-paths-or-p
  text: Test on all platforms if your change touches file paths or processes
  status: supported
  confidence: null
- id: run-tests-pytest-tests--v
  text: 'Run tests**: `pytest tests/ -v`'
  status: supported
  confidence: null
- id: test-manually-run-hermes-and-exercise-the-code-path-you
  text: 'Test manually**: Run `hermes` and exercise the code path you changed'
  status: supported
  confidence: null
- id: check-cross-platform-impact-consider-macos-and-different
  text: 'Check cross-platform impact**: Consider macOS and different Linux distros'
  status: supported
  confidence: null
- id: keep-prs-focused-one-logical-change-per-pr
  text: 'Keep PRs focused**: One logical change per PR'
  status: supported
  confidence: null
- id: what-changed-and-why
  text: What** changed and **why**
  status: supported
  confidence: null
- id: how-to-test-it
  text: How to test** it
  status: supported
  confidence: null
- id: what-platforms-you-tested-on
  text: What platforms** you tested on
  status: supported
  confidence: null
- id: reference-any-related-issues
  text: Reference any related issues
  status: supported
  confidence: null
- id: use-github-issueshttpsgithubcomnousresearchhermes-a
  text: Use [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)
  status: supported
  confidence: null
- id: include-os-python-version-hermes-version-hermes-version
  text: 'Include: OS, Python version, Hermes version (`hermes version`), full error
    traceback'
  status: supported
  confidence: null
- id: include-steps-to-reproduce
  text: Include steps to reproduce
  status: supported
  confidence: null
- id: check-existing-issues-before-creating-duplicates
  text: Check existing issues before creating duplicates
  status: supported
  confidence: null
- id: for-security-vulnerabilities-please-report-privately
  text: For security vulnerabilities, please report privately
  status: supported
  confidence: null
- id: discord-discordggnousresearchhttpsdiscordggnous
  text: 'Discord**: [discord.gg/NousResearch](https://discord.gg/NousResearch)'
  status: supported
  confidence: null
- id: github-discussions-for-design-proposals-and-architecture
  text: 'GitHub Discussions**: For design proposals and architecture discussions'
  status: supported
  confidence: null
- id: skills-hub-upload-specialized-skills-and-share-with-the-c
  text: 'Skills Hub**: Upload specialized skills and share with the community'
  status: supported
  confidence: null
---

Thank you for contributing to Hermes Agent! This guide covers setting up your dev environment, understanding the codebase, and getting your PR merged.

## Contribution Priorities

## Related
<!-- openclaw:wiki:related:start -->
### Referenced By
- [[syntheses/index|Syntheses]]
- [[syntheses/racoony-ops|Raccoony Operations]]

### Related Pages
- [[entities/cli-commands-reference|CLI Commands Reference]]
- [[entities/architecture|Architecture]]
- [[entities/ai-providers|AI Providers]]
- [[entities/open-webui-integration|Open WebUI Integration]]
- [[entities/signal-setup|Signal Setup]]
- [[entities/security|Security]]
- [[entities/features-skills|Features: Skills]]
- [[entities/faq-troubleshooting|FAQ & Troubleshooting]]
- [[entities/use-voice-mode-with-hermes|Use Voice Mode with Hermes]]
- [[entities/use-mcp-with-hermes|Use MCP with Hermes]]
- [[entities/tips-best-practices|Tips & Best Practices]]
- [[entities/learning-path|Learning Path]]
- [[entities/installation|Installation]]
- [[entities/quickstart|Quickstart]]
- [[entities/android-termux|Android / Termux]]
- [[concepts/uncensored-ai-models|Uncensored AI Models]]
<!-- openclaw:wiki:related:end -->

We value contributions in this order:

- **Bug fixes** — crashes, incorrect behavior, data loss

- **Cross-platform compatibility** — macOS, different Linux distros, WSL2

- **Security hardening** — shell injection, prompt injection, path traversal

- **Performance and robustness** — retry logic, error handling, graceful degradation

- **New skills** — broadly useful ones (see [Creating Skills](/docs/developer-guide/creating-skills))

- **New tools** — rarely needed; most capabilities should be skills

- **Documentation** — fixes, clarifications, new examples

## Common contribution paths

- Building a new tool? Start with [Adding Tools](/docs/developer-guide/adding-tools)

- Building a new skill? Start with [Creating Skills](/docs/developer-guide/creating-skills)

- Building a new inference provider? Start with [Adding Providers](/docs/developer-guide/adding-providers)

## Development Setup

### Prerequisites

RequirementNotes**Git**With `--recurse-submodules` support, and the `git-lfs` extension installed**Python 3.11+**uv will install it if missing**uv**Fast Python package manager ([install](https://docs.astral.sh/uv/))**Node.js 20+**Optional — needed for browser tools and WhatsApp bridge (matches root `package.json` engines)
### Clone and Install

```
git clone --recurse-submodules https://github.com/NousResearch/hermes-agent.gitcd hermes-agent# Create venv with Python 3.11uv venv venv --python 3.11export VIRTUAL_ENV=&quot;$(pwd)/venv&quot;# Install with all extras (messaging, cron, CLI menus, dev tools)uv pip install -e &quot;.[all,dev]&quot;uv pip install -e &quot;./tinker-atropos&quot;# Optional: browser toolsnpm install
```
### Configure for Development

```
mkdir -p ~/.hermes/{cron,sessions,logs,memories,skills}cp cli-config.yaml.example ~/.hermes/config.yamltouch ~/.hermes/.env# Add at minimum an LLM provider key:echo &#x27;OPENROUTER_API_KEY=sk-or-v1-your-key&#x27; &gt;&gt; ~/.hermes/.env
```
### Run

```
# Symlink for global accessmkdir -p ~/.local/binln -sf &quot;$(pwd)/venv/bin/hermes&quot; ~/.local/bin/hermes# Verifyhermes doctorhermes chat -q &quot;Hello&quot;
```
### Run Tests

```
pytest tests/ -v
```
## Code Style

- **PEP 8** with practical exceptions (no strict line length enforcement)

- **Comments**: Only when explaining non-obvious intent, trade-offs, or API quirks

- **Error handling**: Catch specific exceptions. Use `logger.warning()`/`logger.error()` with `exc_info=True` for unexpected errors

- **Cross-platform**: Never assume Unix (see below)

- **Profile-safe paths**: Never hardcode `~/.hermes` — use `get_hermes_home()` from `hermes_constants` for code paths and `display_hermes_home()` for user-facing messages. See [AGENTS.md](https://github.com/NousResearch/hermes-agent/blob/main/AGENTS.md#profiles-multi-instance-support) for full rules.

## Cross-Platform Compatibility

Hermes officially supports Linux, macOS, and WSL2. Native Windows is **not supported**, but the codebase includes some defensive coding patterns to avoid hard crashes in edge cases. Key rules:

### 1. `termios` and `fcntl` are Unix-only

Always catch both `ImportError` and `NotImplementedError`:

```
try:    from simple_term_menu import TerminalMenu    menu = TerminalMenu(options)    idx = menu.show()except (ImportError, NotImplementedError):    # Fallback: numbered menu    for i, opt in enumerate(options):        print(f&quot;  {i+1}. {opt}&quot;)    idx = int(input(&quot;Choice: &quot;)) - 1
```
### 2. File encoding

Some environments may save `.env` files in non-UTF-8 encodings:

```
try:    load_dotenv(env_path)except UnicodeDecodeError:    load_dotenv(env_path, encoding=&quot;latin-1&quot;)
```
### 3. Process management

`os.setsid()`, `os.killpg()`, and signal handling differ across platforms:

```
import platformif platform.system() != &quot;Windows&quot;:    kwargs[&quot;preexec_fn&quot;] = os.setsid
```
### 4. Path separators

Use `pathlib.Path` instead of string concatenation with `/`.

## Security Considerations

Hermes has terminal access. Security matters.

### Existing Protections

LayerImplementation**Sudo password piping**Uses `shlex.quote()` to prevent shell injection**Dangerous command detection**Regex patterns in `tools/approval.py` with user approval flow**Cron prompt injection**Scanner blocks instruction-override patterns**Write deny list**Protected paths resolved via `os.path.realpath()` to prevent symlink bypass**Skills guard**Security scanner for hub-installed skills**Code execution sandbox**Child process runs with API keys stripped**Container hardening**Docker: all capabilities dropped, no privilege escalation, PID limits
### Contributing Security-Sensitive Code

- Always use `shlex.quote()` when interpolating user input into shell commands

- Resolve symlinks with `os.path.realpath()` before access control checks

- Don&#x27;t log secrets

- Catch broad exceptions around tool execution

- Test on all platforms if your change touches file paths or processes

## Pull Request Process

### Branch Naming

```
fix/description        # Bug fixesfeat/description       # New featuresdocs/description       # Documentationtest/description       # Testsrefactor/description   # Code restructuring
```
### Before Submitting

- **Run tests**: `pytest tests/ -v`

- **Test manually**: Run `hermes` and exercise the code path you changed

- **Check cross-platform impact**: Consider macOS and different Linux distros

- **Keep PRs focused**: One logical change per PR

### PR Description

Include:

- **What** changed and **why**

- **How to test** it

- **What platforms** you tested on

- Reference any related issues

### Commit Messages

We use [Conventional Commits](https://www.conventionalcommits.org/):

```
&lt;type&gt;(&lt;scope&gt;): &lt;description&gt;
```
TypeUse for`fix`Bug fixes`feat`New features`docs`Documentation`test`Tests`refactor`Code restructuring`chore`Build, CI, dependency updates
Scopes: `cli`, `gateway`, `tools`, `skills`, `agent`, `install`, `whatsapp`, `security`

Examples:

```
fix(cli): prevent crash in save_config_value when model is a stringfeat(gateway): add WhatsApp multi-user session isolationfix(security): prevent shell injection in sudo password piping
```
## Reporting Issues

- Use [GitHub Issues](https://github.com/NousResearch/hermes-agent/issues)

- Include: OS, Python version, Hermes version (`hermes version`), full error traceback

- Include steps to reproduce

- Check existing issues before creating duplicates

- For security vulnerabilities, please report privately

## Community

- **Discord**: [discord.gg/NousResearch](https://discord.gg/NousResearch)

- **GitHub Discussions**: For design proposals and architecture discussions

- **Skills Hub**: Upload specialized skills and share with the community

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](https://github.com/NousResearch/hermes-agent/blob/main/LICENSE).
[Edit this page](https://github.com/NousResearch/hermes-agent/edit/main/website/docs/developer-guide/contributing.md)