# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

> **See also:** [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) for detailed role descriptions and collaboration guidance.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- **Identify**: during planning and ongoing execution
  - **Who**: All team members can raise risks; [Project Manager](octoacme-roles-and-personas.md#project-managers) consolidates
  - **Technical risks**: [Technical Lead](octoacme-roles-and-personas.md#technical-lead), [DevOps Specialist](octoacme-roles-and-personas.md#devops-specialist)
  - **Requirements risks**: [Business Analyst](octoacme-roles-and-personas.md#business-analyst), [Product Manager](octoacme-roles-and-personas.md#product-managers)
  - **Design/UX risks**: [UX Designer](octoacme-roles-and-personas.md#ux-designer)
- **Assess**: estimate impact and likelihood
  - **Led by**: [Project Manager](octoacme-roles-and-personas.md#project-managers) with input from relevant roles
- **Mitigate**: reduced via actions, contingency plans
  - **Owned by**: Role most relevant to the risk (e.g., Technical Lead for technical risks)
- **Monitor**: review at weekly syncs and update status
  - **Coordinated by**: [Project Manager](octoacme-roles-and-personas.md#project-managers) or [Scrum Master](octoacme-roles-and-personas.md#scrum-master)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- **Team-level** → [Project Manager](octoacme-roles-and-personas.md#project-managers) or [Scrum Master](octoacme-roles-and-personas.md#scrum-master)
- **Project Manager** → [Product Manager](octoacme-roles-and-personas.md#product-managers) / Product Lead
- **Product Lead** → Sponsor / Executive
- For **technical escalations**: [Developer](octoacme-roles-and-personas.md#developers) → [Technical Lead](octoacme-roles-and-personas.md#technical-lead) → [Project Manager](octoacme-roles-and-personas.md#project-managers)
- For **infrastructure incidents**: [DevOps Specialist](octoacme-roles-and-personas.md#devops-specialist) → [Technical Lead](octoacme-roles-and-personas.md#technical-lead) → Security/Ops leadership
- For **security incidents**: Follow the security incident runbook and notify Security on-call immediately

## Communication Cadence and Role Responsibilities
- **Daily**: [Scrum Master](octoacme-roles-and-personas.md#scrum-master) or team lead facilitates standup; all team members share updates
- **Weekly**: [Project Manager](octoacme-roles-and-personas.md#project-managers) provides status updates to stakeholders
- **Sprint/Milestone**: [Product Manager](octoacme-roles-and-personas.md#product-managers) demos completed work; team reviews metrics
- **Ad-hoc**: [Business Analyst](octoacme-roles-and-personas.md#business-analyst) clarifies requirements; [Technical Lead](octoacme-roles-and-personas.md#technical-lead) addresses technical questions
