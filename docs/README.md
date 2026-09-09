# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management process documentation. This folder contains comprehensive guides for running projects at OctoAcme, organized by project lifecycle phase.

## Quick Overview

OctoAcme employs a **customer-centric, iterative delivery model** grounded in clear ownership and data-driven decision-making. The organization operates through five distinct lifecycle phases—Initiation, Planning, Execution, Release, and Retrospectives—each with well-defined activities and artifacts. Our framework emphasizes:

- **Customer-first mindset**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Ship small, testable increments rather than large all-or-nothing releases
- **Clear ownership**: Every project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Foster a culture where feedback and learning are encouraged

## Project Lifecycle

Our projects follow five phases:

1. **Initiation** - Define the problem, identify stakeholders, and secure approval
2. **Planning** - Break work into deliverables, establish timelines and dependencies
3. **Execution** - Build, test, iterate, and track progress
4. **Release** - Deploy to production and verify success
5. **Retrospective** - Capture learnings and identify improvements

## Key Roles & Responsibilities

OctoAcme's project structure centers on three primary roles with complementary responsibilities:

- **Product Managers** define what should be built and own prioritization based on customer and business value
- **Project Managers** coordinate delivery activities, manage schedules, dependencies, and communications to keep teams on track
- **Developers** design, build, and test features while collaborating on design and identifying technical risks

This tripartite division of labor—combined with QA/Testing specialists who validate quality against acceptance criteria—creates clear ownership and reduces ambiguity.

## Quality Assurance & Risk Management

Quality assurance and risk management are deeply embedded into OctoAcme's execution practices rather than bolted on at the end. Teams employ:

- Daily standups focused on blockers and dependencies
- Structured pull request workflow (preferring PRs ≤400 lines with automated testing and linting)
- Multi-layered quality gates: unit tests, integration tests, end-to-end smoke tests, and security scanning in CI
- Risk registers tracked weekly with clear escalation paths from team triage through PM escalation to sponsor involvement

## Communication Cadence

Consistent alignment is maintained without creating communication overhead through:

- Weekly PM-PdM syncs
- Twice-weekly standups for delivery teams
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Documentation Guide

### Phase Guides

- **[Project Management Overview](./octoacme-project-management-overview.md)** - Start here to understand OctoAcme's framework, core roles, key artifacts, and communication cadence
- **[Project Initiation](./octoacme-project-initiation.md)** - Learn how to kick off a new project, validate business need, and create a project one-pager
- **[Project Planning](./octoacme-project-planning.md)** - Discover how to create backlogs, estimate work, define acceptance criteria, and manage dependencies
- **[Execution and Tracking](./octoacme-execution-and-tracking.md)** - Understand daily standups, progress tracking, sprint ceremonies, and quality management
- **[Risks and Communication](./octoacme-risks-and-communication.md)** - Manage project risks, escalation paths, and stakeholder communication strategies
- **[Release and Deployment](./octoacme-release-and-deployment.md)** - Follow procedures for release planning, deployment, and production verification
- **[Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Learn how to conduct effective retrospectives and implement process improvements

### Reference Materials

- **[Roles and Personas](./octoacme-roles-and-personas.md)** - Detailed descriptions of project roles, responsibilities, and team personas at OctoAcme

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our core framework and principles.

**Starting a new project?** Follow the flow: Initiation → Planning → Execution → Release → Retrospective, using the phase guides above.

**Looking for a specific process?** Use the Documentation Guide above to jump to the relevant guide for your current project phase.

## Continuous Improvement

OctoAcme treats documentation and continuous improvement as first-class practices. These guides are maintained as living documents in the project repository. Retrospectives are formally scheduled after each project or release, capturing learnings to feed back into process improvements. By centralizing project management knowledge, we reduce single-person dependencies, accelerate onboarding, and enable consistent, repeatable execution across teams.
