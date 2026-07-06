# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs. This folder contains comprehensive guides for running projects using the OctoAcme methodology.

## Quick Overview

OctoAcme is a project management approach built on principles of customer-first delivery, iterative development, clear ownership, and data-informed decisions. The framework emphasizes psychological safety, data-informed decision-making, and consistent, repeatable project execution.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than monolithic releases
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Key Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features and collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

### Project Lifecycle

All cross-functional projects follow this structured lifecycle:

1. **Initiation** — Validate business need, align stakeholders, create lightweight plan
2. **Planning** — Break work into actionable increments with clear acceptance criteria
3. **Execution** — Daily delivery with continuous tracking, testing, and iteration
4. **Release** — Standardized deployment with risk mitigation and observability
5. **Retrospective & Continuous Improvement** — Capture learnings and convert to action items

## Process Documents

### Foundations
- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for core principles, roles, key artifacts, and high-level lifecycle overview
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of Project Manager, Product Manager, Developer, and QA responsibilities and goals

### Phase-by-Phase Guides
- **[Project Initiation](octoacme-project-initiation.md)** — How to validate ideas, align stakeholders, and create a Project One-pager to decide on go/no-go
- **[Project Planning](octoacme-project-planning.md)** — Breaking work into prioritized backlog items, estimating scope, defining Definition of Done, and creating release plans
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily standups, PR workflows, quality standards, testing requirements, and blocker escalation paths
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklists, smoke test procedures, and rollback strategies
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running effective retrospectives, capturing learnings, and converting insights into tracked action items

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Maintaining risk registers, identifying and mitigating risks, stakeholder communication templates, and escalation paths

## Communication Cadence

OctoAcme projects follow a consistent communication rhythm to ensure alignment and transparency:

- **Daily**: Team standups (15 min) focusing on progress, blockers, and dependencies
- **Weekly**: Delivery sync between PM and PdM; risk register review; blocker escalation
- **Monthly**: Stakeholder updates and strategic alignment
- **Ad-hoc**: Escalations for critical issues, incidents, and decisions

## Quality & Testing Standards

Quality is embedded throughout execution:

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI/CD pipelines
- Manual QA for feature acceptance when needed
- Automated CI enforcement of tests, linting, and security checks

## How to Use These Docs

**Starting a new project?**
1. Begin with [Project Initiation](octoacme-project-initiation.md) to validate the business need
2. Review [Roles and Personas](octoacme-roles-and-personas.md) to understand team structure
3. Move to [Project Planning](octoacme-project-planning.md) once approved

**Need to plan a project?**
- Go to [Project Planning](octoacme-project-planning.md) for backlog creation and estimation
- Reference [Risk Management & Communication](octoacme-risks-and-communication.md) to set up your risk register

**Currently executing a project?**
- Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily workflows, PR standards, and escalation
- Check [Risk Management & Communication](octoacme-risks-and-communication.md) for weekly risk reviews and stakeholder updates

**Preparing to release?**
- Review [Release & Deployment](octoacme-release-and-deployment.md) for pre-release checklists and deployment procedures
- Ensure all items in the deployment checklist are completed

**Finished a phase or project?**
- See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and action items

**Managing cross-functional risks or dependencies?**
- Check [Risk Management & Communication](octoacme-risks-and-communication.md) for risk identification, assessment, and escalation
- Use provided communication templates for status updates and incident responses

## Getting Started with OctoAcme

1. **For new team members**: Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md)
2. **For new project leads**: Follow the phase-by-phase guides in order, starting with Initiation
3. **For ongoing project execution**: Bookmark the relevant phase guide and reference as needed
4. **For cross-functional teams**: Keep [Risk Management & Communication](octoacme-risks-and-communication.md) handy for dependency tracking and status updates

## Project Artifacts

Key artifacts created throughout an OctoAcme project include:

- **Project Charter / One-pager**: Business need, goals, success metrics, stakeholders, timeline
- **Risk Register**: Identified risks with impact, likelihood, owner, and mitigation plans
- **Project Backlog**: Prioritized items with acceptance criteria and estimates
- **Release Plan**: Milestones, release timeline, and go/no-go criteria
- **Release Notes**: What's new, migration steps, known issues
- **Retrospective Notes**: What went well, improvements needed, action items with owners and due dates

## Additional Resources

- Attach relevant process docs to Copilot Spaces for context-specific guidance
- Keep project charters in the project repository for easy reference
- Use GitHub Projects boards to visualize workflow and track progress
- Document key decisions and rationale in project README or decision logs
