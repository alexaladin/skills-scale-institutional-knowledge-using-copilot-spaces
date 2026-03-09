# OctoAcme Project Management Docs

## Purpose

This README serves as the single entry point for all OctoAcme project management documentation. It provides a standardized starting point for discovery, improves onboarding for new team members, and clarifies relationships between process documents. Whether you are a Project Manager, Product Manager, Developer, or QA engineer, start here to navigate the full documentation suite.

---

## Project Management Process Overview

OctoAcme operates on a structured five-stage project lifecycle that emphasizes iterative delivery and clear decision gates. The process begins with **Initiation**, where teams validate business need and create a lightweight Project One-pager defining the problem, objectives, and success metrics. This moves into **Planning**, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and dependency mapping. The **Execution** phase leverages GitHub Projects for workflow management (Backlog → Ready → In Progress → In Review → QA → Done) with daily standups, weekly delivery syncs, and a pull request discipline requiring small PRs (≤400 lines), CI automation, and at least one approval before merging. **Release & Deployment** follows standardized practices with pre-release requirements including passing security scans, smoke tests, and documented rollback plans. Finally, **Retrospectives & Continuous Improvement** capture learnings and convert them into actionable improvements tracked across sprints.

OctoAcme defines clear role ownership across four primary personas: **Project Managers** coordinate delivery, manage schedules, risks, and stakeholder communications; **Product Managers** define what to build, prioritize backlogs, and measure outcomes; **Developers** implement features, write tests, and identify technical risks; and **QA/Testing** validates quality and acceptance criteria. Communication is structured through a weekly sync between PM and Product Manager, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations. This communication cadence ensures alignment while maintaining psychological safety and encouraging feedback throughout the project.

Quality is embedded throughout execution with unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. Risk management follows a disciplined approach: risks are identified during planning and ongoing execution, assessed for impact and likelihood, tracked in a Risk Register with mitigation plans, and reviewed weekly. Escalation occurs in three levels—team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. This multi-layered approach ensures blockers are surfaced quickly and resolved at the appropriate level, supporting both speed and organizational alignment.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management principles, core roles, key artifacts, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to kick off a new project: problem statement, stakeholders, goals, and the Project One-pager |
| [Project Planning](octoacme-project-planning.md) | Scope definition, backlog creation, milestone planning, and dependency mapping |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | GitHub Projects board usage, pull request discipline, standups, and delivery syncs |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk Register, mitigation strategies, escalation paths, and stakeholder communication |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, smoke testing, and rollback procedures |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action item tracking, and how learnings feed back into the process |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for each team role |
