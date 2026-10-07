# 강기현 (Chera Kang)
> **11-Year Senior QA Engineer & Test Automation Specialist**  
> 탄탄한 엔지니어링과 데이터 기반의 품질 관리로 빠르고 안정적인 제품 릴리즈 파이프라인을 구축합니다.

[![Portfolio Hub](https://img.shields.io/badge/Portfolio-QA_Engineering_Hub-blue?style=for-the-badge)](https://github.com/Chera-Kang)
[![Live Demo](https://img.shields.io/badge/Jira_Analytics-Live_Demo-success?style=for-the-badge&logo=cloudflarepages&logoColor=white)](https://jira-analytics.pages.dev)
[![Demos](https://img.shields.io/badge/YouTube-Automation_Demos-red?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/t7XDqr4cbYw)

---

## 📌 Projects at a Glance

| 프로젝트 | 도메인 & 핵심 성격 | 주요 엔지니어링 성과 | 바로가기 |
|---|---|---|:---:|
| **[Parmple](#1-parmple-e2e-automation-framework)** | B2B 제약 CSO ERP E2E 자동화 | **회귀 시간 82% 단축**, 세션 격리(Flaky <0.8%), AI 자가치유 | [📂 Repo](https://github.com/Chera-Kang/Parmple) · [🎬 영상](https://youtu.be/t7XDqr4cbYw) · [📁 드라이브](https://drive.google.com/drive/folders/1DHx_hG_0kR07e8FNK_DZIVcNYrUpTyi0) |
| **[Jira Analytics](#2-jira-analytics-dashboard)** | 결함 라이프사이클 & 품질 대시보드 | **실시간 품질 가시성**, Reopen Rate 기반 Go/No-Go 판정 | [📂 Repo](https://github.com/Chera-Kang/JiraAnalytics) · [🌐 Live Demo](https://jira-analytics.pages.dev) |
| **[Apex](#3-apex-engineering-sandbox)** | 기획-개발-검증 3단계 R&D 샌드박스 | **Shift-Left 품질 보증**, 물리 불변성 수학 검증 엔진 | [📂 Repo](https://github.com/Chera-Kang/Apex) |

---

## 🛠 핵심 기술 스택 & 엔지니어링 도구

- **Test Automation**: Python 3, Playwright, Pytest, Robot Framework, Appium, Airtest
- **Framework & Architecture**: Pytest Fixture (Multi-tenant Session Isolation), REST API Mocking/Integration, Allure Report, Playwright Trace Viewer
- **Quality & Ops**: Jira (Workflow/Lifecycle 표준화), Jira Analytics (GViz API / Apps Script Dashboard), WBS & KPT Agile Scrum
- **AI-Assisted QA**: Figma REST API 연계 AI 프롬프트 기반 Testcase 자동 설계 및 Google Gemini 기반 로케이터 자가 치유(Self-Healing) 파이프라인

---

## 📌 주요 프로젝트 상세 (Featured Projects)

### 1. [Parmple E2E Automation Framework](https://github.com/Chera-Kang/Parmple)
> **B2B 제약 CSO ERP 서비스를 위한 엔터프라이즈급 E2E 테스트 자동화 & AI 자가치유 파이프라인**

- **문제 정의**: 기존 Robot Framework/Selenium 환경의 느린 속도(1시간 40분), 다중 권한 간 세션 간섭으로 인한 Flaky(18.5%), OTP/승인 수동 개입 병목 해결
- **핵심 기술 솔루션**:
  - **Python + Playwright 전면 마이그레이션**: 회귀 테스트 소요 시간 **82% 단축 (18분)**
  - **Multi-tenant Session Isolation**: Pytest Fixture 기반 CSO 1~3, 제약사 1~2, 관리자 세션 완전 물리 격리 (**Flaky 0.8% 미만**)
  - **Zero-touch 완전 무인화**: 백그라운드 실시간 OTP 파싱(`email_reader.py`) 및 관리자 REST API(`admin_api.py`) 연동으로 Setup/Teardown 100% 무인화
  - **AI-Assisted Self-Healing & Figma-to-Code**: Figma REST API 기반 워크플로우 자동 완전 탐색 및 Gemini AI 기반 로케이터 자가치유 엔진 구축
  - **3-in-1 Observability**: Allure Report + Playwright Trace Viewer(비디오/DOM 스냅샷) 연계 장애 원인 규명 시간 85% 단축
- 🔗 **상세 링크**: [GitHub Repository](https://github.com/Chera-Kang/Parmple) | [Playwright 회귀 테스트 시연(YouTube)](https://youtu.be/t7XDqr4cbYw) | [AI 3단계 TC 검증 시연(YouTube)](https://youtu.be/mywifH10t74)

---

### 2. [Jira Analytics Dashboard](https://github.com/Chera-Kang/JiraAnalytics)
> **Jira 결함 라이프사이클 표준화 및 실시간 품질 지표(Quality Metrics) 분석 대시보드**

- **문제 정의**: 엑셀 수동 취합으로 인한 주당 3.5시간 리포팅 리소스 낭비 및 주관적 직관에 의존하던 릴리즈 승인 프로세스 개선
- **핵심 기술 솔루션**:
  - **서버리스 실시간 데이터 파이프라인**: Google Apps Script ➔ Google Spreadsheet ➔ GViz API(Google Visualization API) 연동으로 서버 비용 0원 실시간 동기화
  - **정량적 품질 게이트(Quality Gate) 수립**: 결함 재오픈율(Reopen Rate), 해결 소요일수(MTTR), 심각도 분포 기반 **배포 승인(Go/No-Go) 체계** 정립
  - **4대 심층 분석 뷰**: 전체 개요(`Main`), 5종 연동 필터 심층 분석(`DetailedStats`), 개인별 기여도(`MemberStats`), 로드맵(`Roadmap`)
  - **Privacy by Design**: 포트폴리오 공개 시 사내 기밀 텍스트 블러 마스킹 처리 (통계 연산 무결성 100% 보존)
- 🔗 **상세 링크**: [GitHub Repository](https://github.com/Chera-Kang/JiraAnalytics) | [🌐 실시간 라이브 데모 바로가기](https://jira-analytics.pages.dev)

---

### 3. [Apex Engineering Sandbox](https://github.com/Chera-Kang/Apex)
> **기획(Spec) ➔ 모듈 개발(Dev) ➔ 검증 자동화(QA) 전 주기를 실험하고 체계화하는 R&D 샌드박스**

- **문제 정의**: 개발 이후 사후 수동 검증의 한계를 극복하고, 기획부터 데이터 계약과 테스트 오라클을 사전에 정립하는 Shift-Left 방법론 실증
- **핵심 기술 솔루션**:
  - **Shift-Left 품질 보증**: 기획(PRD) 단계에서 Data Contract(JSON 스키마)와 완료 기준(DoD) 사전 정의
  - **데이터 파이프라인 모듈화**: 공식 위키 마이닝 크롤러(BeautifulSoup) 및 순수 연산 엔진 격리 설계
  - **Test Oracle 기반 수학적 불변성 검증 엔진 (`verify_weapons.py`)**:
    인게임 물리 법칙($\text{Head} \ge \text{Body} \ge \text{Leg}$, $\text{DPS} \approx \text{Damage} \times \text{RPM} / 60$)을 자동 단정(Assert)하여 데이터 오염 및 패치 자동 감지
- 🔗 **상세 링크**: [GitHub Repository](https://github.com/Chera-Kang/Apex)

---

## 🔗 포트폴리오 산출물 & 시연 영상 (Resources)

- 📁 **테스트케이스 & 포트폴리오 샘플**: [Google Drive Folder](https://drive.google.com/drive/folders/1DHx_hG_0kR07e8FNK_DZIVcNYrUpTyi0)
- 🎬 **시연 영상 모음**:
  - [[Web] Playwright + Pytest 16개 핵심 도메인 회귀 테스트](https://youtu.be/t7XDqr4cbYw)
  - [[Web] AI 활용 3단계 점진적 TC 자동 설계 및 검증 (18개 E2E)](https://youtu.be/mywifH10t74)
  - [[App] Android 하이브리드 앱 Appium 스모크 테스트](https://youtu.be/AGG6c-pH-6g)
