# OctoAcme Project Management Processes

## Purpose

The OctoAcme process documentation centralizes project management workflows and guidelines, transforming team knowledge into searchable, versioned artifacts for all members. These documents help standardize execution, accelerate onboarding, and reduce single-person dependency risks.

## Key Principles & Approach

OctoAcme's project management is customer-first, iterative, and data-informed. Work is delivered in small, testable increments through a structured five-phase lifecycle: Initiation, Planning, Execution, Release & Deployment, and Retrospective. Each project has a named Project Manager responsible for delivery coordination and a Product Manager focused on outcome definition and prioritization.

## Roles & Communication

- **Project Manager (PM):** Manages timelines, risks, and stakeholder communication.
- **Product Manager (PdM):** Owns product vision, outcomes, and prioritization.
- **Developers:** Build, test, and document features collaboratively.
- **QA/Testing:** Validate quality and acceptance criteria.
- **Stakeholders:** Provide input and approvals.

Communication occurs via daily standups, weekly PM/PdM syncs, and monthly stakeholder updates, with structured escalation for blockers.

## Core Workflows

Projects use a board with columns for Backlog, Ready, In Progress, In Review, QA, and Done. PRs must be small (≤400 lines), linked to issues, pass CI tests, and be reviewed before merging. Risks and dependencies are tracked with a register reviewed weekly. Releases follow a standardized checklist for quality and rollback safety. Retrospectives capture learnings and convert them to actions for continuous improvement.

## Quality Assurance & Continuous Improvement

Automated unit, integration, and smoke tests enforce quality, complemented with manual QA as needed. After each sprint or major release, teams run retrospectives to identify what went well and what could be improved, prioritizing action items for follow-up. Lessons and validated workflow refinements are fed back into living documentation to enable consistent, repeatable execution.

---

## Additional Documents

For details on each process area, see:

- `docs/octoacme-project-management-overview.md`
- `docs/octoacme-project-initiation.md`
- `docs/octoacme-project-planning.md`
- `docs/octoacme-execution-and-tracking.md`
- `docs/octoacme-risks-and-communication.md`
- `docs/octoacme-release-and-deployment.md`
- `docs/octoacme-retrospective-and-continuous-improvement.md`
- `docs/octoacme-roles-and-personas.md`