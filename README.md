# 使用github搜索

awesome xxx //找百科全书

xxx sample //找例子

xxx starter /xxx boilerplate //找空项目架子

xxx tutorial //找教程



# 使用git

## 偷代码

git clone 



## 告诉新建的文件夹要用git管理

git init 



## 测试一下提交

//全部提交到缓冲区 暂存区

git add . 

//单次提交 

git add 2.py



//提交到仓库

git commit -m "加备注" 


## 回滚

git reset HEAD //reset定向到

git chackout HEAD main.py //回退到main.py最后一次提交的版本

git chackout main.py //没有提交前 从缓冲区退回到工作区



## 查看git提交日志

git log  



## 从当前分支为基础新建分支

//创建分支a b

git checkout -b a 

git checkout -b b



## 切换回master主分支

git checkout master



## 合并分支a

git merge a


## 合并有冲突自己难以决策时 放弃当前合并

git merge --abort



## 看当前有哪些分支

git branch



## 完成的分支删除

git branch -D a



## 连接github

github新建仓库有提示



## 推送到远程

git push



## 拉取远程

git pull

# vscode
终端使用bash
插件下载 gitlens