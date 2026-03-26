# Sonmat Coding Tactical Web Template

## English

### Overview
This project is a lightweight multi-page web prototype built with plain HTML, CSS, and a small amount of vanilla JavaScript. It started as a simple connected website and was later revised so that all HTML pages share a tactical sci-fi UI concept inspired by Evangelion-style interface design.

### Revision Context
Based on `02.REVISION-02.md`, all HTML files were refactored to apply a unified theme while keeping existing functionality unchanged.

- Target: all HTML files
- Change request: apply an Evangelion-inspired UI theme
- Keep: existing functionality
- Do not: rename files or remove features

### Pages
- `index.html`: Main landing page with hero messaging, feature highlights, route links, and section-based storytelling.
- `list.html`: Route hub page that presents major content entries as tactical cards.
- `conts.html`: Single-topic content detail page for focused reading.
- `app.html`: Profile-style information page showing user data, status, and activity summary.
- `game.html`: Interactive mini-game page with score tracking and `localStorage` best-score persistence.

### Theme Characteristics
- Dark interface with HUD-like panel styling
- Grid-based sci-fi background overlays
- Orange warning accents and neon green signal accents
- Angular card shapes and technical badge styling
- Unified navigation and button system across all pages

### File Structure
- `index.html`
- `list.html`
- `conts.html`
- `app.html`
- `game.html`
- `01.TASK.md`
- `02.REVISION.md`
- `02.REVISION-01.md`
- `02.REVISION-02.md`

### Navigation Flow
- `index.html` links to `list.html`, `conts.html`, `app.html`, and `game.html`
- `list.html` works as a hub linking into content, profile, and game pages
- `conts.html`, `app.html`, and `game.html` provide return paths back into the main flow

### Technical Notes
- No framework or package manager is required
- All pages use inline CSS for direct editing and rapid prototyping
- Layouts include responsive behavior for smaller screens
- `game.html` contains the only JavaScript logic in the project
- Best score in the game is stored in browser `localStorage`

### How to Use
1. Open `index.html` in a web browser.
2. Move through the linked pages.
3. Edit each HTML file directly if you want to change copy, styling, or structure.

---

## 한국어

### 개요
이 프로젝트는 순수 HTML, CSS, 그리고 소량의 바닐라 JavaScript로 만든 가벼운 멀티페이지 웹 프로토타입입니다. 처음에는 기본 연결형 홈페이지 구조로 시작했고, 이후 `02.REVISION-02.md` 기준으로 모든 HTML 파일에 에반게리온풍 전술 HUD 계열 UI 테마를 적용하도록 수정되었습니다.

### 수정 기준
`02.REVISION-02.md`의 요구사항에 따라 모든 HTML 파일의 UI 콘셉트를 통일했으며, 기존 기능은 유지했습니다.

- 대상: 모든 HTML 파일
- 변경 요청: 일본 애니메이션 에반게리온 스타일의 UI 테마 적용
- 유지: 기존 기능
- 금지: 파일명 변경, 기능 삭제

### 페이지 설명
- `index.html`: 히어로 메시지, 특징 소개, 페이지 이동 링크, 섹션형 스토리 흐름을 담은 메인 랜딩 페이지
- `list.html`: 주요 화면으로 이동할 수 있는 카드형 허브 페이지
- `conts.html`: 하나의 주제를 집중해서 읽는 상세 콘텐츠 페이지
- `app.html`: 사용자 정보, 상태, 활동 요약을 보여주는 프로필형 페이지
- `game.html`: 점수 기록과 최고 점수 저장 기능이 포함된 미니 게임 페이지

### 테마 특징
- 어두운 배경 기반의 HUD 스타일 패널
- 격자형 SF 배경 레이어
- 경고 오렌지와 신호 그린 중심의 포인트 색상
- 각진 카드 형태와 기술 UI 느낌의 배지 스타일
- 모든 페이지에 통일된 내비게이션과 버튼 시스템 적용

### 파일 구성
- `index.html`
- `list.html`
- `conts.html`
- `app.html`
- `game.html`
- `01.TASK.md`
- `02.REVISION.md`
- `02.REVISION-01.md`
- `02.REVISION-02.md`

### 페이지 이동 구조
- `index.html`에서 `list.html`, `conts.html`, `app.html`, `game.html`로 이동할 수 있습니다.
- `list.html`은 콘텐츠, 프로필, 게임 페이지로 진입하는 허브 역할을 합니다.
- `conts.html`, `app.html`, `game.html`은 다시 메인 흐름으로 돌아갈 수 있는 링크를 포함합니다.

### 기술 메모
- 프레임워크나 패키지 매니저가 필요하지 않습니다.
- 모든 페이지는 인라인 CSS 기반으로 구성되어 바로 수정하기 쉽습니다.
- 작은 화면을 위한 반응형 레이아웃을 포함하고 있습니다.
- 실제 JavaScript 로직은 `game.html`에만 들어 있습니다.
- 게임 최고 점수는 브라우저 `localStorage`에 저장됩니다.

### 사용 방법
1. 브라우저에서 `index.html`을 엽니다.
2. 연결된 페이지를 따라 이동합니다.
3. 문구, 스타일, 구조를 바꾸려면 각 HTML 파일을 직접 수정합니다.
