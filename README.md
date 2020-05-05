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

- 'git fetch --prune': To clean up inexistent references.

