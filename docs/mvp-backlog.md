# SkillForge MVP Backlog

## 1. Purpose

This backlog converts the SkillForge MVP scope into concrete product and engineering work.

Work will be prioritized based on its importance to the core learner journey.

### Priority Levels

- **P0 — Must Have:** Required for the MVP.
- **P1 — Important:** Valuable after the core learner journey works.
- **Later:** Not part of the initial MVP implementation.

---

# P0 — Core MVP Features

## P0-1: Project Foundation and Local Development Environment

### Goal

Create a reproducible local development environment and establish the initial SkillForge application structure.

### Tasks

- Create frontend application structure
- Create ASP.NET Core backend solution
- Configure PostgreSQL for local development
- Configure Docker-based local services where appropriate
- Define environment configuration
- Document local startup process
- Define initial API communication between frontend and backend
- Verify database connectivity
- Verify frontend and backend startup

### Done When

A developer can start the frontend, backend, and database using the documented local development process.

---

## P0-2: Public Landing Page

### Goal

Provide a professional public entry point for SkillForge.

### Tasks

- Define landing page structure
- Implement SkillForge branding
- Add navigation
- Add authentication entry points
- Add responsive design
- Add platform information
- Link users to course discovery

### Done When

A visitor can understand what SkillForge is and navigate to available courses.

---

## P0-3: Course Discovery

### Goal

Allow visitors and learners to discover available courses.

### Tasks

- Define the course domain model
- Create course database entities
- Create course API endpoints
- Implement course listing
- Implement course categories
- Implement course details
- Add basic course search
- Display course information in the frontend

### Done When

A visitor can browse, search, and view available courses.

---

## P0-4: Authentication and Onboarding

### Goal

Allow users to create accounts and securely access SkillForge.

### Tasks

- Define the user domain model
- Implement user registration
- Implement login
- Implement logout
- Implement password security
- Implement authentication tokens or sessions
- Implement basic authorization
- Create basic user profiles
- Define learner roles
- Define initial onboarding
- Test registration and login flows

### Done When

A new learner can create an account, log in securely, and access authorized areas of the platform.

---

## P0-5: Course Enrollment

### Goal

Allow learners to enroll in available courses.

### Tasks

- Define enrollment domain model
- Create enrollment database entities
- Create enrollment API endpoints
- Implement course enrollment
- Validate enrollment requests
- Track enrollment status
- Restrict course access based on enrollment
- Test enrollment workflows

### Done When

A learner can successfully enroll in and access an authorized course.

---

## P0-6: Learning Content and Learning Experience

### Goal

Provide the core learning experience.

### Tasks

- Define course content structure
- Define course modules and lessons
- Create content database entities
- Create learning content API endpoints
- Display learning materials
- Implement lesson navigation
- Implement learning activities
- Support basic content types
- Restrict content access based on enrollment

### Done When

A learner can access and navigate structured learning content inside an enrolled course.

---

## P0-7: Assessments

### Goal

Allow learners to complete basic assessments.

### Tasks

- Define assessment domain model
- Create assessment database entities
- Create basic assessment types
- Implement questions and answers
- Implement assessment submissions
- Store assessment results
- Display assessment results
- Define basic passing rules

### Done When

A learner can complete a basic assessment and view the recorded result.

---

## P0-8: Student Progress Tracking

### Goal

Allow learners to understand their learning progress.

### Tasks

- Define progress tracking model
- Track lesson completion
- Track learning activity completion
- Track assessment completion
- Calculate course progress
- Store learner progress
- Display progress in the learner experience
- Track course completion status

### Done When

A learner can see accurate progress and completion information.

---

## P0-9: Student Dashboard

### Goal

Provide learners with a clear overview of their learning activity.

### Tasks

- Display enrolled courses
- Display course progress
- Display completion status
- Display upcoming learning activities
- Display recommended next actions

### Done When

A learner can quickly understand their current learning status after logging in.

---

## P0-10: MVP End-to-End Testing

### Goal

Verify the complete learner journey.

### Test Journey

1. Visitor opens SkillForge.
2. Visitor discovers a course.
3. Visitor creates an account.
4. Learner logs in.
5. Learner enrolls in a course.
6. Learner accesses course content.
7. Learner completes learning activities.
8. Learner completes an assessment.
9. Progress is recorded.
10. Course completion is recorded.

### Tasks

- Test frontend and backend integration
- Test authentication flow
- Test authorization
- Test enrollment flow
- Test course access restrictions
- Test learning content access
- Test assessment submissions
- Test progress tracking
- Test course completion
- Document test results

### Done When

The complete learner journey works reliably from start to finish.

---

# P1 — Important Features

## P1-1: Improved Student Dashboard

- Improved course overview
- Better progress visualization
- Upcoming activities
- Personalized learning information
- Recent learning activity

## P1-2: Instructor Experience

- Instructor course management
- Learning content management
- Learner progress monitoring
- Assessment management
- Learner submission review

## P1-3: Academy Administration

- User management
- Instructor management
- Course management
- Enrollment management
- Administrative workflows

## P1-4: Basic Reporting

- Enrollment reports
- Course completion reports
- Learner progress reports
- Assessment performance reports

## P1-5: Notifications

- Enrollment notifications
- Course activity notifications
- Assessment notifications
- Completion notifications

---

# Later Features

The following features are intentionally postponed:

- Payment integration
- Certificates
- AI learning assistant
- Mobile application
- Instructor marketplace
- Organization accounts
- Enterprise training features
- Advanced analytics
- Advanced learning recommendations
- Advanced learning paths
- Advanced skills intelligence
- Third-party integrations

---

# MVP Implementation Order

The recommended implementation order is:

1. Project Foundation and Local Development Environment
2. Public Landing Page
3. Course Discovery
4. Authentication and Onboarding
5. Course Enrollment
6. Learning Content and Learning Experience
7. Assessments
8. Student Progress Tracking
9. Student Dashboard
10. MVP End-to-End Testing

The team should complete and verify each major stage before adding advanced features.

The core priority is always the complete learner journey:

> Discover → Register → Login → Enroll → Learn → Assess → Track Progress → Complete