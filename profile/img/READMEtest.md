# Starbucks Renewal Project

<div align="center">
  <img src="https://github.com/user-attachments/assets/52cd0249-474b-4ba7-90e7-b2554602aca9" alt="스파로스 114 로고" style="width: 300px;">
</div>

<br>

## 📁 레포지토리 링크

| 구분  | 레포지토리 |
| :---: | :-------- |
| Backend (BE) | [BE-Starbucks-Renewal](https://github.com/3-114/BE-Starbucks-Renewal) |
| Frontend (FE) | [FE-Starbucks-Renewal](https://github.com/3-114/FE-Starbucks-Renewal) |

<br>

# 📖 목차
1. [기획](#-기획)
2. [팀원 소개](#-팀원-소개)
3. [개발 환경](#-개발-환경)
4. [주요 기능](#-주요-기능)
5. [설계 문서](#-설계-문서)
6. [프로젝트 규칙](#-프로젝트-규칙)
7. [포팅 매뉴얼](#-포팅-매뉴얼)

<br>

# 1. ✨ 기획

> **신세계 I&C [스파로스 6기](https://swedu.spharosacademy.com/spharos_total.html) 리빌딩 프로젝트**  
> 스타벅스 내 Shopping 서비스를 새롭게 구현 및 성능 개선  
> 개발 기간: **2025년 3월 10일 ~ 4월 28일**  
> [🌐 홈페이지](https://www.starbucks-renewal.shop)

<br>

# 2. 👥 팀원 소개

<div align="center">

| 이름 | 역할 | 주요 담당 기능 |
|:---:|:---:|:---:|
| [김동현](https://github.com/Demopeu) | 🖥️ Frontend | 메인 페이지, 상품 상세페이지, 장바구니 페이지 |
| [👑 송민석](https://github.com/DoNalD-A) | ⚙️ Backend | 상품 카테고리, 이벤트(기획전), QueryDSL |
| [안동환](https://github.com/Ahn-donghwan) | ⚙️ Backend | 로그인/회원가입, JWT, Security, 장바구니 |
| [오은서](https://github.com/EUNSEO-YA) | ⚙️ Backend | 회원 배송지, 상품 상세 옵션, 데이터 전처리/삽입 |
| [추지우](https://github.com/chuman0216) | ☁️ DevOps | 상품 기능, 상품 이미지 관리, CI/CD |

</div>

<br>

# 3. 🛠 개발 환경

## 🖥️ Frontend
<div align="center">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" height="28"/>
  <br>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/shadcn/ui-000000?style=flat&logo=react&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Zod-7C3AED?style=flat&logo=typescript&logoColor=white" height="28"/>
</div>

<br>

## ⚙️ Backend
<div align="center">
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat&logo=springboot&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/SpringSecurity-6DB33F?style=flat&logo=springsecurity&logoColor=white" height="28"/>
  <br>
  <img src="https://img.shields.io/badge/QueryDSL-009688?style=flat&logo=apachemaven&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/SpringDataJPA-4B8BBE?style=flat&logo=hibernate&logoColor=white" height="28"/>
</div>

<br>

## 🤝 협업 및 개발 도구
<div align="center">
  <img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" height="28"/>
  <br>
  <img src="https://img.shields.io/badge/IntelliJ IDEA-000000?style=flat&logo=intellijidea&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visualstudiocode&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" height="28"/>
</div>

<br>

# 4. 🌱 주요 기능

| 로그인 | 장바구니 | 기획전 |
|:------:|:------:|:------:|
| ![로그인](https://github.com/user-attachments/assets/ce5d47fc-7d8b-4e71-bf9c-309dba8d9419) | ![장바구니](https://github.com/user-attachments/assets/1e01c531-c124-4be3-9669-919cd5b78dc2) | ![기획전](https://github.com/user-attachments/assets/57332611-4430-4934-aacc-71886ad6d116) |

| 메인 | 베스트 | 카테고리 |
|:----:|:----:|:----:|
| ![메인](https://github.com/user-attachments/assets/5f8bd568-e6aa-4e84-8e2e-876cf7c6315d) | ![베스트](https://github.com/user-attachments/assets/9442fd63-6d9a-4194-8c78-dbb9ca9ddb98) | ![카테고리](https://github.com/user-attachments/assets/c34a57e2-2d93-4a28-9d82-c34b40aa4163) |

<br>

# 5. 📜 설계 문서

### 🏗 시스템 아키텍처
![114-아키텍처](https://github.com/user-attachments/assets/58712f9b-50dc-4b0d-ac8d-0e407e7325f4)

<br>

### 📝 [ERD 설계](https://www.erdcloud.com/d/AfbenbEeNpbLj2dwu)
![ERD](./img/erd.png)

<br>

### 📋 [요구사항 정의서](https://funky-baron-4b5.notion.site/1bc02141a4b3810fa400e69f078ac5ab?pvs=4)
![요구사항 정의서](./img/requirement.png)

<br>

### 📋 [API 명세서](https://funky-baron-4b5.notion.site/API-1b502141a4b3804485b7ef524f753b4a?pvs=4)
![API 명세서](./img/apiSpecification.png)

<br>

# 6. 🏁 프로젝트 규칙

## 1️⃣ 커밋 메시지 규칙

**구조**: `[<스코프>]<타입>: <제목>`

- **타입(Type)**:
    - `feat`: 기능 추가
    - `fix`: 버그 수정
    - `docs`: 문서 작성/수정
    - `refactor`: 리팩토링
    - `style`: 스타일 수정
    - `remove`: 파일 삭제
    - `test`: 테스트 코드 추가
    - `chore`: 빌드/환경설정 작업
    - `perf`: 성능 개선
    - `ci`: CI/CD 작업
    - `wip`: 작업 중간 저장

**제목**:
- 50자 이내, 명령문 사용 (ex. `Add JWT authentication`)

**본문(선택)**:
- 변경 이유, 변경된 주요 내용

<br>

## 2️⃣ 브랜치 작성 및 관리 규칙

- **Flow**:  
  이슈 생성 → `Create branch` → 작업 → PR

- **브랜치 네이밍**:  
  `<이슈번호>/<타입>/<설명>`

  예시:
    - `208/feature/login-main`
    - `209/bugfix/fix-login-error`

- **브랜치 타입**:
    - `feature/`
    - `bugfix/`
    - `hotfix/`
    - `release/`
    - `refactor/`
    - `test/`
    - `chore/`
    - `wip/`

- **관리 브랜치**:
    - `main`: 항상 배포 가능한 상태
    - `develop`: 기능 통합 및 테스트

<br>

# 7. 🛠 포팅 매뉴얼

## 💻 시스템 요구사항

| 항목            | 버전                      |
|----------------|---------------------------|
| OS             | Ubuntu 22.04, Windows 11   |
| Java           | 17                         |
| Spring Boot    | 3.4.4                      |
| Gradle (Groovy) | 8.13                      |
| MySQL          | 9.2.0                      |

<br>

## 🔧 의존성 및 라이브러리

```groovy
implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
implementation 'org.springframework.boot:spring-boot-starter-web'
compileOnly 'org.projectlombok:lombok'
developmentOnly 'org.springframework.boot:spring-boot-devtools'
runtimeOnly 'com.mysql:mysql-connector-j'
annotationProcessor 'org.projectlombok:lombok'
testImplementation 'org.springframework.boot:spring-boot-starter-test'
testRuntimeOnly 'org.junit.platform:junit-platform-launcher'

// Security & JWT
implementation 'org.springframework.boot:spring-boot-starter-security'
implementation 'io.jsonwebtoken:jjwt-api:0.12.5'
implementation 'io.jsonwebtoken:jjwt-impl:0.12.5'
implementation 'io.jsonwebtoken:jjwt-jackson:0.12.5'

// Swagger
implementation 'org.springdoc:springdoc-openapi-starter-webmvc-ui:2.7.0'

// Validation
implementation 'org.springframework.boot:spring-boot-starter-validation'