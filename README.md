# learnable-dev-skill

## English Version

A reusable Codex skill for AI-assisted development that helps you maintain project control while preserving technical understanding and safe working habits. Instead of leaving behind only code, it supports a workflow that also produces explainable decisions and learnable implementations.

### What It Helps Preserve

- project control
- decision records
- safety and risk review
- tech-note learning habits
- optional Obsidian companion notes

### What It Does

This skill helps the agent avoid fragile vibe-coded changes by nudging it to:

- identify the affected project area before implementation
- check whether a change crosses a decision-record threshold
- leave Mimir-style records for important changes
- keep a short technical note after meaningful work
- report validation and remaining risk clearly

### Repository Layout

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

### Install

If your Codex setup supports installing skills from a GitHub repo path, point it at this repository and install the `learnable-dev` skill folder.

### Notes

- The skill is intentionally lightweight.
- It does not hard-code one repository layout, but it encourages using:
  - `docs/` for design and planning docs
  - `.ai/records` for canonical decision records
  - `docs/records` for Obsidian companion notes when needed

## 한국어 버전

AI 보조 개발 과정에서 프로젝트 통제권을 유지하고, 기술적 이해와 안전한 작업 습관이 남도록 돕는 재사용 가능한 Codex 스킬입니다. 코드만 남기는 개발이 아니라, 설명 가능한 결정과 학습 가능한 구현이 함께 쌓이도록 돕습니다.

### 무엇을 지켜주나

- 프로젝트 통제권
- 결정 기록
- 안전성과 리스크 점검
- 기술 노트 기반 학습 습관
- 필요 시 Obsidian companion note

### 어떤 일을 하나

이 스킬은 에이전트가 취약한 바이브 코딩으로 흐르지 않도록 아래 흐름을 유도합니다.

- 구현 전에 어떤 프로젝트 파트를 건드리는지 먼저 확인하기
- 변경이 decision record 기준을 넘는지 판단하기
- 중요한 변경에는 Mimir 스타일 기록 남기기
- 기능이 끝난 뒤 짧은 기술 노트 남기기
- 검증 결과와 남은 리스크를 명확히 정리하기

### 저장소 구조

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

### 설치

Codex 환경에서 GitHub repo 경로 기반 설치를 지원한다면, 이 저장소를 가리켜 `learnable-dev` 스킬 폴더를 설치하면 됩니다.

### 참고

- 이 스킬은 의도적으로 가볍게 설계되었습니다.
- 하나의 저장소 구조를 강제하지는 않지만, 아래 같은 구성을 권장합니다.
  - `docs/`: 설계와 계획 문서
  - `.ai/records`: canonical decision record
  - `docs/records`: Obsidian companion note
