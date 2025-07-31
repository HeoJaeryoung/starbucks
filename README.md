# git 정의

git은 코드의 변경 이력을 기록하는 프로그램 <br />
github는 MS사에서 git을 인터넷에서 사용할 수 있게 해주는 소프트웨어이자 사이트

```bash
#기초 코드
git add . # .gitignore에 기재된 내용 뺴고 현재 폴더 내에 있는 모든 파일들을 트래킹하겠다는 의미
git add <파일명 혹은 폴더명> # 특정 파일이나 폴더를 트래킹 목록에 추가하겠다는 의미
git commit -m "메세지" #
```

```bash
# 세팅된 이후에는 아래 명령어 통해서 원격 저장소로 바로 보낼 수 있음
git clone <인터넷 주소> #로컬에 경로로 복사
git pull # 원격저장소에서 내 경로로 (공동작업일 경우, 타인이 작업한 내용을 받아오고 싶을 때. 항상 명령어 입력하는 습관 들이기)
git add .
git commit -m "메세지"
git push
```

```bash
# 리엑트 프로젝트는 패키지 설치 후 사용 가능
npm install
npm run start
```

---

node_modules 는 패키지가 설치된 경로
