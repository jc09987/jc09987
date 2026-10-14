# 👋 Hi, I'm Juan Carlos

**Senior Full-Stack Engineer · AI Systems Design & Automation** · Mexico City 🇲🇽

I've spent 10+ years building production web products for brands like **NBCUniversal, National Geographic, Fandango, and Imagine Learning**. These days I design and ship AI-ready platforms end to end, from the database and payments to the automations and the UI.

---

### 🧠 How I build

I treat AI as a **bounded tool around a solid domain API**, not as the system of record.

- **Postgres and Stripe own the truth.** Models, workflows, and chat channels can only emit a *typed command* from a closed schema.
- **Every inbound event is verified** (HMAC signatures, shared secrets) before anything is written.
- **Side effects are idempotent.** A redelivered webhook never creates a second order.
- **Notifications are decoupled.** Email and WhatsApp go out through an event bus and can fail without rolling back the write.
- **AI runs are traceable.** Prompts, model ids, status, and errors are stored with the row.

The result: systems where an AI agent can act on real business data without being able to break it.

---

### 🚀 What I've been building

Personal projects built as small-business platforms for the Mexican market. One shared architecture runs **8 products** (5 core platforms and 3 variants).

| Project | What it does |
| --- | --- |
| **Garuda** | Multi-tenant commerce: isolated storefronts per merchant, Stripe Connect direct charges, Row Level Security as the tenant boundary |
| **Pantalla** | Real-time in-store TV menu managed from an admin dashboard, with optional WhatsApp notifications |
| **Bellus Lab** | Bookings, staff, and Stripe checkout for a beauty studio, plus 15 n8n workflows for reminders, no-shows, refunds, and reviews |
| **Creator audience platform** | TikTok ingest with Apify, deterministic lead scoring, WhatsApp and email through BullMQ, and a donor CRM with a lifecycle state machine |
| **Generative fulfillment** | Paid AI image generation with OpenAI (`gpt-image-1`): persisted prompts, re-hosted assets, `generating → ready / failed` |

---

### 💼 Experience

- **Independent AI Product Engineer**, Personal Projects · 2026 – present
- **Web UI Developer**, Globant · 2018 – 2026
  - **NBCUniversal Theme Parks:** Web3 quest-and-rewards platform (NestJS, Docker)
  - **Fandango At Home:** app rebrand across 10+ smart TV and console targets (React, spatial navigation)
  - **Imagine Learning:** corporate site, university platform performance work, shared component library (React, Redux, Drupal)
  - **National Geographic Your Shot:** one of 2 principal engineers on Discussions (Symfony, Vanilla Forums)
- **Principal Full-Stack Developer & UI Designer**, Cuatro Creative Labs · 2017 – 2018

---

### 🛠️ Tech stack

**Front-end**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Vue](https://img.shields.io/badge/Vue-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8)
![Webpack](https://img.shields.io/badge/Webpack-1C78C0?style=flat-square&logo=webpack&logoColor=white)

**Back-end**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)
![Drupal](https://img.shields.io/badge/Drupal-0678BE?style=flat-square&logo=drupal&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)

**Data & payments**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-1C1C1C?style=flat-square&logo=supabase&logoColor=3ECF8E)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe_Connect-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Automation & AI**
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_Cloud_API-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)

**DevOps & testing**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=flat-square&logo=circleci&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

**Patterns I reach for:** event-driven architecture · command pattern · state machines · idempotent webhooks · HMAC-signed requests · multi-tenant SaaS with Row Level Security · service boundaries

---

### 🌱 Currently

- Exploring how AI agents can safely operate real business systems through typed tools and closed schemas
- Using AI-assisted workflows (Claude, Cursor) to design and ship full products as a one-person team

### 💞️ Open to

Teams focused on **results, trust, and companionship**, especially roles in AI systems, full-stack product engineering, and automation.

### 📫 Reach me

- ✉️ [jc09987@gmail.com](mailto:jc09987@gmail.com)
- 💼 [linkedin.com/in/jc-garcia-ramirez](https://linkedin.com/in/jc-garcia-ramirez)

Thanks for stopping by! 🙌
