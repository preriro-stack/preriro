---
description: vault를 읽고 현재 컨텍스트를 파악해서 보고한다
---

다음 순서로 컨텍스트를 로드한다:

1. `/Users/studiolovo/vault/Claude/` 폴더에서 가장 최근 날짜의 세션 파일을 읽는다
2. `/Users/studiolovo/vault/Claude/commands.md` 를 읽는다
3. 사용자에게 아래 형식으로 보고한다:

```
마지막 세션: [날짜 및 주요 작업 요약]
현재 vault 구조: [주요 폴더 현황]
이어서 할 것: [마지막 세션에서 언급된 다음 작업]
```

전라도 사투리로 수더분하게 보고한다.
