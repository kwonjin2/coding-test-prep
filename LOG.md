# Learning Log

> 운영 규칙은 [README.md](./README.md) 참조.
> 새 대화 시작 시 이 파일 + 최근 1~2일치 `daily/*.md` 를 함께 첨부.

---

### Upcoming Retries

> Claude 가 세션 시작 시 이 섹션을 **먼저** 확인. 비어있으면 오늘 retry 없음.
> 운영: 신규 풀이 시 추가 / retry 성공 (🟢🔵) 시 제거 / 부분·실패 (🟡🟠🔴) 시 새 날짜로 업데이트.

- 2026-06-08 (월) — 🟡 LC #242 Valid Anagram (자료구조/알고리즘 대안 자력 도출 + 복잡도 trade-off 자력 정리) → [daily/2026-06-01.md](./daily/2026-06-01.md)
- 2026-06-03 (수) — 🟡 BFE #5 debounce (think-aloud → 코드 변환 + BFE Run 자기검증 사이클 자력 시험) → [daily/2026-05-27.md](./daily/2026-05-27.md)
- 2026-06-04 (목) — 🟢 LC #20 Valid Parentheses (closer→opener 매핑 자력 소환 시험) → [daily/2026-05-28.md](./daily/2026-05-28.md)
- 2026-07-14 (화) — 🟡 LC #167 Two Sum II (좌우 포인터 이동 조건 자력 소환 시험) → [daily/2026-07-07.md](./daily/2026-07-07.md)

---

### Pattern Coverage

> 누적 풀이 횟수. Claude 가 daily 의 `Tags` 기준으로 매 세션 끝날 때 업데이트.
> **0회 / 저빈도 유형이 다음 문제 선정 시 우선 후보.**

#### Algorithm

| 유형     | 횟수 | 마지막 풀이 | 최근 Status |
| -------- | ---- | ----------- | ----------- |
| 문자열   | 2    | 2026-06-01  | 🟡          |
| 배열     | 4    | 2026-07-07  | 🟡          |
| 스택     | 1    | 2026-05-28  | 🟢          |
| 투포인터 | 1    | 2026-07-07  | 🟡          |
| 해시     | 5    | 2026-06-01  | 🟡          |

#### Frontend Live

| 유형              | 횟수 | 마지막 풀이 | 최근 Status |
| ----------------- | ---- | ----------- | ----------- |
| HOF               | 1    | 2026-05-27  | 🟡          |
| closure           | 1    | 2026-05-27  | 🟡          |
| debounce-throttle | 1    | 2026-05-27  | 🟡          |

---

### Daily

| Date            | Algo        | FE Live     | Detail                                       |
| --------------- | ----------- | ----------- | -------------------------------------------- |
| 2026-05-22 (금) | 🟡 Two Sum / Map 최적화 못 떠올림 | - | [daily/2026-05-22.md](./daily/2026-05-22.md) |
| 2026-05-25 (월) | 🟡 Valid Anagram / Map 자력 ✅, 배열 26 최적화에서 막힘 | - | [daily/2026-05-25.md](./daily/2026-05-25.md) |
| 2026-05-26 (화) | 🟢 Contains Duplicate / Set 자력 ✅, early exit·복잡도 worst case 코칭 | - | [daily/2026-05-26.md](./daily/2026-05-26.md) |
| 2026-05-27 (수) | - | 🟡 BFE #5 debounce / think-aloud → 코드 변환 갭, BFE Run 자기검증 누락 | [daily/2026-05-27.md](./daily/2026-05-27.md) |
| 2026-05-28 (목) | 🟢 Valid Parentheses / 스택 자력 ✅, 표준 closer→opener 매핑 미인지 + 엣지케이스 think-aloud 빈약 | - | [daily/2026-05-28.md](./daily/2026-05-28.md) |
| 2026-05-29 (금) | 🟢 Two Sum **retry** / Map 자력 + has→set trace 자력 ✅ (단 retry 시험은 키워드 노출로 무효), think-aloud 무의식 누락 3연속 | - | [daily/2026-05-29.md](./daily/2026-05-29.md) |
| 2026-06-01 (월) | 🟡 Valid Anagram **retry** / 풀이 자력 ✅, 대안 자료구조/알고리즘 자력 X (배열26·정렬 둘 다 힌트), 가정↔복잡도 자문 누락 | - | [daily/2026-06-01.md](./daily/2026-06-01.md) |
| 2026-07-07 (화) | 🟡 Two Sum II / 브루트포스 먼저, 정렬 단서 미활용 짚은 후 좌우 포인터 이동 조건 자력 도출 (5주 공백 후 재개, 투포인터 첫 시작) | - | [daily/2026-07-07.md](./daily/2026-07-07.md) |

---

## 작성 형식 (참고)

```
| 2026-05-22 (금) | 🟡 BFS 막힘 | 🟢 debounce | [daily/2026-05-22.md] |
```

- Algo / FE Live 열에는 **Status 이모지 + 핵심 키워드 1~2개**
- 막힌 지점이 있으면 그걸 우선 표기 ("BFS 막힘"이 "BFS 풀음"보다 정보량 큼)
- Detail은 일별 파일 링크
