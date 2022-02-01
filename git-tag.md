## Git Tag

---

display tags  
`git tag [--list|-l]`

filter tags  
`git tag --list|-l <search-term>`

create annotated tag  
`git tag -a <tag-name> [commit-checksum] -m <message>`

create lightweight tag  
`git tag <tag-name> [commit-checksum]`

show tag details along with the commit that was tagged  
`git show <tag-name>`

By default, the git push command doesn’t transfer tags to remote servers.  
`git push <remote> <tag>`

push all tags at once  
`git push <remote> --tags`

delete a local tag  
`git tag -d <tag>`

delete a remote tag  
`git push <remote> --delete <tag>`




