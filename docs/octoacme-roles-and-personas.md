# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Extended Roles & Cross-Functional Personas

These personas represent operational, design, governance, and support roles that frequently participate in cross-functional projects. Including them improves clarity on responsibilities, reduces handoff ambiguity, and strengthens accountability across all project dimensions.

---

### Technical Lead / Architect

#### Role Summary
Technical Leads define system architecture, make key technical decisions, and ensure design consistency and scalability. They serve as the technical authority and strategic advisor for complex initiatives.

#### Responsibilities
- Define system architecture and technical direction
- Make key technical decisions and trade-offs
- Ensure design consistency, scalability, and maintainability
- Conduct technical reviews and design validation
- Identify and mitigate technical risks and dependencies
- Mentor developers on technical best practices

#### Interactions
- **Developers**: Provide architectural guidance and design reviews; clarify implementation patterns and technical decisions
- **Product Managers / Project Managers**: Collaborate on technical trade-offs, feasibility, and resource requirements
- **QA/Testing**: Align on integration testing plans and test infrastructure needs
- **Platform / Infrastructure Engineer**: Coordinate on deployment architecture and operational requirements
- **Security Liaison**: Review designs for security controls and compliance implications

#### Typical Communication
- Technical design reviews and architecture discussions
- Sprint planning and estimation refinement
- Risk registers for technical dependencies
- Cross-team technical alignment meetings

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers lead user research, craft intuitive UX flows and high-fidelity designs, and validate usability. They are advocates for the user and ensure the product is discoverable, accessible, and delightful.

#### Responsibilities
- Conduct user research and usability studies
- Create wireframes, prototypes, and high-fidelity designs
- Define user flows and interaction patterns
- Validate designs through testing and feedback
- Ensure accessibility and design consistency
- Document design decisions and rationale
- Support QA in acceptance criteria related to usability and UX

#### Interactions
- **Product Managers**: Partner to align user needs with product outcomes and prioritization
- **Developers**: Hand off designs and collaborate on feasibility and implementation details
- **QA/Testing**: Define acceptance criteria related to user experience, navigation, and accessibility
- **Project Managers**: Provide design timeline estimates and dependencies
- **Stakeholders**: Present research findings and design direction for feedback

#### Typical Communication
- Design reviews and feedback sessions
- User research reports and insights
- Design specifications and component documentation
- Usability testing sessions and results

---

### Platform / Infrastructure Engineer

#### Role Summary
Platform and Infrastructure Engineers ensure platform reliability, automate deployments, and manage CI/CD pipelines and environment provisioning. They enable teams to ship code safely and frequently.

#### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Provision and manage development, staging, and production environments
- Implement infrastructure-as-code and configuration management
- Optimize build times and deployment processes
- Monitor infrastructure health and capacity
- Support incident response and rollback procedures
- Collaborate on disaster recovery and business continuity planning

#### Interactions
- **Developers**: Provide deployment pipeline support, CI/CD tooling guidance, and environment access
- **Release Manager**: Coordinate deployment windows and post-release verification procedures
- **Observability / SRE Engineer**: Collaborate on monitoring, logging, and alerting infrastructure
- **Security Liaison**: Implement security controls in CI/CD pipelines and environment hardening
- **Technical Lead / Architect**: Align on infrastructure architecture and scalability requirements

#### Typical Communication
- Deployment runbooks and CI/CD documentation
- Infrastructure design reviews
- On-call escalations for infrastructure issues
- Capacity planning and performance optimization discussions

---

### Release Manager

#### Role Summary
Release Managers coordinate releases, maintain release checklists, and own rollback and mitigation plans. They ensure releases are predictable, safe, and communicated clearly to all stakeholders.

#### Responsibilities
- Create and maintain release checklists and procedures
- Coordinate release readiness across all teams
- Manage release timelines and deployment windows
- Own rollback and mitigation plans
- Lead post-release verification and sign-off
- Communicate release status and updates to stakeholders
- Document release notes and known issues
- Coordinate with support on customer communication

#### Interactions
- **Project Manager / Product Manager**: Align on release timing, contents, and stakeholder communication
- **Platform / Infrastructure Engineer**: Coordinate deployment windows and rollback procedures
- **QA/Testing**: Ensure all acceptance criteria are met before release; plan smoke tests
- **Developers**: Coordinate final code freeze and hotfix procedures
- **Support / Customer Success**: Align on customer communication and known issues
- **Security Liaison**: Ensure security scans and compliance checks are complete

#### Typical Communication
- Release status reports and deployment logs
- Release notes and change summaries
- Stakeholder communications and go/no-go decisions
- Post-release retrospectives and incident reports

---

### Observability / SRE Engineer

#### Role Summary
Observability and SRE Engineers define monitoring, alerting, and incident response requirements. They instrument systems for visibility and enable rapid detection and resolution of issues.

#### Responsibilities
- Design and implement monitoring and alerting strategies
- Define and maintain incident runbooks and playbooks
- Create dashboards for key signals (errors, latency, resource usage)
- Own log aggregation and analysis infrastructure
- Support incident triage and root cause analysis
- Optimize system performance and reliability
- Define SLOs, SLIs, and error budgets
- Lead post-incident reviews and process improvements

#### Interactions
- **Developers**: Collaborate on instrumentation, metrics collection, and logging integration
- **Platform / Infrastructure Engineer**: Coordinate on infrastructure monitoring and alerting setup
- **Project Manager / Product Manager**: Report on service health and incident impacts
- **Support / Customer Success**: Provide visibility into service status and incident updates
- **Technical Lead / Architect**: Align on observability requirements in system design

#### Typical Communication
- Alerting rules and dashboard documentation
- Incident reports and post-mortems
- Performance metrics and SLO reviews
- On-call escalations and incident commands

---

### Security Liaison

#### Role Summary
Security Liaisons perform threat assessment, ensure security controls are implemented, and ensure compliance requirements are addressed early in the development lifecycle.

#### Responsibilities
- Perform threat modeling and risk assessment
- Conduct security code reviews and design reviews
- Ensure compliance requirements are met (e.g., data privacy, encryption)
- Coordinate security scanning in CI/CD pipelines
- Identify and track security vulnerabilities
- Define and enforce security policies and standards
- Lead security incident response and notification
- Provide security guidance to development teams

#### Interactions
- **Developers**: Advise on secure coding practices and architectural decisions
- **Technical Lead / Architect**: Review system designs for security controls and threat mitigation
- **Platform / Infrastructure Engineer**: Coordinate on infrastructure security and hardening
- **Release Manager**: Ensure security scanning and compliance checks complete before release
- **Project Manager / Product Manager**: Escalate high-risk items and compliance blockers
- **Observability / SRE Engineer**: Coordinate on security event detection and incident response

#### Typical Communication
- Security threat models and risk assessments
- Vulnerability reports and remediation plans
- Security policy and standards documentation
- Incident response and post-breach communications

---

### Data Analyst / Data Engineer

#### Role Summary
Data Analysts and Data Engineers define success metrics instrumentation, validate data quality, and provide analysis to inform product and business decisions.

#### Responsibilities
- Define key metrics and success criteria instrumentation
- Design and maintain data pipelines and ETL processes
- Ensure data quality and validation
- Create dashboards and reports for stakeholder visibility
- Analyze usage patterns and user behavior
- Support A/B testing and experimentation frameworks
- Provide actionable insights for product decisions
- Maintain data governance and documentation

#### Interactions
- **Product Managers**: Collaborate on success metrics definition and product performance analysis
- **Developers**: Integrate telemetry and logging for metrics collection
- **Observability / SRE Engineer**: Coordinate on event data collection and real-time analytics
- **Project Manager**: Provide reporting on project KPIs and milestones
- **Stakeholders**: Present analytics findings and business impact

#### Typical Communication
- Metrics definitions and instrumentation documentation
- Dashboard and report creation
- Analytics insights and recommendations
- Data quality audits and validation results

---

### Business Analyst / Delivery Lead

#### Role Summary
Business Analysts and Delivery Leads translate stakeholder requirements into clear backlog items, manage acceptance criteria, and drive cross-team coordination to ensure successful delivery.

#### Responsibilities
- Gather and document stakeholder requirements
- Translate requirements into clear user stories and acceptance criteria
- Manage backlog prioritization and refinement
- Drive sprint delivery coordination and unblock teams
- Track deliverables against timelines and commitments
- Facilitate cross-team communication and dependencies
- Document process improvements and lessons learned

#### Interactions
- **Product Manager / Project Manager**: Align on scope, priorities, and timelines
- **Developers / Technical Lead**: Refine requirements and clarify acceptance criteria
- **QA/Testing**: Define test scenarios and acceptance criteria
- **Stakeholders**: Communicate status and manage expectations
- **All teams**: Facilitate standups, planning sessions, and reviews

#### Typical Communication
- User story documentation and backlog refinement
- Requirement clarification and scope discussions
- Sprint status reports and delivery updates
- Retrospectives and process improvement discussions

---

### Stakeholder Representative (e.g., Customer Success, Sales, Support)

#### Role Summary
Stakeholder Representatives advocate for customer and business needs, provide input on prioritization, and surface downstream impacts. They bridge the gap between delivery teams and the broader organization.

#### Responsibilities
- Represent customer needs and feedback in prioritization
- Provide market and business context for features
- Identify downstream impacts (support, sales, operations)
- Provide input on success metrics and customer value
- Support release communications and customer enablement
- Escalate critical customer issues and blockers
- Provide feedback on usability and product fit

#### Interactions
- **Product Manager / Project Manager**: Provide customer feedback and business context for planning
- **Release Manager**: Coordinate on customer communications and release timing
- **Developers / Technical Lead**: Collaborate on feature design and customer requirements
- **UX Researcher / Designer**: Provide user feedback and support UX validation
- **Support / Operations**: Ensure smooth rollout and customer adoption

#### Typical Communication
- Customer feedback and requirements documentation
- Business impact assessments
- Release communications and customer enablement
- Stakeholder updates and leadership briefings

---

## How These Personas Are Used

- **In Project Planning**: Use these persona definitions to identify required roles and dependencies for your project. Not all projects require all personas.
- **In Process Documentation**: Reference these personas when defining responsibilities and communication patterns (e.g., "Technical Lead reviews design" or "Release Manager coordinates with Platform Engineer").
- **In Copilot Spaces**: Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance and documentation.
- **In Skills Exercises**: Use these definitions to frame scenarios and sample interactions that represent realistic cross-functional collaboration.
- **In Onboarding**: Share relevant persona definitions with new team members to clarify roles, responsibilities, and collaboration expectations.
