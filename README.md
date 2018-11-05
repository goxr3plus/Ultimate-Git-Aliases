# Ultimate-Git-Aliases
Ma personal favourite git aliases for every day coding . In order for some commands to work on Linux maybe you have to slightly modify them . For example instead of `"` you need to add `'` on bash .

#### Good to know
I will add more and more aliases on the future and modify this read me file . Feel free to pull request if you want some of your own to be added here :)

#### On windows CMD and PowerShell

**1** Git status : `git st`
> git config --global alias.st status

**2** List all aliases : `git logA`
> git config --global alias.logA "!git config --get-regexp alias"

**3** Add all and commit : `git ac "Your message"`
> git config --global alias.ac "!git add -A && git commit"

**4** Pretty log all commits : `git lg`
> git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"

**5** Pretty log only the releaase tags : `git tags`
>git config --global alias.tags "git log --no-walk --tags --pretty='%h %d %s' --decorate=full"

[More recommendations](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) from official git tutorials .

#### --------- Remove Git Aliases---------

[Stackoverflow tutorial](https://stackoverflow.com/questions/23512402/how-can-i-delete-a-git-alias)

>git config --global --unset alias.aliasName

For example

>git config --global --unset alias.st
