# 📦 Project: Gunner Up

## 1️⃣ 프로젝트 기본 정보

* **프로젝트 이름**: Gunner Up
* **프로젝트 유형**: 웹 서비스 (WordPress 플러그인 기반)
* **진행 상태**: 진행 중 (MVP 개발 단계)
* **기간**: 2025 ~
* **기술 스택**: WordPress, BuddyBoss Theme, Custom PHP Plugin, football-data.org API, FPL API, ESPN API

### 한 줄 요약

> 이 프로젝트는
> **말하지 않아도 아스널 경기에 참여하고 있었다는 감각을
> 소심한 팬들에게 남겨주기 위한 서비스**이다.

---

## 2️⃣ Problem — 내가 느낀 문제

나는 아스널 경기를 보고 나서도
그 경기에 *참여했다*는 느낌을 잘 받지 못했다.

경기는 분명히 끝까지 봤고,
감정도 분명히 있었지만
그 이후의 공간은 언제나 시끄러웠다.

- 인스타 댓글
- 공격적인 반응
- 이겨야만 말할 수 있는 분위기
- 감정이 강한 사람들만 보이는 구조

그 안에서 나는 늘 **보고만 있는 사람**이었다.
말하지 않았다는 이유로,
아무 흔적도 남기지 못한 채
그 경기를 그냥 지나쳐버린 느낌이 들었다.

이 문제는 나처럼:
- 조용하고
- 의견을 말하는 데 오래 고민하고
- 감정을 속으로 정리하는 사람에게
더 크게 다가왔다.

**말하지 않으면, 참여하지 않은 것처럼 취급되는 구조**가
가장 불편했다.

---

## 3️⃣ Why This Project — 왜 이 프로젝트인가

이 문제는 글쓰기나 커뮤니티 규칙을 바꾸는 것으로는 해결되지 않는다고 느꼈다.

기존의 방식은 대부분:
- 말을 잘해야 하고
- 의견을 드러내야 하며
- 반응을 감수해야 한다

하지만 내가 원하는 건
**표현의 훈련이 아니라, 존재의 인정**이었다.

그래서 이 문제를
'커뮤니티'가 아니라
**조용한 참여를 기록하는 서비스**로 풀고 싶었다.

---

## 4️⃣ Project Goal — 이 프로젝트의 목표

Gunner Up의 목표는 단순하다.

* 말하지 않아도 참여했다는 감각을 준다
* 잘했는지가 아니라, 지나가지 않았음을 남긴다
* 감정의 크기가 아니라, 존재의 사실을 기록한다

사용자가 얻길 바라는 변화는 이것이다:

- "나는 아무 말도 안 했지만, 이 경기에 있었다"
- "이 감정을 그냥 흘려보내지 않았다"
- "Up이든 Down이든, 나는 참여했다"

---

## 5️⃣ Solution — 내가 제안하는 해결 방식

Gunner Up는
**경기 하나당 아주 작은 선택 하나**만을 요구한다.

### 핵심 아이디어

- 경기 후 사용자는:
  - 다섯 가지 감정 중 하나를 선택한다
  - 🔥 Ecstatic · 💪 Hopeful · 😐 Uncertain · 😤 Frustrated · 😡 Furious
  - 원한다면 한 줄 평을 남긴다 (선택, 비공개)
- 그 외의 행동은 필요 없다

### 감정 선택의 의미

Gunner Up에서의 감정 선택은:
- 옳고 그름이 아니다
- 다수와의 비교가 아니다
- 평가가 아니다

> **그날의 경기에 대해 내가 느낀 것을
> 아주 조용히, 하나만 남기는 것**이다.

어떤 감정을 선택하든
그것은 그날의 참여이고, 기록이다.

### 비교하지 않는다

Gunner Up는 의도적으로:
- "다수와 일치했는가"를 말하지 않는다
- "너 vs 팬들"을 비교하지 않는다
- "맞았다/틀렸다"를 판단하지 않는다

사용자가 보는 것은:
- 내가 어떤 감정을 남겼는지
- 전체적으로 팬들이 어떻게 느꼈는지 (분포)
- 내가 몇 경기에 참여했는지 (개인 기록)

---

## 6️⃣ 구현 내용 (What I Made)

### 핵심 기능

| 기능 | 설명 | 상태 |
|------|------|------|
| **Match Pulse** | 경기 후 감정 선택 (5가지). 대시보드에서는 최근 경기 1개, 페이지에서는 30일 내 경기 목록. | ✅ 완료 |
| **My Presence** | 개인 참여 기록. 참여 횟수, 연속 참여 기록을 숫자로 보여준다. | ✅ 완료 |
| **Weekly Fan Mood** | 이번 주 전체 팬들의 감정 분포. 비교가 아닌 관찰의 도구. | ✅ 완료 |
| **Upcoming Fixtures** | 다가오는 경기 일정 (PL, CL + 수동 등록 경기). | ✅ 완료 |
| **Recent Results** | 최근 경기 결과와 스코어. | ✅ 완료 |
| **League Table** | 프리미어리그 순위표. 아스널 강조. | ✅ 완료 |
| **Injuries & Suspensions** | 현재 부상/징계 선수 목록 (FPL API). | ✅ 완료 |
| **Arsenal News** | arsenal.com 남자팀 뉴스 자동 크롤링 → WP 포스트 발행. | ✅ 완료 |
| **한 줄 평** | 감정 선택 후 선택적 비공개 코멘트. | 🔜 예정 |

### 관리자 기능

| 기능 | 설명 |
|------|------|
| **Dashboard** | 활성 팬 수, 주간 투표 수, 주요 감정, 최근 투표 내역 + 삭제 |
| **Fixtures** | API 자동 경기 + 수동 등록/삭제, 소스별 현황 카드 |
| **News** | 크롤링된 기사 목록, 수동 크롤링 버튼, 기사 삭제 |
| **Settings** | API 키, 캐시 TTL, 부상 데이터 새로고침, 페이지/메뉴 자동 생성 |

### 프론트엔드 페이지

| 페이지 | 숏코드 |
|--------|--------|
| Dashboard | 기존 대시보드 (위젯 모음) |
| Match Pulse | `[gunnerup_match_pulse_page]` |
| My Presence | `[gunnerup_presence_page]` |
| Fixtures & Results | `[gunnerup_fixtures_page]` |
| League Table | `[gunnerup_table]` |
| Injuries | `[gunnerup_injuries]` |
| Weekly Fan Mood | `[gunnerup_weekly_mood]` |
| Arsenal News | WP 카테고리 아카이브 (arsenal-news) |

### 사용한 기술

| 기술 | 용도 |
|------|------|
| **WordPress** | 플랫폼 |
| **BuddyBoss Theme** | 커뮤니티 기반 UI/UX |
| **Custom Plugin (gunnerup)** | 핵심 로직 — Clean Architecture (Domain/Application/Infrastructure/Interfaces) |
| **football-data.org API** (무료) | 경기 일정, 결과, 순위표 |
| **FPL API** (무료, 인증 불필요) | 부상/징계 데이터, 선수 상태 |
| **ESPN API** (비공식, 무료) | FA Cup 등 추가 대회 일정 |
| **WP-Cron** | 15분마다 경기/순위 갱신, 1시간마다 뉴스 크롤링, 12시간마다 부상 갱신 |

### 설계 원칙

- 말하지 않아도 가능한 구조를 최우선으로 설계
- 비교, 순위, 평가 요소 제거
- 감정 선택은 항상 1번이면 충분
- 개인 기록은 본인만 볼 수 있음
- 관리자가 수동으로 경기를 추가할 수 있음 (API에 없는 대회 대응)

---

## 7️⃣ 결과와 관찰 (Outcome)

아직 완성 단계는 아니지만,
이 구조를 설계하며 분명히 느낀 점이 있다:

- 감정을 하나만 고르는 행위가 생각보다 강한 참여감을 준다
- "몇 경기에 참여했는지"라는 숫자가 조용한 동기를 만든다
- 비교를 없앴을 때, 선택이 더 솔직해진다
- 사이트에 돌아올 이유가 "다음 경기"에 묶여 자연스러운 리텐션이 생긴다

---

## 8️⃣ Blog Strategy — 왜 블로그를 함께 운영하는가

Gunner Up는 감정을 기록하는 서비스다.
하지만 서비스만으로는 사람들에게 닿기 어렵다.

나는 이 프로젝트를 단지 기능으로만 존재하게 두고 싶지 않았다.
그래서 블로그를 함께 운영하기로 했다.

블로그의 목적은 두 가지다:

1. 더 많은 아스널 팬들에게 도달하기 위해
2. Gunner Up의 철학을 자연스럽게 설명하기 위해

현실적으로 나는 일주일에 1–2편 정도만 글을 쓸 수 있다.
그래서 카테고리는 최소한으로, 하지만 방향은 분명하게 정리했다.

---

## 9️⃣ Blog Categories

### 1. Arsenal Matches

이 카테고리는 경기 중심 콘텐츠를 다룬다.

- Match preview
- Post-match analysis
- Tactical thoughts
- Player ratings

검색을 통해 들어오는 팬들에게 가장 먼저 닿는 공간이 될 것이다.
정보성과 분석을 중심으로, 꾸준히 기록한다.

### 2. Arsenal News

빠르게 변하는 아스널 관련 소식을 다룬다.

- Transfer updates
- Injury news
- Press conference summaries
- Squad developments

과도한 자극 대신, 정리된 정보와 개인적인 짧은 생각을 덧붙이는 형식으로 운영할 계획이다.

> **현재 상태**: arsenal.com 남자팀 뉴스를 자동 크롤링하여 WP 포스트로 발행 중.
> 1시간마다 자동, 관리자 수동 실행 가능. 중복 방지.

### 3. Fan Perspective

이곳은 Gunner Up의 철학과 가장 가까운 공간이다.

- 조용한 팬으로 살아가는 이야기
- 온라인 축구 문화에 대한 생각
- 경기 이후 남는 감정에 대한 기록

이 카테고리는 트래픽을 위한 공간이라기보다는,
왜 이 서비스가 존재하는지를 설명하는 공간에 가깝다.

---

## 🔎 블로그의 역할

블로그는 소리를 키우기 위한 도구가 아니다.
하지만 현실적으로는 검색을 통해 사람들에게 도달해야 한다.

그래서 구조는 현실적으로 설계했다.
Arsenal Matches와 Arsenal News는 트래픽을 담당하고,
Fan Perspective는 정체성을 담당한다.

서비스는 "기록"을 남기는 공간이고,
블로그는 "생각"을 남기는 공간이다.

이 두 가지가 함께 갈 때,
Gunner Up는 단순한 기능이 아니라 하나의 방향성을 가진 프로젝트가 된다.

---

## 🔧 기술 아키텍처

```
gunnerup/
├── core/
│   ├── Application/        # 서비스 레이어 (VoteService, MatchService, SiteSetupService)
│   ├── Domain/             # 도메인 모델 (FootballMatch, Vote, VoteResult, Emotion)
│   │   └── Contracts/      # 인터페이스 (VoteRepositoryInterface, MatchRepositoryInterface)
│   ├── Infrastructure/
│   │   ├── External/       # 외부 API 클라이언트 (FootballAPI, FPLClient, ArsenalNewsCrawler)
│   │   └── Repository/     # DB 접근 (VoteRepository, MatchRepository)
│   ├── Installer.php       # DB 테이블 생성/마이그레이션
│   └── Plugin.php          # 부트스트래핑, DI 컨테이너
├── interfaces/
│   ├── Admin/              # 관리자 페이지 (Dashboard, Fixtures, News, Settings)
│   ├── Ajax/               # AJAX 핸들러 (투표)
│   ├── Cron/               # WP-Cron 작업 (캐시 갱신, 뉴스 크롤링)
│   └── Shortcodes/         # 프론트엔드 숏코드 (위젯용 + 페이지용)
├── templates/              # PHP 템플릿 (match-pulse, fixtures, presence, etc.)
├── assets/                 # CSS, JS
└── gunnerup.php            # 플러그인 엔트리포인트, PSR-4 오토로더
```

### 데이터 흐름

```
[외부 API] → FootballAPI / FPLClient / ESPN
     ↓
[MatchService] — 캐시 (WP Transient + DB gunnerup_match_cache)
     ↓
[Shortcode] → [Template] → 프론트엔드 HTML
     ↓
[사용자 투표] → VoteAjaxHandler → VoteService → VoteRepository (DB)
     ↓
[My Presence] — 참여 횟수, 연속 기록 계산
```

---

## 📋 향후 계획

- [ ] 한 줄 평 기능 (감정 선택 후 선택적 비공개 코멘트)
- [ ] 블로그 카테고리 추가 (Arsenal Matches, Fan Perspective)
- [ ] 사이드바 메뉴 COMMUNITY, SHOP 섹션 정리
- [ ] 미사용 코드 정리 (NewsCrawler.php 등)
- [ ] 모바일 반응형 개선
- [ ] 다국어 지원 (한국어/영어)
