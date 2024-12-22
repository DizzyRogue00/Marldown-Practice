## Git 撤销操作
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