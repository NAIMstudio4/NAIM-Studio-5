# NAIM Studio v5

NovelAI 이미지 생성을 브라우저에서 바로 쓰는 모바일 우선 HTML 클라이언트입니다. 단일 HTML 파일로 동작하며, PWA로 설치하면 오프라인에서도 열립니다.

## 사용 방법

### 1) 바로 쓰기 (파일 열기)
`NAIM_Studio_v5.html` 파일을 다운로드해 브라우저로 열면 됩니다.

### 2) PWA 설치 (권장)
GitHub Pages 주소로 접속한 뒤 브라우저의 "홈 화면에 추가 / 앱 설치"를 누르면 앱처럼 설치됩니다. 설치 후에는 오프라인에서도 실행됩니다.

- 설정(Settings) > Pages 에서 배포 브랜치를 `main`, 폴더를 `/ (root)` 로 지정하세요.
- 접속 주소: `https://<owner>.github.io/NAIM-Studio-5/NAIM_Studio_v5.html`

## 구성 파일

| 파일 | 용도 |
|---|---|
| `NAIM_Studio_v5.html` | 본체 (단일 HTML) |
| `manifest.json` | PWA 매니페스트 |
| `sw.js` | 서비스 워커 (오프라인 캐싱) |
| `icon-192.png`, `icon-512.png` | 앱 아이콘 |

## v4 데이터 호환

v4에서 쓰던 프리셋·설정·갤러리 데이터는 v5에서 그대로 인식됩니다(동일 IndexedDB / 저장 스키마 유지). 같은 브라우저·같은 접속 경로에서 열면 기존 데이터가 이어집니다.

## 가이드

(아카라이브 게시글 링크)
