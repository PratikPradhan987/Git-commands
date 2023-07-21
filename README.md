# Git-commands
```
basic git commands I use 
	1. Git config -l  :   / --list
	2. Git init
	3. Git status 
	4. Git add (filename)
	5. 
	6. Git diff (commit number/message) 
	7. Git log : shows list ok all previous commits
	8. Git branch 
	9. Git diff -cached : difference between current staged and previous commit 
	10. Git checkout (commit number) : go to commit stage in project 
	11. Git checkout (branch name) : back to head eg(Git checkout master) 
	12. Git log --graph/Git log --graph --oneline/Git log --oneline
	- Branching 
		a. Git branch (branch name) : created new branch 
		b. Git checkout (branch name) : switch branches 
		c. Git branch : shows all branches 
		d. Git log --graph -oneline --all : --all will be used in remote git 
		e. Git merge (branch name) : merges the (typed)branch to the active branch
		f. Git branch -d (branch name) : delete a branch 
		g. Git checkout -b (branch name): create and switch to a new branch
	- Stash
		a. Git stash : saves tracked modified files(cleans your history)
		b. Git stash apply : applies latest stash to current code
	- Remote cloud Storage (Github)
		a. Git remote -v : shows remote access list
		b. Git push (remote name) (branch name) /Git  push origin master : add to remote branch
		c. Git push origin (local branch name):(remote name)/Git  push origin dev:developer
		d. Git fetch 
		e. Git merge 
		f. Git pull (remote name) (branch name)/Git pull origin master : fetch and merges latest changes
		g. Git clone (remote url)
		
```
![image](https://github.com/PratikPradhan987/Git-commands/assets/71559227/d5c85e4f-f313-4f7e-b946-daca8c765429)
