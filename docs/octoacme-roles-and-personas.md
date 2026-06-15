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

## Additional Personas & Responsibilities

The following personas represent cross-functional and supporting roles that frequently appear in OctoAcme delivery workflows. Including these roles in your project charter and communications improves clarity, accelerates decision-making, and reduces handoff risks.

---

## Engineering Lead

### Role Summary
Engineering Leads own the technical design and architecture decisions for a project. They ensure code quality standards, conduct design reviews, and escalate complex technical challenges. They bridge product requirements and implementation feasibility.

### Responsibilities
- Lead technical design and architecture decisions
- Conduct design reviews and approve major technical changes
- Establish and maintain code quality standards
- Identify and propose solutions for technical risks
- Mentor developers and support skill development
- Escalate blockers and trade-offs to Project Manager and Product Manager

### Goals
- Ensure technical excellence and maintainability
- Reduce rework through early design validation
- Build a strong, collaborative engineering culture
- Minimize technical debt and long-term risks

### Interaction with Other Roles
- **With Developers:** Reviews designs, mentors on implementation, conducts code reviews
- **With Product Manager:** Discusses trade-offs between scope and feasibility
- **With Project Manager:** Escalates technical blockers and dependencies
- **With Security Reviewer:** Collaborates on threat modeling and secure design
- **With Observability Engineer:** Defines instrumentation and monitoring requirements

### Typical Communication
- Technical design documents and architecture reviews
- Weekly technical sync with developers
- Escalation meetings for complex decisions
- Code review comments and feedback

---

## Delivery Lead

### Role Summary
Delivery Leads own end-to-end delivery coordination, schedule tracking, and release readiness. They work closely with the Project Manager to ensure milestones are met and quality gates are passed before release.

### Responsibilities
- Track delivery milestones and schedule adherence
- Coordinate with QA, developers, and release teams on readiness
- Monitor and mitigate delivery risks and dependencies
- Ensure acceptance criteria are met and Definition of Done is followed
- Participate in release planning and deployment coordination
- Provide daily visibility on delivery status to PM and stakeholders

### Goals
- Deliver features on schedule and with agreed quality
- Minimize delays and rework cycles
- Ensure smooth handoffs between phases (development, QA, release)
- Maintain team accountability and momentum

### Interaction with Other Roles
- **With Project Manager:** Partners on milestone tracking and escalation
- **With QA/Testing:** Coordinates test readiness, sign-off, and release blockers
- **With Developers:** Monitors progress and flags risks early
- **With Stakeholder Liaison:** Ensures stakeholder communication on delivery status
- **With Observability Engineer:** Coordinates post-deploy verification activities

### Typical Communication
- Daily delivery status updates
- Weekly milestone review meetings
- Release readiness checklists and sign-offs
- Risk escalations and decision requests

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers own user research, interaction design, and usability validation. They ensure that features are intuitive, accessible, and meet real user needs before development begins.

### Responsibilities
- Conduct user research to validate problem statements
- Create wireframes, mockups, and design specifications
- Participate in acceptance criteria definition
- Validate design decisions with user testing or feedback
- Ensure accessibility and usability standards are met
- Collaborate with developers on implementation details

### Goals
- Ensure solutions address real user problems
- Maximize usability and reduce support burden
- Meet accessibility standards (WCAG, etc.)
- Reduce design rework through early validation

### Interaction with Other Roles
- **With Product Manager:** Validates outcomes through user research; provides design requirements
- **With Developers:** Hands off designs and supports implementation questions
- **With QA/Testing:** Defines acceptance criteria for usability and accessibility
- **With Project Manager:** Participates in planning to identify design research needs early

### Typical Communication
- User research findings and recommendations
- Design mockups and specifications
- Feedback on prototypes and implementation
- Accessibility and usability checklists

---

## Security Reviewer (Security SME)

### Role Summary
Security Reviewers own threat modeling, security architecture reviews, and compliance validation. They work across design and development to ensure security is built in from the start.

### Responsibilities
- Conduct threat modeling during design phase
- Review architecture and design for security risks
- Review code and PRs for security vulnerabilities
- Ensure compliance with security standards and policies
- Report and prioritize security findings
- Participate in security incident response (if applicable)

### Goals
- Prevent security vulnerabilities before production
- Ensure compliance with regulatory and organizational standards
- Build security-first culture across the team
- Minimize security incidents and breach risk

### Interaction with Other Roles
- **With Engineering Lead:** Partners on threat modeling and secure design decisions
- **With Developers:** Reviews code, provides guidance on secure coding practices
- **With Project Manager:** Escalates critical security findings for prioritization
- **With Product Manager:** Collaborates on security requirements and trade-offs
- **With Release Lead:** Validates security sign-off before production deployment

### Typical Communication
- Threat modeling documents
- Security review findings and recommendations
- Code review comments on security concerns
- Security compliance checklist and sign-offs

---

## Observability Engineer (SRE)

### Role Summary
Observability Engineers (often called Site Reliability Engineers or SREs) define monitoring, alerting, and instrumentation requirements. They ensure that systems are observable and that teams can quickly detect and respond to production issues.

### Responsibilities
- Define monitoring and alerting strategy for the feature
- Specify instrumentation requirements for developers
- Create runbooks and incident response procedures
- Support release and post-deploy verification activities
- Monitor system health and performance metrics
- Provide observability signals to PM and stakeholders

### Goals
- Ensure rapid detection and response to production issues
- Maximize system reliability and uptime
- Reduce mean-time-to-resolution (MTTR) for incidents
- Provide data-driven insights on system performance

### Interaction with Other Roles
- **With Developers:** Specifies instrumentation and monitoring code requirements
- **With Engineering Lead:** Collaborates on observability architecture
- **With Release Lead:** Supports post-deploy verification and monitoring setup
- **With Product Manager:** Provides performance and reliability metrics for dashboards
- **With Project Manager:** Escalates reliability risks or instrumentation gaps

### Typical Communication
- Monitoring and alerting specification documents
- Runbooks and incident response playbooks
- Post-deploy verification checklists
- Performance dashboards and reliability reports

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads own the definition of success metrics, instrumentation requirements, and dashboard maintenance. They ensure that decisions are informed by data and that project outcomes are measurable.

### Responsibilities
- Define success metrics aligned with project goals
- Specify data instrumentation and tracking requirements
- Validate that instrumentation is correctly implemented
- Create and maintain dashboards for success metrics
- Analyze outcomes and provide recommendations for iteration
- Ensure data collection complies with privacy standards

### Goals
- Enable data-driven decision-making
- Measure and validate project outcomes
- Identify optimization opportunities through analysis
- Support continuous improvement through data insights

### Interaction with Other Roles
- **With Product Manager:** Collaborates on success metrics definition and outcome validation
- **With Developers:** Specifies instrumentation and tracking requirements
- **With Project Manager:** Provides metrics for project health monitoring and reporting
- **With Observability Engineer:** Coordinates on instrumentation and data collection
- **With Stakeholders:** Presents findings and recommendations from metric analysis

### Typical Communication
- Success metrics definition documents
- Instrumentation specifications and validation reports
- Dashboard designs and maintenance schedules
- Analysis reports and outcome reviews

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the single point of contact for external stakeholders (leadership, customers, partners, support teams). They coordinate communication, manage expectations, and facilitate approvals.

### Responsibilities
- Identify stakeholder groups and communication needs
- Maintain regular stakeholder communication and status updates
- Gather stakeholder feedback and concerns
- Facilitate approval cycles and decision-making
- Escalate stakeholder concerns to PM and project team
- Draft stakeholder communications and announcements

### Goals
- Ensure stakeholder alignment and buy-in throughout the project
- Reduce surprises and misaligned expectations
- Accelerate approvals and decision-making
- Maintain positive stakeholder relationships

### Interaction with Other Roles
- **With Project Manager:** Partners on status reporting and escalation
- **With Product Manager:** Communicates product vision, roadmap, and outcomes to stakeholders
- **With Delivery Lead:** Coordinates delivery status updates to stakeholders
- **With Release Lead:** Manages communication around release timing and impact
- **With Team Members:** Collects updates and context for stakeholder communications

### Typical Communication
- Weekly or milestone-based stakeholder status updates
- Executive summaries and highlight reels
- Decision requests and approval processes
- Post-release announcements and impact reports

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning a project, identify which personas are needed for your team and clarify their responsibilities upfront.
