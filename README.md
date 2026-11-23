<div align="center">
  <img src="./assets/header.svg" width="100%" alt="Han Taewon" />

  <br />

  **데이터 흐름과 서비스 안정성을 고민하는 백엔드 개발자, 한태원입니다.**

  <br />

  <a href="https://github.com/hantawon123">
    <img src="https://img.shields.io/badge/GitHub-hantawon123-6D28D9?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=hantawon123&label=VISITORS&color=6D28D9&style=flat-square" alt="Profile views" />
</div>

## 👋 About me

- ⚙️ **Backend** · Java·Spring Boot와 TypeScript·NestJS로 서비스·DB를 설계하고 업무 API를 구현합니다.
- 🔍 **Performance & Reliability** · SQL과 트랜잭션 경계를 개선하고, 부하 테스트·운영 지표로 성능과 복구 동작을 검증합니다.
- 🧩 **Architecture & Operations** · 모놀리식과 MSA의 동작·성능을 비교하고, CI/CD 및 지표·로그 기반 관측 환경을 구성한 경험이 있습니다.

<p align="center">
  <a href="https://app.notion.com/p/3d888d0e227b8058886bd4639ee1bd2a">
    <img src="https://img.shields.io/badge/PORTFOLIO-6D28D9?style=for-the-badge&logo=notion&logoColor=white" alt="Notion 포트폴리오 보기" />
  </a>
  &nbsp;
  <a href="mailto:hantawon@naver.com">
    <img src="https://img.shields.io/badge/EMAIL-hantawon%40naver.com-0F766E?style=for-the-badge" alt="이메일 보내기: hantawon@naver.com" />
  </a>
</p>

## 🚀 Project Experience

### [DVA · 디버 기업 연계 자율 프로젝트](https://github.com/hantawon123/dver-dva)

AI 전화 상담과 택배 접수를 연결하는 업무 서비스<br>
**Backend · MSA 전환 · CI/CD·관제**

- NestJS·PostgreSQL 기반 고객·기업·통화·주문·결제 API를 구현하고, AI·PBX·결제·택배 서비스와 연동했습니다.
- 결제 응답 유실과 서버 재시작에 대비한 멱등 처리·결과 재조회·재처리 흐름을 구현하고, 목록 SQL과 중복 조회를 최적화했습니다.
- 업무 기능을 5개 MSA 서비스로 이식하여 Outbox/Inbox 기반 이벤트 처리와 원본 동작을 대조하고, Jenkins 검증·배포 및 Prometheus·Grafana·Loki 관제 환경을 구성했습니다.

**주요 기술** · TypeScript · NestJS · PostgreSQL · Docker · Kubernetes(k3s) · Jenkins · Prometheus · Grafana · Loki

> 10만 건 합성 데이터·단일 동시 요청 조건의 로컬 실험에서 고객 목록 API p95를 **577.28ms → 11.90ms**로 개선하고, 기존 응답·권한·검색·페이지 동작을 회귀 검증했습니다.

<details>
<summary>🎙️ VOMI · 음성 통화 확장 경험</summary>

NestJS·LiveKit 기반 통화 연결과 SSE 상태 전달, ElevenLabs 음성 합성 및 OmniVoice·FlashInfer 워커 연동을 진행했습니다. 로컬 GPU 워커와 Lightsail 간 SSH 터널의 자동 재연결을 구성하고 연결 복구를 확인했습니다.

</details>

### [MODERA](https://github.com/hantawon123/MODERA)

스크린샷 분석·분류 기반 지식 관리 서비스<br>
**Backend**

- 서비스·DB를 설계하고 Redis Streams 기반 비동기 분석 연동을 구현했습니다.
- 외부 인증과 DB 트랜잭션을 분리하여 연결 점유와 처리 흐름을 개선했습니다.
- k6 부하 테스트와 연결 풀 지표를 활용해 API 병목과 개선 결과를 검증했습니다.

**주요 기술** · Java · Spring Boot · PostgreSQL · Redis Streams · k6

### [Don't Touch Mine](https://github.com/hantawon123/Dont-touch-mine)

물건을 숨기고 찾는 멀티플레이 게임<br>
개발 완료 · **STOVE 배포 준비 중**<br>
**Game Server · GMS Backend**

- 전용 서버의 반복 연산·물리·시각 처리를 최적화했습니다.
- 참가자 상태와 재접속 처리 흐름을 구현했습니다.
- AI 하이라이트 선정 API에 시간 제한과 규칙 기반 대체 처리를 적용했습니다.

**주요 기술** · C# · Unity · Photon Fusion

## 🛠️ Tech stack

<div align="center">

  **Backend**

  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <br />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" />

  <br /><br />

  **Database**

  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />

  <br /><br />

  **Testing & Observability**

  <img src="https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white" alt="k6" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Loki" />

  <br /><br />

  **Infrastructure & CI/CD**

  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <br />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins" />

  <br /><br />

  **Collaboration**

  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />

  <br /><br />

</div>

<details>
<summary>🎮 Additional Experience · Game Development</summary>

C# · Unity · Photon Fusion

</details>

## 📊 GitHub Contributions

<div align="center">
  <a href="https://github.com/hantawon123?tab=overview">
    <img width="100%" src="https://ghchart.rshah.org/7c3aed/hantawon123" alt="한태원의 최근 1년 GitHub 기여 활동" />
  </a>
</div>

## 🧩 Algorithm

<div align="center">

<a href="https://solved.ac/profile/hantawon123">
    <img src="https://img.shields.io/badge/Algorithm-hantawon123-22D3EE?style=for-the-badge&logo=thealgorithms&logoColor=0B1020" alt="Open Han Tawon solved.ac profile" />
  </a>
  <br>
  <a href="https://solved.ac/profile/hantawon123">
    <img width="49%" src="https://solvedac-readme-badge.vercel.app/api/v1/badge?user=hantawon123&theme=dark&size=large&back_color=0B1020&common_color=67E8F9&sub_color=A5F3FC&border_color=22D3EE" alt="Han Tawon solved.ac profile" />
  </a>

</div>

## 🏆 Awards

| 수상일 | 공모전·대회 | 수상 내역 | 프로젝트명 | 수여 기관 |
| :---: | --- | :---: | --- | --- |
| 2026.06.26 | 삼성청년 SW·AI 아카데미 1학기 | 1학기 성적우수상 · 종합성적 구미5반 3등 | — | 삼성전자주식회사 |
| 2026.07.26 | 제3회 글로벌 데이터 해커톤 DIVE 2026 | 부산교통공사·짐캐리 부문 1등 | 같이가요 | 부산광역시 |
| 2026.08.10 | 삼성청년 SW·AI 아카데미 팀 프로젝트 | 공통프로젝트 우수상 | MODERA | 삼성전자주식회사 |
| 2026.09.28 | 삼성청년 SW·AI 아카데미 팀 프로젝트 | 특화프로젝트 우수상 | Don’t Touch Mine | 삼성전자주식회사 |

<!-- 수상 내역 추가 형식:
| YYYY.MM.DD | 공모전 또는 대회명 | 대상·최우수상·우수상 | 프로젝트명 | 수여 기관 |
-->

## 🎓 Education

| 기간 | 교육 | 상태 |
| :---: | --- | :---: |
| 2026.03 | 삼성 SW 역량 평가 | B형 |
| 2026.01 ~ 현재 | 삼성청년 SW·AI 아카데미(SSAFY) 15기 · 모바일 트랙 | 진행 중 |
| 2020.03 ~ 2025.02 | 국민대학교 소프트웨어학부 | 졸업 |

<br />
