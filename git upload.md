# git upload

1. 구글 검색창에서 `git bash download`를 검색해 다운로드 받습니다.

2. git bash에서 여러가지 명령어를 이용해서 올리고 싶은 파일이 있는 디렉토리로 이동합니다. 

   사용가능한 명령어

   - ls 현재 디렉토리에 있는 파일을 보여줍니다.
   - cd "디렉토리 파일 경로"
   - 

3. 다음과 같은 명령어를 입력합니다.

```bash
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

4. github.com에 로그인을 하고 repository로 이동입니다.
5. 다시 git bash에서 

```bash
  git add "파일 이름"
  git commit -m "comment"
  git remote add origin https://github.com/YoungChanShin/markdown.git
  git push -u origin master
```

실행하고 **로그인**하면 업로드 완료. 3번과 5번의 로그인은 처음 한번만 하면 된다. 