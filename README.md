# Sonmat Coding Web Template

## English

### Overview
This project is a lightweight multi-page website prototype built with plain HTML, CSS, and a small amount of vanilla JavaScript. It focuses on a clean first impression, simple navigation, responsive layouts, and fast local preview without any build step or external dependency.

### Project Goals
- Create a homepage and connected subpages.
- Keep the structure simple enough to open directly in a browser.
- Preserve the existing UI concept while refining spacing where needed.

### Files
- `index.html`: Landing page with hero, feature summary, navigation, and links to all other pages.
- `list.html`: Card-based list page that works as a content hub.
- `conts.html`: Content detail page for reading a single topic in a focused layout.
- `app.html`: User-profile style information page with cards and activity summary.
- `game.html`: Mini interaction page with a simple score game using `localStorage`.
- `01.TASK.md`: Original task definition for generating the website pages.
- `02.REVISION.md`: Revision note requesting spacing checks for `game.html` and `conts.html`.
- `02.REVISION-01.md`: Revision note requesting spacing checks for `app.html`.

### Page Flow
- `index.html` links to `list.html`, `conts.html`, `app.html`, and `game.html`.
- `list.html` links to `conts.html`, `app.html`, and `game.html`.
- `conts.html`, `app.html`, and `game.html` include navigation back into the main flow.

### Key Characteristics
- No framework or package manager required.
- Inline CSS per page for fast prototyping.
- Responsive layouts with mobile breakpoints.
- Consistent page-to-page navigation.
- Lightweight interaction in `game.html` with best-score persistence.

### How to Use
1. Open `index.html` in a web browser.
2. Navigate through the linked pages.
3. Edit each HTML file directly to change text, style, or structure.

### Notes From Existing Markdown
- The original task requested a homepage and connected output pages.
- Later revisions focused on spacing consistency without changing filenames, removing features, or changing the overall UI concept.

---

## 한국어

### 개요
이 프로젝트는 순수 HTML, CSS, 그리고 소량의 바닐라 JavaScript로 만든 가벼운 멀티페이지 웹사이트 프로토타입입니다. 빌드 과정이나 외부 의존성 없이 바로 브라우저에서 실행할 수 있도록 구성되어 있으며, 첫 화면의 인상, 단순한 이동 흐름, 반응형 레이아웃에 초점을 두고 있습니다.

### 프로젝트 목표
- 홈페이지와 연결된 하위 페이지를 만든다.
- 브라우저에서 바로 열 수 있을 정도로 구조를 단순하게 유지한다.
- 필요한 경우 여백을 조정하되 기존 UI 콘셉트와 기능은 유지한다.

### 파일 설명
- `index.html`: 히어로 섹션, 특징 소개, 전체 페이지 링크를 포함한 랜딩 페이지.
- `list.html`: 여러 항목을 카드 형태로 보여주는 목록 허브 페이지.
- `conts.html`: 하나의 주제를 집중해서 읽을 수 있는 상세 콘텐츠 페이지.
- `app.html`: 사용자 프로필과 활동 요약을 보여주는 정보형 페이지.
- `game.html`: `localStorage`를 사용하는 간단한 점수 게임 페이지.
- `01.TASK.md`: 초기 웹사이트 생성 요구사항을 정리한 작업 문서.
- `02.REVISION.md`: `game.html`, `conts.html`의 여백 점검 및 수정 요청 문서.
- `02.REVISION-01.md`: `app.html`의 `main`, `footer` 여백 점검 및 수정 요청 문서.

### 페이지 흐름
- `index.html`에서 `list.html`, `conts.html`, `app.html`, `game.html`로 이동할 수 있습니다.
- `list.html`에서 `conts.html`, `app.html`, `game.html`로 이동할 수 있습니다.
- `conts.html`, `app.html`, `game.html`은 다시 메인 흐름으로 돌아갈 수 있는 링크를 포함합니다.

### 주요 특징
- 프레임워크나 패키지 설치가 필요 없습니다.
- 빠른 프로토타이핑을 위해 페이지별 인라인 CSS를 사용합니다.
- 모바일 대응을 포함한 반응형 레이아웃을 제공합니다.
- 페이지 간 이동 구조가 일관되게 연결되어 있습니다.
- `game.html`은 최고 점수를 브라우저에 저장하는 가벼운 인터랙션을 포함합니다.

### 사용 방법
1. 브라우저에서 `index.html`을 엽니다.
2. 연결된 페이지를 따라 이동하며 확인합니다.
3. 텍스트, 스타일, 구조 변경이 필요하면 각 HTML 파일을 직접 수정합니다.

### 기존 마크다운 분석 메모
- 초기 작업 문서는 홈페이지와 연결 페이지 생성을 목표로 하고 있습니다.
- 이후 수정 문서는 파일명 변경 금지, 기능 삭제 금지, 기존 UI 유지 조건 아래 여백 정리를 요청하고 있습니다.
