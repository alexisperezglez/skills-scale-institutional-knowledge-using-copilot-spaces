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

### Interactions with other roles
- **Product Managers**: receive feature specs and acceptance criteria; provide technical feedback on feasibility and trade-offs.
- **Project Managers**: report progress, flag blockers, and participate in planning and retrospectives.
- **UX/UI Designers**: implement designs and provide feedback on technical constraints; review UI in staging.
- **DevOps Engineers**: collaborate on CI/CD pipelines, branching conventions, and deployment automation.
- **Business Analysts**: clarify requirements and acceptance criteria during refinement and sprint planning.
- **Data Analysts**: implement instrumentation and event tracking as defined in backlog items.

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

### Interactions with other roles
- **Project Managers**: align on delivery timelines, scope trade-offs, and risk prioritization.
- **Developers**: define acceptance criteria, review implementations, and validate shipped features.
- **UX/UI Designers**: collaborate on user research and review prototypes before development begins.
- **Business Analysts**: receive refined business requirements and co-author user stories.
- **Data Analysts**: co-define success metrics and review experiment results for roadmap decisions.

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

### Interactions with other roles
- **Product Managers**: align on scope, priorities, and delivery timelines; jointly manage trade-off decisions.
- **Developers**: remove blockers, track progress, and communicate schedule impacts.
- **DevOps Engineers**: coordinate release windows, environment readiness, and deployment schedules.
- **Business Analysts**: receive scope change flags and dependency risks identified during requirements analysis.
- **Data Analysts**: review project health metrics and incorporate data-driven insights into status reporting.

---

## UX/UI Designer

### Role Summary
UX/UI Designers research user needs, create wireframes and prototypes, and ensure the delivered product is intuitive and accessible. They act as the voice of the user within the delivery team.

### Responsibilities
- Conduct user research, usability tests, and accessibility reviews
- Produce wireframes, mockups, prototypes, and final design assets
- Define interaction patterns, design systems, and visual guidelines
- Collaborate with Product Managers to translate requirements into user flows
- Review implemented features against designs and flag fidelity issues
- Contribute UX acceptance criteria to user stories

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce rework by validating design assumptions early
- Ensure design intent is accurately reflected in the shipped product

### Typical Communication
- Design review sessions with Developers and Product Managers
- Usability test readouts shared with the broader team
- Design assets and annotation notes in shared design tools
- Feedback in PR reviews when UI changes are involved

### Interactions with other roles
- **Product Managers**: align on user problems, prioritize UX work, and review prototypes before development begins.
- **Developers**: hand off design specs, answer implementation questions, and review UI in staging.
- **Business Analysts**: collaborate on user flows derived from business requirements and use cases.
- **Data Analysts**: use usage data and funnel metrics to inform and validate design decisions.
- **Project Managers**: communicate design timeline, flag scope risks related to UX complexity, and participate in planning.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the CI/CD pipelines, infrastructure-as-code, and observability tooling that enable reliable, repeatable delivery. They bridge development and operations to reduce deployment risk.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure using infrastructure-as-code practices
- Define and enforce environment standards (development, staging, production)
- Monitor system health, respond to incidents, and perform root-cause analysis
- Support rollback and mitigation plans for releases
- Drive security scanning integration and supply-chain hygiene in CI
- Collaborate on on-call schedules and incident response runbooks

### Goals
- Maximize deployment frequency while minimizing failure rate and recovery time
- Keep infrastructure reliable, secure, and cost-efficient
- Enable Developers to ship with confidence through fast feedback loops

### Typical Communication
- Deployment status updates to the team during release windows
- Infrastructure change notices ahead of major releases
- Incident triage and post-incident summaries
- Documentation of environment configuration and runbooks

### Interactions with other roles
- **Developers**: support branching strategy, PR automation, and environment provisioning; pair on debugging deployment failures.
- **Project Managers**: coordinate deployment windows, release schedules, and environment freeze periods.
- **Product Managers**: communicate infrastructure constraints that affect release timelines or feature flags.
- **Business Analysts**: implement data pipeline or integration requirements surfaced during requirements analysis.
- **Data Analysts**: provision and maintain data infrastructure and monitoring dashboards.

---

## Business Analyst

### Role Summary
Business Analysts bridge business requirements and technical solutions. They elicit, document, and validate requirements to ensure the team builds the right thing and stakeholders' needs are clearly understood.

### Responsibilities
- Facilitate requirements-gathering sessions with stakeholders and Subject Matter Experts
- Document use cases, user stories, process flows, and acceptance criteria
- Analyze current-state processes and identify improvement opportunities
- Support backlog refinement and scope negotiation with Product and engineering
- Maintain a traceability matrix linking business objectives to deliverables
- Assist QA in deriving test scenarios from business requirements

### Goals
- Ensure requirements are clear, complete, and testable before development begins
- Reduce rework caused by ambiguous or missing requirements
- Keep stakeholder expectations aligned with delivery scope

### Typical Communication
- Requirements workshops and walkthroughs with stakeholders and the delivery team
- Written requirements documents, user stories, and acceptance criteria in the backlog
- Change-request documentation when scope evolves
- Regular check-ins with Product Managers on backlog readiness

### Interactions with other roles
- **Product Managers**: translate business objectives into prioritized backlog items and refine acceptance criteria.
- **Project Managers**: surface scope changes and dependency risks identified during requirements analysis.
- **Developers**: clarify requirements and acceptance criteria during sprint planning and refinement.
- **UX/UI Designers**: collaborate on user flows and ensure business rules are reflected in interface designs.
- **Data Analysts**: identify reporting and data requirements from stakeholder interviews.

---

## Data Analyst

### Role Summary
Data Analysts ensure the team makes evidence-based decisions by defining success metrics, building dashboards, and analyzing product and operational data. They connect raw data to actionable insight.

### Responsibilities
- Define, document, and monitor key performance indicators and success metrics
- Design and maintain dashboards and reports for the team and stakeholders
- Analyze usage patterns, funnel metrics, and experiment results
- Support A/B test design, execution, and interpretation
- Identify instrumentation needs and work with Developers to implement tracking
- Provide data-driven input into roadmap prioritization and retrospectives

### Goals
- Enable data-driven decision-making across the team
- Ensure metrics are instrumented, accurate, and consistently reported
- Surface insights that drive continuous product and process improvement

### Typical Communication
- Metrics reviews in weekly PM/PdM syncs and sprint demos
- Dashboard and report distribution to stakeholders
- Data instrumentation requirements added to backlog items
- Post-experiment readouts shared with Product Managers and leadership

### Interactions with other roles
- **Product Managers**: co-define success metrics for features and initiatives; provide analysis for roadmap decisions.
- **Project Managers**: report on project health metrics and flag data-driven risks or trends.
- **Developers**: specify instrumentation and event-tracking requirements; validate data accuracy post-deployment.
- **Business Analysts**: align on reporting requirements and data definitions surfaced during requirements gathering.
- **UX/UI Designers**: share usage and funnel data to inform user experience improvements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

