# Project Foundation Implementation Plan

> **For agentic workers:** Use superpowers:executing-plans to implement this documentation setup task-by-task. Steps use checkbox syntax for tracking.

**Goal:** Apply the supplied repository structure as a reviewable branch and pull request.

**Architecture:** GitHub holds source, task templates, decisions, and evidence. Google Drive remains the editable-document source. Subsystem directories contain guidance until implementation begins.

**Tech Stack:** Markdown, Mermaid, GitHub YAML forms, Git ignore rules. No runtime dependencies.

**Spec:** User-supplied repository setup proposal, reflected in README.md and docs/planning.md.

## Global constraints

- Keep reported design details proposed until verified against original reports.
- Do not invent Drive URLs, owners, due dates, phase names, or progress.
- Preserve manually maintained Makefiles and Go module manifests.
- Create a separate branch and pull request; leave merging to the team.

## Review focus

Check relative links, required issue fields, directory coverage, generated-versus-source ignore rules, and proposed planning versus live GitHub configuration.

## Task 1: Documentation and workflow

- [ ] Expand README.md and add CONTRIBUTING.md.
- [ ] Add document index, requirements, planning, architecture, and decision guidance/template.
- [ ] Add task, bug, and test-case issue forms and a pull request template.
- [ ] Verify local document links and parse YAML forms; inspect required fields.

## Task 2: Development folders and ignore rules

- [ ] Add guidance for firmware, operator software cmd/internal/web, hardware/PCB/BOM, and integration/performance/safety tests.
- [ ] Extend .gitignore for Go, ESP32, Python, and KiCad; remove blanket Makefile and *.mod exclusions.
- [ ] Check ignored artifacts and visible source/manifests with git check-ignore; run git diff --check.

## Task 3: Review and delivery

- [ ] Review the full change against the supplied structure and correct gaps.
- [ ] Commit verified contents to the setup branch and open a pull request against main.
- [ ] Verify remote branch and pull request; report pending Drive links and live board/task import separately.
