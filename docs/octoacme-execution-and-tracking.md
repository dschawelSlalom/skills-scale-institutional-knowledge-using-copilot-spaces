# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

> **See also:** [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) for detailed role descriptions and collaboration guidance.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - **Facilitated by**: [Scrum Master](octoacme-roles-and-personas.md#scrum-master) or [Project Manager](octoacme-roles-and-personas.md#project-managers)
  - **Attendees**: [Developers](octoacme-roles-and-personas.md#developers), [Technical Lead](octoacme-roles-and-personas.md#technical-lead), [UX Designer](octoacme-roles-and-personas.md#ux-designer), [DevOps Specialist](octoacme-roles-and-personas.md#devops-specialist)
- Weekly delivery sync — show progress, updates, and flagged risks
  - **Led by**: [Project Manager](octoacme-roles-and-personas.md#project-managers)
  - **Attendees**: Full team plus stakeholders as needed
- Demo/Review at the end of each sprint or milestone
  - **Presented by**: [Product Manager](octoacme-roles-and-personas.md#product-managers) and team members
  - **Attendees**: Stakeholders, full delivery team

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup
  - **Owner**: [Scrum Master](octoacme-roles-and-personas.md#scrum-master) or team lead
  - **Action**: Identify resources or workarounds to unblock immediately
- **Level 2**: [Project Manager](octoacme-roles-and-personas.md#project-managers) escalates to Product Lead and dependent teams
  - **When**: Blocker impacts sprint commitment or milestone
  - **Action**: Coordinate cross-team resources or re-prioritize work
- **Level 3**: Sponsor-level escalation for business-impacting issues
  - **When**: Issue affects project timeline, budget, or strategic goals
  - **Action**: Executive decision-making and resource allocation

## Cross-Role Interactions During Execution
- **Developers ↔ Technical Lead**: Code reviews, architectural guidance, technical decisions
- **Developers ↔ UX Designer**: Design clarifications, implementation feasibility discussions
- **Developers ↔ DevOps Specialist**: Build/deployment issues, infrastructure support
- **Business Analyst ↔ Developers**: Requirements clarification, acceptance criteria validation
- **Scrum Master ↔ Team**: Remove impediments, facilitate ceremonies, track velocity
- **Project Manager ↔ All Roles**: Status tracking, risk management, stakeholder communication

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Daily standups held consistently
- [ ] [Technical Lead](octoacme-roles-and-personas.md#technical-lead) reviewing critical code changes
- [ ] [DevOps Specialist](octoacme-roles-and-personas.md#devops-specialist) monitoring system health and CI/CD pipelines
- [ ] [Scrum Master](octoacme-roles-and-personas.md#scrum-master) tracking team velocity and removing impediments (Agile teams)
