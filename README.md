# OFC — Fiber Optic Asset Manager

Enterprise Fiber Optic Network & GIS Asset Management System.

This repository is being prepared for the migrated/new-server deployment of the OFC application.

## Deployment

Use the prepared project package, configure `.env`, then run:

```bash
docker compose up -d --build
```

Do not commit production credentials, Firebase private keys, Telegram bot tokens, or other secrets.
