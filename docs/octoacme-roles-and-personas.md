# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A role describes an area of accountability; on smaller projects, one person may cover multiple roles, while larger projects may assign a role to several people. Teams should make ownership and decision authority explicit for each project.

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

## UX/UI Designers and User Researchers

### Role Summary
UX/UI Designers and User Researchers investigate user needs and design usable, accessible experiences that solve the prioritized problem.

### Responsibilities
- Plan and conduct user research, and share findings
- Create user flows, prototypes, and interface designs
- Validate usability and accessibility with users and appropriate standards
- Identify experience risks and incorporate feedback into design iterations

### Collaboration with Existing Roles
- Work with Product Managers to refine user problems, priorities, and acceptance criteria
- Partner with Developers and the Tech Lead to assess feasibility and clarify design intent
- Coordinate research, design reviews, and dependencies with Project Managers
- Share user findings with the Business Sponsor when they inform strategic choices

---

## Tech Leads and Software Architects

### Role Summary
Tech Leads and Software Architects guide technical direction so that solutions are secure, reliable, maintainable, and feasible within project constraints.

### Responsibilities
- Define or facilitate architecture and technical design decisions
- Identify technical dependencies, constraints, and risks; recommend mitigations
- Support Developers through implementation, design reviews, and technical problem solving
- Advise on non-functional requirements such as performance, security, and reliability

### Collaboration with Existing Roles
- Work with Developers to align implementation and resolve technical questions
- Explain technical options and trade-offs to Product Managers so scope and priorities reflect feasibility
- Provide estimates, dependencies, and technical risks to Project Managers for planning and escalation
- Coordinate with QA/Test Engineers and Operations/SRE on testability, observability, and operational readiness

---

## QA/Test Engineers

### Role Summary
QA/Test Engineers help the team prevent defects and establish whether delivered work meets its acceptance criteria and quality expectations.

### Responsibilities
- Define risk-based test approaches and appropriate test coverage
- Verify requirements and acceptance criteria through manual or automated testing
- Report defects with clear reproduction details and impact
- Communicate quality risks, test status, and release-readiness evidence

### Collaboration with Existing Roles
- Partner with Developers to plan testability, automate checks, and investigate defects
- Clarify expected behavior and acceptance criteria with Product Managers
- Keep Project Managers informed of test progress, blockers, and quality risks for status and release planning
- Coordinate with Tech Leads and Operations/SRE on integration, performance, and production-readiness testing

---

## Operations/SRE and Release Managers

### Role Summary
Operations/SRE and Release Managers prepare and coordinate safe deployment and operation of changes, including monitoring service health and recovery readiness.

### Responsibilities
- Define operational and deployment requirements, including monitoring and alerting
- Coordinate release plans, deployment steps, and rollback or recovery procedures
- Assess operational readiness and communicate service risks
- Support incident response and capture operational follow-up actions

### Collaboration with Existing Roles
- Work with Developers and Tech Leads to make services deployable, observable, and reliable
- Align with Product Managers on customer impact, release timing, and user-facing communications
- Coordinate release dependencies, readiness checks, and stakeholder updates with Project Managers
- Use QA/Test Engineer results as input to readiness decisions and communicate operational risks to the team

---

## Business Sponsors and Key Stakeholders

### Role Summary
Business Sponsors and Key Stakeholders provide strategic context, represent affected groups, and make or escalate decisions that require business authority.

### Responsibilities
- Communicate business goals, constraints, and expected outcomes
- Provide timely decisions on escalated scope, priority, or resource trade-offs
- Review progress and outcomes against agreed success measures
- Identify impacted stakeholder groups and support adoption when needed

### Collaboration with Existing Roles
- Work with Product Managers to connect customer and business value to product priorities and success measures
- Rely on Project Managers for milestone, risk, and decision updates; route delivery coordination through them rather than directing day-to-day team work
- Provide Developers and Tech Leads with business context through the Product Manager when it informs technical trade-offs
- Review user research and delivery outcomes with Product Managers to inform future decisions

---

## Applying Roles to a Project

Not every project needs a separate person for every role. At kickoff, the Project Manager and Product Manager should identify which responsibilities apply, name an accountable owner for each, and clarify who makes decisions and how unresolved issues are escalated. When one person covers multiple roles, teams should still distinguish the responsibilities and manage potential conflicts of interest, such as independently verifying work they implemented.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
