# 박요한 · 대학생활 기록

1학년부터 3학년 2학기까지 학교생활과 태도의 변화를 소개하는 정적 홈페이지입니다. 프로젝트 실적 나열 대신 학기별 배움, 협업, 성찰과 취미를 중심으로 구성했습니다.

홈페이지: https://ohan9i.github.io/yohan-portfolio/

GitHub 저장소: https://github.com/ohan9i/yohan-portfolio

## 바로 보기와 수정

- `dist/index.html`을 브라우저에서 열면 바로 볼 수 있습니다.
- 내용: `dist/index.html`, 디자인: `dist/style.css`, 사진: `dist/assets/`
- 설치나 빌드가 필요하지 않습니다. 모바일 레이아웃과 키보드 탐색을 지원합니다.

## 내용 근거

- 1학년 1학기: 진로설계와 자기이해의 교수님 면담·개인소감, 기초설계·실험 발표자료.
- 1학년 2학기: 수업계획서와 공학소양특강 일정표. 수강 완료나 성적을 단정하지 않았습니다.
- 2학년 1학기: 창의설계의 `제작 프로젝트를 통해 느낀점.docx`. 협업, 역할 분배, 실패와 사고방식에 대한 자기 성찰을 요약했습니다.
- 2학년 2학기: 철학과삶의 `건축공학과 221330 박요한.docx`, 데카르트 에세이 파일 및 전공 자료.
- 3학년 1학기: BIM 수업의 `모델링 발표자료.docx`, AI 스터디 발표자료와 전공·교양 폴더. 피아노·여행·게임·바위너구리 취향은 BIM 자기소개 대본을 근거로 했습니다.
- 3학년 2학기: `221330_박요한_구조계획.pdf`와 보관한 문헌 주제. 문헌 수집은 본인 저술 논문이나 연구 성과로 표시하지 않았습니다.
- 프로필: `2026얼굴.jpg`. 모형 사진: 창의설계 팀 발표 PDF 8쪽의 사진.

문장은 원자료를 바탕으로 홈페이지용으로 재구성했습니다. 타인의 보고서는 개인 경험으로 사용하지 않았습니다. 증명서·계좌·학번·원본 문서 전체는 배포하지 않습니다. 학기별 연도는 별도로 추정하지 않았습니다.

## Git

`main` 브랜치에는 전체 소스가 있고, `gh-pages` 브랜치에는 `dist` 폴더의 홈페이지 파일이 있습니다. GitHub Pages는 `gh-pages`의 루트(`/`)를 공개합니다.

수정 후 PowerShell에서 이 폴더로 이동하여 실행합니다.

```powershell
git add dist README.md
git commit -m "Update university life story"
git push origin main
git subtree push --prefix=dist origin gh-pages
```

마지막 명령은 `dist` 폴더만 배포 브랜치에 올립니다. GitHub의 Pages 배포가 완료되면 홈페이지에 반영됩니다. `.nojekyll`은 HTML과 CSS를 그대로 배포하도록 하는 파일입니다.

이 저장소와 홈페이지는 공개입니다. `.openai/hosting.json`은 이전 Sites 배포를 위한 설정이며 GitHub Pages에서는 사용하지 않습니다.
