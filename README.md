# Practicegit 

# Git
Git is used to keep track of changes in the source code.

# Github
Github is used to host the source code.

# Git shortcuts

- git status -> Displays the state of the working dir.
- git add . ->  Adds a change in the working dir to the staging area.
- git commit -m "" -> Used to save changes to the local repo.
- git reset --soft <commit id> -> Keep the files and stage all changes back.
- git reset --hard <commit id> -> Completely destroy changes.
- git log -> Allows viewing the git log as graph.
- git diff -> To track the changes.
- .gitignore -> Used to ignore a file that commited in the past.
- .gitversion -> To know the specific version of the file.
- git checkout -b <branch name> -> To create new branch
- git branch -D <branch name> -> To delete the branch
- git branch -> Pointers to a snapshot of the changes.
- git checkout <branch name> -> Switch to a new branch
- git push -> Used to push the local repo.
- git pull -> Used to fetch and merge code changes.

## Merge conflict and how to solve it 
It's an event that takes place when git is unable to automatically resolve differences in code between two commits.

- git remote add origin <address>
- git pull origin master
- git status
- git add .
- git commit -m "commit message"
- git push origin master

## Git stash

- git stash pop -> throws away the topmost by default statsh after applying it.
- git stash apply -> leaves it in the stash list for possible later reuse.

## Git rebase

- git reabse -> Rebasing is the process of moving or combining a sequence of commits to a new base commit.
- git commit -a -m ""
- git rebase <base>
- git rebase --onto <>

To know more about git commands - https://www.atlassian.com/git/glossary
Git documentation - https://git-scm.com/docs/git.