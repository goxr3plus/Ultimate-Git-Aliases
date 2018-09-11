# Lit-Git-Aliases
Ma personal favourite git aliases for every day coding . In order for some commands to work on Linux maybe you have to slightly modify them . For example instead of `"` you need to add `'` on bash .

#### Good to know
I will add more and more aliases on the future and modify this read me file . Feel free to pull request if you want some of your own to be added here :)

#### On windows CMD and PowerShell

List all aliases : Usage `git logA`
> git config --global alias.logA "!git config --get-regexp alias"

List all aliases : Usage `git ac "Your message"`
> git config --global alias.ac "!git add -A && git commit"
