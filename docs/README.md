# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This README provides a quick overview of how we run projects at OctoAcme, plus direct links to every detailed process guide in this folder. Whether you're onboarding to the team or looking for a specific workflow, start here.

## OctoAcme Project Management Process — Summary

OctoAcme follows a structured, lifecycle-driven approach to project delivery, moving work through five key phases: **Initiation, Planning, Execution, Release, and Retrospective**. Projects begin with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, and stakeholder alignment before any planning begins. Once approved through a decision gate, work is broken into shippable increments with a prioritized backlog, a Definition of Done, and a milestone map. Dependencies and risks are captured in a Risk Register — tracked with impact, likelihood, owner, and mitigation plan — and reviewed continuously throughout the project lifecycle.

Three core personas drive delivery at OctoAcme. **Project Managers** coordinate schedules, risks, and cross-team communication. **Product Managers** own the product vision, prioritize the backlog, and define success metrics. **Developers** implement features, write tests, participate in design reviews, and help identify technical risks. Supporting these roles are QA/Testing resources who validate acceptance criteria, and Stakeholders who provide inputs and approvals. Clear role ownership is a foundational principle — every project has a named PM and Product Lead to ensure accountability and minimize ambiguity.

OctoAcme's **communication cadence** is deliberately structured to keep teams aligned without creating overhead. Daily 15-minute standups focus on progress and blockers, weekly delivery syncs surface risks and updates, and monthly stakeholder reports maintain executive visibility. Risk escalation follows a defined path from team-level triage → PM → Product Lead → Sponsor, with a separate security incident runbook for sensitive issues. Status updates use a consistent template (progress, next steps, risks, decisions needed) to create a single source of truth across stakeholders.

**Execution quality and continuous improvement** are embedded throughout the process. The engineering workflow enforces small PRs (≤400 lines), automated CI with tests, linting, and security scanning, and at least one required code review approval before merging. Releases are gated by passing CI, completed smoke tests, documented rollback plans, and drafted release notes. After each sprint or milestone, structured retrospectives (45–75 minutes) surface what went well, what could improve, and 2–3 prioritized action items with clear owners and due dates — feeding improvements back into the backlog and keeping OctoAcme's processes continuously evolving.

## Principles

- Customer-first delivery
- Iterative development
- Clear ownership
- Data-driven decisions
- Psychological safety

## Process Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
