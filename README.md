# 강기현 (Chera Kang)
> **11년 차 시니어 QA 엔지니어 & 테스트 자동화 스페셜리스트**  
> 탄탄한 엔지니어링과 데이터 기반의 품질 관리로 빠르고 안정적인 제품 릴리즈 파이프라인을 구축합니다.

---

## 📌 프로젝트 개요

| 프로젝트 | 대상 도메인 및 개요 | 핵심 구현 및 기술 포인트 |
|---|---|---|
| **[Parmple](https://github.com/Chera-Kang/Parmple)** | B2B 제약 CSO ERP 서비스 | Playwright E2E 회귀 자동화, AI 로케이터 자가치유, Figma 명세 기반 테스트케이스 자동 설계 |
| **[Jira Analytics](https://github.com/Chera-Kang/JiraAnalytics)** | 결함 라이프사이클 및 품질 관리 | 결함 재오픈율 및 해결 소요일수 추적, 실시간 품질 가시성 대시보드 |
| **[Apex Info](https://github.com/Chera-Kang/Apex)** | 에이펙스 레전드 게임 데이터 & 전술 도구 | 기획-개발-검증 3단계 라이프사이클, 위키 크롤링 데이터 수치 정합성 검증 엔진 |

---

## 🛠 핵심 기술 스택 및 도구

- **테스트 자동화**: Python 3, Playwright, Pytest, Robot Framework, Appium, Airtest
- **프레임워크 및 아키텍처**: Pytest Fixture (다중 세션 격리), REST API 연동 및 모킹, Allure Report, Playwright Trace Viewer
- **품질 거버넌스 및 운영**: Jira (결함 워크플로우 표준화), Jira Analytics (Google Spreadsheet & GViz API 대시보드), 애자일 스크럼
- **AI 활용 QA**: Figma REST API 연계 테스트케이스 자동 설계 및 Google Gemini 기반 로케이터 자가치유 파이프라인

---

## 📌 주요 프로젝트 상세

### 1. [Parmple](https://github.com/Chera-Kang/Parmple)
> **B2B 제약 CSO ERP 서비스를 위한 E2E 테스트 자동화 & AI 자가치유 파이프라인**

- **배경 및 과제**: 복잡한 B2B 다중 권한 환경에서의 회귀 검증 병목 및 UI 변경에 따른 잦은 스크립트 실패 문제 해결
- **핵심 기술 및 구현**:
  - **Python + Playwright 기반 전면 전환**: 핵심 비즈니스 도메인 E2E 회귀 테스트 자동화 파이프라인 구축 및 안정화
  - **AI 기반 로케이터 자가치유**: 런타임 UI 변경으로 셀렉터 실패 시, 에러 시점의 DOM과 화면을 분석하여 대체 로케이터를 제안받아 테스트 중단 방지
  - **Figma 명세 기반 테스트케이스 자동 설계**: Figma REST API를 연계하여 기획 명세 기반 사용자 여정 자동 탐색 및 테스트케이스 자동화
  - **완전 무인화 테스트 환경**: 실시간 백그라운드 이메일 OTP 파싱 및 관리자 REST API 연동을 통한 사전/사후 조건 자동화
  - **결함 추적성 강화**: Allure Report 및 Playwright Trace Viewer(비디오/DOM 스냅샷) 연계를 통한 빠른 디버깅 체계
- **산출물 및 시연 링크**:
  - 🎬 [[Web] Playwright + Pytest 16개 핵심 도메인 회귀 테스트 시연](https://youtu.be/t7XDqr4cbYw)
  - 🎬 [[Web] AI 활용 3단계 점진적 TC 자동 설계 및 검증 시연](https://youtu.be/mywifH10t74)
  - 🎬 [[App] Android 하이브리드 앱 Appium 스모크 테스트 시연](https://youtu.be/AGG6c-pH-6g)
  - 📁 [테스트 결과 리포트 및 산출물 샘플 (Google Drive)](https://drive.google.com/drive/folders/1DHx_hG_0kR07e8FNK_DZIVcNYrUpTyi0)

---

### 2. [Jira Analytics](https://github.com/Chera-Kang/JiraAnalytics)
> **Jira 결함 라이프사이클 표준화 및 실시간 품질 지표 분석 대시보드**

- **배경 및 과제**: 반복적인 엑셀 수동 리포팅 리소스 낭비를 없애고, 주관적 감에 의존하던 배포 승인 프로세스 개선
- **핵심 기술 및 구현**:
  - **실시간 서버리스 데이터 파이프라인**: Google Apps Script와 GViz API를 연동하여 서버 비용 없는 실시간 데이터 집계 구조 구축
  - **정량적 품질 지표 추적**: 결함 재오픈율, 평균 해결 소요일수, 심각도 분포 기반의 객관적 배포 승인 기준 정립
  - **4대 심층 분석 뷰**: 전체 개요(Main), 5종 연동 필터 심층 분석(DetailedStats), 개인별 기여도(MemberStats), 로드맵(Roadmap)
  - **데이터 보안 및 비식별화**: 외부 포트폴리오 공개 시 사내 기밀 유출을 방지하기 위한 텍스트 블러 마스킹 처리
- **산출물 링크**:
  - 🌐 [Jira Analytics 웹 대시보드](https://jira-analytics.pages.dev)

---

### 3. [Apex Info](https://github.com/Chera-Kang/Apex)
> **에이펙스 레전드(Apex Legends) 게임 데이터 분석 및 기획-개발-검증 3단계 R&D 샌드박스**

- **배경 및 과제**: 사후 수동 검증의 한계를 벗어나, 기획 단계부터 데이터 규격과 검증 로직을 사전에 정의하는 Shift-Left 품질 활동 실증
- **핵심 기술 및 구현**:
  - **Shift-Left 품질 보증**: 기획(PRD) 단계에서 데이터 규격(JSON 스키마)과 완료 기준 사전 정의
  - **데이터 파이프라인 모듈화**: 공식 위키 마이닝 크롤러 및 순수 연산 엔진 격리 설계
  - **총기 수치 정합성 자동 검증 (`verify_weapons.py`)**: 인게임 물리 규칙(헤드샷 데미지 ≥ 몸통 데미지 ≥ 다리 데미지, 연사력 기반 DPS 검증)을 단정문으로 자동 검증하여 데이터 오타 및 패치 내역 자동 감지
- **산출물 링크**:
  - 🌐 실시간 웹 대시보드 (배포 준비 중)

---

## 🔗 포트폴리오 및 산출물

- 📁 **포트폴리오 및 산출물 모음**: [Google Drive 바로가기](https://drive.google.com/drive/folders/1DHx_hG_0kR07e8FNK_DZIVcNYrUpTyi0)
