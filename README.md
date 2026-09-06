<!-- HEADER -->
<h1 align="center">👋 Hi, I'm <b>Justin Hong (홍엽)</b></h1>
<h3 align="center">실패를 통해 비즈니스와 생존의 관점을 배운 메이커</h3>

<p align="center">
  <a href="mailto:madwolves98@gmail.com"><img src="https://img.shields.io/badge/Email-madwolves98@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

<br/>

---

## 🌟 About Me
모두의창업 컴퍼니 빌딩 과정에서 제품의 Zero-to-One 단계를 주도하며 비즈니스의 생존과 기술 효율의 트레이드오프를 치열하게 고민해 왔습니다. 
화면 구현을 넘어 백엔드와의 데이터 흐름 및 서비스 전체 구조를 이해하고, 한정된 리소스 속에서 린(Lean)하게 제품을 빌딩하고 안착시키는 데 집중합니다.

- **비즈니스 가치 검증**: '우물' 프로젝트에서 Next.js 기반 사전예약 환경과 GA4 전환 파이프라인을 구축하여 **418명의 초기 리드 달성** 견인
- **체감 성능 최적화**: 데이트팝 인턴십 당시 이미지 지연 로딩(Lazy Loading) 구조 설계를 통해 **초기 전송량 95% 절감 및 속도 약 40% 개선**
- **데이터 무결성 확보**: 비동기 상태 관리 및 레이스 컨디션 차단을 통해 **서버 상태와 UI 간 데이터 일관성 100% 보장**

---

## 🧰 Tech Stack

### Core (주력 기술)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E3F?style=for-the-badge&logo=bear&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)

### State & Data
![Vue](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 🚀 Featured Projects

### 🧺 우물 – 동네 마트 물가 비교 MVP 빌딩 (2026.06 - 2026.08)
> **모두의창업 핵심 서비스 가설 검증을 위해 공동 창업자 겸 프론트엔드 리드로 참여한 프로젝트입니다.**
- **사전예약 유효성 및 보안**: React Hook Form과 Zod 기반의 선언적 유효성 검증을 도입하여 클라이언트 단계 입력 무결성을 보장하고, GA4 연동 시 PII(개인 식별 정보) 노출을 차단하는 보안 아키텍처 수립을 통해 **누적 사전예약자 418명 달성**에 기여
- **반응형 인터랙션 최적화**: 뷰포트 리사이징 시 복합 인터랙션(Tabs <-> Carousel) 상태 유지를 위한 reInit 핸들러 구현으로 **UI 리셋 버그 100% 해결 및 CLS 방지**
- **BFF 관점의 통신 계층 단일화**: Next.js Rewrites 프록시를 구축하여 도메인이 분리된 환경의 **CORS 제약을 선제적으로 해소**하고 다중 배포 환경의 API 엔드포인트 관리 복잡도 완화

---

### 🏢 데이트팝 ((주)텐핑거스) – 프론트엔드 개발 인턴 (2025.12 - 2026.01)
> **48만 MAU 실서비스 환경에서 웹페이지 성능 최적화 및 인하우스 운영 시스템을 개선한 경험입니다.**
- **메인 페이지 로딩 최적화**: React.lazy 및 선별적 지연 로딩(Lazy Loading) 아키텍처 개편을 통해 **초기 데이터 전송량 95% 절감 (20MB → 1MB)** 및 **페이지 로딩 속도 지표 약 40% 개선 (24.6초 → 17.4초)**
- **Lottie 애니메이션 렌더링 이슈 해결**: 데이터 타입을 판별해 자동으로 렌더러를 선택하는 커스텀 훅 및 파이프라인 구축을 통해 단순 이미지 태그 처리 오류를 해결하고 운영 안정성 확보
- **인하우스 운영 편의성 개선**: TypeScript 기반의 환불 계좌 수정 모달 설계 및 입력 예외 흐름 정리를 통해 운영 편의성 향상 및 데이터 정합성 보장

---

### 🎓 StudyHub Admin – 어드민 서비스 프론트엔드 개발 (2025.10 - 2025.11)
> **비동기 상태 관리의 안정성과 결합도를 고려한 웹 애플리케이션 구조 설계 프로젝트입니다.**
- **레이스 컨디션 해결 및 데이터 무결성 확보**: `mutateAsync().then()` 체이닝 구조를 도입하여 서버 응답이 확정된 시점에만 UI 상태가 변경되도록 흐름을 통제, 데이터 무결성 100% 보장 및 잘못된 운영 조작 유발 위험 차단
- **공통 UI 시스템 구축**: 버튼, 브래드크럼, 페이지네이션 등 공통 UI 컴포넌트 6종을 설계하여 각 팀원 간 **시스템 UI 일관성 100% 확보** 및 전체 페이지 빌딩 속도 단축 기여

---

### 💸 TeamPLPL – 리워드형 크라우드 펀딩 플랫폼 아키텍처 설계 (2024.10 - 2024.11)
> **Spring Boot와 Vue를 연계하여 비즈니스 로직과 서비스의 신뢰성을 확보한 프로젝트입니다.**
- **구매 인증 기반 커뮤니티 설계**: 비후원자의 우회 게시글 작성을 원천 차단하기 위해, 실제 후원 기록 데이터를 검증하는 서버 응답 기반의 인터셉터 검증 로직을 구축하여 서비스 신뢰도 제고
- **API 통신 레이어 캡슐화**: Axios 전용 Wrapper 모듈 설계를 통해 컴포넌트의 API 의존성을 낮추고, 에러 핸들링 및 인증 헤더 주입 로직을 중앙 집중화하여 신규 기능 도입 개발 리스크 30% 절감

---

## 📈 GitHub Stats

<table>
  <tr>
    <td>
      <img height="160px" src="https://github-readme-stats-fast.vercel.app/api?username=Justin-SJ-Hong&show_icons=true&theme=tokyonight"/>
    </td>
    <td>
      <img height="160px" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Justin-SJ-Hong&layout=compact&theme=tokyonight&hide=python,Visual%20Basic%206.0"/>
    </td>
    <td>
      <img height="160px" src="https://github-readme-stats-fast.vercel.app/api/streak?username=Justin-SJ-Hong&theme=tokyonight"/>
    </td>
  </tr>
  <tr>
    <td>My Stat</td>
    <td>Top Used Languages</td>
    <td>My Streak</td>
  </tr>
</table>

---

## 📬 Contact
- Email: **madwolves98@gmail.com** 

---

✨ *“기술적 근거를 바탕으로 문제를 진단하고, 팀의 생존을 함께 고민하며 성장하는 개발자”*
