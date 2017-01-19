
### git checkout

`git checkout -- discardMyChange.txt`

Create a branch from a tag :
`git checkout -b version2 v2.0.0`

### git commit

Re execute commit
`git commit --amend`

### git config
`git config --global alias.co checkout`

### git remote
`git remote -v`

### git reset

`git reset HEAD waitForCommit.txt`

### git tag
Lightweight : `git tag v1.2 && git push origin v1.2`
Annotated : `git tag -a v1.4 -m "my version 1.4" && git push origin v1.4`
