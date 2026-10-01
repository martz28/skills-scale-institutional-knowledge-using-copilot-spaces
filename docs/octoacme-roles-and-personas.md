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

## Design / UX Leads

### Role Summary
Design / UX Leads shape how users experience the product and ensure the solution is usable, consistent, and aligned to customer needs. They partner closely with Product and Engineering to translate outcomes into clear experience decisions.

### Responsibilities
- Define user flows, interface patterns, and design system standards
- Partner with Product Managers to validate requirements and customer needs
- Work with Developers to ensure designs are feasible and testable
- Review prototypes and usability outcomes before release
- Help prioritize UX trade-offs and accessibility considerations

### Goals
- Improve usability, clarity, and customer satisfaction
- Align product decisions with user needs and business outcomes
- Reduce rework caused by unclear design expectations

### Typical Communication
- Product discovery and prioritization sessions
- Design reviews and prototype feedback loops
- Cross-functional planning and release readiness discussions

### Interaction with Existing Roles
- With Product Managers: translate outcomes and customer insights into UX requirements and design direction
- With Developers: clarify implementation constraints, usability expectations, and edge cases
- With Project Managers: align design milestones, review windows, and dependencies with delivery plans

---

## Technical Leads / Architects

### Role Summary
Technical Leads or Architects guide technical direction, reduce architectural drift, and ensure the solution is maintainable, scalable, and aligned with business goals. They provide technical decision-making support without replacing individual contribution by Developers.

### Responsibilities
- Own technical design direction and standards for major features or integrations
- Identify dependencies, architectural risks, and opportunities for simplification
- Help evaluate trade-offs across scalability, reliability, and delivery speed
- Support technical decision-making during planning and incident response
- Mentor Developers and review high-impact implementation choices

### Goals
- Maintain a coherent technical foundation
- Reduce delivery risk and costly rework
- Improve long-term maintainability and operational stability

### Typical Communication
- Architecture reviews and technical design discussions
- Engineering planning and dependency management
- Incident review and technical risk escalation

### Interaction with Existing Roles
- With Developers: provide guidance, architecture guardrails, and technical review feedback
- With Product Managers: translate product goals into solution feasibility and trade-off conversations
- With Project Managers: identify delivery risks, dependencies, and sequencing issues that affect timelines

---

## Delivery / Engineering Managers

### Role Summary
Delivery / Engineering Managers support team health, staffing, and execution quality. They help teams deliver consistently by managing capacity, blockers, and coordination across engineering work.

### Responsibilities
- Support team planning, workload balancing, and execution focus
- Identify bottlenecks, staffing constraints, and delivery risks
- Partner with Project Managers on plans, milestones, and cross-team dependencies
- Support performance and coaching needs within the engineering team
- Help escalate technical or organizational issues that threaten delivery

### Goals
- Improve team predictability and throughput
- Reduce unnecessary friction in delivery execution
- Keep engineering work aligned with project constraints and business needs

### Typical Communication
- Team check-ins, planning, and delivery health reviews
- Escalation conversations with Project Managers and leadership
- Cross-team dependency and staffing coordination

### Interaction with Existing Roles
- With Developers: support prioritization, coaching, and capacity management
- With Project Managers: align team availability, dependency tracking, and risk response
- With Product Managers: clarify delivery constraints, sequencing, and trade-offs based on engineering capacity

---

## Business Analysts / Product Operations Partners

### Role Summary
Business Analysts or Product Operations Partners help translate stakeholder needs, business context, and process requirements into clear, actionable work. They improve clarity across planning and execution by connecting business intent to implementation detail.

### Responsibilities
- Document requirements, workflows, and business rules
- Convert stakeholder feedback into clear acceptance criteria and process inputs
- Support prioritization and trade-off analysis alongside Product Managers
- Maintain alignment between operational needs, project artifacts, and business expectations
- Help identify gaps, ambiguities, and process inefficiencies

### Goals
- Ensure business intent is clear and testable
- Reduce ambiguity across teams
- Improve consistency of requirements and decision records

### Typical Communication
- Requirements workshops, stakeholder interviews, and backlog refinement
- Product and project status coordination
- Documentation and decision tracking

### Interaction with Existing Roles
- With Product Managers: operationalize strategy and clarify requirements
- With Project Managers: support documentation, reporting, and cross-functional coordination
- With Developers and QA: ensure work is described clearly and testable before implementation

---

## QA / Test Leads

### Role Summary
QA / Test Leads define and coordinate validation strategies to ensure the solution meets acceptance criteria and stakeholder expectations before release. They help quality become part of delivery instead of an afterthought.

### Responsibilities
- Define testing strategies, coverage plans, and quality gates
- Coordinate test execution across unit, integration, and user acceptance scenarios
- Validate that acceptance criteria are measurable and complete
- Partner with Developers on defect triage and release readiness
- Communicate quality risk and go / no-go recommendations to stakeholders

### Goals
- Improve confidence in release quality and reduce regression risk
- Ensure customer outcomes are tested, not just code behavior
- Support predictable, low-risk releases

### Typical Communication
- Sprint acceptance reviews and test planning
- Defect triage and release readiness assessments
- Communication with Product Managers and stakeholders on quality risks

### Interaction with Existing Roles
- With Developers: review implementation quality, defects, and validation coverage
- With Product Managers: confirm that acceptance criteria and business outcomes are being met
- With Project Managers: coordinate release quality checks and issue escalation

---

## Release / Operations / SRE Leads

### Role Summary
Release / Operations / SRE Leads ensure production readiness, observability, and safe delivery of changes. They help teams move from feature readiness to operational stability with clear monitoring and rollback plans.

### Responsibilities
- Plan and coordinate release windows, deployment readiness, and verification steps
- Define monitoring, alerting, and rollback requirements for critical changes
- Support operational readiness and production incident response
- Partner with Developers and QA on smoke tests and post-deploy validation
- Capture service health and reliability risks associated with releases

### Goals
- Reduce deployment risk and customer impact
- Keep systems observable, reliable, and recoverable
- Improve the operational quality of each release

### Typical Communication
- Release readiness reviews and deployment checklists
- Incident communications and operational status updates
- Post-release follow-ups and reliability reviews

### Interaction with Existing Roles
- With Developers: align on deployment risk, observability, and rollback automation
- With Project Managers: coordinate release timing, stakeholder communication, and operational dependencies
- With Product Managers: confirm release readiness, risk, and customer impact communication

---

## Customer / Support Representatives

### Role Summary
Customer / Support Representatives bring direct customer and service experience into project decisions. They help teams understand user pain points, support realities, and post-release feedback to improve outcomes.

### Responsibilities
- Share customer feedback, service issues, and support trends with the team
- Help identify customer-impacting risks, edge cases, and unmet needs
- Contribute to release communication and readiness decisions
- Support retrospective learning based on service and support signals
- Help prioritize improvements that reduce friction for users and support teams

### Goals
- Improve customer trust and experience
- Reduce avoidable support burden and escalation churn
- Ensure delivery decisions consider real-world operational feedback

### Typical Communication
- Customer feedback reviews and support trend summaries
- Release note and stakeholder communication updates
- Incident follow-up and retrospective discussions

### Interaction with Existing Roles
- With Product Managers: inform backlog priorities and customer problem framing
- With Developers: surface edge cases and real-world usage problems
- With Project Managers: provide operational context for release timing, communication, and risk escalation

---

## Security / Privacy Partners

### Role Summary
Security / Privacy Partners help protect customer data, maintain compliance, and reduce security risk throughout delivery. They advise teams on controls, principles, and risk decisions before release.

### Responsibilities
- Review designs, data handling, and architecture for security and privacy risks
- Help identify threats, required controls, and compliance needs
- Support risk assessments and mitigation planning for sensitive features or data
- Partner with engineering and leadership on incident response and escalation
- Guide secure release readiness and post-incident learning

### Goals
- Reduce security and privacy exposure
- Protect customer trust and regulatory compliance
- Integrate security practices without slowing delivery unnecessarily

### Typical Communication
- Security review meetings and design discussions
- Risk assessment and mitigation planning
- Incident response and compliance follow-up

### Interaction with Existing Roles
- With Developers: advise on secure implementation patterns and controls
- With Product Managers: assess risk trade-offs against product goals and customer needs
- With Project Managers: support risk reporting, dependency planning, and escalation paths for security concerns

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These additional roles are particularly useful when projects are large, cross-functional, or have higher risk, compliance, customer impact, or operational complexity.
- Teams may assign one person to multiple roles, or combine roles for smaller projects, but ownership and escalation should remain explicit.

