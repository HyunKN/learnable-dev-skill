# learnable-dev-skill

A reusable Codex skill for AI-assisted development that helps you maintain project control while preserving technical understanding and safe working habits. Instead of leaving behind only code, it supports a workflow that also produces explainable decisions and learnable implementations.

## 한국어 설명

AI 보조 개발 과정에서 프로젝트 통제권을 유지하고, 기술적 이해와 안전한 작업 습관이 남도록 돕는 재사용 가능한 Codex 스킬입니다. 코드만 남기는 개발이 아니라, 설명 가능한 결정과 학습 가능한 구현이 함께 쌓이도록 돕습니다.

이 스킬은 다음과 같은 개발 흐름을 지원합니다.

- 중요한 기능 작업 전 리스크와 변경 범위 점검
- 큰 결정이 생겼을 때 Mimir 스타일 결정 기록 남기기
- 기능이 끝난 뒤 짧은 기술 노트 남기기
- 검증 결과와 남은 리스크를 함께 정리하기

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
