<h1 align="center">
  🔗 <a href="https://job-spoon.com" target="_blank" style="text-decoration:none; color:#13B38D;">
    <b>Job-Spoon</b>
  </a> 
</h1>

<p align="center">
  <b>국내 최초, 개발자를 위한 AI 모의면접 플랫폼</b><br/>
  <i>AI로 검증하는 진짜 성장, JobSpoon과 함께하세요.</i><br/>
  <b>WOW 공대팀 · Backend Module</b>
</p>

---

## Project Overview

<p align="center">
<b>JobSpoon</b>은 AI 기반 모의면접을 통해 개발자의 역량을 진단하고,<br/>
출석·퀴즈·스터디 등 다양한 활동 데이터를 종합하여<br/>
<b>개인 성장과 신뢰도를 시각화</b>하는 국내 최초의 AI 개발자 성장 관리 플랫폼입니다.
</p>

---

## MyPage Demo

<p align="center">
  <a href="https://www.youtube.com/watch?v=2HRqqLArhD4" target="_blank">
    <img src="https://img.shields.io/badge/Watch%20Demo-20A4AD?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube Demo">
  </a><br/>
  <i>마이페이지 대시보드 시연 영상 보기</i>
</p>

---

## Team Profile

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/unchul" width="80" height="80" style="border-radius:50%;"/><br/>
      <b>임운철</b><br/>
      <sub>MFE · SEO · PM</sub><br/>
      <a href="https://github.com/unchul" style="color:#13B38D;">@unchul</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/IMCODER0000" width="80" height="80" style="border-radius:50%;"/><br/>
      <b>최현수</b><br/>
      <sub>AI Interview · CI/CD</sub><br/>
      <a href="https://github.com/IMCODER0000" style="color:#13B38D;">@IMCODER0000</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/Mur-pixel" width="80" height="80" style="border-radius:50%;"/><br/>
      <b>김정민</b><br/>
      <sub>SpoonWord</sub><br/>
      <a href="https://github.com/Mur-pixel" style="color:#13B38D;">@Mur-pixel</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/Roto90-BackEnd" width="80" height="80" style="border-radius:50%;"/><br/>
      <b>박태준</b><br/>
      <sub>Studyroom</sub><br/>
      <a href="https://github.com/Roto90-BackEnd" style="color:#13B38D;">@Roto90-BackEnd</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/puppy1012" width="80" height="80" style="border-radius:50%;"/><br/>
      <b>이승현</b><br/>
      <sub>Admin</sub><br/>
      <a href="https://github.com/puppy1012" style="color:#13B38D;">@puppy1012</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/yeolmu96" width="80" height="80" style="border-radius:50%;"/><br/>
      <b>정은선</b><br/>
      <sub>MyPage</sub><br/>
      <a href="https://github.com/yeolmu96" style="color:#13B38D;">@yeolmu96</a>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/IsKJH" width="80" height="80" style="border-radius:50%;"/><br/>
      <b>김지한</b><br/>
      <sub>Flutter Mobile</sub><br/>
      <a href="https://github.com/IsKJH" style="color:#13B38D;">@IsKJH</a>
    </td>
  </tr>
</table>

<br/>

<a href="https://eddi-robot-academy.notion.site/239694fe059580ba9209da02f8fc32b4" target="_blank">
  <img src="https://img.shields.io/badge/Notion%20Team%20Page-13B38D?style=for-the-badge&logo=notion&logoColor=white" alt="Notion Link">
</a>

</div>

---

## Tech Stack

<p align="center">
  <img src="https://github.com/user-attachments/assets/6a79ebcd-0011-4b0f-8005-f0e4e987fd51" width="90%" alt="기술 스택 다이어그램">
</p>

---

## Architecture

<p align="center">
  <img src="https://github.com/user-attachments/assets/201203c4-d9e9-4da3-8670-d31ec7216445" width="90%" alt="서비스 아키텍처 다이어그램">
</p>

---

## Design Pattern

<p align="center">
  <img src="https://github.com/user-attachments/assets/7401fb13-86aa-47fd-96ba-afe1355855ba" width="90%" alt="설계 패턴 구조">
</p>

<div align="center">
<b>Layered Architecture</b> — Controller → Service → Repository 계층으로 책임 분리<br/>
<b>Domain-Driven Design (DDD)</b> — 도메인 단위 패키징으로 유지보수성과 확장성 확보
</div>

---

## Technical Highlights

<div align="center">

<table>
  <thead>
    <tr>
      <th width="220px">기술 포인트</th>
      <th>설명</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>OAuth & Token 관리</td>
      <td>Kakao / Meta 로그인, Redis TTL 세션 캐싱 구조 설계</td>
    </tr>
    <tr>
      <td>Proxy Service 구조</td>
      <td>Django → Spring 전환 시 API 호출 흐름 단일화</td>
    </tr>
    <tr>
      <td>신뢰점수 시스템</td>
      <td>출석·면접·퀴즈 데이터 기반 가중치 점수화 및 자동 갱신</td>
    </tr>
    <tr>
      <td>CI/CD 자동화</td>
      <td>GitHub Actions + Docker + AWS EC2 파이프라인 구축</td>
    </tr>
    <tr>
      <td>시각화 대시보드</td>
      <td>Recharts 기반 성장 그래프 및 사용자 지표 시각화</td>
    </tr>
    <tr>
      <td>MFE 구조</td>
      <td>Rspack + Lerna + Nx 기반 모듈 독립 빌드 및 배포</td>
    </tr>
  </tbody>
</table>

</div>

---

## Key Features

<div align="center">

<table>
  <thead>
    <tr>
      <th width="220px">구분</th>
      <th>주요 기능</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>AI 모의면접</td><td>OpenAI 기반 질의응답, 실시간 평가 및 피드백 생성</td></tr>
    <tr><td>회원 관리</td><td>OAuth (Kakao / Meta), JWT 인증, Redis 세션 관리</td></tr>
    <tr><td>마이페이지 / 대시보드</td><td>활동점수, 레벨, 칭호, 성장 그래프 시각화</td></tr>
    <tr><td>일정 & 스터디 관리</td><td>개인/스터디 일정 통합, 출석률 통계 기능</td></tr>
    <tr><td>퀴즈 / 학습 기능</td><td>직군별 문제 세트 제공 및 점수 기반 성장 관리</td></tr>
    <tr><td>관리자 페이지</td><td>신고 처리, 사용자 제재, 통계 대시보드</td></tr>
    <tr><td>모바일 앱 (Flutter)</td><td>주요 기능 모바일 통합 제공</td></tr>
  </tbody>
</table>

</div>

---

## Collaboration

<p align="center">
  <img src="https://github.com/user-attachments/assets/2fc82de6-15b5-4363-825f-529e5ba211d7" width="80%" alt="협업 환경 다이어그램">
</p>

<div align="center">

<table>
  <thead>
    <tr>
      <th width="220px">도구</th>
      <th>역할</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><a href="https://eddi-robot-academy.notion.site/239694fe059580ba9209da02f8fc32b4" target="_blank"><b>Notion</b></a></td><td>기획, 백로그, 스크럼 관리</td></tr>
    <tr><td>GitHub</td><td>브랜치 전략, Pull Request 리뷰, 커밋 컨벤션</td></tr>
    <tr><td>Slack</td><td>실시간 커뮤니케이션 및 공지 공유</td></tr>
    <tr><td>Issue Tracker</td><td>장애 대응, 기능 개선, 배포 이력 관리</td></tr>
  </tbody>
</table>

</div>

---

## Deployment

<div align="center">

<table>
  <thead>
    <tr>
      <th width="220px">구성</th>
      <th>기술</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Server</td><td>AWS EC2 (Docker Compose)</td></tr>
    <tr><td>Database</td><td>AWS RDS (MySQL)</td></tr>
    <tr><td>Cache</td><td>AWS ElastiCache (Redis)</td></tr>
    <tr><td>Storage</td><td>AWS S3</td></tr>
    <tr><td>CI/CD</td><td>GitHub Actions → Docker Hub → EC2</td></tr>
    <tr><td>Domain/CDN</td><td>AWS Route53 + CloudFront</td></tr>
  </tbody>
</table>

</div>

---

## How to Run

```bash
# Backend 실행
cd backend
./gradlew build
java -jar build/libs/jobspoon.jar
```
