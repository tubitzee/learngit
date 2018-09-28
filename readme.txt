Git is a distributed  version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.

first time to push commit to github.

creating a new branch is quick. 

git commamd record:
1.git reflog       :查看命令历史。
2.git commit -a -m :提交已追踪的文件，并添加msg。
3.git add          : 添加新追踪文件；添加已追踪文件到stash。
4.git reset --hard [HEAD,commit_id] :切换文件版本[版本回退]。
5.git status      : 查看仓库状态。
6.git log         : 查看commit历史。
7.git diff        : 对比文件差异。
8.git reset HEAD filename : 撤消暂存区的文件，返回工作区，不提交。
9.git checkout -- filename : 丢弃工作区的修改[本质：用版本库的版本替换工作区的版本，一键还原]。
10.git rm                  : 删除文件并且提交到暂存区【撤消删除使用：git reset HEAD filename】
11.git push [origin master]:推送本地仓库到远程，origin代表远程仓库分支，mater代表本地仓库分支。 
12.git clone[address]      :克隆仓库到当前执行命令的地方。















