# MISGA-2018-Training
Codebase of MISGA 2018 training sessions

### Link to Thilan's directory
http://45.55.251.175/matrix2018/

### Bootstrap themes
- https://adminlte.io
- https://startbootstrap.com/template-overviews/sb-admin-2/

### Related links
- w3scholls.com
- jquery.com
- Placeholder.com

### Notes
- If you're using any templates move the following folders to a new structure (folder) for easy management  
    * Browser components
    * dist
    * Index.html 

- PHP frameworks
    * https://laravel.com/
    * https://codeigniter.com

- Useful Git commands
    * Remove all remote branches that have been deleted from GitHub
    `git fetch —prune `
    * To update the changes from Master
    ` git checkout b1`
    `git merge master` 
    Or
    `git fetch`
    `git rebase origin/master`
    Merging would mean a commit would be created for the merge, while rebasing would not.
    * the most recently made commit is the HEAD commit.
    `git show HEAD`
    * Restores file to previous commit
    `git checkout HEAD filename`
    * To unstage that file from the staging area
    `git reset HEAD filename`  
    * To rewind to the previous commit. Using the first 7 characters of the SHA of a previous commit
    `git reset commit_SHA`
    * New branch
    `git branch new_branch`
    * To switch to a different branch
    `git checkout branch_name`
    * Used to join a file changes from one branch to another
    `git merge branch_name`
    * Delete branch
    `git branch -d branch_name`
    * Creates a local copy of a remote
    `git clone`
    * Lists a Git project’s remotes.
    `git remote -v`
    * Fetches work from the remote into the local copy
    `git fetch`
    * Merges origin/master into your local branch.
    `git merge origin/master`
    * Pushes a local branch to the origin remote.
    `git push origin <branch_name>`
