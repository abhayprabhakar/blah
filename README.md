# blah

## Initialize git repo
```bash
git init
git vi hi.txt
git add hi.txt
git commit -m "mesa"
git log --online --decorate
```
## Create new branch
```bash
git branch
git checkout -b feature-branch
vi hi.txt
git add .
git commit -m "message here"
git checkout master
git merge feature-branch
git log --online --decorate
```
## Stash
```bash
git checkout -b newbranch
vi hi.txt
git add .
git stash save "message"
git checkout master
git stash apply

```
## Clone
```bash
git clone <repository_url>
git log
```
## Fetch and Rebase
```bash
git init
git remote add origin <url>
git fetch origin
git rebase origin/main
git log --oneline
```

## Collaboration
```bash
git checkout -b feature-branch
vi hi.txt
git add .
git commit -m "Message"
git checkout master
git merge feature-branch -m "message"
git log
```

