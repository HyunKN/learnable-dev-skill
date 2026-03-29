---
name: learnable-dev
description: Use when the user wants help creating or maintaining development-principle docs, learning templates, safety checklists, explainable engineering notes, or AI-assisted development workflows that preserve project control, technical understanding, and safe habits. Trigger especially when the work should produce reusable documents, templates, or guidance rather than code alone.
---

# learnable-dev

Use this skill when the user wants help turning AI-assisted development concerns into durable documents, templates, and workflows.

This skill is not tied to one record format or one repository style. Its main purpose is to help the user:

- keep project control while using AI
- learn while building instead of only shipping code
- create explainable engineering docs and templates
- reduce vibe-coding and safety risks
- leave behind reusable development habits

## Core Behavior

When the task is about creating principles, workflows, templates, or reusable engineering guidance:

1. If the user did not specify language, ask first whether they want Korean or English.
2. Identify the output type:
   - development principles doc
   - learning playbook
   - tech note template
   - risk checklist
   - operating guide
   - role split / ownership guide
3. Prefer creating lightweight, reusable docs over one-off chat answers.
4. Keep the guidance practical and repeatable.
5. If the repository already uses docs, records, or Obsidian notes, adapt to that structure instead of forcing a new one.

## Default Workflow

1. Clarify the target document type and language.
2. Read `references/core-principles.md`.
3. Read only the extra reference files needed for the requested output.
4. Draft the document in a reusable form:
   - concise principles
   - checklist
   - template
   - operating loop
5. Make the output usable immediately in a real project.

## What This Skill Should Help Create

- AI-assisted development principles
- project operating rules
- skill-growth playbooks
- interview-level understanding prompts
- technical note templates
- vibe-coding risk checklists
- implementation review checklists
- ownership / human-vs-AI responsibility guides

## Guardrails

- Do not assume Mimir, Obsidian, or any specific system unless the repository already uses it.
- Do not turn every request into a heavy process document.
- Do not produce abstract philosophy without concrete workflow.
- Do not optimize for speed alone when the user is asking for understanding and control.
- Do not leave the user with only advice when a reusable template or document would help more.

## Load References As Needed

- Read `references/core-principles.md` for the main philosophy behind project control, explainability, and learning while building.
- Read `references/language-and-output.md` when deciding how to ask about Korean vs English and how to shape the output.
- Read `references/learning-playbook.md` when the user wants skill growth and understanding-oriented workflows.
- Read `references/risk-checklist.md` when the user wants safety, security, and vibe-coding risk guidance.
- Read `references/tech-note-template.md` when the user wants reusable feature-level technical note formats.
