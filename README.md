# Lit-Git-Aliases
Ma personal favourite git aliases for every day coding . In order for some commands to work on Linux maybe you have to slightly modify them . For example instead of `"` you need to add `'` on bash .

#### Good to know
I will add more and more aliases on the future and modify this read me file . Feel free to pull request if you want some of your own to be added here :)

#### On windows CMD and PowerShell

Git status : `git st`
> git config --global alias.st status

List all aliases : `git logA`
> git config --global alias.logA "!git config --get-regexp alias"

Add all and commit : `git ac "Your message"`
> git config --global alias.ac "!git add -A && git commit"

Pretty log all commits : `git lg`
> git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
