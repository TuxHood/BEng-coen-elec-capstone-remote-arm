# Development planning

## Proposed GitHub Project

Create one project named **Team 26 — Development Board**, link it to this repository, and add the six team members with appropriate access. No live board or milestones are created by this repository change. Replace the Projects listing link in the main README with the actual board URL once configured.

| Status | Meaning |
| --- | --- |
| Backlog | Captured; scope or priority still needs review |
| Ready | Owner, dependencies, and acceptance criteria are clear; work can begin |
| In Progress | Owner is actively working on the task |
| In Review | Deliverable and evidence await review |
| Blocked | A named dependency prevents progress; record the next action |
| Done | Acceptance criteria met and supporting evidence linked |

Use issue assignees for responsibility, a target-date field for scheduling, and a subsystem field (`Control glove`, `Robotic arm`, `Operator software`, `Hardware / PCB`, `Integration / safety`, `Documentation / planning`). Add start/target dates to a Roadmap view and record blocking issue links explicitly. Configure a board grouped by Status and a table filtered by subsystem or assignee.

Create four repository milestones after verifying the capstone's phase names, deliverables, and dates. The supplied summary identifies four phases without enough information to name or schedule all of them reliably.

## Importing proposal tasks

1. Obtain the submitted Phase 1 proposal and verify its version.
2. Copy the complete task breakdown with existing IDs, wording, dependencies, and owners. Do not infer assignments or completion states from examples.
3. Search existing issues by task ID before creating anything to avoid duplicates.
4. Use the task issue form, add verified source links, and define acceptance criteria. Leave unknown dates unscheduled and owners unassigned.
5. Add issues to the board and confirmed phase milestones; set statuses from actual team progress.

These examples appear in the pasted summary and are **unverified import candidates**, not the complete proposal task list or live issues:

| Reported task ID | Reported description | Verification |
| --- | --- | --- |
| ARM-D1 | CAD modelling | Check against proposal |
| ARM-D4 | Safety design | Check against proposal |
| SW-D1 | Software design | Check against proposal |
| SW-D2 | Development planning | Check against proposal |
| GLOVE-D1 | Sensor layout | Check against proposal |
| GLOVE-D3 | Component selection | Check against proposal |

Create review tasks for the budget, finger-feedback scope, and communication-loss questions in [requirements.md](requirements.md) after checking their sources. This documentation change does not import or assign tasks.
