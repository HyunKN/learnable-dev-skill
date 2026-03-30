# learnable-dev-skill

[English](README.md) | 한국어

AI 보조 개발 과정에서 프로젝트 통제권, 기술적 이해, 학습, 안전성에 대한 고민을 재사용 가능한 문서, 템플릿, 운영 원칙으로 바꾸도록 돕는 Codex 스킬입니다. 코드만 남기는 개발이 아니라, 설명 가능한 결정과 학습 가능한 구현 습관, 실전적인 엔지니어링 가이드를 남길 수 있게 해줍니다.

## 무엇을 만들어주나

- 개발 원칙 문서
- 학습 플레이북
- 채팅 인사이트 기록 가이드
- 기술 결정 학습 노트 템플릿
- 바이브 코딩 리스크 체크리스트
- 설명 가능한 엔지니어링 워크플로

## 어떤 일을 하나

이 스킬은 에이전트가 다음을 하도록 돕습니다.

- 언어가 정해지지 않았다면 먼저 한국어/영문 중 무엇으로 만들지 물어보기
- 재사용 가능한 개발 원칙 문서 만들기
- 대화에서 나온 재사용 가능한 인사이트를 프로젝트 지식으로 남기기
- 학습 템플릿과 안전성 체크리스트 만들기
- 설명 가능한 엔지니어링 노트와 운영 가이드 만들기
- AI를 더 안전하고 이해 가능하게 쓰는 워크플로를 지원하기

## 저장소 구조

```text
learnable-dev/
  SKILL.md
  agents/
    openai.yaml
  references/
    principles-project-control-and-explainable-ai-use.md
    guide-language-selection-and-reusable-output.md
    guide-chat-insight-capture.md
    playbook-learning-while-building.md
    checklist-ai-assisted-development-risks.md
    template-tech-decision-study-note.md
```

## 제목 규칙

`references/` 아래의 재사용 참고문서는 날짜보다 역할이 먼저 보이도록 이름을 짓는 편이 좋습니다.

- 원칙 문서: `principles-...`
- 사용 가이드: `guide-...`
- 학습 문서: `playbook-...`
- 체크리스트: `checklist-...`
- 템플릿: `template-...`

실제 프로젝트에서 남기는 기록 문서는 날짜와 결정 주제가 바로 보이도록 분리하는 편이 좋습니다.

- 결정 기록: `decision-YYYY-MM-DD-what-was-decided.md`
- 인사이트 기록: `insight-YYYY-MM-DD-what-became-clear.md`
- 학습 노트: `tech-note-YYYY-MM-DD-what-we-learned.md`

예시:

- `decision-2026-03-30-adopt-react-query.md`
- `insight-2026-03-30-document-title-clarity.md`
- `tech-note-2026-03-30-why-we-chose-react-query.md`

## 설치

Codex 환경에서 GitHub repo 경로 기반 설치를 지원한다면, 이 저장소를 가리켜 `learnable-dev` 스킬 폴더를 설치하면 됩니다.

## 참고

- 이 스킬은 의도적으로 가볍게 설계되었습니다.
- Mimir, Obsidian, 특정 저장소 구조에 묶이지 않습니다.
- 현재 워크스페이스에 이미 문서 구조가 있다면 그 구조에 맞춰 적응하는 방식으로 쓰는 것을 전제로 합니다.
