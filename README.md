# Venture Operations & AI Automation Portfolio
### Yoona Heo | 허유나

**ERP Development · AI-assisted Operations · Document Automation**

초기기업 액셀러레이팅 실무에서 반복적으로 발생하는 기업정보 조회, 미팅 기록, 후속 업무 관리와 보고 과정을 어떻게 시스템화할 수 있을지 고민했습니다. 이 저장소는 하임벤처투자에서 수행한 **업무 자동화와 내부 시스템 설계·개발 경험**을 설명하는 개인 기술 포트폴리오입니다.

원본 회사 소스코드나 실제 기업 데이터는 포함하지 않습니다. 프로젝트의 주요 기능은 원본 구현 파일을 확인한 범위에서 작성했고, **구현된 기능과 운영 중인 기능을 구분**했습니다.

## Projects

| 프로젝트 | 해결하려는 문제 | 작업 내용 |
|---|---|---|
| **[01 · Venture Operations ERP](projects/01-venture-operations-erp.md)** | 기업·미팅·투자연계·후속업무 정보의 분산 | 데이터 구조 설계, 기업 중심 관리 화면 및 워크플로 구현 |
| **[02 · AI Operations Automation](projects/02-ai-operations-automation.md)** | 반복 점검, 보고 및 후속 업무 누락 | AI 회의 요약, 할 일 연결, 일일 점검·주간 보고 로직 |
| **[03 · Meeting Minutes Automation](projects/03-meeting-minutes-automation.md)** | 회의록 문서 작성 및 Slack 공유의 반복 작업 | JSON 기반 DOCX 생성, Slack 봇 게시·파일 첨부 흐름 |

## Approach

**실무 문제 발견 → 정보·업무 구조화 → 기능 구현 → 반복 개선**

업무의 효율을 높이기 위해서는 단순히 자동화 도구를 추가하기보다, 어떤 정보가 언제 누구에게 필요한지 먼저 정리해야 한다고 생각했습니다. 기업별 활동 기록이 다음 행동으로 이어지도록 데이터와 사용자 화면을 연결하고, 반복적인 문서·보고 업무를 자동화하는 방향으로 프로젝트를 진행했습니다.

## Technology

- **Web & Database:** Next.js, React, TypeScript, Supabase, SQL
- **AI & Workflow:** Google Gemini, 업무 모니터링·보고 루틴
- **Documents & Integration:** Python, JSON, OOXML/DOCX, Bash, Slack Web API

## Scope & Accuracy

- ERP의 대표 구현 파일과 회의록 자동화 관련 실제 소스 및 예제 실행을 확인했습니다.
- AI 직원 설정상 일일 점검·주간 보고는 `active`, 음성 기반 기록·시스템 개선 역할은 `planned`로 구분되어 있습니다.
- 일부 투자 딜 관련 화면에는 목업 데이터가 존재하며, 실제 투자 집행을 자동화했다고 주장하지 않습니다.
- 프로젝트별 실제 가동률, 업무시간 절감 효과 및 전체 코드 기여도는 별도 검증하지 않았습니다.
- 실제 회의록, 투자자료, 개인정보, API 키, 원본 회사 코드 및 내부 운영 문서는 포함하지 않습니다.

[LinkedIn](https://www.linkedin.com/in/imyoonaheo/)
