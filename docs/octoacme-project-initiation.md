# OctoAcme — Project Initiation Guide

**Change Summary (2026-01-20):** Enhanced with explicit role assignments, ownership handoff points, and accountability tracking to prevent gaps. Added role-specific initiation tasks and clarified decision authority. Relates to issue #4.

## Purpose
Define the initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.

## When to use
Whenever a new project idea or feature proposal is ready to be explored.

## Goals
- Confirm business need and measurable outcome
- Identify stakeholders & champions
- Define success criteria and initial timeline
- Decide go/no-go for planning

## Minimum Deliverables
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and key milestones
- Initial risk list
- Resource needs (team roles, rough effort estimate)
- **Role Assignment Matrix** (NEW) - Clear ownership for each role
- **Handoff Agreement** (NEW) - Documented transition points between roles

## Role Assignments & Accountability

To prevent loss of accountability, clearly assign these roles during initiation:

### Core Roles (Required)
- **Product Owner**: _[Name]_ - Owns product vision and backlog prioritization
- **Project Manager**: _[Name]_ - Coordinates delivery, schedules, and communications
- **Product Manager**: _[Name]_ - Defines outcomes and measures success

### Extended Roles (Assign as Needed)
- **Scrum Master**: _[Name]_ - Facilitates Agile ceremonies (if using Scrum)
- **Business Analyst**: _[Name]_ - Gathers and documents requirements
- **Release Manager**: _[Name]_ - Oversees release planning and deployment
- **Lead Developer**: _[Name]_ - Technical leadership and architecture
- **QA Lead**: _[Name]_ - Quality assurance strategy and execution
- **Key Stakeholders**: _[Names and areas]_ - Decision authority and approval gates

### Decision Authority Matrix

Clear decision authority prevents delays and confusion:

| Decision Type | Primary Owner | Consulted | Informed |
|--------------|---------------|-----------|----------|
| Product Vision & Strategy | Product Manager | Product Owner, Stakeholders | Team |
| Backlog Prioritization | Product Owner | Product Manager, Business Analyst | Team |
| Scope Changes | Product Owner | Project Manager, Stakeholders | Team |
| Timeline & Resources | Project Manager | Product Owner, Scrum Master | Team, Stakeholders |
| Technical Approach | Lead Developer | Developers, QA Lead | Project Manager |
| Release Go/No-Go | Release Manager | QA Lead, Product Owner | Project Manager, Stakeholders |
| Process Changes | Scrum Master | Team | Project Manager |

## Project One-pager Template
- Project name:
- Problem statement:
- Objective / Goal (SMART):
- Success metrics:
- Primary stakeholders:
- Suggested timeline / milestones:
- Quick risks & dependencies:
- Proposed team / roles:
- **Product Owner**: _[Name]_
- **Project Manager**: _[Name]_
- **Product Manager**: _[Name]_
- **Scrum Master**: _[Name, if applicable]_
- **Business Analyst**: _[Name, if applicable]_
- **Release Manager**: _[Name, if applicable]_
- **Developers**: _[Names or count]_
- **QA/Testing**: _[Names or count]_
- **Key Stakeholders**: _[Names and roles]_

## Key Handoff Points During Initiation

Understanding handoffs prevents accountability gaps:

1. **Business Need → Requirements**
   - **From:** Stakeholders
   - **To:** Product Manager / Business Analyst
   - **Artifact:** Business case or problem statement
   - **Criteria:** Problem validated and quantified

2. **Requirements → Product Vision**
   - **From:** Business Analyst / Stakeholders
   - **To:** Product Manager
   - **Artifact:** Requirements document or user research
   - **Criteria:** Customer needs understood and documented

3. **Product Vision → Backlog**
   - **From:** Product Manager
   - **To:** Product Owner
   - **Artifact:** Product roadmap and vision
   - **Criteria:** Strategic direction clear, success metrics defined

4. **Approval → Planning**
   - **From:** Stakeholders / Sponsor
   - **To:** Project Manager / Product Owner
   - **Artifact:** Approved One-pager
   - **Criteria:** Go decision documented, budget/resources allocated

5. **Team Assignment → Onboarding**
   - **From:** Project Manager
   - **To:** All assigned roles
   - **Artifact:** Role assignment notification + onboarding checklist
   - **Criteria:** Each team member completes [Role Onboarding Checklist](role-onboarding-checklist.md)

## Initiation Checklist
- [ ] One-pager completed and reviewed by Product Lead
- [ ] **All core roles assigned with named owners** (NEW)
- [ ] **Decision Authority Matrix reviewed and agreed** (NEW)
- [ ] Sponsor / Stakeholder alignment (email or meeting)
- [ ] **Key handoff points identified and documented** (NEW)
- [ ] Decision: Approve to move into planning?
- [ ] Create repo or project board skeleton
- [ ] Add initial artifacts to repo (docs/ or .copilot/)
- [ ] **Distribute Role Onboarding Checklist to all team members** (NEW)
- [ ] **Schedule initiation kickoff meeting with all role owners** (NEW)

## Decision Gate
Move to planning when:
- Success metrics are clear
- Stakeholders agree on priority
- Team availability is confirmed
- **All core roles are assigned with named owners** (NEW)
- **Handoff points and decision authority are documented** (NEW)
- **Accountability gaps identified and mitigation planned** (NEW)

## Initiation Kickoff Meeting Agenda

**Purpose:** Align all role owners on project goals, responsibilities, and handoffs

**Attendees:** All assigned role owners (required), Stakeholders (optional)

**Agenda (60 minutes):**
1. **Introductions** (5 min) - Each person shares their role and background
2. **Project Overview** (10 min) - Product Manager presents One-pager
3. **Role Clarity** (15 min) - Review Role Assignment Matrix and Decision Authority
4. **Handoff Points** (10 min) - Walk through Key Handoff Points
5. **Communication Plan** (10 min) - Establish meeting cadence and channels
6. **Questions & Risks** (10 min) - Surface concerns early

**Outputs:**
- Confirmed role assignments
- Agreed communication cadence
- Initial risk register entries
- Action items with owners

---

**Last Updated:** 2026-01-20  
**See Also:** [Role Onboarding Checklist](role-onboarding-checklist.md) | [Roles and Personas](octoacme-roles-and-personas.md)
