# git

## 최초 설정
커밋에 기록되는 사용자 정보
``` bash (터미널에 입력되는 코드)
- git config --global user.name '이름'
- git config --global user.email 'email'
```

## 로컬명령어
- `git init`
    - `.git` : git repository를 생성 하는 명령어
- `./  ../  .git/  assets/  git.md  linux-command.md  markdown.md` : 앞에 .이 붙으면 숨겨진 폴더라는 뜻
- `user@DESKTOP-F5S6PLJ MINGW64 ~/Downloads/git (master)`는 현재폴더는 master생성과 함께 깃 사용 준비완료

- `git add <file name>`
    - `working directory`에서 `staging area`로 추가
    - 일반적으로 모든 파일, 폴더를 한번에 추가하기 위해 아래의 명령어로 작성
    - `git add .` : .는 현재 폴더, 파일
- `git commit"`
    -  `staging area`에 올라간 파일들의 스냅샷을 찍어 `.git directory`에 저장 
    - `git commit -m "first commit"` : 일반적으로 -m 옵션을 넣어서 커밋메세지를 추가
    - `git commit -m "first commit(message)`

## 원격저장소
- `git remote`
    - 원격저장소 주소를 관리하기 위한 명령어
    - `git remote add original <url>`

- `git push`
    - 원격저장소에 로컬 코드를 업로드 하기 위한 명령어
    - `git push origin master`
    - `git push <remote> <branch>`    