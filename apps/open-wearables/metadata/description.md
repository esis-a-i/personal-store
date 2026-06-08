# Open Wearables

Open source platform for wearable devices. Provides infrastructure for collecting, processing, and querying data from various wearable devices via svix webhooks.

## Services
- `backend` — Python API (port 8000)
- `frontend` — web UI (port 3000)
- `postgres` — PostgreSQL 18
- `redis` — Redis 8
- `svix-server` — webhook delivery
- `celery-worker`, `celery-beat`, `flower` — async task processing
