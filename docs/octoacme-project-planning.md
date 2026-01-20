# OctoAcme — Project Planning

**Change Summary (2026-01-20):** Enhanced with role-specific planning responsibilities and handoff clarity to ensure accountability throughout the planning phase. Relates to issue #4.

## Purpose
Turn an approved initiative into an actionable plan and backlog for delivery.

## Objectives
- Break work into shippable increments
- Identify dependencies and risks
- Align timelines, releases, and responsibilities

## Activities
1. **Kickoff meeting** with stakeholders and delivery team
   - *Led by:* Project Manager
   - *Attendees:* All role owners, key stakeholders
2. **Create prioritized backlog** with acceptance criteria
   - *Led by:* Product Owner
   - *Supported by:* Business Analyst (requirements detail), Product Manager (strategic priorities)
3. **Estimate scope** (T-shirt sizing or story points)
   - *Led by:* Scrum Master or Project Manager
   - *Participants:* Developers, QA, Product Owner
4. **Define Definition of Done (DoD)**
   - *Led by:* Scrum Master
   - *Participants:* Developers, QA, Product Owner
5. **Identify dependencies and integration points**
   - *Led by:* Project Manager
   - *Participants:* Lead Developer, Business Analyst, other Project Managers (for cross-team dependencies)
6. **Create release plan and milestone map**
   - *Led by:* Release Manager
   - *Coordinated with:* Project Manager, Product Owner

## Role-Specific Planning Responsibilities

### Product Owner
- Prioritize the backlog based on business value
- Define acceptance criteria with input from Business Analyst
- Make scope trade-off decisions
- Participate in estimation sessions

### Business Analyst
- Document detailed requirements for high-priority backlog items
- Clarify acceptance criteria with Product Owner
- Identify data and integration needs
- Support feasibility analysis with developers

### Project Manager
- Facilitate planning meetings
- Capture dependencies and risks
- Create and maintain project timeline
- Coordinate resource allocation

### Scrum Master (if applicable)
**Note:** Assign this role for Scrum or Agile projects. For Waterfall or ad-hoc work, the Project Manager may fulfill these responsibilities.

- Facilitate sprint planning ceremonies
- Ensure backlog items meet Definition of Ready
- Coach team on estimation techniques
- Track and visualize team capacity

### Release Manager
- Define release windows and deployment schedule
- Identify release dependencies and constraints
- Plan deployment verification and rollback procedures
- Coordinate with infrastructure teams

### Lead Developer
- Provide technical feasibility input
- Identify technical dependencies and risks
- Define architecture approach for major features
- Support estimation and capacity planning

### QA Lead
- Define testing strategy and approach
- Identify test environment needs
- Estimate QA effort for backlog items
- Contribute to Definition of Done

### Stakeholders
- Review and approve the release plan
- Provide input on business priorities
- Confirm availability for reviews and approvals

## Backlog Item Template
- Title:
- Description:
- Acceptance criteria:
- Priority:
- Estimate:
- Owner:
- Related docs/links:

## Sprint / Iteration Planning
- Timebox planning to agreed sprint length
- Pull items that meet DoD and have clear acceptance criteria
- Ensure team capacity is respected

## Risk & Dependency Management
- Capture in Risk Register:
  - ID, Description, Impact, Probability, Owner, Mitigation
- Mark cross-team dependencies in the project board and escalate during weekly syncs

## Planning Checklist
- [ ] Project kickoff held with all role owners
- [ ] **Role responsibilities for planning phase confirmed** (NEW)
- [ ] Backlog prioritized and estimated
- [ ] **Acceptance criteria reviewed by Product Owner, Business Analyst, and QA** (NEW)
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted
- [ ] **Dependencies logged with owners assigned** (NEW)
- [ ] **Handoff to execution phase documented** (NEW)

## Key Handoffs During Planning

1. **Initiation → Planning Kickoff**
   - **From:** Project Manager (with approved One-pager)
   - **To:** Entire delivery team
   - **Artifact:** Project charter, role assignments
   - **Criteria:** All roles assigned, team availability confirmed

2. **Strategic Priorities → Backlog**
   - **From:** Product Manager
   - **To:** Product Owner
   - **Artifact:** Roadmap and prioritization rationale
   - **Criteria:** Strategic goals clear, success metrics defined

3. **Business Requirements → User Stories**
   - **From:** Business Analyst
   - **To:** Product Owner
   - **Artifact:** Requirements documentation, user stories
   - **Criteria:** Acceptance criteria testable, edge cases documented

4. **Backlog → Sprint Planning**
   - **From:** Product Owner
   - **To:** Scrum Master and Team
   - **Artifact:** Prioritized backlog meeting Definition of Ready
   - **Criteria:** Top items refined, estimated, and have clear acceptance criteria

5. **Planning → Execution**
   - **From:** Project Manager / Scrum Master
   - **To:** Entire delivery team
   - **Artifact:** Sprint plan, Definition of Done, risk register
   - **Criteria:** Team committed to sprint goals, capacity respected

---

**Last Updated:** 2026-01-20  
**See Also:** [Role Onboarding Checklist](role-onboarding-checklist.md) | [Roles and Personas](octoacme-roles-and-personas.md) | [Project Initiation](octoacme-project-initiation.md)
