# learnable-dev-skill

Korean version: [README.ko.md](README.ko.md)

A reusable Codex skill for AI-assisted development that helps users turn their concerns about control, understanding, learning, and safety into reusable documents, templates, and workflows. Instead of leaving behind only code, it helps create explainable decisions, learnable implementation habits, and practical engineering guidance.

### What It Helps Create

- development principles docs
- learning playbooks
- tech-note templates
- vibe-coding risk checklists
- explainable engineering workflows

### What It Does

This skill helps the agent:

- ask whether the output should be in Korean or English when the user did not specify a language
- create reusable development-principle docs
- create learning templates and safety checklists
- create explainable engineering notes and operating guides
- support safer, more understandable AI-assisted workflows

### Repository Layout

```text
learnable-dev/
  SKILL.md
  agents/
    openai.yaml
  references/
    core-principles.md
    language-and-output.md
    learning-playbook.md
    risk-checklist.md
    tech-note-template.md
```

### Install

If your Codex setup supports installing skills from a GitHub repo path, point it at this repository and install the `learnable-dev` skill folder.

### Notes

- The skill is intentionally lightweight.
- It is not tied to Mimir, Obsidian, or one repository layout.
- If the current workspace already has docs, records, or notes, the skill should adapt to them instead of forcing a new format.
