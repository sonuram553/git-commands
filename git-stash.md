## Git Stash

---

stashes only tracked files  
`git stash`

stashes both tracked and untracked files  
`git stash -u`

list all stashes  
`git stash list`

apply last stash  
`git stash apply`

deletes last stash  
`git stash drop`

apply and then deletes last stash  
`git stash pop`

stashes tracked files with a custom message  
`git stash save <message>`

stashes both tracked and untracked files with a custom message  
`git stash save -u <message>`

deletes all the stashes  
`git stash clear`

For a particular stash  
`git stash [show | apply | drop | pop] stash@{<index>}`
