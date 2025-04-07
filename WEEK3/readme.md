# 3주차 기획서 - 개발 환경 세팅 및 기본 구조 구현

## 1. 주차 목표

- 개발에 사용할 환경과 도구 세팅
- 프로젝트 폴더 구조 설계
- 페이지별 라우팅 구성
- 화면 틀(Component) 기본 구현 시작

---

## 2. 개발 환경 및 기술 스택

| 구분 | 기술 스택 |
|------|-----------|
| 프론트엔드 프레임워크 | React (Create React App or Vite) |
| 스타일링 | Tailwind CSS |
| 상태 관리 | React useState (기본) |
| 백엔드 / 데이터베이스 | Firebase (Firestore + Authentication) |
| 배포 | Vercel |
| 협업 및 버전 관리 | GitHub |

---

## 3. 프로젝트 폴더 구조 (예정)

```bash
📁 src/
├── 📁 components/         # 재사용 가능한 UI 컴포넌트
├── 📁 pages/              # 각 라우트별 페이지 컴포넌트
│   ├── Home.jsx
│   ├── SelectGoal.jsx
│   ├── Roadmap.jsx
│   ├── Checklist.jsx
│   └── Progress.jsx
├── 📁 assets/             # 이미지, 아이콘 등 정적 자원
├── 📁 utils/              # 유틸 함수, API 연동 코드 등
├── App.jsx                # 전체 앱 라우팅
├── index.js               # 진입점
