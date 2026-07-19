<div id="top"></div>

# 🛠️ Projects — Build-As-You-Learn

> The **project half** of the [Django-Nextjs-Journey](../README.md). The [roadmap](../docs/roadmap.md) teaches the concepts; this folder turns each level into something **real, useful, and shippable**.

Every project here follows three non-negotiable rules:

1. **No toys.** No calculators, no to-do clones for their own sake. Each project has a one-line reason to exist that a real person (often *me*) would nod at — something worth running, not just worth grading.
2. **Each project rehearses the next.** Most small projects here graduate into a **module of the big product** (see below). I don't build the same thing twice — I build a slice, then plug the slice in.
3. **One north star.** Everything points at **`DjangoNextBaseX`** — my Django + Next.js answer to [LaraBaseX](https://github.com/ayush-sleeping/LaraBaseX). That's the artifact that proves the experience and becomes the foundation for real ERP / CRM / SaaS work later.

Each project lives in its **own GitHub repo**. When it's done, its link goes in the [Project Index](#-project-index) below. This file is the map + tracker; the repos are the code.

> **Started:** 2026-07-20 · **6-month target window:** Jul 2026 → Jan 2027 (Levels 1 + 2).

---

## 🌟 The North Star — `DjangoNextBaseX`

> *Working name — rename freely.* The Django + Next.js equivalent of LaraBaseX: a production-grade starter I can `git clone` and build any real product on top of.

LaraBaseX gives me (Laravel side): Sanctum auth, Spatie roles/permissions, Inertia+React admin, Docker, PHPStan, Pest. `DjangoNextBaseX` should give me the same power on this stack:

| LaraBaseX gives me | `DjangoNextBaseX` equivalent | Built during |
|--------------------|--------------------------|--------------|
| Sanctum auth | DRF SimpleJWT (access/refresh, blacklist, `/me`) | Level 2 · Phase 14 |
| Social login / 2FA | django-allauth + `pyotp` TOTP | Level 2 · Phase 15 |
| Spatie permissions | Groups + DRF permission classes + object-level (RBAC) | Level 2 · Phase 14 |
| Inertia + React admin | Next.js App Router dashboard (data tables, forms) | Level 2 · Phases 16, 18 |
| Activity log | Audit trail (`django-simple-history`) | Level 2 · Phase 21 |
| Queues (Horizon) | Celery + Redis + Flower | Level 2 · Phase 20 |
| PHPStan / Pint | mypy + Ruff + Black + isort | Level 1 · Phase 5 (from day one) |
| Pest | pytest + pytest-django + factory_boy | Level 3 · Phase 22 |
| Docker setup | docker-compose (Django + Next + Postgres + Redis) | Level 3 · Phase 23 |

**How it gets built:** I don't build `DjangoNextBaseX` in one sitting. Each Level-2 concept I learn, I build *as a reusable module* and drop it in. By the end of Level 2 the modules assemble into the starter; in Level 3 I add the tests + CI/CD + live deploy that make it production-grade. That's the LaraBaseX milestone from [CLAUDE.md](../CLAUDE.md), reached by accumulation, not by a big-bang build.

---

## 🎯 What This Portfolio Proves — Beyond CRUD

> The bar these repos aim at isn't "can build CRUD." It's the engineering a senior dev or recruiter actually probes for: **you understand the database, the API contract, concurrency, security, tests, and how the thing behaves in production.** Anyone who opens these repos should see that signal without being told.

Each concern below is demonstrated *concretely* — a real endpoint, a real query plan, a real test — not claimed in prose. Competencies are **honestly scoped to the level that introduces them** (no pretending L1 shows sharding).

| What a reviewer checks | How it shows up in these repos | Where |
|------------------------|--------------------------------|-------|
| **API design & contracts** | Versioned DRF API, pagination, filtering, search, throttling, OpenAPI/Swagger docs, a consistent error envelope, idempotent writes | LinkVault · DjangoNextBaseX |
| **DB correctness** | Transactions (`atomic`), row locking (`select_for_update`), DB-level constraints (unique / check / FK `on_delete`), optimistic concurrency | BookMySlot · DjangoNextBaseX |
| **DB performance** | Composite/partial **indexes**, **N+1 elimination** (`select_related` / `prefetch_related`), reading **`explain()` query plans**, connection pooling, full-text search | LinkVault (L1) · DjangoNextBaseX |
| **DB at scale** | Read replicas, sharding strategy, caching layers, `JSONField` / `ArrayField` modeling | L4 capstones |
| **Caching & performance** | Redis caching, deliberate **cache-invalidation strategy**, cached API responses, Redis-backed rate limiting | DjangoNextBaseX · BookMySlot |
| **Async & background work** | Celery tasks, retries & error handling, periodic jobs (Beat), Flower monitoring | BookMySlot · InvoiceForge · DjangoNextBaseX |
| **Real-time** | Django Channels (WebSockets), live notifications, presence | DjangoNextBaseX |
| **Security & hardening** | JWT with rotation + blacklist, password hashing, CSRF/CORS, secrets via env, security headers, **OWASP Top 10**, dependency & secret scanning | DjangoNextBaseX (+ L3 hardening) |
| **Authorization** | RBAC (groups), **object-level permissions**, multi-tenancy scoping, audit trail | DjangoNextBaseX · capstones |
| **Testing** | pytest pyramid (models / managers / views / API / permissions), `factory_boy`, mocking, **coverage**, tests running in CI | L3 on DjangoNextBaseX |
| **Ops & observability** | Docker Compose, Gunicorn + Nginx, health checks, Sentry, structured logging, **zero-downtime migrations** | L3 on DjangoNextBaseX |
| **Architecture** | Thin views + **service layer**, modular monolith, plugin / Git-submodule modules | InvoiceForge → capstones |

---

## 🗄️ Database Mastery — Core First, Then Advanced

> **The rule: never fail on the basics.** Interviews reject people on fundamentals — a wrong JOIN, no idea what an index actually does, can't explain a transaction — far more often than on sharding. So this track is *ordered*: make the core **bulletproof first**, and treat advanced as "later, and that's fine." I don't chase Tier 2 to look smart while Tier 1 has holes.

### Tier 1 — Core basics (must be bulletproof · do these first)

Non-negotiable. If an interviewer asks these, I answer without thinking. Strong core = strong everything on top.

| Core skill | Roadmap | Bulletproof it in |
|------------|---------|-------------------|
| `SELECT` / `WHERE` / `ORDER BY`, **JOINs** (inner + left), `GROUP BY` / `HAVING`, aggregates | Phase 10 (+ raw-SQL drills) | LinkVault |
| Primary keys, foreign keys, `on_delete`, unique constraints | Phase 10 | every model |
| **What an index is** — when to add one, why it speeds reads and costs writes | Phase 10 | LinkVault |
| The **N+1 problem** — spot it, fix it with `select_related` / `prefetch_related` | Phase 10 | LinkVault |
| **Transactions & ACID** — atomic "all-or-nothing", commit / rollback | Phase 10 | BookMySlot |
| **Normalization basics** (1NF → 3NF) & why they matter | ❌ add | model each schema on paper first |
| Reading a simple `EXPLAIN` (seq scan vs index scan) | Phase 10 | LinkVault |

### Tier 2 — Advanced (later · don't stress until the core is automatic)

Genuinely useful, but *not* what gets you rejected. Reach these once Tier 1 is second nature — mostly Level 4.

| Advanced skill | When |
|----------------|------|
| CTEs (`WITH`) & window functions | after core SQL is fluent |
| Isolation levels, MVCC, phantom reads | alongside BookMySlot concurrency |
| Deadlocks; pessimistic vs optimistic locking | alongside BookMySlot |
| Partitioning, replication depth, sharding | Level 4 capstones |
| SQL vs NoSQL tradeoffs, CAP theorem | Level 4 (system design) |

> Progress check: before I open a Tier 2 topic, Tier 1 must already be automatic. Depth on the fundamentals beats shallow breadth — in every interview and every real project.

---

## 🗓️ The 6-Month Plan (Levels 1 + 2)

The stated target: get **genuinely good at the core** of this stack while shipping meaningful projects. Window: **Jul 2026 → Jan 2027**.

| Window | Level | Learn | Ship |
|--------|-------|-------|------|
| **Jul – Sep 2026** (mo 1–3) | **L1 · Foundations** | Python → Django/DRF → Next.js → wire them together | **`repo-radar`** (CLI) → **`LinkVault`** (first full-stack app) |
| **Oct 2026 – Jan 2027** (mo 4–6) | **L2 · Builder** | Auth, RBAC, caching, real-time, Celery, business patterns | **`DjangoNextBaseX`** (assembled from modules) + **`BookMySlot`** + **`InvoiceForge`** |

> By end of window (Jan 2027) I should have: 2 polished full-stack apps, 2 focused business apps, and a reusable production starter — a portfolio that reads like real backend experience, not a course certificate.

---

## 🧭 Project Ladder

Each entry: **why it exists** · **what it proves** · **maps to phases** · **feeds the north star**. Difficulty rises with the roadmap — I only start a project once I've covered the phases it needs.

### Level 1 — Foundations

#### 1. `repo-radar` — a dev-productivity CLI
- **Why it exists:** I juggle a lot of repos day to day. This scans a folder of git repos and reports what's *uncommitted, unpushed, or stale* — a 9am sanity check I'd actually run.
- **What it proves:** Clean Python — OOP, `dataclasses`, type hints, `pathlib` file I/O, `subprocess`, `argparse`, exceptions. The Python *language*, which is the newest part for me.
- **Maps to:** Phases 1–2 (and Phase 5 tooling: Ruff/Black/mypy from the start).
- **Feeds the north star:** Teaches the clean module + service split that `DjangoNextBaseX`'s `services.py` layer mirrors.
- **Real-world stretch:** ship it as a `pipx`-installable package.

#### 2. `LinkVault` — self-hosted bookmark manager (L1 milestone)
- **Why it exists:** A private, searchable, taggable "read-later + reference" vault — Pocket/Raindrop without handing my data to a SaaS. I'd use it daily.
- **What it proves:** The whole L1 stack end to end — Django models + DRF (CRUD, serializers, pagination, filtering, **search**), **Postgres full-text search + JSONField** (Phase 10 tie-in), and a Next.js App Router frontend (server components, React Query, debounced search, optimistic updates).
- **Beyond CRUD (the depth signal):** This is where I prove I *understand the database*, not just query it — composite indexes on the tag/search columns, N+1 elimination verified with Django Debug Toolbar, `explain()` on the search query, and a documented OpenAPI contract. The kind of thing a senior dev opens the repo to check.
- **Maps to:** Phases 6–13 (the entire Foundations milestone: "Next.js frontend talks to a Django REST API").
- **Feeds the north star:** This is my reference for "one resource, done *really* well." Every `DjangoNextBaseX` module copies its shape: thin view → serializer → service → manager.

### Level 2 — Builder

> This is where `DjangoNextBaseX` gets built. The auth / RBAC / audit / notifications work is done **as `DjangoNextBaseX` modules**, not as throwaway apps. The two standalone apps below exist to exercise concepts on a *different* domain so the patterns stick.

#### 3. `DjangoNextBaseX` — the production starter (north star, assembled here)
- **Why it exists:** My reusable foundation for every serious product after this. See [The North Star](#-the-north-star--djangonextbasex).
- **What it proves:** JWT auth, refresh rotation & blacklist, RBAC (groups + object-level permissions), a Next.js admin dashboard, audit trail, caching, background jobs — the LaraBaseX feature bar on this stack.
- **Maps to:** Phases 14–21 (accumulated), then 22–23 for production-readiness.
- **Feeds the north star:** *It is* the north star.

#### 4. `BookMySlot` — scheduling / booking micro-app
- **Why it exists:** A Calendly-lite for a single person or small team: publish availability, take bookings, send reminders. Genuinely useful and a clean domain for hard concepts.
- **What it proves:** **Celery** (reminder emails, Phase 20), **state machines / approval workflows** and money/decimal handling (Phase 21), optional **Stripe** paid bookings, and real-time slot-locking (`select_for_update`).
- **Beyond CRUD (the depth signal):** The double-booking problem is a real concurrency interview question — I solve it with row locking inside a transaction, not app-level checks. Shows I can reason about race conditions, transactions, and idempotency.
- **Maps to:** Phases 19–21.
- **Feeds the north star:** The Celery + notifications wiring lifts straight into `DjangoNextBaseX`.

#### 5. `InvoiceForge` — invoice generator with PDF export
- **Why it exists:** Clients + line items + tax → a downloadable PDF invoice and CSV export. Every freelancer and small business needs this; it's also the seed of an ERP billing module.
- **What it proves:** Complex domain modeling (invoices, line items, ledgers), **PDF generation** (WeasyPrint/ReportLab), **Excel/CSV export** (`openpyxl`), decimal-precise money, scheduled reports.
- **Maps to:** Phase 21 (Reporting & Documents, Billing).
- **Feeds the north star:** Becomes the reference for the **ERP Module** capstone (Phase 26 · #682) and a `DjangoNextBaseX` reporting module.

### Level 3 — Professional

**No new repo — I harden what exists.** Take `DjangoNextBaseX` (or `LinkVault`) all the way to production: pytest across the pyramid, GitHub Actions CI, Docker Compose, and a **live URL I can prove works**. This *is* the job-ready milestone (Phases 22–23).

### Level 4 — Architect (capstones)

The real portfolio pieces, aligned with [Phase 26](../docs/roadmap.md#phase-26-final-projects). Built *on top of* `DjangoNextBaseX`:
- **CRM** — contacts, pipeline, activities, multi-tenant (Phase 26 · #681)
- **ERP Module** — inventory + invoicing + approvals, extending `InvoiceForge` (Phase 26 · #682)
- **Modular-Monolith Plugin App** — a Git-submodule `app-modules` plugin pattern in Django (Phase 26 · #683) — the crown jewel that proves architecture chops.

---

## 📇 Project Index

Repo links go here as each project ships. Status: ⬜ not started · 🔄 in progress · ✅ done & deployed.

| # | Project | Level | Status | Repo | Live |
|---|---------|-------|--------|------|------|
| 1 | `repo-radar` | L1 | ⬜ | _—_ | _—_ |
| 2 | `LinkVault` | L1 | ⬜ | _—_ | _—_ |
| 3 | `DjangoNextBaseX` | L2→L3 | ⬜ | _—_ | _—_ |
| 4 | `BookMySlot` | L2 | ⬜ | _—_ | _—_ |
| 5 | `InvoiceForge` | L2 | ⬜ | _—_ | _—_ |
| 6 | CRM (capstone) | L4 | ⬜ | _—_ | _—_ |
| 7 | ERP Module (capstone) | L4 | ⬜ | _—_ | _—_ |
| 8 | Plugin App (capstone) | L4 | ⬜ | _—_ | _—_ |

---

## 📝 Per-Project Log Template

When I start a project, I add a short section here (or in the project's own README) using this template — so the *why* is recorded, not just the code.

```markdown
### <project-name>
- **Repo:** <link>   ·   **Live:** <link>   ·   **Status:** 🔄
- **Started / Shipped:** YYYY-MM-DD / —
- **Why it exists:** <the real-world reason, one line>
- **Roadmap phases exercised:** <phase numbers>
- **What graduated into DjangoNextBaseX:** <module, or "n/a">
- **What I'd do differently:** <filled in after shipping>
```

<p align="right"><a href="#top">↑ Back to top</a></p>
