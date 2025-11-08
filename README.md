# jobspoon-backend

<h1 align="center">Job-Spoon</h1>

<p align="center">
  <b>국내 최초, 개발자를 위한 AI 모의면접 플랫폼</b><br/>
  <i>AI로 검증하는 진짜 성장, JobSpoon과 함께하세요.</i><br/>
  <b>WOW 공대팀</b>
</p>

---

## 👥 Team Profile

| 팀원 | 역할 | GitHub |
|------|------|--------|
| 🧠 **임운철** | MFE · SEO · PM | [@unchul](https://github.com/unchul) |
| ⚙️ **최현수** | AI Interview · CI/CD | [@IMCODER0000](https://github.com/IMCODER0000) |
| 🧩 **김정민** | SpoonWord | [@Mur-pixel](https://github.com/Mur-pixel) |
| 🏗️ **박태준** | Studyroom | [@Roto90-BackEnd](https://github.com/Roto90-BackEnd) |
| 🛠️ **이승현** | Admin | [@puppy1012](https://github.com/puppy1012) |
| 🎨 **정은선** | MyPage | [@eunseon-j](https://github.com/eunseon-j) |
| 📱 **김지한** | Flutter Mobile | [@IsKJH](https://github.com/IsKJH) |

---

## 📊 Tech Stack

<p align="center">
  <img src="./assets/tech_env.png" width="90%" alt="기술 스택 다이어그램">
</p>

---

## 🧠 Project Overview

**JobSpoon**은 AI 기반 모의면접을 통해 개발자의 역량을 진단하고,  
출석·퀴즈·스터디 등 다양한 활동 데이터를 종합하여  
개인 성장과 신뢰도를 시각화하는 **국내 최초의 AI 개발자 성장 관리 플랫폼**입니다.

---

## 🧩 Key Features

| 구분 | 주요 기능 |
|------|------------|
| 🤖 **AI 모의면접** | OpenAI 기반 질의응답, 실시간 평가 및 피드백 생성 |
| 👤 **회원 관리** | OAuth (Google / Naver / Kakao / Meta), JWT 인증, Redis 세션 관리 |
| 📊 **마이페이지 / 대시보드** | 신뢰점수, 레벨, 칭호, 성장 그래프 시각화 |
| 🗓️ **일정 & 스터디 관리** | 개인/스터디 일정 통합, 출석률 통계, D-Day 표시 |
| 🧠 **퀴즈 / 학습 기능** | 직군별 문제 세트 제공 및 점수 기반 성장 관리 |
| 🗣️ **커뮤니티** | 개발자 포스트, 댓글, 신고, 관리자 제재 |
| 🧰 **관리자 페이지** | 신고 처리, 사용자 제재, 통계 대시보드 |
| 📱 **모바일 앱 (Flutter)** | 주요 기능 모바일 통합 제공 (출석, 면접 결과 조회 등) |

---

## 🏗️ Architecture

<p align="center">
  <img src="https://github.com/user-attachments/assets/201203c4-d9e9-4da3-8670-d31ec7216445" width="90%" alt="서비스 아키텍처 다이어그램">
</p>

---

## 🧱 Design Pattern

<p align="center">
  <img src="./assets/design_pattern.png" width="90%" alt="설계 패턴 구조">
</p>

- **Layered Architecture** → Controller → Service → Repository 계층 구조로 명확한 책임 분리  
- **Domain-Driven Design (DDD)** → 도메인 단위 패키징으로 유지보수성과 확장성 확보  

---

## 🧠 Tech Highlights

| 기술 포인트 | 설명 |
|--------------|------|
| 🔐 **OAuth & Token 관리** | Google / Naver / Kakao / Meta 로그인, Redis TTL 세션 캐싱 |
| ⚙️ **Proxy Service 구조** | Django → Spring 이관 시 API 단일화 및 호출 흐름 단순화 |
| 📊 **신뢰점수 시스템** | 출석·면접·퀴즈 등 활동 데이터를 가중치 기반 점수화 |
| ☁️ **CI/CD 자동화** | GitHub Actions + Docker + AWS EC2 파이프라인 구축 |
| 🎨 **시각화 대시보드** | Recharts 기반 성장 그래프 / 출석률 / 레벨 변화 시각화 |
| 🧩 **MFE 구조** | Rspack + Lerna + Nx 기반 모듈 간 독립 빌드 및 배포 |

---

## 🤝 Collaboration

<p align="center">
  <img src="./assets/collaboration.png" width="80%" alt="협업 환경 다이어그램">
</p>

| 도구 | 역할 |
|------|------|
| 🗂️ **Notion** | 기획, 백로그, 일정 관리 |
| 🧑‍💻 **GitHub** | 브랜치 전략, PR 리뷰, 커밋 컨벤션 |
| 💬 **Slack** | 실시간 커뮤니케이션 |
| 🪄 **Issue Tracker** | 장애 대응, 기능 개선 기록 |

---

## 🧾 Deployment

| 구성 | 기술 |
|------|------|
| **Server** | AWS EC2 (Docker Compose) |
| **DB** | AWS RDS (MySQL) |
| **Cache** | AWS ElastiCache (Redis) |
| **Storage** | AWS S3 |
| **CI/CD** | GitHub Actions → Docker Hub → EC2 |
| **Domain/CDN** | AWS Route53 + CloudFront |

```bash
# Backend 실행
cd backend
./gradlew build
java -jar build/libs/jobspoon.jar

# Frontend 실행
cd frontend
npm install
npm run start
