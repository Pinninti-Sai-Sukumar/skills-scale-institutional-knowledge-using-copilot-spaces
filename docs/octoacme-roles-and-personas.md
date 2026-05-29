# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Personas

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
- **Product Managers**: Clarify acceptance criteria and priorities
- **Project Managers**: Report progress, dependencies, and blockers
- **QA Lead**: Collaborate on test coverage and acceptance sign-off
- **UX/UI Designer**: Implement designs and provide technical feasibility feedback
- **DevOps Engineer**: Coordinate deployment and infrastructure needs

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
- **Project Managers**: Align on scope, timeline, and resource allocation
- **Developers**: Define requirements and validate technical feasibility
- **QA Lead**: Define acceptance criteria and quality gates
- **UX/UI Designer**: Collaborate on user experience and feature prioritization
- **Business Analyst**: Clarify business logic and requirements
- **Customer Support/Success**: Incorporate user feedback and support insights

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
- **Product Managers**: Align on priorities, scope, and resource allocation
- **Developers**: Track progress, identify blockers, facilitate unblocking
- **QA Lead**: Coordinate QA timeline and release readiness
- **DevOps Engineer**: Coordinate deployment windows and rollout plans
- **Business Analyst**: Align on requirements clarity and stakeholder needs
- **Customer Support/Success**: Communicate timeline and rollout impacts

---

## Supporting & Cross-Functional Personas

---

## QA Lead

### Role Summary
QA Leads oversee quality assurance strategies, define quality gates, and ensure features meet acceptance criteria before release. They collaborate closely with developers and product managers to establish testing approaches and validate readiness for production.

### Responsibilities
- Define test strategies and acceptance criteria validation plans
- Establish quality gates and sign-off criteria for releases
- Plan and execute manual and automated testing
- Identify and triage quality issues and regressions
- Collaborate with developers to improve testability
- Ensure compliance with security and performance standards

### Goals
- Deliver high-quality, reliable features to customers
- Reduce production incidents and rework
- Enable fast, confident releases through robust testing

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Test status reports and blockers
- Release readiness assessments and sign-off
- QA strategy and test plan documentation

### Interactions with Other Roles
- **Developers**: Collaborate on testability, clarify acceptance criteria, review test coverage
- **Product Managers**: Validate feature requirements and define acceptance criteria
- **Project Managers**: Report QA status, flag release blockers, coordinate testing timeline
- **DevOps Engineer**: Coordinate smoke testing and production verification
- **UX/UI Designer**: Validate user experience and usability during testing

---

## UX/UI Designer

### Role Summary
UX/UI Designers partner with product managers and developers to create user flows, visual designs, and interactive prototypes that deliver customer value and usability. They ensure consistency, accessibility, and customer-first outcomes across all features.

### Responsibilities
- Design user flows and wireframes aligned with product goals
- Create visual designs and design systems for consistency
- Conduct user research and usability testing
- Provide design specifications and assets to developers
- Collaborate on accessibility and performance considerations
- Iterate on designs based on feedback and metrics

### Goals
- Maximize user satisfaction and product adoption
- Ensure consistent, delightful user experiences
- Reduce usability issues and support burden

### Typical Communication
- Design reviews with stakeholders and developers
- User research and usability testing findings
- Design specifications and style guides
- Iteration discussions based on feedback

### Interactions with Other Roles
- **Product Managers**: Align on user needs, priorities, and feature direction
- **Developers**: Provide design specifications, discuss feasibility, iterate on implementation
- **QA Lead**: Validate design implementation and usability during testing
- **Business Analyst**: Clarify user workflows and business logic
- **Customer Support/Success**: Incorporate user feedback and pain points

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, maintain environment stability, design deployment strategies, and ensure observability across systems. They enable reliable, frequent deployments while maintaining system health and performance.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage development, staging, and production environments
- Ensure infrastructure stability, security, and scalability
- Implement monitoring, logging, and alerting
- Plan and execute deployments and rollbacks
- Collaborate on performance optimization and incident response

### Goals
- Enable fast, reliable deployments with minimal risk
- Maintain high system availability and performance
- Reduce deployment failures and incident response time

### Typical Communication
- CI/CD pipeline status and improvements
- Deployment plans and release coordination
- Infrastructure and environment updates
- Incident response and post-mortem discussions

### Interactions with Other Roles
- **Developers**: Support deployment, troubleshoot infrastructure issues, enable local development
- **QA Lead**: Coordinate smoke testing and production verification
- **Project Managers**: Coordinate deployment windows and rollout plans
- **Product Managers**: Communicate performance and scalability impacts

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholders and the delivery team by clarifying business requirements, documenting business logic, and validating solutions against business goals. They ensure alignment between what is built and what the business needs.

### Responsibilities
- Gather and clarify business requirements from stakeholders
- Document business logic, workflows, and rules
- Validate proposed solutions against business objectives
- Identify risks and dependencies from a business perspective
- Support change management and stakeholder communication
- Track business metrics and validate outcomes

### Goals
- Ensure solutions deliver measurable business value
- Reduce misalignment between business and delivery teams
- Enable clear, consistent business requirements

### Typical Communication
- Requirements documentation and clarification sessions
- Stakeholder interviews and feedback synthesis
- Business logic and process documentation
- Validation and sign-off of solutions

### Interactions with Other Roles
- **Product Managers**: Clarify business requirements and success metrics
- **Developers**: Explain business logic and requirements
- **Project Managers**: Communicate stakeholder needs and manage expectations
- **UX/UI Designer**: Understand user workflows and business processes
- **Customer Support/Success**: Incorporate business context and stakeholder feedback

---

## Customer Support/Success

### Role Summary
Customer Support and Success professionals provide frontline feedback from users, help triage support issues, escalate critical incidents, and close the loop with the delivery team on fixes and enhancements. They are the voice of the customer and drive continuous improvement.

### Responsibilities
- Collect and prioritize customer feedback and feature requests
- Triage and escalate customer-impacting issues
- Communicate customer impacts during incidents
- Validate fixes and enhancements with customers
- Provide insights to inform roadmap and product decisions
- Support onboarding and customer success initiatives

### Goals
- Maximize customer satisfaction and retention
- Reduce time to resolution for customer issues
- Inform product decisions through customer insights

### Typical Communication
- Customer feedback and issue reports
- Incident impact notifications and updates
- Feature validation and release communications
- Roadmap input and feature request summaries

### Interactions with Other Roles
- **Product Managers**: Provide customer feedback, validate features, inform prioritization
- **Developers**: Report issues, test fixes, provide customer context
- **Project Managers**: Communicate customer impacts and release timing
- **QA Lead**: Validate customer-reported issues and fixes
- **DevOps Engineer**: Coordinate on incident response and customer impact

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Other Roles" section to understand collaboration points and handoffs.
- When planning cross-functional initiatives, consult this document to ensure all necessary perspectives are represented.

