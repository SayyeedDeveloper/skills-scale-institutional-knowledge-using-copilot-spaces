# OctoAcme Project Management Docs

This folder is the single source of truth for how OctoAcme plans, delivers and improves cross-functional projects. Start here for an overview of our project management processes, then follow the links to the detailed guides.

## Overview of OctoAcme's project management processes

OctoAcme runs projects through a five-stage lifecycle: **Initiation → Planning → Execution → Release → Retrospective**. Every project starts with a one-pager that states the problem, a SMART goal, success metrics, stakeholders and early risks. A decision gate moves the work into planning only when success metrics are clear, stakeholders agree on priority and the team is available. In planning, the work is broken into shippable increments with a prioritized, estimated backlog, a Definition of Done, a release plan and a risk register that tracks impact, likelihood, owner and mitigation.

Delivery is shared between clear roles. The **Project Manager** coordinates schedules, risks, dependencies and communication. The **Product Manager** owns outcomes, success metrics and backlog priority. **Developers** build, test and review the work, **QA** validates quality and acceptance criteria, and **stakeholders** provide input and approvals. Our principles are customer-first value, iterative delivery, clear ownership, data-informed decisions and psychological safety.

Day-to-day execution follows a steady rhythm: daily standups, a weekly delivery sync, a weekly PM and PdM sync, monthly stakeholder updates and a demo at the end of each sprint or milestone. Work moves across a project board (Backlog, Ready, In Progress, In Review, QA, Done). Blockers escalate in three levels, from the team to the Product Lead to the Sponsor. Status is reported with a standard weekly template, and incidents follow a defined communication and blameless-retrospective process.

Quality is built into every stage. Pull requests stay small, link their issue and acceptance criteria, and need passing CI (tests, linting and security scanning) plus at least one approval before merging. Releases require met acceptance criteria, release notes, smoke tests and a documented rollback plan, and they move through staging before production. After each sprint, release or incident, a retrospective turns learnings into two or three owned action items that feed back into the backlog, keeping these processes continuously improving.

## Process documents

| Document | What it covers |
| --- | --- |
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle and communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | Validating new work: one-pager template, initiation checklist and the go/no-go decision gate |
| [Project Planning](octoacme-project-planning.md) | Kickoff, backlog and estimation, Definition of Done, risks, dependencies and release planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythm, project board and PR workflow, testing, metrics and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register and lifecycle, stakeholder updates, status and incident templates, escalation paths |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback playbook and release notes |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and tracking improvement action items |
| [Roles & Personas](octoacme-roles-and-personas.md) | Responsibilities, goals and communication for each project role |

## Contributing

To propose a new process document or an update to an existing one, open an issue with the **Add Content to Project Management Process Docs** template in `.github/ISSUE_TEMPLATE/`.
