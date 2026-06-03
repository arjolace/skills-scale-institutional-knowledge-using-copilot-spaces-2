# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains comprehensive guides for managing projects using the OctoAcme methodology.

## Quick Overview of OctoAcme Processes

### Core Philosophy and Lifecycle

OctoAcme operates on a structured, customer-first project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making. The organization divides project management into five distinct phases: Initiation (validating business need and stakeholder alignment), Planning (breaking work into shippable increments), Execution (day-to-day delivery and tracking), Release (standardized deployment to production), and Close & Retrospective (capturing learnings). This phased approach ensures that each project has a named Project Manager coordinating delivery and a Product Manager defining outcomes, with clear separation of concerns that reduces single-person dependency risk and accelerates onboarding.

### Key Roles, Communication, and Quality Practices

OctoAcme's success relies on well-defined personas—Developers who implement features and maintain quality standards, Product Managers who prioritize based on customer value and metrics, and Project Managers who coordinate schedules, risks, and communications. Communication happens through a consistent cadence: daily standups (15 minutes), weekly PM and PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. The organization maintains a single source of truth via GitHub Projects boards (organized into Backlog, Ready, In Progress, In Review, QA, and Done columns), project charters, and risk registers. Quality assurance is embedded throughout execution via unit and integration tests, security scanning in CI/CD pipelines, and end-to-end smoke tests before release, with manual QA for feature acceptance when needed.

### Risk Management and Execution Discipline

Risk management is proactive and continuous, with a Risk Register maintained throughout the project lifecycle (identifying, assessing, mitigating, and monitoring risks). Blockers follow a three-level escalation path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and finally sponsor-level escalation for business-impacting issues. Pull Request discipline is enforced (small PRs ≤400 lines, issue links, acceptance criteria in descriptions, at least one approval before merge) to maintain code quality and traceability. The organization also emphasizes psychological safety and continuous improvement through blameless retrospectives after each sprint, release, or significant milestone, with action items tracked and reviewed in weekly syncs to drive incremental process refinement.

## Documentation Structure

- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward project milestones
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how OctoAcme releases features to production
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Definitions of typical roles and responsibilities in OctoAcme projects

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
3. **In active delivery?** Reference the [Execution & Tracking](./octoacme-execution-and-tracking.md) guide
4. **Need to understand roles?** Review [Roles and Personas](./octoacme-roles-and-personas.md)

## Contributing to Process Documentation

To propose updates or add new content to these process documents, please use the issue template: **[Add Content to Project Management Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)**

---

*Last updated: 2026-06-03*
