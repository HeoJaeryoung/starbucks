# git 정의

git은 코드의 변경 이력을 기록하는 프로그램(오타 수정)
github는 MS사에서 git을 인터넷에서 사용할 수 있게 해주는 소프트웨어이자 사이트

```bash
#기초 코드
git add . # .gitignore에 기재된 내용 뺴고 현재 폴더 내에 있는 모든 파일들을 트래킹하겠다는 의미
git add <파일명 혹은 폴더명> # 특정 파일이나 폴더를 트래킹 목록에 추가하겠다는 의미
git commit -m "메세지" #
```

```bash
# 세팅된 이후에는 아래 명령어 통해서 원격 저장소로 바로 보낼 수 있음
git add .
git commit -m "메세지"
git push
```
