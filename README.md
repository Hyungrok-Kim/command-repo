# Git Command 
> git 현재 설정 값들을 list 형태로 보여준다.
```git
git config --list
```
>git config 설정(global Option)
```git
git config --global user.name []
git config --global user.email []
```
>commit했던 버전들의 Author와 Date를 보여준다.
```git
git log
```
>commit했던 버전 모두를 보여준다.
```git
git log --all
```
>commit의 상세 히스토리 및 인접한 commit간 변화된 부분 보기 
```
git log -p
```
>해당 버전으로 checkout 받아진다.
```
git checkout [버전]
```
>가장 최근의 마스터 버전으로 다시 checkout 받아져서 되돌아간다.
```
git checkout master
```
>브랜치 생성 후 바로 해당 브랜치로 이동
```
git checkout -b [브랜치명]
```
>현재 Remote Repository 주소를 보여준다.
```
git remote -v
```
>해당 branch의 Project를 나의 프로젝트로 Merge
```
git pull origin [브랜치명]
```
>git의 모든 브랜치 확인
```
git branch
```
>Working directory 및 Staging Area 확인(파일 상태 확인 tracked, Untracked)
```
git status
```
>해당 디렉토리 기준으로 하위 디렉토리에서 발생한 변경 내용만 포함해서 Staging Area로 보내기
```
git add . || git add *
git add [파일명]
```
>현재 Working Directory 내의 모든 변경 내용을 전부 Staging Area로 보내기
```
git add -A
```
>각 변경사항을 터미널에서 확인하면서 Staging Area로 넘기거나 제외시키기 
```
git add -p
```
>브랜치 생성
```
git branch [브랜치명]
```
>브랜치 확인
```
git branch
```
>브랜치의 마지막 커밋 메시지 확인
```
git branch -v
```
>브랜치 삭제
```
git branch -d [브랜치명]
```

## git diff 

> 변화를 조금 더 잘 볼 수 있게끔
```
git diff --word-diff
git diff --color-words
```
>특정 파일과 특정 커밋 버전의 내용과 비교 
```
git diff [커밋 버전 hash] [파일명]
```
>특정 파일과 특정 커밋 버전 두 개의 내용 비교 
```
git diff [커밋 버전 hash] [커밋 버전2 hash] [파일명]
```
>특정 커밋 버전과 특정 브랜치의 가장 최신 버전과의 차이점 중 src/ 디렉토리 이하의 상대 경로상의 파일들 비교
```
git diff [커밋 버전 hash] [브랜치명] src/
```

# Linux Command
> CLI 비우기 
```linux
clear
```

> 폴더 및 파일 List  ls(List의 약자)  
```linux
ls
```
