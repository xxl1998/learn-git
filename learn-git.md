# git命令笔记

## 创建本地git仓库并上传到github

```shell
#打开git bash
#进入对应目录   cd命令
mkdir learn-git
cd learn-git
touch learn-git.md
#使用typora打开markdown文件，随便写点什么
git init
#生成SSH key并添加到github
git remote -v

git remote add origin git@github.com:xxl1998/learn-git.git

git remote -v

git status

git add .

git commit -m "first commit"

#在github网页创建同名仓库
git push -u --set-upstream origin master
```

