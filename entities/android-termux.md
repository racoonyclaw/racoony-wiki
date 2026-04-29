---
pageType: entity
id: entity.android-termux
title: Android / Termux
provenanceMode: unsafe-local
sourcePath: /tmp/hermes-docs/android-termux.md
unsafeLocalConfiguredPath: /media/racoony-wiki
unsafeLocalRelativePath: /tmp/hermes-docs/android-termux.md
updatedAt: '2026-04-24T15:05:26.587388+00:00'
sourceIds:
- rawgithubusercontent
- githubcom
sources:
- sourceId: rawgithubusercontent
  sourceType: web
  sourcePath: https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh
  title: raw.githubusercontent.com
- sourceId: githubcom
  sourceType: web
  sourcePath: https://github.com/NousResearch/hermes-agent.git
  title: github.com
claims:
- id: the-hermes-cli
  text: the Hermes CLI
  status: supported
  confidence: null
- id: cron-support
  text: cron support
  status: supported
  confidence: null
- id: ptybackground-terminal-support
  text: PTY/background terminal support
  status: supported
  confidence: null
- id: telegram-gateway-support-manual-best-effort-background-ru
  text: Telegram gateway support (manual / best-effort background runs)
  status: supported
  confidence: null
- id: mcp-support
  text: MCP support
  status: supported
  confidence: null
- id: honcho-memory-support
  text: Honcho memory support
  status: supported
  confidence: null
- id: acp-support
  text: ACP support
  status: supported
  confidence: null
- id: all-is-not-supported-on-android-today
  text: '`.[all]` is not supported on Android today'
  status: supported
  confidence: null
- id: the-voice-extra-is-blocked-by-faster-whisper---ctranslate2
  text: the voice extra is blocked by faster-whisper -> ctranslate2, and ctranslate2
    does not publish Android wheels
  status: supported
  confidence: null
- id: automatic-browser-playwright-bootstrap-is-skipped-in-the-t
  text: automatic browser / Playwright bootstrap is skipped in the Termux installer
  status: supported
  confidence: null
- id: docker-based-terminal-isolation-is-not-available-inside-term
  text: Docker-based terminal isolation is not available inside Termux
  status: supported
  confidence: null
- id: android-may-still-suspend-termux-background-jobs-so-gateway
  text: Android may still suspend Termux background jobs, so gateway persistence is
    best-effort rather than a normal managed service
  status: supported
  confidence: null
- id: uses-pkg-for-system-packages
  text: uses pkg for system packages
  status: supported
  confidence: null
- id: creates-the-venv-with-python--m-venv
  text: creates the venv with `python -m venv`
  status: supported
  confidence: null
- id: installs-termux-with-pip
  text: installs `.[termux]` with pip
  status: supported
  confidence: null
- id: links-hermes-into-prefixbin-so-it-stays-on-your-termux-p
  text: links hermes into `$PREFIX/bin` so it stays on your Termux PATH
  status: supported
  confidence: null
- id: skips-the-untested-browser-whatsapp-bootstrap
  text: skips the untested browser / WhatsApp bootstrap
  status: supported
  confidence: null
- id: python-runtime-venv-support
  text: "python \u2014 runtime + venv support"
  status: supported
  confidence: null
- id: git-cloneupdate-the-repo
  text: "git \u2014 clone/update the repo"
  status: supported
  confidence: null
- id: clang-rust-make-pkg-config-libffi-openssl-needed-to-b
  text: "clang, rust, make, pkg-config, libffi, openssl \u2014 needed to build a few\
    \ Python dependencies on Android"
  status: supported
  confidence: null
- id: nodejs-optional-node-runtime-for-experiments-beyond-the-te
  text: "nodejs \u2014 optional Node runtime for experiments beyond the tested core\
    \ path"
  status: supported
  confidence: null
- id: ripgrep-fast-file-search
  text: "ripgrep \u2014 fast file search"
  status: supported
  confidence: null
- id: ffmpeg-media-tts-conversions
  text: "ffmpeg \u2014 media / TTS conversions"
  status: supported
  confidence: null
- id: voice-pulls-faster-whisper
  text: voice pulls faster-whisper
  status: supported
  confidence: null
- id: faster-whisper-depends-on-ctranslate2
  text: faster-whisper depends on ctranslate2
  status: supported
  confidence: null
- id: ctranslate2-does-not-publish-android-wheels
  text: ctranslate2 does not publish Android wheels
  status: supported
  confidence: null
- id: docker-backend-is-unavailable
  text: Docker backend is unavailable
  status: supported
  confidence: null
- id: local-voice-transcription-via-faster-whisper-is-unavailable
  text: local voice transcription via faster-whisper is unavailable in the tested
    path
  status: supported
  confidence: null
- id: browser-automation-setup-is-intentionally-skipped-by-the-ins
  text: browser automation setup is intentionally skipped by the installer
  status: supported
  confidence: null
- id: some-optional-extras-may-work-but-only-termux-is-curre
  text: some optional extras may work, but only `.[termux]` is currently documented
    as the tested Android bundle
  status: supported
  confidence: null
- id: your-android-version
  text: your Android version
  status: supported
  confidence: null
- id: termux-info
  text: termux-info
  status: supported
  confidence: null
- id: python---version
  text: python --version
  status: supported
  confidence: null
- id: hermes-doctor
  text: hermes doctor
  status: supported
  confidence: null
- id: the-exact-install-command-and-full-error-output
  text: the exact install command and full error output
  status: supported
  confidence: null
---

# Hermes on Android with Termux

This is the tested path for running Hermes Agent directly on an Android phone through Termux.

It gives you a working local CLI on the phone, plus the core extras that are currently known to install cleanly on Android.

## What is supported in the tested path?

The tested Termux bundle installs:

- the Hermes CLI
- cron support
- PTY/background terminal support
- Telegram gateway support (manual / best-effort background runs)
- MCP support
- Honcho memory support
- ACP support

Concretely, it maps to:

```
python -m pip install -e '.[termux]' -c constraints-termux.txt
```

## What is not part of the tested path yet?

A few features still need desktop/server-style dependencies that are not published for Android, or have not been validated on phones yet:

- `.[all]` is not supported on Android today
- the voice extra is blocked by faster-whisper -> ctranslate2, and ctranslate2 does not publish Android wheels
- automatic browser / Playwright bootstrap is skipped in the Termux installer
- Docker-based terminal isolation is not available inside Termux
- Android may still suspend Termux background jobs, so gateway persistence is best-effort rather than a normal managed service

That does not stop Hermes from working well as a phone-native CLI agent — it just means the recommended mobile install is intentionally narrower than the desktop/server install.

## Option 1: One-line installer

Hermes now ships a Termux-aware installer path:

```
curl -fsSL https://raw.githubusercontent.com/NousResearch/hermes-agent/main/scripts/install.sh | bash
```

On Termux, the installer automatically:

- uses pkg for system packages
- creates the venv with `python -m venv`
- installs `.[termux]` with pip
- links hermes into `$PREFIX/bin` so it stays on your Termux PATH
- skips the untested browser / WhatsApp bootstrap

If you want the explicit commands or need to debug a failed install, use the manual path below.

## Option 2: Manual install (fully explicit)

**1. Update Termux and install system packages:**
```
pkg update
pkg install -y git python clang rust make pkg-config libffi openssl nodejs ripgrep ffmpeg
```

Why these packages?

- python — runtime + venv support
- git — clone/update the repo
- clang, rust, make, pkg-config, libffi, openssl — needed to build a few Python dependencies on Android
- nodejs — optional Node runtime for experiments beyond the tested core path
- ripgrep — fast file search
- ffmpeg — media / TTS conversions

**2. Clone Hermes:**
```
git clone --recurse-submodules https://github.com/NousResearch/hermes-agent.git
cd hermes-agent
```

If you already cloned without submodules:
```
git submodule update --init --recursive
```

**3. Create a virtual environment:**
```
python -m venv venv
source venv/bin/activate
export ANDROID_API_LEVEL="$(getprop ro.build.version.sdk)"
python -m pip install --upgrade pip setuptools wheel
```

ANDROID_API_LEVEL is important for Rust / maturin-based packages such as jiter.

**4. Install the tested Termux bundle:**
```
python -m pip install -e '.[termux]' -c constraints-termux.txt
```

If you only want the minimal core agent, this also works:
```
python -m pip install -e '.' -c constraints-termux.txt
```

**5. Put hermes on your Termux PATH:**
```
ln -sf "$PWD/venv/bin/hermes" "$PREFIX/bin/hermes"
```

$PREFIX/bin is already on PATH in Termux, so this makes the hermes command persist across new shells without re-activating the venv every time.

**6. Verify the install:**
```
hermes version
hermes doctor
```

**7. Start Hermes:**
```
hermes
```

## Recommended follow-up setup

**Configure a model:**
```
hermes model
```

Or set keys directly in `~/.hermes/.env`.

**Re-run the full interactive setup wizard later:**
```
hermes setup
```

**Install optional Node dependencies manually:**

The tested Termux path skips Node/browser bootstrap on purpose. If you want to experiment with browser tooling later:

```
pkg install nodejs-lts
npm install
```

The browser tool automatically includes Termux directories (`/data/data/com.termux/files/usr/bin`) in its PATH search, so agent-browser and npx are discovered without any extra PATH configuration.

Treat browser / WhatsApp tooling on Android as experimental until documented otherwise.

## Troubleshooting

**No solution found when installing `.[all]`**

Use the tested Termux bundle instead:

```
python -m pip install -e '.[termux]' -c constraints-termux.txt
```

The blocker is currently the voice extra:

- voice pulls faster-whisper
- faster-whisper depends on ctranslate2
- ctranslate2 does not publish Android wheels

**uv pip install fails on Android**

Use the Termux path with the stdlib venv + pip instead:

```
python -m venv venv
source venv/bin/activate
export ANDROID_API_LEVEL="$(getprop ro.build.version.sdk)"
python -m pip install --upgrade pip setuptools wheel
python -m pip install -e '.[termux]' -c constraints-termux.txt
```

**jiter / maturin complains about ANDROID_API_LEVEL**

Set the API level explicitly before installing:

```
export ANDROID_API_LEVEL="$(getprop ro.build.version.sdk)"
python -m pip install -e '.[termux]' -c constraints-termux.txt
```

**hermes doctor says ripgrep or Node is missing**

Install them with Termux packages:

```
pkg install ripgrep nodejs
```

**Build failures while installing Python packages**

Make sure the build toolchain is installed:

```
pkg install clang rust make pkg-config libffi openssl
```

Then retry:

```
python -m pip install -e '.[termux]' -c constraints-termux.txt
```

## Known limitations on phones

- Docker backend is unavailable
- local voice transcription via faster-whisper is unavailable in the tested path
- browser automation setup is intentionally skipped by the installer
- some optional extras may work, but only `.[termux]` is currently documented as the tested Android bundle

If you hit a new Android-specific issue, please open a GitHub issue with:

- your Android version
- termux-info
- python --version
- hermes doctor
- the exact install command and full error output