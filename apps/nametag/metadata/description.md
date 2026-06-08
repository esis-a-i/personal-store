# Nametag

Personal CRM for managing contacts, groups, and relationships. Built with Next.js + PostgreSQL + Redis.

## Source
- Image: `ghcr.io/mattogodoy/nametag:latest`
- Repo: https://github.com/mattogodoy/nametag
- Web UI: https://nametag-alexesn.duckdns.org (after install)

## Services
- `db` — PostgreSQL 16
- `redis` — Redis 7
- `app` — Next.js application (port 3000)
- `backup` — daily PostgreSQL backup to `${APP_DATA_DIR}/backups/`
- `cron` — reminder + cleanup jobs

## Storage
- `${APP_DATA_DIR}/postgres/` — DB data
- `${APP_DATA_DIR}/redis/` — Redis data
- `${APP_DATA_DIR}/photos/` — uploaded photos
- `${APP_DATA_DIR}/backups/` — daily PostgreSQL dumps
