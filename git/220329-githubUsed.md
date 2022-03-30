# 220329

## git clone

### How to use

1. github에서 New repository를 생성한다.
2. 생성 후 Code버튼을 눌러 나타난 URL를 복사한다.
3. git Bash에서 저장할 폴더로 이동한다.
4. `git clone URL 주소`를 입력해준다.
5. ls를 눌러 폴더가 만들어 졌는지 확인한다.
6. `git remote`와 `git remote -v`를 입력해 잘 연결 되어있는지 확인한다.

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
단, init으로 연결했을 시 상관관계가 다르게 연결되있으므로 ‘git push -u origin main’을 입력해 같은 상관관계 상태로 해준다. (-u: upstream set으로 다른 상관관계를 같게 해준다.), 한번 해주면 다음부터는 -u를 안적어도 된다.

## git init(clone 반대)

### How to use

1. git Bash를 열고 새로운 repository를 만들 폴더로 이동한다.
2. `mkdir 폴더명(first-repo)`를 입력하여 폴더를 만들어준다.
3. `git init`을 입력해 폴더를 repository로 만들어준다.
4. github에서 New repository에 들어가 repository 이름을 만든 폴더와 같은 폴더명으로 생성해준다.
5. 생성 후 Code버튼을 눌러 URL를 복사한다.
6. git Bash에 `git remote add origin URL주소`를 입력한다.
7. `git remote`와 `git remote -v`를 입력해 잘 연결 되어있는지 확인한다.
