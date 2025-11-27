# Docs — OctoAcme Project Processes

This folder contains OctoAcme's program process documents: lightweight, versioned guides to how we initiate, plan, execute, release, and continuously improve projects. These documents are intended to be the single source of truth for project artifacts (one‑pagers, backlogs, risk registers, release checklists) and to help contributors find, follow, and update process guidance. To propose changes to any process doc, please use the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml template.

OctoAcme follows a stage‑gated, iterative lifecycle that starts with a concise Project One‑pager to validate the business need and success metrics, then moves to planning where scope is broken down into prioritized backlog items with acceptance criteria and a Definition of Done. Execution is iterative and focused on small, traceable increments — teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done), timeboxed iterations, and a Pull Request workflow that enforces linked issues, CI checks, and required approvals. Releases are gated by pre‑release checks, release notes, and rollback playbooks; post‑deploy verifications and incident playbooks close the loop when problems arise.

Roles and responsibilities are explicit: Product Managers own the vision and backlog prioritization, Project Managers coordinate schedules, risks, and stakeholder communications, Developers implement features and tests, and QA validates acceptance criteria and product quality. This clear role separation supports ownership while encouraging collaboration during planning, reviews, and retrospectives. Persona definitions and responsibilities are documented so teams can quickly onboard and understand expectations.

Communication is cadence‑driven and transparent: daily standups, regular PM/PdM alignment, weekly delivery syncs, demos at the end of sprints or milestones, and monthly stakeholder updates. Reporting uses velocity, burndown, and dashboards for key signals (errors, latency, usage), while risks are tracked in a Risk Register and escalated through defined paths. Continuous improvement happens through timeboxed retrospectives that produce prioritized action items tracked back into the backlog.

Where to find more
- octoacme-project-management-overview.md — concise intro to approach, roles, and artifacts
- octoacme-project-initiation.md — templates and checklist for starting a project
- octoacme-project-planning.md — backlog, estimates, DoD, and planning checklist
- octoacme-execution-and-tracking.md — team rhythm, PR workflow, QA and reporting
- octoacme-release-and-deployment.md — release types, pre-release checks, and rollback playbook
- octoacme-risks-and-communication.md — risk register, stakeholder templates, and escalation
- octoacme-retrospective-and-continuous-improvement.md — running retros, tracking actions
- octoacme-roles-and-personas.md — role summaries and responsibilities

Contributing
- To propose additions or edits to these process docs, open a process doc update using .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml. Include a summary, rationale, and suggested content. That issue workflow helps ensure stakeholder review and traceability.
