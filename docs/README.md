# OctoAcme Project Management Docs

This README indexes OctoAcme's project management process documents and provides a short summary of our practices to help team members find the right guidance quickly.

Overview

OctoAcme runs projects with a lightweight, repeatable lifecycle that moves from Initiation (one-pager, stakeholder alignment) to Planning (backlog, estimates, Definition of Done), through Execution (build, test, review) and Release, then Close & Retrospective. Planning artifacts — including a Project One-pager, prioritized backlog, release plan, and a risk register — help ensure work proceeds with clear success metrics and stakeholder alignment.

Day-to-day delivery uses an explicit workflow backed by a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request process (keep PRs small, include issue links and acceptance criteria, run CI and security scans, and require reviews before merging). Sprint planning is timeboxed, items must meet the Definition of Done, and estimates are used to manage capacity and releases.

Roles and communication are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, risks, and stakeholder communication; Developers implement and maintain quality; QA validates acceptance criteria; and Stakeholders provide inputs and approvals. Team cadence includes daily standups, weekly delivery syncs, demos at the end of sprints/milestones, and regular retrospectives. Risks are tracked in a simple Risk Register and escalated along a tiered path (team → PM → Product Lead → Sponsor).

Quality and release practices emphasize automated and manual checks: unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Releases follow a checklist with pre-release requirements, staging verification, automated production pipelines where possible, post-deploy verifications, and a rollback/incident playbook. Retrospectives capture learnings as tracked action items that feed back into the backlog.

Docs (click to open):
- docs/octoacme-project-management-overview.md — Overview, principles, roles, and key artifacts
- docs/octoacme-project-initiation.md — Project initiation guide and one-pager template
- docs/octoacme-project-planning.md — Planning activities, backlog and sprint planning
- docs/octoacme-execution-and-tracking.md — Day-to-day execution, workflows, and checklists
- docs/octoacme-risks-and-communication.md — Risk register, communication templates, and escalation paths
- docs/octoacme-release-and-deployment.md — Release types, deployment checklist, and rollback playbook
- docs/octoacme-retrospective-and-continuous-improvement.md — Retrospective structure and tracking improvements
- docs/octoacme-roles-and-personas.md — Role summaries and responsibilities

How to use and update these docs

- Add or update process documents in the docs/ folder. Keep the README in sync when adding, renaming, or removing files.
- To propose content changes, file an issue using the "Add Content to Project Management Process Docs" template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). Include a summary, rationale, suggested content, and acceptance criteria.
- When ready, create a pull request that references the originating issue (use "Closes #<issue-number>" in the PR description to auto-close the issue on merge).

Contact

For questions about these processes or this README, mention @vikas-kesharwani on the issue or PR.
