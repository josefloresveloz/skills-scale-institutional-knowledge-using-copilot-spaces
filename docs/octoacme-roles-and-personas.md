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

## Release Manager

### Role Summary
Coordinates and owns release planning, deployment readiness, and communications during releases.

### Responsibilities
- Manage the release schedule and maintain the release checklist
- Coordinate deployments with CI/CD pipelines and operations teams
- Own rollback and mitigation plans
- Communicate release windows and status to stakeholders
- Verify post-release smoke checks

### Goals
- Ensure smooth, predictable, and low-risk releases
- Maintain clear audit trails and release documentation
- Enable the team to ship confidently and recover quickly if issues arise

### Typical Communication / Interactions
- Works closely with **Developers** to confirm merge readiness and build artifact status
- Coordinates with **QA Analysts** to obtain test sign-off and smoke test results before and after release
- Aligns with **Product Managers / PdMs** on release scope, timing, and feature flags
- Syncs with **Project Managers** to coordinate cross-team dependencies
- Communicates with **Stakeholders** to announce release windows and validate business readiness

> **Example handoff:** When a build is ready to promote to production, the Release Manager confirms with QA Analysts that all acceptance tests have passed, notifies Stakeholders of the release window, and verifies that Developers have documented any rollback steps.

---

## QA Analyst

### Role Summary
Owns testing strategy and execution, verifies acceptance criteria and quality gates.

### Responsibilities
- Create and maintain test plans aligned to acceptance criteria
- Run and coordinate automated and manual tests
- Report defects with clear reproduction steps and severity
- Verify fixes and track defect resolution
- Sign off on releases against defined quality gates

### Goals
- Prevent regressions and ensure acceptance criteria are met before release
- Increase test automation coverage over time
- Provide timely, actionable quality feedback to the team

### Typical Communication / Interactions
- Collaborates with **Developers** on testability, bug reproduction, and fix verification
- Partners with **Product Managers** to clarify and refine acceptance criteria
- Provides release sign-off to the **Release Manager** before deployments proceed
- Notifies **Project Managers** of any quality issues that may impact the schedule

> **Example handoff:** Before a release, the QA Analyst runs the regression suite, confirms all critical flows pass, and sends a written sign-off to the Release Manager so the release can proceed.

---

## UX Designer

### Role Summary
Ensures usability, accessibility, and a coherent user experience across features.

### Responsibilities
- Define UX requirements and design guidelines for features
- Create and review wireframes and prototypes
- Conduct lightweight usability checks during development
- Update design assets (e.g., Figma) and provide implementation guidance to developers
- Validate that delivered UI meets design intent before release

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce back-and-forth between design and development through clear specs
- Advocate for the end user throughout the project lifecycle

### Typical Communication / Interactions
- Engages with **Product Managers** during discovery and scoping to align on user needs
- Provides design specs and guidance to **Developers** during implementation
- Works with **QA Analysts** to ensure acceptance scenarios include UX and accessibility checks
- Participates in user validation sessions with **Stakeholders** when needed

> **Example handoff:** After completing wireframes for a new feature, the UX Designer reviews them with the Product Manager for alignment, then shares annotated design files with Developers and QA Analysts to guide implementation and testing.

---

## Stakeholder (Business Sponsor)

### Role Summary
Provides strategic direction, approves funding and scope, removes high-level blockers, and arbitrates prioritization when necessary.

### Responsibilities
- Set business goals and success criteria for the project
- Approve major trade-offs involving scope, budget, or timeline
- Participate in key milestones (kickoff, major release approvals)
- Accept final deliverables and confirm business value is realized

### Goals
- Ensure the project delivers measurable business outcomes
- Keep the project aligned with organizational strategy
- Unblock critical decisions quickly to maintain delivery momentum

### Typical Communication / Interactions
- Receives regular updates from **Product Managers** and **Project Managers** on progress and risks
- Engages with the **Release Manager** for launch approvals and business readiness confirmation
- Provides prioritization input to **Product Managers** when trade-offs arise

> **Example handoff:** At a major release milestone, the Release Manager and Product Manager present a readiness summary to the Stakeholder for final approval. The Stakeholder confirms business readiness and gives the go/no-go decision before the production deployment proceeds.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

