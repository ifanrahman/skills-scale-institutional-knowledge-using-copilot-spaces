# OctoAcme Project Management Documentation

## Overview
This folder contains the complete project management playbook for OctoAcme. These documents define how we plan, initiate, plan, execute, release, and continuously improve our delivery across projects. Use this README as the single-entry point to find process guidance and recommended artifacts for each stage of the project lifecycle.

## Core Principles
- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments and learn quickly.
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage candid feedback and learning.

## Project Management Documents
- [Project Management Overview](octoacme-project-management-overview.md)
  - High-level introduction to OctoAcme's approach, roles, key artifacts, and lifecycle.
- [Project Initiation](octoacme-project-initiation.md)
  - Steps to validate and authorize new projects, align stakeholders, and create a lightweight plan.
- [Project Planning](octoacme-project-planning.md)
  - How to turn approved initiatives into actionable plans, prioritized backlogs, and release timelines.
- [Execution & Tracking](octoacme-execution-and-tracking.md)
  - Day-to-day execution guidance, team rhythm, and tracking conventions.
- [Risk Management & Communication](octoacme-risks-and-communication.md)
  - Guidance for identifying, assessing, and communicating risks and dependencies.
- [Release & Deployment](octoacme-release-and-deployment.md)
  - Standardized release checklist, deployment steps, and rollback playbooks.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
  - How to run retrospectives and convert learnings into tracked improvements.
- [Roles & Personas](octoacme-roles-and-personas.md)
  - Role definitions and responsibilities for Developers, Product Managers, and Project Managers.

## Quick Navigation by Scenario
- Starting a new project → [Project Initiation](octoacme-project-initiation.md)
- Planning work or a release → [Project Planning](octoacme-project-planning.md)
- Managing daily execution → [Execution & Tracking](octoacme-execution-and-tracking.md)
- Managing risk or stakeholder updates → [Risk Management & Communication](octoacme-risks-and-communication.md)
- Preparing a release → [Release & Deployment](octoacme-release-and-deployment.md)
- Running a retrospective → [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Using these docs in Copilot Spaces
Copy these files (or the whole docs/ folder) into a `.copilot/` folder in a project repository to enable Copilot Spaces to surface relevant guidance and templates when working on project tasks.

## Brief overview of OctoAcme project management processes
OctoAcme follows a lightweight, outcome-driven lifecycle that begins with a focused initiation step: capture the problem, define measurable success, identify stakeholders, and decide whether to move into planning. Approved initiatives move into a planning phase where work is broken into shippable backlog items with clear acceptance criteria, estimates, and owner assignments. Planning produces a release map and Definition of Done that guide execution.

During execution, teams use a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) and maintain a regular rhythm of daily standups, weekly delivery syncs, and sprint demos. Pull requests are kept small, include acceptance criteria and issue links, and must pass automated CI checks and at least one review before merging. This approach reduces risk, keeps feedback loops short, and improves predictability.

Quality assurance combines automated testing (unit, integration, security scans) and targeted manual QA or smoke tests for critical flows. Releases follow a standardized checklist—staging verification, rollback plans, and post-deploy checks—with an incident playbook for rapid triage and rollback when necessary. Continuous improvement is enforced through retrospectives that produce prioritized action items tracked in the backlog and reviewed in weekly syncs.

Roles are clearly defined: Product Managers set vision and success metrics, Project Managers coordinate delivery and communications, Developers implement and test changes, and QA validates acceptance criteria. Communication follows a cadence that emphasizes transparency—daily standups, regular PM–PdM alignment, stakeholder updates, and clear escalation paths (team → PM → Product Lead → Sponsor) for blockers and incidents.
