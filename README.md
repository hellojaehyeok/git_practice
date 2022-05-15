# git_practice

git 연습

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

# 브랜치 변경
git checkout <브랜드명>
```

### merge

```shell
# 병합할 브랜치에서 해야 한다.
git merge <가져올 브랜치명>
```
