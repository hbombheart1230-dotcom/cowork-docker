# AI vs REAL 바이럴 영상 퀴즈 (2026-10-30)

## 📋 프로젝트 개요

2025~2026년 SNS에서 화제가 된 영상 20개를 조사하여, **AI 생성 영상 5개**와 **실제 촬영 영상 5개**를 선별한 블라인드 퀴즈 패키지입니다.

## ⚠️ 중요: 라이선스 현황

**모든 선정된 10개 영상은 `LINK_ONLY` 상태입니다.**

| 영상 | 사유 |
|------|------|
| A01 AI Bunnies | TikTok ToS 재배포 금지 |
| A02 Kangaroo | Instagram ToS 재배포 금지 |
| A04 Three Kittens | TikTok ToS 재배포 금지 |
| A05 Single Ladies Dog | 유료 AI 생성 서비스 (JumpOnTheTrend) |
| A09 Tesla Bridge | X ToS 재배포 금지 |
| R01 Coyote | Storyful 유료 라이선스 필요 |
| R02 Jimothy | Instagram ToS 재배포 금지 |
| R04 Mice Fighting | Independent 라이선스 필요 |
| R08 Smalltown Boy | 크리에이터 라이선스 조건 적용 |
| R09 The JAWN | TikTok ToS 재배포 금지 |

**결론**: CC0/CC-BY 등 명시적 재사용 권한이 있는 영상은 **0개**입니다. 모든 영상은 원본 플랫폼의 이용약관(ToS)에 따라 재배포가 금지되어 있어, GitHub에 MP4 파일로 업로드할 수 없습니다.

## 🎯 퀴즈 구성

| 번호 | 파일명 | 정답 | 영상 제목 | 원본 링크 |
|------|--------|------|-----------|-----------|
| 1 | clip_01.mp4 | **AI** | AI Bunnies on Trampoline | [TikTok @rachelthecatlovers](https://www.tiktok.com/@rachelthecatlovers) |
| 2 | clip_02.mp4 | **AI** | Emotional Support Kangaroo | [Instagram @infiniteunreality](https://www.instagram.com/infiniteunreality/) |
| 3 | clip_03.mp4 | **AI** | Three Kittens Dancing | [TikTok @meowtakeover](https://www.tiktok.com/@meowtakeover) |
| 4 | clip_04.mp4 | **AI** | Single Ladies Dog (Odie) | [TikTok @king_odiee](https://www.tiktok.com/@king_odiee) |
| 5 | clip_05.mp4 | **AI** | Tesla Roadster Golden Gate | [X @HodlMiro](https://x.com/HodlMiro) |
| 6 | clip_06.mp4 | **REAL** | Coyote on Trampoline | [Storyful](https://video.storyful.com/record/35495) |
| 7 | clip_07.mp4 | **REAL** | Jimothy the Raccoon | [Instagram @c1vrgr1](https://www.instagram.com/c1vrgr1/) |
| 8 | clip_08.mp4 | **REAL** | Mice Fighting London Underground | [Independent 기사](https://www.independent.co.uk/tv/news/mice-fighting-london-underground-viral-video-b3044090.html) |
| 9 | clip_09.mp4 | **REAL** | Smalltown Boy Original | [in2mood.com](https://in2mood.com/story) |
| 10 | clip_10.mp4 | **REAL** | The JAWN Dance | [TikTok @monikapilon](https://www.tiktok.com/@monikapilon) |

## 📁 파일 구조

```
ai-real-quiz-20261030/
├── videos/              # MP4 파일 (라이선스 확보 시에만 업로드됨)
│   ├── clip_01.mp4      # 현재 LINK_ONLY - 업로드 불가
│   ├── clip_02.mp4
│   ├── clip_03.mp4
│   ├── clip_04.mp4
│   ├── clip_05.mp4
│   ├── clip_06.mp4
│   ├── clip_07.mp4
│   ├── clip_08.mp4
│   ├── clip_09.mp4
│   └── clip_10.mp4
├── README.md            # 이 파일
├── sources.csv          # 20개 전체 후보 상세 정보
├── answer_key.csv       # 정답표 (clip_filename, correct_answer, candidate_id, ...)
├── candidate_review.csv # 20개 후보 평가 점수 및 선정 여부
└── blocked_sources.csv  # 다운로드/업로드 차단 사유 상세
```

## 📊 평가 기준 및 선정 결과

### 평가 배점 (총 100점)
- SNS 유명세: 40점
- 재미·황당함·신선함: 30점
- AI/REAL 판별 난이도: 20점
- 약 10초 편집 적합성: 10점

### 선정 결과 (AI 5개, REAL 5개)

| 구분 | 후보 | 점수 | 선정 |
|------|------|------|------|
| **AI** | A01 Bunnies on Trampoline | 100 | ✅ |
| **AI** | A04 Three Kittens Dancing | 98 | ✅ |
| **AI** | A02 Kangaroo | 95 | ✅ |
| **AI** | A05 Single Ladies Dog | 95 | ✅ |
| **AI** | A09 Tesla Bridge | 95 | ✅ |
| **REAL** | R01 Coyote | 100 | ✅ |
| **REAL** | R02 Jimothy | 100 | ✅ |
| **REAL** | R04 Mice Fighting | 100 | ✅ |
| **REAL** | R08 Smalltown Boy | 100 | ✅ |
| **REAL** | R09 The JAWN | 100 | ✅ |

### 탈락 후보 (차단 사유)
- A03, A06, A07, A08, A10: 점수 미달 또는 출처 불명
- R03, R05, R06, R07, R10: 라이선스 불명/차단/점수 미달

## 🔍 검증 근거 요약

### AI 영상 (5개)
1. **A01 Bunnies**: TikTok @rachelthecatlovers, 2025.07, 148.8M plays, KnowYourMeme 확정 AI
2. **A02 Kangaroo**: Instagram @infiniteunreality, 2025.05, VFX 아티스트 자작, KnowYourMeme 확정 AI
3. **A04 Three Kittens**: TikTok @meowtakeover, 2026.06, 79.5M views, KnowYourMeme 확정 AI
4. **A05 Single Ladies Dog**: TikTok @king_odiee, 2026.10, JumpOnTheTrend AI 생성 서비스
5. **A09 Tesla**: X @HodlMiro, 2026.10, Lead Stories 팩트체크 99.9% AI 판정 (Hive Moderation)

### REAL 영상 (5개)
1. **R01 Coyote**: Liron Lavie 촬영, Storyful 라이선스, 캘리포니아 타르자나
2. **R02 Jimothy**: Seattle 너구리 Jimothy, short spine syndrome, Instagram @c1vrgr1
3. **R04 Mice**: Sonia Mansfield 촬영, Oxford Circus 역, The Independent 2026.09.03 보도
3. **R08 Smalltown Boy**: Sergei & Elvira 원본, Instagram @mr_unvrs/@elvira.mua.music, 2026.08.04
4. **R09 The JAWN**: Monika Pilon (@monikapilon), TikTok 2026.07.16, 18.7M plays

## 📝 라이선스 및 저작권 안내

| 영상 | 라이선스 상태 | 비고 |
|------|--------------|------|
| 모든 10개 | **LINK_ONLY** | MP4 업로드 불가, 원본 링크만 제공 |

**이유**: 모든 영상이 TikTok, Instagram, X, YouTube, 뉴스 사이트 등 플랫폼 ToS에 의해 재배포가 금지되어 있으며, CC0/CC-BY 등 명시적 재사용 허가가 없습니다.

### 권장 사용 방식
1. **링크 기반 퀴즈**: 각 영상의 원본 링크를 브라우저에서 직접 재생
2. **교육/연구 목적**: 개인 시청 목적의 다운로드만 가능 (플랫폼 기능 사용)
3. **재배포 금지**: MP4 파일을 GitHub, 타 사이트에 재업로드 금지

## 📂 포함된 파일

| 파일 | 설명 |
|------|------|
| `sources.csv` | 20개 전체 후보 상세 정보 (출처, 연도, 크리에이터, URL, 점수 등) |
| `answer_key.csv` | 정답표 (clip_filename, correct_answer, candidate_id, title, license 등) |
| `candidate_review.csv` | 20개 후보 평가 점수, 진위 판단 근거, 다운로드 상태, 최종 선정 여부 |
| `blocked_sources.csv` | 다운로드/업로드 차단 사유 상세 (라이선스, 접근 차단, 출처 불명 등) |
| `answer_key.csv` | 퀴즈 정답표 (파일명, 정답, 출처, 라이선스 상태 등) |

## 🔗 참고 링크

- [KnowYourMeme: AI Bunnies](https://knowyourmeme.com/memes/ai-bunnies-jumping-on-a-trampoline-video)
- [KnowYourMeme: Kangaroo](https://knowyourmeme.com/memes/emotional-support-kangaroo-rejected-entry-to-plane)
- [KnowYourMeme: Three Kittens](https://knowyourmeme.com/memes/three-kittens-dancing-the-dark-triad)
- [Lead Stories: Tesla Fact Check](https://leadstories.com/hoax-alert/2026/10/fake-video-tesla-roadster-jumping-off-golden-gate-bridge-ai-generated-digital-aerobatics.html)
- [KnowYourMeme: Jimothy](https://knowyourmeme.com/memes/jimothy-the-raccoon)
- [Independent: Mice Fighting](https://www.independent.co.uk/tv/news/mice-fighting-london-underground-viral-video-b3044090.html)
- [in2mood: Smalltown Boy](https://in2mood.com/story)
- [JumpOnTheTrend: The JAWN](https://jumponthetrend.app/trends/the-jawn-ai-trend/)

## 📅 작업 일자 및 버전

- **작업일**: 2026-10-30
- **실행 담당**: Hermes Agent (Agentco Main)
- **버전**: 1.0
- **Git 브랜치**: `content/ai-real-quiz-20261030`

---

**작성자**: Hermes Agent (Agentco Main)  
**검증 기준**: KnowYourMeme, Lead Stories, AfricaCheck, 주요 언론 보도, 크리에이터 공식 계정  
**라이선스 준수**: 플랫폼 ToS 및 저작권법 준수, 재배포 권한 없는 콘텐츠는 LINK_ONLY 처리