<div id="top"></div>

# 🗺️ Django + Next.js Roadmap — Zero to Expert

> A complete, level-based, **fast-track-optimized** path to becoming a **master full-stack developer** with a **Django (Python)** backend and a **Next.js (TypeScript/React)** frontend — from language fundamentals to distributed, plugin-based, AI-integrated systems.

**4 levels · 26 phases · 683 topics.** Every topic is tagged 🔵 core / 🟡 skim / ⚪ skip so an experienced dev can skip revision. Each level ends in a concrete milestone.

## 🧭 The Four Levels

| Level | Phases | Topics | Full est. | Fast-track est. | You can… | Goal |
|-------|--------|--------|-----------|-----------------|----------|------|
| **1 — Foundations** | 1–13 | 342 | ~428h / ~36w | ~261h / ~22w | Build a full-stack CRUD app (Django+DRF ↔ Next.js) | Comfortable in the stack |
| **2 — Builder** | 14–21 | 212 | ~265h / ~22w | ~188h / ~16w | Auth + RBAC + admin + audit + caching + jobs + polished UI | Build a LaraBaseX-class product |
| **3 — Professional** | 22–23 | 54 | ~68h / ~6w | ~45h / ~4w | Test, ship & operate in production (Docker, CI/CD, deploy) | Hireable / job-ready |
| **4 — Architect** | 24–26 | 75 | ~69h / ~6w | ~48h / ~4w | Design distributed/plugin systems, integrate AI, ship capstones | Expert |

> **Totals (learning, phases 1–25):** full path ≈ **829h** (~69 weeks) · your fast-track ≈ **543h** (~45 weeks) at 12 h/week. Phase 26 capstones are separate (pick a few; ~20–60h each).

> **Job-ready (end of Level 3)** on the fast-track ≈ **495h** (~41 weeks) — realistically **~10 months** part-time.

> Estimates assume focused study + practice; ranges are guidance, not a contract.

---

## 🏃 Fast-Track for Experienced Devs (your path)

You're a **senior Laravel + React developer**, so a lot of the foundations are revision. Tags let you skip them:

- 🔵 **core** — new / stack-specific. Learn properly.
- 🟡 **skim** — you know the concept (from Laravel/React); just learn the Django/Next.js *delta*.
- ⚪ **skip** — you already know this well. Verify and move on.
- 🟢 **build** — a project to build, not a topic to read.

**Your split:** 🔵 469 core · 🟡 149 skim · ⚪ 45 skip. The skip/skim topics collapse the effective Level 1 from 342 topics down to roughly the 220 that are genuinely new to you.

### Recommended ordering (momentum-first)

1. **Week 1 — Python sprint + first API.** Skim Phase 1 and cherry-pick the 🔵 core of Phase 2 (decorators, generators, context managers, type hints, dataclasses, async). Do the 🔵 core of Phase 5 (pyenv, Ruff/Black, Postgres). Then jump into Phase 6 + the basics of Phase 9 to stand up a *running* DRF endpoint. **Win: a live API in week 1.**
2. **Weeks 2–4 — Django core.** Phase 7 (ORM = your Eloquent bridge), Phase 8 (admin/forms), Phase 9 (DRF in full), Phase 10 (Postgres specifics). This is the real heart of Level 1.
3. **Skip the frontend revision.** ⚪ Phase 4 (you're a React dev) and most of Phase 3 (🟡 sharpen TS only). Go straight to Phases 11–13 — **Next.js App Router / server components / server actions are the genuinely new part** — and wire the client to your API.
4. **Level 2 — the LaraBaseX build.** Phases 14–21 are mostly 🔵 core (Django auth impl, DRF permissions, Celery, Channels). Build your own LaraBaseX-equivalent as you go: auth + RBAC + admin + audit + caching + a data-table dashboard.
5. **Level 3 — get hireable.** Phases 22–23: 🔵 pytest is new; 🟡 skim the testing concepts and Docker/CI you already know. Deploy one project live end-to-end.
6. **Level 4 — architect.** Phases 24–26: scaling, the plugin/modular architecture (your LeapDesk pattern in Django), system design, AI, and capstones (CRM / ERP / plugin app).

> Prefer depth-first? Just walk phases 1→26 in order and let the tags pace you. The ordering above is only to reach a *running app* sooner.

---

## 📌 Table of Contents

**[Level 1 — Foundations](#-level-1--foundations)** · Phases 1–13 · 342 topics

- [Phase 1: Foundation — Python Basics](#phase-1-foundation--python-basics) — 32
- [Phase 2: Python Deep Dive](#phase-2-python-deep-dive) — 31
- [Phase 3: JavaScript & TypeScript Foundation](#phase-3-javascript--typescript-foundation) — 33
- [Phase 4: React Fundamentals](#phase-4-react-fundamentals) — 22
- [Phase 5: Development Environment Setup](#phase-5-development-environment-setup) — 14
- [Phase 6: Django Basics](#phase-6-django-basics) — 26
- [Phase 7: Django Models & ORM](#phase-7-django-models--orm) — 37
- [Phase 8: Django Admin, Forms & Auth Basics](#phase-8-django-admin-forms--auth-basics) — 22
- [Phase 9: Django REST Framework (DRF)](#phase-9-django-rest-framework-drf) — 34
- [Phase 10: Database Integration (PostgreSQL)](#phase-10-database-integration-postgresql) — 21
- [Phase 11: Next.js Basics](#phase-11-nextjs-basics) — 24
- [Phase 12: Next.js Core Concepts](#phase-12-nextjs-core-concepts) — 28
- [Phase 13: Connecting Frontend & Backend](#phase-13-connecting-frontend--backend) — 18

**[Level 2 — Builder](#-level-2--builder)** · Phases 14–21 · 212 topics

- [Phase 14: Authentication & Authorization](#phase-14-authentication--authorization) — 32
- [Phase 15: Advanced Authentication](#phase-15-advanced-authentication) — 24
- [Phase 16: State Management & Frontend Best Practices](#phase-16-state-management--frontend-best-practices) — 23
- [Phase 17: Advanced Django](#phase-17-advanced-django) — 24
- [Phase 18: Advanced Next.js](#phase-18-advanced-nextjs) — 22
- [Phase 19: Caching, Performance & Real-time](#phase-19-caching-performance--real-time) — 26
- [Phase 20: Async Tasks, Payments & Integrations](#phase-20-async-tasks-payments--integrations) — 24
- [Phase 21: Building Business Systems (SaaS / ERP / CRM Patterns)](#phase-21-building-business-systems-saas--erp--crm-patterns) — 37

**[Level 3 — Professional](#-level-3--professional)** · Phases 22–23 · 54 topics

- [Phase 22: Testing](#phase-22-testing) — 24
- [Phase 23: DevOps & Deployment](#phase-23-devops--deployment) — 30

**[Level 4 — Architect](#-level-4--architect)** · Phases 24–26 · 75 topics

- [Phase 24: Scaling & Architecture](#phase-24-scaling--architecture) — 33
- [Phase 25: System Design & Expert Level](#phase-25-system-design--expert-level) — 22
- [Phase 26: Final Projects](#phase-26-final-projects) — 20

Appendices: [Final Mastery Goals](#-final-mastery-goals) · [Key Tools & Libraries](#-key-tools--libraries)

---

## 🧭 Level 1 — Foundations

> Get comfortable in the stack. Master the two languages, React, and the core of Django + DRF + Next.js. **Milestone:** build a full-stack CRUD app where a Next.js frontend talks to a Django REST API.

*Phases 1–13 · 342 topics · fast-track ≈ 261h (~22w)*

### Phase 1: Foundation — Python Basics

> Django is Python. Build a rock-solid base before touching the framework.

`Fast-track:` 🔵 7 core · 🟡 25 skim · ~18h fast-track

#### Getting Started with Python
1. 🟡 What is Python & Where It's Used
2. 🟡 Installing Python & the Interpreter
3. 🟡 Running Scripts vs the REPL
4. 🟡 Comments, Indentation & Code Style

#### Variables & Data Types
5. 🟡 Variables & Assignment
6. 🟡 Numbers (int, float, complex)
7. 🟡 Strings & String Methods
8. 🟡 Booleans & None
9. 🟡 Type Conversion / Casting
10. 🔵 f-strings & String Formatting

#### Operators & Expressions
11. 🟡 Arithmetic & Assignment Operators
12. 🟡 Comparison Operators
13. 🟡 Logical Operators (and / or / not)
14. 🟡 Membership & Identity Operators (in, is)

#### Data Structures
15. 🟡 Lists & List Methods
16. 🟡 Tuples
17. 🟡 Dictionaries & Dict Methods
18. 🟡 Sets & Set Operations
19. 🔵 Slicing
20. 🔵 Comprehensions (list / dict / set)

#### Control Flow
21. 🟡 if / elif / else
22. 🟡 for Loops & range()
23. 🟡 while Loops
24. 🟡 break, continue, pass

#### Functions & Errors
25. 🟡 Defining Functions & Return Values
26. 🟡 Positional, Keyword & Default Arguments
27. 🔵 `*args` and `**kwargs`
28. 🟡 Lambda Functions
29. 🟡 Variable Scope (local / global / nonlocal)
30. 🔵 Exception Handling (try / except / finally)
31. 🔵 Raising Exceptions
32. 🔵 File I/O (open, read, write, `with`)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 2: Python Deep Dive

> OOP, decorators, typing, and async — everything Django leans on internally.

`Fast-track:` 🔵 14 core · 🟡 17 skim · ~22h fast-track

#### Modules & Environments
33. 🟡 Modules & Packages
34. 🟡 The Import System & `__name__`
35. 🟡 Virtual Environments (`venv`)
36. 🟡 `pip`, `requirements.txt` & Dependency Management
37. 🟡 The Python Standard Library Tour

#### Object-Oriented Programming
38. 🟡 Classes & Objects
39. 🔵 `__init__` & Instance Attributes
40. 🟡 Instance vs Class Attributes
41. 🟡 Instance, Class & Static Methods
42. 🟡 Inheritance
43. 🔵 `super()` & Method Overriding
44. 🟡 Multiple Inheritance & MRO
45. 🟡 Encapsulation & Name Mangling
46. 🔵 Properties (`@property`)
47. 🔵 Dunder / Magic Methods
48. 🟡 Abstract Base Classes (`abc`)

#### Functional & Advanced Python
49. 🟡 First-Class Functions & Closures
50. 🔵 Decorators
51. 🔵 Decorators with Arguments
52. 🔵 Iterators & the Iterator Protocol
53. 🔵 Generators & `yield`
54. 🔵 Context Managers (`with`, `__enter__`/`__exit__`)
55. 🔵 Generator Expressions & Lazy Evaluation

#### Typing & Modern Python
56. 🔵 Type Hints & Annotations
57. 🟡 The `typing` Module (Optional, Union, List, Dict)
58. 🟡 Dataclasses
59. 🔵 Enums
60. 🔵 Pattern Matching (`match` / `case`)

#### Concurrency
61. 🟡 Threads vs Processes vs Async (overview)
62. 🔵 `asyncio` & `async` / `await`
63. 🟡 Pythonic Idioms & PEP 8

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 3: JavaScript & TypeScript Foundation

> The frontend runs on TypeScript. Get fluent before Next.js.

`Fast-track:` 🟡 15 skim · ⚪ 18 skip · ~9h fast-track

#### Modern JavaScript
64. ⚪ JavaScript & the Browser / Node Runtime
65. ⚪ `let` / `const` / `var` & Scope
66. ⚪ Data Types & Coercion
67. ⚪ Template Literals
68. ⚪ Arrow Functions
69. ⚪ Destructuring (array & object)
70. ⚪ Spread & Rest Operators
71. ⚪ Default & Named Parameters
72. ⚪ Array Methods (`map` / `filter` / `reduce` / `find`)
73. ⚪ Object Methods & Optional Chaining

#### Asynchronous JavaScript
74. ⚪ Callbacks & the Event Loop
75. ⚪ Promises
76. ⚪ `async` / `await`
77. ⚪ Error Handling in Async Code
78. ⚪ The Fetch API

#### Modules & Tooling
79. ⚪ ES Modules (import / export)
80. ⚪ npm & `package.json`
81. ⚪ Bundlers Overview (Vite / Webpack / Turbopack)

#### TypeScript Fundamentals
82. 🟡 What is TypeScript & Why
83. 🟡 Setup & `tsconfig.json`
84. 🟡 Basic Types
85. 🟡 Arrays, Tuples & Enums
86. 🟡 Type Annotations vs Inference
87. 🟡 Functions & Return Types
88. 🟡 Objects & Optional Properties

#### TypeScript Type System
89. 🟡 Interfaces
90. 🟡 Type Aliases
91. 🟡 Union & Intersection Types
92. 🟡 Literal Types & Narrowing
93. 🟡 Generics
94. 🟡 Utility Types (Partial, Pick, Omit, Record)
95. 🟡 `unknown`, `never`, `any`
96. 🟡 Type Guards & Assertions

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 4: React Fundamentals

> Next.js is React. Nail the component model and hooks.

`Fast-track:` ⚪ 22 skip · ~3h fast-track

#### React Basics
97. ⚪ What is React & the Virtual DOM
98. ⚪ JSX
99. ⚪ Functional Components
100. ⚪ Props
101. ⚪ Rendering Lists & Keys
102. ⚪ Conditional Rendering
103. ⚪ Handling Events

#### State & Hooks
104. ⚪ `useState`
105. ⚪ `useEffect` & the Dependency Array
106. ⚪ `useRef`
107. ⚪ `useContext`
108. ⚪ `useReducer`
109. ⚪ `useMemo` & `useCallback`
110. ⚪ Custom Hooks

#### Component Patterns
111. ⚪ Component Composition
112. ⚪ Lifting State Up
113. ⚪ Controlled vs Uncontrolled Inputs
114. ⚪ Forms in React
115. ⚪ Prop Drilling & Context
116. ⚪ Error Boundaries
117. ⚪ React Performance & `memo`
118. ⚪ Thinking in React (component design)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 5: Development Environment Setup

> Tooling that will carry you the whole journey.

`Fast-track:` 🔵 4 core · 🟡 5 skim · ⚪ 5 skip · ~7h fast-track

#### Editor & Runtimes
119. ⚪ VS Code Setup & Essential Extensions
120. 🔵 Python via `pyenv`
121. 🟡 Node via `nvm`

#### Version Control
122. ⚪ Git Fundamentals
123. ⚪ GitHub Workflow (branches, PRs)
124. ⚪ `.gitignore` & Repo Hygiene

#### Backend Tooling
125. 🔵 PostgreSQL Installation
126. 🟡 Docker Installation & Basics
127. 🟡 Postman / REST Client

#### Quality Tooling
128. 🔵 Ruff, Black & isort (Python)
129. ⚪ ESLint & Prettier (JS / TS)
130. 🟡 Pre-commit Hooks
131. 🟡 EditorConfig
132. 🔵 Debugging (Python & Node)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 6: Django Basics

> First contact with the framework: projects, apps, URLs, views, templates.

`Fast-track:` 🔵 26 core · ~26h fast-track

#### Introduction
133. 🔵 What is Django
134. 🔵 Why Django (batteries-included)
135. 🔵 Django vs Flask vs FastAPI
136. 🔵 The Request / Response Cycle
137. 🔵 MVT Architecture (vs MVC)

#### Project Setup
138. 🔵 Installing Django
139. 🔵 Starting a Project (`startproject`)
140. 🔵 Project vs App (`startapp`)
141. 🔵 `manage.py` Commands
142. 🔵 `settings.py` Overview
143. 🔵 The Development Server (`runserver`)

#### URLs & Views
144. 🔵 URL Configuration (URLconf)
145. 🔵 Path Converters & URL Parameters
146. 🔵 Function-Based Views
147. 🔵 The `HttpRequest` Object
148. 🔵 `HttpResponse` & `JsonResponse`
149. 🔵 Redirects & Status Codes
150. 🔵 Including App URLs & Namespacing

#### Templates (server-rendered basics)
151. 🔵 Django Templates (DTL) Overview
152. 🔵 Template Variables & Tags
153. 🔵 Template Filters
154. 🔵 Template Inheritance (`extends` / `block`)
155. 🔵 Static Files

#### Class-Based Views
156. 🔵 Class-Based Views (CBV) Intro
157. 🔵 Generic Display Views (ListView, DetailView)
158. 🔵 Generic Editing Views (CreateView, UpdateView, DeleteView)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 7: Django Models & ORM

> The ORM is Django's crown jewel — and where your Eloquent instincts transfer.

`Fast-track:` 🔵 37 core · ~37h fast-track

#### Models Basics
159. 🔵 Introduction to the ORM
160. 🔵 Defining Models
161. 🔵 Field Types
162. 🔵 Field Options (null, blank, default, choices)
163. 🔵 Model `Meta` Options
164. 🔵 `__str__` & Model Representation

#### Migrations
165. 🔵 Migrations Overview
166. 🔵 `makemigrations` & `migrate`
167. 🔵 Migration Files Explained
168. 🔵 Data Migrations
169. 🔵 Reversing & Squashing Migrations

#### Querying the Database
170. 🔵 The Django Shell (`shell` / `shell_plus`)
171. 🔵 Creating Objects (`create` / `save`)
172. 🔵 Retrieving Objects (`all`, `get`, `filter`)
173. 🔵 Field Lookups
174. 🔵 QuerySet Laziness & Evaluation
175. 🔵 Chaining, `exclude` & `order_by`
176. 🔵 Slicing & Limiting QuerySets
177. 🔵 Updating Records
178. 🔵 Deleting Records
179. 🔵 `get_or_create` & `bulk_create`

#### Aggregation & Expressions
180. 🔵 Aggregation (Count, Sum, Avg)
181. 🔵 Annotation
182. 🔵 `F` Expressions
183. 🔵 `Q` Objects & Complex Lookups
184. 🔵 Conditional Expressions (`Case` / `When`)

#### Relationships
185. 🔵 `ForeignKey` (One-to-Many)
186. 🔵 `OneToOneField`
187. 🔵 `ManyToManyField`
188. 🔵 Related Managers & `related_name`
189. 🔵 Reverse Relations
190. 🔵 `select_related` (FK / 1-1 joins)
191. 🔵 `prefetch_related` (M2M / reverse)

#### Advanced ORM
192. 🔵 Custom Model Managers
193. 🔵 Custom QuerySets
194. 🔵 Model Methods & Properties
195. 🔵 Model Validation (`clean` / `full_clean`)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 8: Django Admin, Forms & Auth Basics

> The admin and the built-in auth system — free superpowers.

`Fast-track:` 🔵 22 core · ~22h fast-track

#### The Admin Site
196. 🔵 Django Admin Overview
197. 🔵 Registering Models
198. 🔵 Customizing `ModelAdmin` (list_display, search, filters)
199. 🔵 Admin Inlines
200. 🔵 Admin Actions
201. 🔵 Overriding Admin Templates & Branding

#### Forms
202. 🔵 Django Forms
203. 🔵 Form Fields & Widgets
204. 🔵 Form Validation (`clean` methods)
205. 🔵 `ModelForm`
206. 🔵 Rendering & Handling Forms in Views
207. 🔵 Formsets

#### Auth Basics
208. 🔵 The Authentication System Overview
209. 🔵 The Built-in User Model
210. 🔵 `login` / `logout` / `authenticate`
211. 🔵 Login Required (decorator & mixin)
212. 🔵 Custom User Model (`AbstractUser`)
213. 🔵 User Registration Flow
214. 🔵 Permissions & Groups
215. 🔵 The Messages Framework
216. 🔵 The Sessions Framework
217. 🔵 Password Management & Validators

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 9: Django REST Framework (DRF)

> Turn Django into an API backend for Next.js.

`Fast-track:` 🔵 32 core · 🟡 2 skim · ~33h fast-track

#### REST & DRF Setup
218. 🟡 What is a REST API
219. 🟡 REST Principles & Resource Design
220. 🔵 Installing & Configuring DRF
221. 🔵 The Browsable API

#### Serializers
222. 🔵 Serializers
223. 🔵 Serializer Fields
224. 🔵 `ModelSerializer`
225. 🔵 Serializer Validation (field & object level)
226. 🔵 Nested Serializers
227. 🔵 `SerializerMethodField`
228. 🔵 `read_only` / `write_only` Fields
229. 🔵 Handling Relationships in Serializers

#### Views
230. 🔵 Function-Based API Views (`@api_view`)
231. 🔵 `APIView` (Class-Based)
232. 🔵 Request & Response Objects
233. 🔵 Status Codes
234. 🔵 Mixins
235. 🔵 Generic API Views
236. 🔵 ViewSets
237. 🔵 Routers & URL Registration

#### API Features
238. 🔵 Pagination
239. 🔵 Filtering (`django-filter`)
240. 🔵 Search & Ordering
241. 🔵 Throttling / Rate Limiting
242. 🔵 Content Negotiation
243. 🔵 Versioning

#### Permissions & Docs
244. 🔵 DRF Authentication Classes
245. 🔵 DRF Permission Classes
246. 🔵 Custom Permissions
247. 🔵 Object-Level Permissions
248. 🔵 OpenAPI Schema (`drf-spectacular`)
249. 🔵 Swagger / Redoc UI
250. 🔵 Testing the API (browsable + Postman)
251. 🔵 Error Handling & Custom Exception Handler

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 10: Database Integration (PostgreSQL)

> Production databases, done right.

`Fast-track:` 🔵 13 core · 🟡 8 skim · ~17h fast-track

#### PostgreSQL Setup
252. 🟡 Why PostgreSQL
253. 🔵 Installing / Running Postgres (local)
254. 🔵 Running Postgres in Docker
255. 🔵 Connecting Django to Postgres
256. 🔵 Database Drivers (`psycopg`)
257. 🔵 Environment-based DB Config (`django-environ`)

#### Schema & Integrity
258. 🟡 Database Indexes
259. 🟡 Composite & Partial Indexes
260. 🟡 Unique Constraints
261. 🟡 Check Constraints
262. 🟡 Foreign Key Constraints & `on_delete`

#### Transactions & Performance
263. 🟡 Transactions (`atomic`)
264. 🔵 `select_for_update` & Locking
265. 🟡 The N+1 Problem & Detection
266. 🔵 Query Optimization & `explain()`
267. 🔵 Database Views & Raw SQL
268. 🔵 Connection Pooling

#### Postgres Power Features
269. 🔵 `JSONField`
270. 🔵 `ArrayField` & HStore
271. 🔵 Full-Text Search
272. 🔵 `pgvector` (intro for the AI phase)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 11: Next.js Basics

> The frontend framework: routing, layouts, rendering strategies.

`Fast-track:` 🔵 24 core · ~24h fast-track

#### Introduction
273. 🔵 What is Next.js
274. 🔵 Why Next.js
275. 🔵 Next.js vs React (CRA / Vite)
276. 🔵 App Router vs Pages Router
277. 🔵 Next.js Architecture & Rendering Overview

#### Setup & Structure
278. 🔵 Creating a Next.js App
279. 🔵 Project Structure & Conventions
280. 🔵 The `app/` Directory
281. 🔵 Running & Building the App

#### Routing
282. 🔵 File-based Routing
283. 🔵 Pages (`page.tsx`)
284. 🔵 Layouts (`layout.tsx`)
285. 🔵 Static Routes
286. 🔵 Dynamic Routes (`[id]`)
287. 🔵 Catch-all & Optional Routes
288. 🔵 Route Groups & Private Folders
289. 🔵 Linking & Navigation (`Link`, `useRouter`)
290. 🔵 `loading.tsx` & `error.tsx`
291. 🔵 `not-found` & Special Files

#### Rendering Strategies
292. 🔵 The Metadata API
293. 🔵 Static Site Generation (SSG)
294. 🔵 Server-Side Rendering (SSR)
295. 🔵 Incremental Static Regeneration (ISR)
296. 🔵 When to Use Each Rendering Method

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 12: Next.js Core Concepts

> Components, styling, forms, and the App Router essentials.

`Fast-track:` 🔵 24 core · 🟡 4 skim · ~26h fast-track

#### Components
297. 🟡 Server vs Client Components
298. 🔵 The `'use client'` Directive
299. 🟡 Component Composition Patterns
300. 🔵 Passing Server Data to Client Components
301. 🟡 Reusable Components

#### Styling
302. 🔵 Global CSS & CSS Modules
303. 🔵 Tailwind CSS Setup
304. 🔵 Tailwind Patterns & Responsive Design
305. 🔵 ShadCN UI
306. 🔵 Dark Mode / Theming

#### Forms
307. 🔵 Forms in Next.js
308. 🔵 React Hook Form
309. 🔵 Zod Validation
310. 🔵 RHF + Zod Integration
311. 🔵 Server Actions
312. 🔵 Handling Server Errors & Field Errors
313. 🔵 Input & Button Components

#### UI & Assets
314. 🔵 Building a Responsive Navbar / Header
315. 🔵 `next/image` (Image Optimization)
316. 🔵 `next/font` (Font Optimization)
317. 🔵 Icons & Asset Handling

#### API & Utilities
318. 🔵 Route Handlers (API Routes)
319. 🔵 Middleware (basics)
320. 🔵 Environment Variables in Next.js
321. 🟡 Custom Hooks
322. 🔵 Dynamic Imports & Lazy Loading
323. 🔵 Suspense Boundaries
324. 🔵 Cookies & Headers in Next.js

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 13: Connecting Frontend & Backend

> Wire Next.js to the DRF API end to end.

`Fast-track:` 🔵 17 core · 🟡 1 skim · ~17h fast-track

#### API Wiring
325. 🟡 CORS Setup (`django-cors-headers`)
326. 🔵 API Client Setup (axios instance)
327. 🔵 Making Requests to DRF
328. 🔵 Environment Config for API URLs
329. 🔵 Typing API Responses (shared types)

#### Data Fetching
330. 🔵 Server-side Fetching in Next.js
331. 🔵 Client-side Fetching with SWR
332. 🔵 Client-side Fetching with React Query
333. 🔵 Query Keys & Caching (React Query)
334. 🔵 Mutations & Invalidation
335. 🔵 Optimistic Updates

#### UX Concerns
336. 🔵 Handling Loading States
337. 🔵 Handling Errors & Retries
338. 🔵 Pagination & Infinite Scroll
339. 🔵 Debounced Search
340. 🔵 File Uploads (multipart) End-to-End
341. 🔵 API Contract Consistency (OpenAPI → types)
342. 🔵 Auth-aware Requests (interceptors)

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## 🧭 Level 2 — Builder

> Build real products. Auth, RBAC, admin, audit logging, caching, background jobs, payments, real-time, and business-system patterns. **Milestone:** build a **LaraBaseX-class** production starter — and beyond.

*Phases 14–21 · 212 topics · fast-track ≈ 188h (~16w)*

### Phase 14: Authentication & Authorization

> The deep dive: hashing, sessions, JWT, cookies, permissions, protected routes.

`Fast-track:` 🔵 27 core · 🟡 5 skim · ~29h fast-track

#### Fundamentals
343. 🟡 Authentication vs Authorization
344. 🟡 How Password Hashing Works
345. 🔵 Django Password Hashing & Hashers
346. 🟡 Auth Approaches: Session vs Token vs JWT

#### Session & Token Auth
347. 🔵 Session Authentication (DRF)
348. 🔵 Token Authentication (DRF)
349. 🟡 CSRF Protection

#### JWT Auth
350. 🟡 How JWT Works
351. 🔵 Installing & Configuring SimpleJWT
352. 🔵 Access & Refresh Tokens
353. 🔵 Obtaining & Refreshing Tokens
354. 🔵 Token Verification & Expiry
355. 🔵 Token Blacklisting & Logout
356. 🔵 Refresh Token Rotation

#### Auth Endpoints
357. 🔵 User Registration Endpoint
358. 🔵 Login Endpoint
359. 🔵 Current User (`/me`) Endpoint
360. 🔵 Serializing the User Safely
361. 🔵 Password Change Endpoint

#### Frontend Auth
362. 🔵 Storing Tokens Securely (HttpOnly cookies vs storage)
363. 🔵 Auth Context / Provider in Next.js
364. 🔵 Attaching Tokens to Requests
365. 🔵 Protected Routes with Middleware
366. 🔵 Handling Token Refresh on the Client
367. 🔵 Persisting & Restoring Sessions

#### Authorization
368. 🔵 DRF Permissions Recap
369. 🔵 Custom Permission Classes
370. 🔵 Object-Level Permissions
371. 🔵 Roles & Groups
372. 🔵 Role-Based Access Control (RBAC)
373. 🔵 Permission Mixins & Decorators
374. 🔵 Protecting Frontend UI by Role

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 15: Advanced Authentication

> OAuth, social login, 2FA, and managed auth providers.

`Fast-track:` 🔵 21 core · 🟡 3 skim · ~22h fast-track

#### OAuth
375. 🟡 OAuth 2.0 Flow
376. 🟡 OAuth 2.0 Scopes
377. 🔵 `django-allauth` Setup
378. 🔵 Google OAuth (Cloud Console Setup)
379. 🔵 Google OAuth (Backend Integration)
380. 🔵 GitHub OAuth (App Setup)
381. 🔵 GitHub OAuth (Backend Integration)
382. 🔵 Social Account Linking
383. 🔵 Handling OAuth Callbacks in Next.js

#### Managed Auth on the Frontend
384. 🔵 NextAuth.js (Auth.js) Overview
385. 🔵 NextAuth Providers & Config
386. 🔵 NextAuth with a Django Backend
387. 🔵 Clerk (Overview & Tradeoffs)
388. 🔵 Auth0 (Overview & Tradeoffs)

#### 2FA & Account Security
389. 🟡 2FA Flow Overview
390. 🔵 TOTP & Authenticator Apps (`pyotp`)
391. 🔵 Generating & Displaying QR Codes
392. 🔵 Enabling & Verifying 2FA
393. 🔵 Recovery Codes
394. 🔵 Email Verification Flow
395. 🔵 Password Reset Flow (email)
396. 🔵 Rate Limiting Auth Endpoints
397. 🔵 Account Lockout & Brute-Force Protection
398. 🔵 Security Headers & Best Practices

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 16: State Management & Frontend Best Practices

> Client vs server state, and the UX patterns every app needs.

`Fast-track:` 🔵 9 core · 🟡 14 skim · ~15h fast-track

#### Concepts
399. 🟡 Client State vs Server State
400. 🟡 Choosing a State Solution

#### Context & Zustand
401. 🟡 Context API Patterns
402. 🔵 Zustand Setup
403. 🔵 Zustand Stores & Actions
404. 🔵 Zustand Middleware (persist, devtools)
405. 🔵 Global Auth State with Zustand

#### Redux
406. 🔵 Redux Core Concepts
407. 🔵 Redux Toolkit Setup
408. 🔵 Slices & Reducers
409. 🔵 RTK Query

#### Data-Driven UI Patterns
410. 🟡 Pagination UI
411. 🟡 Searching UI
412. 🟡 Sorting UI
413. 🟡 Filtering UI
414. 🟡 Selecting Items / Bulk Actions
415. 🟡 Form Submission Patterns
416. 🟡 Toast / Notification System
417. 🟡 Error Boundaries & Fallbacks
418. 🟡 Loading Skeletons

#### Enterprise UI
419. 🟡 Advanced Data Tables (TanStack Table)
420. 🔵 Component Documentation (Storybook)
421. 🟡 Accessibility (a11y) & Keyboard UX

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 17: Advanced Django

> Signals, middleware, caching, custom commands, hardening.

`Fast-track:` 🔵 24 core · ~24h fast-track

#### Extensibility
422. 🔵 Django Signals
423. 🔵 When (Not) to Use Signals
424. 🔵 Custom Middleware
425. 🔵 Class-Based View Mixins
426. 🔵 Custom Model Fields
427. 🔵 Generic Relations (ContentTypes)
428. 🔵 Model Inheritance (abstract / multi-table / proxy)

#### Configuration & Ops
429. 🔵 Splitting Settings (base / dev / prod)
430. 🔵 `django-environ` & 12-Factor Config
431. 🔵 Logging Configuration
432. 🔵 Custom Management Commands
433. 🔵 Django Debug Toolbar
434. 🔵 Custom Exceptions & Error Handling

#### Caching
435. 🔵 The Caching Framework
436. 🔵 Cache Backends (Redis)
437. 🔵 Per-View Caching
438. 🔵 Template Fragment Caching
439. 🔵 Low-Level Cache API & Invalidation

#### Robustness & i18n
440. 🔵 File & Media Handling (storage backends)
441. 🔵 Internationalization (i18n) & Localization
442. 🔵 Time Zones
443. 🔵 Security Best Practices (settings hardening)
444. 🔵 Performance Profiling
445. 🔵 Feature Flags & Config Toggles

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 18: Advanced Next.js

> The full App Router power set.

`Fast-track:` 🔵 22 core · ~22h fast-track

#### App Router Deep Dive
446. 🔵 App Router Architecture
447. 🔵 Server Components Deep Dive
448. 🔵 Client Components Deep Dive
449. 🔵 Server Actions (Deep Dive)
450. 🔵 Streaming & Suspense
451. 🔵 Parallel Routes
452. 🔵 Intercepting Routes
453. 🔵 Route Handlers (Advanced)

#### Runtime & Caching
454. 🔵 Middleware (Advanced)
455. 🔵 The Edge Runtime
456. 🔵 The Caching Model (fetch cache, Data Cache)
457. 🔵 `revalidatePath` & `revalidateTag`
458. 🔵 Dynamic vs Static Rendering Control
459. 🔵 Automatic Code Splitting
460. 🔵 Dynamic Imports (Advanced)

#### SEO & Delivery
461. 🔵 SEO Optimization
462. 🔵 Metadata & OpenGraph
463. 🔵 Sitemap Generation
464. 🔵 `robots.txt`
465. 🔵 Internationalization (`next-intl`)
466. 🔵 Analytics & Web Vitals
467. 🔵 Error & Not-Found Handling (Advanced)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 19: Caching, Performance & Real-time

> Redis, WebSockets via Channels, and GraphQL.

`Fast-track:` 🔵 22 core · 🟡 4 skim · ~24h fast-track

#### Redis
468. 🟡 Redis Overview & Setup
469. 🟡 Caching with Redis (Django)
470. 🟡 Cache Invalidation Strategies
471. 🔵 Caching API Responses
472. 🔵 Redis Data Structures
473. 🔵 Sorted Sets & Rankings / Leaderboards
474. 🔵 Rate Limiting with Redis

#### Real-time (Channels)
475. 🔵 WebSockets Overview
476. 🔵 ASGI vs WSGI
477. 🔵 Django Channels Setup
478. 🔵 Consumers
479. 🔵 Routing & Scopes
480. 🔵 Channel Layers (Redis Backend)
481. 🔵 Groups & Broadcasting
482. 🔵 Real-time Chat Implementation
483. 🔵 Real-time Notifications
484. 🔵 Presence & Typing Indicators
485. 🔵 Scaling WebSockets

#### GraphQL
486. 🟡 GraphQL Overview
487. 🔵 GraphQL with Strawberry / Graphene
488. 🔵 Types & Schema
489. 🔵 Queries
490. 🔵 Mutations
491. 🔵 GraphQL on the Frontend (Apollo Client)

#### Search at Scale
492. 🔵 Advanced Search (Elasticsearch / Meilisearch / OpenSearch)
493. 🔵 Search Indexing & Sync Strategies

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 20: Async Tasks, Payments & Integrations

> Celery, email, Stripe, file storage.

`Fast-track:` 🔵 20 core · 🟡 4 skim · ~22h fast-track

#### Background Tasks
494. 🟡 Why Background Tasks
495. 🔵 Celery Overview & Architecture
496. 🔵 Celery + Redis / RabbitMQ Setup
497. 🔵 Writing & Calling Tasks
498. 🔵 Task Arguments & Return Handling
499. 🔵 Periodic Tasks (Celery Beat)
500. 🔵 Task Retries & Error Handling
501. 🔵 Task Chaining & Workflows (chains / groups)
502. 🔵 Monitoring with Flower

#### Email
503. 🟡 Sending Email (Django email)
504. 🟡 SMTP / Gmail Setup
505. 🔵 HTML Email Templates
506. 🔵 Async Email with Celery
507. 🔵 Transactional Email Providers (overview)

#### Payments (Stripe)
508. 🟡 Stripe Overview & Concepts
509. 🔵 Stripe Setup & API Keys
510. 🔵 Products, Prices & Customers
511. 🔵 Creating Checkout Sessions / PaymentIntents
512. 🔵 Stripe Webhooks
513. 🔵 Verifying Webhook Signatures
514. 🔵 Confirming Orders
515. 🔵 Stripe Frontend Integration (Elements)

#### Files & Media
516. 🔵 File Uploads in DRF
517. 🔵 Storing Files on S3 (`django-storages`)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 21: Building Business Systems (SaaS / ERP / CRM Patterns)

> Where CRUD ends and real products begin — the cross-cutting patterns behind SaaS, ERP, CRM, and ecommerce. This is what separates "can build an app" from "can build the system a company runs on."

`Fast-track:` 🔵 24 core · 🟡 13 skim · ~30h fast-track

#### Multi-Tenancy
518. 🟡 Multi-Tenancy Overview & Strategies
519. 🔵 Row-Level (Shared DB) Tenancy
520. 🔵 Schema-per-Tenant Tenancy
521. 🔵 Database-per-Tenant Tenancy
522. 🔵 Tenant Resolution (subdomain / header / path)
523. 🔵 Tenant-Scoped QuerySets & Managers
524. 🟡 `django-tenants` (overview & tradeoffs)

#### Advanced Authorization
525. 🟡 Row-Level Permissions
526. 🟡 Field-Level Permissions
527. 🟡 Organization / Team Scoping
528. 🟡 Ownership & Record Sharing Models
529. 🔵 `django-guardian` (object-level permissions)

#### Data Integrity & History
530. 🟡 Audit Trails / Activity Logs
531. 🔵 Model History & Versioning (`django-simple-history`)
532. 🟡 Soft Deletes
533. 🔵 Optimistic Locking & Concurrency Control

#### Domain Logic & Workflows
534. 🟡 Modeling Complex Domains (invoices, orders, ledgers)
535. 🔵 State Machines (`django-fsm` / viewflow)
536. 🔵 Approval Workflows
537. 🔵 The Business-Rules / Validation Layer
538. 🟡 Money, Currency & Decimal Precision

#### Reporting & Documents
539. 🟡 Dashboards & Aggregated Metrics
540. 🔵 PDF Generation (invoices, reports)
541. 🔵 Excel / CSV Export (`openpyxl`)
542. 🔵 Scheduled Reports (Celery)
543. 🔵 Data Exports & GDPR / Right-to-be-Forgotten

#### Billing & Subscriptions
544. 🔵 Subscription & Plan Modeling
545. 🔵 Stripe Billing (plans, proration, metered usage)
546. 🔵 Trials, Upgrades, Downgrades & Dunning
547. 🔵 Usage Metering & Quotas
548. 🔵 Invoicing & Receipts

#### Integrations & Extensibility
549. 🟡 Notifications System (multi-channel: in-app / email / SMS / push)
550. 🔵 Outgoing Webhooks (delivery, retries, signing)
551. 🔵 Public API & API Keys
552. 🔵 Rate Plans & Per-Tenant Quotas
553. 🔵 Data Import / ETL & Bulk Operations
554. 🟡 Feature Flags per Tenant

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## 🧭 Level 3 — Professional

> Ship and operate. Test across the pyramid and deploy to production with Docker, CI/CD, and monitoring. **Milestone:** take a real project all the way to a live server you can prove works — the job-ready bar.

*Phases 22–23 · 54 topics · fast-track ≈ 45h (~4w)*

### Phase 22: Testing

> Backend and frontend, unit through E2E.

`Fast-track:` 🔵 14 core · 🟡 10 skim · ~18h fast-track

#### Foundations
555. 🟡 Testing Philosophy & the Pyramid
556. 🔵 `pytest` & `pytest-django` Setup
557. 🔵 Django `TestCase` vs pytest
558. 🔵 Test Database & Isolation
559. 🔵 Fixtures
560. 🔵 `factory_boy` & Fake Data

#### Backend Tests
561. 🔵 Testing Models
562. 🔵 Testing Managers & QuerySets
563. 🔵 Testing Views
564. 🔵 Testing DRF APIs (`APIClient`)
565. 🔵 Testing Authentication & Permissions
566. 🔵 Mocking & `unittest.mock`
567. 🔵 Testing Celery Tasks
568. 🔵 Testing Signals
569. 🟡 Coverage Reports
570. 🔵 Parametrized Tests

#### Frontend Tests
571. 🟡 Frontend Testing Overview
572. 🟡 Jest Setup
573. 🟡 React Testing Library
574. 🟡 Testing Components
575. 🟡 Testing Hooks
576. 🟡 Mocking API Calls (MSW)

#### End-to-End
577. 🟡 E2E with Playwright
578. 🟡 E2E with Cypress

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 23: DevOps & Deployment

> Ship it: Docker, CI/CD, and production hosting.

`Fast-track:` 🔵 24 core · 🟡 6 skim · ~27h fast-track

#### Docker
579. 🟡 Docker Basics
580. 🔵 Dockerizing Django
581. 🔵 Gunicorn / Uvicorn
582. 🔵 Dockerizing Next.js
583. 🔵 `docker-compose` (multi-service)
584. 🔵 Multi-stage Builds & Image Optimization

#### Serving & Config
585. 🔵 Nginx as Reverse Proxy
586. 🔵 Serving Static Files (WhiteNoise / S3)
587. 🔵 Serving Media Files
588. 🟡 Environment Variables & Secrets Management
589. 🟡 Multiple Environments (dev / staging / prod)
590. 🔵 Production `settings.py` Hardening

#### Data & Release
591. 🔵 Database Migrations in Production
592. 🔵 `collectstatic` in Production
593. 🔵 Zero-downtime Deploys
594. 🔵 Backups & Restore
595. 🔵 Health Checks & Readiness Probes

#### CI/CD & Hosting
596. 🔵 Logging & Monitoring (Sentry)
597. 🟡 CI/CD with GitHub Actions
598. 🟡 Automated Testing in CI
599. 🔵 Deploying Django (Railway / Render / Fly.io)
600. 🔵 Deploying Django (AWS / DigitalOcean)
601. 🔵 Deploying Next.js (Vercel)
602. 🔵 Deploying Next.js (Self-host / Netlify)
603. 🟡 Custom Domains, HTTPS & Env Wiring

#### Security & Reliability Engineering
604. 🔵 Infrastructure as Code (Terraform)
605. 🔵 Load & Performance Testing (k6 / Locust)
606. 🔵 OWASP Top 10 & Threat Modeling
607. 🔵 Dependency & Secret Scanning (Dependabot, trufflehog)
608. 🔵 Container Image Scanning

<p align="right"><a href="#top">↑ Back to top</a></p>

---

## 🧭 Level 4 — Architect

> Design at scale. Distributed & plugin/modular architecture, system design, AI integration, and capstone projects. **Milestone:** design large systems and defend the tradeoffs — genuine expertise.

*Phases 24–26 · 75 topics · fast-track ≈ 48h (~4w)*

### Phase 24: Scaling & Architecture

> From monolith to distributed systems.

`Fast-track:` 🔵 25 core · 🟡 8 skim · ~29h fast-track

#### Architecture Decisions
609. 🟡 Monolith vs Microservices
610. 🟡 Modular Monolith First
611. 🟡 When to Split Services
612. 🔵 Service Boundaries & Contracts

#### Communication
613. 🔵 Synchronous Communication (REST)
614. 🔵 gRPC
615. 🔵 Message Queues (RabbitMQ / Kafka)
616. 🔵 Event-Driven Architecture
617. 🔵 Sagas & Distributed Transactions
618. 🔵 API Gateway

#### Data & Scale
619. 🔵 Database per Service
620. 🔵 Shared Libraries & Code Reuse
621. 🔵 Read Replicas & Sharding (overview)
622. 🔵 Caching Layers at Scale
623. 🟡 CDN & Static Assets

#### Infrastructure
624. 🟡 Load Balancing
625. 🟡 Horizontal Scaling & Statelessness
626. 🔵 Kubernetes Overview
627. 🔵 Deploying to Kubernetes
628. 🔵 Helm Charts
629. 🔵 Autoscaling
630. 🔵 Observability (metrics, tracing, logs)

#### Plugin & Modular Architecture
631. 🟡 Modular Monolith vs Microservices: the Honest Decision
632. 🟡 Plugin Architecture: When You Actually Need One (usually: not yet)
633. 🔵 Django Apps as Plugins (the built-in system)
634. 🔵 Modules as Installable Packages (namespace packages / editable installs)
635. 🔵 Modules as Git Submodules (the LeapDesk pattern)
636. 🔵 Module Registration & Auto-Discovery (`INSTALLED_APPS` / `AppConfig.ready`)
637. 🔵 Module Contributions (routes, migrations, permissions, admin)
638. 🔵 Inter-Module Communication (signals, service contracts, internal APIs)
639. 🔵 Enforcing Module Boundaries (no cross-module imports)
640. 🔵 Per-Module Frontend (Next.js route segments / plugin registry)
641. 🔵 From Modular Monolith to Microservices (the extraction path)

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 25: System Design & Expert Level

> Architecture patterns, distributed-systems theory, and AI integration.

`Fast-track:` 🔵 17 core · 🟡 5 skim · ~19h fast-track

#### Architecture Patterns
642. 🔵 Domain-Driven Design (DDD)
643. 🔵 Bounded Contexts & Ubiquitous Language
644. 🔵 Clean Architecture in Django
645. 🔵 Hexagonal (Ports & Adapters) Architecture
646. 🔵 The Repository Pattern
647. 🔵 The Service Layer Pattern
648. 🔵 CQRS
649. 🔵 Event Sourcing

#### Distributed Systems Theory
650. 🟡 Distributed Systems Basics
651. 🟡 Consistency & the CAP Theorem
652. 🟡 Idempotency & Retries
653. 🟡 Rate Limiting & Backpressure
654. 🔵 Designing for Failure (circuit breakers)
655. 🟡 The System Design Interview Framework

#### AI Integration
656. 🔵 LLM Integration (OpenAI / Anthropic)
657. 🔵 Prompt Design & Structured Output
658. 🔵 AI Summarizer
659. 🔵 AI Chat (RAG Basics)
660. 🔵 Embeddings & Vector Search (`pgvector`)
661. 🔵 AI Search
662. 🔵 AI-powered Documentation Generator
663. 🔵 Cost, Caching & Guardrails for LLM Apps

<p align="right"><a href="#top">↑ Back to top</a></p>

### Phase 26: Final Projects

> Build real, deployable applications — small to microservices-scale.

`Fast-track:` 🟢 20 build

#### Beginner
664. 🟢 Project: Todo CRUD App
665. 🟢 Project: Static Blog (Next.js SSG + Django API)
666. 🟢 Project: Full-stack Auth App

#### Intermediate
667. 🟢 Project: Blogging System (CMS-style)
668. 🟢 Project: Expense Tracker
669. 🟢 Project: Pomodoro / Habit Tracker
670. 🟢 Project: Job Board

#### Advanced
671. 🟢 Project: E-Commerce Store (Stripe)
672. 🟢 Project: Real-time Chat App (Channels)
673. 🟢 Project: Task Management Platform (Trello Clone)
674. 🟢 Project: Social Media App

#### Expert
675. 🟢 Project: SaaS Dashboard (multi-tenant)
676. 🟢 Project: Booking / Reservation System
677. 🟢 Project: Learning Management System (LMS)
678. 🟢 Project: Microservices Reservation System
679. 🟢 Project: AI-powered Documentation Generator
680. 🟢 Project: Real-time Collaborative Editor
681. 🟢 Project: CRM (contacts, pipeline, activities — multi-tenant)
682. 🟢 Project: ERP Module (inventory + invoicing + approvals)
683. 🟢 Project: Modular-Monolith Plugin App (LeapDesk-style, Django `app-modules`)

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
- Build real business systems: multi-tenancy, RBAC, audit trails, billing, reporting, integrations.
- Make architecture decisions (modular monolith vs microservices, plugin systems, DDD, CQRS) and defend the tradeoffs.
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
- **Business systems:** django-tenants, django-guardian, django-simple-history, django-fsm, WeasyPrint/ReportLab (PDF), openpyxl (Excel)
- **Search:** Elasticsearch / Meilisearch / OpenSearch
- **Quality:** pytest, pytest-django, factory_boy, Ruff, Black, isort, mypy
- **Ops & Reliability:** Docker, Gunicorn/Uvicorn, Nginx, WhiteNoise, django-storages, Sentry, Terraform, k6/Locust

### Frontend (Next.js)
- **Core:** Next.js (App Router), React, TypeScript
- **UI:** Tailwind CSS, ShadCN, Material UI, TanStack Table, Storybook
- **Data:** React Query (TanStack), SWR, axios
- **State:** Zustand, Redux Toolkit + RTK Query
- **Forms:** React Hook Form, Zod
- **Auth:** NextAuth (Auth.js), Clerk, Auth0
- **Testing:** Jest, React Testing Library, MSW, Playwright, Cypress

---

**Total: 683 topics across 26 phases.** Update [`progress-tracker.md`](progress-tracker.md) as you go. Happy building! 🚀
