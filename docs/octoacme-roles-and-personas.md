# OctoAcme Personas

**Change Summary (2026-01-20):** Expanded to include Product Owner, Scrum Master, Stakeholder, Business Analyst, and Release Manager roles with clear responsibilities and interaction patterns to address accountability gaps and improve handoff clarity. Relates to issue #4.

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Quality Assurance

### Role Summary
QA/Testing professionals validate quality and acceptance criteria, ensuring features meet defined standards before release.

### Responsibilities
- Execute test plans and test cases
- Verify acceptance criteria are met
- Report defects and track to resolution
- Participate in Definition of Done refinement
- Conduct regression testing before releases
- Collaborate with developers on testability

### Goals
- Ensure features meet quality standards
- Prevent regressions and production defects
- Maintain comprehensive test coverage

### Typical Communication
- Test results and defect reports
- QA sign-off on releases
- Acceptance criteria clarifications with Product Manager and Business Analyst

### Interactions with Other Roles
- **Developers**: Collaborate on testability, reproduce and verify bug fixes
- **Project Manager**: Report testing progress, flag quality risks
- **Product Manager**: Clarify acceptance criteria and edge cases
- **Business Analyst**: Review requirements for testability
- **Release Manager**: Provide QA sign-off before deployment

---

## Product Owner

### Role Summary
The Product Owner defines the product vision and priorities, ensures business value in project deliverables, and serves as the voice of the customer. They own the product backlog and make final decisions on feature prioritization.

### Responsibilities
- Define and communicate the product vision
- Prioritize the product backlog based on business value
- Make decisions on feature scope and trade-offs
- Accept or reject completed work based on acceptance criteria
- Ensure ROI and business value delivery
- Collaborate with stakeholders to gather requirements
- Maintain the product roadmap

### Goals
- Maximize the value delivered by the development team
- Ensure alignment between product development and business objectives
- Maintain a clear and prioritized product backlog

### Typical Communication
- Backlog refinement sessions
- Sprint reviews and planning meetings
- Stakeholder updates on product direction
- Acceptance criteria reviews

### Interactions with Other Roles
- **Product Manager**: Collaborate on strategic direction and market insights; Product Owner focuses on backlog prioritization while Product Manager handles market research and metrics
- **Scrum Master**: Work together to facilitate Agile ceremonies and remove impediments
- **Developers**: Provide clarity on requirements and acceptance criteria
- **Business Analyst**: Receive detailed requirements analysis and business process documentation
- **Stakeholder**: Gather inputs and provide visibility into product decisions
- **Project Manager**: Align on priorities and dependencies
- **QA/Testing**: Review acceptance criteria for completeness

---

## Scrum Master

### Role Summary
The Scrum Master facilitates Agile ceremonies, removes impediments, and ensures the team follows agreed-upon processes. They serve as a coach and advocate for continuous improvement.

### Responsibilities
- Facilitate Scrum ceremonies (daily standups, sprint planning, retrospectives, reviews)
- Remove blockers and impediments to team progress
- Coach the team on Agile principles and practices
- Protect the team from external distractions
- Foster a culture of continuous improvement
- Track and visualize team metrics (velocity, burndown)
- Facilitate conflict resolution

### Goals
- Enable the team to work at maximum effectiveness
- Ensure adherence to Agile principles and practices
- Continuously improve team processes and collaboration

### Typical Communication
- Daily facilitation of standups
- Retrospective facilitation and action tracking
- Team health metrics and improvement initiatives
- Escalation of systemic blockers

### Interactions with Other Roles
- **Project Manager**: Collaborate on scheduling and resource planning; Scrum Master focuses on team process while Project Manager handles cross-team coordination
- **Product Owner**: Help maintain a healthy backlog and facilitate backlog refinement
- **Developers**: Remove impediments and coach on best practices
- **Stakeholders**: Manage expectations and shield team from mid-sprint disruptions
- **Release Manager**: Coordinate on release cadence and deployment readiness

---

## Stakeholder

### Role Summary
Stakeholders represent business or customer interests, engage in reviews, and provide critical feedback. They are invested parties who influence or are affected by the project's outcome.

### Responsibilities
- Provide business context and domain expertise
- Review and approve project proposals and deliverables
- Participate in milestone reviews and demos
- Provide timely feedback on features and releases
- Make go/no-go decisions at key decision gates
- Escalate business-critical concerns

### Goals
- Ensure project outcomes align with business objectives
- Represent customer or business unit interests
- Validate that deliverables meet business needs

### Typical Communication
- Monthly stakeholder updates
- Milestone reviews and demos
- Decision gates and approvals
- Feedback on prototypes and releases

### Interactions with Other Roles
- **Product Owner**: Provide business requirements and validate priorities
- **Product Manager**: Share market insights and customer feedback
- **Project Manager**: Receive status updates and provide approvals
- **Business Analyst**: Provide business process expertise and validate requirements
- **Release Manager**: Review release plans and deployment schedules

---

## Business Analyst

### Role Summary
The Business Analyst gathers requirements, documents processes, and acts as a bridge between business stakeholders and technical teams. They ensure requirements are clear, complete, and feasible.

### Responsibilities
- Elicit and document business requirements
- Create process flows and data models
- Analyze business problems and propose solutions
- Validate requirements with stakeholders
- Write detailed user stories and acceptance criteria
- Facilitate requirements workshops
- Identify process improvement opportunities

### Goals
- Ensure clear, complete, and testable requirements
- Bridge communication gaps between business and technical teams
- Enable informed decision-making through analysis

### Typical Communication
- Requirements documentation and user stories
- Process flow diagrams and business rules
- Requirements workshops and walkthroughs
- Clarifications on acceptance criteria

### Interactions with Other Roles
- **Product Owner**: Provide detailed requirements analysis to support backlog prioritization
- **Product Manager**: Collaborate on market analysis and customer needs translation
- **Developers**: Clarify requirements and answer technical feasibility questions
- **QA/Testing**: Define acceptance criteria and test scenarios
- **Stakeholders**: Elicit requirements and validate documented processes
- **Project Manager**: Identify scope, dependencies, and risks during planning

---

## Release Manager

### Role Summary
The Release Manager oversees release planning, change management, and successful deployments. They ensure releases are coordinated, tested, and delivered with minimal risk.

### Responsibilities
- Plan and coordinate release schedules
- Manage the release pipeline and deployment process
- Ensure proper testing and validation before releases
- Coordinate with multiple teams for integrated releases
- Maintain release documentation and runbooks
- Manage rollback procedures and contingency plans
- Track release metrics and deployment health

### Goals
- Deliver reliable, on-time releases to production
- Minimize deployment risks and production incidents
- Maintain clear release communication and documentation

### Typical Communication
- Release schedules and deployment windows
- Go/no-go decisions before releases
- Post-deployment reports and metrics
- Rollback communications if needed

### Interactions with Other Roles
- **Project Manager**: Align on release timelines and dependencies
- **Developers**: Review code freeze dates and deployment procedures
- **QA/Testing**: Verify release readiness and test completion
- **Product Owner**: Confirm feature completeness and release scope
- **Scrum Master**: Coordinate on sprint completion and release readiness
- **Stakeholders**: Communicate release schedules and impacts

---

## Role Interaction Matrix

The following matrix summarizes key handoffs and collaboration points between roles:

| From Role | To Role | Key Handoffs/Interactions |
|-----------|---------|---------------------------|
| Product Owner | Business Analyst | Product vision → Detailed requirements |
| Business Analyst | Developers | Requirements documentation → Implementation |
| Developers | QA/Testing | Completed features → Testing and validation |
| QA/Testing | Release Manager | QA sign-off → Release approval |
| Release Manager | Stakeholders | Deployment notification → Business validation |
| Stakeholders | Product Owner | Business feedback → Backlog priorities |
| Scrum Master | Project Manager | Team metrics → Cross-team coordination |
| Product Manager | Product Owner | Market insights → Product priorities |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Role Interaction Matrix helps identify handoff points and prevent accountability gaps.

