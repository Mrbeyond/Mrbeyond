# Abiola Beyond Salam

### Go Backend Engineer — Fintech, Payments & Real-Time Platforms

**Six years building production backends.** Solution-first, and allergic to systems that do not
scale.

I start from the problem and the user's story, then build the shortest safe path to it — and I own
the whole thing: the schema, the service, the security boundary, the cloud it runs on, the screens
people actually touch, and the tests and docs that let someone else keep it alive. Money systems
are where I sharpened this, because they punish a mistake fastest.

Right now: lead engineer on **Makemouth**, a peer-to-peer prediction platform with zero house
edge — custodial wallets, live markets whose odds move on every stake, automated payouts.
On the side: making cross-chain stablecoin movement seamless with **Circle CCTP** — shipping as
an open-source Go library first, so any system can move USDC between chains without rebuilding
the plumbing.

## How I engineer

- Architect and plan first — then the safest, shortest path, not the cleverest
- "What could go wrong?" before "does it work?"
- Can it survive at scale? Assume millions, never demo data
- Idempotent by default — a retry must be safe to repeat
- Cache the hot path, index the query, measure the latency
- Invariants in the database, not in comments
- Every error is a design input, including the provider's
- Security boundary per resource, never bolted on afterwards
- Product and user story before feature — UX is not decoration
- Tested against real paths. Documented. Or unfinished
- AI for speed; review and real tests as the gate

## What I bring

- **Concurrency without contention** — parallel batch pipelines where workers claim work cooperatively, so adding capacity adds throughput instead of lock waits
- **Exactness under load** — transactions that abort rather than commit an imbalance, with the guarantee enforced in the database, not in review
- **Low-latency reads** — hot paths served from cache and atomic counters; one user's write never makes another user wait
- **Real-time delivery** — live event streams to clients through bounded workers that shed load under burst instead of stalling
- **Scale proven, not assumed** — keyset-paged fan-out stress-tested past a million records; batch settlement benchmarked at ten thousand participants per run
- **Risk and abuse controls** — per-resource authorization, verified provider webhooks, tiered rate limits, step-up MFA, and identity-linkage detection that shut down coordinated multi-account abuse
- **Cost and delivery** — ~50% lower deployment overhead, 10–30% infrastructure and development cost reduction, zero-downtime automated releases
- **Leads or follows, whichever the work needs** — comfortable owning direction, and equally comfortable executing someone else's
- **Communication over assumption** — ask early, flag a risk while it is still cheap, and keep whoever depends on the work informed instead of surprised

## Where I have worked

- **Makemouth** — Lead Engineer · May 2026 – Present · prediction platform: custodial multi-currency wallets, live parimutuel markets over SSE, raffles, automated settlement, AWS infra, Next.js app and admin console
- **Transfaar (szndpay)** — Primary Go Backend Engineer · Jan 2025 – Mar 2026 · remittance and gateway integrity, admin analytics and case resolution
- **Breezelearn (Intelligent)** — Go Engineer · Feb 2024 – Sep 2024 · bank-integrated airtime and data APIs, worker-pool throughput
- **Medillery** — Full Stack Engineer, later Team Lead · Nov 2019 – Oct 2021, Oct 2022 – Mar 2024 · social digital design platform connecting graphic designers with the people who need them
- *Earlier:* Wazobia Technologies (2022) · Hiosoft Software Solutions (2021–2022) · Paycoins / BOMZAK frontend contract (2021)

## Programming

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

Reading and comfortable in, without shipped work to point at:
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

## Frameworks

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=000000)
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

## Tools & Technology

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-2E7D9A?style=for-the-badge&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=for-the-badge&logo=openapiinitiative&logoColor=white)

![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white)

![SQLC](https://img.shields.io/badge/SQLC-1C6EA4?style=for-the-badge&logo=go&logoColor=white)
![Goose](https://img.shields.io/badge/Goose-5C6BC0?style=for-the-badge&logo=go&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=000000)

*Certified in Golang, React, and JavaScript (TestDome) · Frontend Developer (SkillValue) ·
National Innovation Diploma, Software Architecture — SQI College of ICT*

## Open to

Go-centric teams building systems that have to scale — payments and stablecoin rails, real-time
platforms, or anywhere throughput and correctness are both non-negotiable.

[abiolabeyond@gmail.com](mailto:abiolabeyond@gmail.com) · [LinkedIn](https://linkedin.com/in/abiola-beyond)
