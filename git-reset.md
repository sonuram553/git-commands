## Git Reset

---

The git reset command is a powerful and versatile command in Git that allows you to reset your repository's state to a specific commit or a previous state. It can be used to move the branch pointer to a different commit, discard changes, unstage files, or even remove commits from the branch history.

---

This option moves the branch pointer to a specific commit while keeping the changes from the commits after that commit. It does not modify the staging area or working directory.  
`git reset --soft HEAD~1`

This is the default option when no mode is specified. It moves the branch pointer to a specific commit, resets the staging area to match that commit, but keeps the changes in the working directory.  
`git reset [--mixed] HEAD~1`

This option moves the branch pointer to a specific commit and resets both the staging area and the working directory to match that commit. It discards all changes made after the specified commit.  
`git reset --hard HEAD~1`

The reflog keeps track of all the changes to the branch's references, including commits, merges, and resets.  
`git reflog`
