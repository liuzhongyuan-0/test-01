# GIT命令

## 1.仓库初始化

```shell
git init
```

## 2.文件放入暂存区

```shell
git add 文件名
git add .
```

## 3.文件提交到仓库

```shell
git sommit -m "文件描述"
```

## 4.查看文件状态

```shell
git status
git status -s
```

## 5.撤销对文件的修改

```shell
git checkout -- 文件名
```

## 6.把暂存区的文件移除

```shell
git reset HEAD 文件名
git reset HEAD .
```

## 7.跳过暂存区，直接提交到仓库

```shell
git sommit -a am "文件描述" 
```

## 8.移除文件

```shell
# 从 Git仓库和工作区中同时移除 index.js 文件
git rm -f index.js
# 只从 Git 仓库中移除 index.css，但保留工作区中的 index.css 文件
git rm --cached index.css
```

## 9.查看历史记录

```shell
git log
```



