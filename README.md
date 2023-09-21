 # Git Cheat Sheet and Branching Practice


 ## Basic Commands
 * `git init` - initialize local Git repo
 * `git add fileName` - stage changed file `fileName`
 for commit
 *`git commit -m "message"` - commit staged changes, with commit message "message"
## Info Commands
 * `git status` - show status of working directory
 * `git log` - list local commit hstory
 * `git log --oneline` - list local commit history in compact form

 ## Branching Commands
 * `git branch` - list local branches
 * `git branch -m newName` - rename current branch to `newName`
 * `git branch branchName` - create local branch `branchName`
 * `git chickout branchName` - switch to local branch `branchName`

 ## Remote Commands
 * `git remote add origin url` - configure `url` as a remote repo, with alias `origin`
 * `git push origin branchName` - push local commits to remote repo ` origin` on branch `newBranch`