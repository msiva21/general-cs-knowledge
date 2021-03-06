# Useful `git` commands

## Reset the current git environment back to HEAD
* [Command] `git reset --hard`
* [My understanding] reset everything changed (*NOT* including untracked) and go back to `HEAD`.
* [Reference] https://git-scm.com/docs/git-reset.
 
## Switch to another branch after cloning a repo
* [Command] `git branch -a` following by `git checkout *<the-specific-branch>*`
* [My understanding] switch to remote branch (usually a newly cloned repo) that is not existent yet in local repo.
* [Reference] https://stackoverflow.com/questions/67699/how-to-clone-all-remote-branches-in-git

## Check difference between HEAD
* [Command] 
    * `git diff` for all the tracked files; 
    * `git diff <specific-file.*>` for a specific file;
    * `git diff --cached <specific-file.*>` to see already added changes in a specific file.
* [My understanding] just simply check what lines have been adeed, what have been deleted.
* [Reference] https://stackoverflow.com/questions/10039747/how-to-view-file-diff-in-git-before-commit