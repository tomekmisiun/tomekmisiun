# Hi, I'm Tomek 👋

Backend-focused developer building production-oriented APIs, automation systems and SaaS backends with **Python, FastAPI, PostgreSQL and Docker**.

I'm currently focused on backend architecture, API design, database modelling, testing, CI/CD, observability and AI-assisted software development workflows.

---

## Tech Stack

| Area                   | Tools                                                      |
| ---------------------- | ---------------------------------------------------------- |
| **Backend**            | Python 3.13, FastAPI, Uvicorn / ASGI, Pydantic Settings    |
| **Database**           | PostgreSQL, SQLAlchemy 2.0, Alembic                        |
| **Auth & APIs**        | JWT authentication, httpx, Twilio API                      |
| **Cache / Background** | Redis                                                      |
| **Testing**            | pytest, pytest-cov, pytest-xdist                           |
| **Quality**            | ruff, pre-commit, coverage thresholds                      |
| **DevOps**             | Docker, Docker Compose, GitHub Actions, Linux, Bash        |
| **Security**           | Trivy, pip-audit, gitleaks                                 |
| **Observability**      | Prometheus metrics, Sentry, healthchecks, readiness checks |
| **Storage**            | MinIO / S3-compatible storage                              |

---

## Main Projects

### Appointment Voice SaaS

Backend SaaS project for appointment booking through phone-based **IVR / DTMF** flows.

The system is designed for service businesses such as salons and supports:

* IVR / DTMF phone menu flows
* SMS notifications
* call transfer logic
* appointment booking workflows
* multi-tenant business configuration
* external booking link support
* Twilio API integration

**Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic, Redis, Docker, pytest, GitHub Actions, Twilio API

**What I worked on:**

* Planned product assumptions, roadmap and technical documentation before implementation
* Built the project on top of my reusable FastAPI backend foundation
* Designed backend API, domain models and database structure
* Implemented IVR/SMS-related backend flows
* Integrated Twilio API for voice and SMS workflows
* Added backend tests and CI validation
* Used Docker Compose for local development with PostgreSQL, Redis and test services
* Worked in a branch-per-task workflow with review and automated validation

---

### FastAPI Production Foundation

Reusable backend template built with FastAPI as a foundation for future backend projects.

The goal of this project is to provide a production-oriented starting point for backend applications with authentication, database setup, tests, Docker, CI, observability and development tooling already prepared.

**Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic, Docker, Redis, pytest, GitHub Actions, Prometheus

**Features and areas covered:**

* modular FastAPI application structure
* PostgreSQL and Alembic migration setup
* JWT authentication foundation
* Docker Compose development environment
* pytest setup with coverage threshold
* GitHub Actions validation pipeline
* healthchecks and Prometheus metrics
* security checks with Trivy, pip-audit and gitleaks
* backporting bug fixes from Appointment Voice SaaS back into the base template

---

## Current Focus

* Backend architecture
* REST API design
* PostgreSQL and database modelling
* Docker-based development workflows
* CI/CD and automated quality gates
* Observability and monitoring
* Security basics for backend projects
* AI-assisted software development workflows

---

## Background

Before moving deeper into software development, I worked in technical event production, handling audio/video systems, livestream setups, on-site troubleshooting and client-facing technical work.

That experience shaped how I approach backend development: practical problem solving, debugging issues, responsibility for systems that need to work reliably and clear communication when something breaks.

---

## Philosophy

**Build. Ship. Measure. Improve.**

Learning comes from building real systems, debugging real problems and improving through iteration.

---

## Contact

* LinkedIn: [linkedin.com/in/tomasz-misiun](https://linkedin.com/in/tomasz-misiun/)
