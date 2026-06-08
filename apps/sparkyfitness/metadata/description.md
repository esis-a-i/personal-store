# SparkyFitness

Self-hosted fitness, nutrition, and health tracking platform. AI-powered food recognition, exercise tracking, biometric monitoring, and MCP server for agent integration.

## Source
- Frontend image: `codewithcj/sparkyfitness:latest`
- Server image: `codewithcj/sparkyfitness_server:latest`
- MCP image: `codewithcj/sparkyfitness_mcp:latest`
- Repo: https://github.com/codewithcj/sparkyfitness

## Services
- `db` — PostgreSQL 18
- `server` — API server (internal port 3010)
- `frontend` — Next.js web app (main, port 80)
- `mcp` — MCP server for agent integration (internal port 3001)

## Storage
- `${APP_DATA_DIR}/postgresql/` — DB data
- `${APP_DATA_DIR}/backup/` — server backups
- `${APP_DATA_DIR}/uploads/` — user uploads (profile pictures, exercise images)

## MCP integration
SparkyFitness exposes an MCP server for AI agents to read food diary, weight, biometrics, etc. Used by `agents/mcp/sparkyfitness.md` in Obsidian.
