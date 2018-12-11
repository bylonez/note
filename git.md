# git command

## delete all local branch that merged into master
git branch --merged master | xargs git branch -d
