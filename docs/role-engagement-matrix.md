# Role Engagement Matrix

## Purpose
Clarify which personas are engaged at each phase of the project lifecycle, ensuring appropriate involvement and reducing gaps in accountability.

## Matrix Overview

| Phase | Developer | Product Manager | Project Manager | UX Designer | Data Analyst | Customer Success Manager | Security Lead |
|-------|-----------|-----------------|-----------------|-------------|-------------|--------------------------|---------------|
| **Initiation** | Support | Lead | Lead | Support | Support | Support | Support |
| **Planning** | Lead | Lead | Lead | Lead | Support | Support | Support |
| **Execution** | Lead | Support | Support | Lead | Support | Support | Lead (reviews) |
| **Testing & QA** | Support | Support | Support | Lead (validation) | Lead (metrics) | Support | Lead (security testing) |
| **Release** | Support | Lead | Lead | Support | Lead | Lead | Lead (approvals) |
| **Operations** | Support | Support | Support | Support | Lead | Lead | Lead |
| **Retrospective** | Participant | Lead | Lead | Participant | Lead | Participant | Participant |

### Legend
- **Lead**: Primary responsibility and decision-making authority
- **Support**: Active participation and input; supports the lead
- **Participant**: Attends and contributes as appropriate to their expertise

---

## Detailed Phase Breakdowns

### Initiation Phase
**Goal**: Validate problem, define business case, align stakeholders

| Role | Responsibility | Key Activities |
|------|---|---|
| **Product Manager** | Lead | Define problem, goals, success metrics |
| **Project Manager** | Lead | Develop initial timeline, resource estimate |
| **Developer** | Support | Validate technical feasibility, identify risks |
| **UX Designer** | Support | Share user research or design constraints |
| **Data Analyst** | Support | Confirm metrics strategy |
| **Security Lead** | Support | Identify security requirements |
| **Customer Success Manager** | Support | Provide customer feedback and market context |

**Deliverables**: Project One-pager, Stakeholder List, Initial Risk Register

---

### Planning Phase
**Goal**: Create detailed project plan, define backlog, identify dependencies

| Role | Responsibility | Key Activities |
|------|---|---|
| **Product Manager** | Lead | Refine backlog, define acceptance criteria, prioritize |
| **Project Manager** | Lead | Create detailed timeline, allocate resources, plan milestones |
| **Developer** | Lead | Estimate work, identify technical dependencies, define DoD |
| **UX Designer** | Lead | Create wireframes, design specs, usability testing plan |
| **Data Analyst** | Support | Define success metrics, identify instrumentation needs |
| **Security Lead** | Support | Define security requirements and design patterns |
| **Customer Success Manager** | Support | Prioritize customer needs, provide feedback |

**Deliverables**: Detailed Backlog, Release Plan, Design Specs, Risk Register, Definition of Done

---

### Execution Phase
**Goal**: Build and test features, manage progress and blockers

| Role | Responsibility | Key Activities |
|------|---|---|
| **Developer** | Lead | Implement features, write tests, participate in code reviews |
| **UX Designer** | Lead | Review UI/UX implementation, coordinate design iterations |
| **Project Manager** | Support | Manage schedule, track dependencies, escalate blockers |
| **Product Manager** | Support | Clarify requirements, adjust priorities based on progress |
| **Security Lead** | Lead (async) | Review PRs for security, advise on secure patterns |
| **Data Analyst** | Support | Monitor early signals if applicable |
| **Customer Success Manager** | Support | Share customer feedback that impacts execution |

**Deliverables**: Completed Features, Passing Tests, Code Review Comments, Risk Updates

---

### Testing & QA Phase
**Goal**: Validate quality, user experience, and security readiness

| Role | Responsibility | Key Activities |
|------|---|---|
| **QA/Testing** | Lead | Execute test plan, document defects, validate fixes |
| **UX Designer** | Lead | Validate UI/UX against specs, coordinate usability feedback |
| **Data Analyst** | Lead | Verify instrumentation, confirm metric tracking works |
| **Developer** | Support | Fix defects, assist with test troubleshooting |
| **Product Manager** | Support | Validate acceptance criteria, approve feature readiness |
| **Security Lead** | Lead | Run security tests, validate compliance |
| **Customer Success Manager** | Support | Coordinate user feedback if UAT is planned |

**Deliverables**: QA Sign-off, Security Approval, Metrics Instrumentation Confirmed, Release Ready Status

---

### Release & Deployment Phase
**Goal**: Deploy to production safely, verify functionality, communicate impact

| Role | Responsibility | Key Activities |
|------|---|---|
| **Project Manager** | Lead | Coordinate deployment window, manage rollout |
| **Product Manager** | Lead | Finalize release notes, manage stakeholder comms |
| **Customer Success Manager** | Lead | Communicate to customers, manage support escalation |
| **Data Analyst** | Lead | Monitor success metrics, confirm instrumentation, prepare dashboards |
| **Developer** | Support | Provide technical support during deployment, assist with rollback if needed |
| **Security Lead** | Lead | Monitor security alerts, authorize deployment |
| **UX Designer** | Support | Be available for rapid UX adjustments if needed |

**Deliverables**: Release Notes, Customer Communications, Deployment Verification, Metrics Dashboard

---

### Operations & Monitoring Phase
**Goal**: Ensure system stability, monitor user adoption, identify improvement areas

| Role | Responsibility | Key Activities |
|------|---|---|
| **Data Analyst** | Lead | Track success metrics, identify trends, report on impact |
| **Customer Success Manager** | Lead | Monitor customer feedback, identify support issues |
| **Security Lead** | Lead | Monitor security alerts, respond to incidents |
| **Developer** | Support | Address critical defects, assist with incident response |
| **Product Manager** | Support | Review metrics, prioritize improvements based on data |
| **Project Manager** | Support | Manage incident response coordination if needed |
| **UX Designer** | Support | Analyze user feedback, plan UX improvements |

**Deliverables**: Weekly Metrics Reports, Customer Feedback Summaries, Incident Reports

---

### Retrospective & Continuous Improvement Phase
**Goal**: Capture learnings, plan improvements, celebrate wins

| Role | Responsibility | Key Activities |
|------|---|---|
| **Project Manager** | Lead | Facilitate retrospective, capture action items |
| **Product Manager** | Lead | Review product learnings, plan next iterations |
| **Data Analyst** | Lead | Present project metrics, analyze process efficiency |
| **Developer** | Participant | Share technical learnings, contribute to improvements |
| **UX Designer** | Participant | Share design learnings, discuss usability insights |
| **Security Lead** | Participant | Review security incidents, plan preventive measures |
| **Customer Success Manager** | Participant | Share customer impact and feedback themes |

**Deliverables**: Retrospective Notes, Action Items with Owners, Process Improvements, Metrics Summary

---

## Decision Matrix: When to Escalate to Each Role

| Scenario | Primary Contact | Secondary Input |
|----------|---|---|
| Feature scope or prioritization change | Product Manager | Project Manager, UX Designer |
| Timeline or resource constraint | Project Manager | Product Manager, Developer |
| User experience concern | UX Designer | Product Manager, Developer |
| Security or compliance question | Security Lead | Developer, Project Manager |
| Customer impact question | Customer Success Manager | Product Manager, Data Analyst |
| Success metric interpretation | Data Analyst | Product Manager, Project Manager |
| Technical feasibility question | Developer | Security Lead, Project Manager |

---

## Usage Guidelines

1. **During Project Kickoff**: Review this matrix with the team to confirm roles and engagement expectations.
2. **During Planning**: Use to ensure all required roles are involved in planning activities.
3. **During Execution**: Reference to confirm who should be in each meeting and decision point.
4. **During Retrospectives**: Update based on team learnings about effective collaboration.

---

## Notes
- This matrix assumes all roles are present on the project. Adapt for smaller teams by combining roles.
- Some roles may be shared across projects; adjust involvement levels based on capacity.
- Use the Persona Interaction Matrix in `octoacme-roles-and-personas.md` for more detail on specific working relationships.
