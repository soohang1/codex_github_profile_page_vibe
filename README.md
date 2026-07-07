# GitHub Pages 개발자 포트폴리오

순수 HTML, CSS, JavaScript로 만든 한국어 원페이지 개발자 포트폴리오입니다. GitHub Pages의 프로젝트 사이트 배포를 기준으로 모든 리소스 경로를 상대 경로로 작성했습니다.

## 파일 구조

- `index.html`: 포트폴리오 콘텐츠와 섹션 구조
- `styles.css`: 반응형 레이아웃과 시각 디자인
- `script.js`: 모바일 메뉴와 현재 섹션 내비게이션 상태
- `assets/hero-workspace.png`: 히어로 이미지
- `assets/og-image.png`: Open Graph 이미지
- `.nojekyll`: GitHub Pages에서 Jekyll 처리를 건너뛰기 위한 파일

폰트는 Pretendard Variable을 CDN으로 불러오며, 로딩이 실패하면 시스템 폰트로 표시됩니다.

## 교체할 샘플 값

- 이름: `백은기`
- GitHub: `https://github.com/soohang1`
- LinkedIn: `https://www.linkedin.com/in/eun-ki-baek-8201b21b6`
- 이메일: `soohang1@naver.com`
- 프로젝트 저장소 링크와 프로젝트 설명
- `assets/hero-workspace.png`, `assets/og-image.png`

## 로컬 확인

`index.html`을 브라우저로 직접 열어 확인할 수 있습니다. 별도 빌드 도구나 패키지 설치가 필요 없습니다.

## GitHub Pages 배포

```powershell
git init
git branch -M main
git add .
git commit -m "Add portfolio site"
git remote add origin https://github.com/soohang1/codex_github_profile_page_vibe.git
git push -u origin main
```

GitHub 저장소의 `Settings` → `Pages`에서 `Deploy from a branch`, `main`, `/root`를 선택합니다.

배포 URL 형식:

```text
https://soohang1.github.io/codex_github_profile_page_vibe/
```
