# SkillForge Architecture

## 1. Project Overview

SkillForge is a professional learning platform built on Moodle 4.5.

The goal of the project is to create a production-oriented Moodle platform while using the project as a practical environment for learning and demonstrating professional Moodle development.

SkillForge will use Moodle's existing LMS functionality and extend it through custom plugins, themes, configuration, integrations, and frontend development.

The project will prioritize security, maintainability, testing, version control, and production deployment.

## 2. Technology Stack

- Moodle 4.5 LTS
- PHP
- MariaDB/MySQL
- JavaScript
- HTML
- CSS
- Mustache templates
- Moodle APIs
- Git
- GitHub
- Docker
- PHPUnit
- Behat
- Linux
- Nginx or Apache
- Cloud deployment

## 3. Moodle 4.5 Role

Moodle 4.5 will be the core LMS platform for SkillForge.

Moodle will provide the core functionality for:

- User management
- Authentication
- Roles and permissions
- Courses
- Enrolments
- Activities
- Assessments
- Grades
- Completion
- Learning management

SkillForge will extend Moodle rather than modifying Moodle core whenever possible.

## 4. Custom Development

Custom functionality will be implemented using Moodle's supported extension mechanisms.

The project may include:

- Custom Moodle plugins
- Custom theme
- Custom landing page
- Custom dashboards
- Custom reports
- Custom integrations
- Custom administrative functionality

Moodle core files should not be modified unless there is a documented and unavoidable reason.

## 5. Plugin Strategy

Custom functionality will be developed as Moodle plugins when appropriate.

The project will learn and use different Moodle plugin types where they provide a suitable architectural solution.

Potential plugin types include:

- Local plugins
- Block plugins
- Report plugins
- Activity modules
- Admin tools
- Themes
- Other Moodle plugin types when required

Each plugin should follow Moodle development standards and use Moodle APIs rather than bypassing the platform architecture.

## 6. Landing Page

SkillForge will have a custom public-facing landing page.

The landing page will provide:

- SkillForge branding
- Course discovery
- Course information
- Search and filtering
- Authentication links
- Responsive design

The landing page should integrate with Moodle without modifying Moodle core unnecessarily.

## 7. Development Environment

Development will initially be performed locally.

The project will use Docker to create a reproducible development environment.

The development environment will eventually include:

- Moodle
- PHP
- Database
- Web server
- Moodledata
- Required development tools

Development configuration will remain separate from production configuration.

## 8. Git and GitHub Strategy

Git will be used for version control.

GitHub will host the SkillForge repository.

The project will use:

- Main branch
- Feature branches when appropriate
- Meaningful commits
- Pull requests when appropriate
- GitHub Issues
- GitHub Actions
- Version tags for releases

Changes should be committed in small, understandable units.

## 9. Testing Strategy

The project will use automated testing where appropriate.

Testing will include:

- PHPUnit
- Behat
- Plugin-specific tests
- Integration testing
- Security testing

Tests should be developed alongside important custom functionality.

## 10. Deployment Strategy

SkillForge will eventually be deployed to a production server or cloud environment.

The deployment process will include:

- Production Moodle configuration
- Database configuration
- Secure environment configuration
- HTTPS
- Moodle cron
- File permissions
- Database backups
- Moodledata protection
- Logging
- Monitoring
- Deployment automation

Production deployment should be reproducible and documented.