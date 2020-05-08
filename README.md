B2: Change 1 -> committed on B2
B2: Change 2 -> committed on B2

#Git collaboration workshop

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

## Working with Git steps

1. Create a new branch
2. Edit the readme file (use the pr branch notes)
	- add/commit changes
3. Push the branch to the remote (github)
4. Create the PR
5. Look around
6. Merge the PR
7. Delete the branch on github
8. Go to master on local computer
9. Pull merged changes
10. Clean up all the branches on github and computer
