# SkillForge MVP Scope

## 1. MVP Goal

The goal of the first SkillForge version is to provide a complete and reliable learning journey for a learner.

A learner should be able to:

1. Discover a course.
2. Create an account or log in.
3. Enroll in a course.
4. Access course content.
5. Complete learning activities.
6. Complete assessments.
7. Track learning progress.
8. Complete the course.

The MVP should focus on making this journey work reliably before adding advanced features.

---

## 2. Features Included in the MVP

### 2.1 Public Experience

The MVP will include:

- SkillForge landing page
- Course discovery
- Course categories
- Course search
- Course details
- Login and registration entry points

### 2.2 Authentication and Onboarding

The MVP will include:

- User registration
- Login
- Logout
- Password management
- Account authentication
- Basic user profiles
- Initial onboarding
- Role-based access control

Authentication and authorization will be implemented through the SkillForge backend.

### 2.3 Course Management

The MVP will provide the foundation for:

- Creating courses
- Managing course information
- Organizing course content
- Publishing courses
- Managing course availability

The first version should keep course management simple and focused on supporting the learner journey.

### 2.4 Enrollment

The MVP will include:

- Course enrollment
- Enrollment validation
- Enrollment status
- Course access control

A learner should only access courses they are authorized to access.

### 2.5 Learning Experience

The MVP will include:

- Course access
- Learning content
- Learning materials
- Learning activities
- Basic assessments
- Assessment results
- Progress tracking
- Course completion

The learning experience should support a structured course journey without introducing unnecessary complexity.

### 2.6 Student Dashboard

The MVP will provide a learner-focused dashboard showing:

- Enrolled courses
- Learning progress
- Course completion status
- Upcoming activities
- Recommended next actions

---

## 3. Features Not Included in the MVP

The following features are intentionally postponed:

- Payment integration
- Certificates
- Instructor marketplace
- Multi-organization accounts
- Advanced analytics
- Mobile applications
- AI learning assistant
- Complex learning paths
- Advanced recommendation systems
- Advanced skills intelligence
- Enterprise integrations

These features may be considered after the core learning journey is stable.

---

## 4. MVP Technical Approach

The MVP will follow these principles:

1. Build SkillForge as an independent application.
2. Use Next.js for the primary frontend application.
3. Use ASP.NET Core for backend APIs and application services.
4. Use PostgreSQL for persistent data.
5. Keep business logic in the backend.
6. Use APIs as the communication boundary between frontend and backend.
7. Keep the first version simple and maintainable.
8. Design modules with clear responsibilities.
9. Implement authentication and authorization securely.
10. Test important business functionality.
11. Avoid unnecessary infrastructure and architectural complexity.

---

## 5. MVP Success Criteria

The first version of SkillForge will be considered successful when:

- A visitor can discover available courses.
- A visitor can create an account.
- A learner can log in securely.
- A learner can enroll in a course.
- A learner can access authorized learning content.
- A learner can complete learning activities.
- A learner can complete basic assessments.
- Learning progress is recorded correctly.
- Course completion is tracked correctly.
- The frontend and backend communicate reliably through APIs.
- The platform runs reliably in the documented local development environment.

---

## 6. MVP Boundary

The MVP should solve one complete problem well:

> A learner can discover, enroll in, complete, and track progress in a course.

Any feature that does not directly support this journey should be evaluated carefully before being added to the MVP.

The goal is not to build every possible learning feature in the first version.

The goal is to build one complete, reliable learning workflow that provides a strong foundation for future product development.