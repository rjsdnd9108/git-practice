# Git Practice

## 자기소개
안녕하세요! 동국대학교 컴퓨터공학전공 장건웅입니다. 현재 Git과 GitHub 실습을 진행하고 있습니다.

## 관심 분야
- Web
- Backend
- Frontend

## Git 명령어 정리
- git init: 로컬 Git 저장소를 생성하고 초기화합니다.
- git status: 작업 디렉토리와 스테이징 영역의 상태를 확인합니다.
- git add: 변경된 파일을 스테이징 영역(Staging Area)에 추가합니다.
- git commit: 스테이징 영역에 있는 파일들을 메시지와 함께 로컬 저장소에 기록합니다.
- git log: 지금까지 진행한 커밋 히스토리를 확인합니다.
- git branch: 브랜치 목록을 확인하거나 새로운 브랜치를 생성합니다.
- git switch 또는 git checkout: 다른 브랜치로 전환합니다.
- git remote: 원격 저장소를 연결하고 관리합니다.
- git push: 로컬 저장소의 커밋들을 원격 저장소(GitHub 등)로 업로드합니다.

## CLI 실습 기록
- 사용한 명령어 순서:
  git init
  git add README.md
  git commit -m [커밋 3회 실행]
  git checkout -b feature/profile
  git switch -c feature/profile
  git remote add origin https://github.com/rjsdnd9108/git-practice
  git push -u origin feature/profile
- 생성한 브랜치명: feature/profile
- 커밋 메시지 3개:
  Docs: Add README
  README 수정: 자기소개 작성
  README 수정: 관심분야 및 git 명령어 정리
- 어려웠던 점:
  GUI 기능으로 하면 직관적이라서 간단하게 할 수 있는 작업인데, CLI로 하니까 명령어가 익숙치 않아서 그런지 조금 시간이 걸린 것 같다.

## PR 실습 기록
- PR 제목:
- PR 링크:
- PR에서 수정한 내용:
- Merge 여부:
