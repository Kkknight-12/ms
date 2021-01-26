# how to clone repo

**_git clone https:git@github.com:userName/repoName.git_**

## create new branch

### `git branch branchName`

## or

_-b for new branch_

### `git checkout -b branchName`

## command to see all the branches

### `git branch -a`

## change branch

### `git checkout branchName`

## push the branch to git

### `git push --set-upstream origin branchName`##

# delete branch

## delete before merge

### `git branch -D branchName`

## delete after merge

###`git branch -d branchNAme`

## merge to master

first go back to master branch
**git checkout master**
than
**git merge branchName**
