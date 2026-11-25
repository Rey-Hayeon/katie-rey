# CLAUDE.md — Katie 브랜드 작업 규칙

이 폴더는 Katie의 퍼스널 브랜드와 그 아래 라인(katie_from_korea, 꼬물상점, 성장기록 블로그)을 하나의 SSOT로 관리하는 저장소다. Katie는 판단하고, Claude는 함께 정리하고 만든다.

## 반드시 지킬 것

1. **작업 전에 [SSOT.md](SSOT.md)를 읽고, '문서 지도'에서 업무에 해당하는 [docs/ssot/](docs/ssot/) 파일을 모두 읽는다.** 애매하면 읽는다. 특히 '판단 기준'과 '에이전트(Claude)를 위한 규칙'은 매번 확인한다.
2. **SSOT와 충돌하는 작업은 하지 않는다.** 애매하면 만들지 말고 Katie에게 묻는다.
3. **사실은 Katie가 말한 것만 쓴다.** 추측, 해석, 제안은 [초안]으로 표시한다.
4. **결정이 생기면** SSOT 해당 문서(SSOT.md 또는 docs/ssot/)와 [결정 로그](docs/ssot/decision-log.md)를 함께 고친다. 질문과 답은 [docs/interviews/interview-log.md](docs/interviews/interview-log.md) 맨 위에 추가한다.
5. **Katie가 직접 쓴 글은 고치지 않는다.** [docs/interviews/katie-raw-answers.md](docs/interviews/katie-raw-answers.md)와 [docs/sources/](docs/sources/)는 원문 그대로 두고, 새 원문은 붙이기만 한다.
6. **결정되지 않은 아이디어는 SSOT에 넣지 않는다.** [docs/notes/](docs/notes/)에 둔다.
7. **문서를 가볍게 유지한다.** SSOT.md에는 판단 기준만, 계획과 설계는 docs/ssot/에, 현황과 작업물은 라인 폴더에 쓴다. 같은 내용을 두 곳에 쓰지 않는다. 노션 HQ와 겹치지 않게 [workplace.md](docs/ssot/workplace.md)를 따른다.

## 읽는 범위

| 구분 | 무엇 |
| --- | --- |
| 늘 읽는다 | 이 파일, [SSOT.md](SSOT.md) |
| 업무에 해당하면 꼭 읽는다 | [docs/ssot/](docs/ssot/)의 파일. SSOT.md '문서 지도'를 따른다 |
| 필요할 때만 찾는다 | 라인 폴더 README, [docs/interviews/](docs/interviews/), [docs/decisions/](docs/decisions/), [docs/sources/](docs/sources/) |
| 읽지 않는다 | [archive/](archive/). Katie가 지난 작업을 찾으라고 할 때만 본다 |

- 폴더를 통째로 읽지 않는다. 필요한 파일을 찾아서 읽는다. 사진·영상 폴더는 목록만 본다.
- 결정 로그에는 최근 2주만 둔다. 지난 줄과 끝난 작업물은 일요일 주간 회고에서 옮기자고 제안하고, Katie 승인 뒤에 옮긴다.

## 경계

- **체험단 블로그는 Katie 브랜드 밖이다.** 생활비를 줄여 주는 도구로 가볍게 다룬다. 외국인 여행객에게 맞는 곳만 katie_from_korea 소재로 쓴다.
- **odssi 편집 툴킷([tools/odssi-style-kit/](tools/odssi-style-kit/))은 남이 만든 유료·무료 배포물이다.** 툴킷 안에서는 툴킷의 CLAUDE.md를 따른다. 툴킷 파일(자막 디자인, 효과음, 배경, 코드, 지침)을 다른 곳에 복사·공유·업로드하지 않는다(`사용조건.md`). git에도 올리지 않는다.
- **협찬 콘텐츠는** 이해관계를 밝힌다.
- **사람의 얼굴·이야기는 동의를 받은 것만** 쓴다. 친구는 정수리샷처럼 얼굴이 안 보이게 찍은 것을 기본으로 한다. [초안]
- **주소, 연락처, 관심 신청자 개인정보, 비밀번호·토큰은 저장소에 남기지 않는다.**

## 글쓰기

- 기본 언어는 한국어다. katie_from_korea의 영상 문구는 영어가 기본이다.
- 후킹 문장과 자막은 **Katie가 먼저 쓰고**, Claude는 '더 짧게', '영어 문법 확인' 같은 피드백만 한다 (4주 시험 중, 2026-11-16~12-13).
- 문서는 짧은 문장, 표, 체크리스트로 쓴다.
- 날짜는 2026-11-25처럼 쓴다. '오늘', '이번 주'는 날짜로 바꿔 적는다.

## 폴더별 안내

| 폴더 | 무엇 | 먼저 읽을 것 |
| --- | --- | --- |
| [katie-from-korea/](katie-from-korea/) | 인스타 katie_from_korea: 미디어 키트, 홈페이지 소스 | katie-from-korea/README.md |
| [kkomul-store/](kkomul-store/) | 꼬물상점: 캐릭터, 카드뉴스, 디자인 인수인계 | kkomul-store/README.md |
| [growth-blog/](growth-blog/) | 성장기록 블로그(네이버 + 브런치) 원고 | growth-blog/README.md |
| [review-blog/](review-blog/) | 체험단 블로그 (브랜드 밖) | review-blog/README.md |
| [tools/](tools/) | 작업 도구. odssi 릴스 편집 툴킷 | tools/README.md, 툴킷의 CLAUDE.md |
| [docs/](docs/) | ssot(계획·설계·결정 로그), interviews(인터뷰·원문), sources(원본 문서), notes(미정 아이디어), decisions(지난 결정) | 필요한 파일만 |
| [archive/](archive/) | 끝난 작업물 | 읽지 않는다 |

## 커밋

- 커밋 메시지는 한국어 한 줄: 무엇이 왜 바뀌었는지.
- SSOT(SSOT.md, docs/ssot/)를 바꾼 커밋은 결정 로그 변경을 함께 담는다.
- 사진·영상·툴킷은 git에 올리지 않는다(.gitignore). 원격은 GitHub **비공개** 저장소만 쓴다.
- 일을 끝낼 때 커밋 안 된 변경을 남기지 않는다.
