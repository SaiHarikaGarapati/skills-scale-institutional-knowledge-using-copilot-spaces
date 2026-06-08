# OctoAcme — Cross-Functional Collaboration

## Purpose
Provide guidelines for how different roles and personas work together effectively throughout the project lifecycle. This document clarifies communication patterns, decision rights, and collaboration touchpoints.

## Core Collaboration Principles
- **Clear Ownership**: Every work item and decision has a named owner
- **Early Involvement**: Bring affected roles in during planning, not just execution
- **Async-First Communication**: Use written artifacts as the source of truth
- **Psychological Safety**: Encourage questions, feedback, and dissenting opinions
- **Data-Driven Decisions**: Use metrics and user feedback to inform choices

## Collaboration by Project Phase

### Initiation & Planning Phase

**Key Participants**: Product Manager, Project Manager, UX Designer, Developers (tech lead), Data Analyst

**Activities**:
- Define the problem statement and success metrics (Product Manager + Data Analyst)
- Create user personas and research findings (UX Designer)
- Estimate technical feasibility and effort (Developers)
- Identify risks and dependencies (Project Manager)
- Align on timeline and resource needs (Project Manager + Product Manager)

**Communication Cadence**: Weekly alignment meetings until plan is finalized

**Deliverables**: Project Charter, User Research Summary, Technical Design, Risk Register

---

### Design & Specification Phase

**Key Participants**: UX Designer, Product Manager, Developers, Scrum Master

**Activities**:
- Conduct user research and usability testing (UX Designer)
- Create design specifications and wireframes (UX Designer)
- Refine acceptance criteria with developers (Product Manager + Developers)
- Identify design-to-implementation gaps (UX Designer + Developers)
- Finalize sprint/iteration scope (Scrum Master + Team)

**Communication Cadence**: Design reviews (2x per week) + Sprint planning (weekly)

**Deliverables**: Design System Docs, Acceptance Criteria, Sprint Backlog

---

### Development & Testing Phase

**Key Participants**: Developers, QA/Testing, Scrum Master, UX Designer, Release Manager

**Activities**:
- Implement features with design fidelity (Developers + UX Designer reviews)
- Run unit and integration tests (Developers + QA)
- Conduct usability testing if needed (UX Designer)
- Track progress against sprint goals (Scrum Master)
- Prepare for release (Release Manager)

**Communication Cadence**: Daily standups (Scrum Master facilitated) + Mid-sprint check-ins

**Deliverables**: Code, Test Reports, PR Reviews, Release Checklist

---

### Release & Deployment Phase

**Key Participants**: Release Manager, Developers, QA/Testing, Customer Support Liaison, Product Manager

**Activities**:
- Verify release readiness (Release Manager checklist)
- Deploy to staging/production (Developers + Release Manager)
- Run post-deploy verification (QA/Testing + Release Manager)
- Communicate release to customers (Customer Support Liaison + Product Manager)
- Monitor for issues (Data Analyst + Product Team)

**Communication Cadence**: Daily or as-needed during release window

**Deliverables**: Release Notes, Deployment Log, Incident Report (if needed)

---

### Monitoring & Learning Phase

**Key Participants**: Data Analyst, Product Manager, Customer Support Liaison, Developers, Project Manager

**Activities**:
- Track success metrics and KPIs (Data Analyst)
- Monitor for production issues (Data Analyst + Developers)
- Collect customer feedback (Customer Support Liaison)
- Identify optimization opportunities (Data Analyst + Product Manager)
- Conduct retrospective and capture learnings (Project Manager)

**Communication Cadence**: Weekly metrics review + Post-release retrospective

**Deliverables**: Metrics Dashboard, Retrospective Notes, Action Items

---

## Key Collaboration Touchpoints

### Daily Standup
**Participants**: Development team (Developers, QA, Scrum Master), optional: Product Manager

**Purpose**: Synchronize on progress, blockers, and dependencies

**Scrum Master facilitates**: Each person shares what they did, what they're doing, and any blockers

**Blocker Resolution**: If a blocker requires cross-team input, escalate in weekly syncs

---

### Weekly Product-Engineering Sync
**Participants**: Product Manager, Project Manager, Developers (tech lead), Scrum Master

**Purpose**: Align on priorities, risks, and upcoming work

**Topics**:
- Backlog prioritization and scope adjustments
- Risk and dependency updates
- Metrics review and learnings
- Upcoming milestones and releases

**Duration**: 45–60 minutes

---

### Design Review
**Participants**: UX Designer, Developers, Product Manager

**Purpose**: Review design fidelity, identify implementation challenges, align on user experience

**Cadence**: 2–3 times per sprint as needed

**Outcome**: Design approval or iteration feedback

---

### Release Planning & Coordination
**Participants**: Release Manager, Developers, QA/Testing, Product Manager, Customer Support Liaison

**Purpose**: Coordinate release timing, verify readiness, plan communications

**Key Artifacts**:
- Release checklist
- Change log
- Known issues list
- Rollback plan
- Customer communication template

---

### Retrospective
**Participants**: Full project team (Developers, QA, UX Designer, Scrum Master, Product Manager, Project Manager)

**Purpose**: Reflect on what went well, what could improve, and capture action items

**Structure**:
- What went well (celebrate wins)
- What could improve (identify gaps)
- Action items (owner, due date, success criteria)

**Duration**: 45–75 minutes

**Follow-up**: Review action items in weekly PM sync

---

## Escalation & Decision-Making

### Level 1: Team Discussion
- **When**: Decisions affect the team's day-to-day work
- **Who**: Relevant team members in daily standup or design review
- **Resolution**: Scrum Master or Product Manager facilitates consensus

### Level 2: PM/PdM Sync
- **When**: Decisions affect scope, timeline, or product direction
- **Who**: Project Manager + Product Manager (+ tech lead if technical)
- **Resolution**: PM and PdM align and communicate decision back to team

### Level 3: Stakeholder Escalation
- **When**: Decisions have business impact or require executive input
- **Who**: Project Manager escalates to Product Lead or Sponsor
- **Resolution**: Stakeholder decision is communicated by PM to team

---

## Asynchronous Collaboration Best Practices

1. **Document Everything**: Use GitHub issues, PRs, design docs, and Notion/Confluence for decisions and context
2. **Async-First Mindset**: Assume team members are in different timezones; provide context upfront
3. **Clear Owners**: Always name an owner and due date for decisions and action items
4. **Use GitHub as Source of Truth**: Link PRs to issues, reference design docs in PRs, include acceptance criteria
5. **Slack for Urgent**: Use chat for blockers, not for decisions; escalate in writing after
6. **Feedback Loops**: Build in clear review cycles (e.g., design review, code review, QA sign-off)

---

## Collaboration Checklist
- [ ] Project charter and stakeholder list defined
- [ ] Clear owners assigned for each work stream
- [ ] Communication cadence scheduled (daily standups, weekly syncs, demos)
- [ ] GitHub project board or tracking tool configured with all roles visible
- [ ] Definition of Done and acceptance criteria templates agreed
- [ ] Risk register and escalation paths documented
- [ ] Retrospective schedule and format agreed
