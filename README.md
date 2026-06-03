# Scale institutional knowledge using Copilot Spaces

This repository contains sample OctoAcme project-management documentation for practicing how to use GitHub Copilot Spaces as a shared knowledge source.

## What this repository contains

The `docs/` directory documents a lightweight project delivery lifecycle:

- **Project management overview**: principles, core roles, artifacts, lifecycle, and communication cadence
- **Project initiation**: one-pager, stakeholder alignment, success metrics, and go/no-go decision gate
- **Project planning**: backlog creation, estimation, definition of done, release planning, and dependency tracking
- **Execution and tracking**: team rituals, project board workflow, PR expectations, testing, metrics, and escalations
- **Risk management and communication**: risk register structure, stakeholder updates, and escalation paths
- **Release and deployment**: release types, pre-release checks, deployment checklist, rollback, and release notes
- **Retrospective and continuous improvement**: retrospective format, action-item tracking, and improvement culture
- **Roles and personas**: responsibilities and goals for developers, product managers, and project managers

## Project management process summary

OctoAcme follows an iterative, cross-functional delivery process built around clear ownership and lightweight documentation.

1. **Initiate**
   - Define the business problem, goal, success metrics, stakeholders, initial milestones, and rough risks.
   - Use a one-pager to align on whether work should move forward.

2. **Plan**
   - Break approved work into backlog items with acceptance criteria and estimates.
   - Document the Definition of Done, dependencies, release milestones, and QA approach.

3. **Execute and track**
   - Use regular standups, weekly delivery syncs, and end-of-sprint demos.
   - Track work on a project board through stages like Backlog, Ready, In Progress, In Review, QA, and Done.
   - Keep PRs small, link them to issues, and require CI plus review before merge.

4. **Manage risks and communicate status**
   - Maintain a simple risk register with owner, impact, likelihood, mitigation, and status.
   - Share weekly or milestone-based updates using a single source of truth.
   - Escalate blockers through team, PM, product lead, and sponsor paths as needed.

5. **Release safely**
   - Verify acceptance criteria, CI, security scans, release notes, rollback plans, and smoke tests before release.
   - Validate in staging, deploy to production, and perform post-deploy checks and stakeholder communication.

6. **Learn and improve**
   - Run retrospectives after sprints, releases, milestones, and incidents.
   - Convert learnings into owned action items and review progress during PM syncs.

## How to use this repository with Copilot Spaces

### Add the repository as a Space source

1. Open **GitHub Copilot Spaces**.
2. Create a new Space or open an existing one.
3. Add this repository (`aganepol/skills-scale-institutional-knowledge-using-copilot-spaces-asa`) as a source.
4. Optionally add selected documents from `docs/` or process-specific guidance from `.copilot/` for more focused context.

### Suggested custom chat modes

Create custom chat modes in your Space to analyze the documentation from different perspectives:

- **Process Analyst**
  - Purpose: summarize the end-to-end delivery process, decision gates, and handoffs.
  - Example prompt: "Analyze the repository docs and explain the full OctoAcme project lifecycle, including key artifacts, meetings, and approvals."

- **Documentation Auditor**
  - Purpose: identify gaps, ambiguity, duplication, and outdated guidance.
  - Example prompt: "Review the documentation for missing process details, unclear ownership, inconsistent terminology, and opportunities to improve discoverability."

- **Project Ops Advisor**
  - Purpose: recommend operational improvements for planning, execution, risk management, and release readiness.
  - Example prompt: "Based on these docs, propose improvements to project tracking, communication cadence, escalation handling, and release discipline."

- **Persona Coach**
  - Purpose: tailor answers to developers, product managers, or project managers.
  - Example prompt: "Using the roles and personas doc, explain what a project manager should prepare at initiation, planning, execution, and retrospective stages."

## Documentation insights discovered

A few strong themes emerge from the documentation:

- The process is intentionally lightweight and designed for cross-functional collaboration.
- Ownership is explicit: PM and Product Lead responsibilities are clearly central.
- Documentation emphasizes measurable outcomes, acceptance criteria, and incremental delivery.
- Risks, communication, and retrospectives are treated as ongoing practices rather than one-time activities.
- The docs describe a solid operating model, but they would benefit from more templates and cross-links between documents for faster onboarding.

## Recommended next documentation improvements

If you continue this exercise, useful follow-up updates would be:

- add a single index page in `docs/` linking all process documents
- add sample templates for risk registers, status reports, and decision logs
- add a glossary for PM, PdM, DoD, and other terms
- add a contributor workflow section that links the delivery process to the repo’s actual branch and PR practices

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
