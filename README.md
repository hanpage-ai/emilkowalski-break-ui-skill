# emilkowalski-break-ui-skill

> 최악의 데이터로 UI를 깨뜨리고, 어디서 깨지는지 코드로 짚는 스킬

데모 데이터로는 완벽해 보이는 UI, 막상 실제 사용자가 접속하면 어긋나고 찌그러질 때,
이 스킬은 **worst-case 데이터 + 깨진 항목 + 수정 코드**를 알려줍니다.

## 이 스킬의 역할

- 긴 이름, 깨지지 않는 이메일, 빈 필드, 이모지, 비라틴 문자 등 worst-case 데이터 생성
- `overflow-wrap`, `flex-shrink`, `min-width`, `Intl.PluralRules` 누락으로 깨진 UI 진단
- Severity(Broken/Ugly/Fragile)로 등급 매기고, 수정 코드를 그 자리에서 제시

## 누가 쓰면 좋은지

- **실제 사용자 데이터를 예상하지 못한 개발자**: 데모에서는 멀쩡했는데 프로덕션에서 어긋날 때
- **다양한 로케일·스크린을 지원하는 개발자**: 긴 이름, 1글자 이름, 이모지, RTL 등 edge case 대응
- **UI 리뷰를 코드 수준으로 받고 싶은 분**: 어떤 속성이 부족해서 깨지는지 라인 단위로 짚고 싶을 때

## 사용법

1. `SKILL.md` 열기 (아래)
2. AI 에이전트(Claude Code, Cursor 등)에 붙여넣기

## 원문

[SKILL.md](SKILL.md)

## 원본 출처

- **URL**: [emilkowalski/skills](https://github.com/emilkowalski/skills/tree/main/skills/break-ui)
