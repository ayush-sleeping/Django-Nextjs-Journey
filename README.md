<div id="top"></div>

## 🚀 &nbsp; Django-Nextjs-Journey
> A complete learning path from **Zero to Expert** — from Python & TypeScript fundamentals to production-ready, scalable full-stack applications with **Django + Next.js**.

This is a structured, phase-by-phase learning journey designed to take a developer from foundational Python and TypeScript all the way to advanced full-stack engineering — covering the backend with **Django + Django REST Framework**, the frontend with **Next.js**, databases, authentication, real-time features, testing, DevOps, scaling, and system design.

**Created and maintained by [Ayush Mishra](https://github.com/ayush-sleeping)** — a personal, open curriculum documenting my journey through the modern Python + TypeScript full-stack ecosystem. Feel free to follow along, fork it, or use it as a reference for your own learning path.

## Overview

**What Django-Nextjs-Journey Is**

A self-paced curriculum for developers who want to master a **Python-backed, TypeScript-fronted** full-stack in a deliberate, end-to-end way.
- **Django backend** → MVT architecture, the ORM, Django REST Framework, authentication, background tasks, real-time.
- **Next.js frontend** → App Router, SSR/SSG/ISR, server components, Tailwind/ShadCN, React Query/Zustand.
- **Type-safe boundaries** → Python type hints on the backend, TypeScript on the frontend, shared API contracts.
- **Auth deep-dive** → password hashing, JWT (SimpleJWT), sessions, cookies, OAuth (Google/GitHub), 2FA.
- **Production thinking** → PostgreSQL, Redis, Celery, Docker, CI/CD, Kubernetes, observability.
- **Real projects** → from Todo CRUD to a booking system and an AI-powered doc generator.

**Why It's Useful**
- Removes guesswork — every phase has an ordered checklist of topics, so you always know what's next.
- Builds depth, not just breadth — auth, the ORM, and deployment are each treated as multi-week deep dives.
- Tracks progress — a **683-topic** tracker across **4 levels** shows exactly where you are.
- Bridges learning and production — ends with real, deployable projects rather than toy demos.

## 🧭 The Four Levels

The journey is organized into 4 cumulative levels, each ending in a concrete milestone you can point to. Every topic is **tagged for fast-tracking** (🔵 core · 🟡 skim · ⚪ skip) so an experienced dev can skip revision — the *Fast-track est.* column reflects that.

| Level | Phases | Topics | Full est. | Fast-track est. | Milestone |
|-------|--------|--------|-----------|-----------------|-----------|
| **1 — Foundations** | 1–13 | 342 | ~428h | ~261h | Build a full-stack CRUD app (Django + DRF ↔ Next.js) |
| **2 — Builder** | 14–21 | 212 | ~265h | ~188h | Build a **LaraBaseX-class** product (auth, RBAC, admin, audit, caching, jobs) |
| **3 — Professional** | 22–23 | 54 | ~68h | ~45h | Test, ship & operate in production → **job-ready** |
| **4 — Architect** | 24–26 | 75 | ~69h | ~48h | Distributed/plugin systems, AI, capstones → **expert** |

> Levels are **cumulative** — job-ready (Level 3) means you have Levels 1 + 2 + 3.
> **Fast-track to job-ready ≈ 495h** (~10 months at 12 h/week, or ~6 months at 20 h/week). Full path ≈ 829h. See the [roadmap's Fast-Track section](docs/roadmap.md#-fast-track-for-experienced-devs-your-path) for the recommended ordering.

**Included Major Phases**
- **Foundations** → Python, JavaScript, TypeScript, React, dev-environment setup.
- **Backend (Django)** → projects/apps, views, the ORM, admin, forms, Django REST Framework.
- **Frontend (Next.js)** → file-based routing, SSR/SSG/ISR, App Router, server components.
- **Auth** → password hashing, JWT, sessions, cookies, OAuth, 2FA, NextAuth/Clerk/Auth0.
- **Business systems** → multi-tenancy, RBAC, audit trails, billing, reporting, integrations.
- **Advanced** → caching with Redis, WebSockets (Channels), GraphQL, Celery, Stripe, email, testing.
- **DevOps** → Docker, migrations, CI/CD, Vercel, Railway/Render, AWS.
- **Scaling** → microservices, plugin/modular architecture, gRPC, Kubernetes, observability.
- **Capstone Projects** → e-commerce, CRM, ERP module, real-time chat, SaaS dashboard, AI doc generator.

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-092E20?style=for-the-badge" /></a></p>

<br>

##

### Table of contents:

| No. | Topics |
| --- | ------ |
| 0. | [Tech Stack](#tech-stack) |
| 1 | [Features and Integrations](#features-and-integrations) |
| 2 | [Getting Started](#getting-started) |
| 3 | [Documentation](#documentation) |
| 4 | [Folder Structure](#folder-structure) |

<br>

#

## Tech Stack
> A modern, production-ready full-stack.
- **Backend**: Django + Django REST Framework (Python)
- **Frontend**: Next.js (App Router, React Server Components) + Tailwind / ShadCN
- **Languages**: Python (backend), TypeScript (frontend)
- **Database**: PostgreSQL (Django ORM)
- **Authentication**: Django auth, DRF SimpleJWT, sessions, cookies, OAuth (Google/GitHub), 2FA, NextAuth
- **Caching & Real-time**: Redis, Django Channels (WebSockets)
- **Background Jobs**: Celery + Redis/RabbitMQ
- **API Layer**: REST (DRF), GraphQL (Strawberry/Graphene)
- **DevOps**: Docker, Gunicorn/Uvicorn, Nginx, GitHub Actions, Vercel, Railway/Render, Kubernetes
- **Testing**: pytest, pytest-django, Jest, React Testing Library, Playwright, Cypress

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-092E20?style=for-the-badge" /></a></p>

<br>

#

## Features and Integrations

| Category | Integrations & Features |
|----------|--------------------------|
| Languages | Python (type hints, dataclasses, async), TypeScript (strict mode, generics) |
| Backend Framework | Django (MVT, ORM, admin, signals, middleware, management commands) |
| API Framework | Django REST Framework (serializers, viewsets, routers, permissions, throttling) |
| Frontend Framework | Next.js (App Router, SSR, SSG, ISR, server components, server actions) |
| RDBMS | PostgreSQL (JSONField, ArrayField, full-text search, indexes) |
| ORM | Django ORM (QuerySets, managers, `select_related`/`prefetch_related`) |
| Authentication | password hashing, SimpleJWT, sessions, cookies, OAuth (Google/GitHub), 2FA (TOTP) |
| Authorization | permissions, groups, DRF permission classes, object-level permissions |
| State Management | Zustand, Redux Toolkit + RTK Query, Context API |
| Forms & Validation | React Hook Form, Zod, Django Forms, DRF serializers |
| UI Libraries | Tailwind CSS, ShadCN, Material UI |
| Data Fetching | fetch, axios, SWR, React Query (TanStack) |
| Caching | Redis (Django cache framework, sorted sets, rankings) |
| Real-time | Django Channels, WebSocket consumers, chat & notifications |
| Background Jobs | Celery, Celery Beat, Flower |
| API Styles | REST, GraphQL (Strawberry/Graphene, Apollo client) |
| Payments | Stripe (checkout, webhooks, frontend integration) |
| Email | Django email, SMTP/Gmail, templates, async delivery |
| Security | CORS, CSRF, rate limiting/throttling, settings hardening, input validation |
| API Documentation | OpenAPI / Swagger via drf-spectacular |
| Testing | pytest, pytest-django, factory_boy, Jest, RTL, Playwright, Cypress |
| DevOps | Docker, docker-compose, Gunicorn, Nginx, multi-environment configs |
| Deployment | Vercel, Railway, Render, Fly.io, AWS, DigitalOcean |
| CI/CD | GitHub Actions |
| Scaling | message queues, gRPC, load balancing, Kubernetes, Helm |
| Architecture | DDD, Hexagonal, Clean Architecture, Modular Monolith, CQRS |
| AI Integration | LLM (OpenAI/Anthropic), summarizer, chat (RAG), search (pgvector) |

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-092E20?style=for-the-badge" /></a></p>

<br>

#

## Getting Started

1. **Clone the repo:**
   ```sh
   git clone https://github.com/ayush-sleeping/Django-Nextjs-Journey.git
   cd Django-Nextjs-Journey
   ```

2. **Open the roadmap** — the master list of all 26 phases and 683 topics:
   ```sh
   open docs/roadmap.md
   ```

3. **Open the progress tracker** — mark each topic `⬜` → `🔄` → `✅`:
   ```sh
   open docs/progress-tracker.md
   ```

4. **Pick your starting point** (everyone begins in **Level 1 — Foundations**):
   - New to Python → start at [Phase 1: Foundation](docs/roadmap.md#phase-1-foundation--python-basics).
   - Know Python & TS → jump to [Phase 6: Django Basics](docs/roadmap.md#phase-6-django-basics).
   - Know Django → jump to [Phase 11: Next.js Basics](docs/roadmap.md#phase-11-nextjs-basics).

5. **Organize code by phase (recommended):**
   ```sh
   mkdir -p phase-06-django-basics
   mkdir -p phase-11-nextjs-basics
   # ...and so on per phase
   ```

6. **Install the basics (when you reach Phase 5–6):**
   ```sh
   # Python (via pyenv) + virtual env
   pyenv install 3.12 && python -m venv .venv && source .venv/bin/activate
   pip install django djangorestframework

   # Node (via nvm) for the Next.js side (Phase 11)
   nvm install --lts
   npx create-next-app@latest
   ```

7. **Update the tracker as you go** — flip `⬜` → `🔄` → `✅` in [`docs/progress-tracker.md`](docs/progress-tracker.md) and update the summary counts.

8. **Build the final projects (Phase 25)** — start small (Todo CRUD, Static Blog) and work up to the booking system and AI doc generator.

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-092E20?style=for-the-badge" /></a></p>

<br>

#

## Documentation
> The full learning curriculum and progress tracking.

| No. | Topics | Includes |
| --- | ------ | -------- |
| 1 | [Full Roadmap](docs/roadmap.md) | 4 levels · 26 phases · 683 topics: Python → TS → Django → Next.js → Auth → Business systems → Testing → DevOps → Scaling → System Design |
| 2 | [Progress Tracker](docs/progress-tracker.md) | 683-row checklist to track ⬜ / 🔄 / ✅ per topic, grouped by phase |
| 3 | [Phase 1: Foundation — Python Basics](docs/roadmap.md#phase-1-foundation--python-basics) | Python syntax, data structures, functions, exceptions, file I/O |
| 4 | [Phase 2: Python Deep Dive](docs/roadmap.md#phase-2-python-deep-dive) | OOP, decorators, generators, context managers, type hints, async |
| 5 | [Phase 3: JavaScript & TypeScript Foundation](docs/roadmap.md#phase-3-javascript--typescript-foundation) | ES6+, promises, TS types, interfaces, generics, utility types |
| 6 | [Phase 4: React Fundamentals](docs/roadmap.md#phase-4-react-fundamentals) | JSX, components, props, state, hooks, composition |
| 7 | [Phase 5: Development Environment Setup](docs/roadmap.md#phase-5-development-environment-setup) | VS Code, pyenv/nvm, Docker, Postgres, linters, pre-commit |
| 8 | [Phase 6: Django Basics](docs/roadmap.md#phase-6-django-basics) | Projects/apps, URLconf, views, templates, class-based views |
| 9 | [Phase 7: Django Models & ORM](docs/roadmap.md#phase-7-django-models--orm) | Models, migrations, QuerySets, relations, managers |
| 10 | [Phase 8: Django Admin, Forms & Auth Basics](docs/roadmap.md#phase-8-django-admin-forms--auth-basics) | Admin, ModelForms, custom user model, permissions, sessions |
| 11 | [Phase 9: Django REST Framework](docs/roadmap.md#phase-9-django-rest-framework-drf) | Serializers, viewsets, routers, pagination, permissions, OpenAPI |
| 12 | [Phase 10: Database Integration](docs/roadmap.md#phase-10-database-integration-postgresql) | PostgreSQL, indexes, transactions, query optimization, JSON/Array fields |
| 13 | [Phase 11: Next.js Basics](docs/roadmap.md#phase-11-nextjs-basics) | File-based routing, layouts, SSG/SSR/ISR, metadata |
| 14 | [Phase 12: Next.js Core Concepts](docs/roadmap.md#phase-12-nextjs-core-concepts) | Server/client components, forms (RHF + Zod), Tailwind/ShadCN, route handlers |
| 15 | [Phase 13: Connecting Frontend & Backend](docs/roadmap.md#phase-13-connecting-frontend--backend) | CORS, axios/fetch, SWR, React Query, shared types |
| 16 | [Phase 14: Authentication & Authorization](docs/roadmap.md#phase-14-authentication--authorization) | Hashing, JWT, sessions, cookies, permissions, protected routes |
| 17 | [Phase 15: Advanced Authentication](docs/roadmap.md#phase-15-advanced-authentication) | OAuth, django-allauth, 2FA, NextAuth, Clerk, Auth0 |
| 18 | [Phase 16: State Management & Frontend Best Practices](docs/roadmap.md#phase-16-state-management--frontend-best-practices) | Zustand, Redux Toolkit, pagination/search/sort/filter UX |
| 19 | [Phase 17: Advanced Django](docs/roadmap.md#phase-17-advanced-django) | Signals, middleware, caching, custom commands, hardening |
| 20 | [Phase 18: Advanced Next.js](docs/roadmap.md#phase-18-advanced-nextjs) | App Router, server actions, streaming, edge, revalidation, SEO |
| 21 | [Phase 19: Caching, Performance & Real-time](docs/roadmap.md#phase-19-caching-performance--real-time) | Redis, Django Channels (WebSockets), GraphQL |
| 22 | [Phase 20: Async Tasks, Payments & Integrations](docs/roadmap.md#phase-20-async-tasks-payments--integrations) | Celery, email, Stripe, S3 storage |
| 23 | [Phase 21: Building Business Systems](docs/roadmap.md#phase-21-building-business-systems-saas--erp--crm-patterns) | Multi-tenancy, RBAC, audit trails, billing, reporting/PDF, webhooks, ETL |
| 24 | [Phase 22: Testing](docs/roadmap.md#phase-22-testing) | pytest, DRF tests, factory_boy, Jest, Playwright, Cypress |
| 25 | [Phase 23: DevOps & Deployment](docs/roadmap.md#phase-23-devops--deployment) | Docker, Gunicorn/Nginx, CI/CD, Terraform, load testing, Vercel, Railway, AWS |
| 26 | [Phase 24: Scaling & Architecture](docs/roadmap.md#phase-24-scaling--architecture) | Microservices, message queues, gRPC, Kubernetes, plugin/modular architecture, observability |
| 27 | [Phase 25: System Design & Expert Level](docs/roadmap.md#phase-25-system-design--expert-level) | DDD, Clean/Hexagonal architecture, CQRS, event sourcing, AI integration |
| 28 | [Phase 26: Final Projects](docs/roadmap.md#phase-26-final-projects) | Todo CRUD → E-Commerce → CRM → ERP module → Modular-monolith plugin app → AI Doc Generator |

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-092E20?style=for-the-badge" /></a></p>

<br>

#

## Folder Structure
```
Django-Nextjs-Journey/
├── docs/
│   ├── roadmap.md              # Full 26-phase, 683-topic curriculum
│   └── progress-tracker.md     # Trackable checklist (⬜ / 🔄 / ✅)
│
├── phase-01-python-basics/         # Python fundamentals
│   └── (your practice code)
├── phase-02-python-deep-dive/      # OOP, decorators, async
├── phase-03-js-ts-foundation/      # JavaScript + TypeScript
├── phase-04-react-fundamentals/    # React core
├── phase-05-dev-setup/             # Environment configs
├── phase-06-django-basics/         # First Django app
├── phase-07-django-orm/            # Models & the ORM
├── phase-08-django-admin-forms/    # Admin, forms, auth basics
├── phase-09-drf/                   # Django REST Framework
├── phase-10-database/              # PostgreSQL integration
├── phase-11-nextjs-basics/         # First Next.js app
├── phase-12-nextjs-core/           # Components, forms, UI
├── phase-13-fullstack-connect/     # Connecting Django + Next.js
├── phase-14-auth/                  # JWT, sessions, permissions
├── phase-15-advanced-auth/         # OAuth, 2FA, NextAuth
├── phase-16-state-mgmt/            # Zustand, Redux Toolkit
├── phase-17-advanced-django/       # Signals, caching, hardening
├── phase-18-advanced-nextjs/       # App Router, server actions
├── phase-19-cache-realtime/        # Redis, Channels, GraphQL
├── phase-20-async-payments/        # Celery, Stripe, email
├── phase-21-business-systems/      # Multi-tenancy, billing, audit, reporting
├── phase-22-testing/               # pytest, Playwright, Cypress
├── phase-23-devops/                # Docker, CI/CD, Terraform, deployment
├── phase-24-scaling/               # Microservices, plugins, Kubernetes
├── phase-25-system-design/         # DDD, architecture, AI
├── phase-26-projects/              # Capstone projects
│   ├── todo-crud/
│   ├── auth-app/
│   ├── ecommerce/
│   ├── chat-app/
│   ├── trello-clone/
│   ├── saas-dashboard/
│   ├── crm/
│   ├── erp-module/
│   └── booking-system/
│
├── NestJS-NextJS-Journey/     # Archived: the previous NestJS curriculum
├── .gitignore
└── README.md
```

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-092E20?style=for-the-badge" /></a></p>

<br>

#

## Author

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/ayush-sleeping">
        <img src="https://github.com/ayush-sleeping.png" width="100px;" alt="Ayush Mishra"/>
        <br />
        <sub><b>Ayush Mishra</b></sub>
      </a>
      <br />
      <sub>Creator &amp; Maintainer</sub>
    </td>
  </tr>
</table>

Built and maintained by **[Ayush Mishra](https://github.com/ayush-sleeping)** as a personal full-stack learning journey.
If this roadmap helps you, consider giving the repo a ⭐ on GitHub — it keeps the motivation going.

<br>

**Happy Coding! 🚀**
