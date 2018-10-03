Git is a distributed  version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.

first time to push commit to github.

creating a new branch is quick & simple. 

this is git stash test.
dev function develope stop.



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
13.git branch <name>       :创建分支。
14.git checkout <name>     :切换分支。
15.git checkout -b <name>  :创建+切换。
16.git merge <branch name> :合并分支。
17.git branch -d <name>    :删除分支。
18.git merge --no-ff -m    : merge with no fast forward.
19.git stash               :将不能提交的改动暂存起来，一般用于在开发分支上开发时，遇到需要修改bug，需要将当前不能提交的分支暂存，然后切换分支开发。否则当前进度会丢失。
20. git branch -d<D> <branchname> :删除分支。D为强制删除。 
21.git push origin branch-name :推送本地分支到远程分支。如果远程分支不存在，则在远程创建分支并拉取。
22.git checkout -b branch-name origin/branch-name :在本地创建和远程分支对应的分支。
23.git branch --set-upstream branch-name origin/branch-name:建立本地分支与远程分支的关联，便于拉取和推送。
24.git pull       ：从远程抓取分支。
25.git tag        : 查看标签历史。
26.git tag <name> ：打标签。
27.git tag -a -m  : 给标签添加备注。
28.git show <tagname> : 查看标签说明文字。
 








关于git在生产环境中的架构设计的猜想：
	有三个git环境：1.生产服务器本地，代码供用户访问。
		       2.代码托管服务器，供开发者提交和拉取代码，master提供给服务器拉取更新代码。
		       3.开发者本地，开发功能，提交代码到远程代码托管服务器。












