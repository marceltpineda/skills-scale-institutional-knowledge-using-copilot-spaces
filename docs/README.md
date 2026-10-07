# OctoAcme Project Management Docs

## Overview

OctoAcme delivers projects using a structured, customer-first approach based on these core principles:

- Customer-first: Prioritize customer value and usability
- Iterative delivery: Deliver small, testable increments
- Clear ownership: Each project has a named Project Manager and Product Lead
- Data-informed decisions: Measure impact and iterate based on evidence
- Psychological safety: Encourage feedback and learning

## How OctoAcme Runs Projects

OctoAcme’s project management approach is built around a clear lifecycle: initiate, plan, execute, release, and close with a retrospective. At the start of a project, teams validate the business problem, stakeholder alignment, and measurable success criteria through a project one-pager and decision gate before moving into planning. Planning then breaks work into prioritized backlog items with acceptance criteria, estimates, owners, and milestones, while also documenting the Definition of Done, dependencies, and release plan. This makes the work actionable and ensures that projects are launched with shared expectations rather than vague goals.

The operating model also defines key roles and responsibilities so work is coordinated across functions. Product managers define outcomes and prioritize the backlog, project managers coordinate schedules, risks, communication, and documentation, and developers, QA, and stakeholders contribute to implementation, validation, and approval. Each project should have clear ownership, a named PM and Product Lead, and common artifacts such as the project charter, roadmap, risk register, and retrospective notes. This keeps accountability visible and supports cross-functional alignment across delivery and business stakeholders.

Communication is a continuous rhythm rather than a one-off activity. OctoAcme uses daily or twice-weekly standups, weekly PM/Product syncs, monthly stakeholder updates, and demos or reviews at sprint or milestone boundaries. It also specifies escalation paths for blockers, from team triage to PM escalation, Product Lead escalation, and sponsor-level involvement for business-critical issues. Risk and dependency communication is captured in a single source of truth, such as a project README or release doc, with clear status reporting and stakeholder updates to avoid confusion and delayed decisions.

Quality assurance is treated as an integral part of delivery, not a final afterthought. The process requires unit tests for new logic, integration tests where appropriate, smoke tests for critical flows before release, security scanning in CI, and manual QA for feature acceptance when needed. Release and deployment standards add pre-release requirements, deployment checklists, rollback plans, and post-deploy verification, while retrospectives ensure lessons learned are turned into action items and tracked in the backlog. Together, these practices create a disciplined, repeatable project system focused on delivery quality, team visibility, and continuous improvement.

## Project Lifecycle

All OctoAcme projects follow this high-level lifecycle:

1. Initiation — Validate the business need, align stakeholders, and confirm go/no-go
2. Planning — Break work into shippable increments, identify dependencies and risks
3. Execution — Build, test, review, and iterate with daily standups and progress tracking
4. Release — Deploy to production with safety checks, verification, and announcements
5. Close & Retrospective — Capture learnings and convert them into actionable improvements

## Quick Start by Project Phase

- Starting a new project? Begin with [Project Initiation Guide](octoacme-project-initiation.md)
- Ready to plan? See [Project Planning](octoacme-project-planning.md)
- In active delivery? Reference [Execution & Tracking](octoacme-execution-and-tracking.md)
- Preparing for release? Check [Release & Deployment Guide](octoacme-release-and-deployment.md)
- Project complete? Run a [Retrospective](octoacme-retrospective-and-continuous-improvement.md)

## Core Roles

See [OctoAcme Personas](octoacme-roles-and-personas.md) for detailed role definitions:

- Project Manager (PM): Coordinates delivery, schedules, risks, and communications
- Product Manager (PdM): Defines outcomes, prioritizes backlog, and measures success
- Developers: Implement features, collaborate on design and testability
- QA/Testing: Validates quality and acceptance criteria
- Stakeholders: Provide inputs, approvals, and strategic direction

## Full Documentation Index

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme’s approach, roles, and key artifacts |
| [Project Initiation](octoacme-project-initiation.md) | Validate ideas, align stakeholders, and create a lightweight plan with go/no-go decision |
| [Project Planning](octoacme-project-planning.md) | Break work into shippable increments, identify dependencies, and establish release timeline |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution, progress tracking, team rhythm, and quality standards |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, track, and communicate risks, dependencies, and stakeholder updates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardize release processes, deployment checklists, rollback plans, and verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, identify action items, and drive improvements |
| [Personas & Roles](octoacme-roles-and-personas.md) | Detailed role definitions and responsibilities across the organization |

## Getting Started

New to OctoAcme? Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, principles, and key artifacts.

Have a new project idea? Follow the [Project Initiation](octoacme-project-initiation.md) guide to validate the business need, align stakeholders, and make a go/no-go decision.

Need to know your role? Check [Personas & Roles](octoacme-roles-and-personas.md) to understand responsibilities and communication patterns.

Looking for a specific process? Use the documentation index above to find guidance for your project phase.

---

These docs are living artifacts. For suggestions, updates, or clarifications, open a GitHub issue using the Add Content to Project Management Process Docs template.
