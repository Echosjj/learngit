1.学习git init, git add, git commit
2.回退过去：git log (查看提交历史）, git reset --hard HEAD^
3.回到未来： git reflog（查看命令历史）, git reset --hard commit_id
4.缓存区
5.工作区
6.git diff HEAD -- readMe.txt 查看当前版本与仓库最新版的不同
7. 撤销修改：（1）git checkout -- <file> 撤销在工作区的修改 （2）git reset HEAD <file> 撤销缓存区的修改， git checkout -- <file> 撤销工作中的修改
8.删除文件
   git rm <file>, git commit -m ""
9.创建分支，切换分支，删除分支
10：git branch <name> 创建分支， git checkout <name> 切换分支， git checkout -b <name> 创建并切换分支