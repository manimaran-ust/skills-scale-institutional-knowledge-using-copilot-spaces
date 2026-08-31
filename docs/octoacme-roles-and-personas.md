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

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and coach the team on agile practices and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, retrospectives, and reviews
- Identify and help resolve blockers and dependencies
- Coach team on agile principles and practices
- Track sprint metrics and burndown
- Protect team from scope creep and external interruptions

### Goals
- Enable high-performing, self-organizing teams
- Improve team velocity and predictability
- Foster a culture of continuous improvement

### Interactions with Other Roles
- Works closely with Project Manager to manage backlog priorities and address blocking issues
- Supports Developers through coaching and ceremony facilitation
- Partners with Product Manager to maintain backlog clarity and acceptance criteria
- Escalates organizational blockers that require PM or leadership intervention

### Typical Communication
- Daily standups and sprint retrospectives
- Weekly metrics reviews and velocity tracking
- Ad-hoc coaching conversations with team members

---

## QA / Test Lead

### Role Summary
QA/Test Leads own the quality strategy, define test plans, validate acceptance criteria, and ensure features meet quality standards before release.

### Responsibilities
- Define test strategy and test coverage requirements
- Create and maintain test plans for features
- Validate acceptance criteria with Product Manager
- Coordinate manual and automated testing efforts
- Report quality metrics, defects, and risk assessments
- Participate in release readiness reviews
- Guide Developers on testability and test-driven development

### Goals
- Ensure products meet quality standards and user expectations
- Minimize defects reaching production
- Reduce testing cycle time through effective automation

### Interactions with Other Roles
- Collaborates with Developers on testability, test automation, and acceptance criteria clarification
- Partners with Product Manager to validate feature requirements and acceptance criteria
- Works with DevOps/Release Manager on pre-deployment smoke tests and rollback readiness
- Reports quality risks to Project Manager and escalates blockers

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Test plan documentation and defect reports
- Quality metrics dashboards and release readiness assessments

---

## Technical Lead / Architect

### Role Summary
Technical Leads define the technical direction, make architectural decisions, and mentor developers to ensure scalability, maintainability, and adherence to technical standards.

### Responsibilities
- Define technical approach and architecture for features
- Conduct technical design reviews and code reviews
- Mentor Developers on best practices, patterns, and standards
- Identify technical risks and propose mitigations
- Ensure code quality, system observability, and maintainability
- Make trade-off decisions on technical complexity vs. delivery speed
- Guide technical strategy alignment with business goals

### Goals
- Deliver scalable, maintainable, and secure technical solutions
- Reduce technical debt and maintenance burden
- Enable faster feature delivery through solid architecture

### Interactions with Other Roles
- Partners with Product Manager to understand requirements and discuss technical trade-offs
- Mentors Developers and leads technical design and code reviews
- Works with DevOps/Release Manager on infrastructure requirements and deployment strategy
- Advises Project Manager on technical risks, dependencies, and estimation challenges
- Collaborates with QA/Test Lead on testability and quality requirements

### Typical Communication
- Technical design docs and architecture decision records (ADRs)
- Code review comments and design review meetings
- Risk assessments and technical dependency tracking

---

## UX / Design Lead

### Role Summary
UX/Design Leads define user experience requirements, design interfaces, and validate usability to ensure features meet user needs and organizational standards.

### Responsibilities
- Conduct user research and define user personas and workflows
- Design interfaces, interactions, and information architecture
- Create design specifications and design system documentation
- Validate designs through user testing and feedback
- Collaborate on accessibility and usability standards
- Guide Developers on design implementation and consistency

### Goals
- Deliver intuitive, accessible user experiences
- Minimize user friction and support burden
- Maintain design consistency across the product

### Interactions with Other Roles
- Works closely with Product Manager to understand user needs and validate feature concepts
- Collaborates with Developers on design implementation and technical feasibility
- Partners with QA/Test Lead on usability validation and acceptance criteria
- Advises Project Manager on design-related risks and schedule impacts

### Typical Communication
- Design specs, wireframes, and prototypes
- User research findings and testing reports
- Design review meetings and feedback sessions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve scope and budget, and remove organizational blockers to enable project success.

### Responsibilities
- Define business requirements and success criteria
- Approve project scope, budget, and timelines
- Remove organizational blockers and provide executive support
- Review and approve major project milestones and deliverables
- Communicate project status and outcomes to leadership
- Provide domain expertise and business guidance

### Goals
- Ensure project aligns with business strategy and priorities
- Maximize return on investment and business value
- Enable smooth delivery through organizational support

### Interactions with Other Roles
- Partners with Product Manager to validate business requirements and success metrics
- Works with Project Manager on approval, escalation, and resource decisions
- Receives regular status updates and risk reports from the delivery team
- Provides guidance and decisions on trade-offs and scope changes

### Typical Communication
- Monthly or milestone-based status updates and reviews
- Approval meetings for major decisions and budget allocation
- Escalation meetings for critical blockers or risks

---

## Security Officer

### Role Summary
Security Officers review security risks, ensure compliance with security standards, and conduct security reviews to protect systems and data.

### Responsibilities
- Define security requirements and standards for projects
- Conduct security reviews of design and implementation
- Identify and assess security risks and vulnerabilities
- Ensure compliance with organizational and regulatory policies
- Guide teams on secure coding practices and data protection
- Participate in incident response and post-incident reviews

### Goals
- Prevent security breaches and data loss
- Maintain compliance and organizational trust
- Build security awareness across the team

### Interactions with Other Roles
- Collaborates with Technical Leads on security architecture and design decisions
- Reviews code and infrastructure for security vulnerabilities
- Advises Project Manager on security-related risks and dependencies
- Works with DevOps/Release Manager on secure deployment practices

### Typical Communication
- Security review reports and threat assessments
- Security training and best practices documentation
- Compliance checklists and audit participation

---

## DevOps / Release Manager

### Role Summary
DevOps/Release Managers manage infrastructure, deployment pipelines, and release orchestration to ensure reliable, repeatable deployments to production.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Manage release planning and coordination
- Conduct pre-deployment verifications and smoke tests
- Monitor deployments and respond to production issues
- Manage rollback procedures and incident response
- Document release notes and deployment procedures
- Optimize infrastructure for performance, reliability, and cost

### Goals
- Enable safe, reliable, and frequent deployments
- Minimize downtime and deployment risks
- Reduce time-to-recovery for production issues

### Interactions with Other Roles
- Works with Technical Leads on infrastructure requirements and deployment architecture
- Collaborates with QA/Test Lead on smoke tests and release readiness
- Coordinates with Developers on deployment and troubleshooting
- Advises Project Manager on deployment risks and scheduling constraints
- Partners with Security Officer on secure deployment practices

### Typical Communication
- Release planning meetings and deployment schedules
- Deployment runbooks and incident procedures
- Infrastructure and monitoring dashboards

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Interactions with Other Roles" sections to understand cross-functional dependencies and communication patterns.
