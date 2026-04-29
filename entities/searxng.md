---
id: entity.searxng
title: SearXNG
pageType: entity
created: 2026-04-23
tags:
  - infrastructure
  - search
  - self-hosted
confidence: high
---

# SearXNG

Privacy-respecting metasearch engine running as a Docker container on this system.

## Access

- **URL**: `http://searxng`
- **JSON API**: `http://searxng/search?q=<query>&format=json`
- **Host mapping**: `/etc/hosts` maps `127.0.0.1` to `searxng`

## Deployment

- **Container**: `searxng-core`
- **Image**: `searxng/latest`
- **Network**: `searxng_default`
- **Volumes**: `searxng-settings`, `searxng-valkey`
- **Docker Compose**: `/opt/stacks/searxng/` (pre-configured stack available on host `openclaw` at `10.0.3.130`)
- **Redis**: `valkey:9-alpine` as backend

## Port Configuration

- **Host port**: 80 → **Container port**: 8080
- **Important**: `settings.yml` inside the container declares `server.port: 8888`, but the app actually listens on port **8080** (verified via startup logs: `Listening at: http://:::8080`)
- Debugging method: `docker logs searxng-core | grep -i listen`

This was a non-obvious finding discovered through trial and error — the config file was misleading.

## Hermes-agent Integration

Hermes-agent's built-in `web_search_tool` uses **Parallel, Exa, Tavily, and Firecrawl** backends — **not** SearXNG. SearXNG is used directly via curl when:
- Privacy-respecting search is needed
- Specific engines are required (google, arxiv, wikipedia, stackoverflow, etc.)
- Direct JSON API access is preferred

## Search Fallback Order (Hermes-agent)

1. **SearXNG** → `curl "http://searxng/search?q=..."` (privacy-respecting, multi-engine)
2. **Direct HTTP** → curl against specific known URLs
3. **browser_navigate** → last resort for JS-rendered pages or anti-bot challenges

## URL Format Note

curl does **not** support scheme-relative URLs like `//searxng/search?...` — the `http://` prefix is required. Browsers auto-fill the scheme from the page context; curl does not.

**Correct**: `curl "http://searxng/search?q=..."`
**Wrong**: `curl "//searxng/search?q=..."` (scheme-relative, fails)

## Engine Examples

| Engine | Use for |
|--------|---------|
| `google` | General web search |
| `bing` | Microsoft search |
| `brave` | Privacy-focused search |
| `wikipedia` | Encyclopedia |
| `arxiv` | Academic papers |
| `stackoverflow` | Programming Q&A |
| `wikidata` | Knowledge graph |
| `startpage` | Private search |

## Reddit Limitation

SearXNG's Google index only surfaces Reddit's static archive pages, not live hot/new/top posts. Workaround: use `old.reddit.com` JSON API directly with a browser User-Agent.

## Health Check

```bash
curl -s -o /dev/null -w "%{http_code}" http://searxng/search?q=test
# Expected: 200
```

## Troubleshooting

| Problem | Solution |
|---------|---------|
| `Connection reset by peer` | Wrong port mapping — verify container listens on 8080, use `80:8080` |
| `Could not resolve host` | Add `127.0.0.1 searxng` to `/etc/hosts` |
| Empty results from Google | Some engines rate-limit; try `engines=google,bing,brave` or no engine param |
| Port 8080 gives static files | 8080 is the static file server, not the search API — use port 80 |

## Source

- Skill file: `~/.hermes/skills/web/searxng/SKILL.md`
