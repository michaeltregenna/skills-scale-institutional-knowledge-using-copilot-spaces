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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy and execution. They define testing approaches, validate acceptance criteria, and ensure product quality standards are met before release.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Design and execute manual and automated test suites
- Identify and document defects and quality issues
- Validate that acceptance criteria are met before marking work as done
- Perform smoke tests before and after production deployment
- Collaborate with developers on testability and test coverage improvements

### Goals
- Ensure high product quality and customer satisfaction
- Reduce post-release defects and rework
- Build confidence in release readiness through comprehensive testing

### Typical Communication
- Sprint planning and backlog refinement
- Daily standup updates on test progress and blockers
- Defect triage and prioritization with development team
- Pre-release testing reports and smoke test results

### Interactions with Other Roles
- **Developers:** Collaborate on test coverage improvements and testability during design and implementation
- **Project Managers:** Provide testing progress updates and identify blockers affecting delivery timelines
- **Product Managers:** Validate acceptance criteria and provide feedback on feature usability
- **Release Manager:** Execute smoke tests and sign off on release readiness

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads own technical strategy and execution. They mentor developers, make architectural decisions, manage technical risks, and serve as the primary technical liaison to product and project leadership.

### Responsibilities
- Make technical architecture and design decisions
- Mentor and support developers on technical growth
- Identify and mitigate technical risks and dependencies
- Review technical designs and code quality standards
- Manage technical debt and refactoring efforts
- Coordinate with QA on testability and quality standards
- Contribute technical input to planning and estimation

### Goals
- Deliver maintainable, scalable code that meets performance and reliability standards
- Reduce technical debt and cycle time
- Build a strong, capable development team
- Enable smooth handoffs and knowledge sharing

### Typical Communication
- Weekly technical design reviews
- Architecture and dependency discussions in planning
- Technical risk updates in risk registers
- Sprint planning and retrospectives

### Interactions with Other Roles
- **Developers:** Provide technical guidance, conduct code reviews, and mentor on best practices
- **Project Managers:** Communicate technical risks, dependencies, and capacity constraints
- **QA/Testing Lead:** Ensure code design supports testability and quality standards
- **Product Managers:** Advise on technical trade-offs and feasibility of feature requests
- **Release Manager:** Coordinate technical aspects of deployments and rollback strategies

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business interests and decision authority. They approve project scope, allocate resources, and serve as escalation points for major decisions and business-impacting issues.

### Responsibilities
- Approve project charter and business case
- Provide guidance on business priorities and trade-offs
- Allocate budget and resources to the project
- Make go/no-go decisions at key milestones
- Review and approve release decisions
- Serve as escalation point for business-impacting risks and issues
- Champion the project and communicate status to broader leadership

### Goals
- Ensure project delivers expected business value and ROI
- Maintain alignment between technical delivery and business strategy
- Minimize business risk and disruption

### Typical Communication
- Monthly stakeholder updates
- Milestone approval meetings
- Escalated risk and issue reviews
- Release announcements and post-release outcome briefings

### Interactions with Other Roles
- **Project Managers:** Receive status reports and escalated issues; provide strategic guidance
- **Product Managers:** Review business case validation and success metrics
- **Engineering Lead:** Address escalated technical risks and resource allocation decisions
- **Release Manager:** Approve release decisions and communicate outcomes to leadership

---

## Release Manager

### Role Summary
Release Managers own the end-to-end release process from planning through production verification. They coordinate deployments, manage communication, and ensure all pre- and post-release activities are completed.

### Responsibilities
- Create and maintain release plans and schedules
- Coordinate with developers, QA, and infrastructure teams on deployment timing
- Ensure all pre-release requirements are met (passing CI, security scans, documentation)
- Coordinate deployment windows and communicate status
- Manage release notes and stakeholder communication
- Execute or coordinate deployment to staging and production
- Run post-deployment verification and smoke tests
- Manage rollback procedures if issues occur
- Capture lessons learned and improve the release process

### Goals
- Deliver releases on schedule with high reliability
- Minimize deployment risk and post-release incidents
- Ensure clear communication throughout the release cycle
- Build repeatable, efficient release processes

### Typical Communication
- Release planning meetings with engineering and QA
- Pre-release checklists and sign-offs
- Deployment day communications and status updates
- Post-deployment retrospectives and metrics

### Interactions with Other Roles
- **QA/Testing Lead:** Coordinate smoke testing and release sign-off
- **Developers:** Track deployment status and troubleshoot release issues
- **Engineering Lead:** Coordinate technical deployment strategies and rollback procedures
- **Project Managers:** Communicate release timeline and status to stakeholders
- **Stakeholders/Sponsors:** Obtain approval for release decisions and communicate outcomes

---

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads ensure that projects meet security and regulatory requirements. They integrate security practices into the delivery pipeline and manage security-related risks and incidents.

### Responsibilities
- Define security requirements and acceptance criteria for projects
- Integrate security scanning and testing into CI/CD pipeline
- Review code and architecture for security vulnerabilities
- Assess and prioritize security-related risks
- Manage security incident response and communication
- Ensure compliance with regulatory and organizational standards
- Provide security training and guidance to development teams
- Review release readiness from a security perspective

### Goals
- Prevent security vulnerabilities and data breaches
- Maintain compliance with regulatory requirements
- Build a security-first culture across projects
- Enable fast, secure delivery

### Typical Communication
- Security requirements in project planning and acceptance criteria
- Security risk assessments in risk registers
- Security scanning results in CI/CD pipeline
- Security incident communication and post-incident reviews
- Quarterly security training and compliance reviews

### Interactions with Other Roles
- **Developers:** Provide security guidance and code review feedback on vulnerabilities
- **Project Managers:** Escalate security risks and compliance blockers; advise on incident communication
- **QA/Testing Lead:** Coordinate security testing and vulnerability assessment
- **Release Manager:** Verify security scanning completion before production release
- **Engineering Lead:** Advise on secure architecture and technical security debt

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
