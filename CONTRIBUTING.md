# Contributing

Use GitHub for source code, tasks, reviews, and test evidence. Keep editable reports in Google Drive and maintain their links in [docs/README.md](docs/README.md).

## Task workflow

1. Open a task, bug, or test-case issue. Reuse a proposal task ID only after checking the original task table.
2. Record the subsystem, responsible person, target date (or explicitly unscheduled), related document, dependencies, and measurable acceptance criteria. Set the GitHub assignee and milestone when known.
3. Work on a descriptive branch such as `docs/document-index`, `feat/glove-calibration`, or `fix/arm-timeout`. Keep changes focused.
4. Open a pull request linked to the issue. Explain the change and provide verification evidence. Ask a teammate to review it before merging.
5. Close the issue when acceptance criteria are met and evidence is linked. Update the project status and relevant documentation.

The proposed board workflow is **Backlog → Ready → In Progress → In Review → Done**, with **Blocked** available when a dependency prevents progress. See the [planning guide](docs/planning.md) for status definitions.

## Documentation and decisions

- Add editable documents to the index; avoid repeated DOCX exports. Record submitted report dates and versions to preserve what was handed in.
- Use a [decision record](docs/decisions/template.md) for consequential choices. Mark proposals as proposed until the team accepts them.
- Give each confirmed requirement an ID, source/version reference, and verification method in [requirements.md](docs/requirements.md).
- Version source schematics, CAD, PCB layouts, and dependency manifests. Identify hardware revisions in test evidence.

## Verification

Run the build and checks documented by the affected subsystem. Until executable code exists, review Markdown links, Mermaid diagrams, issue forms, and ignore rules. Do not claim hardware verification from a simulation or documentation review.

Record the commit, hardware/firmware versions, procedure, expected and actual results, and logs for tests using the [test guide](tests/README.md). Changes affecting motion, gripping, limits, power, or communication loss must include reviewed safety requirements and a controlled verification procedure.

## Public repository hygiene

Do not commit credentials, Wi-Fi passwords, private correspondence, personal information, or restricted document exports. Check sharing permissions before adding document links. Commit reproducible source files and lockfiles; keep generated output and local configuration out of Git.
