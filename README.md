# Git practice command notes

## HEAD is a pointer to the current, move HEAD pointer
$ checkout + ID

## GUI
$ gitg 

## info
$ git log

## check git status
$ git status


## git color
$ git config --global color.ui auto


## commit file
$ git commit -a

## merge 
$ git merge master

## git log go out
$ q


## track file using git
$ git add .gitignore


## link github
$ git remote add origin https://github.com/CansenJIANG/git_practice.git

## where you want to synchronize with your github, git push
$ git push origin master 
$ username
$ password

## Always remember to checkout to the branch you want to modify
$ git checkout master
## merge only one point, git cherry-pick ID
$ git cherry-pick 8aac7fed4d818bf93de30121c766e139225afff0


## someone requested a pull, and aproved, you update your git using fetch command.
$ git fetch origin

## now you want to use the new master on github
$ git checkout master
$ git rebase origin/master


