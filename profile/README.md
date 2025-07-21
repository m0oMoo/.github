
# 🧩 m0omoo

**m0omoo**는 사용자가 자유롭게 대시보드를 생성하고 패널(차트/위젯)을 배치할 수 있는 **커스터마이징 대시보드 플랫폼**입니다.  

<br/>

## 🚀 프로젝트 소개

- 사용자가 직접 생성한 **대시보드에 원하는 차트와 위젯을 배치**할 수 있도록 지원
- 패널의 **위치, 크기, 속성 설정을 실시간 반영**
- 추후 다양한 형태의 **스냅샷 및 공유 기능 확장** 예정
- 현재는 **백엔드 API 개발 중**

<br/>

## ⚙️ 백엔드 기술 스택

| 분류 | 스택 |
|------|------|
| Language | Java 17 |
| Framework | Spring Boot 3 |
| Build Tool | Gradle |
| Database | MySQL |
| Auth | JWT 기반 인증 |

<br/>

## ⚛️ 프론트엔드 기술 스택

| 분류         | 스택                         |
| ---------- | -------------------------- |
| Language   | TypeScript                 |
| Framework  | Next.js (App Router)       |
| State      | Zustand                    |
| Styling    | Tailwind CSS, CSS Modules  |
| UI Library | React Tabulator, Chart.js  |
| Auth       | JWT 기반 인증 (백엔드 연동)         |

<br/>

## 📌 주요 기능

### ▸ 사용자 인증 및 계정 관리
- 이메일 기반 회원가입 및 로그인
- JWT 토큰 기반 인증 처리
- 비밀번호 변경, 회원 탈퇴

### ▸ 대시보드 기능
- 사용자별 대시보드 생성 / 조회 / 수정 / 삭제
- 대시보드 복제 및 이름/설명 변경

### ▸ 패널 관리
- 대시보드 내 패널(차트/위젯) 생성 / 수정 / 삭제
- 패널 드래그 위치 및 크기 정보 저장
- 패널 속성 변경 및 타입별 렌더링 지원

### ▸ 기타 기능 (예정)
- 대시보드 상태 스냅샷 저장
- 알림, 활동 로그 등 확장 기능 고려 중

<br/>

## 🖼️ 대시보드 예시

> 아래는 m0omoo 대시보드 UI 입니다.
<img width="1917" height="913" alt="image" src="https://github.com/user-attachments/assets/c017e054-ee14-4ed6-b498-77d55d26a148" />
<img width="1915" height="911" alt="image" src="https://github.com/user-attachments/assets/b44a3a8d-5cff-4db3-9fc9-1ef2cd4192d0" />

<br/>
<br/>

## 🛠️ 디렉토리 구조

```

m0omoo-backend/
├── src/
│   ├── main/
│   │   ├── java/com/m0omoo/...
│   │   └── resources/
│   └── test/
├── build.gradle.kts
└── README.md
```
<br/>

```
m0omoo-frontend/
├─ app
│  └─ dashboard    
├─ components
│  ├─ table        
│  └─ chart        
|
├─ types
│  └─ app.ts        
└─ styles
   └─ globals.css
```

<br/>

## 👨‍💻 개발자 노트

본 백엔드 프로젝트는 1인 개발로 진행되며, 프론트엔드 구현은 이미 완료된 상태입니다.  
지속적으로 API 기능을 확장해나가고 있으며, 코드 품질 및 유지보수성을 고려한 설계를 지향합니다.

<br/>

## 📬 문의

> 관련 문의는 GitHub Issue 또는 아래 연락처로 주세요.  
> 이메일: [6suyeon@email.com]  



