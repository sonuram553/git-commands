## Git Tag

---

display tags  
`git tag [--list|-l]`

filter tags  
`git tag --list|-l <search-term>`

Create a tag to the commit to which the HEAD is pointing or pass a commit's checksum  
create annotated tag  
`git tag -a <tag-name> [commit-checksum] -m <message>`

create lightweight tag  
`git tag <tag-name> [commit-checksum]`

Use -f flag to replace an already existing tag  
`git tag [-a] -f <tag-name>`

show tag details along with the commit that was tagged  
`git show <tag-name>`

By default, the git push command doesn’t push tags to remote servers.  
`git push <remote> <tag-name>`

push all tags at once  
`git push <remote> --tags`

checkout a tag
`git checkout <tag-name>`

delete a local tag  
`git tag -d <tag>`

delete a remote tag  
`git push <remote> --delete <tag>`
