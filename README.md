<p align="center">
  <img src="./brand/ploto-app-icon.svg" alt="Ploto" width="76" height="76" />
</p>

<h1 align="center">Ploto</h1>

<p align="center">
  AutoCAD · AutoCAD LT 도곽 자동 인식 A3 일괄 PDF 출력 데스크톱 앱
</p>

---

## 설치 방법

1. 오른쪽 **[Releases](https://github.com/moontomoon119/ploto/releases/latest)** 페이지에서 최신 **`Ploto-Setup-<버전>.exe`** 파일만 내려받아 실행합니다.
   - `.blockmap`, `latest.yml`, `Source code` 파일은 내려받으실 필요 없습니다.
   - Python이나 .NET을 따로 설치하지 않아도 바로 동작합니다.
2. 최초 실행 시 Windows 보안 경고(*"Windows의 PC 보호"*)가 뜨면 **추가 정보 → 실행**을 누릅니다.
3. 설치가 끝나면 바탕화면의 **Ploto** 아이콘으로 실행합니다.

---

## 주요 특징

- **AutoCAD 정식판 & AutoCAD LT 전 버전 지원** — LISP 없이 순수 스크립트(`.scr`)로 동작하며, 영문판·한글판 용지명을 자동 인식합니다.
- **원본 파일 보호** — 모든 DWG는 읽기 전용으로만 접근하며, 원본 폴더를 수정하거나 임시 파일을 남기지 않습니다.
- **고속 멀티엔진 분할 출력** — 도곽이 많은 도면도 여러 CAD 엔진에 자동 분할해 빠르게 A3 PDF로 출력합니다.
- **전역 + 도면별 CTB 영구 기억** — 기본 CTB 외에 특정 도면만 별도 CTB로 지정하면 다음 실행 때도 그대로 유지됩니다.
- **한눈에 보는 도곽 타일 & 책갈피 병합 PDF** — 도곽별 성공/확인필요/실패 상태를 타일로 확인하고, 도면번호순 책갈피가 포함된 통합 PDF를 함께 생성합니다.
- **라이트 / 다크 테마 & 자동 업데이트** — 앱을 열 때마다 최신 버전을 자동 확인해 상단 버튼으로 간편하게 업데이트할 수 있습니다.

---

## 실행 환경

- **OS**: Windows 10 / 11 (64-bit)
- **필수 프로그램**: AutoCAD 또는 AutoCAD LT 설치 (정식판 / LT 다연도 · 한/영 호환)

---

## Brand Assets (`brand/`)

- `brand/ploto-logo.svg` — 정적 모노크롬 로고 (`64×64`, Roll Spiral)
- `brand/ploto-app-icon.svg` — 앱 아이콘
- `brand/ploto-loader.svg` — 단독 SVG 로딩 애니메이션
- `brand/ploto-brand-component.html` — 인터랙티브 로고/로더 참고 컴포넌트
