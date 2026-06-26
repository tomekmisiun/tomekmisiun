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
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic" />
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
<img src="https://img.shields.io/badge/Alembic-6BA81E?style=flat-square" alt="Alembic" />
<img src="https://img.shields.io/badge/REST_API-005571?style=flat-square" alt="REST API" />
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/httpx-2D3748?style=flat-square" alt="httpx" />
</p>

### Databases, queues and storage

<p>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/MinIO-C72E49?style=flat-square&logo=minio&logoColor=white" alt="MinIO" />
<img src="https://img.shields.io/badge/S3_compatible-569A31?style=flat-square&logo=amazons3&logoColor=white" alt="S3-compatible storage" />
</p>

### Frontend

<p>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

### Testing and quality

<p>
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
<img src="https://img.shields.io/badge/pytest--cov-0A9EDC?style=flat-square" alt="pytest-cov" />
<img src="https://img.shields.io/badge/pytest--xdist-0A9EDC?style=flat-square" alt="pytest-xdist" />
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
<img src="https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black" alt="Ruff" />
<img src="https://img.shields.io/badge/pre--commit-FAB040?style=flat-square&logo=precommit&logoColor=black" alt="pre-commit" />
</p>

### DevOps, security and observability

<p>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker Compose" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
<img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white" alt="Railway" />
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
<img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" alt="Sentry" />
<img src="https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white" alt="Trivy" />
<img src="https://img.shields.io/badge/gitleaks-6F42C1?style=flat-square" alt="gitleaks" />
</p>

### Integrations and AI tooling

<p>
<img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white" alt="Twilio" />
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
<img src="https://img.shields.io/badge/Codex_CLI-000000?style=flat-square&logo=openai&logoColor=white" alt="Codex CLI" />
<img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor" />
<img src="https://img.shields.io/badge/LLM_APIs-6C63FF?style=flat-square" alt="LLM APIs" />
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
