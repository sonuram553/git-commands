## Git Commands

---

show manual page for a verb(like config, add or branch)  
`git help <verb>`

get concise help output for a verb(like config, add or branch)  
`git <verb> -h`

initialize git repository in local directory  
`git init `

copy a Git repository to local system  
`git clone <url> [<newDirectoryName>]`

`git status [--short|-s]`

add files to staging area  
`git add <path>|.`

un stage a file or files  
`git restore --stage <file>|.`

discard changes from a file or files in the working directory  
`git restore <file>|.`

create a commit  
`git commit [-m <message>]`

commit modified files directly without using git add command  
`git commit -a`

update last commit  
`git commit --amend`

remove a file and stage the deletion  
`git rm <file>`

if the file is modified or in staging area then use the force removal
`git rm -f <file>`

remove a file from git tracking  
`git rm --cached <file>`

rename a file and stage the changes  
`git mv file_from file_to`

if you want the default behavior of git (fast-forward if possible, else create a merge
commit)  
`git config --global pull.rebase "false"`

if you want to rebase when pulling  
`git config --global pull.rebase "true"`

fetch data from remote repository to local repository  
`git fetch [<remote or url>]`

fetch from remote branch and merge to local branch  
`git pull [<remote> <branch>]`

push local branch's commits to the remote branch  
`git push [<remote> <branch>]`
