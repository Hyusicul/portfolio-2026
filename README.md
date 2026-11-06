\# 박현 Portfolio



전북대학교 스마트팜학과 박현의 개인 포트폴리오입니다.



\## 사이트



https://hyusicul.github.io/portfolio-2026/



\## 소개



스마트팜과 인공지능을 결합하여 실제 농업 문제를

해결하는 기술에 관심이 있습니다.



\## 주요 프로젝트



\### PeachScope

\- 복숭아 RGB 영상 기반 품질 예측 Android 앱

\- Kotlin, Android, Python, FastAPI

\- 담당: 앱 개발 및 서버·AI 모델 연동



\### Blue Chat

\- 사용자 간 소통을 위한 채팅 애플리케이션

\- 사용자 인터페이스 설계 및 구현



\## 기술



\- Hugo

\- HTML / CSS / JavaScript

\- Git / GitHub

\- GitHub Actions

\- GitHub Pages



\## 로컬 실행



Hugo가 설치된 환경에서:



```powershell

cd site

hugo server

```



\## 배포



main 브랜치에 변경사항을 Push하면

GitHub Actions가 Hugo 사이트를 빌드하고

GitHub Pages에 배포합니다.



\## 사용 테마 및 라이선스



Hugo Profile 테마를 기반으로 개인화했습니다.



원본: https://github.com/gurusabarish/hugo-profile



\## 개발 및 실행 환경



본 사이트는 Hugo 정적 사이트 생성기와 Hugo Profile 테마를 이용하여 제작했습니다.



\- 운영체제: Windows

\- Hugo: 0.143.0

\- Git 및 GitHub

\- GitHub Actions

\- GitHub Pages



\### 로컬 실행 방법



1\. GitHub 저장소 복제



&#x20;  git clone https://github.com/Hyusicul/portfolio-2026.git



2\. 프로젝트 폴더 이동



&#x20;  cd portfolio-2026



3\. 테마 의존성 준비



&#x20;  git submodule update --init --recursive



4\. Hugo 버전 확인



&#x20;  hugo version



5\. 사이트 폴더 이동



&#x20;  cd site



6\. 로컬 서버 실행



&#x20;  hugo server



7\. 웹 브라우저에서 http://localhost:1313/ 접속



프로젝트에 포함된 테마 파일 및 설정을 유지한 상태에서 실행합니다.



\## 주요 파일 설명



\- site/hugo.yaml : 사이트 설정, 자기소개, 프로젝트, 메뉴

\- site/static/images/ : 프로필 사진, 프로젝트 로고, 파비콘

\- site/static/docs/ : 프로젝트 PDF 자료

\- site/static/viewers/ : PDF 열람 화면과 돌아가기 기능

\- .github/workflows/hugo-pages.yml : 자동 빌드 및 배포

\- README.md : 개발 환경과 실행 안내



\## 수정 및 자동 배포 방법



1\. site/hugo.yaml 등 수정할 파일을 편집합니다.

2\. 변경사항을 확인합니다.



&#x20;  git status --short

&#x20;  git diff --check



3\. 수정한 파일을 Git에 추가합니다.



&#x20;  git add site/hugo.yaml



4\. 변경 내용을 커밋합니다.



&#x20;  git commit -m "docs: update portfolio content"



5\. GitHub main 브랜치에 업로드합니다.



&#x20;  git push origin main



6\. GitHub Actions의 build 및 deploy 성공 여부를 확인합니다.



&#x20;  https://github.com/Hyusicul/portfolio-2026/actions



7\. 실제 배포 사이트에서 변경사항을 검사합니다.



&#x20;  https://hyusicul.github.io/portfolio-2026/



\## 문제 해결 및 검증



\- 빌드 실패: GitHub Actions의 build 로그에서 ERROR 메시지를 확인합니다.

\- 이미지 표시 오류: site/static/images/ 내부 파일명과 hugo.yaml 이미지 경로를 비교합니다.

\- PDF 오류: site/static/docs/ 및 site/static/viewers/ 경로를 확인합니다.

\- 화면 변경이 반영되지 않음: 배포 성공 여부를 확인하고 브라우저에서 강력 새로고침을 실행합니다.

\- 공백 오류: git diff --check로 확인한 뒤 수정합니다.



\## 사용 테마와 라이선스



Hugo Profile 테마를 기반으로 개인화한 포트폴리오입니다.



원본: https://github.com/gurusabarish/hugo-profile



원본 테마의 저작권 및 라이선스 고지를 유지합니다.
