# OctoAcme Project Management Documentation Index

Welcome to the OctoAcme project management knowledge base. This collection centralizes our processes, roles, and checklists to make it easier for teams and stakeholders to find, follow, and contribute to our delivery practices.

## Brief Overview of OctoAcme Project Management Processes

OctoAcme runs projects through a clear, staged lifecycle that begins with lightweight initiation and moves through planning, execution, release, and retrospective. Initiation uses a Project One-pager to capture the problem, success metrics, stakeholders, and an initial timeline to inform a go/no-go decision. Planning breaks approved initiatives into shippable increments with prioritized backlogs, acceptance criteria, estimates, a Definition of Done, and a release plan.

Execution emphasizes small, reviewable changes and disciplined pull request practices: keep PRs small when possible, include issue links and acceptance criteria, run automated tests and linters in CI, and require approvals before merging. Day-to-day tracking uses a project board (Backlog, Ready, In Progress, In Review, QA, Done), daily standups for immediate blockers, and weekly delivery syncs to surface risks and dependencies. Release follows a standardized checklist (CI and security scans passing, release notes drafted, smoke tests run) and includes a rollback and incident playbook.

Roles and personas are explicitly defined to maintain clear ownership. Product Managers define outcomes and success metrics; Project Managers coordinate schedules, risks, and communications; Developers implement features, tests, and documentation; QA validates acceptance criteria and designs tests; stakeholders provide input and approvals. This role clarity reduces single-person dependencies and ensures owners are named for artifacts like the risk register and action items.

Communication and quality assurance are tightly integrated into the process. Teams follow a regular cadence (daily standups, weekly PM+PdM syncs, sprint demos/reviews, and monthly stakeholder updates) and use a single source of truth for status. Risk management uses a Risk Register and defined escalation paths. Quality gates include unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed; these are enforced via the Definition of Done and CI policies.

## Documentation Index
- Project Management Overview: [docs/octoacme-project-management-overview.md](docs/octoacme-project-management-overview.md)
- Project Initiation Guide: [docs/octoacme-project-initiation.md](docs/octoacme-project-initiation.md)
- Project Planning: [docs/octoacme-project-planning.md](docs/octoacme-project-planning.md)
- Execution & Tracking: [docs/octoacme-execution-and-tracking.md](docs/octoacme-execution-and-tracking.md)
- Risk Management & Communication: [docs/octoacme-risks-and-communication.md](docs/octoacme-risks-and-communication.md)
- Release & Deployment Guide: [docs/octoacme-release-and-deployment.md](docs/octoacme-release-and-deployment.md)
- Retrospective & Continuous Improvement: [docs/octoacme-retrospective-and-continuous-improvement.md](docs/octoacme-retrospective-and-continuous-improvement.md)
- Roles & Personas: [docs/octoacme-roles-and-personas.md](docs/octoacme-roles-and-personas.md)

## How to use and contribute
- Keep the README and each process doc up to date as decisions change.
- Use the issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes.
- For Copilot Spaces: add process-specific docs into `.copilot/` if you want them included as Space context.

---

*Acceptance criteria:*
- Content aligns with existing process docs
- Improves clarity and discoverability of the docs set

Relates to: #2
