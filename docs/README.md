# OctoAcme Project Management Documentation

This repository collects and standardizes OctoAcme's core project management processes for team effectiveness and organizational alignment.

## Overview of Project Management Processes

OctoAcme project management is organized around a five-phase lifecycle that emphasizes customer value, iterative delivery, and clear accountability:

### Key Phases
- **Initiation**: Validate business needs and stakeholder alignment through a lightweight Project One-pager that defines the problem, goal, success metrics, and key risks
- **Planning**: Break approved work into shippable increments with prioritized backlogs, acceptance criteria, risk identification, and release planning
- **Execution & Tracking**: Manage day-to-day delivery through daily standups, weekly syncs, GitHub Projects, structured PR workflows, and quality assurance
- **Release & Deployment**: Standardize releases with pre-release checklists, release notes, automated deployments, and documented rollback plans
- **Retrospectives & Continuous Improvement**: Capture lessons learned and convert them into actionable improvements with clear owners and timelines

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than large monolithic releases
- **Clear ownership**: Each project has named Project Manager and Product Lead roles with defined accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

### Roles & Responsibilities
OctoAcme operates with three core roles working in collaboration:
- **Project Managers (PMs)**: Coordinate delivery, manage schedules, risks, communications, and ensure project documentation
- **Product Managers (PdMs)**: Define outcomes, prioritize backlogs, and measure success
- **Developers**: Implement features, collaborate on design, write tests, and identify technical risks

### Communication & Transparency
- Daily standups (15 minutes) focused on progress, blockers, and dependencies
- Weekly PM-PdM syncs for alignment
- Twice-weekly team standups (or as agreed)
- Monthly stakeholder updates
- Tiered escalation: Team → PM → Product Lead → Sponsor

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Pull requests ≤400 lines with at least one approval before merging

---

## Process Documentation Index

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate business needs, align stakeholders, and gate decisions to move into planning
- **[Project Planning](octoacme-project-planning.md)** — How to create actionable plans, prioritized backlogs, release timelines, and manage dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Guidance for day-to-day delivery, testing, quality assurance, and risk escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, assess, monitor risks and communicate status to stakeholders
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized processes for releases, deployment checklists, and rollback procedures
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives and convert learnings into actionable improvements
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed role definitions and responsibilities for developers, product managers, and project managers

---

## How to Use These Docs

1. **For new team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand OctoAcme's approach and core roles
2. **For project initiation**: Follow the [Project Initiation Guide](octoacme-project-initiation.md) and use the Project One-pager template
3. **For ongoing projects**: Reference the relevant phase guide and use templates and checklists to ensure consistent execution
4. **For continuous improvement**: Use the [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) guide and track action items in your project backlog
5. **For process updates**: Open an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template to propose additions or improvements

---

## Contributing to These Docs

These documents represent the current best practices and standards for OctoAcme projects. To suggest updates:

1. Open an issue using the **"Add Content to Project Management Process Docs"** template in `.github/ISSUE_TEMPLATE/`
2. Provide a clear rationale for the change and align with existing principles
3. Include examples or suggested content when appropriate
4. Ensure updates are reviewed and approved before merging
