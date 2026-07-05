<div id="top"></div>

# 🗺️ Django + Next.js Roadmap — Zero to Expert

> A complete, deeply-structured learning path to become a **master full-stack developer** with a **Django (Python)** backend and a **Next.js (TypeScript/React)** frontend — from language fundamentals through REST APIs, authentication, real-time systems, testing, DevOps, scaling, distributed architecture, and AI integration.

**25 phases · 622 topics.** Each phase is grouped into thematic sub-sections and ordered as a dependency chain — work top to bottom. Track your progress in [`progress-tracker.md`](progress-tracker.md).

---

## 📌 Table of Contents

| Phase | Title | Topics |
|-------|-------|--------|
| 1 | [Foundation — Python Basics](#phase-1-foundation--python-basics) | 32 |
| 2 | [Python Deep Dive](#phase-2-python-deep-dive) | 31 |
| 3 | [JavaScript & TypeScript Foundation](#phase-3-javascript--typescript-foundation) | 33 |
| 4 | [React Fundamentals](#phase-4-react-fundamentals) | 22 |
| 5 | [Development Environment Setup](#phase-5-development-environment-setup) | 14 |
| 6 | [Django Basics](#phase-6-django-basics) | 26 |
| 7 | [Django Models & ORM](#phase-7-django-models--orm) | 37 |
| 8 | [Django Admin, Forms & Auth Basics](#phase-8-django-admin-forms--auth-basics) | 22 |
| 9 | [Django REST Framework (DRF)](#phase-9-django-rest-framework-drf) | 34 |
| 10 | [Database Integration (PostgreSQL)](#phase-10-database-integration-postgresql) | 21 |
| 11 | [Next.js Basics](#phase-11-nextjs-basics) | 24 |
| 12 | [Next.js Core Concepts](#phase-12-nextjs-core-concepts) | 28 |
| 13 | [Connecting Frontend & Backend](#phase-13-connecting-frontend--backend) | 18 |
| 14 | [Authentication & Authorization](#phase-14-authentication--authorization) | 32 |
| 15 | [Advanced Authentication](#phase-15-advanced-authentication) | 24 |
| 16 | [State Management & Frontend Best Practices](#phase-16-state-management--frontend-best-practices) | 20 |
| 17 | [Advanced Django](#phase-17-advanced-django) | 24 |
| 18 | [Advanced Next.js](#phase-18-advanced-nextjs) | 22 |
| 19 | [Caching, Performance & Real-time](#phase-19-caching-performance--real-time) | 24 |
| 20 | [Async Tasks, Payments & Integrations](#phase-20-async-tasks-payments--integrations) | 24 |
| 21 | [Testing](#phase-21-testing) | 24 |
| 22 | [DevOps & Deployment](#phase-22-devops--deployment) | 25 |
| 23 | [Scaling & Architecture](#phase-23-scaling--architecture) | 22 |
| 24 | [System Design & Expert Level](#phase-24-system-design--expert-level) | 22 |
| 25 | [Final Projects](#phase-25-final-projects) | 17 |

Appendices: [Final Mastery Goals](#-final-mastery-goals) · [Key Tools & Libraries](#-key-tools--libraries)

---

## Phase 1: Foundation — Python Basics

> Django is Python. Build a rock-solid base before touching the framework.

### Getting Started with Python
1. What is Python & Where It's Used
2. Installing Python & the Interpreter
3. Running Scripts vs the REPL
4. Comments, Indentation & Code Style

### Variables & Data Types
5. Variables & Assignment
6. Numbers (int, float, complex)
7. Strings & String Methods
8. Booleans & None
9. Type Conversion / Casting
10. f-strings & String Formatting

### Operators & Expressions
11. Arithmetic & Assignment Operators
12. Comparison Operators
13. Logical Operators (and / or / not)
14. Membership & Identity Operators (in, is)

### Data Structures
15. Lists & List Methods
16. Tuples
17. Dictionaries & Dict Methods
18. Sets & Set Operations
19. Slicing
20. Comprehensions (list / dict / set)

### Control Flow
21. if / elif / else
22. for Loops & range()
23. while Loops
24. break, continue, pass

### Functions & Errors
25. Defining Functions & Return Values
26. Positional, Keyword & Default Arguments
27. `*args` and `**kwargs`
28. Lambda Functions
29. Variable Scope (local / global / nonlocal)
30. Exception Handling (try / except / finally)
31. Raising Exceptions
32. File I/O (open, read, write, `with`)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 2: Python Deep Dive

> OOP, decorators, typing, and async — everything Django leans on internally.

### Modules & Environments
33. Modules & Packages
34. The Import System & `__name__`
35. Virtual Environments (`venv`)
36. `pip`, `requirements.txt` & Dependency Management
37. The Python Standard Library Tour

### Object-Oriented Programming
38. Classes & Objects
39. `__init__` & Instance Attributes
40. Instance vs Class Attributes
41. Instance, Class & Static Methods
42. Inheritance
43. `super()` & Method Overriding
44. Multiple Inheritance & MRO
45. Encapsulation & Name Mangling
46. Properties (`@property`)
47. Dunder / Magic Methods
48. Abstract Base Classes (`abc`)

### Functional & Advanced Python
49. First-Class Functions & Closures
50. Decorators
51. Decorators with Arguments
52. Iterators & the Iterator Protocol
53. Generators & `yield`
54. Context Managers (`with`, `__enter__`/`__exit__`)
55. Generator Expressions & Lazy Evaluation

### Typing & Modern Python
56. Type Hints & Annotations
57. The `typing` Module (Optional, Union, List, Dict)
58. Dataclasses
59. Enums
60. Pattern Matching (`match` / `case`)

### Concurrency
61. Threads vs Processes vs Async (overview)
62. `asyncio` & `async` / `await`
63. Pythonic Idioms & PEP 8

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 3: JavaScript & TypeScript Foundation

> The frontend runs on TypeScript. Get fluent before Next.js.

### Modern JavaScript
64. JavaScript & the Browser / Node Runtime
65. `let` / `const` / `var` & Scope
66. Data Types & Coercion
67. Template Literals
68. Arrow Functions
69. Destructuring (array & object)
70. Spread & Rest Operators
71. Default & Named Parameters
72. Array Methods (`map` / `filter` / `reduce` / `find`)
73. Object Methods & Optional Chaining

### Asynchronous JavaScript
74. Callbacks & the Event Loop
75. Promises
76. `async` / `await`
77. Error Handling in Async Code
78. The Fetch API

### Modules & Tooling
79. ES Modules (import / export)
80. npm & `package.json`
81. Bundlers Overview (Vite / Webpack / Turbopack)

### TypeScript Fundamentals
82. What is TypeScript & Why
83. Setup & `tsconfig.json`
84. Basic Types
85. Arrays, Tuples & Enums
86. Type Annotations vs Inference
87. Functions & Return Types
88. Objects & Optional Properties

### TypeScript Type System
89. Interfaces
90. Type Aliases
91. Union & Intersection Types
92. Literal Types & Narrowing
93. Generics
94. Utility Types (Partial, Pick, Omit, Record)
95. `unknown`, `never`, `any`
96. Type Guards & Assertions

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 4: React Fundamentals

> Next.js is React. Nail the component model and hooks.

### React Basics
97. What is React & the Virtual DOM
98. JSX
99. Functional Components
100. Props
101. Rendering Lists & Keys
102. Conditional Rendering
103. Handling Events

### State & Hooks
104. `useState`
105. `useEffect` & the Dependency Array
106. `useRef`
107. `useContext`
108. `useReducer`
109. `useMemo` & `useCallback`
110. Custom Hooks

### Component Patterns
111. Component Composition
112. Lifting State Up
113. Controlled vs Uncontrolled Inputs
114. Forms in React
115. Prop Drilling & Context
116. Error Boundaries
117. React Performance & `memo`
118. Thinking in React (component design)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 5: Development Environment Setup

> Tooling that will carry you the whole journey.

### Editor & Runtimes
119. VS Code Setup & Essential Extensions
120. Python via `pyenv`
121. Node via `nvm`

### Version Control
122. Git Fundamentals
123. GitHub Workflow (branches, PRs)
124. `.gitignore` & Repo Hygiene

### Backend Tooling
125. PostgreSQL Installation
126. Docker Installation & Basics
127. Postman / REST Client

### Quality Tooling
128. Ruff, Black & isort (Python)
129. ESLint & Prettier (JS / TS)
130. Pre-commit Hooks
131. EditorConfig
132. Debugging (Python & Node)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 6: Django Basics

> First contact with the framework: projects, apps, URLs, views, templates.

### Introduction
133. What is Django
134. Why Django (batteries-included)
135. Django vs Flask vs FastAPI
136. The Request / Response Cycle
137. MVT Architecture (vs MVC)

### Project Setup
138. Installing Django
139. Starting a Project (`startproject`)
140. Project vs App (`startapp`)
141. `manage.py` Commands
142. `settings.py` Overview
143. The Development Server (`runserver`)

### URLs & Views
144. URL Configuration (URLconf)
145. Path Converters & URL Parameters
146. Function-Based Views
147. The `HttpRequest` Object
148. `HttpResponse` & `JsonResponse`
149. Redirects & Status Codes
150. Including App URLs & Namespacing

### Templates (server-rendered basics)
151. Django Templates (DTL) Overview
152. Template Variables & Tags
153. Template Filters
154. Template Inheritance (`extends` / `block`)
155. Static Files

### Class-Based Views
156. Class-Based Views (CBV) Intro
157. Generic Display Views (ListView, DetailView)
158. Generic Editing Views (CreateView, UpdateView, DeleteView)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 7: Django Models & ORM

> The ORM is Django's crown jewel — and where your Eloquent instincts transfer.

### Models Basics
159. Introduction to the ORM
160. Defining Models
161. Field Types
162. Field Options (null, blank, default, choices)
163. Model `Meta` Options
164. `__str__` & Model Representation

### Migrations
165. Migrations Overview
166. `makemigrations` & `migrate`
167. Migration Files Explained
168. Data Migrations
169. Reversing & Squashing Migrations

### Querying the Database
170. The Django Shell (`shell` / `shell_plus`)
171. Creating Objects (`create` / `save`)
172. Retrieving Objects (`all`, `get`, `filter`)
173. Field Lookups
174. QuerySet Laziness & Evaluation
175. Chaining, `exclude` & `order_by`
176. Slicing & Limiting QuerySets
177. Updating Records
178. Deleting Records
179. `get_or_create` & `bulk_create`

### Aggregation & Expressions
180. Aggregation (Count, Sum, Avg)
181. Annotation
182. `F` Expressions
183. `Q` Objects & Complex Lookups
184. Conditional Expressions (`Case` / `When`)

### Relationships
185. `ForeignKey` (One-to-Many)
186. `OneToOneField`
187. `ManyToManyField`
188. Related Managers & `related_name`
189. Reverse Relations
190. `select_related` (FK / 1-1 joins)
191. `prefetch_related` (M2M / reverse)

### Advanced ORM
192. Custom Model Managers
193. Custom QuerySets
194. Model Methods & Properties
195. Model Validation (`clean` / `full_clean`)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 8: Django Admin, Forms & Auth Basics

> The admin and the built-in auth system — free superpowers.

### The Admin Site
196. Django Admin Overview
197. Registering Models
198. Customizing `ModelAdmin` (list_display, search, filters)
199. Admin Inlines
200. Admin Actions
201. Overriding Admin Templates & Branding

### Forms
202. Django Forms
203. Form Fields & Widgets
204. Form Validation (`clean` methods)
205. `ModelForm`
206. Rendering & Handling Forms in Views
207. Formsets

### Auth Basics
208. The Authentication System Overview
209. The Built-in User Model
210. `login` / `logout` / `authenticate`
211. Login Required (decorator & mixin)
212. Custom User Model (`AbstractUser`)
213. User Registration Flow
214. Permissions & Groups
215. The Messages Framework
216. The Sessions Framework
217. Password Management & Validators

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 9: Django REST Framework (DRF)

> Turn Django into an API backend for Next.js.

### REST & DRF Setup
218. What is a REST API
219. REST Principles & Resource Design
220. Installing & Configuring DRF
221. The Browsable API

### Serializers
222. Serializers
223. Serializer Fields
224. `ModelSerializer`
225. Serializer Validation (field & object level)
226. Nested Serializers
227. `SerializerMethodField`
228. `read_only` / `write_only` Fields
229. Handling Relationships in Serializers

### Views
230. Function-Based API Views (`@api_view`)
231. `APIView` (Class-Based)
232. Request & Response Objects
233. Status Codes
234. Mixins
235. Generic API Views
236. ViewSets
237. Routers & URL Registration

### API Features
238. Pagination
239. Filtering (`django-filter`)
240. Search & Ordering
241. Throttling / Rate Limiting
242. Content Negotiation
243. Versioning

### Permissions & Docs
244. DRF Authentication Classes
245. DRF Permission Classes
246. Custom Permissions
247. Object-Level Permissions
248. OpenAPI Schema (`drf-spectacular`)
249. Swagger / Redoc UI
250. Testing the API (browsable + Postman)
251. Error Handling & Custom Exception Handler

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 10: Database Integration (PostgreSQL)

> Production databases, done right.

### PostgreSQL Setup
252. Why PostgreSQL
253. Installing / Running Postgres (local)
254. Running Postgres in Docker
255. Connecting Django to Postgres
256. Database Drivers (`psycopg`)
257. Environment-based DB Config (`django-environ`)

### Schema & Integrity
258. Database Indexes
259. Composite & Partial Indexes
260. Unique Constraints
261. Check Constraints
262. Foreign Key Constraints & `on_delete`

### Transactions & Performance
263. Transactions (`atomic`)
264. `select_for_update` & Locking
265. The N+1 Problem & Detection
266. Query Optimization & `explain()`
267. Database Views & Raw SQL
268. Connection Pooling

### Postgres Power Features
269. `JSONField`
270. `ArrayField` & HStore
271. Full-Text Search
272. `pgvector` (intro for the AI phase)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 11: Next.js Basics

> The frontend framework: routing, layouts, rendering strategies.

### Introduction
273. What is Next.js
274. Why Next.js
275. Next.js vs React (CRA / Vite)
276. App Router vs Pages Router
277. Next.js Architecture & Rendering Overview

### Setup & Structure
278. Creating a Next.js App
279. Project Structure & Conventions
280. The `app/` Directory
281. Running & Building the App

### Routing
282. File-based Routing
283. Pages (`page.tsx`)
284. Layouts (`layout.tsx`)
285. Static Routes
286. Dynamic Routes (`[id]`)
287. Catch-all & Optional Routes
288. Route Groups & Private Folders
289. Linking & Navigation (`Link`, `useRouter`)
290. `loading.tsx` & `error.tsx`
291. `not-found` & Special Files

### Rendering Strategies
292. The Metadata API
293. Static Site Generation (SSG)
294. Server-Side Rendering (SSR)
295. Incremental Static Regeneration (ISR)
296. When to Use Each Rendering Method

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 12: Next.js Core Concepts

> Components, styling, forms, and the App Router essentials.

### Components
297. Server vs Client Components
298. The `'use client'` Directive
299. Component Composition Patterns
300. Passing Server Data to Client Components
301. Reusable Components

### Styling
302. Global CSS & CSS Modules
303. Tailwind CSS Setup
304. Tailwind Patterns & Responsive Design
305. ShadCN UI
306. Dark Mode / Theming

### Forms
307. Forms in Next.js
308. React Hook Form
309. Zod Validation
310. RHF + Zod Integration
311. Server Actions
312. Handling Server Errors & Field Errors
313. Input & Button Components

### UI & Assets
314. Building a Responsive Navbar / Header
315. `next/image` (Image Optimization)
316. `next/font` (Font Optimization)
317. Icons & Asset Handling

### API & Utilities
318. Route Handlers (API Routes)
319. Middleware (basics)
320. Environment Variables in Next.js
321. Custom Hooks
322. Dynamic Imports & Lazy Loading
323. Suspense Boundaries
324. Cookies & Headers in Next.js

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 13: Connecting Frontend & Backend

> Wire Next.js to the DRF API end to end.

### API Wiring
325. CORS Setup (`django-cors-headers`)
326. API Client Setup (axios instance)
327. Making Requests to DRF
328. Environment Config for API URLs
329. Typing API Responses (shared types)

### Data Fetching
330. Server-side Fetching in Next.js
331. Client-side Fetching with SWR
332. Client-side Fetching with React Query
333. Query Keys & Caching (React Query)
334. Mutations & Invalidation
335. Optimistic Updates

### UX Concerns
336. Handling Loading States
337. Handling Errors & Retries
338. Pagination & Infinite Scroll
339. Debounced Search
340. File Uploads (multipart) End-to-End
341. API Contract Consistency (OpenAPI → types)
342. Auth-aware Requests (interceptors)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 14: Authentication & Authorization

> The deep dive: hashing, sessions, JWT, cookies, permissions, protected routes.

### Fundamentals
343. Authentication vs Authorization
344. How Password Hashing Works
345. Django Password Hashing & Hashers
346. Auth Approaches: Session vs Token vs JWT

### Session & Token Auth
347. Session Authentication (DRF)
348. Token Authentication (DRF)
349. CSRF Protection

### JWT Auth
350. How JWT Works
351. Installing & Configuring SimpleJWT
352. Access & Refresh Tokens
353. Obtaining & Refreshing Tokens
354. Token Verification & Expiry
355. Token Blacklisting & Logout
356. Refresh Token Rotation

### Auth Endpoints
357. User Registration Endpoint
358. Login Endpoint
359. Current User (`/me`) Endpoint
360. Serializing the User Safely
361. Password Change Endpoint

### Frontend Auth
362. Storing Tokens Securely (HttpOnly cookies vs storage)
363. Auth Context / Provider in Next.js
364. Attaching Tokens to Requests
365. Protected Routes with Middleware
366. Handling Token Refresh on the Client
367. Persisting & Restoring Sessions

### Authorization
368. DRF Permissions Recap
369. Custom Permission Classes
370. Object-Level Permissions
371. Roles & Groups
372. Role-Based Access Control (RBAC)
373. Permission Mixins & Decorators
374. Protecting Frontend UI by Role

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 15: Advanced Authentication

> OAuth, social login, 2FA, and managed auth providers.

### OAuth
375. OAuth 2.0 Flow
376. OAuth 2.0 Scopes
377. `django-allauth` Setup
378. Google OAuth (Cloud Console Setup)
379. Google OAuth (Backend Integration)
380. GitHub OAuth (App Setup)
381. GitHub OAuth (Backend Integration)
382. Social Account Linking
383. Handling OAuth Callbacks in Next.js

### Managed Auth on the Frontend
384. NextAuth.js (Auth.js) Overview
385. NextAuth Providers & Config
386. NextAuth with a Django Backend
387. Clerk (Overview & Tradeoffs)
388. Auth0 (Overview & Tradeoffs)

### 2FA & Account Security
389. 2FA Flow Overview
390. TOTP & Authenticator Apps (`pyotp`)
391. Generating & Displaying QR Codes
392. Enabling & Verifying 2FA
393. Recovery Codes
394. Email Verification Flow
395. Password Reset Flow (email)
396. Rate Limiting Auth Endpoints
397. Account Lockout & Brute-Force Protection
398. Security Headers & Best Practices

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 16: State Management & Frontend Best Practices

> Client vs server state, and the UX patterns every app needs.

### Concepts
399. Client State vs Server State
400. Choosing a State Solution

### Context & Zustand
401. Context API Patterns
402. Zustand Setup
403. Zustand Stores & Actions
404. Zustand Middleware (persist, devtools)
405. Global Auth State with Zustand

### Redux
406. Redux Core Concepts
407. Redux Toolkit Setup
408. Slices & Reducers
409. RTK Query

### Data-Driven UI Patterns
410. Pagination UI
411. Searching UI
412. Sorting UI
413. Filtering UI
414. Selecting Items / Bulk Actions
415. Form Submission Patterns
416. Toast / Notification System
417. Error Boundaries & Fallbacks
418. Loading Skeletons

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 17: Advanced Django

> Signals, middleware, caching, custom commands, hardening.

### Extensibility
419. Django Signals
420. When (Not) to Use Signals
421. Custom Middleware
422. Class-Based View Mixins
423. Custom Model Fields
424. Generic Relations (ContentTypes)
425. Model Inheritance (abstract / multi-table / proxy)

### Configuration & Ops
426. Splitting Settings (base / dev / prod)
427. `django-environ` & 12-Factor Config
428. Logging Configuration
429. Custom Management Commands
430. Django Debug Toolbar
431. Custom Exceptions & Error Handling

### Caching
432. The Caching Framework
433. Cache Backends (Redis)
434. Per-View Caching
435. Template Fragment Caching
436. Low-Level Cache API & Invalidation

### Robustness & i18n
437. File & Media Handling (storage backends)
438. Internationalization (i18n) & Localization
439. Time Zones
440. Security Best Practices (settings hardening)
441. Performance Profiling
442. Feature Flags & Config Toggles

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 18: Advanced Next.js

> The full App Router power set.

### App Router Deep Dive
443. App Router Architecture
444. Server Components Deep Dive
445. Client Components Deep Dive
446. Server Actions (Deep Dive)
447. Streaming & Suspense
448. Parallel Routes
449. Intercepting Routes
450. Route Handlers (Advanced)

### Runtime & Caching
451. Middleware (Advanced)
452. The Edge Runtime
453. The Caching Model (fetch cache, Data Cache)
454. `revalidatePath` & `revalidateTag`
455. Dynamic vs Static Rendering Control
456. Automatic Code Splitting
457. Dynamic Imports (Advanced)

### SEO & Delivery
458. SEO Optimization
459. Metadata & OpenGraph
460. Sitemap Generation
461. `robots.txt`
462. Internationalization (`next-intl`)
463. Analytics & Web Vitals
464. Error & Not-Found Handling (Advanced)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 19: Caching, Performance & Real-time

> Redis, WebSockets via Channels, and GraphQL.

### Redis
465. Redis Overview & Setup
466. Caching with Redis (Django)
467. Cache Invalidation Strategies
468. Caching API Responses
469. Redis Data Structures
470. Sorted Sets & Rankings / Leaderboards
471. Rate Limiting with Redis

### Real-time (Channels)
472. WebSockets Overview
473. ASGI vs WSGI
474. Django Channels Setup
475. Consumers
476. Routing & Scopes
477. Channel Layers (Redis Backend)
478. Groups & Broadcasting
479. Real-time Chat Implementation
480. Real-time Notifications
481. Presence & Typing Indicators
482. Scaling WebSockets

### GraphQL
483. GraphQL Overview
484. GraphQL with Strawberry / Graphene
485. Types & Schema
486. Queries
487. Mutations
488. GraphQL on the Frontend (Apollo Client)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 20: Async Tasks, Payments & Integrations

> Celery, email, Stripe, file storage.

### Background Tasks
489. Why Background Tasks
490. Celery Overview & Architecture
491. Celery + Redis / RabbitMQ Setup
492. Writing & Calling Tasks
493. Task Arguments & Return Handling
494. Periodic Tasks (Celery Beat)
495. Task Retries & Error Handling
496. Task Chaining & Workflows (chains / groups)
497. Monitoring with Flower

### Email
498. Sending Email (Django email)
499. SMTP / Gmail Setup
500. HTML Email Templates
501. Async Email with Celery
502. Transactional Email Providers (overview)

### Payments (Stripe)
503. Stripe Overview & Concepts
504. Stripe Setup & API Keys
505. Products, Prices & Customers
506. Creating Checkout Sessions / PaymentIntents
507. Stripe Webhooks
508. Verifying Webhook Signatures
509. Confirming Orders
510. Stripe Frontend Integration (Elements)

### Files & Media
511. File Uploads in DRF
512. Storing Files on S3 (`django-storages`)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 21: Testing

> Backend and frontend, unit through E2E.

### Foundations
513. Testing Philosophy & the Pyramid
514. `pytest` & `pytest-django` Setup
515. Django `TestCase` vs pytest
516. Test Database & Isolation
517. Fixtures
518. `factory_boy` & Fake Data

### Backend Tests
519. Testing Models
520. Testing Managers & QuerySets
521. Testing Views
522. Testing DRF APIs (`APIClient`)
523. Testing Authentication & Permissions
524. Mocking & `unittest.mock`
525. Testing Celery Tasks
526. Testing Signals
527. Coverage Reports
528. Parametrized Tests

### Frontend Tests
529. Frontend Testing Overview
530. Jest Setup
531. React Testing Library
532. Testing Components
533. Testing Hooks
534. Mocking API Calls (MSW)

### End-to-End
535. E2E with Playwright
536. E2E with Cypress

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 22: DevOps & Deployment

> Ship it: Docker, CI/CD, and production hosting.

### Docker
537. Docker Basics
538. Dockerizing Django
539. Gunicorn / Uvicorn
540. Dockerizing Next.js
541. `docker-compose` (multi-service)
542. Multi-stage Builds & Image Optimization

### Serving & Config
543. Nginx as Reverse Proxy
544. Serving Static Files (WhiteNoise / S3)
545. Serving Media Files
546. Environment Variables & Secrets Management
547. Multiple Environments (dev / staging / prod)
548. Production `settings.py` Hardening

### Data & Release
549. Database Migrations in Production
550. `collectstatic` in Production
551. Zero-downtime Deploys
552. Backups & Restore
553. Health Checks & Readiness Probes

### CI/CD & Hosting
554. Logging & Monitoring (Sentry)
555. CI/CD with GitHub Actions
556. Automated Testing in CI
557. Deploying Django (Railway / Render / Fly.io)
558. Deploying Django (AWS / DigitalOcean)
559. Deploying Next.js (Vercel)
560. Deploying Next.js (Self-host / Netlify)
561. Custom Domains, HTTPS & Env Wiring

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 23: Scaling & Architecture

> From monolith to distributed systems.

### Architecture Decisions
562. Monolith vs Microservices
563. Modular Monolith First
564. When to Split Services
565. Service Boundaries & Contracts

### Communication
566. Synchronous Communication (REST)
567. gRPC
568. Message Queues (RabbitMQ / Kafka)
569. Event-Driven Architecture
570. Sagas & Distributed Transactions
571. API Gateway

### Data & Scale
572. Database per Service
573. Shared Libraries & Code Reuse
574. Read Replicas & Sharding (overview)
575. Caching Layers at Scale
576. CDN & Static Assets

### Infrastructure
577. Load Balancing
578. Horizontal Scaling & Statelessness
579. Kubernetes Overview
580. Deploying to Kubernetes
581. Helm Charts
582. Autoscaling
583. Observability (metrics, tracing, logs)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 24: System Design & Expert Level

> Architecture patterns, distributed-systems theory, and AI integration.

### Architecture Patterns
584. Domain-Driven Design (DDD)
585. Bounded Contexts & Ubiquitous Language
586. Clean Architecture in Django
587. Hexagonal (Ports & Adapters) Architecture
588. The Repository Pattern
589. The Service Layer Pattern
590. CQRS
591. Event Sourcing

### Distributed Systems Theory
592. Distributed Systems Basics
593. Consistency & the CAP Theorem
594. Idempotency & Retries
595. Rate Limiting & Backpressure
596. Designing for Failure (circuit breakers)
597. The System Design Interview Framework

### AI Integration
598. LLM Integration (OpenAI / Anthropic)
599. Prompt Design & Structured Output
600. AI Summarizer
601. AI Chat (RAG Basics)
602. Embeddings & Vector Search (`pgvector`)
603. AI Search
604. AI-powered Documentation Generator
605. Cost, Caching & Guardrails for LLM Apps

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## Phase 25: Final Projects

> Build real, deployable applications — small to microservices-scale.

### Beginner
606. Project: Todo CRUD App
607. Project: Static Blog (Next.js SSG + Django API)
608. Project: Full-stack Auth App

### Intermediate
609. Project: Blogging System (CMS-style)
610. Project: Expense Tracker
611. Project: Pomodoro / Habit Tracker
612. Project: Job Board

### Advanced
613. Project: E-Commerce Store (Stripe)
614. Project: Real-time Chat App (Channels)
615. Project: Task Management Platform (Trello Clone)
616. Project: Social Media App

### Expert
617. Project: SaaS Dashboard (multi-tenant)
618. Project: Booking / Reservation System
619. Project: Learning Management System (LMS)
620. Project: Microservices Reservation System
621. Project: AI-powered Documentation Generator
622. Project: Real-time Collaborative Editor

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## 🎯 Final Mastery Goals

By the end of this roadmap you should be able to:

- Design and build scalable, modular, production-ready full-stack apps with Django + Next.js.
- Model complex domains cleanly with the ORM and keep views thin via a service layer.
- Ship secure auth (JWT, sessions, OAuth, 2FA) and correct authorization (RBAC, object-level).
- Reason about performance: caching, N+1 elimination, query plans, and real-time at scale.
- Test confidently across the pyramid — unit, integration, and E2E — front and back.
- Deploy, observe, and operate systems: Docker, CI/CD, migrations, monitoring, zero-downtime.
- Make architecture decisions (monolith vs services, DDD, CQRS) and defend the tradeoffs.
- Integrate LLMs responsibly (RAG, embeddings, guardrails, cost control).
- Mentor others, contribute to OSS, and write about what you've built.

---

## 📚 Key Tools & Libraries

### Backend (Django)
- **Core:** Django, Django REST Framework
- **Auth:** SimpleJWT, django-allauth, pyotp
- **Data:** PostgreSQL, psycopg, django-environ, pgvector
- **Async & Real-time:** Celery, Redis, Django Channels, RabbitMQ
- **API Docs:** drf-spectacular
- **Quality:** pytest, pytest-django, factory_boy, Ruff, Black, isort, mypy
- **Ops:** Docker, Gunicorn/Uvicorn, Nginx, WhiteNoise, django-storages, Sentry

### Frontend (Next.js)
- **Core:** Next.js (App Router), React, TypeScript
- **UI:** Tailwind CSS, ShadCN, Material UI
- **Data:** React Query (TanStack), SWR, axios
- **State:** Zustand, Redux Toolkit + RTK Query
- **Forms:** React Hook Form, Zod
- **Auth:** NextAuth (Auth.js), Clerk, Auth0
- **Testing:** Jest, React Testing Library, MSW, Playwright, Cypress

---

**Total: 622 topics across 25 phases.** Update [`progress-tracker.md`](progress-tracker.md) as you go. Happy building! 🚀
