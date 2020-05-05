# Repository to test tools 

Git collaboration workshop

- 'git clone <URL>': downloads the repository from the web to our compueter
	- Make sure yo don't nest this command in another repository
	- Just like 'git init´ do this only once per repository

## Branches

- 'git branch <branch_name>': creat a new branch
- 'git switch <branch_name>': move to a branch
	- 'git checkout <branch_name>': old way of moving to branch

- 'git switch -c <branch_name>': create and move in 1 command
	'git checkout -b <branch_name>'

- 'git stash': To make a temporary commit to not lose changes before moving to other branches
	'git stash apply' to apply the last stash from the stack
	'git stash list'
	'git stash clear'

## Pull requests (Online Merge)

- 'git push origin <branch_name>': pushes branch to the remote
	- this is where you will create the PR (online)
	- you merge the PR (and also the branch) by accepting and merging the PR
	- don't forget to clean up your branches
- 'git fetch --prune': cleans up references in your 'git log --oneline --graph --all --decorate
- 'git branch -d <branch_name>': delete branch on you local machine
	- it will tell you to move to another branch (e.g., master) first


