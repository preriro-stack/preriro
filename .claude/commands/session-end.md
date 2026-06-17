---
description: 세션 내용을 요약해서 vault에 볼팅하고 GitHub에 push한다
---

다음 순서로 세션을 마무리한다:

1. 오늘 대화에서 다룬 내용을 분석한다
2. 아래 OKF 형식으로 `/Users/studiolovo/vault/Claude/YYYY-MM-DD-[주제].md` 파일을 생성한다:

```markdown
---
type: Session
title: [세션 주제]
description: [한 줄 요약]
tags: [관련 태그들]
timestamp: [현재 시각]
---

# [세션 주제]

## 오늘 한 것
- 항목별 정리

## 결정된 것
- 중요한 결정 사항

## 다음에 할 것
- 이어서 진행할 작업

## 관련 파일
- 생성/수정된 파일 목록
```

3. 터미널에서 vault GitHub push 실행:
```bash
cd /Users/studiolovo/vault && git add . && git commit -m "session: [날짜] [주제] 세션 마무리" && git push
```

4. 사용자에게 마무리 보고한다.
