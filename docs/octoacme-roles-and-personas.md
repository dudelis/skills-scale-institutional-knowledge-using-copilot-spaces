# OctoAcme Personas

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

## Technical Leads

### Role Summary
Technical Leads provide end-to-end technical direction. They align architecture and delivery choices with product goals while keeping implementation quality high.

### Responsibilities
- Shape solution approach and architecture boundaries
- Break larger initiatives into implementation-ready technical slices
- Guide engineering quality standards and review practices
- Identify technical risks early and define mitigation options
- Coordinate cross-team technical dependencies and integration readiness

### Goals
- Reduce technical ambiguity before execution begins
- Maintain delivery speed without sacrificing code quality
- Improve predictability for integration, testing, and release

### Typical Communication
- Technical discovery notes and architecture trade-off summaries
- Cross-functional planning sessions with Product and Project Managers
- Ongoing code review and dependency-risk updates

### Interaction Points with Existing Roles
- Developers: convert architecture intent into actionable tasks and unblock implementation decisions
- Product Managers: align technical trade-offs with product outcomes and scope priorities
- Project Managers: provide effort/risk input for plans, milestones, and escalations
- QA/Testing: define test strategy inputs for critical paths and integration coverage
- Stakeholders: explain technical constraints, sequencing, and expected delivery impacts

### Lifecycle Ownership Focus
- Initiation: validate feasibility and high-level constraints
- Planning: define implementation approach and dependency sequencing
- Execution: resolve technical blockers and maintain design consistency
- Release: support readiness checks for critical technical risk areas
- Retrospective: drive technical follow-ups that reduce repeat delivery friction

---

## Release Managers

### Role Summary
Release Managers own release readiness and cross-role handoffs from execution through production verification. They ensure releases are coordinated, auditable, and low-risk.

### Responsibilities
- Maintain release readiness criteria and entry/exit gates
- Coordinate release schedules, communication, and deployment windows
- Confirm QA sign-off, rollback readiness, and stakeholder notifications
- Track release risks, unresolved decisions, and final go/no-go ownership
- Capture release outcomes and feed improvements into retrospectives

### Goals
- Increase release consistency and reduce late-stage surprises
- Improve accountability for deployment and post-release verification
- Shorten recovery time when incidents or rollbacks occur

### Typical Communication
- Release readiness check-ins and go/no-go updates
- Deployment timeline announcements and support coordination
- Post-release summaries with actions for future improvements

### Interaction Points with Existing Roles
- Developers: confirm release scope, deployment notes, and production verification owners
- Product Managers: align release content with customer-facing outcomes and messaging
- Project Managers: synchronize release gates with timeline, risks, and stakeholder reporting
- QA/Testing: validate acceptance, regression coverage, and release sign-off status
- Stakeholders: communicate release timing, status, and business impact updates

### Lifecycle Ownership Focus
- Initiation: flag release/compliance constraints that affect planning
- Planning: establish release gates and handoff responsibilities
- Execution: monitor readiness drift and dependency completion
- Release: lead final go/no-go coordination and communication
- Retrospective: capture release lessons and process improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the [Lifecycle RACI Matrix Template](octoacme-raci-matrix-template.md) to assign accountable owners by phase and reduce role ambiguity.
