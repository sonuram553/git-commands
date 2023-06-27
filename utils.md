## Reset local branch to the remote branch

Replace *your_branch_name* with the name of your branch that has diverged from the remote branch.

The `git fetch --all `command fetches the latest changes from all remote branches, and the `git reset --hard` command resets your local branch to match the state of the remote branch.

**Note:** This command discards any local commits and changes that are not present in the remote branch.

`git fetch --all`  
`git reset --hard origin/<your_branch_name>`
