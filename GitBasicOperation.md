## Git 与github连接
```
本地
git init
git remote add origin xxx
git branch -m main
git add xxx
git commit -m
git push -u origin main
```
## Git 撤销操作
撤销commit，不撤销add
```
git reset --soft HEAD~1
```
撤销commit，撤销add
```
git reset --mixed HEAD~1
```
撤销 commit、撤销 git add 。 操作、撤销修改代码
```
git reset --hard HEAD~1
```
```
git commit -m "initial comit"
git add forgotten_file
git commit --amend
```

```
add后没有commit
git reset HEAD file_name
```

#### 创建标签
附注标签
```
git tag -a v1.4 -m "my version 1.4"
git show
```
轻量标签
```
git tag v1.4-1w
```
后期打标签
```
git log --pretty=oneline
git tag -a v1.2 部分校验和
git tag
git show v1.2
```
显示共享标签
```
git push origin v1.5
git push origin --tags
```
删除标签
```
git tag -d <tagname> #删掉本地仓库的标签
1. git push <remote> :ref/tags/<tagname> #远程仓库删除标签
2. git push origin --delete <tagname>
```
####远程分支
删除远程分支
```
git branch -d LocalBranchName
git push origin --delete remoteBranchName
```
