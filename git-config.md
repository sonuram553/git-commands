## Git Config

---

Git configuration local to a project  
path - .git/config  
list all configuration  
`git config --local --list|-l`

Git configuration for a specific user  
path - ~/.gitconfig  
list all configuration  
`git config --global --list|-l `

Git configuration for all users on a system  
path - `<path>`/etc/gitconfig  
list all configuration  
`git config --system --list|-l` 

To view configurations from all three places, optionally we can display source of each configuration with `--show-origin `  
`git config --list|-l [--show-origin]`

opens config file in an editor  
`git config [--local|--global|--system] --edit|-e` 

show or set value of the property-name  
`git config [--local|--global|--system] <property-name> [<value>]`

A property can appear in multiple config files. Display which file Git is using to set the value of the property  
`git config --show-origin <property-name>`
