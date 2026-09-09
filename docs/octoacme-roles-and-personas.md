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

### Key Interactions
- Work with Product Managers on acceptance criteria clarification
- Collaborate with QA/Testing Leads on testability and test coverage
- Engage with Technical Architects on design reviews and technical decisions
- Coordinate with DevOps/Ops Engineers on deployment and operational concerns

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

### Key Interactions
- Work with Project Managers on timeline and resource planning
- Collaborate with QA/Testing Leads to define acceptance criteria and testing strategy
- Partner with Security Officers to incorporate security requirements into features
- Engage with Business Analysts to translate market needs into feature specifications

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

### Key Interactions
- Coordinate with Product Managers on prioritization and scope decisions
- Work with all technical roles (Developers, Technical Architects, DevOps/Ops Engineers) to track delivery progress
- Engage Engineering Managers/Tech Leads on team capacity and resource allocation
- Escalate risks and dependencies identified by any team member

---

## Quality Assurance / Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and acceptance validation. They work with Product Managers to define acceptance criteria and with Developers to establish testing standards. They ensure features meet quality expectations before release.

### Responsibilities
- Design and maintain comprehensive test strategy (unit, integration, end-to-end, smoke tests)
- Create and prioritize test cases aligned with acceptance criteria
- Conduct manual QA and acceptance testing
- Identify defects, coordinate retesting, and track quality metrics
- Report on test coverage and quality metrics during release readiness reviews
- Advise on test automation opportunities and help establish testing best practices
- Participate in release planning to ensure adequate testing time

### Goals
- Ensure all features meet acceptance criteria before release
- Maintain high-quality standards and catch regressions early
- Enable team confidence in deployments through comprehensive testing
- Provide data-driven quality insights to inform release decisions

### Typical Communication
- Sprint planning and backlog refinement sessions to review acceptance criteria
- Test plans and test case documentation
- Quality reports and metrics in weekly status updates and pre-release reviews
- Defect logs and triage discussions with Developers and Product Managers
- Post-release retrospectives to capture quality learnings

### Key Interactions
- Collaborate with Product Managers to clarify and validate acceptance criteria
- Work with Developers on testability during design and implementation
- Partner with Technical Architects on test strategy for complex systems
- Coordinate with DevOps/Ops Engineers on test environment setup and smoke testing procedures
- Report quality status to Project Managers for release decision-making

### Project Phase Engagement
- **Initiation**: Contribute to quality risk assessment
- **Planning**: Define test strategy and acceptance criteria validation approach
- **Execution**: Execute testing activities, identify and report defects
- **Release**: Conduct smoke tests and sign off on quality readiness
- **Retrospective**: Share quality metrics and identify testing improvements

---

## Technical Architect

### Role Summary
Technical Architects define technical direction, design solutions for complex problems, and ensure systems are scalable, maintainable, and secure. They collaborate with Developers, DevOps, and Project Managers to align technical decisions with business goals and long-term strategy.

### Responsibilities
- Review and approve technical designs and architectural decisions
- Identify technical risks and propose mitigations
- Guide technology choices, integration strategies, and system design patterns
- Review code for architectural alignment and best practices
- Mentor developers on system design, scalability, and maintainability
- Document system architecture and decision rationale (Architecture Decision Records)
- Ensure architectural decisions support security and operational requirements

### Goals
- Deliver scalable, maintainable, and secure systems
- Minimize technical debt and costly rework
- Support long-term product evolution and team growth
- Enable developers to make sound technical decisions independently

### Typical Communication
- Technical design reviews and architecture decision records (ADRs)
- Code review comments and architecture feedback
- Risk register updates for technical risks
- Design documentation and system architecture diagrams
- Technical mentoring sessions and knowledge-sharing

### Key Interactions
- Collaborate with Developers on design reviews and technical guidance
- Partner with DevOps/Ops Engineers to ensure operational and infrastructure considerations are incorporated
- Work with Technical Leads/Engineering Managers on team architecture standards
- Engage with Security Officers to embed security into system design
- Inform Project Managers of technical risks and mitigation strategies
- Align with Product Managers on technical feasibility of proposed features

### Project Phase Engagement
- **Planning**: Define technical approach, architecture, and design standards
- **Execution**: Review designs and code, provide architectural guidance
- **Release**: Assess technical readiness and deployment strategy
- **Retrospective**: Capture architectural learnings and improvements

---

## Security Officer

### Role Summary
Security Officers provide security guidance, conduct threat assessments, and ensure compliance with security and privacy standards. They are engaged from planning through release to embed security into the delivery process and protect customer data and system integrity.

### Responsibilities
- Review features for security and privacy implications
- Conduct threat assessments and security design reviews
- Establish security requirements and acceptance criteria for features
- Coordinate security testing and vulnerability scanning in CI/CD
- Review and approve release security readiness
- Respond to security incidents and lead post-incident reviews (blameless retrospectives)
- Ensure compliance with regulatory and organizational security standards
- Advise on secure coding practices and security tooling

### Goals
- Protect customer data and system integrity
- Prevent security vulnerabilities from reaching production
- Ensure compliance with regulatory and organizational standards
- Build a security-first culture across the delivery team

### Typical Communication
- Security requirement documents and threat assessments
- Security acceptance criteria in backlog items
- Security sign-off before release
- Incident response and post-mortems
- Security training and awareness communications
- Risk register updates for security risks

### Key Interactions
- Collaborate with Product Managers to incorporate security requirements into features
- Work with Developers and Technical Architects on secure design and implementation
- Partner with QA/Testing Leads on security testing strategy and vulnerability scanning
- Coordinate with DevOps/Ops Engineers on security infrastructure and compliance monitoring
- Inform Project Managers of security risks and release readiness

### Project Phase Engagement
- **Initiation**: Identify security risks and compliance requirements
- **Planning**: Define security requirements and testing strategy
- **Execution**: Review designs, conduct security reviews, coordinate security testing
- **Release**: Approve security readiness and oversee secure deployment
- **Retrospective**: Review security incidents and improve security practices

---

## Business Analyst

### Role Summary
Business Analysts translate business requirements, market needs, and customer feedback into clear technical specifications and feature requirements. They bridge business and technical teams to ensure solutions deliver measurable business value.

### Responsibilities
- Gather and document business requirements and user needs
- Analyze business processes and identify improvement opportunities
- Translate business requirements into detailed technical specifications
- Validate scope with stakeholders and identify gaps or conflicts
- Create user stories and acceptance criteria aligned with business goals
- Support trade-off analysis between business priorities and technical constraints
- Measure and report on business value delivered by features

### Goals
- Ensure solutions align with business objectives and customer needs
- Reduce rework by clarifying requirements upfront
- Enable data-driven decisions about feature prioritization and trade-offs
- Maximize return on investment for development efforts

### Typical Communication
- Requirements documentation and user story specifications
- Business case and impact analysis for features
- Stakeholder briefings and feedback sessions
- Acceptance criteria and success metrics
- Business value reporting in retrospectives and demos

### Key Interactions
- Collaborate with Product Managers to translate market insights into feature requirements
- Work with Developers and Technical Architects to assess feasibility and identify trade-offs
- Partner with Project Managers on scope management and timeline planning
- Coordinate with QA/Testing Leads to ensure acceptance criteria are measurable and testable
- Engage with stakeholders to validate requirements and gather feedback

### Project Phase Engagement
- **Initiation**: Support business case development and stakeholder alignment
- **Planning**: Create requirements documentation and acceptance criteria
- **Execution**: Clarify requirements and support scope management
- **Release**: Validate delivered features meet business objectives
- **Retrospective**: Report on business value realized and improvements

---

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers and Tech Leads provide technical mentorship, oversee code quality, manage team development, and enable developers to deliver high-quality work efficiently. They balance team capacity, career growth, and technical excellence.

### Responsibilities
- Mentor and develop individual contributors and junior engineers
- Oversee code quality standards and review practices
- Manage team capacity planning and work allocation
- Identify and mitigate technical risks within the team
- Foster a culture of continuous learning and psychological safety
- Represent engineering in planning and prioritization discussions
- Support career development and performance feedback
- Remove blockers and support team productivity

### Goals
- Develop high-performing, collaborative engineering teams
- Maintain code quality and system reliability
- Reduce cycle time and improve delivery efficiency
- Support retention and career growth of team members

### Typical Communication
- One-on-one feedback and career development conversations
- Code review oversight and quality standards
- Team planning and capacity discussions
- Technical mentoring and knowledge-sharing sessions
- Status updates and team health metrics

### Key Interactions
- Work with Developers on mentorship, code quality, and capability development
- Partner with Technical Architects on architecture standards and design decisions
- Collaborate with Project Managers on team capacity and timeline planning
- Engage with QA/Testing Leads on quality standards and testing practices
- Coordinate with Product Managers on feature feasibility and team bandwidth
- Support DevOps/Ops Engineers on operational readiness

### Project Phase Engagement
- **Planning**: Input on team capacity, effort estimates, and technical risks
- **Execution**: Mentor team, ensure quality standards, remove blockers
- **Release**: Support release readiness and team support during deployment
- **Retrospective**: Gather team feedback and drive continuous improvement

---

## DevOps / Ops Engineer

### Role Summary
DevOps/Ops Engineers manage infrastructure, deployment pipelines, monitoring, and operational readiness. They enable reliable, scalable systems and support smooth deployments from development through production.

### Responsibilities
- Design and maintain infrastructure and deployment pipelines
- Implement automated testing, building, and deployment processes (CI/CD)
- Manage environments (development, staging, production) and configurations
- Monitor system health, performance, and security in production
- Support incident response and system troubleshooting
- Establish operational standards and runbooks
- Optimize infrastructure for cost, performance, and reliability
- Coordinate backups, disaster recovery, and business continuity

### Goals
- Enable reliable, secure, and scalable deployments
- Minimize downtime and improve system observability
- Automate repetitive tasks and reduce manual effort
- Support rapid iteration while maintaining system stability

### Typical Communication
- Infrastructure documentation and runbooks
- Deployment procedures and release coordination
- Incident alerts and post-incident reviews
- Performance metrics and capacity planning
- Operational readiness checklists for releases
- Infrastructure cost and optimization reports

### Key Interactions
- Collaborate with Developers on deployment concerns and application observability
- Partner with Technical Architects on infrastructure design and scalability
- Work with QA/Testing Leads on test environment setup and smoke testing
- Coordinate with Project Managers on deployment scheduling and release timing
- Support Security Officers on infrastructure security and compliance monitoring
- Engage with Engineering Managers on team operational practices

### Project Phase Engagement
- **Planning**: Design infrastructure and deployment approach
- **Execution**: Support development environment needs, maintain CI/CD pipeline health
- **Release**: Coordinate deployment, monitor system health, support rollback if needed
- **Retrospective**: Share operational learnings and identify infrastructure improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the "Key Interactions" sections to understand cross-functional dependencies and communication patterns.
- Use the "Project Phase Engagement" sections to understand when each role is most critical in the project lifecycle.
