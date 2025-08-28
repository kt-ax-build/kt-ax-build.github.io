# KT AX Build TF

![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> AI 혁신을 통해 미래를 선도하는 KT AX Build TF 의 공식 웹사이트입니다.

## 🚀 프로젝트 개요

KT AX Build TF는 AI 기술을 활용한 혁신적인 솔루션 개발과 AI 문화 확산을 목표로 하는 태스크포스입니다. 본 웹사이트는 우리의 주요 업무와 프로젝트를 소개하는 메인 플랫폼입니다.

### 🎯 주요 업무 영역

1. **🧠 Agile 기반 AI Lead 개발**
   - 애자일 방법론을 활용한 혁신적 AI 솔루션 개발
   - 빠른 프로토타이핑과 지속적 개선

2. **🎓 AI 활용 문화 전파**
   - 조직 내 AI 역량 강화를 위한 교육 및 워크샵
   - 해커톤 및 경진대회를 통한 AI 친화적 문화 확산

## 🌐 웹사이트 구조

```
kt-ax-build.github.io/
├── index.html              # 메인 페이지
├── styles.css              # 스타일시트
├── bootcamp/               # kode:vibe Bootcamp 사이트
└── hackathon/              # kode:vibeJam Hackathon
```

## 🛠️ 기술 스택

- **Frontend**: HTML5, CSS3
- **Design**: Modern CSS with animations and interactions
- **Icons**: Font Awesome 6
- **Fonts**: Inter, JetBrains Mono (Google Fonts)
- **Deployment**: GitHub Pages with GitHub Actions

## ✨ 주요 기능

### 🎨 디자인 & UX
- 반응형 디자인 (Mobile-first approach)
- 다크/라이트 테마 지원
- 부드러운 애니메이션과 트랜지션
- 인터랙티브 요소 (호버 효과, 클릭 이펙트)

### 📱 인터랙션
- CSS 기반 애니메이션과 트랜지션
- 호버 효과 및 변형 애니메이션
- 플로팅 카드 애니메이션

### 🔧 기능
- CSS 기반 모바일 네비게이션
- SEO 최적화

## 🚀 배포

### GitHub Pages 자동 배포

이 프로젝트는 GitHub Actions를 통한 자동 배포가 설정되어 있습니다:

- **자동 트리거**: `main` 또는 `master` 브랜치에 push 시
- **수동 트리거**: GitHub Actions에서 `workflow_dispatch` 이벤트로 수동 실행
- **배포 URL**: `https://kt-ax-build.github.io/`

### 로컬 개발

```bash
# 프로젝트 클론
git clone https://github.com/kt-ax-build/kt-ax-build.github.io.git
cd kt-ax-build.github.io

# 로컬 서버 실행 (Python 3)
python -m http.server 8000

# 또는 Node.js 사용 시
npx serve .

# 브라우저에서 http://localhost:8000 접속
```

## 📁 서브 프로젝트

### 🎓 kode:vibe Bootcamp
- **URL**: `https://kt-ax-build.github.io/bootcamp/`
- **설명**: AI 에이전틱 기술을 활용한 현대적 소프트웨어 개발 방법론 교육 과정
- **기술**: MkDocs Material, Python, uv

### 🏆 kode:vibeJam
- **URL**: `https://kt-ax-build.github.io/hackathon/`
- **설명**: AI 혁신을 위한 해커톤 및 경진대회 플랫폼
- **기술**: (추후 업데이트 예정)

<div align="center">
  <p><strong>🤖 AI Leading Innovation with KT AX Build TF 🚀</strong></p>
  <p>Made with ❤️ by KT AX Build Task Force</p>
</div>
