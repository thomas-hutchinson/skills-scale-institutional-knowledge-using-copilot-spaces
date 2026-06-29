# OctoAcme Personas

This document defines typical roles, responsibilities, and collaboration points used in OctoAcme project docs and exercises.

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

## QA / Testing

### Role Summary
QA and testing specialists validate that delivered work meets acceptance criteria, quality standards, and release expectations before it reaches customers.

### Responsibilities
- Build and maintain the test approach for features, regressions, and release readiness
- Validate acceptance criteria and identify gaps before work is marked done
- Triage defects with Developers and confirm fixes
- Highlight quality risks, test coverage gaps, and release blockers early

### Goals
- Prevent escaped defects and rework
- Make quality status visible before release decisions
- Keep validation fast enough to support iterative delivery

### Typical Communication
- Test plans, bug reports, and release-readiness updates
- Defect triage with Developers and Technical Leads
- Exit-criteria reviews with Product Managers and Project Managers

### Interaction Points
- **Developers:** align on test scenarios, reproduce defects, and confirm fix readiness.
- **Product Managers:** verify acceptance criteria, edge cases, and customer-impact expectations.
- **Project Managers:** surface quality risks, test milestones, and release blockers early enough to adjust timelines.

---

## Engineering Managers

### Role Summary
Engineering Managers are accountable for team capacity, execution health, and delivery sustainability across the project lifecycle.

### Responsibilities
- Manage team capacity, staffing, and delivery risk removal
- Coach Developers and Technical Leads on execution practices
- Support dependency management and cross-team coordination
- Escalate staffing or process constraints that threaten delivery

### Goals
- Keep delivery predictable and sustainable
- Maintain healthy team throughput and ownership
- Resolve organizational blockers quickly

### Typical Communication
- Capacity and staffing discussions
- Delivery health reviews and escalation summaries
- Cross-team coordination with engineering counterparts

### Interaction Points
- **Developers:** unblock execution, coach on ownership, and align workload with priorities.
- **Product Managers:** clarify feasibility trade-offs and capacity impacts of priority changes.
- **Project Managers:** review schedule risk, dependency pressure, and mitigation options.

---

## Technical Leads / Staff Engineers

### Role Summary
Technical Leads guide solution design, technical decision-making, and implementation quality across the team.

### Responsibilities
- Shape architecture and implementation approach
- Break down complex work into executable increments
- Set expectations for non-functional requirements, observability, and maintainability
- Lead technical risk identification and mitigation planning

### Goals
- Deliver solutions that are scalable, supportable, and practical
- Reduce ambiguity in technical direction
- Balance speed with long-term maintainability

### Typical Communication
- Design reviews and architecture notes
- Technical trade-off discussions
- Implementation guidance during planning and execution

### Interaction Points
- **Developers:** provide technical direction, review patterns, and remove design ambiguity.
- **Product Managers:** translate user outcomes into feasible technical options and trade-offs.
- **Project Managers:** identify dependencies, sequencing risks, and technical decision deadlines.

---

## UX / UI Designers

### Role Summary
UX and UI Designers define user flows, interaction patterns, and design specifications that help teams deliver usable, accessible solutions.

### Responsibilities
- Turn problem statements into user journeys, wireframes, and prototypes
- Validate usability assumptions with Product Managers and stakeholders
- Provide implementation-ready design specifications and accessibility guidance
- Clarify design trade-offs when scope or timelines change

### Goals
- Reduce rework caused by unclear user experience expectations
- Improve usability and accessibility from the start
- Help teams make fast, informed design decisions

### Typical Communication
- Discovery workshops and design reviews
- Wireframes, prototypes, and annotated specs
- Feedback loops with Product Managers, Developers, and QA

### Interaction Points
- **Developers:** provide implementation-ready assets and resolve edge-case questions during build.
- **Product Managers:** align on user problems, success criteria, and scope trade-offs.
- **Project Managers:** flag design dependencies, review timing, and asset delivery expectations.

---

## Security / Compliance Leads

### Role Summary
Security and compliance leads ensure product changes meet security, privacy, and regulatory expectations without creating late delivery surprises.

### Responsibilities
- Define required controls, review risk areas, and advise on mitigation plans
- Participate in threat modeling and release-readiness checks for sensitive changes
- Confirm compliance evidence is captured when required
- Escalate unresolved risks that affect scope, release timing, or customer impact

### Goals
- Reduce security and compliance risk before release
- Make required controls visible early in planning
- Prevent last-minute approval bottlenecks

### Typical Communication
- Risk reviews and threat-model outputs
- Security sign-off notes and control checklists
- Escalations for unresolved compliance blockers

### Interaction Points
- **Developers:** advise on secure implementation, testing expectations, and remediation priorities.
- **Product Managers:** clarify compliance-driven requirements and trade-offs that affect scope.
- **Project Managers:** highlight approval lead times, risk status, and escalation paths before release.

---

## Customer Support / Enablement Representatives

### Role Summary
Customer support and enablement representatives bring customer-impact insights into delivery and prepare downstream teams for change.

### Responsibilities
- Share recurring customer pain points and operational concerns
- Prepare support content, known-issue notes, and release readiness materials
- Feed post-release issues and adoption insights back into the backlog
- Help coordinate incident communication when customer-facing issues occur

### Goals
- Reduce avoidable customer confusion during releases
- Improve adoption by preparing support and enablement teams early
- Shorten the feedback loop from production issues to product decisions

### Typical Communication
- Release briefings and known-issue summaries
- Customer trend reporting and escalation updates
- Support readiness reviews with delivery leads

### Interaction Points
- **Developers:** provide reproducible issue details and validate workarounds or fixes.
- **Product Managers:** share customer themes that influence prioritization and rollout planning.
- **Project Managers:** align on launch timing, communication readiness, and incident escalation expectations.

---

## Role Interaction Matrix

| Collaboration | Lifecycle stage | Expected outputs |
| --- | --- | --- |
| Product Manager + Project Manager | Initiation, Planning, Release | Approved one-pager, shared priorities, stakeholder-ready status narrative |
| Product Manager + Technical Lead | Initiation, Planning, Execution | Feasible solution options, clarified acceptance criteria, technical trade-offs |
| Project Manager + Engineering Manager | Planning, Execution, Release | Capacity plan, dependency escalations, mitigation decisions |
| Developers + QA / Testing | Planning, Execution, Release | Test scenarios, defect triage outcomes, release-quality evidence |
| UX / UI Designer + Product Manager + Developers | Initiation, Planning, Execution | User flows, prototypes, implementation-ready design notes |
| Security / Compliance Lead + Technical Lead + Project Manager | Planning, Execution, Release | Risk assessment, required controls, approval timeline |
| Customer Support / Enablement + Product Manager + Project Manager | Release, Retrospective | Launch communications, known-issue summary, customer feedback themes |
| Project Manager + All role leads | Retrospective | Improvement actions, owners, due dates, process updates |

## Handoff Points by Lifecycle Phase

| Phase | Primary handoff | What must be handed off | Expected output |
| --- | --- | --- | --- |
| Initiation | Product Manager → Project Manager, Technical Lead, UX / UI Designer | Problem statement, success metrics, initial scope, stakeholder list | Approved one-pager and kickoff agenda |
| Planning | Project Manager → Delivery team leads | Milestones, dependencies, decision deadlines, release target | Prioritized backlog, capacity-aware plan, named owners |
| Execution | Technical Lead + Developers → QA / Testing, Product Manager | Build status, test evidence, unresolved risks, demo-ready increment | Validated increment and updated risk status |
| Release | QA / Testing + Technical Lead → Project Manager, Product Manager, Customer Support / Enablement | Exit-criteria status, known issues, rollback plan, support notes | Go / no-go decision and release communication pack |
| Retrospective | Project Manager → All project roles | Delivery metrics, incident notes, customer feedback, action-item proposals | Agreed improvements with owners and due dates |

## Decision Ownership Guidance

Use the table below as a lightweight RACI-style reference when a decision affects scope, timing, or customer impact.

| Decision | Accountable owner | Primary contributors | Consult / inform | Record in |
| --- | --- | --- | --- | --- |
| Prioritization and backlog ordering | Product Manager | Technical Lead, Engineering Manager | Project Manager, Customer Support / Enablement | Backlog notes or roadmap update |
| Scope changes after planning | Product Manager | Project Manager, Technical Lead | Engineering Manager, stakeholders | Decision log with impact summary |
| Release go / no-go | Project Manager | Technical Lead, QA / Testing | Product Manager, Customer Support / Enablement | Release checklist and status update |
| Incident communication | Project Manager | Engineering Manager, Technical Lead | Product Manager, Customer Support / Enablement, stakeholders | Incident channel update and follow-up summary |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
