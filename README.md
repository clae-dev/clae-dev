## 👋 안녕하세요!
🧩 문제 해결을 즐기는 백엔드 개발자 조창래입니다.

사용자에게 실질적인 가치를 주는 서비스를 만들기 위해  
Java · Spring 기반으로 구조와 기본기를 중요하게 생각하며 개발하고 있습니다.

---

## 🚀 주요 프로젝트

 🚀 K-MAC 해커톤 프로젝트
 
🔗 GitHub Repository 
([K-MAC](https://github.com/KMAC-hackerton/frontend.git))
([K-MAC](https://github.com/KMAC-hackerton/backend.git)))

 🚀 세미 프로젝트  봉사 커뮤니티 웹 서비스
 
🔗 GitHub Repository https://github.com/Trouble-Developer/semi_project.git

 🚀 SIMVEX 3D 공학 학습 플랫폼 (해커톤 MVP)
 
🔗 GitHub  
https://github.com/Blaybus-TED-Chang/simvex-web

---

###🚀 K-MAC 해커톤 프로젝트

실사용 시나리오 기반 MVP 개발 해커톤
- 제한된 시간 내 요구사항 분석 → 기능 설계 → 구현 경험
- Java · Spring 기반으로 백엔드 API 설계 및 데이터 흐름 구현
실제 서비스 관점에서
- 기능 우선순위 선정
- 구현 범위 조절
- 기술적 트레이드오프를 고려한 의사결정 경험
- 협업 과정에서 이슈 공유 및 해결 방식 학습

🔗 기획 문서 
[KMAC PPT.pdf](https://github.com/user-attachments/files/25028764/KMAC.PPT.pdf)

🚀 세미 프로젝트 | 봉사 커뮤니티 웹 서비스

게시판 중심 봉사 커뮤니티 웹 서비스 개발
- Spring 기반 MVC 구조로 회원 관리, 게시판, 댓글 기능 구현
- 자유게시판·봉사후기·공지사항 등 게시판 유형 분리 및 공통 로직 설계
- 댓글/대댓글 구조 구현과 삭제·권한 처리 등 실제 서비스 예외 상황 고려
- MyBatis를 활용한 SQL 분리 및 데이터 흐름 명확화
- 로그인 세션 기반 인증 처리 및 마이페이지 기능 구현
👉 “기본기에 집중하여 게시판 중심 웹 서비스의 전체 흐름을 완성한 프로젝트”

🔍 담당 역할 & 기여도 

- 게시판 CRUD 및 댓글/대댓글 기능 전담 구현
- Controller → Service → Mapper → DB 레이어 구조 설계 및 구현
- 게시글 삭제, 권한 체크, 예외 처리 로직 설계
- 공통 UI 흐름(목록 / 상세 / 작성 / 수정 / 삭제) 유지


## 🚀 SIMVEX | 3D 공학 학습 플랫폼 (해커톤 MVP)

공대생 및 기계·로봇공학 입문자를 위한  
웹 기반 3D 기계 부품 시각화 학습 서비스

### 📌 프로젝트 개요

- Three.js 기반 3D 뷰어로 드론, 로봇팔, 판스프링, 서스펜션 모델 분해/조립 학습
- 부품 클릭 시 기능 설명 제공
- OpenAI GPT-5-mini 기반 AI 학습 어시스턴트
- 사용자 GLB/FBX 모델 업로드 및 커뮤니티 공유 기능
- Supabase 기반 인증, 노트 저장, 채팅 기록 동기화
- PDF 학습 자료 내보내기 기능 구현

---

### 🧠 Architecture Overview

Client (Next.js + React + Three.js)
        ↓
Next.js API Routes
        ↓
Supabase (Auth / PostgreSQL / Storage)
        ↓
OpenAI GPT-5-mini API

> 프론트엔드, API 레이어, DB, 외부 AI API를 분리하여  
> 확장성과 유지보수를 고려한 구조로 설계했습니다.

---

### 🔍 담당 역할 & 기여도

- Supabase PostgreSQL 테이블 설계  
  (user_notes, chat_conversations, user_models)
- RLS(Row Level Security) 정책 설계 및 적용
- Supabase Auth 기반 인증 시스템 구축
- 세션 관리 미들웨어 및 OAuth 콜백 처리
- Next.js API 라우트 설계 및 AI API 연동
- 컨텍스트 기반 프롬프트 엔지니어링 설계
- Supabase Storage 업로드 파이프라인 구현
- DB 마이그레이션 스크립트 작성
- 노트/채팅 기록 CRUD 및 동기화 로직 구현
- Vercel 배포 및 환경 변수 관리

---

### 📈 프로젝트 성과

- 10일 MVP 해커톤 완주 및 실제 배포
- 3D 렌더링 + 인증 + 스토리지 + AI API 통합 설계 경험
- 사용자 노트/대화 기록 동기화 기능 완성
- 제한된 기간 내 기능 우선순위 조정 및 범위 관리 경험

---

### 🛠 Tech Stack

Next.js / React / TypeScript  
Three.js / @react-three/fiber  
Zustand  
Supabase (PostgreSQL, Auth, Storage)  
OpenAI API  
Tailwind CSS  
Vercel  

🔗 GitHub  
https://github.com/Blaybus-TED-Chang/simvex-web

---




---

  ## 🛠 기술 스택                                                                                                                                                                              
  
  **Backend**                                                                                                                                                                                   ![Java](https://img.shields.io/badge/JAVA-007396?style=for-the-badge&logo=java&logoColor=white)                                                                                             
  ![Spring Boot](https://img.shields.io/badge/SPRING%20BOOT-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
  ![Spring Security](https://img.shields.io/badge/SPRING%20SECURITY-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
  ![JDBC](https://img.shields.io/badge/JDBC-59666C?style=for-the-badge)
  ![Supabase](https://img.shields.io/badge/SUPABASE-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

  **Frontend**
  ![Next.js](https://img.shields.io/badge/NEXT.JS-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

  **Database**
  ![Oracle](https://img.shields.io/badge/ORACLE-F80000?style=for-the-badge&logo=oracle&logoColor=white)

  **Tools & DevOps**
  ![Git](https://img.shields.io/badge/GIT-F05032?style=for-the-badge&logo=git&logoColor=white)
  ![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📚 교육 & 학습

- KH정보교육원  
  디지털컨버전스 React & Spring 활용 Java 개발자 과정  
  → 문제해결 시나리오 기반 평가 및 포트폴리오 중심 학습

-  AI 응용소프트웨어공학과 재학  
  → C, Python, AI 리터러시 등 소프트웨어 전반 학습

---

## 📬 Contact & Portfolio

[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:12michael23@naver.com)
[![Notion](https://img.shields.io/badge/NOTION-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/2e827c307157805aaff3c159fb23c716?source=copy_link)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/clae-dev)

<!-- updated -->
