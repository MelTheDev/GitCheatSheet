## GIT BASICS
To Initialize Git repository

    git init

Add files to staging
    
    For Individual File:
        git add <file>

    For adding everything
        git add .  (dot will add everything)

Check git status
    
    git status

Reset (Unstage a staged file)
    
    git reset <file>

Check difference with staged and with not unstaged
    
    git diff

Commit staged changes

    git commit -m "some commit message here"

Lists branches available
    
    git branch

To create new branch
    
    git branch <new branch name>

Switch to another branch

    git checkout <branc_name>

To merge a branch with another branch

    git merge <branch_name>

Check git logs (Shows all commits to a currently selected branch)
    
    git log

For pushing to remote

    git push <alias> <branch>

To pull from remote

    git pull <alias> <branch>

To Fetch all the branches to local

    git fetch <alias>

Add remote git URL

    git remote add <alias> <url>
