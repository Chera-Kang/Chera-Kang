# 강기현 (Chera Kang)
> **Senior QA & Test Automation Engineer**  
> 탄탄한 엔지니어링과 데이터 기반의 품질 관리로 신뢰도 높은 소프트웨어 릴리즈 환경을 구축합니다.

---

## 📌 주요 프로젝트

### 1. [Parmple](https://github.com/Chera-Kang/Parmple)
> **B2B 제약 CSO ERP 서비스를 위한 Playwright 기반 E2E 테스트 자동화 프레임워크**

- **다중 권한 세션 격리**: Pytest Fixture 기반 CSO·제약사·관리자 독립 `BrowserContext` 구성으로 세션 간섭 및 Flaky 방지
- **이메일 OTP 자동 파싱 & Admin API**: IMAP4 메일함 주기적 조회로 OTP 파싱 및 Admin API 기반 사전 데이터 셋업 자동화
- **실패 관측성 및 신속한 디버깅**: Allure Report 및 실패 시점의 Playwright Trace Viewer 연계를 통한 결함 추적성 확보
- **시연 영상**:
  - 🎬 [[Web] Playwright + Pytest 16개 핵심 도메인 회귀 테스트 시연 영상](https://youtu.be/t7XDqr4cbYw)
  - 🎬 [[App] Android 하이브리드 앱 Appium 스모크 테스트 시연 영상](https://youtu.be/AGG6c-pH-6g)

---

### 2. [Jira Analytics](https://github.com/Chera-Kang/JiraAnalytics)
> **Jira 결함 라이프사이클 표준화 및 Zero-Cost 실시간 품질 모니터링 대시보드**

- **Serverless 실시간 파이프라인**: 별도 DB/서버 없이 Google Spreadsheet와 GViz API를 연동하여 인프라 비용 0원 동기화 구현
- **데이터 심층 분석 및 거버넌스**: 결함 재오픈율(Reopen Rate)과 우선순위별 해결 소요일수(Lead Time) 추적으로 반복 결함 및 병목 식별
- **4대 심층 분석 뷰**: 전체 개요(Main), 필터 세부 통계(DetailedStats), 역할별 기여도(MemberStats), 릴리즈 버전 분석(Roadmap)
- **데이터 보안 마스킹**: 외부 포트폴리오 공개를 위한 민감 이슈 데이터 비식별화 및 UI 블러 처리
- 🌐 [Jira Analytics 실시간 웹 대시보드 바로가기](https://jira-analytics.pages.dev)

---

### 3. [Todays Coffee](https://github.com/Chera-Kang/todays-coffee)
> **커피 큐레이션 웹 서비스 & Playwright E2E 테스트베드 (17 TCs)**

- **E2E 회귀 테스트 스위트 (17 TCs)**: Python Playwright + Pytest 기반으로 클라이언트 주요 상태와 엣지 케이스를 검증하는 8대 테스트 스위트 구축
- **BrowserContext 세션 격리**: Pytest Fixture(`scope="function"`) 기반 독립 세션 구성으로 LocalStorage 데이터 간섭 및 Flaky 방지
- **실패 시점 Trace 자동 수집 & 디버깅**: 테스트 실패(FAILED) 시점에만 Playwright Trace(`.zip`)를 자동 저장하여 결함 추적 시간 단축 및 Allure Report 연동
- **핵심 시나리오 및 엣지 케이스 검증**: BVA 경계값 분석(카페인 400mg 초과 경고 UI 전이), 메모 CRUD 입력값 예외 방어 및 새로고침 유지, 시간 제어(자정 00:00 로컬스토리지 초기화) 및 해시 라우팅 검증
- **No-Backend 웹 아키텍처**: React 19 + Tailwind CSS 기반 순수 클라이언트 웹 애플리케이션 (8대 브랜드 45종 음료 및 12종 원두 JSON 데이터 연동)
- **시연 및 산출물 바로가기**:
  - 🎬 [[VOD] Playwright E2E 회귀 테스트 시연 영상 (Allure & Trace Viewer)](https://youtu.be/kdgQ6l0w_JI)
  - 📁 [Allure Report 및 Playwright Trace 결과 산출물 (Google Drive)](https://drive.google.com/drive/folders/1PykjxS6gSBaLlbLu98dLLxI5iT5WbGNU)
  - 🌐 [Todays Coffee 웹 서비스 바로가기](https://todays-coffee.pages.dev/)

---

## 🛠 핵심 기술 스택

- **Test Automation**: Python 3, Playwright, Pytest, Appium, Allure Report, Playwright Trace Viewer
- **Frontend & Dashboard**: React 19, JavaScript (ES6+), Tailwind CSS, Vite, Cloudflare Pages, GViz API
- **QA Governance & Methods**: Jira 결함 라이프사이클 표준화, 릴리즈 게이트(Release Gate) 수립, 경계값 분석(BVA), 애자일 스크럼
