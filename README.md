# OctoAcme Project Management Docs

This folder centralizes OctoAcme's program-level project management processes, providing practical guidance for planning, executing, releasing, and continuously improving product work. The goal is to make institutional knowledge actionable and accessible, enabling consistent, repeatable project execution and accelerating onboarding.

## Project Management Processes Overview

OctoAcme’s approach is iterative and customer-focused, structured around five core stages: Initiation, Planning, Execution, Release, and Retrospective. Projects begin with a validated business need and stakeholder alignment using a Project One-pager. Planning breaks down work into shippable increments, prioritizes backlog items with clear acceptance criteria, and identifies dependencies and risks. Execution is managed through daily standups, project boards, and disciplined pull request workflows with automated CI gating. Releases leverage checklists, smoke tests, and rollback plans to ensure readiness and reduce risk. Retrospectives capture learnings and convert them into actionable improvements for future cycles.

## Key Workflows, Roles, and Communication

Roles are clearly defined for accountability: the Project Manager coordinates delivery and risk, the Product Manager owns product outcomes and backlog, Developers build and test features, QA ensures quality standards, and Stakeholders provide input and approvals. Communication is intentional, with weekly PM/Product syncs, twice-weekly team standups, and regular stakeholder updates. Risks and blockers follow an established escalation path, from team triage to sponsor-level intervention for business-critical issues.

## Quality Assurance Practices

Quality assurance is embedded throughout the lifecycle. Automated unit, integration, and end-to-end tests are required for new logic, with security scanning in CI/CD pipelines. Manual QA is performed for feature acceptance when needed, and deployment checklists ensure production readiness and rollback procedures. Incidents trigger a structured response and root cause analysis, while retrospectives ensure continual improvement by turning insights into owned backlog items.

## Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to Use

- Add or update content in the specific doc that needs refinement, then open a PR referencing the related process issue for review.
- Keep the project README / one‑pager in each project repo up to date so program docs remain tied to actual projects and outcomes.

---

**Acceptance criteria:**
- Content aligns with the existing process docs in this folder
- Improves discoverability and onboarding
- Is reviewed by the appropriate stakeholders (PM / Product Lead) as needed
