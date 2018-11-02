# Git Tutorial M43B

## Getting started

##### 한 컴퓨터당 하나씩 설정
```Bash
$ git config --global user.name "Da Hoon"
$ git config --global user.email "crysis1@naver.com"

```
<hr>

| Command                                    | Description                                 | Example                                    |
| ------------------------------------------ | ------------------------------------------- | ------------------------------------------ |
| `$ git init`                               | .git 디렉토리 생성 및 초기화                | `$ git init`                               |
| `$ git add <File>`                         | untracked 된 <File>을 staging or tracking   | `$ git add index.html`                     |
| `$ git add <Path>`                         | untracked된 <Path>안의 전체 파일을 tracking | `$ git add .`                              |
| `$ git commit`                             | staging or tracking된 파일을 버전만들기     | `$ git commit -m "message"`                |
| `$ git status`                             | git 현재 상태를 알려주는 git 명령어         | `$ git status`                             |
| `$ git remote add origin "github address"` | git remote Repository 생성                  | `$ git remote add origin "github address"` |
| `$ git push <remote> <master>              | git push함으로써 백업 및 공유               | `$ git push origin master`                 |

##### 이외 내용
* SCM : Source Code Management
* git과 github는 다르다.
