# Katie

> 한국과 외국인을 잇는 1인 크리에이터, Katie의 브랜드 저장소.

Katie의 퍼스널 브랜드와 그 아래 라인(katie_from_korea, 꼬물상점, 성장기록 블로그)을 하나의 기준 문서(SSOT)로 관리한다. 기준 문서, 라인별 작업 공간, Claude가 따를 규칙이 모두 여기에 있다.

## 가장 먼저 읽을 것

1. [SSOT.md](SSOT.md): 브랜드의 단일 기준. 모든 작업은 이 문서와 맞아야 한다.
2. [CLAUDE.md](CLAUDE.md): Claude가 일하는 규칙.
3. [docs/interviews/interview-log.md](docs/interviews/interview-log.md): SSOT가 어떤 질문과 답을 거쳐 만들어졌는지.

## 폴더 구조

```
katie/
├── SSOT.md                 # 브랜드의 단일 기준 (판단 기준 + 문서 지도)
├── CLAUDE.md               # Claude 작업 규칙
├── katie-from-korea/       # 인스타 katie_from_korea (주 수입원)
│   ├── media-kit/          # 미디어 키트 이미지
│   └── homepage/           # 홈페이지에 쓸 사진·영상 소스
├── kkomul-store/           # 꼬물상점: 캐릭터, 카드뉴스, 디자인 인수인계
├── growth-blog/            # 성장기록 블로그 (네이버 + 브런치)
├── review-blog/            # 체험단 블로그. 브랜드 밖
├── tools/
│   └── odssi-style-kit/    # 릴스 자동 편집 툴킷 (git 제외)
├── docs/
│   ├── ssot/               # SSOT의 계획·설계: 나, 목표, 라인별, 워크플레이스, 열린 질문, 결정 로그
│   ├── interviews/         # 인터뷰 기록, Katie 원문
│   ├── sources/            # SSOT 이전 문서 원본 (Claude 문서 내보낸 본)
│   ├── notes/              # 아직 결정되지 않은 아이디어
│   └── decisions/          # 2주 지난 결정
└── archive/                # 끝난 작업물
```

## 일하는 방식

- **결정이 생기면**: SSOT의 해당 문서를 고치고, [결정 로그](docs/ssot/decision-log.md)에 날짜·결정·이유를 한 줄 추가한다. 2주가 지난 결정은 [docs/decisions/](docs/decisions/)로 옮긴다.
- **인터뷰나 긴 고민이 있었다면**: 질문과 답을 [interview-log.md](docs/interviews/interview-log.md) 맨 위에 추가한다. Katie가 직접 쓴 긴 글은 [katie-raw-answers.md](docs/interviews/katie-raw-answers.md)에 고치지 않고 붙인다.
- **결정되지 않은 아이디어는**: [docs/notes/](docs/notes/)에 둔다. SSOT에는 결정된 것만 들어간다.
- **매주 기록과 할 일 체크는** 노션 [Katie HQ](https://app.notion.com/p/Katie-HQ-41bfdffd443781b4b312c004edc71ec5)에서 한다. 역할 나누기는 [workplace.md](docs/ssot/workplace.md).
- **커밋 메시지는** 무엇이 왜 바뀌었는지 한국어 한 줄로 쓴다.

## 기준 문서의 역사

SSOT는 2026-11-14~23에 Claude와의 인터뷰로 만들었다. 그때 쓴 Claude 문서(https://claude.ai/artifact/VsbJv5c642m837tjTDr5Pu)는 초안 기록으로 남기고([내보낸 본](docs/sources/ssot-claude-doc-2026-11-25.md)), **2026-11-25부터는 이 저장소의 `SSOT.md`가 기준**이다.

## 지금 단계

**0단계: 4주 시험 (2026-11-16 ~ 12-13)**. katie_from_korea는 조회수 하락 원인을 시험 중이고, 꼬물상점은 7일 첫걸음(11/23~)으로 관심 신청을 받을 준비를 한다. 12/14가 첫 리뷰일이고, 그 결과로 1분기(12/14 ~ 2027-03-14) 계획을 세운다. 자세한 일정은 [goals.md](docs/ssot/goals.md).
