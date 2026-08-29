# OctoAcme Project Management Processes

Welcome to the central documentation hub for OctoAcme project management processes. This README serves as the entry point for all process documentation, helping every team member quickly find the guidance they need.

---

## Overview

OctoAcme follows a structured five-stage project lifecycle — **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective** — grounded in a set of core principles: customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

### Key Workflows

During **Initiation**, teams validate business need through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and an initial risk assessment. The **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a shared Definition of Done.

**Execution** leverages GitHub Projects with standardized columns (Backlog → Ready → In Progress → In Review → QA → Done) and enforces small pull requests (≤ 400 lines) that include issue links and pass automated CI checks before requiring at least one approval. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, and security scanning in CI. Teams maintain a **Risk Register** (ID, description, impact, likelihood, owner, mitigation) reviewed weekly as risks are identified, assessed, mitigated, and monitored.

The **Release** phase requires passing CI/security checks, drafted release notes, and a documented rollback plan before deployment. Finally, the **Close & Retrospective** phase drives continuous improvement through post-sprint retrospectives (45–75 minutes) that capture what went well, identify improvements, and generate prioritized action items tracked in future planning cycles.

All projects are grounded in customer-first principles with success measured through defined metrics from the Project One-pager. Weekly status updates, shared dashboards (errors, latency, usage), and velocity/burndown tracking provide full visibility into progress, creating a repeatable, scalable approach that reduces single-person dependency risk and accelerates onboarding.

---

## Process Documents

### By Project Stage

| Stage | Document |
|-------|----------|
| Overview | [OctoAcme Project Management Overview](octoacme-project-management-overview.md) |
| Initiation | [Project Initiation](octoacme-project-initiation.md) |
| Planning | [Project Planning](octoacme-project-planning.md) |
| Execution & Tracking | [Execution and Tracking](octoacme-execution-and-tracking.md) |
| Risks & Communication | [Risks and Communication](octoacme-risks-and-communication.md) |
| Release & Deployment | [Release and Deployment](octoacme-release-and-deployment.md) |
| Close & Retrospective | [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |

### By Topic

| Topic | Document |
|-------|----------|
| Roles & Personas | [Roles and Personas](octoacme-roles-and-personas.md) |
| Risk Management | [Risks and Communication](octoacme-risks-and-communication.md) |
| Release Process | [Release and Deployment](octoacme-release-and-deployment.md) |
| Retrospectives | [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |

---

## Quick Reference

### Key Roles

| Role | Responsibilities |
|------|-----------------|
| **Developers** | Implement features, write tests, collaborate on design, submit PRs |
| **Product Managers (PdM)** | Prioritize the roadmap, define success metrics, own the product backlog |
| **Project Managers (PM)** | Coordinate delivery, manage risks, facilitate communication, track progress |

### Project Lifecycle Stages

1. **Initiation** — Validate business need; produce Project One-pager
2. **Planning** — Define scope, backlog, acceptance criteria, and Definition of Done
3. **Execution** — Build and track work via GitHub Projects; enforce quality gates
4. **Release** — Verify CI/security, draft release notes, confirm rollback plan, deploy
5. **Close & Retrospective** — Capture learnings; generate action items for next cycle

### Communication Cadence

| Frequency | Activity |
|-----------|----------|
| **Daily** | Standup (15 min) — progress, blockers, plan for the day |
| **Weekly** | PM + PdM sync — align delivery with product goals; delivery team standups |
| **Monthly** | Stakeholder updates — overall progress against success metrics |
| **Ad-hoc** | Escalations and incident response |

---

## Navigation Guide

Use the table below to jump directly to the most relevant documentation for your role.

| Persona | Recommended Starting Points |
|---------|-----------------------------|
| **Developer** | [Execution and Tracking](octoacme-execution-and-tracking.md) · [Project Planning](octoacme-project-planning.md) · [Release and Deployment](octoacme-release-and-deployment.md) |
| **Product Manager** | [Project Management Overview](octoacme-project-management-overview.md) · [Project Initiation](octoacme-project-initiation.md) · [Project Planning](octoacme-project-planning.md) |
| **Project Manager** | [Project Management Overview](octoacme-project-management-overview.md) · [Risks and Communication](octoacme-risks-and-communication.md) · [Execution and Tracking](octoacme-execution-and-tracking.md) · [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| **Stakeholder** | [Project Management Overview](octoacme-project-management-overview.md) · [Roles and Personas](octoacme-roles-and-personas.md) · [Risks and Communication](octoacme-risks-and-communication.md) |

> **New to the project?** Start with [OctoAcme Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md) to understand the framework and find your place within it.

---

*For questions or suggestions, open an issue or reach out to the Project Manager responsible for your team.*
