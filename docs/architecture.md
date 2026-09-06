# SkillForge Architecture

## 1. Project Overview

SkillForge is a modern learning and skills management platform built using current web and cloud technologies.

The platform is designed to help learners, instructors, and organizations manage learning programs, courses, skills, progress, and professional development.

SkillForge will be developed as an independent platform using modern .NET technologies rather than relying on an existing Learning Management System.

The project will prioritize:

- Clean architecture
- Maintainability
- Security
- Scalability
- Automated testing
- Containerized development
- API-first design
- Production-ready deployment

---

## 2. Technology Stack

SkillForge will use modern, stable technologies.

### Backend

- ASP.NET Core
- C#
- REST APIs
- Entity Framework Core

### Frontend

- Next.js
- React
- TypeScript

### Database

- PostgreSQL

### Architecture

- Modular Monolith
- Clean Architecture principles
- Domain-driven design where appropriate

### Infrastructure

- Docker
- Docker Compose
- Environment-based configuration

### Testing

- xUnit
- Unit testing
- Integration testing
- API testing

### Development and Delivery

- Git
- GitHub
- GitHub Actions
- Automated CI/CD

---

## 3. High-Level Architecture

SkillForge will use a modern web architecture.

```text
┌──────────────────────────────┐
│       Next.js Frontend       │
│     React + TypeScript       │
└──────────────┬───────────────┘
               │
               │ HTTPS / REST API
               ▼
┌──────────────────────────────┐
│      ASP.NET Core API        │
│                              │
│  Authentication              │
│  Authorization               │
│  REST Endpoints              │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│      Application Layer       │
│                              │
│  Use Cases                   │
│  Application Services        │
│  DTOs                        │
│  Validation                  │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│        Domain Layer          │
│                              │
│  Entities                    │
│  Business Rules              │
│  Domain Logic                │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│    Infrastructure Layer      │
│                              │
│  Entity Framework Core       │
│  Authentication Services     │
│  External Integrations       │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│        PostgreSQL            │
└──────────────────────────────┘