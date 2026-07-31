# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation and a short, discoverable entry point for contributors and new team members.

Overview

OctoAcme runs projects through a lightweight, repeatable lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Project initiation captures the problem, objective, success metrics, stakeholders, and a high-level timeline using a Project One-pager. Planning turns approved initiatives into prioritized, estimable backlog items with clear acceptance criteria and a release/milestone plan. Execution follows an explicit board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a pull request process that emphasizes small changes, CI/lint checks, linked issues, and reviewer approvals. Releases require passing CI and security scans, smoke testing in staging, and a rollback plan. Retrospectives and continuous improvement practices convert learnings into tracked action items.

Key Workflows & Practices

- Team rhythms: daily standups, weekly delivery syncs, PM+PdM syncs, demos at the end of sprints/milestones, and regular retrospectives.
- Roles: Product Managers (define outcomes and success metrics), Project Managers (coordinate delivery, schedules, and communications), Developers (implement and test), QA (validate acceptance criteria and run manual checks when required), and Stakeholders (input and approvals).
- Quality & Testing: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance as needed.
- Risk & Communication: maintain a Risk Register, follow escalation paths (team → PM → Product Lead → Sponsor), and use templated weekly and incident communication messages.

Docs index

- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — Overview and core roles
- [octoacme-project-initiation.md](./octoacme-project-initiation.md) — Project initiation guide and one-pager template
- [octoacme-project-planning.md](./octoacme-project-planning.md) — Planning steps, backlog templates, and checklists
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) — Execution workflows, PR conventions, and tracking
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) — Risk register template and communication cadence
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) — Release checklist and rollback playbook
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and action tracking
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Roles, responsibilities, and persona usage

How to use this folder

- Keep these docs up to date as the single source of truth for OctoAcme's processes.
- To propose changes, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/.
- For quick discovery, link this README from the repository root or project README if desired.
