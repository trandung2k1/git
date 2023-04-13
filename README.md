# Git + Github
I - Status
    1. Tracked 
    2. Untracked 
II - Staging
    1. git status
    2. git add filename.extension: Staged
    3. git rm --cached filename.extension: Unstaged
    4. git add .
    5. git add --all
    6. git add -A
III. Commit
    1. git commit -m"Content commit"

IV. Other
    1. git status --short
        a, ?? Untracked files
        b, A files added to stage
        c, M Modified files
        d, Deleted files
V. Log
    1. git log
VI. Support git
    1. git help --all
    2. git --help

VII. Branch
    1. git branch branchName - create new branch
    2. git branch - display all branches
    3. git checkout branchName - switched to branch
    4. git restore --staged filename.extension - unstage(using branch)
    5. git checkout -b branchName - shorthand
    6. git branch -d branchName - delete branch
VIII. Merge
    1. git merge branchName
    
IX. Pull vs fetch
    1. git pull origin branchName - fetch and merge
    2. git fetch origin
