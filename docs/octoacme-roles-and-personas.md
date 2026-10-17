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

## Additional Personas (proposed additions)

Below are proposed additional personas to add into the Roles & Personas document. Each entry includes a short role summary, responsibilities, and how the persona typically interacts with existing roles. These aim to reduce ambiguity, improve handoffs, and clarify ownership across delivery and operational concerns.

### Technical Program Manager (TPM)

Role Summary
- Coordinates large cross-team technical efforts, integration points, and program-level schedules.

Responsibilities
- Manage program-level timelines and milestones across multiple teams.
- Track cross-team dependencies and ensure integration readiness.
- Facilitate technical risk identification and mitigation across squads.
- Drive alignment on technical scopes and interface contracts.

Interactions
- Works closely with Project Managers (scheduling), Engineering Managers (capacity & resourcing), and Product Managers (prioritization of cross-team work).
- Escalates unresolved technical dependencies or systemic risks to Product Leads or sponsors.

---

### Release Manager

Role Summary
- Owns release coordination, deployment readiness, and post-release verification planning.

Responsibilities
- Maintain the release calendar and coordinate release windows.
- Ensure deployment runbooks, rollback plans, and release notes are prepared.
- Coordinate cross-team cutovers, migrations, and deployment checks.
- Lead post-release verification and capture release incidents.

Interactions
- Coordinates with Developers, QA, SRE/Platform, and PM to confirm readiness.
- Works with the PM and Product Manager to schedule releases and communicate stakeholder impacts.
- Notifies Customer Success/Support of release content and known issues.

---

### Site Reliability / Platform Lead (SRE)

Role Summary
- Ensures production reliability and observability; owns operational readiness and incident response integration.

Responsibilities
- Define and maintain SLOs, monitoring, and alerting requirements for features.
- Review system architecture and capacity planning for changes.
- Integrate on-call and runbook requirements into the project plan.
- Lead incident response coordination and post-incident reviews.

Interactions
- Collaborates with Developers and Release Manager for deploy safety and verification.
- Advises PM/PdM on operational risk and capacity implications.
- Works with Data Analysts on telemetry and with Security Liaison on operational security constraints.

---

### UX Researcher / Designer Liaison

Role Summary
- Ensures user research and design inputs drive feature acceptance and shape backlog priorities.

Responsibilities
- Conduct or synthesize user research and usability testing relevant to the project.
- Provide design specifications and UX acceptance criteria.
- Validate user flows and accessibility requirements.
- Help the team interpret research findings into actionable backlog items.

Interactions
- Partners with Product Managers on prioritization and acceptance criteria.
- Works with Developers and QA to ensure designs are implemented correctly and validated.
- Engages with Customer Success for user feedback when applicable.

---

### Data Analyst / Metrics Owner

Role Summary
- Defines outcome metrics, ensures telemetry is implemented, and analyzes results post-release.

Responsibilities
- Define success metrics and dashboards to measure impact.
- Specify instrumentation and event schemas needed for analysis.
- Validate that telemetry is landed and data quality is sufficient.
- Run post-release analysis and recommend follow-up actions.

Interactions
- Works with Product Managers to define success criteria.
- Coordinates with Developers to implement instrumentation.
- Shares insights with PM, PdM, and stakeholders to inform iterations.

---

### Security / Compliance Liaison

Role Summary
- Ensures security, privacy, and regulatory requirements are identified and addressed early in the project lifecycle.

Responsibilities
- Perform early security reviews and threat modeling when needed.
- Surface compliance requirements and required artifacts (e.g., data handling).
- Recommend mitigations and track security work items.
- Sign off on release readiness from a security/compliance perspective.

Interactions
- Coordinates with Developers and Architects to implement security controls.
- Works with PM to incorporate security tasks into planning and risk registers.
- Escalates critical security issues to Product Leads and Security leadership.

---

### Customer Success / Support Representative

Role Summary
- Brings customer-facing knowledge to planning and owns support readiness and post-release client communications.

Responsibilities
- Provide insights on customer impact, common support patterns, and operational concerns.
- Prepare support playbooks and known-issues documentation for release.
- Collect feedback from customers and triage issues for the team.
- Assist with rollout communications and enablement materials.

Interactions
- Feeds customer-facing considerations to Product Managers and PMs.
- Works with Developers and QA on reproducibility and supportability of issues.
- Partners with Release Manager for go/no-go and post-release monitoring.

---

### Business Analyst (BA)

Role Summary
- Translates stakeholder needs into detailed requirements, acceptance criteria, and maintains traceability.

Responsibilities
- Capture and refine business requirements and user stories.
- Define acceptance criteria and ensure testability of requirements.
- Maintain requirement traceability and support UAT activities.
- Help clarify scope and edge cases before development.

Interactions
- Works closely with Product Managers to refine scope and priorities.
- Liaises with Developers and QA to ensure shared understanding of requirements.
- Coordinates with Stakeholders and PM for sign-offs and acceptance.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---
