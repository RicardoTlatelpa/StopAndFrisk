# StopAndFrisk
Data Mining Project

*Always make sure to `git pull`(to get the most recent changes) from other classmates.

# Git Branching

`git branch -a` to list all local and remote branches

`git checkout branch_name` to switch branches

`git checkout -b branch_name` to create and switch to the created branch

When you create any new changes in the repository, create a new branch with the name:

your_first_name-type_of_change

example: ricardo-jupyter-data-analysis

After your branch has been created, commit and push your new branch up into the repository.

Try to push up your branch as often as every change in order to avoid any merge conflicts.

# Merging Branches

`git checkout main` - to put yourself in the main branch

`git merge branch_name` - merge the branch you’ve been working on with the main branch

# Deleting Branches

### Delete branch locally

`git branch -d branch_name`

### Delete branch remotely

`git push origin --delete branch_name`

### Both Commands at the same time

`git push origin --delete branch_name && git branch -d branch_name`
