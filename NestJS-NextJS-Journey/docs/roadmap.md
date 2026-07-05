# 🚀 Next.js + NestJS Full-Stack Roadmap

> A complete learning path from **Zero to 100** — covering everything from JavaScript basics to production-ready, scalable microservices architecture.

---

## 📌 Table of Contents

1. [Phase 1: Foundation (Beginner)](#phase-1-foundation-beginner)
2. [Phase 2: TypeScript Mastery](#phase-2-typescript-mastery)
3. [Phase 3: Development Environment Setup](#phase-3-development-environment-setup)
4. [Phase 4: NestJS Basics (Backend Start)](#phase-4-nestjs-basics-backend-start)
5. [Phase 5: NestJS Core Concepts](#phase-5-nestjs-core-concepts)
6. [Phase 6: Database Integration with NestJS](#phase-6-database-integration-with-nestjs)
7. [Phase 7: Next.js Basics (Frontend Start)](#phase-7-nextjs-basics-frontend-start)
8. [Phase 8: Next.js Core Concepts](#phase-8-nextjs-core-concepts)
9. [Phase 9: Connecting Frontend & Backend](#phase-9-connecting-frontend--backend)
10. [Phase 10: Authentication & Authorization](#phase-10-authentication--authorization)
11. [Phase 11: Advanced Authentication](#phase-11-advanced-authentication)
12. [Phase 12: State Management & Frontend Best Practices](#phase-12-state-management--frontend-best-practices)
13. [Phase 13: Advanced NestJS](#phase-13-advanced-nestjs)
14. [Phase 14: Advanced Next.js](#phase-14-advanced-nextjs)
15. [Phase 15: Caching, Performance & Real-time](#phase-15-caching-performance--real-time)
16. [Phase 16: Payments & Third-Party Integrations](#phase-16-payments--third-party-integrations)
17. [Phase 17: Testing](#phase-17-testing)
18. [Phase 18: DevOps & Deployment](#phase-18-devops--deployment)
19. [Phase 19: Microservices Architecture](#phase-19-microservices-architecture)
20. [Phase 20: System Design & Expert Level](#phase-20-system-design--expert-level)
21. [Phase 21: Final Projects](#phase-21-final-projects)

---

## Phase 1: Foundation (Beginner)

### JavaScript Essentials
- ES6+ Features
- Arrow Functions
- Promises
- Async / Await
- Modules (import / export)
- Array Methods
- Destructuring
- Spread & Rest Operators

### React Fundamentals
- Functional Components
- Props
- State
- Hooks (useState, useEffect)
- Component Composition

### Node.js Basics
- Node.js Runtime
- npm / yarn Package Management
- package.json
- Running Node Scripts

### Command Line Interface (CLI)
- File System Navigation
- Installing Packages
- Executing Terminal Commands

---

## Phase 2: TypeScript Mastery

### TypeScript Overview
- What is TypeScript
- Why TypeScript
- TypeScript vs JavaScript
- Environment Setup
- Executing TypeScript Code
- Catching Errors with TypeScript

### Types
- Basic Types
- More on Types
- Examples of Types
- Where to Use Types
- The Any Type
- Fixing the "Any" Type
- Void and Never

### Type Annotations & Inference
- Type Annotations
- Type Inference
- Annotations with Variables
- Object Literal Annotations
- Annotations Around Functions
- Understanding Inference
- Delayed Initialization
- When Inference Doesn't Work
- Inference Around Functions
- Annotations for Anonymous Functions
- Destructuring with Annotations
- Annotations Around Objects

### Arrays & Tuples
- Arrays in TypeScript
- Why Typed Arrays
- Multiple Types in Arrays
- When to Use Typed Arrays
- Tuples in TypeScript
- Tuples in Action
- Why Tuples

### Interfaces
- Interfaces Basics
- Long Type Annotations
- Fixing Annotations with Interfaces
- Syntax Around Interfaces
- Functions in Interfaces
- Code Reuse with Interfaces
- General Plan with Interfaces

### Classes
- Classes Basics
- Basic Inheritance
- Class Method Modifiers
- Fields in Classes
- Fields with Inheritance
- Where to Use Classes
- Generics
- Modules

### Advanced TypeScript Patterns
- Type Definition Files
- Using Type Definition Files
- Export Statements in TypeScript
- Hiding Functionality
- Private Modifiers
- Restricting Access with Interfaces
- Implicit Type Checks
- Optional Implements Clauses
- Updating Interface Definitions

---

## Phase 3: Development Environment Setup

- VS Code Setup
- Node.js Installation
- npm / yarn / pnpm
- Docker Installation
- Git & GitHub Basics
- Postman / REST Client (VSCode Extension)
- Bundling with Parcel

---

## Phase 4: NestJS Basics (Backend Start)

### Introduction
- What is NestJS
- Why NestJS
- NestJS vs Express
- NestJS Architecture Overview

### Project Setup
- Setup NestJS App
- Project Setup
- TypeScript Configuration
- Running the App
- File Naming Conventions
- Backend Module Structure

### First Steps
- Creating a Controller
- Starting Up a Nest App
- Routing Decorators
- App Setup
- Using the Nest CLI to Generate Files
- More on Generating Files
- Adding Routing Logic

---

## Phase 5: NestJS Core Concepts

### Controllers & Routing
- Controllers
- Routing
- Accessing Request Data with Decorators
- Decorators in Depth

### Services & Providers
- Services
- Repositories
- Implementing a Repository
- Implementing a Service
- Reading and Writing to a Storage File

### Modules
- Modules Basics
- Module Design
- Generating Modules, Controllers, and Services
- Setting Up DI Between Modules
- More on DI Between Modules
- Consuming Multiple Modules
- Modules Wrap-up

### Dependency Injection
- Understanding Inversion of Control
- Introduction to Dependency Injection
- Refactoring to Use Dependency Injection
- Advanced DI Patterns

### Validation & Pipes
- Using Pipes for Validation
- Adding Validation Rules
- Behind the Scenes of Validation
- How Type Info is Preserved
- Installing Validation Libraries
- DTOs (Data Transfer Objects)
- class-validator
- class-transformer
- Validating Query String Values
- Transforming Query String Data
- Setting Up Body Validation

### Exception Handling
- Reporting Errors with Exceptions
- A Few Notes on Exceptions
- Exception Filters

### Manual Testing
- Manual Testing of the Controller
- Postman Setup
- VSCode REST Client Extension

---

## Phase 6: Database Integration with NestJS

### Database Setup
- Install Database Dependencies
- Setup TypeORM
- Setup Config Module
- Install Postgres using Docker
- Database & Config Module
- Setting Up a Database Connection
- Viewing a DB's Contents
- Fix Volume Issue
- Fix Config Module Issue

### TypeORM Basics
- Persistent Data with Nest
- Creating an Entity
- Create Entity (Practical)
- Creating a Repository
- Creating an Entity and Repository
- Understanding TypeORM Decorators
- One Quick Note on Repositories
- Abstract Repository

### CRUD Operations
- A Few Extra Routes
- Creating and Saving a User
- More on Create vs Save
- Querying for Data
- Updating Data
- Removing Users
- Finding and Filtering Records
- Removing Records
- Updating Records
- Reservations CRUD

### TypeORM Relations
- Building Associations
- Types of Associations
- The ManyToOne and OneToMany Decorators
- More on Decorators
- Setting up the Association
- Relations Without Foreign Keys

### Query Building
- Creating a Query Builder
- Writing a Query to Produce the Estimate

### Prisma (Alternative ORM)
- Why Prisma
- Setup Prisma
- Prisma Schema
- Type-safe DB Interaction
- Prisma vs TypeORM

---

## Phase 7: Next.js Basics (Frontend Start)

### Introduction
- What is Next.js
- Why Next.js
- Next.js vs React
- Next.js Architecture

### Setup
- Setup Next.js App
- Install Packages
- Project Structure

### Routing
- File-based Routing
- Pages Directory
- Static Routes
- Dynamic Routes
- Layouts
- Navigation

### Rendering Methods
- Static Site Generation (SSG)
- Server-Side Rendering (SSR)
- Incremental Static Regeneration (ISR)
- When to Use Each Method

---

## Phase 8: Next.js Core Concepts

### Components
- Client-Side Component vs Server-Side
- Component Composition
- Forward Ref
- Reusable Components

### Forms & Validation
- React Hook Form
- Zod Validation
- Register Form Validation Schema using Zod
- React Hook Form and Zod Validation
- UseForm API Zod Validator
- Handle Server Error
- Fixing Validation Errors

### UI Building
- Input Component
- Button Component
- Material UI
- Tailwind CSS / ShadCN
- Building Responsive Navbar
- Header Component
- Template Setup

### Pages & Routing (Practical)
- Router Setup
- Multiple Routes
- Public and Private Routes
- Dynamic Routing
- Lazy Loading

### API Routes
- Built-in API Routes
- Serverless Functions
- Custom Hooks

---

## Phase 9: Connecting Frontend & Backend

- Enable CORS on Backend
- Make API Request to Backend Endpoint
- Fetching Data with fetch / axios
- Client-side Fetching with SWR
- Client-side Fetching with React Query
- Handling Loading States
- Handling Errors
- Common Files
- Shared Module

---

## Phase 10: Authentication & Authorization

### Password Security
- How Password Hashing Works
- Encrypt User Password with bcrypt
- Salting and Hashing the Password

### User Registration & Login
- Auth Module
- Create Module, Controller and Service
- Creating Register Route in Auth Controller
- Using Data Transfer Object create user dto
- Create User
- Implementing Signup Functionality
- Login User
- Handle User Sign In
- Compare User Password
- Signing in a User

### JWT Authentication
- How JSON Web Token Works
- JWT Auth Passport
- JWT Strategy
- Generate JWT Tokens
- Passport Setup
- Local Strategy

### Sessions & Cookies
- Setting up Sessions
- Changing and Fetching Session Data
- Setup Cookie Auth
- Return Cookie from Login Response
- Understand Cookie Flow
- Extract Token from Cookie
- HttpOnly Cookies
- Understand Include

### Auth Wrapper & Protected Routes
- Auth Wrapper
- Restrict Access to Private Profile Route
- Preventing Access with Authentication Guards
- Common Auth Guard
- Protected Routes
- Restrict Routes for Unauthorized Users
- Getting the Current User
- Signing Out a User
- Logout Handler

### Authorization
- Authorization vs Authentication
- Adding an Authorization Guard
- Multiple User Scopes
- Login with Scopes
- User Roles
- Different Types of Users
- Authenticated User Endpoint
- Profile Endpoint

### Decorators & Middleware for Auth
- Custom Param Decorators
- Why a Decorator and Interceptor
- Communicating from Interceptor to Decorator
- Connecting an Interceptor to Dependency Injection
- Globally Scoped Interceptors
- Assigning CurrentUser with a Middleware
- Middlewares, Guards, and Interceptors

### Serialization
- Excluding Response Properties
- Solution to Serialization
- How to Build Interceptors
- Serialization in the Interceptor
- Customizing the Interceptor's DTO
- Wrapping the Interceptor in a Decorator
- Controller-Wide Serialization
- Type Safety Around Serialize

---

## Phase 11: Advanced Authentication

### Social Login (OAuth)
- Understand OAuth Flow
- OAuth 2.0 Scopes
- Authentication Strategies in Next.js

### Google OAuth
- Create new Project on Google Cloud
- Set Config
- Create OAuth Client
- Create Google Client ID and Secret
- Copy Client ID and Secret
- Creating Google Strategy
- Google Login Route Handlers
- Inject Google Strategy
- Change Redirect URL to Dashboard
- Debug OAuth Flow

### GitHub OAuth
- Create Github OAuth App
- Generate Github Client ID and Client Secret
- Adding Github Route Handler
- Github Strategy
- Get User Profile from Github
- Refactor Callback URL in Github

### Social Login Integration
- Implement Social Login Method
- Adding Social Links
- Restart Docker Container

### Two-Factor Authentication (2FA)
- Understand 2FA Flow
- Install 2FA Dependencies
- Added TwoFA Secret and Enabled Column
- Create Generate Endpoint
- Create 2FA Service
- Verify Method
- Enable 2FA
- Update Auth Store in Frontend
- Display QR Code on Frontend
- Generate QR Code with API Request
- Test QR Code with Google Authenticator
- Refactor Login
- 2FA Login on Frontend
- Make Verify 2FA Request
- Parse Cookie Pending User
- Test 2FA Auth

### Next-Auth Alternatives
- NextAuth.js
- Clerk
- Auth0

---

## Phase 12: State Management & Frontend Best Practices

### State Management
- State Plan
- Setup Zustand
- Mutate the State
- Refactor Components with Store
- Redux Basics
- Using Redux
- Redux Toolkit
- Context API

### Frontend Architecture
- Client Wrapper Component
- Render Client Wrapper
- Refactor Navbar
- Make Navbar Responsive
- Restrict Access for Dashboard Page
- Access Token Check on Dashboard Page
- Test Dashboard Page
- Refactor LoginForm

### Frontend Features
- Pagination
- Searching
- Sorting
- Filtering
- Selecting Items
- Form Submissions
- Order Total Calculations

---

## Phase 13: Advanced NestJS

### Interceptors & Guards
- How to Build Interceptors
- Guards in Depth
- Custom Decorators

### Configuration
- Headaches with Config Management
- TypeORM and Nest Config
- Env-Specific Database Config
- Understanding Dotenv
- Applying Dotenv for Config
- Specifying the Runtime Environment

### Logging
- Validation & Logging
- Custom Loggers

### Event-Driven Architecture
- Event Emitters
- CQRS (Command Query Responsibility Segregation)

### API Documentation
- Swagger Setup
- OpenAPI Documentation
- Auto-generating Docs

### Rate Limiting & Security
- Rate Limiting
- Throttler Module
- Security Best Practices

---

## Phase 14: Advanced Next.js

### Next.js 13+ Features
- App Router
- Server Components
- Client Components
- Server Components vs Client Components

### Performance Optimization
- Edge Functions
- Middleware
- Image Optimization
- Font Optimization
- Automatic Code Splitting
- Lazy Loading
- React Suspense

### SEO
- SEO Optimization
- Metadata Control
- Sitemap Generation
- robots.txt

### Internationalization
- i18n Setup
- Multi-language Support

---

## Phase 15: Caching, Performance & Real-time

### Redis
- Redis Setup
- Caching with Redis
- Caching Products
- Searching Products
- Sorting Products
- Paginating Products
- Redis Sorted Sets
- Rankings
- Formatting Rankings
- Update Rankings

### WebSockets
- Real-time Communication
- WebSocket Gateways
- Chat Implementation

### GraphQL
- GraphQL Integration
- Apollo Driver
- Schema-first Approach
- Resolvers
- Queries & Mutations
- Apollo Federation

---

## Phase 16: Payments & Third-Party Integrations

### Stripe Integration
- Stripe Setup
- Latest Stripe API Version
- Reservations Payments - Part 1
- Reservations Payments - Part 2
- Configuration
- Confirming Orders
- Submitting Payment Forms
- Stripe Frontend Integration

### Email Notifications
- Sending Emails
- Emit Notification
- Email Notification
- Nodemailer Setup
- Gmail Integration
- Email Templates

### Other Integrations
- Stats Endpoints
- Revenue Tracking
- Links Generation
- Creating Links
- Getting Link Data

---

## Phase 17: Testing

### Testing Fundamentals
- Testing Overview
- Testing Setup
- Why Testing is Confusing
- Getting TypeScript to Help With Mocks
- Improving File Layout
- Speeding Up Tests

### Unit Testing
- Unit Testing Basics
- Ensuring Password Gets Hashed
- Testing Email in Use
- Changing Mock Implementations
- Testing the Signin Flow
- Checking Password Comparison
- More Intelligent Mocks
- Refactoring to Use Intelligent Mocks
- Unit Testing a Controller
- More Mock Implementations
- Testing the Signin Method

### End-to-End (E2E) Testing
- Getting Started with End to End Testing
- Creating an End to End Test
- App Setup Issues in Spec Files
- Applying a Globally Scoped Pipe
- Applying a Globally Scoped Middleware
- Solving Failures Around Repeat Test Runs
- Creating Separate Test and Dev Databases
- Running Migrations During E2E Tests
- A Followup Test

### Testing Specific Features
- Testing Report Creation
- Testing Report Approval
- Testing the Estimate Logic

### Frontend Testing
- Jest
- React Testing Library
- Playwright
- Cypress

---

## Phase 18: DevOps & Deployment

### Docker
- Docker Basics
- Dockerize NestJS
- Dockerize Next.js
- Production Dockerfile
- Docker Build Hanging Fix

### Environment Management
- Environment Variables
- Multiple Environments (dev, staging, prod)

### Migrations
- The Synchronize Flag
- Dangers of Synchronize
- Theory Behind Migrations
- Installing the TypeORM CLI
- Generating and Running Migrations
- Migration Updates for Production

### Production Deployment
- The Path to Production
- Providing the Cookie Key
- Production DB Config
- Heroku CLI Setup
- Heroku Specific Project Config
- Deploying to Heroku
- Deploying Next.js (Vercel)
- Deploying Next.js (Netlify)

### CI/CD
- GitHub Actions
- CloudBuild (Google Cloud)
- CodePipeline (AWS)
- Automated CI/CD Pipeline

---

## Phase 19: Microservices Architecture

### Microservices Fundamentals
- System Architecture
- Microservices Overview
- Course Prerequisites & Setup
- Monorepo Structure
- Common Shared Library
- Custom package.json per Microservice
- Custom Dockerfile per Microservice

### Communication Between Services
- TCP Transport Layer
- gRPC
- RabbitMQ
- Asynchronous Message Processing
- Message Retry Mechanism

### Database in Microservices
- Database per Service
- Postgres

### Cloud Deployment
- Google Cloud Engine Setup
- Productionize & Push Dockerfile
- Helm Chart
- Kubernetes Services & Env Variables
- Health Checks
- Google Kubernetes Engine
- Ingress Load Balancer
- AWS Branch
- Amazon Elastic Kubernetes Service (EKS)

### API Gateway
- GraphQL API Gateway
- Apollo Federation
- Exposing Microservices

### Real Microservice Project
- Reservations Service
- Users Service
- Payments Service (Stripe)
- Notifications Service (Email)
- Debugging Microservices

---

## Phase 20: System Design & Expert Level

### Architecture Patterns
- Domain-Driven Design (DDD)
- Hexagonal Architecture
- Clean Architecture
- Modular Monolith

### Advanced Concepts
- Contract Testing (Pact)
- Distributed Systems
- Message-Driven Architecture
- Event Sourcing

### Frontend Architecture
- Monorepo with TurboRepo
- Custom Hooks
- Reusable Component Libraries

### AI Integration
- LLM Integration (OpenAI)
- AI Summarizer
- AI Chat
- AI Search
- AI-powered Documentation Generator

---

## Phase 21: Final Projects

### Beginner Projects
- Todo CRUD App
- Static Blog (Next.js SSG)

### Intermediate Projects
- Full-stack Auth App (NestJS + Next.js)
- Blogging System (CMS-style)
- Expense Tracker
- Pomodoro Session Tracker

### Advanced Projects
- E-Commerce Store
- Real-time Chat App
- Task Management Platform (Trello Clone)
- Ambassador App (Admin + Ambassador + Checkout)

### Expert Projects
- SaaS Dashboard
- Booking System with Admin Portal
- Reservation Booking System with Microservices
- AI-powered Documentation Generator

---

## 🎯 Final Mastery Goals

- Build scalable, modular, production-ready full-stack apps
- Mentor others, contribute to OSS, write tech blogs
- Understand performance bottlenecks and advanced debugging
- Think about maintainability, architecture, and developer experience

---

## 📚 Key Tools & Libraries

### Backend (NestJS)
- TypeORM / Prisma
- class-validator, class-transformer
- Swagger, JWT, Passport
- Redis, Kafka, RabbitMQ
- Jest

### Frontend (Next.js)
- Tailwind CSS / ShadCN / Material UI
- React Query / SWR
- Zustand / Redux Toolkit
- React Hook Form + Zod
- NextAuth / Clerk / Auth0
- Jest / Playwright / Cypress

---

**Happy Coding! 🚀**
