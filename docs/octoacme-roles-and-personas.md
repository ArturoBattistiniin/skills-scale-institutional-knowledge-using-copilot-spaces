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

## Engineering Managers

### Role Summary
Engineering Managers support team execution, staffing, and technical delivery health. They connect product priorities, team capacity, and engineering quality while helping the team remove blockers and improve throughput.

### Responsibilities
- Align engineering capacity with roadmap and sprint goals
- Support team planning, hiring, and onboarding needs
- Monitor delivery health, technical debt, and engineering risks
- Partner with PM and Product to resolve prioritization trade-offs
- Coach developers and help maintain sustainable engineering practices

### Goals
- Improve delivery predictability and team health
- Reduce bottlenecks and workflow friction
- Maintain a high-quality engineering culture

### Typical Communication
- Weekly engineering planning and staffing syncs
- Team-level execution updates and dependency reviews
- Cross-functional coordination with PM, Product, and stakeholders

### Interaction with Existing Roles
- Works with Project Managers on timeline realism, resourcing, and risk mitigation
- Works with Product Managers to balance roadmap priorities with delivery capacity
- Supports Developers by clarifying technical constraints and team-level planning decisions

---

## QA / Quality Leads

### Role Summary
QA / Quality Leads define validation standards, testing strategy, and release readiness criteria. They ensure that work is not only built, but also verified against user expectations and acceptance standards.

### Responsibilities
- Define test plans, quality gates, and acceptance validation criteria
- Review requirements for testability and edge cases
- Coordinate manual and automated testing efforts
- Validate release readiness prior to deployment
- Identify quality risks and recommend mitigation actions

### Goals
- Reduce defects and user-facing issues
- Increase confidence in delivery quality
- Support consistent release readiness and operational stability

### Typical Communication
- Test strategy reviews and QA sign-off checkpoints
- Bug triage and release readiness discussions
- Collaboration with Developers, PMs, and stakeholders on acceptance criteria

### Interaction with Existing Roles
- Works with Developers to ensure bugs and fixes are tested and verified
- Partners with Product Managers to confirm that acceptance criteria reflect user value and expected outcomes
- Coordinates with Project Managers on quality milestones, release readiness, and risk communication

---

## Security / Compliance Leads

### Role Summary
Security / Compliance Leads protect the team and the business by ensuring security, privacy, and compliance requirements are addressed throughout the project lifecycle.

### Responsibilities
- Review architecture, data flows, and dependencies for risk exposure
- Define security and compliance controls for features and releases
- Support threat modeling, access reviews, and secure design discussions
- Partner with engineering teams to remediate vulnerabilities and control gaps
- Ensure release readiness includes required security checks and approvals

### Goals
- Reduce security and compliance risk
- Build trust with customers, regulators, and stakeholders
- Ensure projects meet organizational standards before production release

### Typical Communication
- Security review meetings and architecture check-ins
- Risk escalations and exception handling discussions
- Coordination with PMs, Developers, and Release teams before launch

### Interaction with Existing Roles
- Advises Product and Project Managers on risk trade-offs and required controls
- Collaborates with Developers on secure implementation practices and remediation timelines
- Supports Release Managers in confirming deployment readiness and rollback/incident preparedness

---

## Release Managers / Delivery Operations

### Role Summary
Release Managers / Delivery Operations roles coordinate the movement of work from validation into production. They reduce release risk and help ensure that teams communicate clearly before, during, and after deployment.

### Responsibilities
- Schedule deployment windows and coordinate launch readiness
- Prepare release checklists, rollback plans, and communication artifacts
- Validate deployment health and post-release monitoring signals
- Coordinate with cross-functional teams during production changes
- Capture known issues and support communication for stakeholder updates

### Goals
- Minimize release failures and customer disruption
- Improve predictability and consistency of deployment processes
- Strengthen operational readiness across the project lifecycle

### Typical Communication
- Release readiness reviews and go/no-go checkpoints
- Incident and rollback coordination during production changes
- Stakeholder announcements and post-release updates

### Interaction with Existing Roles
- Coordinates with Project Managers on release milestones and stakeholder communications
- Works with Developers and QA leads to confirm feature readiness and smoke-test coverage
- Partners with Security / Compliance Leads to confirm required approvals and mitigation steps

---

## Customer Success / Support Liaisons

### Role Summary
Customer Success / Support Liaisons represent the post-delivery customer perspective. They ensure that product improvements are informed by real user issues, feedback, and support trends.

### Responsibilities
- Collect and triage customer feedback, support cases, and escalation trends
- Surface user pain points and operational issues for prioritization
- Coordinate with Product and Project teams on issue follow-up and communication
- Monitor adoption, satisfaction, and support load after release
- Contribute to release communication and customer-facing guidance

### Goals
- Improve customer satisfaction and retention
- Close the loop between customer feedback and product decisions
- Reduce avoidable support friction and escalations

### Typical Communication
- User feedback reviews and support trend briefings
- Customer-facing updates and issue escalation coordination
- Collaboration with Product, PM, and release stakeholders

### Interaction with Existing Roles
- Provides Product Managers with customer-derived insights that inform prioritization and backlog refinement
- Helps Project Managers identify delivery risk and stakeholder impact associated with customer issues
- Supports Release Managers by sharing customer impact signals and readiness concerns during launch planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles create a clearer picture of accountability, handoffs, and cross-functional collaboration across the project lifecycle.

---

## Cross-functional interaction model
These roles work best when responsibilities are explicit and handoffs are documented:
- Product Managers define outcomes and priorities
- Project Managers coordinate delivery and stakeholder communication
- Engineering Managers support team execution and capacity
- Developers build and validate software changes
- QA / Quality Leads ensure readiness and acceptance criteria are met
- Security / Compliance Leads reduce operational and policy risk
- Release Managers coordinate production rollout and communication
- Customer Success / Support Liaisons connect delivery outcomes to user impact

This model strengthens accountability, improves escalation paths, and helps teams deliver more predictable, higher-quality outcomes.

