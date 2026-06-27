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

## QA / Testing

### Role Summary
QA validates that features meet acceptance criteria and quality standards through testing and verification.

### Responsibilities
- Define and execute test plans (unit, integration, manual)
- Coordinate verification of acceptance criteria
- Report defects and track resolution
- Collaborate with Developers on testability and automation

### Goals
- Ensure product quality and reliability
- Identify regressions before release
- Improve test coverage and automation over time

### Typical Communication
- Bug reports and triage meetings
- QA sign-off in PRs or release checklists
- Test status in weekly syncs

---

## Additional Suggested Personas (New additions)

To improve clarity and accountability, add the following personas. Each entry below follows the pattern of Role Summary, Responsibilities, Goals, and Typical Communication.

- Delivery Lead
  - Role Summary: Oversees day-to-day delivery across multiple teams or streams to ensure coordinated, predictable outcomes.
  - Responsibilities:
    - Coordinate sequencing of backlog items across teams
    - Track and remove cross-team impediments
    - Maintain release schedule and milestone tracking
    - Liaise with Release Manager to ensure readiness
  - Goals:
    - Improve predictability of delivery
    - Minimize cross-team blockers and delays
  - Typical Communication:
    - Daily/weekly delivery syncs, escalation to PMs, status updates to stakeholders

- Engineering Manager
  - Role Summary: Provides technical leadership, resource planning, and development team health oversight.
  - Responsibilities:
    - Coach and mentor engineers; manage capacity and resourcing
    - Drive technical roadmaps and prioritize technical debt
    - Resolve escalated technical blockers
  - Goals:
    - Maintain team performance and engineering quality
    - Balance delivery demands with technical sustainability
  - Typical Communication:
    - One-on-ones, technical design reviews, capacity planning sessions

- UX Researcher / Designer
  - Role Summary: Ensures product designs meet user needs through research, testing, and design guidance.
  - Responsibilities:
    - Run user research and usability testing
    - Produce design assets and interaction patterns
    - Validate acceptance criteria from a UX perspective
  - Goals:
    - Improve usability and adoption of features
  - Typical Communication:
    - Design reviews, handoffs to developers, input to acceptance criteria

- Security Engineer
  - Role Summary: Ensures product and processes meet security requirements and mitigates risks throughout the lifecycle.
  - Responsibilities:
    - Perform threat modeling and security reviews of designs and PRs
    - Define and maintain security CI checks and guidance
    - Lead remediation plans for security findings
  - Goals:
    - Reduce security risk to acceptable levels prior to release
  - Typical Communication:
    - Security review comments in PRs, escalations to PM/Project Manager for schedule impact

- Data Analyst
  - Role Summary: Defines success metrics, builds dashboards, and analyzes outcomes post-release.
  - Responsibilities:
    - Work with PdM to define measurable success criteria
    - Instrument metrics and create dashboards for monitoring
    - Analyze release impact and inform retrospectives
  - Goals:
    - Ensure data-informed decisions and measurable outcomes
  - Typical Communication:
    - Metrics reports to PdM, release verification summaries

- Support / Customer Success Liaison
  - Role Summary: Bridges the customer-facing teams and delivery teams to ensure customer issues and feedback are captured and prioritized.
  - Responsibilities:
    - Surface customer-impacting issues and trends
    - Coordinate incident communications and follow-ups
    - Help prioritize urgent support-driven fixes
  - Goals:
    - Improve customer satisfaction and reduce time-to-resolution
  - Typical Communication:
    - Incident updates, customer feedback summaries, prioritization meetings

- Release Manager
  - Role Summary: Coordinates the operational aspects of releasing software safely and reliably.
  - Responsibilities:
    - Own the release checklist and runbook
    - Verify rollback plans and release readiness
    - Coordinate deployments and post-deploy verification
  - Goals:
    - Ensure smooth, observable, and reversible releases
  - Typical Communication:
    - Release briefings, verification notes, coordination with Delivery Lead and QA

- QA Lead
  - Role Summary: Defines QA strategy and coordinates test activities across teams.
  - Responsibilities:
    - Own test coverage strategy and manual testing plans
    - Coordinate test resources and sign-offs for releases
    - Drive improvements in test automation and processes
  - Goals:
    - Improve testing effectiveness and release confidence
  - Typical Communication:
    - QA status reports, test plan reviews, acceptance criteria verification

---

## How to use these personas
- Add a named owner to major artifacts (e.g., Release Manager on release notes, Data Analyst on dashboards)
- Use the Typical Communication fields to determine who to invite to meetings and reviews
- Include persona ownership in the Project One-pager and project README for clarity
