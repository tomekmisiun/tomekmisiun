<a id="readme-top"></a>

<div align="center">

# Hi, I'm Tomasz Misiun 👋

### Backend-focused developer building production-oriented APIs, SaaS systems and automation workflows

I work mainly with **Python**, **FastAPI**, **PostgreSQL**, **Redis** and **Docker**.  
I am interested in the complete application lifecycle — from product behavior and data modelling to deployment, observability and reliability.

<br />

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-MISIUN.DEV-2ea44f?style=for-the-badge&logo=vercel&logoColor=white)](https://misiun.dev)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-TOMASZ_MISIUN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tomasz-misiun/)
[![Email](https://img.shields.io/badge/EMAIL-CONTACT_ME-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tomek.misiun@gmail.com)

<br />

[![GitHub followers](https://img.shields.io/github/followers/tomekmisiun?style=flat-square&logo=github&label=Followers)](https://github.com/tomekmisiun?tab=followers)
[![Profile views](https://komarev.com/ghpvc/?username=tomekmisiun&style=flat-square&label=Profile+views)](https://github.com/tomekmisiun)
[![Location](https://img.shields.io/badge/Gdańsk-Poland-1f6feb?style=flat-square&logo=googlemaps&logoColor=white)](https://misiun.dev)

<br />

![Python](https://img.shields.io/badge/Python-3.13%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-APIs-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-Queue_&_Cache-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## Contents

- [About me](#about-me)
- [Featured projects](#featured-projects)
- [Core stack](#core-stack)
- [What I focus on](#what-i-focus-on)
- [How I work](#how-i-work)
- [Background](#background)
- [GitHub activity](#github-activity)
- [Contact](#contact)

---

## About me

I am a Computer Science student and backend-focused developer based in **Gdańsk, Poland**.

I build applications as complete systems rather than isolated code samples. That includes:

- understanding how a product should behave from the user's perspective,
- designing APIs, domain models and database structures,
- implementing authentication, integrations and background processing,
- adding automated tests and quality gates,
- packaging applications with Docker,
- deploying them to the cloud,
- monitoring health, failures and production behavior.

I am particularly interested in **process automation**, **developer productivity** and the practical use of **AI coding agents** in structured software-development workflows.

> **Build. Ship. Measure. Improve.**

---

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 📞 [VoxSlot](https://github.com/tomekmisiun/appointment-voice-saas)

Multi-tenant SaaS for appointment-based businesses that miss phone calls while serving customers.

The system combines a phone IVR, appointment scheduling, SMS communication, calendar synchronization and an owner dashboard.

**Highlights**

- Twilio Voice and SMS
- IVR / DTMF booking flows
- service and staff availability
- booking, cancellation and rescheduling
- multi-tenant business configuration
- Redis workers and transactional outbox
- Next.js owner dashboard
- metrics, health checks and CI/CD

**Stack**

`Python` `FastAPI` `PostgreSQL` `Redis` `Twilio` `Next.js` `Docker`

<br />

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/tomekmisiun/appointment-voice-saas)
[![Live demo](https://img.shields.io/badge/Live-Demo-2ea44f?style=flat-square&logo=railway&logoColor=white)](https://voxslot.up.railway.app/)

</td>
<td width="50%" valign="top">

### 🥗 [OnTrack](https://github.com/tomekmisiun/OnTrack)

Full-stack meal-planning and household-budget application.

It connects products, recipes, household members, meal planning, nutrition targets and expense tracking through one system.

**Highlights**

- product and recipe catalog
- meal calendar
- household-member profiles
- calorie and macro calculator
- day schedules
- budget summaries and exports
- PL/EN interface and PL/GB markets
- FastAPI and Next.js architecture

**Stack**

`Python` `FastAPI` `Next.js` `TypeScript` `PostgreSQL` `Redis` `Docker`

<br />

[![Repository](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/tomekmisiun/OnTrack)
[![Live demo](https://img.shields.io/badge/Live-Demo-2ea44f?style=flat-square&logo=railway&logoColor=white)](https://ontrackapp.up.railway.app/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ [FastAPI Production Foundation](https://github.com/tomekmisiun/fastapi-production-foundation)

Reusable, AI-ready backend foundation for SaaS and API projects.

It provides a production-oriented starting point with authentication, database migrations, testing, background workers, security checks and observability already configured.

**Highlights**

- JWT authentication and token lifecycle
- PostgreSQL and Alembic
- Redis queues and rate limiting
- S3-compatible uploads
- webhook idempotency
- audit logging and multi-tenant hooks
- Prometheus, Sentry and health checks
- CI security and coverage gates

**Stack**

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `Redis` `pytest` `Docker`

<br />

[![Repository](https://img.shields.io/badge/GitHub-Template-181717?style=flat-square&logo=github)](https://github.com/tomekmisiun/fastapi-production-foundation)
[![Stars](https://img.shields.io/github/stars/tomekmisiun/fastapi-production-foundation?style=flat-square)](https://github.com/tomekmisiun/fastapi-production-foundation/stargazers)

</td>
<td width="50%" valign="top">

### 🤖 [AI Agent Rules Template](https://github.com/tomekmisiun/ai-agent-rules-template)

Reusable policy and workflow system for AI coding agents.

The template keeps one source of truth for development rules and provides adapters for Cursor, Claude Code and Codex CLI.

**Highlights**

- one task per branch
- explicit scope control
- mandatory testing and review
- builder / reviewer handoffs
- cross-provider review
- Git approval gates
- static workflow validation
- reusable repository adapters

**Tools**

`Cursor` `Claude Code` `Codex CLI` `Bash` `GitHub Actions`

<br />

[![Repository](https://img.shields.io/badge/GitHub-Template-181717?style=flat-square&logo=github)](https://github.com/tomekmisiun/ai-agent-rules-template)
[![Release](https://img.shields.io/github/v/release/tomekmisiun/ai-agent-rules-template?style=flat-square)](https://github.com/tomekmisiun/ai-agent-rules-template/releases)

</td>
</tr>
</table>

---

## Core stack

### Backend and APIs

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="44" height="44" alt="Python" title="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" width="44" height="44" alt="FastAPI" title="FastAPI" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pydantic/pydantic-original.svg" width="44" height="44" alt="Pydantic" title="Pydantic" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlalchemy/sqlalchemy-original.svg" width="44" height="44" alt="SQLAlchemy" title="SQLAlchemy" />
  <img src="https://cdn.simpleicons.org/jsonwebtokens/000000" width="44" height="44" alt="JWT" title="JSON Web Tokens" />
  <img src="https://cdn.simpleicons.org/openapiinitiative/6BA539" width="44" height="44" alt="OpenAPI" title="OpenAPI / REST APIs" />
</p>

### Databases, queues and storage

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="44" height="44" alt="PostgreSQL" title="PostgreSQL" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/redis/redis-original.svg" width="44" height="44" alt="Redis" title="Redis" />
  <img src="https://cdn.simpleicons.org/minio/C72E49" width="44" height="44" alt="MinIO" title="MinIO" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="44" height="44" alt="Amazon S3" title="S3-compatible storage" />
</p>

### Frontend

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" width="44" height="44" alt="Next.js" title="Next.js" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" width="44" height="44" alt="React" title="React" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="44" height="44" alt="TypeScript" title="TypeScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" width="44" height="44" alt="Tailwind CSS" title="Tailwind CSS" />
</p>

### Testing and quality

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytest/pytest-original.svg" width="44" height="44" alt="pytest" title="pytest, pytest-cov and pytest-xdist" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitest/vitest-original.svg" width="44" height="44" alt="Vitest" title="Vitest" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/playwright/playwright-original.svg" width="44" height="44" alt="Playwright" title="Playwright" />
  <img src="https://cdn.simpleicons.org/ruff/D7FF64" width="44" height="44" alt="Ruff" title="Ruff" />
  <img src="https://cdn.simpleicons.org/precommit/FAB040" width="44" height="44" alt="pre-commit" title="pre-commit" />
</p>

### DevOps, security and observability

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="44" height="44" alt="Docker" title="Docker and Docker Compose" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" width="44" height="44" alt="GitHub Actions" title="GitHub Actions" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="44" height="44" alt="Linux" title="Linux" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" width="44" height="44" alt="Bash" title="Bash" />
  <img src="https://cdn.simpleicons.org/railway/0B0D0E" width="44" height="44" alt="Railway" title="Railway" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/prometheus/prometheus-original.svg" width="44" height="44" alt="Prometheus" title="Prometheus" />
  <img src="https://cdn.simpleicons.org/sentry/362D59" width="44" height="44" alt="Sentry" title="Sentry" />
  <img src="https://cdn.simpleicons.org/trivy/1904DA" width="44" height="44" alt="Trivy" title="Trivy" />
</p>

### Integrations and AI tooling

<p>
  <img src="https://github.com/twilio.png?size=80" width="44" height="44" alt="Twilio" title="Twilio" />
  <img src="https://cdn.simpleicons.org/anthropic/D97757" width="44" height="44" alt="Claude Code" title="Claude Code" />
  <img src="https://github.com/openai.png?size=80" width="44" height="44" alt="Codex CLI" title="Codex CLI and LLM APIs" />
  <img src="https://cdn.simpleicons.org/cursor/000000" width="44" height="44" alt="Cursor" title="Cursor" />
</p>

---

## What I focus on

<table>
<tr>
<td width="50%" valign="top">

### Backend engineering

- REST API design
- domain and data modelling
- authentication and authorization
- multi-tenant isolation
- asynchronous jobs
- external API integrations
- idempotency and failure handling

</td>
<td width="50%" valign="top">

### Production readiness

- Docker-based environments
- database migrations
- automated test suites
- CI/CD quality gates
- metrics and health checks
- security scanning
- backup and recovery workflows

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Product thinking

- translating business problems into features
- mapping complete user flows
- documenting assumptions before implementation
- separating MVP scope from later expansion
- maintaining roadmaps and technical debt

</td>
<td width="50%" valign="top">

### AI-assisted development

- repository-level coding-agent rules
- builder and reviewer roles
- cross-provider review
- scope and Git safety gates
- structured handoffs
- repeatable validation workflows

</td>
</tr>
</table>

---

## How I work

```text
Understand the problem
        ↓
Define scope and acceptance criteria
        ↓
Design the data and API flow
        ↓
Implement a focused vertical slice
        ↓
Write and run targeted tests
        ↓
Run automated review and quality gates
        ↓
Document verified behavior
        ↓
Deploy, observe and improve
```

My repositories generally follow these practices:

- one logical task per branch,
- Conventional Commits,
- no unrelated drive-by refactors,
- tests for new behavior and bug fixes,
- migrations for database changes,
- CI validation before merge,
- explicit documentation of risks and unfinished work,
- reusable fixes backported into shared foundations.

---

## Background

Before moving deeper into software development, I worked in technical event production.

That work included audio and video systems, livestream setups, on-site troubleshooting and direct responsibility for technical delivery.

It taught me habits that transfer directly to software engineering:

- diagnosing failures under time pressure,
- taking ownership of the final result,
- working from technical documentation,
- communicating clearly when systems fail,
- preparing fallback solutions,
- keeping complex systems operational during real events.

I am currently studying **Computer Science** at **WSB Merito Gdańsk**.

---

## GitHub activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=tomekmisiun&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" alt="Tomasz Misiun GitHub statistics" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tomekmisiun&layout=compact&hide_border=true&theme=transparent&langs_count=8" alt="Most used languages" />

<br />

<img src="https://streak-stats.demolab.com?user=tomekmisiun&theme=transparent&hide_border=true" alt="GitHub contribution streak" />

</div>

> GitHub language statistics describe repository contents, not a complete measurement of professional proficiency.

---

## Contact

<div align="center">

[![Portfolio](https://img.shields.io/badge/misiun.dev-Portfolio-2ea44f?style=for-the-badge&logo=vercel&logoColor=white)](https://misiun.dev)
[![LinkedIn](https://img.shields.io/badge/Tomasz_Misiun-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tomasz-misiun/)
[![GitHub](https://img.shields.io/badge/@tomekmisiun-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/tomekmisiun)
[![Email](https://img.shields.io/badge/tomek.misiun%40gmail.com-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tomek.misiun@gmail.com)

<br />

**Gdańsk, Poland**

</div>

---

<div align="center">

**Build. Ship. Measure. Improve.**

[Back to top](#readme-top)

</div>
