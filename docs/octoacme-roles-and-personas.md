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

### Interactions with Other Roles
- Work with **QA/Testing Leads** on test coverage and acceptance criteria validation
- Collaborate with **Technical Leads** on architecture and design decisions
- Partner with **Product Managers** on feature requirements and priorities
- Support **Project Managers** with effort estimates and risk identification

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

### Interactions with Other Roles
- Align with **Stakeholders/Sponsors** on business objectives and trade-offs
- Define acceptance criteria with **QA/Testing Leads**
- Work with **Developers** and **Technical Leads** on feasibility and design
- Coordinate with **Project Managers** on timeline and resource planning

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

### Interactions with Other Roles
- Escalate blockers identified by **Scrum Masters** or **Developers**
- Track quality milestones with **QA/Testing Leads**
- Coordinate release planning with **Release Managers**
- Report status and risks to **Stakeholders/Sponsors**
- Partner with **Product Managers** on timeline and scope management

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy, test planning, and acceptance validation for project deliverables. They work closely with Product Managers and Developers to define acceptance criteria and ensure products meet quality standards before release.

### Responsibilities
- Define quality gates and acceptance criteria for features
- Create and maintain test plans and test cases
- Coordinate manual and automated testing efforts
- Identify and triage quality issues and regressions
- Collaborate with developers on testability and coverage
- Sign off on feature readiness for release
- Report quality metrics and trends

### Goals
- Ensure product quality meets customer expectations
- Reduce production defects and post-release issues
- Enable fast, confident releases through comprehensive testing
- Maintain test coverage and automation standards

### Typical Communication
- Sprint planning and acceptance criteria refinement
- Test status reports and quality metrics reviews
- Escalation of blockers via daily standups and weekly syncs
- Quality gate sign-offs before release

### Interactions with Other Roles
- Partner with **Developers** on test automation and coverage strategies
- Collaborate with **Product Managers** to clarify acceptance criteria
- Report quality readiness to **Project Managers** and **Release Managers**
- Support **Technical Leads** in defining testability requirements
- Provide feedback to **Stakeholders** on release quality confidence

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove impediments, and coach teams on iterative delivery practices. They enable self-organization and continuous improvement within delivery teams.

### Responsibilities
- Facilitate daily standups, planning, and retrospective meetings
- Identify and help remove blockers and impediments
- Coach team on Agile practices and iterative delivery
- Track team velocity and iteration progress
- Promote psychological safety and open communication
- Escalate team-level risks to Project Manager
- Monitor and improve team processes

### Goals
- Enable the team to deliver value consistently
- Reduce cycle time and improve predictability
- Foster a culture of continuous improvement
- Remove organizational barriers to team success

### Typical Communication
- Daily standups with the delivery team
- Sprint planning and retrospective facilitation
- Escalation of blockers to Project Manager
- Coaching conversations with individual team members
- Metrics and velocity trends to Project Manager

### Interactions with Other Roles
- Support **Developers** in removing technical blockers
- Ensure **QA/Testing Leads** have clear priorities and bandwidth
- Coordinate with **Project Manager** on risk escalation and timeline impacts
- Coach **Technical Leads** on team process maturity
- Report team health and risks to **Product Manager**

---

## Technical Lead / Architect

### Role Summary
Technical Leads define technical direction, review design decisions, and manage technical dependencies. They ensure solutions are scalable, maintainable, and aligned with long-term technical strategy.

### Responsibilities
- Define system architecture and technical direction
- Review design proposals and code for architectural alignment
- Identify and manage technical dependencies across teams
- Mentor developers on technical best practices
- Assess technical risks and propose mitigations
- Support effort estimation and feasibility analysis
- Drive technical excellence and quality standards

### Goals
- Ensure scalable, maintainable, and secure solutions
- Reduce technical debt and complexity
- Accelerate development through clear technical guidance
- Enable knowledge sharing and skill development

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring
- Technical risk assessments in planning and execution
- Dependency management with other technical leads
- Technology decisions and trade-off analysis

### Interactions with Other Roles
- Guide **Developers** on architecture and design decisions
- Collaborate with **QA/Testing Leads** on testability and quality standards
- Support **Product Managers** with feasibility assessment and trade-off analysis
- Work with **Project Managers** on technical timeline and dependency impacts
- Partner with **Release Managers** on technical deployment considerations

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Project Sponsors provide business context, validate strategic alignment, and make or approve key trade-off decisions. They ensure projects deliver business value and stay aligned with organizational priorities.

### Responsibilities
- Define business objectives and success metrics
- Approve project scope and priority trade-offs
- Provide feedback on deliverables and direction
- Allocate resources and budget
- Escalate or resolve organizational blockers
- Review and approve release readiness
- Communicate project value to broader organization

### Goals
- Maximize business value delivery
- Ensure alignment with organizational strategy
- Reduce project risk through clear decision-making
- Enable successful project outcomes

### Typical Communication
- Monthly stakeholder updates and demos
- Weekly sync with Product Lead and Project Manager
- Ad-hoc approvals and decision gates
- Escalation of organizational blockers
- Release announcements and impact communication

### Interactions with Other Roles
- Align with **Product Managers** on business objectives and prioritization
- Review status and risks with **Project Managers** weekly
- Provide feedback on deliverables from **QA/Testing Leads**
- Make trade-off decisions involving **Technical Leads**
- Approve release readiness with **Release Managers**

---

## Release Manager

### Role Summary
Release Managers coordinate release planning, deployment execution, rollback procedures, and production verification. They minimize release risk and ensure consistent, predictable delivery to production environments.

### Responsibilities
- Create and maintain release plans and schedules
- Coordinate pre-release validation and smoke testing
- Execute or oversee deployment procedures
- Manage rollback and incident response
- Verify post-deployment functionality and health
- Maintain release documentation and checklists
- Communicate release status to stakeholders

### Goals
- Minimize production risk and deployment incidents
- Enable fast, confident releases to production
- Maintain high availability and stability
- Reduce mean time to recovery (MTTR) for incidents

### Typical Communication
- Release planning and coordination meetings
- Deployment window communications and status updates
- Post-deployment verification and health checks
- Incident response and escalation
- Release notes and deployment documentation

### Interactions with Other Roles
- Partner with **QA/Testing Leads** on pre-release validation and smoke tests
- Coordinate with **Developers** on deployment readiness and rollback procedures
- Work with **Project Managers** on release schedule and milestone tracking
- Collaborate with **Technical Leads** on deployment architecture and risk mitigation
- Report release status to **Stakeholders/Sponsors**
- Coordinate with **Scrum Masters** on release readiness from team perspective

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Review the "Interactions with Other Roles" section to understand cross-functional dependencies and communication patterns.
