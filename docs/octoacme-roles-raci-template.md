# OctoAcme — RACI Template

A reusable template for assigning clear ownership of key tasks across the project lifecycle.

---

## How to use this template

1. Copy the table below into your project's documentation or issue tracker.
2. For each task, assign one of the following to each role column:
   - **R** — Responsible: does the work
   - **A** — Accountable: owns the outcome (only one per row)
   - **C** — Consulted: provides input before or during the work
   - **I** — Informed: notified of progress or decisions
3. Ensure every task has exactly one **A** (Accountable) entry.
4. Revisit the RACI at the start of each project phase to reflect any staffing or scope changes.
5. Use the [Roles & Personas doc](octoacme-roles-and-personas.md) as a reference for each role's responsibilities.

---

## RACI Table

| Task | Project Manager | Product Manager | Developer | UX Designer | DevOps Engineer | Business Analyst | Customer Support Lead |
|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | |
| Define project charter and goals | A | C | I | I | I | C | I |
| Identify and document stakeholders | A | C | I | I | I | R | I |
| Establish initial risk register | A | C | I | I | C | C | I |
| Confirm team availability and resources | A | C | R | C | C | I | I |
| **Planning** | | | | | | | |
| Conduct stakeholder kickoff | A | R | C | C | C | R | C |
| Elicit and document requirements | C | A | C | C | I | R | C |
| Create and prioritize backlog | C | A | C | C | I | R | I |
| Define acceptance criteria | I | A | C | C | I | R | I |
| Produce wireframes and prototypes | I | C | C | A | I | I | I |
| Estimate scope and capacity | A | C | R | C | C | C | I |
| Identify dependencies and integration points | A | C | R | C | R | C | I |
| Define Definition of Done | A | C | R | C | C | C | I |
| Create release plan and milestones | A | C | C | I | C | I | C |
| **Execution & Tracking** | | | | | | | |
| Implement features to acceptance criteria | I | I | A | C | C | C | I |
| Maintain CI/CD pipelines and environments | I | I | C | I | A | I | I |
| Conduct design reviews and UX validation | I | C | C | A | I | I | I |
| Update project board and track progress | A | I | R | R | R | R | I |
| Run daily standups | A | I | R | R | R | R | I |
| Triage and escalate blockers | A | C | R | C | C | C | I |
| **Risks & Communication** | | | | | | | |
| Maintain and review risk register | A | C | C | I | C | C | C |
| Send weekly status updates | A | C | I | I | I | I | I |
| Escalate business-impact risks | A | A | C | I | C | C | C |
| Relay customer-reported issues as risk input | C | C | I | I | I | C | A |
| **Release & Deployment** | | | | | | | |
| Schedule and coordinate deployment window | A | I | C | I | R | I | C |
| Verify pre-release checklist is complete | A | C | C | C | C | I | C |
| Execute deployment and run smoke tests | C | I | C | I | A | I | I |
| Prepare and publish release notes | A | C | R | I | C | C | R |
| Brief support staff before release | C | I | I | I | I | I | A |
| Monitor post-deploy signals and alerts | C | I | C | I | A | I | C |
| Coordinate rollback if needed | A | C | C | I | R | I | I |
| **Retrospective** | | | | | | | |
| Facilitate retrospective session | A | C | R | R | R | R | R |
| Document action items and owners | A | C | R | R | R | R | R |
| Track and follow up on retro action items | A | C | C | C | C | C | C |
| Surface customer feedback in retro | C | C | I | I | I | I | A |

---

## Notes
- This table covers the full OctoAcme lifecycle. Remove rows that do not apply to your project.
- Add project-specific tasks as rows with the same R/A/C/I notation.
- The full lifecycle is described in the [Project Management Overview](octoacme-project-management-overview.md).
- Role definitions are in the [Roles & Personas doc](octoacme-roles-and-personas.md).
