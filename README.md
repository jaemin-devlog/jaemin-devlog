<div align="center">

![header](https://capsule-render.vercel.app/api?type=rect&height=105&color=0:1E293B,100:0F766E&text=%EC%A0%95%EC%9E%AC%EB%AF%BC&fontColor=FFFFFF&fontSize=30&fontAlignY=40&desc=Backend%20Developer&descSize=15&descAlignY=68)

**실패 상황에서도 데이터 정합성과 사용자 경험을 지키는 백엔드를 설계합니다.**

Java와 Spring Boot를 중심으로 인증, 데이터 모델링, 비동기 처리와 복구 가능한 시스템을 구현하고 있습니다.

![Java & Spring Boot](https://img.shields.io/badge/Java%20%26%20Spring%20Boot-334155?style=flat-square&logo=springboot&logoColor=white)
![Data Integrity](https://img.shields.io/badge/Data%20Integrity-0F766E?style=flat-square)
![Failure Recovery](https://img.shields.io/badge/Failure%20Recovery-2563EB?style=flat-square)

[![Email](https://img.shields.io/badge/Email-jjm0203311%40naver.com-0F766E?style=flat-square&logo=naver&logoColor=white)](mailto:jjm0203311@naver.com)

</div>

## About

- 기능이 성공할 때뿐 아니라 **실패·재시도·복구 과정에서도 데이터가 안전한 구조**에 관심이 있습니다.
- 트랜잭션 경계, 비동기 Worker, 소유권 격리와 인증처럼 서비스의 신뢰성을 결정하는 문제를 구체적인 테스트로 확인합니다.
- 구현 내용과 문서가 어긋나지 않도록 소스 코드, migration, 테스트와 실행 환경을 함께 관리합니다.
- 현재 오픈소스 Career Intelligence Engine인 **PRIZM**을 개발하고 있습니다.

## Selected Projects

### [PRIZM](https://github.com/jaemin-devlog/PRIZM)

> 흩어진 커리어 문서를 버전별로 관리하고, 등록된 원문 근거를 검색하는 오픈소스 Career Intelligence Engine

- 새 문서 버전의 처리가 완료되기 전까지 기존 `ACTIVE` 버전을 유지하고, 검증 완료 시 `active_version_id`를 원자적으로 전환했습니다.
- 파일 삭제를 요청 트랜잭션에서 분리해 lease, retry/backoff, claim-version fencing과 복구를 갖춘 Cleanup Worker로 구현했습니다.
- 사용자 소유권과 `ACTIVE` 버전을 기준으로 PostgreSQL `pgvector` exact cosine 검색을 구성했습니다.
- TXT/PDF 업로드, 문서 CRUD·버전 관리, PDF 미리보기와 최대 5개 Career Evidence 검색을 React Reference App으로 제공합니다.

`Java 17` `Spring Boot` `PostgreSQL` `pgvector` `Flyway` `React` `TypeScript` `Docker`

### [AirConnect](https://github.com/jaemin-devlog/AirConnect)

> 1:1 소개팅과 다대다 과팅을 지원하는 실시간 매칭 서비스

- OAuth2, JWT와 Spring Security를 이용한 인증 흐름을 구성했습니다.
- WebSocket/STOMP 기반 실시간 채팅과 Redis를 활용한 상태 관리를 구현했습니다.
- 알림 유실을 줄이기 위해 FCM 전송과 Outbox Worker 구조를 적용했습니다.
- Docker Compose, Nginx와 GitHub Actions를 이용해 실행·배포 환경을 구성했습니다.

`Java 17` `Spring Boot` `MySQL` `Redis` `WebSocket` `STOMP` `FCM` `Docker`

## Engineering Focus

- **Data Integrity** — transaction, versioning, migration, ownership
- **Failure Recovery** — durable job, retry/backoff, lease, fencing, idempotency
- **Backend Security** — JWT, OAuth2, Spring Security, owner-scoped access
- **Verification** — JUnit 5, Mockito, Testcontainers, integration test, CI

## Tech Stack

| Area | Technologies |
|---|---|
| Backend | Java, Spring Boot, Spring Security, JPA/Hibernate, Flyway |
| Data & Search | PostgreSQL, pgvector, MySQL, Redis |
| Async & Realtime | Worker, Outbox Pattern, WebSocket, STOMP, FCM |
| Infra & Test | Docker, Nginx, GitHub Actions, JUnit 5, Mockito, Testcontainers |
| Frontend | React, TypeScript, Vite |

## Contact

- Email: [jjm0203311@naver.com](mailto:jjm0203311@naver.com)
