# learnable-dev-skill

A reusable Codex skill for AI-assisted development that helps you maintain project control while preserving technical understanding and safe working habits. Instead of leaving behind only code, it supports a workflow that also produces explainable decisions and learnable implementations.

## What It Helps Preserve

- project control
- decision records
- safety/risk review
- tech-note learning habits
- optional Obsidian companion notes

## What It Does

This skill helps the agent avoid fragile vibe-coded changes by nudging it to:

- identify the affected project area before implementation
- check whether a change crosses a decision-record threshold
- leave Mimir-style records for important changes
- keep a short technical note after meaningful work
- report validation and remaining risk clearly

## Repository Layout

```text
learnable-dev/
  SKILL.md
  agents/
    openai.yaml
  references/
    learning-playbook.md
    risk-checklist.md
    tech-note-template.md
    record-thresholds.md
```

## Install

If your Codex setup supports installing skills from a GitHub repo path, point it at this repository and install the `learnable-dev` skill folder.

## Notes

- The skill is intentionally lightweight.
- It does not hard-code one repository layout, but it encourages using:
  - `docs/` for design and planning docs
  - `.ai/records` for canonical decision records
  - `docs/records` for Obsidian companion notes when needed
