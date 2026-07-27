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

## Engineering Leads

### Role Summary
Engineering Leads translate product goals into a feasible technical approach. They align implementation choices, surface delivery trade-offs, and keep technical decisions connected to project outcomes.

### Responsibilities
- Shape solution options, architecture boundaries, and delivery sequencing
- Partner with Developers on estimates, technical risks, and dependency planning
- Review technical trade-offs with Product Managers and Project Managers
- Confirm the team has a clear implementation and rollout approach
- Support release readiness and retrospective follow-through for technical action items

### Goals
- Keep delivery technically feasible and maintainable
- Reduce rework caused by unclear technical direction
- Make dependencies, constraints, and trade-offs visible early

### Typical Communication
- Technical design notes and implementation guidance
- Planning discussions on estimates, risks, and sequencing
- Release readiness reviews and post-release follow-ups

### Interaction Points
- **Developers**: clarify implementation direction, review trade-offs, and unblock design decisions
- **Product Managers**: align on scope, feasibility, and cost of product decisions
- **Project Managers**: confirm delivery sequencing, dependencies, and milestone risk
- **QA/Testing**: align on quality risks, test strategy, and release confidence
- **Stakeholders**: explain technical implications of timeline or scope changes when needed

---

## QA / Testing Leads

### Role Summary
QA / Testing Leads define how quality will be validated across the project lifecycle. They make acceptance expectations testable and help the team release with confidence.

### Responsibilities
- Turn acceptance criteria into a practical test approach
- Identify coverage gaps, regression risks, and release validation needs
- Coordinate manual, automated, and smoke-test expectations
- Flag quality blockers early and track them to resolution
- Contribute release sign-off input and retrospective quality improvements

### Goals
- Catch defects before release
- Make quality expectations visible before execution starts
- Improve release confidence without slowing delivery unnecessarily

### Typical Communication
- Test plans, test cases, and coverage notes
- Defect triage updates and release-readiness feedback
- Retrospective input on escaped defects and process gaps

### Interaction Points
- **Developers**: review acceptance criteria, reproduce defects, and align on test coverage
- **Product Managers**: confirm expected behavior and acceptance outcomes
- **Project Managers**: communicate quality risk, test status, and sign-off timing
- **Stakeholders**: share release-readiness concerns or validation results when approvals are needed

---

## Sponsors / Business Stakeholders

### Role Summary
Sponsors / Business Stakeholders provide business context, approve major decisions, and confirm that delivery stays aligned to the intended outcome. They are the escalation point for priority, scope, and business-impact trade-offs.

### Responsibilities
- Confirm the problem to solve, desired outcome, and success measures
- Approve major scope, timeline, or funding changes
- Provide timely input on priority, risk tolerance, and release readiness
- Remove organizational blockers that the delivery team cannot solve alone
- Participate in milestone reviews and retrospectives when business decisions are involved

### Goals
- Ensure the project delivers meaningful business value
- Keep high-impact decisions moving without ambiguity
- Maintain alignment between delivery plans and business priorities

### Typical Communication
- Kickoff approvals and milestone reviews
- Status updates focused on outcomes, risks, and decisions needed
- Go / no-go input for major releases or scope changes

### Interaction Points
- **Developers**: provide business context when implementation trade-offs affect scope or timing
- **Product Managers**: align on priorities, success metrics, and customer outcomes
- **Project Managers**: approve plans, respond to escalations, and unblock cross-functional decisions
- **QA/Testing**: review readiness findings when release quality affects business commitments

---

## Lifecycle Ownership Guide

| Lifecycle phase | Primary owner | Key supporting roles | Typical accountability checkpoints |
|---|---|---|---|
| Initiation | Product Manager | Sponsor / Business Stakeholder, Project Manager | Problem statement agreed, success metrics named, sponsor identified |
| Planning | Project Manager | Product Manager, Engineering Lead, QA / Testing Lead, Developers | Backlog shaped, estimates reviewed, RACI matrix completed, dependencies assigned |
| Execution | Engineering Lead | Developers, Project Manager, QA / Testing Lead | Technical decisions documented, blockers escalated, quality status visible |
| Release | Project Manager | QA / Testing Lead, Engineering Lead, Product Manager, Stakeholders | Release readiness reviewed, approvals confirmed, communication sent |
| Retrospective | Project Manager | Product Manager, Engineering Lead, QA / Testing Lead, Developers, Stakeholders | Action items captured with owners and due dates |

Use the [RACI matrix template](octoacme-raci-matrix-template.md) when a project needs explicit ownership for approvals, handoffs, or cross-team decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
