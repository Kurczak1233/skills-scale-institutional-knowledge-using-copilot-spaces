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

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project. They define testing standards, oversee test execution, and serve as the final quality gate before release. They work closely with Developers and the Project Manager to ensure acceptance criteria are met and defects are resolved before shipping.

### Responsibilities
- Define and maintain the overall test strategy (unit, integration, end-to-end, regression)
- Author and review acceptance criteria and Definition of Done with the Product Manager
- Manage the QA pipeline in CI and track defect metrics
- Coordinate with Developers on bug triage and resolution priority
- Sign off on release readiness from a quality perspective
- Maintain test documentation and QA checklists

### Goals
- Prevent defect leakage into production
- Reduce cycle time for defect detection and resolution
- Establish measurable quality gates at each phase of delivery

### Typical Interactions
- **Developers**: paired review of acceptance criteria, defect triage in daily standups
- **Product Managers**: alignment on acceptance criteria and feature completeness
- **Project Managers**: status updates on test coverage, blocking defects, and release readiness sign-off
- **DevOps Engineer**: collaboration on test environment provisioning and CI pipeline quality gates
- **Lifecycle participation**: Planning (define DoD and test approach), Execution (daily QA, defect tracking), Release (sign-off gate)

---

## UX Designer

### Role Summary
The UX Designer translates user needs and business goals into intuitive, accessible interface designs. They advocate for the end user throughout the delivery lifecycle, from research and wireframes through to final usability validation.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define UX acceptance criteria and accessibility standards
- Collaborate with Developers to ensure design fidelity during implementation
- Review implemented features against design specifications before release

### Goals
- Deliver experiences that are intuitive and accessible to all users
- Reduce usability defects identified post-release
- Create reusable design patterns to accelerate future delivery

### Typical Interactions
- **Developers**: design handoff, implementation review, and guidance on interactive behaviours
- **Product Managers**: alignment on user stories, prioritization of UX debt, and user research findings
- **Project Managers**: scoping design work into sprint capacity and flagging UX blockers
- **Business Analyst**: collaboration on translating requirements into user flows
- **Lifecycle participation**: Initiation (user research, problem framing), Planning (design scope estimation), Execution (design delivery and review)

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business stakeholders and the delivery team. They gather, document, and validate requirements, ensuring that what is built aligns with business intent and measurable outcomes.

### Responsibilities
- Elicit and document requirements through stakeholder interviews and workshops
- Author detailed user stories with clear acceptance criteria
- Facilitate requirement reviews and sign-off with stakeholders
- Identify process gaps, conflicting requirements, and dependencies
- Support UAT (User Acceptance Testing) coordination with stakeholders

### Goals
- Ensure requirements are complete, unambiguous, and testable before development begins
- Reduce rework caused by unclear or changing requirements
- Maintain a shared understanding of scope across technical and non-technical team members

### Typical Interactions
- **Developers**: clarification of requirements during sprint, acceptance criteria refinement
- **Product Managers**: backlog grooming, prioritization input, and roadmap alignment
- **Project Managers**: scope change impact analysis and dependency tracking
- **UX Designer**: collaboration on translating requirements into user flows and wireframes
- **QA Lead**: reviewing acceptance criteria to ensure testability
- **Lifecycle participation**: Initiation (requirements discovery), Planning (backlog refinement), Execution (requirements validation during development)

---

## DevOps Engineer

### Role Summary
The DevOps Engineer designs and maintains the CI/CD pipelines, infrastructure, and deployment automation that enable reliable, repeatable delivery. They are the primary owner of deployment processes and operational observability.

### Responsibilities
- Build and maintain CI/CD pipelines (build, test, deploy automation)
- Manage infrastructure provisioning and configuration as code
- Own deployment runbooks and rollback procedures
- Monitor production systems and maintain alerting and dashboards
- Collaborate with Developers on infrastructure requirements and performance
- Conduct post-deploy verifications and support incident response

### Goals
- Achieve zero-downtime deployments with reliable rollback capability
- Reduce manual steps in the deployment process
- Maintain high system availability and fast incident recovery times

### Typical Interactions
- **Developers**: pipeline integration, environment configuration, and performance guidance
- **Project Managers**: deployment scheduling, release window coordination, and incident status updates
- **QA Lead**: test environment provisioning and CI quality gate configuration
- **Product Managers**: input on release strategy (feature flags, staged rollouts)
- **Lifecycle participation**: Planning (infrastructure scoping), Execution (CI/CD maintenance, environment support), Release (deployment execution and post-deploy verification)

---

## Support Specialist

### Role Summary
The Support Specialist is the voice of the customer within the project team. They surface production issues and user feedback, coordinate with engineering on critical escalations, and ensure customers are informed during incidents and releases.

### Responsibilities
- Triage and respond to customer-reported issues and service requests
- Escalate critical or recurring issues to the Project Manager and development team
- Contribute product feedback and usage patterns to the backlog
- Draft and distribute customer-facing communications during incidents and releases
- Participate in release planning to ensure support documentation is up to date

### Goals
- Minimize customer impact from defects and incidents
- Reduce repeat contacts by driving root-cause fixes
- Maintain customer confidence through clear, timely communication

### Typical Interactions
- **Developers**: issue reproduction, bug reports, and resolution confirmation
- **Product Managers**: feedback loops on customer pain points and feature requests
- **Project Managers**: escalation path for critical production issues and communication planning
- **DevOps Engineer**: coordination during incidents on rollback and recovery actions
- **Lifecycle participation**: Release (release notes review, support readiness), Post-release (incident escalation, feedback capture)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See `octoacme-raci-mapping.md` for a summary of which roles own key artifacts and participate in key meetings.

