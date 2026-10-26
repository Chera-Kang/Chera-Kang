# 강기현 (Chera Kang)
> **Senior QA & Test Automation Engineer**  
> 탄탄한 엔지니어링과 데이터 기반의 품질 관리로 신뢰도 높은 소프트웨어 릴리즈 환경을 구축합니다.

---

## 📌 주요 프로젝트

### 1. [Parmple](https://github.com/Chera-Kang/Parmple)
> **B2B 제약 CSO ERP 서비스를 위한 Playwright 기반 E2E 테스트 자동화 & AI 자가치유 파이프라인**

- **다중 권한 세션 물리 격리**: Pytest Fixture를 활용해 CSO, 제약사, 관리자 간 BrowserContext를 독립 분리하여 세션 간섭 및 간헐적 실패 차단
- **OTP 실시간 파싱 & Admin API**: IMAP 메일함 조회 기반 실시간 OTP 자동 파싱 및 관리자 REST API 연동 자동화
- **AI 자가치유 (Self-Healing)**: UI 변경으로 인한 에러 발생 시 AI가 에러 시점의 DOM과 화면을 분석해 대체 셀렉터로 자동 복구
- **시연 및 산출물**:
  - 🎬 [[Web] Playwright + Pytest 16개 핵심 도메인 회귀 테스트 시연](https://youtu.be/t7XDqr4cbYw)
  - 🎬 [[Web] AI 활용 3단계 점진적 TC 자동 설계 및 검증 시연](https://youtu.be/mywifH10t74)
  - 🎬 [[App] Android 하이브리드 앱 Appium 스모크 테스트 시연](https://youtu.be/AGG6c-pH-6g)
  - 📁 [Allure 테스트 결과 리포트 및 산출물 샘플 (Google Drive)](https://drive.google.com/drive/folders/1DHx_hG_0kR07e8FNK_DZIVcNYrUpTyi0)

---

### 2. [Jira Analytics](https://github.com/Chera-Kang/JiraAnalytics)
> **Jira 결함 라이프사이클 표준화 및 Zero-Cost 실시간 품질 모니터링 대시보드**

- **Serverless 실시간 파이프라인**: 별도 DB/서버 없이 Google Spreadsheet와 GViz API를 연동하여 인프라 비용 0원 동기화 구현
- **품질 지표 추적 및 관리**: 결함 재오픈율(Reopen Rate)과 해결 소요일수(Lead Time)를 실시간 추적하여 반복 결함 및 처리 지연 방지
- **4대 심층 분석 뷰**: 전체 개요(Main), 5종 연동 필터 심층 통계(DetailedStats), 역할별 기여도(MemberStats), 로드맵(Roadmap)
- **데이터 보안 마스킹**: 민감한 내용 블러 및 비식별화 처리
- 🌐 [Jira Analytics 실시간 웹 대시보드 바로가기](https://jira-analytics.pages.dev)

---

### 3. [Todays Coffee](https://github.com/Chera-Kang/todays-coffee)
> **국내 8대 커피 프랜차이즈 음료·원두 큐레이션 및 일일 카페인 트래킹 에디토리얼 웹 서비스**

- **맞춤 큐레이션 & 2-Tier 탐색 엔진**: 8대 브랜드 45종 음료 데이터를 기반으로 컨디션별 맞춤 큐레이션(야근, 제로슈거, 디카페인, 운동 전) 및 6종 복합 정렬·필터링 제공
- **원두 가이드 & 브랜드 비교 인포그래픽**: 12종 원두 프로파일링(산미·바디감·로스팅) 및 8대 브랜드 아메리카노 기준 용량·가격·100ml당 단가 비교
- **카페인 트래커 & 숙면 가이드 (CRUD)**: 일일 권장량(400mg) 게이지, 체내 반감기 기반 숙면 안심 컷오프 시간 안내, 자정(00:00) 자동 리셋 및 테이스팅 메모 영속화
- **No-Backend & 모바일 퍼스트 UX**: 정규화된 JSON SSOT 아키텍처, 29CM/화해 감성 에디토리얼 UI, 메뉴별 해시 라우팅(`#drink-{id}`) 및 모바일 뒤로가기 모달 제어
- 🌐 [Todays Coffee 웹 서비스 바로가기](https://todays-coffee.pages.dev/)

---

## 🛠 핵심 기술 스택

- **Test Automation**: Python 3, Playwright, Pytest, Appium, Allure Report, Playwright Trace Viewer
- **Frontend & Dashboard**: React 19, JavaScript (ES6+), Tailwind CSS v4, HTML5/CSS3, Cloudflare Pages, GViz API
- **QA Governance & Methods**: Jira 결함 라이프사이클 표준화, CTM(분류트리기법) 테스트 설계, 애자일 스크럼
- **AI-Assisted QA**: Figma REST API 명세 파싱 및 Google Gemini API 기반 로케이터 자가치유 파이프라인
