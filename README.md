# Awesome SaaS Stack

The tools behind 6,683 live SaaS and AI products, ranked by how many of them actually use each one — not by who wrote the loudest blog post.

Every count comes from a source you can open: the maker's own words, the product's website, DNS records, subprocessor lists, customer stories and job postings (18,611 sourced usages in all). Follow a tool's link to see which products use it and why. Generated from [How Makers Build](https://howmakersbuild.com), refreshed weekly — last 2026-10-20.

<a href="https://howmakersbuild.com"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/overview-dark.svg"><img alt="The most common pick per decision. Frontend Framework: Next.js; Backend Framework: Laravel; Database: Supabase; Database Access &amp; ORMs: Prisma; Authentication: Clerk; File Storage: Cloudflare R2; Background Jobs &amp; Cron: Temporal; Transactional Email: SendGrid; Payments: Stripe; LLM API: OpenAI API; AI SDK &amp; Agent Framework: LangChain; Vector Database: Pinecone; LLM Observability &amp; Evals: Langfuse; Hosting: Vercel; Image &amp; Video Hosting: Cloudinary; Error Monitoring: Sentry; Web Analytics: Google Analytics; Product Analytics: PostHog; Newsletter: Kit; Lifecycle Email: Loops; AI Coding Assistants: Claude Code; AI App Builders: Lovable" src="charts/overview-light.svg" width="800"></picture></a>

## Contents

- [Foundation](#foundation)
  - [Frontend Framework](#frontend-framework)
  - [Backend Framework](#backend-framework)
  - [Database](#database)
  - [Database Access & ORMs](#database-access--orms)
  - [Authentication](#authentication)
  - [File Storage](#file-storage)
  - [Background Jobs & Cron](#background-jobs--cron)
  - [Transactional Email](#transactional-email)
- [Money](#money)
  - [Payments](#payments)
- [AI in the product](#ai-in-the-product)
  - [LLM API](#llm-api)
  - [AI SDK & Agent Framework](#ai-sdk--agent-framework)
  - [Vector Database](#vector-database)
  - [LLM Observability & Evals](#llm-observability--evals)
- [Shipping](#shipping)
  - [Hosting](#hosting)
  - [Image & Video Hosting](#image--video-hosting)
  - [Error Monitoring](#error-monitoring)
- [Growth](#growth)
  - [Web Analytics](#web-analytics)
  - [Product Analytics](#product-analytics)
  - [Newsletter](#newsletter)
  - [Lifecycle Email](#lifecycle-email)
- [Building with AI](#building-with-ai)
  - [AI Coding Assistants](#ai-coding-assistants)
  - [AI App Builders](#ai-app-builders)
- [How the counts work](#how-the-counts-work)
- [Contributing](#contributing)

## Foundation

The parts every web product is built on.

### Frontend Framework

Pick the full-stack framework your web app lives in — routing, data loading, server code and rendering — on top of a UI library. What 2,279 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/frontend-framework).

<a href="https://howmakersbuild.com/tasks/frontend-framework"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/frontend-framework-dark.svg"><img alt="Frontend Framework: Next.js 76%, Astro 12%, React 10%, Vue.js 3%, Svelte 2%, Nuxt 1%" src="charts/frontend-framework-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Next.js](https://howmakersbuild.com/tools/nextjs) · open source | 1,731 (76%) | React apps that want server rendering, API routes and the largest set of examples, templates and SaaS starters. | [vs Astro](https://howmakersbuild.com/compare/astro-vs-nextjs) |
| [Astro](https://howmakersbuild.com/tools/astro) · open source | 270 (12%) | Marketing sites, docs and blogs that ship minimal JavaScript, with interactive islands from any UI library. | [vs Next.js](https://howmakersbuild.com/compare/astro-vs-nextjs) |
| [React](https://howmakersbuild.com/tools/react) · open source | 233 (10%) | Single-page apps built from React components, with the largest ecosystem of component libraries, examples and AI-generated code. | [vs Angular](https://howmakersbuild.com/compare/angular-vs-react) |
| [Vue.js](https://howmakersbuild.com/tools/vue) · open source | 66 (3%) | Single-page apps with approachable single-file components and official router and state libraries from the same team. | [vs React](https://howmakersbuild.com/compare/react-vs-vue) |
| [Svelte](https://howmakersbuild.com/tools/svelte) · open source | 41 (2%) | Interactive apps and widgets with little boilerplate, compiled to small client bundles. | [vs SolidJS](https://howmakersbuild.com/compare/solid-vs-svelte) |
| [Nuxt](https://howmakersbuild.com/tools/nuxt) · open source | 28 (1%) | Vue apps, with a large module ecosystem for auth, content, images and SEO. | [vs Next.js](https://howmakersbuild.com/compare/nextjs-vs-nuxt) |
| [Angular](https://howmakersbuild.com/tools/angular) · open source | 23 (1%) | Larger TypeScript apps that want routing, forms, an HTTP client, dependency injection and a CLI from one framework, with signals for reactivity. | [vs React](https://howmakersbuild.com/compare/angular-vs-react) |
| [SolidJS](https://howmakersbuild.com/tools/solid) · open source | 5 (<1%) | Fast, small interactive apps written in JSX, where signals update only the parts of the page that change. | [vs Svelte](https://howmakersbuild.com/compare/solid-vs-svelte) |
| [SvelteKit](https://howmakersbuild.com/tools/sveltekit) · open source | 2 (<1%) | Apps written in Svelte, with less boilerplate and small client bundles. |  |
| [htmx](https://howmakersbuild.com/tools/htmx) · open source | 2 (<1%) | Server-rendered apps where links, forms and buttons fetch HTML fragments from the backend and swap them into the page, with no client-side framework. |  |

</details>

### Backend Framework

Pick the framework that serves your API or server-rendered app, when your frontend framework's own server routes aren't enough. What 192 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/backend-framework).

<a href="https://howmakersbuild.com/tasks/backend-framework"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/backend-framework-dark.svg"><img alt="Backend Framework: Laravel 33%, FastAPI 16%, Django 16%, Ruby on Rails 14%, NestJS 11%, Hono 3%" src="charts/backend-framework-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Laravel](https://howmakersbuild.com/tools/laravel) · open source | 64 (33%) | PHP apps with ORM, queues, auth scaffolding and an optional paid ecosystem for hosting and admin panels. | [vs AdonisJS](https://howmakersbuild.com/compare/adonisjs-vs-laravel) |
| [FastAPI](https://howmakersbuild.com/tools/fastapi) · open source | 30 (16%) | Python APIs with request validation and interactive docs generated from type hints. | [vs Flask](https://howmakersbuild.com/compare/fastapi-vs-flask) |
| [Django](https://howmakersbuild.com/tools/django) · open source | 30 (16%) | Python apps that want an ORM, migrations, auth and an admin panel on day one. | [vs Flask](https://howmakersbuild.com/compare/django-vs-flask) |
| [Ruby on Rails](https://howmakersbuild.com/tools/rails) · open source | 26 (14%) | Full-stack Ruby apps where one developer builds models, views, jobs and emails with strong conventions. | [vs Laravel](https://howmakersbuild.com/compare/laravel-vs-rails) |
| [NestJS](https://howmakersbuild.com/tools/nestjs) · open source | 21 (11%) | Larger TypeScript backends organized into modules, with dependency injection and decorators. | [vs Hono](https://howmakersbuild.com/compare/hono-vs-nestjs) |
| [Hono](https://howmakersbuild.com/tools/hono) · open source | 5 (3%) | Small TypeScript APIs that run on Node, Bun, Deno or edge platforms like Cloudflare Workers. | [vs Express](https://howmakersbuild.com/compare/express-vs-hono) |
| [Wasp](https://howmakersbuild.com/tools/wasp) · open source | 5 (3%) | Full-stack React and Node.js apps where a config file declares auth, routes, jobs and emails and Wasp generates the wiring. |  |
| [Flask](https://howmakersbuild.com/tools/flask) · open source | 4 (2%) | Small Python web apps and APIs where you add only the extensions you need. | [vs Django](https://howmakersbuild.com/compare/django-vs-flask) |
| [Express](https://howmakersbuild.com/tools/express) · open source | 3 (2%) | Node.js servers where you want a widely documented default and a huge middleware catalog. | [vs Hono](https://howmakersbuild.com/compare/express-vs-hono) |
| [AdonisJS](https://howmakersbuild.com/tools/adonisjs) · open source | 3 (2%) | TypeScript apps that want Rails- or Laravel-style conventions — ORM, migrations, auth, validation and mail — in Node.js. | [vs Laravel](https://howmakersbuild.com/compare/adonisjs-vs-laravel) |

</details>

### Database

Store your app's data somewhere reliable, and talk to it from code. What 1,243 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/database).

<a href="https://howmakersbuild.com/tasks/database"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/database-dark.svg"><img alt="Database: Supabase 45%, Firebase 15%, MongoDB 10%, PostgreSQL 8%, Neon 8%, Convex 4%" src="charts/database-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Supabase](https://howmakersbuild.com/tools/supabase) · open source | 560 (45%) | Postgres plus auth, storage and realtime in one project. | [vs Firebase](https://howmakersbuild.com/compare/firebase-vs-supabase) · [pricing](https://howmakersbuild.com/tools/supabase/pricing) |
| [Firebase](https://howmakersbuild.com/tools/firebase) | 183 (15%) | Mobile apps that need offline sync and client-side SDKs. | [vs Supabase](https://howmakersbuild.com/compare/firebase-vs-supabase) · [pricing](https://howmakersbuild.com/tools/firebase/pricing) |
| [MongoDB](https://howmakersbuild.com/tools/mongodb) | 127 (10%) | Document-shaped data and teams already fluent in Mongo. | [vs PostgreSQL](https://howmakersbuild.com/compare/mongodb-vs-postgresql) · [pricing](https://howmakersbuild.com/tools/mongodb/pricing) |
| [PostgreSQL](https://howmakersbuild.com/tools/postgresql) · open source | 98 (8%) | The engine behind most of the hosted options above, run on your own server or container for full control and a flat cost. | [vs MongoDB](https://howmakersbuild.com/compare/mongodb-vs-postgresql) |
| [Neon](https://howmakersbuild.com/tools/neon) · open source | 95 (8%) | Serverless Postgres that scales to zero, with a branch per preview deploy. | [vs Supabase](https://howmakersbuild.com/compare/neon-vs-supabase) · [pricing](https://howmakersbuild.com/tools/neon/pricing) |
| [Convex](https://howmakersbuild.com/tools/convex) · open source | 50 (4%) | Realtime, collaborative apps written entirely in TypeScript. | [vs Supabase](https://howmakersbuild.com/compare/convex-vs-supabase) · [pricing](https://howmakersbuild.com/tools/convex/pricing) |
| [ClickHouse](https://howmakersbuild.com/tools/clickhouse) · open source | 47 (4%) | Fast aggregate queries over billions of rows of events, logs or metrics, self-hosted or on ClickHouse Cloud. | [vs DuckDB](https://howmakersbuild.com/compare/clickhouse-vs-duckdb) |
| [PlanetScale](https://howmakersbuild.com/tools/planetscale) | 29 (2%) | Apps that expect heavy scale and want zero-downtime schema changes. | [vs Neon](https://howmakersbuild.com/compare/neon-vs-planetscale) · [pricing](https://howmakersbuild.com/tools/planetscale/pricing) |
| [Tinybird](https://howmakersbuild.com/tools/tinybird) | 29 (2%) | Managed ClickHouse that turns SQL over event streams into fast API endpoints for dashboards and usage analytics in your product. | [vs ClickHouse](https://howmakersbuild.com/compare/clickhouse-vs-tinybird) · [pricing](https://howmakersbuild.com/tools/tinybird/pricing) |
| [Snowflake](https://howmakersbuild.com/tools/snowflake) | 24 (2%) | A managed data warehouse that joins data from your app, billing and other sources, on the AWS, Azure or Google Cloud region you choose. |  |

</details>

### Database Access & ORMs

How your code reads and writes the database — typed queries, schema changes and migrations — once you've picked where the data lives. What 49 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/orm).

<a href="https://howmakersbuild.com/tasks/orm"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/orm-dark.svg"><img alt="Database Access &amp; ORMs: Prisma 76%, Drizzle ORM 22%, SQLAlchemy 2%" src="charts/orm-light.svg" width="800"></picture></a>

<details><summary>All 3 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Prisma](https://howmakersbuild.com/tools/prisma) · open source | 37 (76%) | A schema-first ORM with generated types and migrations. | [vs Drizzle ORM](https://howmakersbuild.com/compare/drizzle-vs-prisma) |
| [Drizzle ORM](https://howmakersbuild.com/tools/drizzle) · open source | 11 (22%) | A thin, SQL-like TypeScript ORM that runs well on serverless and edge runtimes. | [vs Prisma](https://howmakersbuild.com/compare/drizzle-vs-prisma) |
| [SQLAlchemy](https://howmakersbuild.com/tools/sqlalchemy) · open source | 1 (2%) | Python backends (FastAPI, Flask, scripts) that want an ORM or a SQL toolkit over any relational database. |  |

</details>

### Authentication

Let users sign up, sign in and stay signed in — without building password storage, sessions and OAuth yourself. What 420 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/authentication).

<a href="https://howmakersbuild.com/tasks/authentication"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/authentication-dark.svg"><img alt="Authentication: Clerk 80%, Auth0 5%, WorkOS 5%, Supabase 3%, Better Auth 2%, Kinde 2%" src="charts/authentication-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Clerk](https://howmakersbuild.com/tools/clerk) | 334 (80%) | Dropping prebuilt sign-in, profile and organization UI into a React or Next.js app. | [vs Auth0](https://howmakersbuild.com/compare/auth0-vs-clerk) · [pricing](https://howmakersbuild.com/tools/clerk/pricing) |
| [Auth0](https://howmakersbuild.com/tools/auth0) | 21 (5%) | Complex identity needs and enterprise compliance. | [vs WorkOS](https://howmakersbuild.com/compare/auth0-vs-workos) · [pricing](https://howmakersbuild.com/tools/auth0/pricing) |
| [WorkOS](https://howmakersbuild.com/tools/workos) | 20 (5%) | B2B SaaS that will need enterprise SSO and directory sync. | [vs Auth0](https://howmakersbuild.com/compare/auth0-vs-workos) · [pricing](https://howmakersbuild.com/tools/workos/pricing) |
| [Supabase](https://howmakersbuild.com/tools/supabase) · open source | 13 (3%) | Apps already on Supabase — auth is part of the same project as the database. | [vs Clerk](https://howmakersbuild.com/compare/clerk-vs-supabase) · [pricing](https://howmakersbuild.com/tools/supabase/pricing) |
| [Better Auth](https://howmakersbuild.com/tools/better-auth) · open source | 7 (2%) | TypeScript apps that want users and sessions in their own database, at no cost. | [vs Auth.js](https://howmakersbuild.com/compare/authjs-vs-better-auth) · [pricing](https://howmakersbuild.com/tools/better-auth/pricing) |
| [Kinde](https://howmakersbuild.com/tools/kinde) | 7 (2%) | Auth that also covers feature flags and organizations in one place. | [pricing](https://howmakersbuild.com/tools/kinde/pricing) |
| [PropelAuth](https://howmakersbuild.com/tools/propelauth) | 5 (1%) | B2B products where every customer is an organization with members, roles, invites and SAML. | [pricing](https://howmakersbuild.com/tools/propelauth/pricing) |
| [Stytch](https://howmakersbuild.com/tools/stytch) | 5 (1%) | Passwordless sign-in (magic links, one-time codes, passkeys) and B2B SSO through APIs, free up to 10,000 monthly active users. |  |
| [Firebase](https://howmakersbuild.com/tools/firebase) | 4 (1%) | Mobile and client-heavy apps already using Firebase. | [pricing](https://howmakersbuild.com/tools/firebase/pricing) |
| [Hexclave (Stack Auth)](https://howmakersbuild.com/tools/stack-auth) · open source | 2 (<1%) | A Clerk-style developer experience you can also self-host. | [pricing](https://howmakersbuild.com/tools/stack-auth/pricing) |

</details>

### File Storage

Store the files your users upload — avatars, attachments, exports — and serve them back without filling up your app server. What 10 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/file-storage).

<a href="https://howmakersbuild.com/tasks/file-storage"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/file-storage-dark.svg"><img alt="File Storage: Cloudflare R2 40%, Supabase 30%, Uppy 20%, MinIO 10%" src="charts/file-storage-light.svg" width="800"></picture></a>

<details><summary>All 4 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Cloudflare R2](https://howmakersbuild.com/tools/cloudflare-r2) | 4 (40%) | Files that get downloaded often — the S3 API without egress fees. | [vs Supabase](https://howmakersbuild.com/compare/cloudflare-r2-vs-supabase) · [pricing](https://howmakersbuild.com/tools/cloudflare-r2/pricing) |
| [Supabase](https://howmakersbuild.com/tools/supabase) · open source | 3 (30%) | Apps already on Supabase — storage access follows the same row-level security policies as your data. | [vs Cloudflare R2](https://howmakersbuild.com/compare/cloudflare-r2-vs-supabase) · [pricing](https://howmakersbuild.com/tools/supabase/pricing) |
| [Uppy](https://howmakersbuild.com/tools/uppy) · open source | 2 (20%) | An open-source upload widget with drag-and-drop, progress, resumable uploads and direct-to-S3, in front of whatever bucket you choose. |  |
| [MinIO](https://howmakersbuild.com/tools/minio) · open source | 1 (10%) | The long-standing S3-compatible server for self-hosting, with many existing guides, Docker setups and client SDKs. |  |

</details>

### Background Jobs & Cron

Run work outside the request — sending batches, processing uploads, calling slow AI APIs, nightly cleanups — with retries when it fails. What 80 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/background-jobs).

<a href="https://howmakersbuild.com/tasks/background-jobs"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/background-jobs-dark.svg"><img alt="Background Jobs &amp; Cron: Temporal 44%, Trigger.dev 29%, Inngest 20%, RabbitMQ 4%, Dagster 4%, Upstash 3%" src="charts/background-jobs-light.svg" width="800"></picture></a>

<details><summary>All 8 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Temporal](https://howmakersbuild.com/tools/temporal) · open source | 35 (44%) | Long-running, multi-step workflows — payments, onboarding, AI agent loops — whose state must survive crashes and deploys, in Go, Java, Python, TypeScript and more. | [vs Inngest](https://howmakersbuild.com/compare/inngest-vs-temporal) · [pricing](https://howmakersbuild.com/tools/temporal/pricing) |
| [Trigger.dev](https://howmakersbuild.com/tools/trigger-dev) · open source | 23 (29%) | Long-running TypeScript tasks — AI calls, media processing — that would time out in a serverless function. | [vs Inngest](https://howmakersbuild.com/compare/inngest-vs-trigger-dev) · [pricing](https://howmakersbuild.com/tools/trigger-dev/pricing) |
| [Inngest](https://howmakersbuild.com/tools/inngest) · open source | 16 (20%) | Event-driven, multi-step workflows where each step retries on its own and your code stays in your existing app. | [vs Temporal](https://howmakersbuild.com/compare/inngest-vs-temporal) · [pricing](https://howmakersbuild.com/tools/inngest/pricing) |
| [RabbitMQ](https://howmakersbuild.com/tools/rabbitmq) · open source | 3 (4%) | A dedicated message broker for queues and pub/sub between services, in any language, or as the broker behind Celery. |  |
| [Dagster](https://howmakersbuild.com/tools/dagster) · open source | 3 (4%) | Data pipelines described by the tables, files and models they produce, with lineage between them, schedules, sensors and native dbt integration, in Python. |  |
| [Upstash](https://howmakersbuild.com/tools/upstash) | 2 (3%) | Simple scheduled calls and delayed HTTP jobs on serverless or edge hosting, via QStash. | [pricing](https://howmakersbuild.com/tools/upstash/pricing) |
| [BullMQ](https://howmakersbuild.com/tools/bullmq) · open source | 1 (1%) | Node apps on a long-running server that already have Redis — free and fully in your control. |  |
| [Prefect](https://howmakersbuild.com/tools/prefect) · open source | 1 (1%) | Turning existing Python scripts into scheduled, retried, monitored workflows with decorators, using ordinary Python control flow instead of a fixed DAG. |  |

</details>

### Transactional Email

Send the emails your app triggers — sign-up confirmations, password resets, receipts — and make sure they arrive. What 2,461 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/transactional-email).

<a href="https://howmakersbuild.com/tasks/transactional-email"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/transactional-email-dark.svg"><img alt="Transactional Email: SendGrid 46%, Resend 44%, Postmark 26%, Mailgun 2%, Amazon SES &lt;1%, Plunk &lt;1%" src="charts/transactional-email-light.svg" width="800"></picture></a>

<details><summary>All 7 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [SendGrid](https://howmakersbuild.com/tools/sendgrid) | 1,143 (46%) | One vendor for both jobs at large scale. | [vs Amazon SES](https://howmakersbuild.com/compare/amazon-ses-vs-sendgrid) · [pricing](https://howmakersbuild.com/tools/sendgrid/pricing) |
| [Resend](https://howmakersbuild.com/tools/resend) | 1,081 (44%) | A modern developer API with email templates written as React components. | [vs Postmark](https://howmakersbuild.com/compare/postmark-vs-resend) · [pricing](https://howmakersbuild.com/tools/resend/pricing) |
| [Postmark](https://howmakersbuild.com/tools/postmark) | 652 (26%) | Deliverability when the mail has to arrive within seconds. | [vs Resend](https://howmakersbuild.com/compare/postmark-vs-resend) · [pricing](https://howmakersbuild.com/tools/postmark/pricing) |
| [Mailgun](https://howmakersbuild.com/tools/mailgun) | 46 (2%) | High volume and inbound email parsing and routing. | [vs SendGrid](https://howmakersbuild.com/compare/mailgun-vs-sendgrid) · [pricing](https://howmakersbuild.com/tools/mailgun/pricing) |
| [Amazon SES](https://howmakersbuild.com/tools/amazon-ses) | 5 (<1%) | Sending at high volume, where cost per email matters more than tooling. | [vs SendGrid](https://howmakersbuild.com/compare/amazon-ses-vs-sendgrid) · [pricing](https://howmakersbuild.com/tools/amazon-ses/pricing) |
| [Plunk](https://howmakersbuild.com/tools/plunk) · open source | 5 (<1%) | Transactional emails, event-triggered sequences and newsletters in one open-source tool, billed per email with no monthly fee. |  |
| [Loops](https://howmakersbuild.com/tools/loops) | 1 (<1%) | SaaS onboarding sequences triggered by product events, with transactional sending included. | [pricing](https://howmakersbuild.com/tools/loops/pricing) |

</details>

## Money

Getting paid — per seat, per month, or per token, with metering on top when you charge by usage.

### Payments

Charge customers — one-off or subscription — and stay on the right side of sales tax. What 1,216 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/payments).

<a href="https://howmakersbuild.com/tasks/payments"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/payments-dark.svg"><img alt="Payments: Stripe 76%, PayPal 8%, Paddle 7%, Lemon Squeezy 7%, Polar 4%, Dodo Payments 2%" src="charts/payments-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Stripe](https://howmakersbuild.com/tools/stripe) | 926 (76%) | Full control over checkout and billing, lower fees than a merchant of record, and the widest integration ecosystem. | [vs Lemon Squeezy](https://howmakersbuild.com/compare/lemon-squeezy-vs-stripe) · [pricing](https://howmakersbuild.com/tools/stripe/pricing) |
| [PayPal](https://howmakersbuild.com/tools/paypal) | 94 (8%) | Adding PayPal and Venmo as a checkout option for buyers who won't type in a card. | [vs Stripe](https://howmakersbuild.com/compare/paypal-vs-stripe) · [pricing](https://howmakersbuild.com/tools/paypal/pricing) |
| [Paddle](https://howmakersbuild.com/tools/paddle) | 86 (7%) | Established SaaS businesses that want a mature MoR. | [vs Lemon Squeezy](https://howmakersbuild.com/compare/lemon-squeezy-vs-paddle) · [pricing](https://howmakersbuild.com/tools/paddle/pricing) |
| [Lemon Squeezy](https://howmakersbuild.com/tools/lemon-squeezy) | 83 (7%) | Selling software and digital downloads with minimal setup. | [vs Stripe](https://howmakersbuild.com/compare/lemon-squeezy-vs-stripe) · [pricing](https://howmakersbuild.com/tools/lemon-squeezy/pricing) |
| [Polar](https://howmakersbuild.com/tools/polar) · open source | 50 (4%) | Developers selling SaaS, subscriptions, usage-based plans or license keys. | [vs Dodo Payments](https://howmakersbuild.com/compare/dodo-payments-vs-polar) · [pricing](https://howmakersbuild.com/tools/polar/pricing) |
| [Dodo Payments](https://howmakersbuild.com/tools/dodo-payments) | 30 (2%) | AI and SaaS products with usage-based billing, selling globally. | [vs Stripe](https://howmakersbuild.com/compare/dodo-payments-vs-stripe) · [pricing](https://howmakersbuild.com/tools/dodo-payments/pricing) |
| [Razorpay](https://howmakersbuild.com/tools/razorpay) | 21 (2%) | Selling to customers in India, with UPI, cards, net banking and wallets in one checkout. |  |
| [Orb](https://howmakersbuild.com/tools/orb) | 15 (1%) | High-volume usage billing with many pricing models, for products whose revenue depends on it. |  |
| [Autumn](https://howmakersbuild.com/tools/autumn) · open source | 11 (1%) | Credits, usage limits and plan entitlements on top of Stripe, checked from your code with a few calls instead of Stripe webhooks. |  |
| [Creem](https://howmakersbuild.com/tools/creem) | 2 (<1%) | SaaS and AI products that need revenue splits between co-founders or affiliates. | [pricing](https://howmakersbuild.com/tools/creem/pricing) |

</details>

## AI in the product

Models, the code that calls them, the data they read, and seeing what they do.

### LLM API

Call large language models from your product. What 985 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/llm-api).

<a href="https://howmakersbuild.com/tasks/llm-api"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/llm-api-dark.svg"><img alt="LLM API: OpenAI API 74%, Claude 26%, Gemini API 10%, OpenRouter 6%, Groq 4%, Azure OpenAI 2%" src="charts/llm-api-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [OpenAI API](https://howmakersbuild.com/tools/openai) | 728 (74%) | The broadest model lineup — text, images, speech, embeddings — and the largest ecosystem. | [vs Claude](https://howmakersbuild.com/compare/claude-vs-openai) · [pricing](https://howmakersbuild.com/tools/openai/pricing) |
| [Claude](https://howmakersbuild.com/tools/claude) | 252 (26%) | Coding, long documents and agent-style tool use. | [vs OpenAI API](https://howmakersbuild.com/compare/claude-vs-openai) · [pricing](https://howmakersbuild.com/tools/claude/pricing) |
| [Gemini API](https://howmakersbuild.com/tools/gemini-api) | 99 (10%) | Very long context and multimodal input, with a free tier to start. | [vs Claude](https://howmakersbuild.com/compare/claude-vs-gemini-api) · [pricing](https://howmakersbuild.com/tools/gemini-api/pricing) |
| [OpenRouter](https://howmakersbuild.com/tools/openrouter) | 61 (6%) | Trying many models from many providers with one API key and one bill, without opening an account at each. | [vs LiteLLM](https://howmakersbuild.com/compare/litellm-vs-openrouter) |
| [Groq](https://howmakersbuild.com/tools/groq) | 39 (4%) | Very low-latency inference on open models, for real-time features. | [vs Grok API](https://howmakersbuild.com/compare/grok-api-vs-groq) · [pricing](https://howmakersbuild.com/tools/groq/pricing) |
| [Azure OpenAI](https://howmakersbuild.com/tools/azure-openai) | 22 (2%) | OpenAI models inside an Azure account, with regional and EU/US data-zone deployments. | [vs OpenAI API](https://howmakersbuild.com/compare/azure-openai-vs-openai) |
| [LiteLLM](https://howmakersbuild.com/tools/litellm) · open source | 21 (2%) | Running your own OpenAI-compatible proxy in front of your own provider keys, with retries, routing and per-key budgets. | [vs OpenRouter](https://howmakersbuild.com/compare/litellm-vs-openrouter) |
| [Mistral AI](https://howmakersbuild.com/tools/mistral) | 15 (2%) | A European provider whose API covers chat, coding, OCR and speech models. | [vs Claude](https://howmakersbuild.com/compare/claude-vs-mistral) · [pricing](https://howmakersbuild.com/tools/mistral/pricing) |
| [Together AI](https://howmakersbuild.com/tools/together-ai) | 12 (1%) | Per-token access to a wide catalog of open-weight models, with fine-tuning and dedicated GPUs from the same vendor. | [pricing](https://howmakersbuild.com/tools/together-ai/pricing) |
| [DeepSeek](https://howmakersbuild.com/tools/deepseek) | 11 (1%) | Low per-token prices on strong reasoning and coding models, with OpenAI- and Anthropic-format endpoints. | [vs Claude](https://howmakersbuild.com/compare/claude-vs-deepseek) · [pricing](https://howmakersbuild.com/tools/deepseek/pricing) |

</details>

### AI SDK & Agent Framework

The code between your product and the model — streaming, tool calls, structured output — and, when you need it, the agent loop that keeps state and hands work between steps. What 115 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/agent-framework).

<a href="https://howmakersbuild.com/tasks/agent-framework"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/agent-framework-dark.svg"><img alt="AI SDK &amp; Agent Framework: LangChain 57%, Mastra 21%, LlamaIndex 14%, AI SDK 4%, CrewAI 3%, OpenAI Agents SDK 1%" src="charts/agent-framework-light.svg" width="800"></picture></a>

<details><summary>All 9 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [LangChain](https://howmakersbuild.com/tools/langchain) · open source | 65 (57%) | The largest set of ready-made integrations for models, tools and data sources, in Python and JavaScript. | [vs LlamaIndex](https://howmakersbuild.com/compare/langchain-vs-llamaindex) |
| [Mastra](https://howmakersbuild.com/tools/mastra) · open source | 24 (21%) | TypeScript and Next.js apps that want agents, workflows, memory and RAG without a Python service. | [vs AI SDK](https://howmakersbuild.com/compare/mastra-vs-vercel-ai-sdk) |
| [LlamaIndex](https://howmakersbuild.com/tools/llamaindex) · open source | 16 (14%) | Agents that mostly retrieve and reason over your own documents. | [vs LangChain](https://howmakersbuild.com/compare/langchain-vs-llamaindex) |
| [AI SDK](https://howmakersbuild.com/tools/vercel-ai-sdk) · open source | 5 (4%) | TypeScript agents with tool calling, multi-step loops and streaming to the UI, on any model provider. | [vs Mastra](https://howmakersbuild.com/compare/mastra-vs-vercel-ai-sdk) |
| [CrewAI](https://howmakersbuild.com/tools/crewai) · open source | 3 (3%) | Python projects that split work across several role-based agents, like researcher, writer and reviewer. | [vs LangChain](https://howmakersbuild.com/compare/crewai-vs-langchain) |
| [OpenAI Agents SDK](https://howmakersbuild.com/tools/openai-agents-sdk) · open source | 1 (1%) | A small agent loop with tools, handoffs, guardrails and tracing built in, from the OpenAI team. |  |
| [LangGraph](https://howmakersbuild.com/tools/langgraph) · open source | 1 (1%) | Stateful agents built as an explicit graph of steps, with checkpoints, retries, streaming and pauses for human approval, in Python or JavaScript. |  |
| [Dify](https://howmakersbuild.com/tools/dify-ai) | 1 (1%) | Agents, RAG chatbots and multi-step LLM workflows built on a visual canvas and published as a web app, API or MCP server. |  |
| [Langflow](https://howmakersbuild.com/tools/langflow) · open source | 1 (1%) | Agents, RAG flows and MCP servers assembled from components on a visual canvas and served as an API, an MCP server or an embedded chat widget, under the MIT license. |  |

</details>

### Vector Database

Store embeddings and find the most similar ones fast, for semantic search, RAG and recommendations. What 107 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/vector-database).

<a href="https://howmakersbuild.com/tasks/vector-database"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/vector-database-dark.svg"><img alt="Vector Database: Pinecone 50%, Qdrant 17%, Weaviate 15%, Chroma 11%, turbopuffer 7%, LanceDB 3%" src="charts/vector-database-light.svg" width="800"></picture></a>

<details><summary>All 7 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Pinecone](https://howmakersbuild.com/tools/pinecone) | 53 (50%) | A fully hosted index with nothing to operate, sized by usage. | [vs Weaviate](https://howmakersbuild.com/compare/pinecone-vs-weaviate) · [pricing](https://howmakersbuild.com/tools/pinecone/pricing) |
| [Qdrant](https://howmakersbuild.com/tools/qdrant) · open source | 18 (17%) | Heavy metadata filtering alongside vector search, self-hosted from one binary or on its managed cloud. | [vs Chroma](https://howmakersbuild.com/compare/chroma-vs-qdrant) · [pricing](https://howmakersbuild.com/tools/qdrant/pricing) |
| [Weaviate](https://howmakersbuild.com/tools/weaviate) · open source | 16 (15%) | Hybrid search that mixes keyword and vector results, with built-in modules that can create embeddings for you. | [vs Pinecone](https://howmakersbuild.com/compare/pinecone-vs-weaviate) · [pricing](https://howmakersbuild.com/tools/weaviate/pricing) |
| [Chroma](https://howmakersbuild.com/tools/chroma) · open source | 12 (11%) | Prototyping RAG on your laptop with a pip or npm install and no server to run. | [vs Qdrant](https://howmakersbuild.com/compare/chroma-vs-qdrant) · [pricing](https://howmakersbuild.com/tools/chroma/pricing) |
| [turbopuffer](https://howmakersbuild.com/tools/turbopuffer) | 8 (7%) | Very large or many-tenant indexes where storing everything on object storage keeps cost down. | [vs LanceDB](https://howmakersbuild.com/compare/lancedb-vs-turbopuffer) · [pricing](https://howmakersbuild.com/tools/turbopuffer/pricing) |
| [LanceDB](https://howmakersbuild.com/tools/lancedb) · open source | 3 (3%) | An embedded vector database that stores vectors and data as files on local disk or object storage, with no server to run. | [vs Qdrant](https://howmakersbuild.com/compare/lancedb-vs-qdrant) |
| [pgvector](https://howmakersbuild.com/tools/pgvector) · open source | 1 (1%) | Apps already on Postgres that want vector search in the same database, joined with normal tables. |  |

</details>

### LLM Observability & Evals

See what your prompts, models and agents actually did in production, and test changes against real examples before you ship them. What 65 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/llm-observability).

<a href="https://howmakersbuild.com/tasks/llm-observability"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/llm-observability-dark.svg"><img alt="LLM Observability &amp; Evals: Langfuse 52%, Helicone 20%, LangSmith 17%, Braintrust 9%, Weights &amp; Biases 2%" src="charts/llm-observability-light.svg" width="800"></picture></a>

<details><summary>All 5 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Langfuse](https://howmakersbuild.com/tools/langfuse) · open source | 34 (52%) | Tracing, prompt management and evals in one tool you can run on your own server for free. | [vs LangSmith](https://howmakersbuild.com/compare/langfuse-vs-langsmith) · [pricing](https://howmakersbuild.com/tools/langfuse/pricing) |
| [Helicone](https://howmakersbuild.com/tools/helicone) · open source | 13 (20%) | Getting request logs, costs and latency by changing one base URL, with no SDK instrumentation. | [vs Langfuse](https://howmakersbuild.com/compare/helicone-vs-langfuse) · [pricing](https://howmakersbuild.com/tools/helicone/pricing) |
| [LangSmith](https://howmakersbuild.com/tools/langsmith) | 11 (17%) | Apps built on LangChain or LangGraph, where tracing works with almost no setup. | [vs Langfuse](https://howmakersbuild.com/compare/langfuse-vs-langsmith) · [pricing](https://howmakersbuild.com/tools/langsmith/pricing) |
| [Braintrust](https://howmakersbuild.com/tools/braintrust) | 6 (9%) | Eval-driven work — scoring outputs and comparing prompts and models side by side in experiments. | [vs LangSmith](https://howmakersbuild.com/compare/braintrust-vs-langsmith) |
| [Weights & Biases](https://howmakersbuild.com/tools/weights-biases) | 1 (2%) | Tracing and evaluating LLM apps and agents with W&B Weave, in the same account you use for experiment tracking and a model registry when you train or fine-tune models. |  |

</details>

## Shipping

Where it runs, and knowing when it breaks.

### Hosting

Get your app onto the internet with a URL, HTTPS and deploys from git. What 3,503 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/hosting).

<a href="https://howmakersbuild.com/tasks/hosting"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/hosting-dark.svg"><img alt="Hosting: Vercel 57%, Amazon Web Services 13%, Cloudflare 11%, Netlify 8%, Google Cloud Platform 5%, DigitalOcean 4%" src="charts/hosting-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Vercel](https://howmakersbuild.com/tools/vercel) | 2,006 (57%) | Next.js apps — zero-config deploys and preview URLs. | [vs Netlify](https://howmakersbuild.com/compare/netlify-vs-vercel) · [pricing](https://howmakersbuild.com/tools/vercel/pricing) |
| [Amazon Web Services](https://howmakersbuild.com/tools/aws) | 451 (13%) | The widest catalog of building blocks — Lambda, containers, managed databases, queues — to assemble your own infrastructure. | [vs Microsoft Azure](https://howmakersbuild.com/compare/aws-vs-microsoft-azure) · [pricing](https://howmakersbuild.com/tools/aws/pricing) |
| [Cloudflare](https://howmakersbuild.com/tools/cloudflare) | 372 (11%) | Cheap global hosting with Workers, plus database (D1) and storage (R2) on the same platform. | [vs Vercel](https://howmakersbuild.com/compare/cloudflare-vs-vercel) · [pricing](https://howmakersbuild.com/tools/cloudflare/pricing) |
| [Netlify](https://howmakersbuild.com/tools/netlify) | 265 (8%) | Static sites and JAMstack apps on any framework. | [vs Vercel](https://howmakersbuild.com/compare/netlify-vs-vercel) · [pricing](https://howmakersbuild.com/tools/netlify/pricing) |
| [Google Cloud Platform](https://howmakersbuild.com/tools/google-cloud) | 174 (5%) | Containers on Cloud Run that scale to zero, next to BigQuery, Firebase and Google's AI services. | [vs Amazon Web Services](https://howmakersbuild.com/compare/aws-vs-google-cloud) |
| [DigitalOcean](https://howmakersbuild.com/tools/digitalocean) | 148 (4%) | App Platform deploys from git next to DigitalOcean's managed databases, storage and droplets. | [vs Amazon Web Services](https://howmakersbuild.com/compare/aws-vs-digitalocean) |
| [Render](https://howmakersbuild.com/tools/render) | 137 (4%) | A Heroku-style platform for web services, cron jobs and Postgres. | [vs Railway](https://howmakersbuild.com/compare/railway-vs-render) · [pricing](https://howmakersbuild.com/tools/render/pricing) |
| [GitHub Pages](https://howmakersbuild.com/tools/github-pages) | 128 (4%) | Free hosting for static sites, docs and landing pages published straight from a repo. | [vs Netlify](https://howmakersbuild.com/compare/github-pages-vs-netlify) |
| [Railway](https://howmakersbuild.com/tools/railway) | 120 (3%) | Servers, workers and databases deployed together, with almost no configuration. | [vs Render](https://howmakersbuild.com/compare/railway-vs-render) · [pricing](https://howmakersbuild.com/tools/railway/pricing) |
| [Hetzner Cloud](https://howmakersbuild.com/tools/hetzner) | 110 (3%) | A lot of CPU and RAM per euro, in European, US and Singapore regions. | [vs DigitalOcean](https://howmakersbuild.com/compare/digitalocean-vs-hetzner) · [pricing](https://howmakersbuild.com/tools/hetzner/pricing) |

</details>

### Image & Video Hosting

Store user uploads and product media, resize and compress them on the fly, and serve them fast from a CDN. What 113 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/media-hosting).

<a href="https://howmakersbuild.com/tasks/media-hosting"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/media-hosting-dark.svg"><img alt="Image &amp; Video Hosting: Cloudinary 52%, ImageKit 22%, Mux 21%, imgix 5%" src="charts/media-hosting-light.svg" width="800"></picture></a>

<details><summary>All 4 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Cloudinary](https://howmakersbuild.com/tools/cloudinary) | 59 (52%) | Apps with lots of user-uploaded images and video that need crops, overlays and format conversion through URLs. | [pricing](https://howmakersbuild.com/tools/cloudinary/pricing) |
| [ImageKit](https://howmakersbuild.com/tools/imagekit) | 25 (22%) | Adding resizing and optimization in front of storage you already have, such as an S3 bucket. | [pricing](https://howmakersbuild.com/tools/imagekit/pricing) |
| [Mux](https://howmakersbuild.com/tools/mux) | 24 (21%) | Apps where video is the product — uploads encoded and streamed adaptively with a player and playback analytics. |  |
| [imgix](https://howmakersbuild.com/tools/imgix) | 6 (5%) | Resizing and optimizing images straight from your own bucket through URL parameters. | [pricing](https://howmakersbuild.com/tools/imgix/pricing) |

</details>

### Error Monitoring

Find out when your app throws an error in production, with the stack trace and context to fix it, before users email you. What 190 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/error-monitoring).

<a href="https://howmakersbuild.com/tasks/error-monitoring"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/error-monitoring-dark.svg"><img alt="Error Monitoring: Sentry 96%, Rollbar 3%, BugSnag 1%, Highlight 1%, Honeybadger 1%" src="charts/error-monitoring-light.svg" width="800"></picture></a>

<details><summary>All 5 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Sentry](https://howmakersbuild.com/tools/sentry) | 182 (96%) | Broad SDK coverage across languages and frameworks, with performance tracing next to errors. | [vs GlitchTip](https://howmakersbuild.com/compare/glitchtip-vs-sentry) · [pricing](https://howmakersbuild.com/tools/sentry/pricing) |
| [Rollbar](https://howmakersbuild.com/tools/rollbar) | 6 (3%) | Error grouping tied to releases, with session replays linked to errors. | [vs Sentry](https://howmakersbuild.com/compare/rollbar-vs-sentry) · [pricing](https://howmakersbuild.com/tools/rollbar/pricing) |
| [BugSnag](https://howmakersbuild.com/tools/bugsnag) | 2 (1%) | Crash and error reporting for mobile, web and backend apps, with a stability score for each release. |  |
| [Highlight](https://howmakersbuild.com/tools/highlight) · open source | 2 (1%) | Self-hosting errors, session replays, logs and traces from the open-source code of a product that no longer runs as a hosted service. |  |
| [Honeybadger](https://howmakersbuild.com/tools/honeybadger) | 1 (1%) | One tool covering errors, logs, uptime checks and cron monitoring, with a free plan for a single developer. | [pricing](https://howmakersbuild.com/tools/honeybadger/pricing) |

</details>

## Growth

Knowing who comes and what they do, and writing to them.

### Web Analytics

Count how many people visit your site, which pages they read, and where they came from — search, social posts, launch sites or newsletters. What 900 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/web-analytics).

<a href="https://howmakersbuild.com/tasks/web-analytics"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/web-analytics-dark.svg"><img alt="Web Analytics: Google Analytics 46%, Plausible Analytics 26%, Cloudflare Web Analytics 15%, Umami 9%, Fathom Analytics 5%, Simple Analytics 3%" src="charts/web-analytics-light.svg" width="800"></picture></a>

<details><summary>All 6 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Google Analytics](https://howmakersbuild.com/tools/google-analytics) | 412 (46%) | Free, deep campaign and audience reporting tied to Google Ads and Search Console. | [pricing](https://howmakersbuild.com/tools/google-analytics/pricing) |
| [Plausible Analytics](https://howmakersbuild.com/tools/plausible) · open source | 230 (26%) | One page of traffic numbers with no cookie banner, with funnels and revenue goals on higher plans. | [pricing](https://howmakersbuild.com/tools/plausible/pricing) |
| [Cloudflare Web Analytics](https://howmakersbuild.com/tools/cloudflare-web-analytics) | 139 (15%) | Free cookie-free visit counts for sites on any host, set up in minutes. | [pricing](https://howmakersbuild.com/tools/cloudflare-web-analytics/pricing) |
| [Umami](https://howmakersbuild.com/tools/umami) · open source | 78 (9%) | Open-source website analytics you can self-host free, with a cloud free plan up to 100,000 events a month. | [pricing](https://howmakersbuild.com/tools/umami/pricing) |
| [Fathom Analytics](https://howmakersbuild.com/tools/fathom) | 48 (5%) | A cookie-free dashboard with up to 50 sites on every plan. | [pricing](https://howmakersbuild.com/tools/fathom/pricing) |
| [Simple Analytics](https://howmakersbuild.com/tools/simple-analytics) | 31 (3%) | A free cookie-free plan with unlimited pageviews, keeping only the last 30 days of data. | [pricing](https://howmakersbuild.com/tools/simple-analytics/pricing) |

</details>

### Product Analytics

See what signed-in users do inside the product — which steps they finish, where they drop off, and whether they come back. What 521 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/product-analytics).

<a href="https://howmakersbuild.com/tasks/product-analytics"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/product-analytics-dark.svg"><img alt="Product Analytics: PostHog 65%, Mixpanel 21%, Amplitude 17%" src="charts/product-analytics-light.svg" width="800"></picture></a>

<details><summary>All 3 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [PostHog](https://howmakersbuild.com/tools/posthog) · open source | 337 (65%) | One tool for analytics, session replay, feature flags, experiments and surveys, each with its own free monthly allowance. | [pricing](https://howmakersbuild.com/tools/posthog/pricing) |
| [Mixpanel](https://howmakersbuild.com/tools/mixpanel) | 109 (21%) | Mature funnel, retention and cohort analysis on event data. | [pricing](https://howmakersbuild.com/tools/mixpanel/pricing) |
| [Amplitude](https://howmakersbuild.com/tools/amplitude) | 86 (17%) | Funnel, retention and cohort analysis, with session replay and experiments on every plan, including free. | [pricing](https://howmakersbuild.com/tools/amplitude/pricing) |

</details>

### Newsletter

Build an email list you own and send regular updates, so your audience doesn't depend on any algorithm. What 157 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/newsletter).

<a href="https://howmakersbuild.com/tasks/newsletter"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/newsletter-dark.svg"><img alt="Newsletter: Kit 47%, Ghost 30%, Substack 10%, beehiiv 9%, MailerLite 5%" src="charts/newsletter-light.svg" width="800"></picture></a>

<details><summary>All 5 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Kit](https://howmakersbuild.com/tools/kit) | 74 (47%) | Creators who need automations and tagged sequences, like a course launch funnel. | [pricing](https://howmakersbuild.com/tools/kit/pricing) |
| [Ghost](https://howmakersbuild.com/tools/ghost) · open source | 47 (30%) | A publication with its own site, memberships and paid subscriptions, open source or hosted. | [pricing](https://howmakersbuild.com/tools/ghost/pricing) |
| [Substack](https://howmakersbuild.com/tools/substack) | 15 (10%) | Writers who want discovery from Substack's own reader network and free sending. | [pricing](https://howmakersbuild.com/tools/substack/pricing) |
| [beehiiv](https://howmakersbuild.com/tools/beehiiv) | 14 (9%) | A newsletter you want to grow and monetize, with referrals, a recommendation network and ads. | [pricing](https://howmakersbuild.com/tools/beehiiv/pricing) |
| [MailerLite](https://howmakersbuild.com/tools/mailerlite) | 8 (5%) | Newsletters with signup forms, automations and landing pages, on a free plan that grows by subscriber count. | [pricing](https://howmakersbuild.com/tools/mailerlite/pricing) |

</details>

### Lifecycle Email

Send the right email at the right point in a user's journey — onboarding, nudges, upgrade prompts, win-backs — based on what they did in your product. What 287 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/lifecycle-email).

<a href="https://howmakersbuild.com/tasks/lifecycle-email"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/lifecycle-email-dark.svg"><img alt="Lifecycle Email: Loops 80%, Customer.io 17%, Userlist 3%" src="charts/lifecycle-email-light.svg" width="800"></picture></a>

<details><summary>All 3 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Loops](https://howmakersbuild.com/tools/loops) | 231 (80%) | Event-triggered onboarding sequences and transactional email from one tool, with a free tier to start. | [pricing](https://howmakersbuild.com/tools/loops/pricing) |
| [Customer.io](https://howmakersbuild.com/tools/customer-io) | 48 (17%) | Complex behavior-driven journeys across email, push, SMS and in-app messages. | [pricing](https://howmakersbuild.com/tools/customer-io/pricing) |
| [Userlist](https://howmakersbuild.com/tools/userlist) | 8 (3%) | B2B SaaS where messages depend on both the user and the company account they belong to. | [pricing](https://howmakersbuild.com/tools/userlist/pricing) |

</details>

## Building with AI

The agents and builders that write the code with you.

### AI Coding Assistants

Use an AI assistant to write, edit and explain code in your own project, from autocomplete to agents that carry out multi-step tasks. What 1,401 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/ai-coding-assistant).

<a href="https://howmakersbuild.com/tasks/ai-coding-assistant"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/ai-coding-assistant-dark.svg"><img alt="AI Coding Assistants: Claude Code 52%, Cursor 38%, OpenAI Codex 10%, OpenCode 3%, Devin Desktop (formerly Windsurf) 3%, Zed 2%" src="charts/ai-coding-assistant-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Claude Code](https://howmakersbuild.com/tools/claude-code) | 735 (52%) | Handing off multi-step tasks — features, refactors, bug hunts — to an agent that reads the repo, edits files and runs commands. | [vs GitHub Copilot](https://howmakersbuild.com/compare/claude-code-vs-github-copilot) · [pricing](https://howmakersbuild.com/tools/claude-code/pricing) |
| [Cursor](https://howmakersbuild.com/tools/cursor) | 534 (38%) | A VS Code-style editor with AI completions, chat and agents built in, keeping your VS Code extensions. | [vs Claude Code](https://howmakersbuild.com/compare/claude-code-vs-cursor) · [pricing](https://howmakersbuild.com/tools/cursor/pricing) |
| [OpenAI Codex](https://howmakersbuild.com/tools/openai-codex) · open source | 136 (10%) | Delegating tasks to an agent in the terminal, IDE or desktop app, or to cloud tasks that run in the background and open pull requests. | [vs Claude Code](https://howmakersbuild.com/compare/claude-code-vs-openai-codex) · [pricing](https://howmakersbuild.com/tools/openai-codex/pricing) |
| [OpenCode](https://howmakersbuild.com/tools/opencode) · open source | 41 (3%) | An open-source coding agent that works with almost any model provider, local models, or an existing Copilot or ChatGPT subscription. | [vs Claude Code](https://howmakersbuild.com/compare/claude-code-vs-opencode) · [pricing](https://howmakersbuild.com/tools/opencode/pricing) |
| [Devin Desktop (formerly Windsurf)](https://howmakersbuild.com/tools/windsurf) | 37 (3%) | A VS Code-style editor with unlimited Tab completions, an in-editor agent, and one place to manage local and cloud Devin agents. | [vs Cursor](https://howmakersbuild.com/compare/cursor-vs-windsurf) · [pricing](https://howmakersbuild.com/tools/windsurf/pricing) |
| [Zed](https://howmakersbuild.com/tools/zed) · open source | 31 (2%) | A fast, open-source native editor with built-in AI edit predictions and agent chat, and a choice of models. | [pricing](https://howmakersbuild.com/tools/zed/pricing) |
| [GitHub Copilot](https://howmakersbuild.com/tools/github-copilot) | 27 (2%) | Adding AI completions, chat and agents to the editor you already use, including VS Code and JetBrains IDEs, plus pull request reviews on GitHub. | [vs Claude Code](https://howmakersbuild.com/compare/claude-code-vs-github-copilot) · [pricing](https://howmakersbuild.com/tools/github-copilot/pricing) |
| [Conductor](https://howmakersbuild.com/tools/conductor) | 23 (2%) | Running several Claude Code, Codex, Cursor or OpenCode agents at once on a Mac, each in an isolated copy of the repo, then reviewing and merging their changes. | [pricing](https://howmakersbuild.com/tools/conductor/pricing) |
| [Google Antigravity](https://howmakersbuild.com/tools/antigravity) | 12 (1%) | An editor from Google with a manager view for running several coding agents in parallel, plus a CLI. | [vs Cursor](https://howmakersbuild.com/compare/antigravity-vs-cursor) |
| [Kilo Code](https://howmakersbuild.com/tools/kilo-code) · open source | 11 (1%) | An open-source agent for VS Code, JetBrains IDEs and the terminal with access to 500+ models, through your own keys, local models or Kilo's gateway at provider rates. |  |

</details>

### AI App Builders

Describe your app in a chat and get a working, clickable version in minutes — as a prototype to test the idea, or as the start of the real codebase. What 246 makers' products chose — [decide by situation](https://howmakersbuild.com/tasks/ai-app-builder).

<a href="https://howmakersbuild.com/tasks/ai-app-builder"><picture><source media="(prefers-color-scheme: dark)" srcset="charts/ai-app-builder-dark.svg"><img alt="AI App Builders: Lovable 30%, v0 17%, Bubble 15%, Replit 14%, Softr 11%, Bolt 10%" src="charts/ai-app-builder-light.svg" width="800"></picture></a>

<details><summary>All 10 with what each is best for, comparisons and pricing</summary>

| Tool | Used by | Best for | More |
|---|---|---|---|
| [Lovable](https://howmakersbuild.com/tools/lovable) | 73 (30%) | Full-stack web apps from chat, with auth and database through a built-in Supabase connection. | [vs Replit](https://howmakersbuild.com/compare/lovable-vs-replit) · [pricing](https://howmakersbuild.com/tools/lovable/pricing) |
| [v0](https://howmakersbuild.com/tools/v0) | 41 (17%) | React and Next.js UI and apps that you pull into your own repository or deploy on Vercel. | [vs Lovable](https://howmakersbuild.com/compare/lovable-vs-v0) |
| [Bubble](https://howmakersbuild.com/tools/bubble) | 38 (15%) | Building a full web or native mobile app visually — pages, database, workflows and hosting in one place. |  |
| [Replit](https://howmakersbuild.com/tools/replit) | 34 (14%) | Building with an AI agent in a full cloud IDE, in many languages, with hosting included. | [vs Lovable](https://howmakersbuild.com/compare/lovable-vs-replit) |
| [Softr](https://howmakersbuild.com/tools/softr) | 26 (11%) | Client portals, internal tools and simple CRMs built visually on top of data you already keep in Airtable, Google Sheets, Notion or a database. |  |
| [Bolt](https://howmakersbuild.com/tools/bolt-new) | 24 (10%) | Generating and running a full-stack app entirely in the browser, with the code visible and editable as it is written. |  |
| [FlutterFlow](https://howmakersbuild.com/tools/flutterflow) | 13 (5%) | Visually building mobile apps that compile to real Flutter code and deploy to the app stores. |  |
| [Base44](https://howmakersbuild.com/tools/base44) | 8 (3%) | Full-stack web apps and internal tools from chat, with database, auth and hosting built into the platform, so there is no outside backend account to set up. | [vs Replit](https://howmakersbuild.com/compare/base44-vs-replit) · [pricing](https://howmakersbuild.com/tools/base44/pricing) |
| [Rork](https://howmakersbuild.com/tools/rork) | 2 (1%) | Native mobile apps from chat — SwiftUI for iPhone, Kotlin for Android — with a hosted backend, RevenueCat subscriptions and built-in publishing to the App Store and Google Play. |  |
| [WeWeb](https://howmakersbuild.com/tools/weweb) | 1 (<1%) | Generating a web app with AI, then editing its UI, data and logic visually, on top of a backend you choose such as Supabase or Xano. |  |

</details>

## How the counts work

- **Used by** counts makers' products — indie launches to small teams — where a source ties the tool to that decision. The percentage is a share of the products where we could source the decision at all, so each table has its own sample.
- Open-source repositories known only from their dependencies aren't counted here: most aren't products. They're listed separately on each tool's page.
- What a website can show is over-counted, and what runs behind it is under-counted: a hosted auth widget is easy to spot, an auth library isn't. A tool missing from a table isn't unused, just unobserved.
- More on each kind of evidence: [how evidence is collected](https://howmakersbuild.com/about/evidence).

## Contributing

Know a product built with one of these tools? [Open an issue](../../issues/new) with the product, the tool and a public source that says so — the maker's own post, a page on its site, a job posting. It's checked and added to the data, and shows up here on the next weekly refresh.

The README is generated, so pull requests that edit it by hand get overwritten; issues are the way in.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): use it anywhere, with a link back to [How Makers Build](https://howmakersbuild.com).
