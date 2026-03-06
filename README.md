<p align="center">
  <img src="./screenshots/screenshot-1-hero.png" alt="POKEIT" width="720" />
</p>

<h1 align="center">POKEIT</h1>

<p align="center">
  <b>POKE! the UI. Tell AI what to fix.</b><br/>
  고치고 싶은 UI를 폭! 찍고 AI에게 수정 요청하세요.
</p>

<p align="center">
  <a href="https://pokeit.app">Website</a> · <a href="#installation--설치-방법">Install</a> · <a href="#features--주요-기능">Features</a>
</p>

---

## What is POKEIT? / POKEIT이 뭔가요?

POKEIT is a free Chrome extension that turns your browser into a visual QA tool for AI-powered development. Inspect any element, leave a QA note in plain language, and copy the full component context — tree, computed styles, source paths — straight to your AI coding agent. No npm packages, no project config — just install the extension and go.

POKEIT은 브라우저를 AI 개발용 비주얼 QA 도구로 바꿔주는 크롬 익스텐션입니다. 아무 컴포넌트나 클릭해서 검사하고, QA 노트를 남긴 뒤, 복사버튼을 눌러보세요! 컴포넌트 트리·스타일·소스 경로 등 전체 컨텍스트를 AI 코딩 에이전트에 바로 붙여넣을 수 있습니다. npm 설치도, 프로젝트 설정도 필요 없어요. 익스텐션만 깔면 바로 쓸 수 있습니다.

---

## How it works / 작동 방식

### 1. Inspect / 검사
Press `⌥P` or Option-click any element. POKEIT reads the React component tree, computed styles, and source file location.
`⌥P` 누르거나 Option-클릭하면 끝. 컴포넌트 트리, 스타일, 소스 위치를 알아서 읽어옵니다.

<p align="center">
  <img src="./screenshots/screenshot-2-inspect.png" alt="Inspect Mode" width="720" />
</p>

### 2. Annotate / 메모
Leave a note — *"Make this 16px"* or *"Align to grid"*. Stack as many notes as you need.
*"패딩 24px로"*, *"그리드에 맞춰"* — 이런 식으로 메모 남기면 됩니다. 여러 개 쌓아도 OK.

### 3. Copy to AI / AI에게 전달
One click copies all notes with full component context. Paste into Claude Code, Cursor, or any AI agent.
복사 한 번이면 노트 + 컴포넌트 컨텍스트가 통째로 클립보드에. Claude Code, Cursor 등 아무데나 붙여넣으면 됩니다.

<p align="center">
  <img src="./screenshots/screenshot-3-annotate.png" alt="Annotate & Copy" width="720" />
</p>

---

## Features / 주요 기능

| Feature | Description |
|---------|-------------|
| **Component Tree** | Reads React fiber — component names, source file paths, and line numbers. 리액트 구조를 읽어 컴포넌트 이름, 소스 파일 경로, 라인 번호를 표시합니다. |
| **Computed Styles** | Shows resolved CSS values and detects spacing overlaps between parent and child. 계산된 CSS 값을 보여주고, 부모-자식 간 간격을 표시합니다. |
| **QA Notes** | Leave plain-language notes on any element. Notes are saved per site and persist across page reloads. 아무 요소에 메모 남기고, 사이트별로 자동 저장됩니다. 새로고침해도 안 날아가요. |
| **One-Click Copy** | Exports all notes with full context — tree, styles, source paths — formatted for AI agents. 트리, 스타일, 소스 경로 — 전부 AI 에이전트용 포맷으로 한 방에 내보냅니다. |
| **Zero Config** | Works on any React site — production or localhost. No project setup required. 어떠한 React 사이트에서도 잘 동작합니다. npm 등 프로젝트 별 설정이 필요 없습니다. |

---

## Installation / 설치 방법

> Chrome Web Store approval is taking longer than expected, so we're releasing the extension here first. Install manually for now — the store link will be added once approved.
> 크롬 웹 스토어 승인이 좀 오래 걸려서, 일단 여기서 먼저 공개합니다. 승인되면 스토어 링크 추가할게요!

### 1. Download / 다운로드

Download **[pokeit-extension.zip](./pokeit-extension.zip)** from this repository.

**[pokeit-extension.zip](./pokeit-extension.zip)** 받아주세요.

### 2. Unzip / 압축 해제

Extract the zip file to any folder.

아무 폴더에 압축 풀면 됩니다.

### 3. Load in Chrome / Chrome에 로드

1. Open `chrome://extensions` / `chrome://extensions` 열기
2. Enable **Developer mode** (top right toggle) / 우측 상단 **개발자 모드** 켜기
3. Click **Load unpacked** / **압축해제된 확장 프로그램을 로드합니다** 클릭
4. Select the extracted folder / 압축 해제한 폴더 선택

### 4. Done! / 끝!

Click the POKEIT icon on any webpage to start inspecting.

아무 웹페이지에서 포킷 아이콘 누르면 바로 시작!

---

## Roadmap / 앞으로의 계획

We bought the domain for 5 years — POKEIT is here to stay. Actively developing new features and improvements.
pokeit.app 도메인을 5년 샀습니다... — POKEIT 포킷은 모두가 더 예쁜 디자인을 할 수 있도록 계속해서 디벨롭하겠습니다!

---

## Contact / 연락처

Got feedback, ideas, or bugs to report? Reach out:

의견이나 버그 제보 언제든 환영합니다:

- **KR:** [@0x3den](https://x.com/0x3den)
- **EN:** [@sejinxjung](https://x.com/sejinxjung)
- **LinkedIn:** [sejinxjung](https://linkedin.com/in/sejinxjung)

---

<p align="center">
  <a href="https://pokeit.app">pokeit.app</a>
</p>
