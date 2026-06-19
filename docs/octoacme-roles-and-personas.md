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

## QA / Testing Engineer

### Role Summary
QA/Testing Engineers validate that delivered work meets acceptance criteria and quality standards before release. They own test planning, execution, and defect reporting across the delivery lifecycle.

### Responsibilities
- Define and maintain test plans and test cases aligned to acceptance criteria
- Execute manual and automated tests across functional and non-functional requirements
- Report, track, and verify resolution of defects
- Participate in release readiness decisions
- Contribute to Definition of Done criteria

### Goals
- Prevent regressions and ensure release quality
- Reduce defect escape rate to production
- Improve test automation coverage over time

### Typical Communication
- Sprint reviews and bug triage meetings
- Defect reports and test summary docs
- Coordination with Developers on fix verification and release criteria

### Interaction with Existing Roles
- Works with **Developers** to clarify acceptance criteria and verify bug fixes
- Aligns with **Product Managers** on usability and functional requirements
- Informs **Project Managers** on quality risk and release readiness
- Partners with **DevOps/Platform Engineers** on test environment stability

---

## Engineering Manager

### Role Summary
Engineering Managers own engineering capacity, technical execution health, and people leadership. They bridge delivery accountability with team sustainability.

### Responsibilities
- Balance delivery commitments with sustainable team capacity
- Remove execution blockers escalated by Project Managers or Developers
- Ensure technical quality standards and development practices are followed
- Support career development and performance of engineering team members

### Goals
- Sustain a healthy, high-performing engineering team
- Protect the team from scope creep and unplanned interruptions
- Maintain alignment between engineering execution and business commitments

### Typical Communication
- Weekly syncs with Project Managers and Tech Leads
- 1:1s and team retrospectives
- Escalation paths for resourcing and cross-team dependencies

### Interaction with Existing Roles
- Partners with **Project Managers** on schedule risk and staffing trade-offs
- Partners with **Product Managers** on scope feasibility and sequencing
- Supports **Developers** with prioritization guidance and escalation resolution
- Coordinates with **Tech Lead/Solution Architect** on technical health and process improvements

---

## Tech Lead / Solution Architect

### Role Summary
The Tech Lead or Solution Architect provides technical direction, architecture guardrails, and design decision ownership. They ensure the solution is sound, scalable, and consistent with long-term engineering goals.

### Responsibilities
- Define solution approach and document key technical decisions
- Validate non-functional requirements (scalability, reliability, security)
- Guide decomposition of work into implementable increments
- Conduct or lead technical design reviews

### Goals
- Deliver technically sound solutions that minimize future rework
- Establish shared understanding of architecture across the team
- Reduce technical risk and debt introduced during delivery

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code and design review sessions
- Sync with Product Managers to align technical scope with product outcomes

### Interaction with Existing Roles
- Collaborates with **Developers** on design patterns and code quality expectations
- Aligns with **Product Managers** to convert product outcomes into technical scope
- Advises **Project Managers** on technical dependencies and schedule risk
- Works with **Engineering Manager** on team capacity and technical practice improvements
- Consults with **Security & Compliance Lead** on secure-by-design requirements

---

## UX / Product Designer

### Role Summary
UX/Product Designers ensure solutions are user-centered, usable, and consistent with the product experience. They translate user needs and product requirements into interaction designs and specifications.

### Responsibilities
- Produce user flows, wireframes, and interaction specifications
- Define usability acceptance criteria in collaboration with Product Managers
- Validate designs through user feedback and usability testing inputs
- Maintain design system consistency across features

### Goals
- Deliver intuitive experiences that reduce user friction
- Align design decisions with product goals and technical feasibility
- Ensure design handoffs are clear and implementation-ready

### Typical Communication
- Design reviews and stakeholder walkthroughs
- Figma/prototype links and annotated specs in feature tickets
- Sync with Developers during build to address implementation questions

### Interaction with Existing Roles
- Works with **Product Managers** on problem framing, user needs, and solution usability
- Works with **Developers** to ensure feasible, consistent implementation
- Informs **QA/Testing Engineers** with UX-focused acceptance criteria
- Aligns with **Tech Lead** on design system and component constraints

---

## DevOps / Platform Engineer

### Role Summary
DevOps/Platform Engineers own delivery pipelines, environment reliability, and operational infrastructure. They enable safe, automated, and repeatable deployments.

### Responsibilities
- Maintain CI/CD reliability and release automation
- Manage environment provisioning, rollback paths, and observability tooling
- Support deployment planning and release safety reviews
- Partner on incident readiness and post-incident remediation

### Goals
- Enable fast, reliable, and low-risk deployments
- Reduce deployment toil and manual intervention
- Maintain high availability and observability in production

### Typical Communication
- Release readiness and deployment runbooks
- Incident response coordination and post-mortem participation
- Platform health and pipeline status reports

### Interaction with Existing Roles
- Coordinates with **Project Managers** on release timelines and deployment risk windows
- Enables **Developers** with tooling, deployment workflows, and environment access
- Partners with **QA/Testing Engineers** for stable, consistent test environments
- Supports **Security & Compliance Lead** on deployment controls and audit requirements

---

## Security & Compliance Lead

### Role Summary
The Security & Compliance Lead integrates security and compliance requirements into delivery. They ensure risks are identified early and that controls are in place before release.

### Responsibilities
- Define security controls and review high-risk changes
- Ensure threat modeling and risk considerations are addressed during planning
- Advise on compliance constraints that affect scope or timelines
- Guide incident communication for security-impacting events

### Goals
- Reduce security exposure through proactive risk identification
- Embed security practices into the delivery process rather than treating them as a gate
- Ensure regulatory and policy compliance across shipped features

### Typical Communication
- Security review outputs and risk register entries
- Compliance checklists in release gates
- Incident communication drafts for security events

### Interaction with Existing Roles
- Works with **Tech Lead/Solution Architect** and **Developers** on secure design and implementation
- Works with **Project Managers** on risk register updates and escalation paths
- Aligns with **Product Managers** where compliance requirements impact scope or timeline
- Partners with **DevOps/Platform Engineers** on deployment controls and audit trails

---

## Customer Success / Support Representative

### Role Summary
Customer Success or Support Representatives bring customer-impact signals into planning and release decisions. They represent end users and support readiness across the delivery lifecycle.

### Responsibilities
- Surface customer pain points, support trends, and rollout risks to the team
- Validate release readiness from a customer support perspective
- Assist in drafting release communications and managing known-issue documentation
- Provide post-release feedback loops based on user reports

### Goals
- Protect customer experience during and after releases
- Reduce reactive support burden through proactive readiness
- Ensure customers receive clear, timely communication about changes

### Typical Communication
- Release notes and customer-facing communication drafts
- Support readiness reviews ahead of releases
- Customer feedback summaries shared with Product Managers

### Interaction with Existing Roles
- Feeds customer insights and support trends to **Product Managers** for prioritization
- Partners with **Project Managers** on stakeholder communication cadence
- Coordinates with **QA/Testing Engineers** on high-impact user scenarios and edge cases
- Informs **DevOps/Platform Engineers** of customer-visible operational issues

---

## Data Analyst / Analytics Owner

### Role Summary
Data Analysts or Analytics Owners define and validate outcome measurement. They ensure delivery impact is visible and decisions are data-informed.

### Responsibilities
- Translate success metrics into measurable instrumentation requirements
- Build and maintain dashboards for adoption, quality, and delivery outcomes
- Support post-release analysis and retrospective evidence gathering
- Identify gaps in data coverage and work with engineers to close them

### Goals
- Make project outcomes measurable and visible to stakeholders
- Enable data-driven iteration after releases
- Improve confidence in delivery decisions through evidence

### Typical Communication
- Dashboard links and metric summaries in stakeholder updates
- Retrospective data summaries and trend analysis
- Instrumentation requirements in feature tickets

### Interaction with Existing Roles
- Works with **Product Managers** on KPI definition and success measurement
- Works with **Developers** and **Tech Lead** on instrumentation and event tracking requirements
- Supports **Project Managers** with objective status reporting and milestone evidence
- Partners with **Customer Success** on usage and satisfaction signal alignment

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [RACI Matrix](./octoacme-raci-matrix.md) to understand which roles are Responsible, Accountable, Consulted, or Informed for each lifecycle phase.
- Use the [Handoff Checklist](./octoacme-handoff-checklist.md) and [Communication & Escalation Checklist](./octoacme-communication-escalation-checklist.md) for practical process execution.

