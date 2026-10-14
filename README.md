# 강기현 (Chera Kang)
> **11년 차 시니어 QA 엔지니어 & 테스트 자동화 스페셜리스트**  
> 탄탄한 엔지니어링과 데이터 기반의 품질 관리로 신뢰도 높은 소프트웨어 릴리즈 환경을 구축합니다.

---

## 📌 주요 프로젝트

### 1. [Parmple](https://github.com/Chera-Kang/Parmple)
> **B2B 제약 CSO ERP 서비스를 위한 Playwright 기반 E2E 테스트 자동화 & AI 자가치유 파이프라인**

- **다중 권한 세션 물리 격리**: Pytest Fixture를 활용해 CSO, 제약사, 관리자 간 BrowserContext를 독립 분리하여 세션 간섭 및 간헐적 실패 차단
- **OTP 자동 파싱 & API Setup**: IMAP 기반 이메일 인증번호 실시간 자동 파싱 및 관리자 API 연계 테스트 사전 조건 자동화
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

### 3. [Apex Info](https://github.com/Chera-Kang/Apex)
> **에이펙스 레전드(Apex Legends) 게임 데이터 파이프라인 및 수치 정합성 자동 검증 토이 샌드박스**

- **데이터 ETL 자동화**: 공식 위키의 29종 무기 수치 및 최신 밸런스 패치 데이터를 크롤링하여 정규화 JSON으로 적재
- **수치 무결성 자동 검증 (`verify_weapons.py`)**: 헤드/바디 데미지 비율 및 연사력 기반 DPS 연산 정합성을 단정문(Assertion)으로 자동 검증
- **초경량 웹 뷰 (`index.html`)**: 검증된 무기 데이터를 손쉽게 필터링하고 조회할 수 있는 미니 웹 도감

---

## 🛠 핵심 기술 스택

- **Test Automation**: Python 3, Playwright, Pytest, Appium, Allure Report, Playwright Trace Viewer
- **Frontend & Dashboard**: React 19, JavaScript (ES6+), HTML5/CSS3, Cloudflare Pages, GViz API
- **QA Governance & Methods**: Jira 결함 라이프사이클 표준화, CTM(분류트리기법) 테스트 설계, 애자일 스크럼
- **AI-Assisted QA**: Figma REST API 명세 파싱 및 Google Gemini API 기반 로케이터 자가치유 파이프라인
