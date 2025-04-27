# App Template

Template to create apps as images

## Git Commands

### Clone repository

    git clone git@github.com:x-cute/app-template.git

### Check status of local repository

    git status

### Check status of local-remote repositories

    git fetch
    git status

### Send commit to remote (no review)

    git push origin HEAD:main

### Rebase (caused by later commits in github)

    git rebase origin/main
    
 Resolve all conflicts manually

    git add .
    git commit --amend
    git fetch
    git status

### Verify remote and local is up to date (You branch is up to date with orgin/main)

    git fetch
    git status
