# git_test



## 开发流程

拉去项目代码到本地

git clone https://github.com/git1998-zhu/git_test.git
cd 项目名称 进入拉去得项目


每日开发流程

1：拉去最新代码

git pull

2:开发

啊是大多数

3：下班前

git pull 拉取云端最新代码

git add . 添加到缓存
git status 查看状态
git commit -m "本次提交代码注释"

git push 推送到云端 （你开发的模块已经在云端了， 别人也可以拉去你的代码了）





分支开发：
添加分支： git branch 分支1


老大说我们在test1分支下开发
切换到test分支 git checkout test1
拉取代码： git pull origin test1

开发

提交

git add .
git commit -m "注释"
git push origin test1 推送到对应分支到云端





冲突产生 ： 别人开发代码提交到云端， 你没有拉取最新代码就git push ， 就会因为版本不一致，产生冲突

解决 ： git pull 拉去最新代码，  商量，删除=====HEADe之类得没用得东西

git push


分支：
老大说我们要在
