# OctoAcme Project Management Docs

This directory contains the project management guidance for OctoAcme, a lightweight but structured approach for cross-functional delivery. The materials help teams align on goals, work in shared ways, and keep execution consistent from project initiation through retrospective and improvement.

## OctoAcme project management process

OctoAcme projects follow a clear lifecycle: initiate and validate the opportunity, plan scope and work, execute in visible increments, release with verification, and close with reflection. During initiation, teams confirm the business need, success metrics, stakeholders, resource needs, and risks in a one-pager. Once leaders agree on priority and feasibility, the project moves into planning, where the backlog is prioritized, milestones are mapped, and responsibilities, estimates, and dependencies are defined.

During execution, the team uses daily or regular standups, weekly delivery syncs, and milestone demos to track progress, identify blockers, and keep stakeholders informed. Work is managed through a project board with states such as Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests should stay small when feasible, include issue links and acceptance criteria, and pass tests and linting before review. Quality is enforced through unit tests for new logic, integration tests where relevant, smoke testing for critical paths, and manual QA when needed.

Communication is a core part of OctoAcme's operating model. The Project Manager and Product Manager align weekly, while the broader team participates in standup and sprint planning routines. Stakeholder updates are shared regularly, and risks and blockers are escalated through a defined chain from the team to the PM, Product Lead, and sponsor when necessary. This is paired with a strong emphasis on evidence-informed decision-making, customer value, and psychological safety so that problems are surfaced early and improvements are acted on without blame.

At release time, work is only moved to production when acceptance criteria are met, CI and security checks are passing, and rollback or mitigation plans are documented. After the release, teams close out with a retrospective to capture wins, identify improvements, and assign action items with clear owners and due dates. These practices create a repeatable way to deliver software and services while keeping quality, accountability, and learning embedded throughout the project lifecycle.

## Document index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Core roles

- Project Manager (PM): coordinates delivery, schedules, risks, and stakeholder communication.
- Product Manager (PdM): defines outcomes, priorities, and success metrics.
- Developers: design, build, test, and maintain working software.
- QA/Testing: validates quality and acceptance criteria.
- Stakeholders: provide input, approvals, and business context.

## Principles

- Customer-first thinking
- Iterative delivery in small, testable increments
- Clear ownership and accountability
- Data-informed decisions and measurable outcomes
- Psychological safety and continuous improvement
