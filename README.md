
# Cheat Sheet GIT

### git branch
to see all branch :
`git branch -a`

to see remote branch
`git branch -r`

### git checkout
`git checkout -- discardMyChange.txt`

`git checkout -b development origin/development`

Create a branch from a tag :
`git checkout -b version2 v2.0.0`

Track a branch (which is automatically done 90% of the time) :
`git checkout --track origin/serverfix`

### git commit
Re-execute commit : 
`git commit --amend`

### git config
List config : `git config --list --show-origin`

Alias : `git config --global alias.co checkout`


### git diff
compare WD <> SA :
`git diff`

compare SA <> Last Commit :
`git diff --staged`

### git fetch
prune deleted remote branche
git fetch -p  

### git log
`git log --pretty=format:"%h - %an, %ar : %s"`

Delete a remote Branch
`git push origin --delete serverfix`

Delete a remote Tag :
`git push origin :refs/tags/webhook-0.1.0.7`

### git remote
`git remote -v`



### git reset
`git reset HEAD waitForCommit.txt`


### git rm
remove from SA but not in WD :
`git rm --cached .project`


### git tag
Lightweight : `git tag v1.2 && git push origin v1.2`

Annotated : `git tag -a v1.4 -m "my version 1.4" && git push origin v1.4`
