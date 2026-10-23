# 제3자 저작권과 라이선스

Baton은 여러 오픈소스 구성요소를 사용합니다. 아래 구성요소의 권리는 각각의 저작자에게 있으며, **Baton의 개인용 제한·복제 금지가 해당 라이선스의 권리를 축소하지 않습니다.**

전체 수집 목록, 정확한 버전, 패키지 출처와 동봉 고지 원문은 [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt)에 있습니다. 같은 원문은 한 번 보관하고 각 패키지에서 해당 원문 번호를 참조합니다.

## 주요 구성요소

| 구성요소 | 사용 영역 | 공급자 선언 라이선스 |
| --- | --- | --- |
| [Tauri](https://github.com/tauri-apps/tauri)와 플러그인 | Windows 앱, 창, 알림, 업데이트 등 | MIT 또는 Apache-2.0 등 패키지별 고지 |
| [Svelte](https://github.com/sveltejs/svelte) | 화면 구성 | MIT |
| [CodeMirror](https://codemirror.net/)·Lezer | 코드 편집·문법 강조·변경 비교 | MIT |
| [xterm.js](https://github.com/xtermjs/xterm.js) | 터미널 화면 | MIT |
| [Three.js](https://github.com/mrdoob/three.js) | 지원 3D 파일 보기 | MIT |
| [SQLite](https://sqlite.org/copyright.html)·rusqlite | 로컬 기록 보관 | SQLite는 public domain, Rust 바인딩은 별도 라이선스 |
| [portable-pty](https://github.com/wezterm/wezterm) | 터미널 프로세스 연결 | MIT |
| [Vite](https://github.com/vitejs/vite)·Rolldown | 화면 빌드 도구 | MIT 및 포함된 별도 고지 |
| Rust 생태계의 간접 의존성 | 직렬화·통신·파일 감시·창 처리 등 | MIT, Apache-2.0, BSD, ISC, MPL-2.0, Unicode 등 |

## 원본 소스와 MPL-2.0

수집 목록의 **원본 패키지** 주소는 고정 버전의 npm 패키지 또는 crates.io 소스 배포본입니다. MPL-2.0 구성요소도 해당 주소에서 원본 소스를 받을 수 있습니다. 현재 해당 원본에 Baton 전용 소스 수정을 적용하지 않았습니다.

| MPL-2.0 구성요소 | 해당 버전 소스 |
| --- | --- |
| cssparser 0.37.0 | [소스 패키지](https://crates.io/api/v1/crates/cssparser/0.37.0/download) |
| cssparser-macros 0.7.1 | [소스 패키지](https://crates.io/api/v1/crates/cssparser-macros/0.7.1/download) |
| dtoa-short 0.3.5 | [소스 패키지](https://crates.io/api/v1/crates/dtoa-short/0.3.5/download) |
| option-ext 0.2.0 | [소스 패키지](https://crates.io/api/v1/crates/option-ext/0.2.0/download) |
| selectors 0.38.0 | [소스 패키지](https://crates.io/api/v1/crates/selectors/0.38.0/download) |

이 구성요소에는 [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/)을 따르는 사용·수정·배포·소스 접근 권리가 있습니다. Baton 고유 코드의 비공개 정책과 구분합니다. 소스 접근에 문제가 있으면 [배포 저장소 Issues](https://github.com/JellyDuke/Baton-Releases/issues)로 알려 주세요.

## 수집 범위와 보완 사항

현재 목록은 앱 버전 `0.2.0`의 잠금 파일, Windows용 Cargo 메타데이터, 설치된 npm 패키지를 읽어 작성했습니다. 간접 의존성과 빌드 도구도 포함하며 모든 항목이 최종 설치 파일에 포함된다는 의미는 아닙니다. 법률 검토나 모든 실행 환경에 대한 완전한 라이선스 감사 완료를 뜻하지 않습니다.

패키지에 원문 파일이 빠진 경우 해당 배포 커밋의 공식 저장소 또는 동봉 상위 패키지에서 보완했습니다. `is-reference`와 `locate-character`는 원 배포본에 MIT 선언만 있어 패키지 작성자·원본 출처·표준 MIT 본문을 함께 기록했습니다. 원본에 없는 저작권 연도나 문구를 추정해 넣지 않았습니다.

WebView2 Runtime, Git, AI CLI, 선택한 스킬·MCP 서버와 외부 서비스는 별도 설치·연결 대상입니다. 각각의 라이선스와 이용 조건을 따르며 Baton의 개인용 사용권에 포함되는 것으로 보지 않습니다.

## 고지 수정

누락·잘못된 출처·추가 고지 필요 사항이 있다면 [Issues](https://github.com/JellyDuke/Baton-Releases/issues)에 해당 구성요소와 근거를 알려 주세요. 원래 권리자의 조건이 이 요약보다 우선합니다.
