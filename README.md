# git_practice

git 연습

### git alias

단축키 설정

```shell
vim ~/.gitconfig

----

[alias]
        s = status -s
        br = branch
        co = checkout
        ci = commit
```

### clone

```shell
git clone <URL>
```

### Log & status

```shell
git log
git status
```

### add

```shell
git add -file-
git add *
```

### commit

```shell
git commit -m <메시지>
# add + commit
git commit -am <메시지>
```

### push

```shell
git push <원격저장소명> <브랜치명>
```

### branch

```shell
# 브랜치 확인
git branch

# 원격 브랜치 확인
git branch -r

# 모든 브랜치 확인
git branch -a

# 새로운 브랜치 생성
git branch <브랜치명>

#  브랜치 삭제
git branch -D <브랜치명>

# 브랜치 변경
git checkout <브랜드명>

# 브랜치 생성 및 변경
git checkout -b <브랜드명>

```

### merge

```shell
# 병합할 브랜치에서 해야 한다.
git merge <가져올 브랜치명>
```

### fetch

```shell
# 변경 내용 가져오기
git fetch
```

### diff

```shell
# 변경 사항 확인
git diff

# 파일 사항 확인
git diff <파일명>
```
