---
name: learnable-dev
description: Use when doing meaningful AI-assisted software development that should preserve project control, technical understanding, safe working habits, explainable decisions, and learnable implementation notes. Trigger for architecture changes, schema or pipeline changes, security-sensitive work, or any feature work that should leave behind durable technical understanding instead of code alone.
---

# learnable-dev

Use this skill when the work should leave behind not just code, but also understanding, safety checks, and a durable decision trail.

## Core Goals

- Keep project control with the human, not the model.
- Avoid fragile vibe-coded changes that are hard to explain later.
- Leave technical understanding behind after meaningful work.
- Record important decisions in a canonical format.
- Keep Obsidian-friendly notes updated when the project uses Obsidian.

## Workflow

1. Before implementation, identify the affected project area in the workspace docs if they exist.
2. For meaningful work, read:
   - `references/learning-playbook.md`
   - `references/risk-checklist.md`
3. Decide whether the task crosses a decision-record threshold.
4. If the threshold is crossed:
   - create or update a canonical decision record
   - render a readable summary when useful
   - create an Obsidian-friendly companion note when the workspace uses Obsidian
5. After meaningful implementation, leave a short technical note using `references/tech-note-template.md`.
6. Report validation clearly:
   - what was tested
   - what was not tested
   - what still looks risky

## Repository Hints

When the current repository already uses these paths, prefer them:

- `docs/` for design and planning
- `.ai/records/decisions` for canonical decision records
- `.ai/records/reports` for readable summaries
- `docs/records` for Obsidian companion notes
- `docs/learning` for learning notes and templates

If these paths do not exist, adapt to the repository instead of forcing them.

## Guardrails

- Do not treat AI output as correct until you can explain it.
- Do not add dependencies without stating why they are needed.
- Do not change critical flows without checking the risk checklist.
- Do not leave major decisions only in chat context.
- Do not hide incomplete validation.

## Load References As Needed

- Read `references/record-thresholds.md` when deciding whether a change deserves a canonical record.
- Read `references/learning-playbook.md` when the user wants skill growth, clearer understanding, or reusable technical learning.
- Read `references/risk-checklist.md` before high-impact AI-assisted changes.
- Read `references/tech-note-template.md` when leaving behind a short learning note after meaningful work.
