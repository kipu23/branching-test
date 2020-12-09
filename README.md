# Git branching commands

https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging

## 1. create new repo on git with readme and clone it
	- git clone <repourl>

## 2. check branches
	- git branch			#only local branches
	- git branch -a		# remote-tracking and local branches
	
 ## 3. check remote
	- git remote -v

## 4. create branch
	- git branch <featurebranch>
	
5. switch to branch
	-  git checkout <featurebranch>
	
6. push new branch to remote
	- git push --set-upstream origin <featurebranch>
	
7. merge branch to master and push to remote
	- git checkout master
	- git merge <featurebranch>
	- git push
	
8. delete branch
	- git branch -d <featurebranch>								#delete local branch
	- git push origin :<featurebranch>						#push locally deleted branch to remote
	
	- git push origin --delete <featurebranch>		#delete on remote
