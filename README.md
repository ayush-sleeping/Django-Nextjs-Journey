<div id="top"></div>

## 🚀  &nbsp; Nestjs-Nextjs-Journey
> A complete learning path from **Zero to 100** — covering everything from JavaScript basics to production-ready, scalable microservices architecture with **NestJS + Next.js**.

This is a structured, phase-by-phase learning journey designed to take a developer from foundational JavaScript and TypeScript all the way to advanced full-stack engineering — covering backend with NestJS, frontend with Next.js, databases, authentication, DevOps, microservices, and system design.

**Created and maintained by [Ayush Mishra](https://github.com/ayush-sleeping)** — a personal, open curriculum documenting my journey through the modern TypeScript full-stack ecosystem. Feel free to follow along, fork it, or use it as a reference for your own learning path.

## Overview

What Nestjs-Nextjs-Journey Is

A self-paced curriculum for developers who want to master the modern TypeScript-based full-stack ecosystem in a deliberate, end-to-end way.
- NestJS backend → modular architecture, REST APIs, TypeORM/Prisma, authentication, microservices.
- Next.js frontend → App Router, SSR/SSG/ISR, Tailwind/ShadCN, React Query/Zustand.
- TypeScript-first → strong typing across the stack with shared interfaces and DTOs.
- Auth deep-dive → bcrypt, JWT, sessions, OAuth (Google/GitHub), 2FA.
- Production thinking → Docker, CI/CD, Kubernetes, GraphQL, Redis, WebSockets.
- Real projects → from Todo CRUD to a microservices-based reservation booking system.


Why It's Useful
- Removes guesswork — every phase has an ordered checklist of topics, so you always know what's next.
- Builds depth, not just breadth — auth, databases, and microservices are each treated as multi-week deep dives, not one-line bullets.
- Tracks progress — a 549-topic tracker lets you see exactly where you are in the journey.
- Bridges learning and production — ends with real, deployable projects rather than toy demos.


Included Major Phases
- **Foundations** → JavaScript, TypeScript, dev environment setup.
- **Backend (NestJS)** → controllers, services, modules, DI, validation, TypeORM, Prisma, MongoDB.
- **Frontend (Next.js)** → file-based routing, SSR/SSG/ISR, App Router, server components.
- **Auth** → password hashing, JWT, sessions, OAuth, 2FA, NextAuth/Clerk/Auth0.
- **Advanced** → caching with Redis, WebSockets, GraphQL, Stripe, email, testing.
- **DevOps** → Docker, migrations, CI/CD, Heroku, Vercel.
- **Microservices** → TCP/gRPC/RabbitMQ, GKE/EKS, API Gateway, Apollo Federation.
- **Capstone Projects** → e-commerce, real-time chat, Trello clone, SaaS dashboard, AI-powered doc generator.

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-blueviolet?style=for-the-badge" /></a></p>

<br>

<br>

##

### Table of content:

| No.     | Topics                                                                                  |
| ------- | --------------------------------------------------------------------------------------- |
| 0.      | [Tech Stack](#tech-stack)                                                               |
| 1       | [Features and Integrations](#features-and-integrations)                                 |
| 2       | [Getting Started](#getting-started)                                                     |
| 3       | [Documentations](#documentations)                                                       |
| 4       | [Folder Structure](#folder-structure)                                                   |

<br>

<br>

#

## Tech Stack
> A modern tech stack for building scalable, production-ready full-stack applications.
- **Backend**: NestJS (Node.js + TypeScript, REST + GraphQL)
- **Frontend**: Next.js (App Router, React Server Components) + Tailwind / ShadCN
- **Language**: TypeScript (end-to-end)
- **Database**: PostgreSQL (TypeORM / Prisma), MongoDB
- **Authentication**: JWT, Passport, Sessions, OAuth (Google, GitHub), 2FA, NextAuth
- **Caching & Real-time**: Redis, WebSockets
- **API Layer**: REST, GraphQL (Apollo), Apollo Federation
- **Messaging**: TCP, gRPC, RabbitMQ
- **DevOps**: Docker, Kubernetes (GKE / EKS), Helm, GitHub Actions, Vercel, Heroku
- **Testing**: Jest, React Testing Library, Playwright, Cypress

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-blueviolet?style=for-the-badge" /></a></p>

<br>

<br>

#

## Features and Integrations

| Category              | Integrations & Features                                                                 |
|-----------------------|----------------------------------------------------------------------------------------|
| Language              | TypeScript (strict mode, generics, decorators)                                          |
| Backend Framework     | NestJS (modules, controllers, services, DI, pipes, guards, interceptors)                |
| Frontend Framework    | Next.js (App Router, SSR, SSG, ISR, server components)                                  |
| RDBMS                 | PostgreSQL (via TypeORM and Prisma)                                                     |
| NoSQL                 | MongoDB (Atlas, Mongoose)                                                               |
| ORM                   | TypeORM, Prisma                                                                         |
| Authentication        | bcrypt, JWT, Passport, Sessions, Cookies, OAuth (Google, GitHub), 2FA                   |
| Authorization         | Role-based access, scopes, guards, custom decorators                                    |
| State Management      | Zustand, Redux Toolkit, Context API                                                     |
| Forms & Validation    | React Hook Form, Zod, class-validator, class-transformer                                |
| UI Libraries          | Tailwind CSS, ShadCN, Material UI                                                       |
| Data Fetching         | fetch, axios, SWR, React Query                                                          |
| Caching               | Redis (with sorted sets, rankings, pagination)                                          |
| Real-time             | WebSocket Gateways, Chat implementation                                                 |
| API Styles            | REST, GraphQL (Apollo, Federation)                                                      |
| Payments              | Stripe integration (backend + frontend)                                                 |
| Email                 | Nodemailer, Gmail, SMTP, email templates                                                |
| Security              | CORS, CSRF, Rate limiting (Throttler), HTTPS, input validation                          |
| Logging & Monitoring  | Custom loggers, event emitters, CQRS                                                    |
| API Documentation     | Swagger / OpenAPI auto-generation                                                       |
| Testing               | Jest (unit), Supertest (E2E), React Testing Library, Playwright, Cypress                |
| DevOps                | Docker, multi-environment configs, TypeORM migrations                                   |
| Deployment            | Heroku, Vercel, Netlify, GKE, EKS                                                       |
| CI/CD                 | GitHub Actions, CloudBuild, CodePipeline                                                |
| Microservices         | TCP transport, gRPC, RabbitMQ, monorepo, shared libraries                               |
| API Gateway           | GraphQL Gateway, Apollo Federation                                                      |
| Architecture Patterns | DDD, Hexagonal, Clean Architecture, Modular Monolith                                    |
| AI Integration        | LLM (OpenAI), AI Summarizer, AI Chat, AI Search, AI Doc Generator                       |

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-blueviolet?style=for-the-badge" /></a></p>

<br>

<br>

#

## Getting Started

1. **Clone the repo:**
   ```sh
   git clone https://github.com/ayush-sleeping/Nestjs-Nextjs-Journey.git
   cd Nestjs-Nextjs-Journey
   ```

2. **Open the roadmap:**
   ```sh
   open docs/roadmap.md
   ```
   - This is the master list of all 21 phases and 549 topics.

3. **Open the progress tracker:**
   ```sh
   open docs/progress-tracker.md
   ```
   - Mark each topic as you progress: `⬜` not started, `🔄` in progress, `✅` completed.

4. **Pick your starting phase:**
   - Beginner → start at [Phase 1: Foundation](docs/roadmap.md#phase-1-foundation-beginner).
   - Already know JS/TS → jump to [Phase 4: NestJS Basics](docs/roadmap.md#phase-4-nestjs-basics-backend-start).
   - Already know NestJS → jump to [Phase 7: Next.js Basics](docs/roadmap.md#phase-7-nextjs-basics-frontend-start).

5. **Organize code by phase (recommended):**
   ```sh
   mkdir -p phase-01-foundation
   mkdir -p phase-04-nestjs-basics
   # ...and so on per phase
   ```

6. **Install the basics (when you reach Phase 3):**
   ```sh
   # Node.js (via nvm)
   nvm install --lts

   # NestJS CLI
   npm i -g @nestjs/cli

   # Next.js (when you reach Phase 7)
   npx create-next-app@latest
   ```

7. **Update the tracker as you go:**
   - Edit [`docs/progress-tracker.md`](docs/progress-tracker.md) and flip `⬜` → `🔄` → `✅`.
   - Update the Progress Summary counts at the top.

8. **Build the final projects (Phase 21):**
   - Start small (Todo CRUD, Static Blog) and work up to the microservices reservation system.

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-blueviolet?style=for-the-badge" /></a></p>

<br>

<br>

#

## Documentations
> The full learning curriculum and progress tracking.

| No. | Topics | Includes |
| --- | ------ | -------- |
| 1 | [Full Roadmap](docs/roadmap.md) | All 21 phases, table of contents, and 549 topics covering JS → TypeScript → NestJS → Next.js → Auth → DevOps → Microservices → System Design |
| 2 | [Progress Tracker](docs/progress-tracker.md) | 549-row checklist to track ⬜ / 🔄 / ✅ status per topic, grouped by phase |
| 3 | [Phase 1: Foundation](docs/roadmap.md#phase-1-foundation-beginner) | JavaScript essentials, React fundamentals, Node.js basics, CLI |
| 4 | [Phase 2: TypeScript Mastery](docs/roadmap.md#phase-2-typescript-mastery) | Types, inference, interfaces, classes, generics, advanced patterns |
| 5 | [Phase 3: Development Environment Setup](docs/roadmap.md#phase-3-development-environment-setup) | VS Code, Node, Docker, Git, Postman, Parcel |
| 6 | [Phase 4: NestJS Basics](docs/roadmap.md#phase-4-nestjs-basics-backend-start) | Controllers, routing, Nest CLI, project structure |
| 7 | [Phase 5: NestJS Core Concepts](docs/roadmap.md#phase-5-nestjs-core-concepts) | Services, modules, DI, pipes, DTOs, exception filters |
| 8 | [Phase 6: Database Integration](docs/roadmap.md#phase-6-database-integration-with-nestjs) | TypeORM, Prisma, MongoDB, CRUD, relations, query builder |
| 9 | [Phase 7: Next.js Basics](docs/roadmap.md#phase-7-nextjs-basics-frontend-start) | File-based routing, SSG/SSR/ISR, layouts, navigation |
| 10 | [Phase 8: Next.js Core Concepts](docs/roadmap.md#phase-8-nextjs-core-concepts) | Client/server components, forms (RHF + Zod), Tailwind/ShadCN, API routes |
| 11 | [Phase 9: Connecting Frontend & Backend](docs/roadmap.md#phase-9-connecting-frontend--backend) | CORS, axios/fetch, SWR, React Query |
| 12 | [Phase 10: Authentication & Authorization](docs/roadmap.md#phase-10-authentication--authorization) | bcrypt, JWT, Passport, sessions, cookies, guards, serialization |
| 13 | [Phase 11: Advanced Authentication](docs/roadmap.md#phase-11-advanced-authentication) | Google OAuth, GitHub OAuth, 2FA, NextAuth, Clerk, Auth0 |
| 14 | [Phase 12: State Management & Frontend Best Practices](docs/roadmap.md#phase-12-state-management--frontend-best-practices) | Zustand, Redux Toolkit, Context API, pagination, filtering |
| 15 | [Phase 13: Advanced NestJS](docs/roadmap.md#phase-13-advanced-nestjs) | Interceptors, guards, config, logging, CQRS, Swagger, rate limiting |
| 16 | [Phase 14: Advanced Next.js](docs/roadmap.md#phase-14-advanced-nextjs) | App Router, server components, middleware, image/font optimization, i18n |
| 17 | [Phase 15: Caching, Performance & Real-time](docs/roadmap.md#phase-15-caching-performance--real-time) | Redis, WebSocket gateways, GraphQL, Apollo Federation |
| 18 | [Phase 16: Payments & Third-Party Integrations](docs/roadmap.md#phase-16-payments--third-party-integrations) | Stripe, Nodemailer, Gmail, email templates |
| 19 | [Phase 17: Testing](docs/roadmap.md#phase-17-testing) | Jest, unit tests, E2E tests, React Testing Library, Playwright, Cypress |
| 20 | [Phase 18: DevOps & Deployment](docs/roadmap.md#phase-18-devops--deployment) | Docker, env management, migrations, Heroku, Vercel, GitHub Actions |
| 21 | [Phase 19: Microservices Architecture](docs/roadmap.md#phase-19-microservices-architecture) | TCP, gRPC, RabbitMQ, GKE, EKS, Helm, API Gateway |
| 22 | [Phase 20: System Design & Expert Level](docs/roadmap.md#phase-20-system-design--expert-level) | DDD, Hexagonal, Clean Architecture, Event Sourcing, AI Integration |
| 23 | [Phase 21: Final Projects](docs/roadmap.md#phase-21-final-projects) | Todo CRUD → E-Commerce → Trello Clone → SaaS Dashboard → Microservices Booking System |

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-blueviolet?style=for-the-badge" /></a></p>

<br>

<br>

#

## Folder Structure
```
Nestjs-Nextjs-Journey/
├── docs/
│   ├── roadmap.md              # Full 21-phase, 549-topic curriculum
│   └── progress-tracker.md     # Trackable checklist (⬜ / 🔄 / ✅)
│
├── phase-01-foundation/        # JavaScript, React, Node.js basics
│   └── (your practice code)
│
├── phase-02-typescript/        # TypeScript mastery
│   └── (your practice code)
│
├── phase-03-dev-setup/         # Dev environment configs
│   └── (your practice code)
│
├── phase-04-nestjs-basics/     # First NestJS app
│   └── (your practice code)
│
├── phase-05-nestjs-core/       # Services, modules, DI, pipes
│   └── (your practice code)
│
├── phase-06-database/          # TypeORM, Prisma, MongoDB
│   └── (your practice code)
│
├── phase-07-nextjs-basics/     # First Next.js app
│   └── (your practice code)
│
├── phase-08-nextjs-core/       # Forms, UI, routing
│   └── (your practice code)
│
├── phase-09-fullstack-connect/ # Connecting NestJS + Next.js
│   └── (your practice code)
│
├── phase-10-auth/              # bcrypt, JWT, sessions, guards
│   └── (your practice code)
│
├── phase-11-advanced-auth/     # OAuth, 2FA, NextAuth
│   └── (your practice code)
│
├── phase-12-state-mgmt/        # Zustand, Redux Toolkit
│   └── (your practice code)
│
├── phase-13-advanced-nestjs/   # Interceptors, CQRS, Swagger
│   └── (your practice code)
│
├── phase-14-advanced-nextjs/   # App Router, server components
│   └── (your practice code)
│
├── phase-15-cache-realtime/    # Redis, WebSockets, GraphQL
│   └── (your practice code)
│
├── phase-16-payments/          # Stripe, Email integrations
│   └── (your practice code)
│
├── phase-17-testing/           # Jest, Playwright, Cypress
│   └── (your practice code)
│
├── phase-18-devops/            # Docker, CI/CD, deployment
│   └── (your practice code)
│
├── phase-19-microservices/     # TCP, gRPC, RabbitMQ, K8s
│   └── (your practice code)
│
├── phase-20-system-design/     # DDD, Hexagonal, AI integration
│   └── (your practice code)
│
├── phase-21-projects/          # Capstone projects
│   ├── todo-crud/
│   ├── auth-app/
│   ├── ecommerce/
│   ├── chat-app/
│   ├── trello-clone/
│   ├── saas-dashboard/
│   └── reservations-microservices/
│
├── .gitignore
└── README.md
```

<p align="right"><a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-blueviolet?style=for-the-badge" /></a></p>

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
