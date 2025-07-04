
## Initialize a Repository
git init

## Clone a Repository
git clone <repository-url>

## Check Status
```bash
git status

## Add Files to Staging
git add <file>
git add .

## Commit Changes
git commit -m "Your commit message"

## View Commit History
git log
git reflog

## Push to Remote Repository
git push origin <branch-name>

## Pull Latest Changes
git pull

## Create a New Branch
git branch <branch-name> // need testing
git checkout -b <branch-name>


## Switch Branches
git checkout <branch-name>

## Merge Branches
git merge <branch-name>

## Reset not pushed commit
git reset HEAD~1