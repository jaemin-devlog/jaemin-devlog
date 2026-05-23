<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&height=150&color=0:0F172A,100:0E7490&text=%EC%A0%95%EC%9E%AC%EB%AF%BC&fontColor=FFFFFF&fontSize=42&fontAlignY=38&desc=Java%20/%20Spring%20Boot%20Backend&descSize=17&descAlignY=62)

<a href="https://github.com/jaemin-devlog">
  <img src="https://img.shields.io/badge/GitHub-jaemin--devlog-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://jaemin-devlog.github.io/">
  <img src="https://img.shields.io/badge/Blog-GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white" alt="Blog" />
</a>
<a href="mailto:jjm0203311@naver.com">
  <img src="https://img.shields.io/badge/Email-jjm0203311%40naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
</a>

<br><br>

`Java` `Spring Boot` `JPA` `MySQL` `Redis` `WebSocket` `FCM` `Docker`

</div>

<br>

<h2 align="center">Projects</h2>

<table align="center">
  <tr>
    <td width="33%" valign="top" align="center">
      <h3>AirConnect</h3>
      <p>
        1,300명이 사용한 교내 소셜 매칭 웹 서비스의 한계를 바탕으로 만든<br>
        <b>실시간 그룹매칭·채팅·알림 기반 친구찾기 앱</b>
      </p>
      <p>
        Redis 큐·분산 락 기반 2:2/3:3 그룹매칭<br>
        WebSocket/STOMP + Redis Pub/Sub 채팅<br>
        FCM Outbox 기반 알림 전송·재시도
      </p>
      <p>
        <code>Spring Boot</code>
        <code>Redis</code>
        <code>WebSocket</code>
        <code>FCM</code>
        <code>MySQL</code>
      </p>
      <a href="https://github.com/jaemin-devlog/AirConnect">GitHub</a> ·
      <a href="https://apps.apple.com/kr/app/%EC%97%90%EC%96%B4%EC%BB%A4%EB%84%A5%ED%8A%B8-airconnect/id6761365188">App Store</a>
    </td>
    <td width="33%" valign="top" align="center">
      <h3>MoneyWay</h3>
      <p>
        예산을 입력하면 AI 여행 코스를 생성하고 저장·공유까지 연결하는<br>
        <b>제주 여행 플래닝 서비스</b>
      </p>
      <p>
        Kakao OAuth2 + JWT Access/Refresh 인증<br>
        장바구니 중복 방지·owner 검증<br>
        Apache POI 기반 장소 데이터 업로드
      </p>
      <p>
        <code>Spring Boot</code>
        <code>JPA</code>
        <code>Redis</code>
        <code>Docker</code>
        <code>Nginx</code>
      </p>
      <a href="https://github.com/jaemin-devlog/MoneyWay">GitHub</a> ·
      <a href="https://moneyway.jeju.kr/">Service</a>
    </td>
    <td width="33%" valign="top" align="center">
      <h3>Seosan-issue</h3>
      <p>
        흩어진 서산 지역 공공 정보를 수집하고 요약 API와 연결한<br>
        <b>지역 정보 파이프라인 서비스</b>
      </p>
      <p>
        서산시청·복지·문화관광 게시글 크롤링<br>
        Flask 크롤러/요약 API와 내부 연동<br>
        link unique + Scheduler 중복 저장 방지
      </p>
      <p>
        <code>Spring Boot</code>
        <code>Flask</code>
        <code>WebClient</code>
        <code>Scheduler</code>
        <code>MySQL</code>
      </p>
      <a href="https://github.com/jaemin-devlog/seosan-issue">GitHub</a> ·
      <a href="https://seosan-issue.web.app/">Service</a>
    </td>
  </tr>
</table>

<br>

## Tech Stack

<table>
  <tr>
    <td><b>Backend</b></td>
    <td>
      <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
      <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
      <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Database</b></td>
    <td>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Realtime</b></td>
    <td>
      <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white" />
      <img src="https://img.shields.io/badge/STOMP-59666C?style=flat-square" />
      <img src="https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black" />
      <img src="https://img.shields.io/badge/Outbox%20Pattern-326CE5?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><b>Infra / Test</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
      <img src="https://img.shields.io/badge/GCP%20Ubuntu-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
      <img src="https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white" />
      <img src="https://img.shields.io/badge/Mockito-78A641?style=flat-square" />
    </td>
  </tr>
</table>
