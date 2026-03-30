# learnable-dev-skill

English | [한국어](README.ko.md)

A reusable Codex skill for AI-assisted development that helps users turn their concerns about control, understanding, learning, and safety into reusable documents, templates, and workflows. Instead of leaving behind only code, it helps create explainable decisions, learnable implementation habits, and practical engineering guidance.

### What It Helps Create

- development principles docs
- learning playbooks
- tech-decision study note templates
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
    principles-project-control-and-explainable-ai-use.md
    guide-language-selection-and-reusable-output.md
    playbook-learning-while-building.md
    checklist-ai-assisted-development-risks.md
    template-tech-decision-study-note.md
```

### Naming Pattern

For reusable reference docs under `references/`, prefer names that show the document role before anything else.

- principles docs: `principles-...`
- usage guides: `guide-...`
- learning docs: `playbook-...`
- checklists: `checklist-...`
- templates: `template-...`

For project-specific records, prefer names that immediately show when the decision happened and what it was about.

- decision records: `decision-YYYY-MM-DD-what-was-decided.md`
- study notes: `tech-note-YYYY-MM-DD-what-we-learned.md`

Examples:

- `decision-2026-03-30-adopt-react-query.md`
- `tech-note-2026-03-30-why-we-chose-react-query.md`

### Install

If your Codex setup supports installing skills from a GitHub repo path, point it at this repository and install the `learnable-dev` skill folder.

### Notes

- The skill is intentionally lightweight.
- It is not tied to Mimir, Obsidian, or one repository layout.
- If the current workspace already has docs, records, or notes, the skill should adapt to them instead of forcing a new format.
