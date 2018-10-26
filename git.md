使用git在本地新建一个分支后，需要做远程分支关联
关联目的是在执行git pull, git push操作时就不需要指定对应的远程分支
	git branch --set-upstream-to=origin/remote_branch  your_branch