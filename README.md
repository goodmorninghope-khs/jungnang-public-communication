# 맛있는 커뮤니케이션 · jungnang-public-communication

이슈나 정책 하나를 넣으면 공공커뮤니케이션 기획안을 만드는 Claude 스킬입니다. 김현성의 커뮤니케이션 전략수립 모래시계 모델로 넓게 조사하고, 한 문장으로 좁히고, 다섯 수단 가운데 무엇으로 할지 고른 뒤, 다시 넓게 펼칩니다. 단계마다 ROI(Relevance·Originality·Impact) 점검 틀로 거릅니다.

## 흐름

```
 ▽ 넓게   1단계 조사·환경분석   3C(Company·Condition·Consumer) + 경험격차 4관문
             ── ROI 관문 ① 이슈 판독: 공(攻)인가 수(守)인가
   ╳ 좁게  허리 · 컨셉           뜻 + 양념 + 컨셉 한 문장
          수단 선택              BRANDING · ISSUE FIGHTING · CAMPAIGN · STORYTELLING · COMMUNITY(NETWORKING)
             ── ROI 관문 ② 컨셉·수단 간보기
 △ 넓게   2단계 전략 수립         재료(Contents·Channel·Community+Agenda·Authority) · 도구 · Crisis
          3단계 실행 프로그램      단계별·이슈별·위기 대응·사후관리
             ── ROI 관문 ③ 실행 검증: 노출이 아니라 수용과 이용
```

결과물은 세 가지입니다. 기획안, 주민에게 건넬 첫 문장(BEFORE/AFTER), 담당자가 바뀌어도 같은 맛이 나도록 남기는 레시피 카드 한 장.

## 파일 구성

| 파일 | 내용 |
|---|---|
| `SKILL.md` | 스킬 본문: 흐름, 단계별 작업, 화자·공공성 기준 |
| `references/hourglass.md` | 모래시계 모델 원형(2019)과 단계별 작업표, 걸음 예시 |
| `references/menus.md` | 다섯 수단 플레이북과 수단별 ROI 비교표 |
| `references/roi.md` | ROI 점검 틀, 관문 세 개, 채점 기준, 위기 대응 |
| `references/recipe.md` | 경험격차, 3C2A 재료, 다섯 양념, 도구 |
| `references/listening.md` | 경청 8원칙과 청책 7단계(듣는 조사) |
| `references/plain-sentences.md` | 친절한 중랑씨: 친절은 다음 행동이 보이는 상태 |
| `references/cases.md` | 사례 창고: 수단·양념별 사례와 출처·쪽수 |
| `assets/plan-template.md` | 기획안 양식 |
| `assets/recipe-card.md` | 레시피 카드 양식 |
| `agents/openai.yaml` | 다른 도구용 표시 이름과 호출 안내 |
| `examples/` | 적용 예시: 망우역사문화공원 커뮤니케이션 기획안(내부 검토용 초안) |

## 설치

- Claude(claude.ai): 이 폴더를 zip으로 묶어 설정 → 기능 → 스킬에서 업로드합니다.
- Claude Code: 이 폴더를 `~/.claude/skills/jungnang-public-communication/`에 둡니다.

요청 예시: "이 정책의 커뮤니케이션 기획안을 모래시계 모델과 ROI 관문으로 만들어 주세요. 대상은 ○○, 기한은 ○○입니다."

## 근거 자료

김현성, 「디지털커뮤니케이션」 강의안(2019) · 『72년생 김현성의 물음』 원고 · 「맛있는 커뮤니케이션에는 레시피가 있다」 특강(2026. 10. 1. / 10. 15.) · 2017 amStory 인터뷰 원고 · 박원순, 『경청』(휴먼큐브, 2014). 출처별로 읽은 범위는 `references/cases.md`에 적었습니다.

## 쓸 때 주의

- 실제 없는 성과·주민 반응·발언을 만들지 않습니다. 검토 단계의 구상은 [제안]으로 표시하고 확정된 성과처럼 쓰지 않습니다.
- 수치·연도는 쓰기 전에 최신 자료로 다시 확인합니다.
- 선거운동이나 정치 성향별 표적 설득에 쓰지 않습니다. 게시·발송은 기관 결재를 거친 뒤에만 합니다.
- `examples/`의 기획안은 내부 검토용 초안이며 중랑구의 공식 계획이 아닙니다.
