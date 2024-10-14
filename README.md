### How to initialize git?
- To initialize git in local repository use the below command
    `git init`


### How to remove .git from local repository?
- For removing .git from local repository use `rm -fr .git`


### How to check the modification or changes in repository?
- For check changes use `git status`


### How move file in staging area?
- To add all files and folders use `git add -A` or `git add --all`
- To add all files in current directory `git add .`
- To add all files but not deleted ones `git add *`
- To add indivisual files `git add file_name`
- To add same type files `git add *(extension)` like to add all JavaScript file `git add *.js`

### How to unstage from staging area?
- To go back from staging area use `git reset`

### How to commit file thats are in staging area?
- To commit the file use `git commit -m "message"` in message area just give a suitable message

### How to unstage after commit?
- For going back after commit use `git reset HEAD~`

### How to roll back deleted file?
- To do that use `git reset --hard`

### How to remove file but keep file in staging area?
- To do that use `git rm file_name`

### How to the branches in local repository?
- To do that use `git branch`

### How to create new branch?
- To create new branch `git branch branch_name`

### How to switch branch?
- To switch branch `git checkout branch_name`


### How to merge two branch?
- To merge two branch `git merge branch_name -m "message"`

