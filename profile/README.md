<h1 align="center">MUMUL 🟣</h1>
<p align="center"><b>익명 Q&A 커뮤니티 플랫폼</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Spring%20Boot%203.0.5-6DB33F?logo=springboot" />
  <img src="https://img.shields.io/badge/Frontend-React%2016.8-61DAFB?logo=react" />
  <img src="https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql" />
  <img src="https://img.shields.io/badge/Security-JWT%20%26%20OAuth2-000000?logo=jsonwebtokens" />
  <img src="https://img.shields.io/badge/Infra-AWS%20Elastic%20Beanstalk-FF9900?logo=amazonaws" />
  <img src="https://img.shields.io/badge/Email-Gmail%20API-EA4335?logo=gmail" />
</p>

---

## 📌 프로젝트 개요
**MUMUL**은 사용자가 익명 또는 닉네임으로 질문을 등록하고  
답변을 **공개/비공개 선택**할 수 있는 AMA(Ask Me Anything) 기반 Q&A 커뮤니티 플랫폼입니다.

- 스페이스 팔로우 기능  
- 새로운 답변 알림(Gmail API 기반 이메일)  
- 스페이스 중지 기능을 통한 공간 관리  

지식 공유와 커뮤니티 참여를 자연스럽게 유도하는 서비스로 설계되었습니다.

---

## 🛠 기술 스택

| 영역 | 기술 |
|------|-----|
| Backend | Java 17 · Spring Boot 3.0.5 · Spring Security · JWT · MySQL · JPA · Gradle |
| Frontend | React 16.8 · Axios · React Router · Swiper · moment.js |
| Infra | AWS Elastic Beanstalk · Google OAuth 2.0 · Gmail API |

---

## 🔧 담당 역할 및 구현 기능

### ✔ Backend
- 질문/답변 CRUD API 개발
- 스페이스 **팔로우 시스템** 구현
- **Gmail API 기반 이메일 알림 자동 발송**
- **Google OAuth + JWT** 기반 로그인·인가 처리
- JPA ORM 기반 데이터 모델링 및 트랜잭션 일관성 보장

### ✔ Frontend
- React 기반 **반응형 UI/UX 구현**
- 질문 생성/조회/필터링 기능 개발
- **팔로우 토글 및 스페이스 상태 관리 UI**
- Axios 기반 REST API 전면 연동

---

## 🚀 주요 성과 & 기술적 특징

- 비동기 처리(`@EnableAsync`)로 이메일 발송 성능 최적화
- **CORS 정책 강화**로 크로스도메인 통신 안정화
- **JWT 기반 인증 구조**로 사용자 보안 강화
- **AWS Elastic Beanstalk 배포 및 운영 성공**

---

## 💡 프로젝트 의의
MUMUL은 단순한 익명 커뮤니티가 아니라  
**지식 공유와 상호 참여를 지속적으로 유도하는 커뮤니티 플랫폼**을 목표로 합니다.  
팔로우·알림·공개 범위 제어 기능을 통해  
익명성과 신뢰 기반 소통의 균형을 갖춘 Q&A 경험을 제공합니다.
