<p align="center">
  <img src="./screenshots/screenshot-1-hero.png" alt="POKEIT" width="720" />
</p>

<h1 align="center">POKEIT</h1>

<p align="center">
  <b>Poke the UI. Tell AI what to fix.</b><br/>
  UI를 찍고, AI에게 수정을 맡기세요.
</p>

<p align="center">
  <a href="https://pokeit.app">Website</a> · <a href="#installation--설치-방법">Install</a> · <a href="#features--주요-기능">Features</a>
</p>

---

## What is POKEIT? / POKEIT이 뭔가요?

POKEIT is a free Chrome extension that turns your browser into a visual QA tool for AI-powered development. Inspect any element, leave a QA note in plain language, and copy the full component context — tree, computed styles, source paths — straight to your AI coding agent.

POKEIT은 브라우저를 AI 개발용 비주얼 QA 도구로 바꿔주는 무료 Chrome 확장 프로그램입니다. 아무 요소나 클릭해서 검사하고, 자연어로 QA 노트를 남긴 뒤, 컴포넌트 트리·스타일·소스 경로 등 전체 컨텍스트를 AI 코딩 에이전트에 바로 붙여넣을 수 있습니다.

---

## How it works / 작동 방식

### 1. Inspect / 검사
Press `⌥P` or Option-click any element. POKEIT reads the React component tree, computed styles, and source file location.

`⌥P`를 누르거나 Option-클릭하면 React 컴포넌트 트리, 계산된 스타일, 소스 파일 위치를 읽어옵니다.

<p align="center">
  <img src="./screenshots/screenshot-2-inspect.png" alt="Inspect Mode" width="720" />
</p>

### 2. Annotate / 메모
Leave a note — *"Make this 16px"* or *"Align to grid"*. Stack as many notes as you need.

메모를 남기세요 — *"패딩 24px로"*, *"그리드에 맞춰"*. 원하는 만큼 쌓을 수 있습니다.

### 3. Copy to AI / AI에게 전달
One click copies all notes with full component context. Paste into Claude Code, Cursor, or any AI agent.

클릭 한 번으로 전체 컴포넌트 컨텍스트와 함께 모든 노트를 복사합니다. Claude Code, Cursor 등 아무 AI 에이전트에 붙여넣으세요.

<p align="center">
  <img src="./screenshots/screenshot-3-annotate.png" alt="Annotate & Copy" width="720" />
</p>

---

## Features / 주요 기능

| Feature | Description |
|---------|-------------|
| **Component Tree** | Reads React fiber — component names, source file paths, and line numbers. React fiber를 읽어 컴포넌트 이름, 소스 파일 경로, 라인 번호를 표시합니다. |
| **Computed Styles** | Shows resolved CSS values and detects spacing overlaps between parent and child. 계산된 CSS 값을 보여주고, 부모-자식 간 간격 겹침을 감지합니다. |
| **QA Notes** | Leave plain-language notes on any element. Site-level copy and delete from the popup. 아무 요소에 자연어 메모를 남기세요. 팝업에서 사이트별 복사·삭제가 가능합니다. |
| **One-Click Copy** | Exports all notes with full context — tree, styles, source paths — formatted for AI agents. 트리, 스타일, 소스 경로 등 전체 컨텍스트를 AI 에이전트용 포맷으로 내보냅니다. |
| **Zero Config** | Works on any React site — production or localhost. No project setup required. 아무 React 사이트에서 동작합니다. 프로젝트 설정이 필요 없습니다. |

---

## Installation / 설치 방법

> Chrome Web Store is currently under review. In the meantime, install manually:
> 크롬 웹 스토어 심사 중입니다. 그동안 수동 설치 방법:

### 1. Download / 다운로드

Download **[pokeit-extension.zip](./pokeit-extension.zip)** from this repository.

이 레포에서 **[pokeit-extension.zip](./pokeit-extension.zip)**을 다운로드합니다.

### 2. Unzip / 압축 해제

Extract the zip file to any folder.

zip 파일의 압축을 아무 폴더에 풀어주세요.

### 3. Load in Chrome / Chrome에 로드

1. Open `chrome://extensions` / `chrome://extensions` 열기
2. Enable **Developer mode** (top right toggle) / 우측 상단 **개발자 모드** 켜기
3. Click **Load unpacked** / **압축해제된 확장 프로그램을 로드합니다** 클릭
4. Select the extracted folder / 압축 해제한 폴더 선택

### 4. Done! / 끝!

Click the POKEIT icon on any webpage to start inspecting.

아무 웹페이지에서 POKEIT 아이콘을 클릭하면 바로 시작됩니다.

---

<p align="center">
  <b>No account required · Works instantly · 100% free</b><br/>
  계정 불필요 · 즉시 사용 · 완전 무료
</p>

<p align="center">
  <a href="https://pokeit.app">pokeit.app</a>
</p>
