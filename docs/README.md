# OctoAcme Project Management Guide

## Overview

Welcome to OctoAcme's project management documentation. This guide provides a comprehensive overview of how we run cross-functional projects to deliver product features, services, and integrations. Our approach emphasizes customer-first thinking, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Whether you're a new team member or a seasoned contributor, this README will orient you to our workflows, roles, communication practices, and quality standards.

At OctoAcme, we follow a structured lifecycle from project initiation through continuous improvement. Each project begins with a **Project One-pager** that defines the problem statement, success metrics, and stakeholders. From there, we move through planning (creating a prioritized backlog and release plan), execution (building and testing with daily standups and weekly syncs), release (deploying to production with proper verification), and retrospectives (capturing learnings for continuous improvement). Throughout this journey, our **risk register** and **project board** keep us aligned, while regular demos and stakeholder updates ensure transparency.

Our culture is built on collaboration across key personas: **Project Managers (PM)** coordinate delivery and manage risks; **Product Managers (PdM)** define outcomes and prioritize work; **Developers** implement features with quality and testability in mind; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide essential inputs and approvals. Communication happens at multiple cadences—daily standups for the delivery team, weekly PM-PdM syncs, bi-weekly demos, and monthly stakeholder updates—with clear escalation paths when blockers arise. Quality assurance is embedded throughout, from unit and integration tests in CI to end-to-end smoke tests before release, supported by security scanning and manual QA where needed.

By following these practices and leveraging our documented artifacts (Project Charter, roadmap, sprint backlog, Definition of Done, release notes, and retrospective action items), we maintain high standards while adapting to changing needs. This guide references detailed documentation for each phase—explore the linked documents below to dive deeper into specific workflows, templates, and checklists that will help you succeed at OctoAcme.

---

## Key Workflows

OctoAcme projects follow a five-phase lifecycle:

### 1. **Initiation**
Validate the business need and align stakeholders before committing resources.

- **Key Artifacts**: Project One-pager, stakeholder list, high-level timeline, initial risk list
- **Activities**: Define problem statement, identify success metrics, confirm resource needs
- **Decision Gate**: Move to planning when success metrics are clear, stakeholders agree on priority, and team availability is confirmed
- **Documentation**: [Project Initiation Guide](octoacme-project-initiation.md)

### 2. **Planning**
Turn an approved initiative into an actionable plan and backlog.

- **Key Artifacts**: Prioritized backlog, Definition of Done, release plan, risk register
- **Activities**: Kickoff meeting, create backlog with acceptance criteria, estimate scope (T-shirt sizing or story points), identify dependencies
- **Sprint Planning**: Timebox planning to agreed sprint length, respect team capacity
- **Documentation**: [Project Planning Guide](octoacme-project-planning.md)

### 3. **Execution & Tracking**
Manage day-to-day execution and track progress toward milestones.

- **Key Artifacts**: Project board (Backlog, Ready, In Progress, In Review, QA, Done), PR descriptions with issue links
- **Activities**: Daily standups, weekly delivery syncs, sprint demos/reviews
- **PR Workflow**: Small PRs (≤400 lines preferred), automated tests and linting in CI, at least one approval before merging
- **Documentation**: [Execution & Tracking Guide](octoacme-execution-and-tracking.md)

### 4. **Release & Deployment**
Standardize releases to production to reduce risk and improve observability.

- **Key Artifacts**: Release notes, smoke tests, rollback plan
- **Activities**: Deploy to staging, run smoke tests, deploy to production, post-deploy verifications, stakeholder announcements
- **Release Types**: Patch (hotfixes), Minor (incremental features), Major (significant functionality or breaking changes)
- **Documentation**: [Release & Deployment Guide](octoacme-release-and-deployment.md)

### 5. **Retrospective & Continuous Improvement**
Capture learnings and convert them into actionable improvements.

- **Key Artifacts**: Retrospective notes, action items with owners and due dates
- **Activities**: Review what went well and what could be improved, prioritize 2-3 top action items, track improvements in backlog
- **Timing**: After each sprint, release, or milestone; also after incidents
- **Documentation**: [Retrospective & Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md)

---

## Core Personas & Roles

Understanding roles and responsibilities ensures clear ownership and effective collaboration.

### **Project Manager (PM)**
Coordinates delivery activities, manages schedules, risks, and communications.

- **Responsibilities**: Create project plans, manage risk register, facilitate meetings (kickoff, planning, retrospectives), maintain project documentation
- **Goals**: Deliver on time and within scope, minimize unplanned work, maintain transparency
- **Communication**: Weekly status updates, risk registers, project board coordination

### **Product Manager (PdM)**
Defines what should be built to deliver customer and business value.

- **Responsibilities**: Define problem statements and success metrics, prioritize roadmap and backlog, validate solutions through user research
- **Goals**: Maximize customer value and impact, make data-driven prioritization decisions
- **Communication**: Weekly alignment with PM and engineering leads, roadmap updates, acceptance criteria

### **Developers**
Design, build, test, and deliver software components.

- **Responsibilities**: Implement features meeting acceptance criteria, write tests and documentation, participate in code reviews, estimate work
- **Goals**: Deliver reliable, maintainable code, reduce cycle time, maintain high test coverage
- **Communication**: Daily standups, PR descriptions and code review comments, technical design docs

### **QA/Testing**
Validate quality and acceptance criteria.

- **Responsibilities**: Execute test plans, verify acceptance criteria, report defects, participate in Definition of Done
- **Goals**: Ensure features meet quality standards, prevent regressions
- **Communication**: Test results, defect reports, QA sign-off on releases

### **Stakeholders**
Provide inputs and approvals to guide project direction.

- **Responsibilities**: Review proposals, provide domain expertise, approve go/no-go decisions
- **Goals**: Ensure project aligns with business objectives
- **Communication**: Monthly updates, milestone reviews, escalation as needed

**Detailed Role Definitions**: [Roles and Personas](octoacme-roles-and-personas.md)

---

## Communication Strategies

Effective communication keeps teams aligned and reduces surprises.

### **Communication Cadence**

- **Daily Standups** (15 min): Progress, blockers, dependencies—delivery team only
- **Weekly PM + PdM Sync**: Alignment on priorities, risks, and decisions
- **Bi-weekly Delivery Sync**: Show progress, updates, flagged risks to broader team
- **Sprint Demos/Reviews**: End of each sprint or milestone—demonstrate completed work
- **Monthly Stakeholder Updates**: High-level status, upcoming milestones, risks

### **Weekly Status Template**
- Progress this week
- Next steps
- Risks & blockers
- Asks / decisions needed

### **Escalation Paths**
Clear escalation ensures blockers are resolved quickly.

- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Security Incidents**: Follow security incident runbook and notify Security on-call

### **Stakeholder Communication**
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

**Detailed Guidance**: [Risk Management & Communication](octoacme-risks-and-communication.md)

---

## Quality Assurance Practices

Quality is embedded throughout the development lifecycle.

### **Testing Strategy**

- **Unit Tests**: For new logic and code changes
- **Integration Tests**: Where applicable, especially for cross-component interactions
- **End-to-End Smoke Tests**: For critical flows before release
- **Security Scanning**: Automated in CI pipeline
- **Manual QA**: For feature acceptance when needed

### **Definition of Done (DoD)**
Defined during planning and includes:
- All acceptance criteria met
- Code reviewed and approved
- Tests written and passing
- Documentation updated
- Security scans passing
- Deployed to staging and verified

### **PR Quality Standards**
- Small PRs (≤400 lines when possible) for easier review
- Include issue link and acceptance criteria in PR description
- Run automated tests and linting in CI before requesting review
- Require at least one approval before merging (or team-defined policy)

### **QA Checklists**
- **Pre-release Requirements**: All acceptance criteria met, passing CI and security scans, release notes drafted, rollback plan documented, smoke tests prepared
- **Post-deploy Verifications**: Smoke tests in production, monitoring dashboards reviewed, stakeholder announcements sent

### **Metrics & Monitoring**
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

**Detailed Practices**: [Execution & Tracking](octoacme-execution-and-tracking.md), [Release & Deployment](octoacme-release-and-deployment.md)

---

## Key Artifacts & Templates

These standardized artifacts ensure consistency and reduce rework.

| Artifact | Purpose | Owner | Phase |
|----------|---------|-------|-------|
| **Project One-pager** | Problem statement, goal, success metrics, stakeholders, timeline | PM + PdM | Initiation |
| **Risk Register** | ID, description, impact, likelihood, owner, mitigation, status | PM | Planning, Execution |
| **Project Board** | Track work status (Backlog, Ready, In Progress, In Review, QA, Done) | PM | Execution |
| **Backlog Items** | Title, description, acceptance criteria, priority, estimate, owner | PdM + Team | Planning, Execution |
| **Definition of Done** | Checklist of requirements for work to be considered complete | Team | Planning |
| **Sprint/Iteration Plan** | Committed work for the sprint, capacity, goals | Team | Execution |
| **Release Notes** | Release name/number, date, summary, notable changes, migration steps, known issues | PM + Developers | Release |
| **Demo Agenda** | Features to demonstrate, participants, feedback capture | PM + PdM | Execution |
| **Retrospective Notes** | What went well, what could be improved, action items with owners and due dates | PM | Retrospective |
| **Stakeholder Updates** | Progress, next steps, risks/blockers, decisions needed | PM | Ongoing |

---

## Principles

Our work is guided by these core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

---

## How to Use These Docs

- **New to OctoAcme?** Start with this README for the big picture, then explore phase-specific guides as you engage in projects.
- **Starting a new project?** Begin with the [Project Initiation Guide](octoacme-project-initiation.md) and create your Project One-pager.
- **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for daily practices and [Risk Management & Communication](octoacme-risks-and-communication.md) for escalations.
- **Preparing for release?** Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) checklist.
- **After a milestone or sprint?** Use the [Retrospective Guide](octoacme-retrospective-and-continuous-improvement.md) to capture learnings.
- **Need role clarity?** Review [Roles and Personas](octoacme-roles-and-personas.md) for detailed responsibilities.
- **Copilot Spaces**: Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

---

## Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities
- [Project Initiation](octoacme-project-initiation.md) — How to validate and authorize new projects
- [Project Planning](octoacme-project-planning.md) — Creating actionable plans and backlogs
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution, testing, and reporting
- [Release & Deployment](octoacme-release-and-deployment.md) — Standardized release processes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and improving
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Managing risks, stakeholder communication, and escalation

---

## Getting Help

- **Questions about a specific phase?** Refer to the detailed guide linked in the Documentation Index above.
- **Need to escalate a blocker?** Follow the escalation paths outlined in [Risk Management & Communication](octoacme-risks-and-communication.md).
- **Proposing a process improvement?** Raise it in a retrospective or create an issue with the `process-improvement` label.

---

**Last Updated**: 2026-01-20  
**Maintained by**: OctoAcme Project Management Team
