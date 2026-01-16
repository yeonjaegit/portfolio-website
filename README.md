# 🌐 Backend Developer Portfolio Website

간단하고 깔끔한 개인 포트폴리오 랜딩 페이지

---

## 🚀 GitHub Pages로 배포하기

### 1단계: GitHub 레포지토리 생성
1. GitHub에서 새 레포지토리 생성
2. 레포지토리 이름: `yeonjaegit.github.io` (중요! 본인의 GitHub 사용자명 사용)
3. Public으로 설정

### 2단계: 코드 푸시
```bash
cd portfolio-website
git init
git add .
git commit -m "Initial commit: Portfolio landing page"
git branch -M main
git remote add origin https://github.com/yeonjaegit/yeonjaegit.github.io.git
git push -u origin main
```

### 3단계: GitHub Pages 활성화
1. GitHub 레포지토리 → Settings → Pages
2. Source: `main` 브랜치 선택
3. Save 클릭

### 4단계: 접속
- 5분 후 `https://yeonjaegit.github.io` 에서 확인 가능!

---

## 📝 커스터마이징

### 이름 변경
```html
<h1>Backend Developer</h1>
<!-- 여기에 본인 이름 추가 가능 -->
```

### 기술 스택 추가/삭제
```html
<span class="badge">새로운 기술</span>
```

### 색상 변경
```css
/* 그라데이션 배경 */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* 다른 색상 예시 */
/* 블루-그린: linear-gradient(135deg, #667eea 0%, #06b6d4 100%); */
/* 오렌지-레드: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); */
```

---

## ✨ 포함된 기능

- ✅ 반응형 디자인 (모바일 최적화)
- ✅ 애니메이션 효과
- ✅ 그라데이션 배경
- ✅ 호버 효과
- ✅ 다크 모드 대응
- ✅ SEO 메타태그

---

## 🔗 링크 업데이트

현재 설정된 링크:
- 노션 포트폴리오: https://www.notion.so/Backend-Developer-Portfolio-d42284a0eb564b69873c9d2dfe62afcd
- GitHub: https://github.com/yeonjaegit
- 이메일: sba0613@naver.com

링크 변경은 `index.html`의 `<a href="...">` 부분을 수정하세요.

---

## 📧 Contact

이메일: sba0613@naver.com

---

**Last Updated**: 2026년 1월 16일
