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

## QA / Quality Assurance Lead

### Role summary
QA Leads ensure that features meet acceptance criteria and quality standards before release. They coordinate test planning, validation, and quality gates across development and release activities.

### Responsibilities
- Define and validate acceptance criteria and test plans
- Execute and/or coordinate manual and exploratory testing
- Oversee test automation coverage and strategy
- Triage, track, and verify defect fixes
- Participate in release readiness checks and sign-offs
- Maintain QA artifacts (test plans, test matrices, runbooks)

### Typical communication & artifacts
- Test plans, test reports, and QA sign-off documents
- QA status in daily standups and release syncs
- Defect dashboards and verification notes

### Interaction with other roles
- With Developers: review PRs for testability and test coverage; collaborate on automation and fix verification
- With Product Managers: confirm acceptance criteria and validate feature behavior against user needs
- With Project Managers: surface release blockers and timing risks; contribute QA status for planning
- With DevOps: validate staging smoke tests and deployment verification

### Success metrics
- Defect escape rate (production incidents)
- Test coverage for critical paths
- Time-to-verify fixes for critical defects

---

## Technical Lead / Architect

### Role summary
Technical Leads define and steward the technical strategy, architecture, and major design decisions to ensure the system meets functional and non-functional requirements.

### Responsibilities
- Define architecture and system integration patterns
- Produce and maintain design docs and ADRs (Architecture Decision Records)
- Evaluate trade-offs, propose technical designs and standards
- Identify and mitigate technical risk and technical debt
- Lead design reviews and mentor engineering staff on architecture and best practices

### Typical communication & artifacts
- Architecture diagrams, design docs, ADRs
- Design review notes and technical risk logs

### Interaction with other roles
- With Product Managers: translate product requirements into technical solutions and constraints
- With Developers: guide and approve significant design and implementation decisions
- With QA & Security: surface integration, performance, and security needs early in design
- With Project Managers: advise on technical risks and delivery implications

### Success metrics
- System reliability and scalability metrics
- Reduced rework from architectural churn
- Timely resolution of architecture-related incidents

---

## Design / UX Lead

### Role summary
Design/UX Leads ensure the product delivers a usable, accessible, and consistent experience aligned with the design system and user needs.

### Responsibilities
- Define and evangelize UX patterns and design system usage
- Conduct user research, usability testing, and design validation
- Produce UI specifications, prototypes, and accessibility checklists
- Collaborate in sprint planning to ensure design readiness

### Typical communication & artifacts
- Wireframes, interactive prototypes, design system components, usability test reports
- Design handoff notes and acceptance criteria for visuals/interactions

### Interaction with other roles
- With Product Managers: define user outcomes and prioritize UX work
- With Developers: provide specs, review implementations, and validate accessibility
- With QA: define UX acceptance criteria and usability checks

### Success metrics
- Usability test success rates
- Accessibility compliance
- Time-to-implement from design handoff to validated feature

---

## Stakeholder / Sponsor

### Role summary
Stakeholders or Sponsors provide strategic guidance, prioritization, and resources. They own business outcomes and make high-level decisions.

### Responsibilities
- Set and communicate strategic priorities and constraints
- Allocate funding and approve scope or timeline changes
- Provide timely decisions for escalations
- Validate that delivered outcomes meet business goals

### Typical communication & artifacts
- Roadmap endorsements, executive summaries, milestone approvals
- Periodic demos, outcome reports, stakeholder alignment meetings

### Interaction with other roles
- With Product Managers: align on strategy, scope, and investment decisions
- With Project Managers: agree on timelines, budget, and escalate cross-team dependencies
- With the team: receive demos and outcome metrics to confirm business alignment

### Success metrics
- Achievement of business KPIs tied to releases
- Stakeholder satisfaction and confidence in delivery cadence

---

## Scrum Master / Agile Coach

### Role summary
Scrum Masters or Agile Coaches facilitate the team’s agile process, remove impediments, and help the team continuously improve.

### Responsibilities
- Facilitate ceremonies (standups, retrospectives, sprint planning)
- Remove blockers and escalate impediments
- Coach the team on agile practices and help optimize flow
- Track team health and delivery metrics
- Capture and follow-up on retrospective action items

### Typical communication & artifacts
- Sprint plans, retrospective action items, impediment logs, team health checks

### Interaction with other roles
- With Project Managers: coordinate cross-team dependencies and scheduling
- With Product Managers: ensure backlog readiness and healthy refinement practices
- With Developers and QA: support process improvements and remove impediments affecting delivery

### Success metrics
- Team velocity stability and predictability
- Reduced cycle time and mean lead time
- Closure rate of retrospective action items

---

## Security / Compliance Officer

### Role summary
Security and Compliance Officers ensure the project meets security standards, compliance requirements, and manages risk during design, build, and release.

### Responsibilities
- Define security and compliance requirements for features and releases
- Coordinate security reviews, threat modeling, and penetration testing
- Monitor and enforce security scanning and remediation SLAs
- Maintain compliance artifacts and audit readiness

### Typical communication & artifacts
- Security review reports, compliance checklists, vulnerability trackers, remediation plans

### Interaction with other roles
- With Developers: prescribe secure development practices and review fixes
- With DevOps: ensure secure pipelines, secrets management, and deployment controls
- With Product/PM: advise on risk-based prioritization and trade-offs

### Success metrics
- Open vulnerability counts and mean time to remediate
- Compliance audit pass rate
- Security incident trends and reductions

---

## DevOps / Infrastructure Engineer

### Role summary
DevOps and Infrastructure Engineers own CI/CD pipelines, environment provisioning, and operational reliability for applications and environments.

### Responsibilities
- Design and maintain CI/CD pipelines, environment provisioning, and runbooks
- Manage infrastructure as code, monitoring, and alerting
- Support deployments, rollbacks, and incident response
- Optimize release automation, reliability, and observability practices

### Typical communication & artifacts
- Pipeline definitions, deployment runbooks, SLOs/SLA documentation, incident post-mortems

### Interaction with other roles
- With Developers: support build packaging, staging validations, and rollout strategies
- With QA: coordinate staging environments and automated smoke tests
- With Security: implement guardrails and compliance controls in pipelines
- With Project Managers: surface deployment windows and operational constraints

### Success metrics
- Deployment frequency and mean time to recover (MTTR)
- Pipeline success rates and build times
- Infrastructure reliability and cost efficiency

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
