## Basic Commands
 * `git init` - initialize local Git repo
 * `git add fileName` - stage changed file `fileName`
 for commit
 * `git commit -m "message"` - commit staged changes, with commit message "message"
 * `git commit -m "message"` - commit staged changes, with commit message "message"

 Basic info commands and local commit history

## Info Commands
 * `git status` - show status of working directory
 * `git log` - list local commit hstory
 * `git log --oneline` - list local commit history in compact form
 * `git config --lost` - show config settings for local repo format
 * `git log --pretty` - lost local commit history in prettyish format


 ## Branching Commands
 * `git branch` - list local branches
 * `git branch -m newName` - rename current branch to `newName`
 * `git branch branchName` - create local branch `branchName`
 * `git chickout branchName` - switch to local branch `branchName`
 * `git checkout -b branchName` - create and switch to `branchName`
 * `git config -- list` - show config settings for local repo


 ## Remote Commands
 * `git remote add origin url` - configure `url` as a remote repo, with alias `origin`
 * `git push origin branchName` - push local commits to remote repo ` origin` on branch `newBranch`
 * git push -u origin `branchName` -push and make `origin` the defual remote for further `git push`
 * `git pull origin branchName` into current local branch