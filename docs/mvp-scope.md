# SkillForge MVP Scope

## 1. MVP Goal

The goal of the first SkillForge version is to provide a complete learning journey for a learner.

A learner should be able to:

1. Discover a course.
2. Create an account or log in.
3. Enroll in a course.
4. Access course content.
5. Complete learning activities.
6. Track learning progress.
7. Complete the course.

The MVP should focus on making this journey work reliably before adding advanced features.

---

## 2. Features Included in the MVP

### 2.1 Public Experience

The MVP will include:

- SkillForge landing page
- Course discovery
- Course categories
- Course search
- Login and registration entry points

### 2.2 Authentication

The MVP will use Moodle's existing functionality for:

- User registration
- Login
- Password management
- User profiles

Custom authentication functionality will not be developed unless required.

### 2.3 Learning Experience

The MVP will include:

- Course enrollment
- Course access
- Learning materials
- Learning activities
- Assessments
- Grades
- Progress tracking
- Course completion

Moodle will provide most of this functionality.

### 2.4 Student Dashboard

The MVP will provide a learner-focused dashboard showing:

- Enrolled courses
- Learning progress
- Course completion status
- Upcoming activities

---

## 3. Features Not Included in the MVP

The following features are intentionally postponed:

- Payment integration
- Certificates
- Instructor marketplace
- Organization accounts
- Advanced analytics
- Mobile application
- AI learning assistant
- Complex learning paths
- Advanced recommendation systems

These features may be considered after the core learning journey is stable.

---

## 4. MVP Technical Approach

The MVP will follow these principles:

1. Use Moodle core functionality whenever possible.
2. Avoid modifying Moodle core.
3. Build custom functionality only when it provides clear product value.
4. Keep the first version simple and maintainable.
5. Use Moodle APIs and supported plugin architecture.
6. Test important custom functionality.

---

## 5. MVP Success Criteria

The first version of SkillForge will be considered successful when:

- A visitor can discover available courses.
- A visitor can create an account.
- A learner can enroll in a course.
- A learner can access learning content.
- A learner can complete activities.
- Learning progress is recorded correctly.
- Course completion is tracked correctly.
- The platform works reliably in the local Docker environment.

---

## 6. MVP Boundary

The MVP should solve one complete problem well:

> A learner can discover, enroll in, complete, and track progress in a course.

Any feature that does not directly support this journey should be evaluated carefully before being added to the MVP.
