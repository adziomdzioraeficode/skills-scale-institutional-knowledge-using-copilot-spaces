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

### Typical Interactions
- Receive feature requirements and acceptance criteria from Product Manager
- Coordinate on estimates, sprint capacity, and blockers with Project Manager
- Work with QA Lead to clarify testability requirements and resolve defects
- Collaborate with UX/UI Designer on implementation of design specs
- Partner with DevOps Engineer on CI/CD pipeline integration and deployment readiness

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

### Typical Interactions
- Align on timeline, scope, and risk with Project Manager
- Provide requirements, acceptance criteria, and prioritization direction to Developers
- Engage UX/UI Designer early in feature definition to ensure usability is designed in
- Collaborate with QA Lead to confirm the Definition of Done and acceptance criteria are testable
- Participate in Go/No-go decisions with Release Manager

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

### Typical Interactions
- Sync weekly with Product Manager on scope, priorities, and risks
- Escalate blockers and resource constraints on behalf of Developers
- Coordinate release scheduling and communications with Release Manager
- Ensure QA Lead has adequate capacity and timeline for testing activities
- Engage DevOps Engineer on deployment windows and infrastructure readiness

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Quality Assurance Lead

### Role Summary
The QA Lead ensures that quality standards are met throughout the delivery lifecycle. They define test strategies, coordinate testing efforts, and validate that features meet the Definition of Done before release.

### Responsibilities
- Define and maintain test strategy and acceptance test plans
- Coordinate and execute functional, regression, and exploratory testing
- Report, track, and verify resolution of defects
- Validate that acceptance criteria and Definition of Done are met before each release
- Champion quality practices across the team, including test automation and code coverage goals
- Participate in sprint reviews and Go/No-go release decisions

### Goals
- Prevent defects from reaching production
- Maintain confidence in every release through structured, repeatable test coverage
- Reduce manual testing overhead through automation over time

### Typical Interactions
- Collaborate with Product Manager to ensure acceptance criteria are clear and testable
- Work closely with Developers to surface defects early and validate fixes
- Coordinate with Release Manager on pre-release readiness and smoke test results
- Inform Project Manager of testing progress and risks to the release timeline

### Typical Communication
- Test plans and test results reports shared with PM, PdM, and Release Manager
- Defect reports and triage sessions with Developers
- Go/No-go sign-off communicated to Release Manager and Project Manager

---

## UX/UI Designer

### Role Summary
UX/UI Designers own the user experience and interface design. They work closely with Product Managers and Developers to ensure solutions are usable, accessible, and aligned with customer needs.

### Responsibilities
- Conduct user research and translate insights into design requirements
- Create wireframes, mockups, and high-fidelity prototypes
- Define usability and accessibility standards for features
- Collaborate with Product Manager to refine feature requirements before development
- Deliver design specs and assets to Developers
- Participate in sprint reviews and demos to evaluate implemented designs
- Iterate on designs based on feedback and usability testing results

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce rework by ensuring design alignment before development begins
- Establish and maintain a consistent visual and interaction language across the product

### Typical Interactions
- Engage early with Product Manager to shape feature requirements and user stories
- Hand off design specs and assets directly to Developers; available during implementation for clarification
- Review implemented features with Developers and QA Lead to confirm design fidelity
- Share prototypes or usability findings with stakeholders during demos and reviews

### Typical Communication
- Design specs, annotated mockups, and asset libraries shared with development team
- Participation in sprint planning and reviews to align on design readiness
- Ad-hoc design feedback during implementation and review cycles

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain the infrastructure, CI/CD pipelines, and deployment automation that enable reliable, repeatable releases. They bridge development and operations to support fast, safe delivery.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Manage infrastructure provisioning, configuration, and monitoring
- Automate deployment, rollback, and environment promotion processes
- Ensure security scanning and compliance checks are integrated into the pipeline
- Collaborate on incident response, root cause analysis, and reliability improvements
- Support Developer onboarding to tooling and environments

### Goals
- Enable fast, reliable, and automated deployments with minimal manual intervention
- Reduce mean time to recovery (MTTR) through observability and automated rollback
- Maintain consistent, reproducible environments across development, staging, and production

### Typical Interactions
- Partner with Developers to integrate builds, tests, and security checks into CI/CD pipelines
- Coordinate deployment windows and infrastructure readiness with Release Manager and Project Manager
- Support QA Lead in provisioning and maintaining test environments
- Respond to and assist with production incidents alongside on-call teams

### Typical Communication
- Pipeline status, deployment readiness reports, and incident postmortems shared with PM and Release Manager
- Technical runbooks and environment setup guides for the development team
- Ad-hoc coordination with Developers during deployments or pipeline failures

---

## Release Manager

### Role Summary
Release Managers orchestrate the end-to-end release process. They coordinate all stakeholders involved in a release, ensure pre-release readiness criteria are met, and own release communications.

### Responsibilities
- Maintain the release calendar and coordinate release scheduling with all teams
- Track pre-release readiness: acceptance criteria, QA sign-off, CI status, rollback plan
- Facilitate Go/No-go decision meetings with PM, PdM, QA Lead, and DevOps Engineer
- Draft and distribute release notes and stakeholder communications
- Oversee deployment execution in partnership with DevOps Engineer
- Ensure rollback plans are documented and validated before every release
- Conduct post-release checks and confirm successful deployment with QA Lead

### Goals
- Deliver releases on schedule with minimal risk and maximum stakeholder confidence
- Maintain a clear, auditable record of release decisions and sign-offs
- Continuously improve the release process based on retrospective learnings

### Typical Interactions
- Coordinate closely with Project Manager on release timelines, scope, and risk
- Obtain final QA sign-off from QA Lead before Go/No-go decision
- Execute deployment steps in partnership with DevOps Engineer
- Communicate release outcomes and next steps to Product Manager and stakeholders

### Typical Communication
- Release readiness checklists and Go/No-go decision records shared with PM, PdM, and QA Lead
- Release notes and deployment announcements distributed to stakeholders and support teams
- Post-release status confirmation to Project Manager and Product Manager

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [Role Handoff Checklist](octoacme-role-handoff-checklist.md) for actionable guidance on key cross-role handoff points.

