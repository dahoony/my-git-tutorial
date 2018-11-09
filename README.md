# Git Tutorial M43B

## Getting started

##### 한 컴퓨터당 하나씩 설정
```Bash
$ git config --global user.name "Da Hoon"
$ git config --global user.email "crysis1@naver.com"

```

##### Git 기본 명령어
| Command                                    | Description                                 | Example                                    |
| ------------------------------------------ | ------------------------------------------- | ------------------------------------------ |
| `$ git init`                               | .git 디렉토리 생성 및 초기화                | `$ git init`                               |
| `$ git add <File>`                         | untracked 된 <File>을 staging or tracking   | `$ git add index.html`                     |
| `$ git add <Path>`                         | untracked된 <Path>안의 전체 파일을 tracking | `$ git add .`                              |
| `$ git commit`                             | staging or tracking된 파일을 버전만들기     | `$ git commit -m "message"`                |
| `$ git status`                             | git 현재 상태를 알려주는 git 명령어         | `$ git status`                             |
| `$ git remote add origin "github address"` | git remote Repository 생성                  | `$ git remote add origin "github address"` |
| `$ git push <remote> <master>`             | git push함으로써 백업 및 공유               | `$ git push origin master`                 |
| `$ git branch <branch name>`               | git branch를 생성함으로써 복사함            | `$ git branch about-page`                  |
| `$ git checkout <branch name>`             | git branch에 복사한 곳으로 변경             | `$ git checkout about-page`                |
| `$ git merge <branch name>`                | merge해야할 곳으로 가서 merge               | `$ git merge about-page`                   |
| `$ git branch -d <branch name>`            | branch 삭제(-D: 강제로 지우기)              | `$ git branch -d about-page`               |
| `$ git reset`                              | add하고 commit 하기 전 상태에서 되돌리기     | `$ git reset                               |
| `$ git rm -r --cached <file_name>`         | add나 commit 했는데 되돌리고 싶을 때         | `$ git rm -r --cached node_modules/`       |


<hr>

##### 이외 내용
* SCM : Source Code Management
* git과 github는 다르다.
* html:5 + tab키를 누르면 html 기본 양식 완성
* rebase 명령어는 지양하는것이 좋다.(무시)
* Markdown 언어 연습 및 활용 : <a href="https://typora.io/">Typora</a> 편집기 추천
