# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or adapted to fit a project's size and needs, but ownership for each responsibility should remain clear.

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

## UX Designers / User Researchers

### Role Summary
UX Designers and User Researchers investigate user needs and shape accessible, usable experiences that address the product problem.

### Responsibilities
- Plan and conduct user research, and synthesize findings
- Create user flows, prototypes, and interaction designs
- Identify accessibility and usability needs and incorporate them into designs
- Validate proposed designs with users and share evidence with the team

### Collaboration with Existing Roles
- Partner with the Product Manager to validate user problems and inform requirements and acceptance criteria
- Coordinate research timing, participant access, and design dependencies with the Project Manager
- Work with Developers and the Engineering Lead to assess feasibility and refine designs
- Partner with QA/Testing to include usability and accessibility in validation
- Share research findings and design decisions with Stakeholders

### Goals
- Make product decisions grounded in user evidence
- Deliver experiences that are usable, accessible, and consistent

### Typical Communication
- Research plans, findings, and design reviews
- Prototypes and design specifications
- Usability feedback and accessibility considerations in planning and review

---

## Engineering Leads / Technical Leads

### Role Summary
Engineering Leads guide technical design and implementation quality, helping the team deliver maintainable solutions within agreed product scope.

### Responsibilities
- Facilitate technical design and document significant decisions
- Support engineering estimates and identify technical dependencies and risks
- Promote engineering standards, reliability, and testability
- Coordinate technical work across Developers and raise unresolved technical risks

### Collaboration with Existing Roles
- Coordinate dependencies, estimates, and technical risks with the Project Manager
- Work with the Product Manager to explain technical trade-offs and options without taking over product prioritization
- Guide and unblock Developers while encouraging shared ownership of implementation
- Partner with QA/Testing on testability and technical validation needs
- Explain material technical implications and decisions to Stakeholders

### Goals
- Enable a coherent, reliable, and maintainable technical solution
- Surface technical risks and trade-offs early enough to inform plans

### Typical Communication
- Design proposals and decision records
- Engineering estimates, dependency updates, and risk reviews
- Technical discussions with Developers, QA/Testing, and product and project leads

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads help teams define how success will be measured and ensure outcome data is fit for decision-making.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Advise on event definitions, data quality, and analysis methods
- Validate that collected data supports reliable reporting
- Communicate measurement limitations and findings

### Collaboration with Existing Roles
- Work with the Product Manager to make success metrics measurable and interpretable
- Coordinate measurement tasks and reporting milestones with the Project Manager
- Partner with Developers to implement instrumentation and with QA/Testing to verify event behavior and data quality
- Share evidence, caveats, and outcome trends with Stakeholders
- Coordinate with the Security / Privacy Lead when measurement involves personal or sensitive data

### Goals
- Provide trustworthy evidence of product outcomes
- Help the team make informed decisions and adjust based on results

### Typical Communication
- Metric definitions and instrumentation plans
- Data quality checks and outcome reports
- Measurement risks or caveats in planning and delivery updates

---

## Security / Privacy Leads

### Role Summary
Security / Privacy Leads advise the team on security and privacy requirements, risks, and appropriate validation for the project's context.

### Responsibilities
- Identify applicable security and privacy requirements and review relevant designs
- Assess risks and recommend mitigations and verification activities
- Help coordinate security and privacy reviews and escalate unresolved material risks through established paths
- Advise on incident and data-handling considerations when relevant

### Collaboration with Existing Roles
- Work with the Project Manager to record risks, owners, mitigations, and escalation needs
- Advise the Product Manager on security and privacy implications of scope and requirements
- Partner with the Engineering Lead and Developers to incorporate controls into design and implementation
- Coordinate security and privacy verification with QA/Testing
- Communicate material risks, required decisions, and mitigations to Stakeholders

### Goals
- Address security and privacy risks early and proportionately
- Make required controls and verification responsibilities clear

### Typical Communication
- Risk register updates and design review findings
- Security and privacy requirements and validation plans
- Escalations through the security incident runbook and established project paths

---

## Release / Operations Leads

### Role Summary
Release / Operations Leads coordinate operational readiness, deployment, monitoring, and handoff so changes can be released and supported reliably.

### Responsibilities
- Coordinate release readiness, deployment tasks, and operational handoffs
- Confirm monitoring, rollback or mitigation plans, and post-deployment checks are prepared
- Identify operational dependencies and readiness risks
- Coordinate release follow-up and incident escalation with the appropriate teams

### Collaboration with Existing Roles
- Align release timing, dependencies, and communications with the Project Manager
- Confirm release scope and acceptance expectations with the Product Manager
- Coordinate deployment preparation and operational requirements with the Engineering Lead and Developers
- Work with QA/Testing on smoke tests and release verification
- Communicate readiness, operational risks, and post-release status to Stakeholders and Customer Support / Service Representatives

### Goals
- Make releases predictable, observable, and supportable
- Ensure ownership of deployment verification and operational follow-up

### Typical Communication
- Release readiness checklists and deployment plans
- Monitoring, rollback, and handoff details
- Post-deployment status and incident updates

---

## Customer Support / Service Representatives

### Role Summary
Customer Support / Service Representatives bring customer-impact and supportability needs into delivery and relay feedback after release.

### Responsibilities
- Share recurring customer questions, pain points, and support trends
- Identify support, documentation, and training needs for upcoming changes
- Help prepare customer-facing support materials and escalation guidance
- Collect and route post-release feedback and issue reports to the responsible teams

### Collaboration with Existing Roles
- Work with the Product Manager to bring customer needs and feedback into prioritization and acceptance criteria
- Coordinate customer communications and support readiness with the Project Manager
- Provide Developers and QA/Testing with clear customer-reported symptoms and reproduction details
- Coordinate knowledge transfer and operational handoff with the Release / Operations Lead
- Share customer impact, support trends, and unresolved concerns with Stakeholders

### Goals
- Help customers adopt changes and get timely, consistent support
- Ensure customer feedback informs future product decisions

### Typical Communication
- Support trend summaries and customer feedback
- Knowledge-base updates, release guidance, and escalation notes
- Post-release feedback shared with product, project, development, and testing teams

---

## Role Boundaries

The Product Manager remains accountable for product outcomes and prioritization, and the Project Manager remains accountable for delivery coordination, schedule, risks, and project communication. The additional roles provide domain expertise and own the responsibilities described above; they raise decisions outside their remit through the established project and escalation paths. Projects may combine roles when appropriate, while keeping responsibility and decision ownership explicit.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
