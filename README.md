<h1 align="center">Jamshidbek Ikromov</h1>
<p align="center"><b>Senior Go Backend Engineer · Team Lead</b></p>
<p align="center">
  Tashkent, Uzbekistan (UTC+5) ·
  <a href="https://solves.hatsker.info">solves.hatsker.info</a> ·
  <a href="https://www.linkedin.com/in/jamshidbek-ikromov">LinkedIn</a> ·
  <a href="https://t.me/Hatsker01">Telegram</a>
</p>

---

I design and ship production backends in **Go** — the parts that have to be right: orders that never oversell, payments that never double-charge, auth and RBAC, real-time geolocation, and the data model underneath all of it.

4+ years in commercial backend development. Currently **CTO / Backend Lead** of a 5-person cross-functional team building a used-car marketplace and a B2B SaaS for auto-service businesses. Previously led backend for a bike-sharing & powerbank-rental platform.

## What I do

- **Backend from scratch** — domain model → PostgreSQL schema → REST/gRPC API → deployment, with migrations, tests and docs your frontend team can use on day one.
- **Correctness under load** — idempotent payment webhooks, transactional stock reservation, outbox pattern for side effects, explicit state machines with audit logs.
- **Team leadership** — code review, architecture decisions, splitting a monolith into services only when it actually pays off.

## Selected work

| Project | Role | What I built |
|---|---|---|
| **AutoMarket UZ** — used-car marketplace | CTO / Backend Lead · 2025–now | Go microservices over gRPC, PostgreSQL, listings & search, payments and push-notification integrations, role-based access |
| **B2B SaaS for auto-service businesses** | Backend Lead · 2025–now | Sales & cash-desk flows, stock with low-stock analytics, P&L / balance reports, payment-gateway integration |
| **Qwatt Bike** — bike-sharing + powerbank rental | Backend Team Lead · 2022–2025 | Order lifecycle (rent → ride → return), real-time geolocation, per-station availability, courier tasks; Go, PostgreSQL, Redis, NATS |
| **CAR24** — automotive platform | Backend Engineer | Core API and integrations |

## Stack

**Core:** Go (Chi, gRPC, pgx + sqlc), PostgreSQL / PostGIS, Redis
**Messaging:** NATS, Kafka
**Infra:** Docker, Linux, Nginx, S3-compatible storage, GitHub Actions
**Also ship:** Next.js + TypeScript front-ends with my team for full A–Z products

## How I work

- Start with the ERD and the API contract — most bugs are schema bugs.
- Business logic lives in the API, never in the client.
- Every side effect goes through an outbox; every external call is retried and idempotent.
- Small PRs, clear commit messages, docs next to the code.

## Contact

Open to backend contracts and full-stack product builds through **[ikromov.solves](https://solves.hatsker.info)**.
Email: tjamshidbek1805@gmail.com · Telegram: [@Hatsker01](https://t.me/Hatsker01)

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Hatsker01&show_icons=true&include_all_commits=true&count_private=true&theme=dark&hide_border=true" height="150" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hatsker01&layout=compact&theme=dark&hide_border=true" height="150" alt="Top languages" />
</p>
