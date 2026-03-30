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
   - tech-decision study note template
   - chat insight capture guide
   - risk checklist
   - operating guide
   - role split / ownership guide
3. Prefer creating lightweight, reusable docs over one-off chat answers.
4. When the conversation reveals a reusable explanation, decision criterion, or working pattern, capture it in an existing document or a new note.
5. Keep the guidance practical and repeatable.
6. Choose filenames that reveal the document role at a glance.
7. For project-specific decision, study, or insight notes, include the date and topic in the filename.
8. If the repository already uses docs, records, or Obsidian notes, adapt to that structure instead of forcing a new one.

## Default Workflow

1. Clarify the target document type and language.
2. Read `references/principles-project-control-and-explainable-ai-use.md`.
3. Read only the extra reference files needed for the requested output.
4. If a meaningful chat insight appears, decide whether to update an existing document or create a new one.
5. Draft the document in a reusable form:
   - concise principles
   - checklist
   - template
   - operating loop
6. Make the output usable immediately in a real project.

## What This Skill Should Help Create

- AI-assisted development principles
- project operating rules
- skill-growth playbooks
- interview-level understanding prompts
- chat-derived project knowledge docs
- tech-decision study note templates
- vibe-coding risk checklists
- implementation review checklists
- ownership / human-vs-AI responsibility guides

## Guardrails

- Do not assume Mimir, Obsidian, or any specific system unless the repository already uses it.
- Do not turn every request into a heavy process document.
- Do not record every chat by default; only capture reusable insights.
- Do not produce abstract philosophy without concrete workflow.
- Do not optimize for speed alone when the user is asking for understanding and control.
- Do not leave the user with only advice when a reusable template or document would help more.

## Load References As Needed

- Read `references/principles-project-control-and-explainable-ai-use.md` for the main philosophy behind project control, explainability, and learning while building.
- Read `references/guide-language-selection-and-reusable-output.md` when deciding how to ask about Korean vs English and how to shape the output.
- Read `references/playbook-learning-while-building.md` when the user wants skill growth and understanding-oriented workflows.
- Read `references/guide-chat-insight-capture.md` when the user wants reusable ways to preserve valuable chat insights as project knowledge.
- Read `references/checklist-ai-assisted-development-risks.md` when the user wants safety, security, and vibe-coding risk guidance.
- Read `references/template-tech-decision-study-note.md` when the user wants reusable feature-level technical decision note formats.
