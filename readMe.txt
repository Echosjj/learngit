1.学习git init, git add, git commit
2.回退过去：git log (查看提交历史）, git reset --hard HEAD^
3.回到未来： git reflog（查看命令历史）, git reset --hard commit_id
4.缓存区
5.工作区
6.测试合并分支“”
6.git diff HEAD -- readMe.txt 查看当前版本与仓库最新版的不同
7. 撤销修改：（1）git checkout -- <file> 撤销在工作区的修改 （2）git reset HEAD <file> 撤销缓存区的修改， git checkout -- <file> 撤销工作中的修改
8.删除文件
   git rm <file>, git commit -m ""
9.创建分支，切换分支，删除分支
10：git branch <name> 创建分支， git checkout <name> 切换分支， git checkout -b <name> 创建并切换分支， git merge <name> 合并指定分支到当前分支， git branch -d <name> 删除分支
11.给远程仓库创建分支：（1）git branch <name> 创建本地分支（2）git push origin <name>把本地分支提交到远程仓库 （3）git branch -a 查看远程有多少分支
12.提交本地仓库代码到远程仓库： git push origin <name> (分支名称）
13.解决多人协作在远程造成的冲突： git pull, 解决冲突文件，git commit, git push origin <name>
14.tag： git tag <v1.0>本地仓库创建tag;  远程仓库创建tag： git push <branch-name> <v1.0>