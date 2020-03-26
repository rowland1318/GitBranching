## Git Branching

### Overview

Overview and cheat sheet of Git commands. Introduction to branching.

### Basic Commands

* `git init` - Initialize local git repository
* `git add` - Stage local working directory for commit
* `git commit` - Commit staged files to local repo
* `git status` - Show status of repository
* `git rm --cached fileName` - Remove fileName from commit index
* `git log` - Show commit history
* `git log --oneline` - Show commit history (compact)

### Branching Commands

* `git branch` - List local branches, highlight checked-out branch
* `git branch branchName` - Create branch `branchName`
* `git checkout branchName` - Move to branch `branchName`
* `git checkout -b branchName` - Checkout branch `newBranch`, creating it if needed.
* `git push origin branchName` - Push local branch `branchName` to origin
* `git pull origin master` - Pull remote `master` into local branch (resolve conflicts)
