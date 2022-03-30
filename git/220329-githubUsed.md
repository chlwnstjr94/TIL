# 220329

## git clone

### How to use

1. github에서 New repository를 생성한다.
2. 생성 후 Code버튼을 눌러 나타난 URL를 복사한다.
3. git Bash에서 저장할 폴더로 이동한다.
4. `git clone URL 주소`를 붙여넣어준 후 엔터를 누른다.
5. ls를 눌러 폴더가 만들어 졌는지 확인한다.

## git add, commit, push

1. 원격저장소와 연결된 원하는 폴더에 들어간다.
2. touch README.md와 같이 파일을 추가해준다.
3. vi README.md로 vim으로 내용을 추가해준다.
4. git status로 상태를 확인한다.
5. Changes not staged for commit 메세지를 확인했으면 `git add README.md`를 해준다.
6. git status로 확인하여 Change to be commit 메세지와 밑에 파일이 초록색으로 변한 것을 확인한 후 git commit을 해준다.
7. git commit을 입력 후 엔터를 치면 제목과 내용을 쓰는 창으로 넘어가는데 알맞은 제목과 내용을 적은 후 완료한다.
8. git status로 확인해 Your branch is ahead of 'origin/main' by 1 commit 이라는 메세지를 확인했다면 완료된 것이다.
9. 그 후 이제 원격저장소로 보내주기 위해 `git push origin main`을 눌러 원격저장소로 push 해준다.
