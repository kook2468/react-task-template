# react-task-template

프론트엔드 과제용 React 템플릿 프로젝트입니다.  
React + TypeScript + Vite 기반으로 구성되어 있으며, TailwindCSS, Zustand, React Query 등의 실무형 스택을 포함합니다.

## 🚀 기술 스택

| 범주             | 사용 기술                 |
| ---------------- | ------------------------- |
| 기본 세팅        | React + TypeScript + Vite |
| 스타일링         | TailwindCSS               |
| 상태관리         | Zustand                   |
| 데이터 패칭/캐싱 | React Query               |
| HTTP 통신        | Axios                     |
| 라우팅           | React Router              |
| 배포             | Vercel                    |

## 📁 폴더 구조

```
src/
┣ assets/     # 정적 리소스
┣ components/ # 공통 UI 컴포넌트
┣ features/   # 도메인별 기능 모듈 (ex. community, product)
┣ hooks/      # 커스텀 훅
┣ services/   # API 요청 및 비즈니스 로직
┣ stores/     # 전역 상태 관리
┣ types/      # 전역 타입 정의
┣ App.tsx     # 앱 전체 구조 설정
┗ main.tsx    # 애플리케이션 진입점
```

## 🛠 사용법

```bash
npm install
npm run dev
```
