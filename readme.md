# Git Notes 

First! Make a .gitignore

## Commands

```
git init
git add <filename>
git commit -m 'Commit Message'
git add -A 
git status
clear
git branch
git checkout -b <new-branch-name> (-b create a new branch in it is not existing)
git checkout <branch-name> (is how we move from branches)
git remote add <origin> <url>
git push origin <branch-name>
git  tag -a <verison> -m "first release"
git reset --hard
```

## Common Workflows 

Regularly Committing 

```
git add -A
git commit -m 'Msg'
```

## Git Workflow

Branches:
- master
    - this is live!
- dev
    - Merge features into here for all teammates, and push to github
- feature-branch (Don't put spaces in folder)
    - Do the major dev here 

## Contributors 

- Kevin Pham