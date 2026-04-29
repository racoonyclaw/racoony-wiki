---
title: Hindsight Memory Server
id: entity.hindsight-memory-server
pageType: entity
sourceIds:
  - session-2026-04-23
updatedAt: 2026-04-23
claims:
  - id: location
    text: "Running at /opt/stacks/hindsight_memory/"
    confidence: high
    evidence:
      - sourceId: session-2026-04-23
        detail: "Docker compose stack at /opt/stacks/hindsight_memory/"
  - id: api-port
    text: "API on port 8888, Control Plane on port 9999"
    confidence: high
    evidence:
      - sourceId: session-2026-04-23
  - id: database
    text: "Uses pgvector/pgvector:pg18 (PostgreSQL with pgvector extension)"
    confidence: high
    evidence:
      - sourceId: session-2026-04-23
        detail: "Fixed postgres:18 -> pgvector/pgvector:pg18 for vector similarity search"
  - id: llm-provider
    text: "Uses MiniMax-M2.7 via HINDSIGHT_API_LLM_PROVIDER=minimax"
    confidence: high
    evidence:
      - sourceId: session-2026-04-23
  - id: api-key
    text: "HINDSIGHT_API_KEY is set in .env but API key auth is not enforced in this version (v0.5.4)"
    confidence: medium
    evidence:
      - sourceId: session-2026-04-23
        detail: "API remains open on localhost. Key would need to be enforced at proxy level."
  - id: volumes
    text: "Data persisted at ./db (pgvector data) and ./hindsight-data (embedded pg0 fallback)"
    confidence: high
    evidence:
      - sourceId: session-2026-04-23
  - id: compose-fix
    text: "compose.yaml had two bugs: (1) wrong env_file syntax 'path: .env' should be '.env', (2) volume mount ./db:/var/lib/postgresql/data wrong — pgvector image stores at /var/lib/postgresql not /var/lib/postgresql/data"
    confidence: high
    evidence:
      - sourceId: session-2026-04-23
---

## Stack Location
`/opt/stacks/hindsight_memory/`

## Services
- **hindsight** — Main API + Control Plane (web UI), ports 8888/9999
- **hindsight-db** — PostgreSQL 18 with pgvector, health-checked

## Files
- `compose.yaml` — Docker compose config (pgvector:pg18 + hindsight:latest)
- `.env` — Environment variables (MiniMax key + HINDSIGHT_API_KEY)
- `db/` — PostgreSQL data volume
- `hindsight-data/` — Embedded pg0 data (fallback, not currently used)

## API
- **API**: http://localhost:8888 (open, no auth enforced)
- **Control Plane**: http://localhost:9999
- **OpenAPI docs**: http://localhost:8888/docs

## Auth Note
`HINDSIGHT_API_KEY` is loaded into the container environment but API key auth is not enforced in v0.5.4. API is open on localhost. To secure it for remote access, enforce auth at the proxy level (nginx, Cloudflare Tunnel, etc.).

## Stack Management
```bash
cd /opt/stacks/hindsight_memory
docker compose up -d      # start
docker compose down       # stop
docker compose restart     # restart
docker compose logs -f    # tail logs
```

## Test Commands
```bash
# Create a bank
curl -X PUT http://localhost:8888/v1/default/banks/test-bank \
  -H "Content-Type: application/json" \
  -d '{"description": "Test bank"}'

# Retain a memory
curl -X POST http://localhost:8888/v1/default/banks/test-bank/memories \
  -H "Content-Type: application/json" \
  -d '{"items": [{"content": "Quoc prefers concise answers"}]}'

# Recall
curl -X POST http://localhost:8888/v1/default/banks/test-bank/memories/recall \
  -H "Content-Type: application/json" \
  -d '{"query": "What does Quoc prefer?"}'
```
