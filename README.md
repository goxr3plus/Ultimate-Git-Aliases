![image](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

# Ultimate-Git-Aliases
Ma personal favourite git aliases for every day coding . In order for some commands to work on Linux maybe you have to slightly modify them . For example instead of `"` you need to add `'` on bash .

[Cmder](http://cmder.net/) is one of the best tools for console lovers ... it has everything .

## What is Git Alias?

Git Alias is a collection of git version control shortcuts, functions, and commands:

  * Shortcuts such as `s` for `status`.
  * Improvements such as `optimize` to do a prune and repack with recommended settings.
  * Topic branch flows such as `topic-start` to create a new topic branch using master.
  * Visualizations such as `graphviz` to show logs and charts using third-party tools.

#### Good to know
I will add more and more aliases on the future and modify this read me file . Feel free to pull request if you want some of your own to be added here :)

#### On windows CMD and PowerShell

 **1** Git status : `git st`

 `> git config --global alias.st status`

  =>**1.1** Git branch : `git br`

   `> git config --global alias.br branch`
 
  =>**1.2** Git checkout : `git co`

   `> git config --global alias.co checkout`
 
   =>**1.2.1** Git checkout - create new branch: `git cob`

    `> git config --global alias.cob checkout -b`
 
  =>**1.3** Git commit : `git c`

   `> git config --global alias.c commit`
 
  =>**1.4** Git push : `git ps`

   `> git config --global alias.ps push`
 
  =>**1.5** Git pull : `git pl`

   `> git config --global alias.pl pull`
 
  =>**1.6** Git fetch : `git fe`

   `> git config --global alias.fe fetch`
 
  =>**1.7** Git add all : `git aa`

   `> git config --global alias.aa add -A`
 
**2** List all aliases : `git logA`

`> git config --global alias.logA "!git config --get-regexp alias"`

**3** Add all and commit : `git ac "Your message"`

`> git config --global alias.ac "!git add -A && git commit"`

**4** Pretty log all commits : `git lg`

`> git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"`

**5** Pretty log only the releaase tags : `git tags`

`>git config --global alias.tags "git log --no-walk --tags --pretty='%h %d %s' --decorate=full"`

[More recommendations](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases) from official git tutorials .

#### --------- Remove Git Aliases---------

[Stackoverflow tutorial](https://stackoverflow.com/questions/23512402/how-can-i-delete-a-git-alias)

>git config --global --unset alias.aliasName

For example

>git config --global --unset alias.st

# Complete list taken from the console

``` java
alias.br branch                                                                                                                                  
alias.ci commit                                                                                                                                  
alias.st status                                                                                                                                  
alias.last log -1 HEAD                                                                                                                           
alias.visual !gitk                                                                                                                               
alias.dfw diff --ignore-space-change                                                                                                             
alias.lg !git log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit
alias.fc !git add -A && git commit                                                                                                               
alias.add-commit !git add -A && git commit                                                                                                       
alias.ac !git add -A && git commit                                                                                                               
alias.loga !git config --get-regexp alias                                                                                                        
alias.lg2 log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit    
alias.tags !git log --no-walk --tags --pretty='%h %d %s' --decorate=full                                                                         
alias.doggy !git log --oneline --decorate --all --graph                                                                                          
alias.c commit                                                                                                                                   
alias.p push                                                                                                                                     
alias.pl pull                                                                                                                                    
alias.fe fetch                                                                                                                                   
alias.ps push                                                                                                                                    
alias.cob !git checkout -b                                                                                                                       
alias.aliases config --get-regexp alias                                                                                                          
alias.aa add                                                                                                                                     
alias.co checkout                                                                                                                                
alias.bra br -a                                                                                                                                  
alias.fu fetch --prune                                                                                                                           
alias.d !git diff                                                                                                                                
alias.reb !git rebase -i                                                                                                                         
alias.cof !git co -f                                                                                                                             

```
