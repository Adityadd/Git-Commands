# Git commands

initial setup `with git config –global user.name "[name]"`<br>
              `git config –global user.email "[email address]"`

### 1. `git init`<br>
    creates a local git repo in current directory
### 1. `git add .`<br>
    adds all the files/folders (except those in .gitignore) [the file will go from untracked/unstaged to tracked/staged and ready to commit]
### 1. `git status`<br>
    shows status on each files (tracked/staged/modified etc.)
### 1. `git remote add`*`unique_remote_name link`*<br>
    used to link remote repo to the local one [unique_remote_name is generally *origin*]
### 1. `git push`<br>
    to push the changes/commit to the remote repo [if the branch already exists on the remote repo]
### 1. `git push --set-upstream`*`unique_remote_name branchname`*<br>
    used(when the branch is not there on remote repoinitially) to create a branch on remote repo and then push the files there [only git push will fail if the remote repo doesn't have the branch]
### 1. `git commit -m`*` "message"`*<br>
    to commit the changes
### 1. `git branch`*`branchname`*<br>
    used to create a branch on local repo
### 1.  `git checkout`*`branchname`*<br>
    used to checkout a branch(move to that branch)
### 1. `git merge`*`branchname`*<br>
    to merge a branch to the current one
### 1. `git log`<br>
    shows commit history
### 1. `git pull`<br>
    to get the changes from the remote repo to local