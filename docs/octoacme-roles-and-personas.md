# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may hold more than one role, especially on smaller teams, but ownership for each responsibility should remain explicit.

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

### Interactions and Accountability
- Work with the Product Manager to clarify requirements and acceptance criteria.
- Coordinate with the Technical Lead on implementation decisions and engineering standards.
- Partner with QA/Testing to make work testable and resolve defects.
- Share progress, estimates, blockers, and technical risks with the Project Manager.

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

### Interactions and Accountability
- Own product priorities, outcomes, and acceptance criteria; consult the Project Manager on delivery constraints and the Technical Lead on feasibility.
- Partner with the UX/UI Designer or Researcher to incorporate user needs and usability evidence.
- Work with the Data/Analytics Lead to define how success will be measured and interpreted.
- Align product decisions and trade-offs with stakeholders.

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

### Interactions and Accountability
- Own delivery coordination, project status, and escalation of schedule, dependency, and resource risks.
- Coordinate with the Product Manager on scope and priorities, and with the Technical Lead and functional leads on plans, estimates, and dependencies.
- Ensure decisions, owners, and actions are recorded and communicated to stakeholders.

---

## QA/Testing

### Role Summary
QA/Testing validates that delivered work meets acceptance criteria and quality expectations, helping the team detect defects and release with confidence.

### Responsibilities
- Collaborate on test strategy and identify coverage needs
- Validate features against acceptance criteria
- Report, track, and help triage defects
- Perform integration, regression, and release testing as appropriate

### Interactions and Accountability
- Work with the Product Manager to understand acceptance criteria and with Developers to plan testability and resolve defects.
- Coordinate with the Security/Privacy Lead on relevant security validation and with the Operations/SRE or Release Owner on release checks.
- Share test status, quality risks, and release concerns with the Project Manager and delivery team.

---

## UX/UI Designer or Researcher

### Role Summary
The UX/UI Designer or Researcher helps the team understand users and create accessible, usable experiences that address their needs.

### Responsibilities
- Plan and conduct user research or usability evaluations
- Develop user journeys, interaction designs, wireframes, and visual specifications as needed
- Identify accessibility and usability considerations
- Share research findings and design rationale with the team

### Interactions and Accountability
- Partner with the Product Manager to translate user needs and research findings into product opportunities and acceptance criteria.
- Collaborate with Developers and the Technical Lead to assess feasibility and resolve design questions during implementation.
- Work with QA/Testing to define usability and accessibility checks.
- Share findings and design decisions with the Project Manager and relevant stakeholders; the Product Manager remains accountable for product priorities.

---

## Technical Lead or Architect

### Role Summary
The Technical Lead or Architect guides technical design and engineering alignment so that the solution is feasible, maintainable, and appropriately integrated.

### Responsibilities
- Guide technical design, architecture, and engineering standards
- Identify technical dependencies, integration points, and risks
- Support estimates and implementation planning
- Facilitate technical decisions and document significant trade-offs
- Promote maintainability, reliability, and appropriate technical quality

### Interactions and Accountability
- Provide technical direction to Developers and support design and code reviews.
- Advise the Product Manager on feasibility and technical trade-offs, and the Project Manager on estimates, dependencies, and technical risks.
- Coordinate with the Security/Privacy Lead on security and privacy requirements and with the Operations/SRE or Release Owner on operational readiness.
- Escalate unresolved technical risks to the appropriate project and engineering decision-makers; product scope and delivery coordination remain with the Product Manager and Project Manager respectively.

---

## Data/Analytics Lead

### Role Summary
The Data/Analytics Lead helps the team define and implement reliable measurement so product and project outcomes can be evaluated using evidence.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Advise on event definitions, data quality, and analysis methods
- Validate that dashboards or reports reflect agreed metrics
- Communicate findings, limitations, and emerging trends

### Interactions and Accountability
- Partner with the Product Manager to define outcome measures and interpret results against product goals.
- Coordinate with Developers to implement instrumentation and with QA/Testing to verify measurement behavior where appropriate.
- Share relevant insights with the Project Manager and stakeholders to inform progress reporting and decisions; the Product Manager remains accountable for product priorities and success measures.

---

## Security/Privacy Lead

### Role Summary
The Security/Privacy Lead advises the team on security, privacy, and compliance risks and helps ensure appropriate controls are considered throughout delivery.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Advise on threat and privacy risks and recommend mitigations
- Review relevant designs, changes, or release readiness evidence
- Escalate material concerns through established security and incident channels

### Interactions and Accountability
- Work with the Technical Lead and Developers to incorporate security and privacy requirements into design and implementation.
- Coordinate with QA/Testing on relevant security validation and with the Operations/SRE or Release Owner on production controls and incident readiness.
- Keep the Project Manager informed of material risks and mitigations, and follow the organization's security escalation process for security incidents.
- Provide specialist guidance; accountable engineering and business owners retain responsibility for implementing and accepting risks through the proper governance process.

---

## Operations/SRE or Release Owner

### Role Summary
The Operations/SRE or Release Owner coordinates operational readiness and supports safe deployment, monitoring, and recovery of delivered changes.

### Responsibilities
- Define or coordinate operational readiness and deployment checks
- Ensure monitoring, alerting, and support arrangements are prepared
- Coordinate deployment timing and rollback or mitigation plans
- Monitor service health after release and communicate operational issues

### Interactions and Accountability
- Partner with Developers and the Technical Lead on reliability, deployment, and observability requirements.
- Coordinate with QA/Testing on release checks and with the Security/Privacy Lead on applicable production controls.
- Align release plans, dependencies, and communications with the Project Manager; coordinate release timing and scope with the Product Manager.
- Escalate incidents through the established on-call and incident response process and provide status to stakeholders with the Project Manager.

---

## Stakeholders

### Role Summary
Stakeholders provide domain knowledge, feedback, resources, and decisions needed to align project work with organizational and customer needs.

### Responsibilities
- Provide timely input on needs, constraints, and expected outcomes
- Review relevant plans, milestones, and deliverables
- Make or obtain decisions within their authority
- Raise concerns and communicate changes that may affect the project

### Interactions and Accountability
- Work with the Product Manager on product direction and with the Project Manager on delivery updates, approvals, and escalations.
- Consult relevant specialists, such as UX/UI, Data/Analytics, Technical, Security/Privacy, and Operations leads, for domain-specific decisions.
- Provide decisions or feedback by agreed dates so that dependencies and impacts can be managed transparently.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- On smaller teams, one person may cover multiple personas; make the owner for each decision and responsibility clear.
