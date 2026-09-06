# SkillForge MVP Backlog

## 1. Purpose

This backlog converts the SkillForge MVP scope into concrete product and engineering work.

Work will be prioritized based on its importance to the core learner journey.

### Priority Levels

- **P0 — Must Have:** Required for the MVP.
- **P1 — Important:** Valuable but can be completed after the core journey works.
- **Later:** Not part of the initial MVP implementation.

---

# P0 — Core MVP Features

## P0-1: Local Development Environment

### Goal

Ensure SkillForge can run reliably in a reproducible local environment.

### Tasks

- Verify Docker environment
- Verify Moodle container
- Verify database container
- Verify Moodle installation
- Document local startup process
- Verify persistent Moodle data

### Done When

A developer can start SkillForge locally using the documented process.

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
- Link users to course discovery

### Done When

A visitor can understand what SkillForge is and navigate to available courses.

---

## P0-3: Course Discovery

### Goal

Allow visitors and learners to discover available courses.

### Tasks

- Display available courses
- Display course categories
- Add course information
- Add course search
- Link courses to Moodle course pages

### Done When

A visitor can browse and search available courses.

---

## P0-4: Authentication and Onboarding

### Goal

Allow users to create accounts and access SkillForge.

### Tasks

- Configure Moodle registration
- Configure login flow
- Configure user profiles
- Define initial onboarding experience
- Test registration and login

### Done When

A new learner can create an account and access the platform.

---

## P0-5: Course Enrollment

### Goal

Allow learners to enroll in available courses.

### Tasks

- Configure enrollment method
- Test learner enrollment
- Verify course access
- Handle enrollment permissions

### Done When

A learner can successfully enroll in and access a course.

---

## P0-6: Learning Experience

### Goal

Provide the core learning experience.

### Tasks

- Configure course format
- Add learning materials
- Add activities
- Configure assessments
- Configure grades
- Configure course completion

### Done When

A learner can complete learning activities inside a course.

---

## P0-7: Student Progress Tracking

### Goal

Allow learners to understand their learning progress.

### Tasks

- Enable activity completion
- Enable course completion
- Configure progress tracking
- Verify grades
- Verify completion status

### Done When

A learner can see accurate progress and completion information.

---

## P0-8: MVP End-to-End Testing

### Goal

Verify the complete learner journey.

### Test Journey

1. Visitor opens SkillForge.
2. Visitor discovers a course.
3. Visitor creates an account.
4. Learner logs in.
5. Learner enrolls in a course.
6. Learner accesses course content.
7. Learner completes activities.
8. Progress is recorded.
9. Course completion is recorded.

### Done When

The complete learner journey works reliably from start to finish.

---

# P1 — Important Features

## P1-1: Improved Student Dashboard

- Custom course overview
- Improved progress visualization
- Upcoming activities
- Personalized learning information

## P1-2: Instructor Experience

- Instructor workflow improvements
- Learner progress monitoring
- Assessment management improvements

## P1-3: Academy Administration

- Improved user management
- Enrollment management tools
- Administrative workflows

## P1-4: Basic Reporting

- Enrollment reports
- Course completion reports
- Learner progress reports

---

# Later Features

The following features are intentionally postponed:

- Payment integration
- Certificates
- AI learning assistant
- Mobile application
- Instructor marketplace
- Organization accounts
- Advanced analytics
- Advanced learning recommendations

---

# MVP Implementation Order

The recommended implementation order is:

1. Local Development Environment
2. Public Landing Page
3. Course Discovery
4. Authentication and Onboarding
5. Course Enrollment
6. Learning Experience
7. Student Progress Tracking
8. MVP End-to-End Testing

The team should complete and verify each stage before moving to advanced features.
