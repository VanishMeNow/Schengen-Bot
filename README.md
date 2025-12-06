# Vanish Now — Telegram Visa Appointment Assistant

This repository is a **production-minded skeleton** for *Vanish Now* — a Telegram bot that monitors and demos visa appointment slots for BLS / TLS / VFS centers worldwide.

## What is included
- TypeScript Node.js backend skeleton
- Telegram bot integration (grammy)
- Background worker skeleton (BullMQ + Redis)
- Fake appointment generator
- Sample Playwright scraper template
- PostgreSQL migration SQL
- Dockerfile + docker-compose for local testing
- README with run instructions

## Quick start (local, development)
1. Copy `.env.example` to `.env` and fill variables (Telegram bot token, Postgres, Redis).
2. Install dependencies:
```bash
npm install
```
3. Start services (recommended using Docker Compose):
```bash
docker-compose up -d
```
4. Run migrations:
```bash
npm run migrate
```
5. Start dev server:
```bash
npm run dev
```

## What to do next
- Add real scraping selectors for target centers under `src/scrapers/`
- Implement database migrations for your production DB
- Configure secure secrets and deployment (Kubernetes/GKE/EKS)

