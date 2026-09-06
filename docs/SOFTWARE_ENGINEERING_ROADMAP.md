# SkillForge Software Engineering Roadmap

## 1. Purpose

This roadmap defines the technical skills and engineering knowledge required to build SkillForge as a modern production-oriented learning and skills management platform.

SkillForge will be used as a practical environment for learning and applying professional software engineering practices.

The primary technology direction is:

- C#
- .NET
- ASP.NET Core
- PostgreSQL
- Entity Framework Core
- Next.js
- React
- TypeScript
- Docker
- Automated testing
- CI/CD
- Cloud deployment

The goal is not simply to learn individual technologies.

The goal is to become capable of designing, building, testing, deploying, and maintaining production software.

---

# Phase 1 — Software Engineering Foundations

## Goal

Build strong programming and software engineering fundamentals.

### Topics

- Programming fundamentals
- Object-oriented programming
- SOLID principles
- Separation of concerns
- Dependency management
- Error handling
- Debugging
- Logging
- Data structures and algorithms
- HTTP fundamentals
- REST API fundamentals
- Software architecture basics

### Practical Work

- Build small C# applications
- Practice debugging problems
- Write clean functions and classes
- Refactor poorly structured code
- Learn to read unfamiliar codebases

### SkillForge Application

Use these principles when creating:

- Domain models
- Application services
- API controllers
- Database repositories
- Frontend components

### Completion Criteria

You can explain why code belongs in a particular layer and identify tightly coupled or poorly structured code.

---

# Phase 2 — C# and .NET

## Goal

Become comfortable building backend applications using C# and .NET.

### Learn

- C# syntax
- Classes and interfaces
- Records
- Generics
- Collections
- LINQ
- Async and await
- Exceptions
- Dependency injection
- Configuration
- Logging
- .NET project structure

### Practical Work

- Build console applications
- Build small APIs
- Practice asynchronous programming
- Create reusable services

### SkillForge Application

Begin implementing:

- Users
- Courses
- Enrollments
- Learning content

### Completion Criteria

You can create a well-structured .NET application without copying code blindly.

---

# Phase 3 — ASP.NET Core APIs

## Goal

Build secure and maintainable backend APIs.

### Learn

- ASP.NET Core application structure
- Controllers and endpoints
- Routing
- Request and response models
- Dependency injection
- Middleware
- Validation
- Exception handling
- Authentication
- Authorization
- API versioning concepts
- OpenAPI and Swagger

### Practical Work

Build APIs for:

- Users
- Courses
- Enrollments
- Learning content
- Progress

### SkillForge Application

Create the initial SkillForge backend API.

### Completion Criteria

The frontend can communicate with a documented backend API.

---

# Phase 4 — Database and PostgreSQL

## Goal

Learn to design and manage reliable application data.

### Learn

- Relational database design
- Tables and relationships
- Primary and foreign keys
- Indexes
- SQL fundamentals
- PostgreSQL
- Database normalization
- Transactions
- Query performance basics

### Entity Framework Core

Learn:

- DbContext
- Entity configuration
- Migrations
- Relationships
- Queries
- Tracking
- Performance considerations

### SkillForge Application

Design the initial database models for:

- Users
- Roles
- Courses
- Categories
- Enrollments
- Course modules
- Lessons
- Assessments
- Questions
- Submissions
- Progress

### Completion Criteria

The SkillForge backend can persist and retrieve application data reliably.

---

# Phase 5 — Backend Architecture

## Goal

Build maintainable backend architecture.

### Learn

- Clean Architecture concepts
- Domain-driven design basics
- Application layer
- Domain layer
- Infrastructure layer
- Dependency inversion
- Repository patterns
- Service patterns
- Domain models
- DTOs
- Mapping

### SkillForge Application

Organize the backend around:

```text
Backend
│
├── SkillForge.API
├── SkillForge.Application
├── SkillForge.Domain
└── SkillForge.Infrastructure