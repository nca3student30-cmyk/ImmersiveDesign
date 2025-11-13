# Immersive Design

Google Stitch UI 디자인 프로젝트 - Railway 배포용

## 🚀 Railway 배포 방법

### 1. Railway 프로젝트 생성
1. [Railway](https://railway.app)에 로그인
2. "New Project" 클릭
3. "Deploy from GitHub repo" 선택
4. 이 리포지토리 선택

### 2. 자동 배포
- Railway가 자동으로 `package.json`을 감지하고 배포합니다
- 환경 변수 설정이 필요 없습니다 (기본 PORT 사용)

### 3. 커스텀 도메인 (선택사항)
- Railway 대시보드에서 "Settings" → "Domains"
- 커스텀 도메인 추가 가능

## 📁 프로젝트 구조

```
ImmersiveDesign/
├── index.html          # 메인 HTML 파일
├── styles.css          # 스타일시트
├── script.js           # JavaScript 파일
├── server.js           # Express 서버
├── package.json        # Node.js 의존성
├── railway.json        # Railway 설정
└── README.md          # 프로젝트 문서
```

## 🛠️ 로컬 개발

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm start

# 브라우저에서 http://localhost:3000 접속
```

## 📝 Google Stitch UI 파일 추가하기

1. Google Stitch에서 내보낸 HTML/CSS/JS 파일들을 프로젝트 루트에 추가
2. `index.html`을 업데이트하거나 새로운 HTML 파일로 교체
3. 변경사항을 커밋하고 푸시
4. Railway가 자동으로 재배포

## 🌐 배포 완료 후

배포가 완료되면 Railway에서 제공하는 URL로 접속할 수 있습니다:
`https://your-project-name.up.railway.app`

## 📞 지원

문제가 발생하면 Railway 문서를 참조하세요:
- [Railway Docs](https://docs.railway.app)
- [Railway Discord](https://discord.gg/railway)
