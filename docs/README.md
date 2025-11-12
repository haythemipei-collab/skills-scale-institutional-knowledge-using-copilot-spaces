# OctoAcme Project Management Docs

This folder centralizes OctoAcme's program and project management processes, templates, and checklists to help teams run repeatable, visible, and measurable delivery. These docs describe how we take initiatives from idea to production — covering initiation, planning, execution, release, and continuous improvement — and link to the process-level artifacts teams should maintain in each project repository.

OctoAcme follows a lightweight, stage-based lifecycle with clear decision gates and artifacts: a Project One‑pager for alignment, a prioritized and estimated backlog for planning, a project board and PR workflow for execution, a release plan and rollback playbook for deployment, and retrospectives with tracked action items for continuous improvement. Work is delivered iteratively with an emphasis on small, testable increments and evidence-driven decisions against defined success metrics.

Roles and responsibilities are explicit: Product Managers own outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, and communications; Developers implement and test features; QA validates acceptance and release readiness; and Stakeholders receive regular status updates. Communication follows a predictable cadence (daily standups, weekly delivery syncs, monthly stakeholder updates) and uses a single source of truth (project README / release doc) to keep messaging consistent.

Quality assurance and release controls are embedded throughout execution. Teams are expected to use automated CI (unit/integration/security scans), follow a pull request process with acceptance criteria and small change sizes, run smoke tests in staging, and follow the rollback/incident playbook if needed. Retrospectives convert learnings into prioritized backlog action items tracked to completion to reduce repeat issues.

Process document links
- Project Management Overview: ./docs/octoacme-project-management-overview.md
- Project Initiation Guide: ./docs/octoacme-project-initiation.md
- Project Planning: ./docs/octoacme-project-planning.md
- Execution & Tracking: ./docs/octoacme-execution-and-tracking.md
- Risks & Communication: ./docs/octoacme-risks-and-communication.md
- Release & Deployment: ./docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement: ./docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: ./docs/octoacme-roles-and-personas.md

Notes
- Templates for issue-driven process updates live in .github/ISSUE_TEMPLATE/.
- Keep the Project One-pager and release docs updated in the project repo to serve as the single source of truth.
