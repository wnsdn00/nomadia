<p align="center">
  <a href="https://nomadia-two.vercel.app/">
  <img width="200" height="200" alt="logo" src="./public/images/icons/logo.svg" />
  </a>
</p>

<div align="center">

# Nomadia : Nomad + Utopia

### 어디서든 '나답게' 머무는 경험을 시작하세요.

**노마디아 (Nomadia)** 는 노마드를 위한 **액티비티 예약 플랫폼**입니다.  
사용자가 직접 체험을 등록하고, 다른 노마드의 체험을 예약하며 경험을 공유할 수 있습니다.

</div>
<p align="center">
배포 링크: https://nomadia-two.vercel.app/
</p>

<div align="center">
<details>
<summary> 👀 Preview GIF/MP4</summary>

#### 회원가입/로그인

![회원가입_로그인_2배속](https://github.com/user-attachments/assets/27669840-8ad0-4cfc-895b-0731aa1e2e4e)

#### 메인페이지 캐러셀

#### 메인페이지 리스트

#### 메인페이지 검색

---

#### 체험 등록

https://github.com/user-attachments/assets/e7392d86-01c6-4a3e-9dea-505839d868ca

#### 마이페이지 내 체험 관리 - 체험 수정

![체험수정_2배속](https://github.com/user-attachments/assets/8d7843fd-2522-4443-aec8-d6379d2d20a6)

#### 마이페이지 내 체험 관리 - 체험 삭제

![내체험관리_체험삭제](https://github.com/user-attachments/assets/b8ded43c-53b0-4326-9c6c-ba835170561e)

#### 마이페이지 예약 내역 - 취소

![예약취소_2배속](https://github.com/user-attachments/assets/00d2a0a5-814d-4444-b0ef-7dc1b91713b4)

#### 마이페이지 예약 내역 - 후기 작성

![후기작성](https://github.com/user-attachments/assets/931a7f38-b350-4b6d-b31c-4f8784736b69)

#### 마이페이지 내 예약 현황

---

#### 상세페이지

https://github.com/user-attachments/assets/1dcba629-9388-41bc-a9a5-a5c0f5c12bc1

---

</details>
<br>
</div>

## 주요 기능

- 💻 **체험 등록** - 노마드가 직접 체험을 등록하고 관리
- 📅 **예약 시스템** - 실시간 예약 가능 날짜 확인 및 예약
- 🔍 **스마트 검색** - 카테고리, 지역별 체험 검색
- 👤 **마이페이지** - 예약 내역, 예약 현황, 체험 관리, 프로필 수정

## 기술 스택

### **Core Stack**

| 기술            | 버전                | 설명                                        |
| --------------- | ------------------- | ------------------------------------------- |
| **Next.js**     | 15.3.5 (App Router) | 파일 기반 라우팅, SSR로 SEO 최적화          |
| **TypeScript**  | 5.x                 | 정적 타입으로 개발 안정성 향상              |
| **React**       | 19.0.0              | 최신 기능(Server Components, Suspense) 활용 |
| **TailwindCSS** | v4 + Turbopack      | 빠른 빌드와 일관된 디자인 시스템            |

### **Data & State Management**

| 기술               | 설명                                           |
| ------------------ | ---------------------------------------------- |
| **TanStack Query** | 서버 상태 캐싱과 동기화로 API 요청 최적화      |
| **Zustand**        | 간단하고 직관적인 클라이언트 상태 관리         |
| **Axios**          | 안정적인 HTTP 클라이언트, 인터셉터로 토큰 관리 |

### **Form & Validation**

| 기술                | 설명                        |
| ------------------- | --------------------------- |
| **React Hook Form** | 성능 최적화된 폼 라이브러리 |
| **Zod**             | TypeScript 기반 스키마 검증 |

### **UI/UX**

| 기술              | 설명                                |
| ----------------- | ----------------------------------- |
| **shadcn/ui**     | 커스터마이징 가능한 컴포넌트 시스템 |
| **Framer Motion** | 부드러운 애니메이션과 인터랙션      |
| **Swiper**        | 반응형 캐러셀과 터치 슬라이더       |

### **Development & Deployment**

| 기술                    | 설명                             |
| ----------------------- | -------------------------------- |
| **Vercel**              | Next.js 최적화된 배포 플랫폼     |
| **Husky + lint-staged** | Git Hook으로 코드 품질 자동 검증 |
| **Lighthouse CI**       | 성능 및 접근성 지속적 모니터링   |

<br>

## 프로젝트 문서

### 트러블슈팅

| 분류     | 설명                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **UX & Interaction** | - [모달 ESC 키 제어 방식 (로컬 vs 전역이벤트)](https://www.notion.so/ESC-vs-268bbeae3e2b80e5a292f152e60e3d5d) <br> - [[UX] 로그인 성공 후 이전 맥락으로 리다이렉트](https://www.notion.so/UX-268bbeae3e2b8012882bce823bdca54f) <br> - [[UX] 모달 warning 이미지 로드 방식 개선(preload 적용)](https://www.notion.so/UX-warning-preload-26bbbeae3e2b8017ada8e43ddc792d31)                                                 |
| **Performance & Optimization** | - [Props Hell 탈출기: Context API로 컴포넌트 최적화](https://dust-radiator-52b.notion.site/Props-Hell-Context-API-263b2ffc607580b5923cd91b1bd088d4?source=copy_link) <br> - [Tanstack Query를 활용한 API 중복 요청 해결](https://dust-radiator-52b.notion.site/Tanstack-Query-API-263b2ffc607580df8b40d836d1afb1fc?source=copy_link) <br> - [코드 스플리팅 & lazy loading 적용을 통한 페이지 최적화](https://dust-radiator-52b.notion.site/Lazy-Loading-263b2ffc607580088b60c780d4d67af7?source=copy_link) <br> - [커스텀 클래스 사용 시 타이포그래피 우선순위 문제](https://www.notion.so/248bbeae3e2b80adb9b2c8a16d298ea0) |
| **Stability & Security** | - [Next.js 앱 라우터 에러 핸들링: 각 에러 코드에 대한 UI 구현](https://www.notion.so/in-237bbeae3e2b80588e00f306680edaec) <br> - [예약 중복 요청 방지하기](https://www.notion.so/269bbeae3e2b808588bad2c3d4045729) <br> - [Form-data 보안 취약점 해결](https://dust-radiator-52b.notion.site/form-data-263b2ffc607580fc9f92f3a23698cdd7?source=copy_link)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

### 공통 컴포넌트, 로직

| 작성자     | 설명                                                                                                                                                                                           |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **전지윤** | - [모달 공통 컴포넌트 - 사용 가이드](https://www.notion.so/23abbeae3e2b8001b05bd84257659cca) <br> - [캘린더 공통 컴포넌트 - 설계 구조](https://www.notion.so/26cbbeae3e2b8018b061f355ba257cde) |
| **김영현** | [공통 컴포넌트 docs](https://dust-radiator-52b.notion.site/DOCS-204b2ffc607580a4874bee3ab6056d51?source=copy_link)                                                                             |
