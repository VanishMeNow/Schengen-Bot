# Booking Appointment Bot — Support Bypass Selfi

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

🚀 Technologies & Tools Used
<p align="left"> <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Selenium-Automation-43B02A?logo=selenium&logoColor=white" /> <img src="https://img.shields.io/badge/ChromeDriver-Testing-4285F4?logo=google-chrome&logoColor=white" /> <img src="https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-4B8BBE?logo=beautifulsoup&logoColor=white" /> <img src="https://img.shields.io/badge/Requests-HTTP%20Client-444444?logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite&logoColor=white" /> </p>
🛒 Buy the Bot (WhatsApp)
<a href="https://wa.me/201029107547" target="_blank"> <img src="https://img.shields.io/badge/💰 Buy_Shengen_Visa_Bot-WhatsApp-green?style=for-the-badge&logo=whatsapp" /> </a>
⭐ Examples of more stylish icons if you want extra shine:
🧰 Programming Languages
<p> <img src="https://img.shields.io/badge/Python-FFD43B?logo=python&logoColor=blue" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000" /> </p>
🧪 Automation & Scraping
<p> <img src="https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white" /> <img src="https://img.shields.io/badge/Playwright-1C1E24?logo=microsoft-edge&logoColor=white" /> <img src="https://img.shields.io/badge/BS4-BeautifulSoup-4B8BBE" /> </p>
🗃️ Database & Storage
<p> <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" /> <img src="https://img.shields.io/badge/JSON-555555?logo=json&logoColor=white" /> </p>
