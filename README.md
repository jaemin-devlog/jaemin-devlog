<div align="center">

![Backend Developer](https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0F172A,50:0F766E,100:2563EB&text=Backend%20Developer&fontColor=FFFFFF&fontSize=38&fontAlignY=38&desc=Reliable%20systems%20through%20verification&descSize=15&descAlignY=59)

### 왜 이렇게 동작해야 하는지 이해한 뒤 구현합니다.

정상 흐름뿐 아니라 실패·재시도·복구 상황에서도  
데이터와 사용자 흐름이 유지되는 백엔드를 고민합니다.

![Java](https://img.shields.io/badge/Java-334155?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Data Integrity](https://img.shields.io/badge/Data_Integrity-0F766E?style=flat-square)
![Failure Recovery](https://img.shields.io/badge/Failure_Recovery-2563EB?style=flat-square)
![AI Verification](https://img.shields.io/badge/AI_Verification-7C3AED?style=flat-square)

</div>

<br />

## About Me

- 문제를 작은 단위로 나누고, 정상 상황뿐 아니라 실패와 예외 상황까지 함께 고려합니다.
- 기술 선택과 개선 결과는 테스트와 측정 가능한 근거를 바탕으로 판단합니다.
- 새로운 기술과 AI를 적극적으로 활용하지만, 최종 판단은 직접 검증한 결과를 기준으로 내립니다.
- 구현에서 끝내지 않고 실제로 배포하고 운영할 수 있는 상태까지 완성하는 것을 중요하게 생각합니다.

<br />

## Featured Projects

### [PRIZM](https://github.com/jaemin-devlog/PRIZM)

![AI Search](https://img.shields.io/badge/AI_Document_Search-0F766E?style=flat-square)
![Open Source](https://img.shields.io/badge/Open_Source-334155?style=flat-square)
![In Progress](https://img.shields.io/badge/In_Progress-F59E0B?style=flat-square)

> 경력 문서를 분석하고 관련 원문 근거를 찾아주는 AI 문서 검색 서비스

- 검색 실패 25건을 분석해 개발 평가셋의 Top-1 Accuracy를 **57.14% → 82.14%**로 개선했습니다. 이후 별도 Holdout에서 기준 미달을 확인해 과적합된 개선은 실제 검색에 반영하지 않았습니다.
- 문서 추출·임베딩 완료 후에만 검색 버전을 전환하고, Lease·Heartbeat를 적용해 장시간 작업의 실패와 재시작에 대응했습니다.
- 검색 기능을 읽기 전용 MCP 도구로 제공하면서 JWT 인증과 사용자별 데이터 격리를 유지하고 실환경 E2E로 검증했습니다.

`Java 17` `Spring Boot` `PostgreSQL` `pgvector` `Flyway` `Ollama` `MCP` `Docker`

---

### [AirConnect](https://github.com/jaemin-devlog/AirConnect)

![Mobile Service](https://img.shields.io/badge/Mobile_Service-2563EB?style=flat-square)
![Production](https://img.shields.io/badge/Production-16A34A?style=flat-square)
![Realtime](https://img.shields.io/badge/Realtime-7C3AED?style=flat-square)

> 학교 인증 기반 친구 찾기·그룹 매칭 모바일 서비스

- Redis Queue로 후보를 탐색하고 DB Row Lock과 Unique Constraint로 최종 상태를 검증해 중복 매칭을 차단했습니다.
- DB를 기준으로 Redis Queue를 복구하고, FCM 전송을 Outbox Worker로 분리해 외부 알림 실패를 격리했습니다.
- Gabia Ubuntu 서버에 백엔드를 배포해 모바일 앱의 운영 API를 제공하고 있습니다.

[![App Store](https://img.shields.io/badge/App_Store-000000?style=for-the-badge&logo=apple&logoColor=white)](https://apps.apple.com/kr/app/%EC%97%90%EC%96%B4%EC%BB%A4%EB%84%A5%ED%8A%B8-airconnect/id6761365188)
[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=org.airconnect.hsu&hl=ko)

`Java 17` `Spring Boot` `MySQL` `Redis` `WebSocket/STOMP` `FCM` `Ubuntu`

---

### [MoneyWay](https://github.com/jaemin-devlog/MoneyWay)

![Team Lead](https://img.shields.io/badge/Team_Lead-D97706?style=flat-square)
![Award](https://img.shields.io/badge/Award-Winner-F59E0B?style=flat-square)
![Cloud](https://img.shields.io/badge/Cloud_Deployment-4285F4?style=flat-square)

> 예산에 맞춰 제주 여행 일정을 만드는 서비스

- 5인 팀의 팀장으로 서비스 기획, 백엔드 개발, 요구사항과 API 범위 조율을 담당했습니다.
- 이메일 로그인과 Kakao OAuth2를 통합하고 여행 계획에 사용자별 소유권 검증을 적용했습니다.
- GCP Ubuntu 서버에 백엔드를 배포하고 Nginx를 설정했습니다.
- 관광데이터 활용 공모전 **우수상·한국관광공사 사장상**을 수상했습니다.

`Java 21` `Spring Boot` `Spring Security` `OAuth2` `JWT` `MySQL` `GCP` `Nginx`

<br />

## Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square)

### Data & Search

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square)

### Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

### AI & Realtime

![Embedding](https://img.shields.io/badge/Embedding-7C3AED?style=flat-square)
![Vector Search](https://img.shields.io/badge/Vector_Search-0F766E?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-334155?style=flat-square)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square)
![FCM](https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black)
