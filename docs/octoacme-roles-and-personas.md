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

## QA / Test Engineers

### Role Summary
QA / Test Engineers own product quality. They define how features are tested, validate that work meets its acceptance criteria and give the quality sign-off before a release.

### Responsibilities
- Define the test strategy and initial test plan during project planning
- Review acceptance criteria for clarity and testability
- Write and maintain automated regression, integration and end-to-end smoke tests
- Perform manual and exploratory testing for feature acceptance
- Report, triage and verify defects
- Provide the quality sign-off in the release checklist

### Goals
- Catch defects before they reach customers
- Keep the test suite fast, reliable and trusted by the team
- Make quality visible with clear test results and defect trends

### Typical Communication
- Defect reports and test results in issues and PRs
- Quality status in the weekly delivery sync
- Release readiness sign-off

### Interactions with Existing Roles
- **Developers:** pair on testability, review test coverage in PRs and verify fixes.
- **Product Managers:** refine acceptance criteria and agree on what "done" means for each feature.
- **Project Managers:** report quality risks for the risk register and confirm release readiness.

---

## Executive Sponsors

### Role Summary
Executive Sponsors are accountable for the business outcome of a project. They approve initiatives, secure funding and resources, and make the final call on escalated decisions.

### Responsibilities
- Approve projects at the initiation decision gate
- Secure budget, staffing and cross-team support
- Resolve level 3 (sponsor-level) escalations and business-impacting trade-offs
- Champion the project with senior stakeholders

### Goals
- Ensure the project delivers measurable business value
- Remove organizational blockers quickly
- Keep project priorities aligned with company strategy

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Decision requests and escalations from the Project Manager
- Go/no-go decisions at key gates

### Interactions with Existing Roles
- **Project Managers:** receive status reports and escalations, and make decisions the team cannot.
- **Product Managers:** agree on the problem, success metrics and priority of the initiative.
- **Developers:** are informed of strategic context and decisions through the PM and PdM rather than directly.

---

## DevOps / Release Engineers

### Role Summary
DevOps / Release Engineers own the path to production. They maintain CI/CD pipelines and environments, run deployments and make sure releases can be monitored and rolled back safely.

### Responsibilities
- Build and maintain CI pipelines for tests, linting and security scanning
- Manage staging and production environments
- Run and automate deployments, and own the rollback procedure
- Set up dashboards and alerts for errors, latency and usage
- Lead technical response during deployment incidents and support on-call

### Goals
- Make releases frequent, repeatable and low risk
- Shorten the time from merge to production
- Detect and recover from production issues quickly

### Typical Communication
- Deployment schedules and release announcements
- Pipeline and environment status
- Incident updates and post-incident reviews

### Interactions with Existing Roles
- **Developers:** keep pipelines fast and green, and help diagnose build and deployment failures.
- **Project Managers:** agree on release windows and report deployment risks and outcomes.
- **QA / Test Engineers:** run smoke tests in staging and production as part of each release.

---

## UX Designers

### Role Summary
UX Designers make sure what we build is usable and valuable. They research user needs and turn them into flows, prototypes and designs the team can deliver.

### Responsibilities
- Run user research and usability testing
- Create user flows, wireframes and prototypes
- Define design acceptance criteria and accessibility requirements
- Review implemented features against the design

### Goals
- Deliver intuitive, accessible experiences
- Validate ideas with users before building them
- Keep a consistent design language across products

### Typical Communication
- Design reviews and prototype walkthroughs
- Research findings shared with the team
- Design notes and links in backlog items

### Interactions with Existing Roles
- **Product Managers:** shape problem statements and prioritize based on user research.
- **Developers:** hand off designs, clarify details and review the built experience.
- **Project Managers:** plan design work and research into the timeline and milestones.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

