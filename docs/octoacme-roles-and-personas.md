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

## UX Designer

### Role Summary
UX Designers ensure that features are intuitive, accessible, and aligned with user needs. They bridge the gap between business requirements and the end-user experience throughout the product lifecycle.

### Responsibilities
- Design and validate user flows, wireframes, and prototypes
- Conduct or coordinate user research and usability testing
- Collaborate with Product Managers on requirements to ensure user-centered acceptance criteria
- Review implementation for fidelity to design intent and accessibility standards
- Document design decisions and maintain design assets

### Goals
- Deliver experiences that are intuitive and accessible to all users
- Reduce rework by validating designs early with real users
- Ensure visual and interaction consistency across product surfaces

### Typical Communication
- Design reviews and prototype walkthroughs during planning and execution
- Annotated mockups shared in pull requests or design tool links
- Usability findings summarized in project documentation

### Interactions with existing roles
- **Developers**: Share annotated designs and discuss technical constraints early; review implementation in code reviews and QA
- **Product Managers**: Co-define acceptance criteria that include UX requirements; align on scope and prioritization of design work
- **Project Managers**: Flag design-dependency risks during planning; confirm design deliverables in the [release readiness checklist](octoacme-roles-raci-template.md)

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain the infrastructure, CI/CD pipelines, and operational practices that keep OctoAcme services reliable and deployable. They partner with Developers and Project Managers to reduce release risk.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation (see [Release & Deployment Guide](octoacme-release-and-deployment.md))
- Monitor infrastructure reliability and respond to on-call alerts
- Define and enforce environment standards (staging, production)
- Implement and maintain security scanning, secrets management, and access controls
- Document runbooks and contribute to incident post-mortems

### Goals
- Enable fast, safe, and repeatable deployments
- Reduce mean time to recovery (MTTR) for production incidents
- Maintain infrastructure-as-code and eliminate manual deployment toil

### Typical Communication
- Deployment windows and rollback plans coordinated with Project Managers
- CI/CD status and incident updates via project board and on-call channels
- Runbooks and operational docs kept alongside process documentation

### Interactions with existing roles
- **Developers**: Provide pipeline feedback, merge gate requirements, and environment access; assist during debugging of CI failures
- **Product Managers**: Advise on operational feasibility and infrastructure cost implications for roadmap items
- **Project Managers**: Confirm deployment readiness status in the [RACI template](octoacme-roles-raci-template.md); escalate infrastructure risks during weekly syncs

---

## Business Analyst

### Role Summary
Business Analysts translate business needs into well-structured requirements that development teams can act on. They ensure that delivery work maps back to measurable business outcomes.

### Responsibilities
- Elicit, document, and validate business requirements from stakeholders
- Convert business needs into user stories with clear acceptance criteria (see [Project Planning](octoacme-project-planning.md))
- Analyse current processes and identify opportunities for improvement
- Maintain traceability between business goals and backlog items
- Support UAT planning and sign-off

### Goals
- Eliminate ambiguity in requirements before development begins
- Ensure delivered features demonstrably meet business objectives
- Improve stakeholder confidence through clear documentation

### Typical Communication
- Requirements workshops during project initiation and planning phases
- Acceptance criteria documented on backlog items
- UAT reports and sign-off communicated to Project Manager and Product Manager

### Interactions with existing roles
- **Developers**: Clarify acceptance criteria and edge cases; participate in backlog refinement and sprint reviews
- **Product Managers**: Align requirements with product vision; prioritize stories based on business impact data
- **Project Managers**: Flag scope changes early to support timeline adjustments; contribute to the risk register (see [Risks & Communication](octoacme-risks-and-communication.md))

---

## Customer Support Lead

### Role Summary
The Customer Support Lead represents the voice of existing customers in the project process. They surface insights from support ticket trends, coordinate release communication to support staff, and ensure feedback loops between customers and the project team stay open.

### Responsibilities
- Analyse support ticket trends and surface recurring issues to Product and Project Managers
- Communicate upcoming product changes to support staff ahead of releases (see [Release & Deployment Guide](octoacme-release-and-deployment.md))
- Contribute customer-impact context to risk assessments
- Participate in retrospectives to share post-release customer feedback (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))
- Maintain and update customer-facing release notes and FAQs

### Goals
- Reduce support ticket volume through proactive product improvements
- Ensure support teams are fully prepared before each release
- Close the feedback loop between customer pain points and backlog priorities

### Typical Communication
- Pre-release briefings for support staff
- Ticket trend summaries shared in weekly stakeholder updates
- Retro contributions highlighting customer-reported issues

### Interactions with existing roles
- **Developers**: Share reproduction steps and customer context for bug triage
- **Product Managers**: Provide data-backed input on customer pain points to inform prioritization
- **Project Managers**: Confirm support readiness as part of pre-release checks in the [RACI template](octoacme-roles-raci-template.md)

---

## How These Roles/Personas Are Used

### In the project lifecycle
Each persona is engaged at different stages of the project lifecycle. Use the [RACI Template](octoacme-roles-raci-template.md) to assign Responsible, Accountable, Consulted, and Informed designations across lifecycle phases for your specific project.

### Quick reference by phase
| Phase | Key roles involved |
|---|---|
| Initiation | Product Manager, Project Manager, Business Analyst, Stakeholders |
| Planning | All roles — Business Analyst and UX Designer drive requirements and design |
| Execution & Tracking | Developers, UX Designer, DevOps Engineer, Project Manager |
| Risks & Communication | Project Manager, Business Analyst, Customer Support Lead |
| Release & Deployment | DevOps Engineer, Project Manager, Customer Support Lead, Developers |
| Retrospective | All roles |

### As Copilot Spaces persona prompts
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [RACI Template](octoacme-roles-raci-template.md) to understand ownership expectations per role before writing prompts.

