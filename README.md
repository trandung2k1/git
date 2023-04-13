I - Status

1.  Tracked
2.  Untracked

II - Staging

1. git status - git add filename.extension: Staged
2. git rm --cached filename.extension: Unstaged
3. git add .
4. git add --all
5. git add -A

IV. Other

1. git status --short
    - ?? Untracked files
    - A files added to stage
    - M Modified files
    - D Deleted files

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

X. Delete branch

1.  Remote: git push origin -d dev
2.  Local: git branch -d dev
