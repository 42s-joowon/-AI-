# 원본 로그 (편집 없음)

정리된 문서(01~03)와 별개로, 재현성을 위해 **모델 응답 원문을 그대로** 여기에 저장한다.

| 파일명 | 내용 |
|---|---|
| `01_compare_chatgpt.md` | 01 보고서 §2 입력 + T1~T3 응답 원문 (ChatGPT) |
| `01_compare_claude.md` | 같은 내용 (Claude) |
| `01_compare_gemini.md` | 같은 내용 (Gemini) |
| `02_reasoning_v1.md` / `02_reasoning_v2.md` | 02 문서 §9 v1/v2 응답 원문 |
| `02_hallucination_{모델}.md` | 02 문서 §10 H1~H8 응답 원문 |
| `03_dialogue_raw.md` | 03 실행 로그 대화 전문 |

각 파일 맨 위에 다음 헤더를 붙인다.

```
- 모델명: (UI 표시 이름)
- 요금제: 무료 / 유료
- 채널: 웹 / 앱 / API
- 날짜: YYYY-MM-DD
- 설정: 웹 기본값 (API라면 temperature / top_p / max_tokens)
- 대화 공유 링크(있으면):
```

저장 방법: 웹 UI의 "복사" 버튼으로 응답을 복사해 붙여넣거나, 대화 공유 링크를 함께 남긴다. 개인정보(실명, 연락처, 계정)가 섞였다면 `[역할명]`, `[삭제]`로 가린 뒤 저장한다.
