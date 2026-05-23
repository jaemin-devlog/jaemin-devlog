<div align="center">

# 정재민

**Java / Spring Boot Backend Developer**

사용자 불편을 기능 요구사항으로 정리하고,  
실시간 처리·인증/권한·데이터 파이프라인을 백엔드 구조로 구현합니다.

<br>

<a href="https://github.com/jaemin-devlog">
  <img src="https://img.shields.io/badge/GitHub-jaemin--devlog-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://jaemin-devlog.github.io/">
  <img src="https://img.shields.io/badge/Blog-GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white" alt="Blog" />
</a>

</div>

---

## Backend Focus

- **Realtime**: Redis Queue, Distributed Lock, WebSocket/STOMP, Redis Pub/Sub
- **Notification**: FCM, Outbox Pattern, retry, duplicate prevention
- **Auth / Security**: OAuth2, JWT, HttpOnly Cookie, owner validation
- **Data Pipeline**: WebClient, Scheduler, Apache POI, Flask integration
- **Test**: JUnit5, Mockito, AssertJ

---

## Featured Projects

### AirConnect

교내 소셜 매칭 웹 서비스의 한계를 바탕으로 실시간 그룹매칭·채팅·알림 경험을 확장한 친구찾기 앱 서비스

- Redis 큐, 분산 락, queueToken 기반 2:2/3:3 그룹매칭
- WebSocket/STOMP, Redis Pub/Sub 기반 채팅과 읽음/미읽음 처리
- FCM Outbox 기반 알림 전송, 재시도, 중복 방지
- JUnit5, Mockito, AssertJ 기반 주요 예외 흐름 검증

`Spring Boot` `Redis` `WebSocket/STOMP` `FCM` `MySQL` `JUnit5`

[GitHub](https://github.com/jaemin-devlog/AirConnect) · [App Store](https://apps.apple.com/kr/app/%EC%97%90%EC%96%B4%EC%BB%A4%EB%84%A5%ED%8A%B8-airconnect/id6761365188)

### MoneyWay

예산 기반 AI 여행 코스, 장바구니, 계획 저장, 커뮤니티 공유를 연결한 제주 여행 플래닝 서비스

- Kakao OAuth2, JWT Access/Refresh, HttpOnly Cookie, Redis TTL 기반 인증
- owner 검증과 idempotent add로 중복 장소 추가·타 사용자 데이터 접근 방지
- Apache POI 배치 조회/saveAll 구조로 엑셀 데이터 적재 병목 개선
- Docker Compose, Nginx, GCP Ubuntu 배포 환경 구성

`Spring Boot` `OAuth2/JWT` `MySQL` `Redis` `Apache POI` `Docker`

[GitHub](https://github.com/jaemin-devlog/MoneyWay) · [Service](https://moneyway.jeju.kr/)

### Seosan-issue

분산된 서산 지역 공공 정보를 수집하고 요약 API와 연동하는 지역 정보 파이프라인 서비스

- 서산시청·복지·문화관광·읍면동 게시판 목록/상세 크롤링
- Flask 크롤러/요약 API와 Spring Boot 도메인 API 분리
- WebClient 내부 연동, link unique UPSERT, Scheduler 기반 중복 저장 방지

`Spring Boot` `Flask` `WebClient` `Scheduler` `MySQL`

[GitHub](https://github.com/jaemin-devlog/seosan-issue) · [Service](https://seosan-issue.web.app/)

---

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/WebSocket-2B2B2B?style=flat-square" alt="WebSocket" />
  <img src="https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="FCM" />
  <img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit5" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

<details>
<summary>More Stack</summary>

### Backend

`Java` `Spring Boot` `Spring Data JPA` `Spring Security` `REST API`

### Auth / Security

`OAuth2` `JWT` `HttpOnly Cookie`

### Async / Realtime

`WebSocket` `STOMP` `Redis Pub/Sub` `Redis Queue` `FCM` `Outbox Pattern`

### Data / Integration

`WebClient` `Scheduler` `Apache POI` `Flask`

### Test / Infra

`JUnit5` `Mockito` `AssertJ` `Docker` `Nginx` `GCP Ubuntu`

</details>
