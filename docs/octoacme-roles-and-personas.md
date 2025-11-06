# OctoAcme Personas

## Overview

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. These personas clarify accountability, hand-offs, and collaboration across the project lifecycle—from initiation through delivery and continuous improvement.

As projects scale, recognizing the full spectrum of contributors reduces ambiguity, improves onboarding, and ensures that implicit knowledge is captured explicitly. The personas below represent common roles across both traditional and agile delivery models.

Use these definitions to:
- Frame role-specific guidance in Copilot Spaces
- Clarify responsibilities and interaction points in process documents
- Support onboarding and cross-functional collaboration

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

### Collaboration Points
- **Technical Lead**: Seek guidance on architecture and complex technical decisions
- **UX Designer**: Collaborate on design implementation and feasibility
- **DevOps Specialist**: Coordinate on build, test, and deployment issues
- **Business Analyst**: Clarify requirements and acceptance criteria
- **Product Manager**: Discuss feature scope and technical trade-offs

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

### Collaboration Points
- **Business Analyst**: Partner on requirements and stakeholder alignment
- **UX Designer**: Collaborate on user needs and design direction
- **Technical Lead**: Discuss technical feasibility and effort estimates
- **Project Manager**: Align on priorities, timelines, and resource allocation
- **Developers**: Clarify feature intent and validate delivered value

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

### Collaboration Points
- **Product Manager**: Align on priorities and scope changes
- **Scrum Master**: Coordinate on team process and impediment removal (Agile teams)
- **Technical Lead**: Monitor technical risks and architecture decisions
- **DevOps Specialist**: Schedule releases and deployment windows
- **All team members**: Facilitate communication and remove blockers

---

## Scrum Master

### Role Summary
Scrum Masters guide the team in Agile practices, facilitate ceremonies, remove impediments, and foster continuous improvement. They ensure the team operates efficiently within the Agile framework.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and reviews
- Remove blockers and impediments for the team
- Coach the team on Agile principles and self-organization
- Protect the team from external distractions
- Track and improve team velocity and delivery metrics

### Goals
- Enable the team to deliver value predictably
- Foster a culture of continuous improvement
- Ensure ceremonies are effective and timeboxed
- Support team health and morale

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members to address concerns
- Coordination with Project Manager on risks and dependencies
- Sprint reports and velocity trends

### Collaboration Points
- **Project Manager**: Align on timelines, escalations, and cross-team dependencies
- **Product Manager**: Ensure backlog is ready and prioritized for sprint planning
- **Developers**: Remove technical and organizational blockers
- **Technical Lead**: Coordinate on technical debt and architectural decisions

---

## Technical Lead

### Role Summary
Technical Leads provide technical direction, oversee architecture and code quality, and support the team with complex technical challenges. They bridge engineering and product strategy.

### Responsibilities
- Define technical architecture and design patterns
- Review critical code changes and technical designs
- Make technical trade-off decisions
- Mentor developers on best practices and technologies
- Identify and manage technical risks and debt

### Goals
- Ensure technical solutions are scalable and maintainable
- Maintain high code quality and engineering standards
- Enable the team to make sound technical decisions
- Balance technical excellence with delivery timelines

### Typical Communication
- Technical design documents and architecture diagrams
- Code review comments and technical guidance
- Technical risk assessments during planning
- Architecture decision records (ADRs)

### Collaboration Points
- **Developers**: Provide guidance, review designs, pair on complex problems
- **Product Manager**: Advise on technical feasibility and effort estimates
- **Project Manager**: Report technical risks and suggest mitigations
- **DevOps Specialist**: Align on infrastructure and deployment architecture

---

## Business Analyst

### Role Summary
Business Analysts gather and analyze requirements, document business processes, and help translate business needs into technical solutions. They ensure alignment between stakeholder expectations and delivery.

### Responsibilities
- Elicit and document detailed requirements
- Analyze business processes and identify improvement opportunities
- Create user stories with clear acceptance criteria
- Facilitate requirements workshops with stakeholders
- Maintain traceability between business needs and delivered features

### Goals
- Ensure requirements are complete, clear, and testable
- Bridge communication between business stakeholders and technical teams
- Reduce rework by catching requirement gaps early
- Support stakeholder alignment throughout delivery

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and data models
- Stakeholder workshops and interviews
- Acceptance criteria validation sessions

### Collaboration Points
- **Product Manager**: Collaborate on feature definition and prioritization
- **Stakeholders**: Gather needs, validate requirements, and demo solutions
- **Developers**: Clarify requirements and answer questions during implementation
- **QA**: Define test scenarios and acceptance criteria

---

## UX Designer

### Role Summary
UX Designers create user-centered experiences, design interfaces, conduct usability research, and advocate for intuitive, accessible design. They ensure products meet user needs effectively.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and design systems
- Advocate for accessibility and inclusive design
- Validate designs with users and iterate based on feedback

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Maintain design consistency across products
- Base design decisions on user research and data

### Typical Communication
- Design mockups and interactive prototypes
- Usability test reports and user feedback summaries
- Design system documentation
- Collaboration sessions with product and engineering

### Collaboration Points
- **Product Manager**: Align on user needs, feature goals, and success metrics
- **Developers**: Collaborate on implementation feasibility and design hand-offs
- **Business Analyst**: Ensure designs address documented requirements
- **Stakeholders**: Present designs and gather feedback

---

## DevOps Specialist

### Role Summary
DevOps Specialists manage CI/CD pipelines, infrastructure, automation, monitoring, and incident response. They enable reliable, efficient software delivery and operations.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure as code and cloud resources
- Implement monitoring, logging, and alerting
- Respond to incidents and lead troubleshooting efforts
- Automate deployment and operational processes

### Goals
- Enable fast, reliable deployments
- Minimize downtime and production incidents
- Improve system observability and diagnostics
- Automate repetitive operational tasks

### Typical Communication
- Infrastructure diagrams and runbooks
- Incident reports and postmortems
- Deployment notifications and release updates
- Performance and availability metrics

### Collaboration Points
- **Developers**: Support with build, test, and deployment automation
- **Technical Lead**: Align on infrastructure architecture and scaling strategies
- **Project Manager**: Coordinate on release schedules and deployment windows
- **Product Manager**: Report on system health and operational metrics

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these roles in process documents to clarify ownership and hand-offs.

