# 2026 크리스마스의 기적 지원사업 통합 공모 — 사업소개 웹페이지

부천희망재단 「크리스마스의 기적」 지원사업 안내 페이지입니다. GitHub Pages로 바로 게시할 수 있는 정적 웹페이지입니다.

## 파일 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 웹페이지 본문 (디자인 · 사업 데이터 · 탭 기능 포함) |
| `logo.png` | 부천희망재단 로고 |
| `.nojekyll` | GitHub Pages가 파일을 그대로 게시하도록 하는 설정 파일 |

## GitHub Pages로 게시하기

1. GitHub에 로그인한 뒤 오른쪽 위 **+ › New repository**를 눌러 저장소를 만듭니다.
   - 이름 예시: `christmas-miracle-2026`
   - **Public**으로 선택 (무료 계정은 Public 저장소만 Pages 게시 가능)
2. 새 저장소 화면에서 **uploading an existing file**을 눌러 이 폴더의 파일 3개(`index.html`, `logo.png`, `.nojekyll`)를 끌어다 놓고 **Commit changes**를 누릅니다.
   - `.nojekyll`은 숨김 파일이라 보이지 않으면 빼고 올려도 페이지는 정상 동작합니다.
3. 저장소의 **Settings › Pages**로 이동합니다.
4. **Build and deployment › Source**를 `Deploy from a branch`로, **Branch**를 `main` / `/ (root)`로 선택하고 **Save**를 누릅니다.
5. 1~2분 뒤 같은 화면 위쪽에 게시 주소가 표시됩니다.
   - 주소 형식: `https://<GitHub 아이디>.github.io/<저장소 이름>/`

## 내용 수정하기

- **사업별 문구**(지원대상, 제출서류, 심사기준 등): `index.html` 아래쪽 `<script>` 안의 `var P = [ ... ]` 부분을 고칩니다.
- **공고문 링크 주소**: `<script>` 안의 `NOTICE_URL` 한 줄만 고치면 버튼 3개에 모두 적용됩니다.
- **그 밖의 문구**(제목, 신청방법, 일정, 문의처 등): `index.html`의 `<template id="app-tpl">` 안에서 해당 글자를 찾아 고칩니다.
- GitHub 저장소에서 파일을 열고 연필(✏️) 아이콘으로 직접 고친 뒤 **Commit changes**를 누르면 1~2분 뒤 사이트에 반영됩니다.

## 문의

부천희망재단 사무국 · 032-321-9123~4 · hope9123@nate.com
