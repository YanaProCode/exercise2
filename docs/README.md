# OctoAcme Project Management Docs

This directory is the single discoverable index for OctoAcme's program and project management process documents. It provides short summaries and links to the full process guides used across initiation, planning, execution, release, and continuous improvement.

OctoAcme runs projects using a clear stage-based lifecycle: Initiation to validate the problem, stakeholders, and success metrics via a concise project one-pager; Planning to turn approved work into a prioritized, estimated backlog with a Definition of Done and a risk register; Execution and Tracking to deliver work using a project board (Backlog 16 Ready 16 In Progress 16 In Review 16 QA 16 Done), a disciplined PR workflow, and a regular team cadence; Release & Deployment to standardize pre-release checks, automated pipelines, smoke tests, and rollback plans; and Retrospective & Continuous Improvement to capture learnings, convert them into tracked action items, and measure impact.

Roles and responsibilities are clearly defined so ownership and decision-making are explicit: Product Managers focus on outcomes and success metrics, Project Managers coordinate delivery and communications, Developers implement and test, and QA validates acceptance criteria. These personas are used to assign owners for artifacts such as the one-pager, risk register, release notes, and retrospective action items, and to guide estimates, reviews, and escalations.

Quality assurance and communication are embedded into the process. The team uses daily standups and regular delivery syncs to surface blockers and dependencies, scheduled demos and stakeholder updates to maintain alignment, and CI-driven testing (unit, integration, and security scans) plus manual QA and end-to-end smoke tests for critical flows. Metrics (velocity, burndown, errors, latency, usage dashboards) are used to monitor health, guide decisions, and inform continuous improvements captured in retrospectives.

## Documents
- [Project Management Overview](./octoacme-project-management-overview.md) 16 overview of principles, lifecycle, roles, and artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) 16 one-pager template and initiation checklist
- [Project Planning](./octoacme-project-planning.md) 16 backlog templates, sprint planning, and risk register guidance
- [Execution & Tracking](./octoacme-execution-and-tracking.md) 16 team rhythm, PR workflow, and tracking guidance
- [Release & Deployment](./octoacme-release-and-deployment.md) 16 release checklist, deployment steps, and rollback playbook
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) 16 retro structure and action item tracking
- [Risk Management & Communication](./octoacme-risks-and-communication.md) 16 risk register and stakeholder templates
- [Roles & Personas](./octoacme-roles-and-personas.md) 16 role definitions used across documents

## How to propose updates
Use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ to propose additions or edits so changes can be reviewed and tracked.
