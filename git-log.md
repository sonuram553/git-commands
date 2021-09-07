## Git Log

---

prints below each commit entry a list of modified files, how many  
files were changed, and how many lines in those files were added and removed  
`git log --stat `

--graph adds a nice little ASCII graph showing your branch and merge history  
`git log --online --graph`

this command works with lots of formats — specify date like "2008-01-15", or a  
relative date such as "2 years 1 day 3 minutes ago".  
`git log --since=2.weeks`

`git log --until=2.weeks`

--author option allows you to filter on a specific author  
`git log --author author_name`

--grep option lets you search for keywords in the commit messages  
`git log --grep keywords`

-S option will show the last commit that added or removed a reference to a specific function  
`git log -S function_name`     

if we specify a directory or file name, we can limit the log output to commits that introduced a change to those files.  
`git log -- file_path`

to prevent the display of merge commits cluttering up your log history, simply add the log option --no-merges.  
`git log --no-merges`   


