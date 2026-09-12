# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This folder contains all the processes, checklists, and guidance needed to successfully plan and deliver projects at OctoAcme.

## Quick Start

**New to OctoAcme?** Start here: [Project Management Overview](./octoacme-project-management-overview.md)

## Documentation by Project Phase

### 1. Initiation
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, decide go/no-go

### 2. Planning
- [Project Planning](./octoacme-project-planning.md) — Break work into increments, identify risks, align timelines

### 3. Execution
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day delivery, track progress, escalate blockers

### 4. Release
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize releases, reduce risk, improve observability

### 5. Retrospective & Continuous Improvement
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings, convert to action items

## Cross-cutting Topics

- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, assess, and mitigate risks; communicate with stakeholders
- [Roles and Personas](./octoacme-roles-and-personas.md) — Core roles, responsibilities, and communication patterns

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Project Lifecycle Overview

1. **Initiation**: Define problem, goals, success metrics, and stakeholders
2. **Planning**: Scope work, estimate, identify dependencies, create backlog
3. **Execution**: Build, test, review, and iterate on features
4. **Release**: Deploy to production, verify, announce
5. **Close & Retrospective**: Capture learnings and continuous improvements

---

## OctoAcme Project Management Processes: Executive Summary

OctoAcme operates a structured yet iterative project management approach centered on five core lifecycle phases: Initiation, Planning, Execution, Release, and Retrospective. The process begins with a lightweight Project Initiation phase where new ideas are validated through a One-pager that captures the problem statement, success metrics, stakeholders, and resource needs. Once stakeholders and a sponsor align on business value and priority, the project moves into Planning, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a Definition of Done is established. This structured approach ensures clarity upfront while maintaining flexibility for iterative delivery—a core principle that emphasizes small, testable increments over large batches of work.

Execution at OctoAcme is governed by a consistent team rhythm and clear workflows designed to maintain momentum and transparency. The team operates with daily standups (15 minutes), weekly delivery syncs, and regular demos at sprint or milestone completion. Work flows through a project board using columns (Backlog, Ready, In Progress, In Review, QA, Done), and pull requests are kept small (≤400 lines when possible) with required CI checks and at least one approval before merge. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance. Risk and dependencies are actively managed through a Risk Register tracked in weekly syncs, with clear escalation paths from team-level triage through PM, Product Lead, and ultimately Sponsor-level escalation for business-critical issues.

The organizational structure leverages three primary roles working in concert: Project Managers coordinate delivery, timelines, and stakeholder communication; Product Managers define outcomes, prioritize the backlog, and measure success; and Developers implement features while contributing to design, testing, and risk identification. Communication happens through weekly PM-PdM syncs, twice-weekly standups, and monthly stakeholder updates, with a single source of truth (project README or release docs) to ensure alignment. This clarity of roles and structured communication prevents confusion and keeps all parties informed of progress, risks, and decisions.

Release and continuous improvement complete the cycle. Before deployment, OctoAcme requires all acceptance criteria to be met, CI and security scans to pass, release notes to be drafted, and a rollback plan to be documented. Smoke tests are run in staging before production deployment, and post-deploy verification occurs before announcing to stakeholders. Finally, retrospectives are held after each sprint, release, or milestone to capture what went well, identify improvements, and convert insights into action items with clear owners and timelines. This blameless, continuous improvement mindset ensures the team learns and evolves its processes based on evidence, reinforcing OctoAcme's core principles of customer focus, iterative delivery, clear ownership, and data-informed decision-making.
