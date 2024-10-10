# Git
- version control system tools
- [Download Git Tools](https://git-scm.com/)
- install defualt
- check git version
  ```
  git --version
  ```
## Git configuration list 
```
git config --list
```
## Now check in vscode editor turminal 
```
git --version
```

# git clone url form github to store in your local
- copy url < https:// > from github and paste after git clone 
```
git clone
```
- modifies Files and Folders

## git Status to show file status 
```
git status
```
- cd to go directory and show all the files 

## type of file 
- untracked or new file 
- modified (somthing changed)
- staged (ready to commit)
- unmodified (no changed)
## add  ( git add < file name > or < . > for all files ) 
```
git add .
```
- check git status 

## commit (git commit -m "commit message " )
```
git commit -m "first commit"
```
## git push to upload files 
```
git push
```

- Go to check on github directory and files
  
# Now you can create directory from vscode and push on github 
- create file and directory 
- CD  go to directory 
- create .git file
``` 
git init 
```
- check files 
```
ls -a
```
## git remote add origin < link >
- git romote -v (to verify remote)
```
git remote -v
```
- git branch (to check branch)
```
git branch
```
- git branch -M main (to rename branch)
```
git branch -M main
```
- git push origin main or git push -u origin main
```
git push -u origin main
```

## type of file 
- untracked or new file 
- modified (somthing changed)
- staged (ready to commit)
- unmodified (no changed)
## add  ( git add < file name > or < . > for all files ) 
```
git add .
```
- check git status 

## commit (git commit -m "commit message " )
```
git commit -m "first commit"
```
## git push to upload files 
```
git push
```

- Go to check on github directory and files
  
# Branch Commands 
- git branch
- git branch -M main (to rename branch)
- git checkout < branch name> (to navigate)
- git checkout -b < new branch name> (to create new branch)
- git checkout -d < branch name >
## Merging Code or branch 
- git branch -d < branch > (to delete branch )
- git checkout main or other branch < branch name > (to use changing branch)
### way 1
- git diff < branck name> ( to compare commits, branches,files & more)
- git merge < branch name >
### way 2 
- create a Pull Requirest 
## pull Requirest  or Pull Command 
- git pull origin main ( used to fetch and download content from a remote repo and immediately update the local repo to match that content.)
## Resolving Merge Conflicts
- An event that takes place when Git is is unable to automatically resolve differences in code between two commits.
- git diff main 
- git merge main 
- git status 
## Undoing changes 
### case 1 : staged changes 
- git reser < file name >     (reset file for last changes  )
- git reset              ( all reset changes in multiple files )
### case 2 : commited changes ( for one commit )
- git reset HEAD-1 ( back to the last commit or like undo )
- check log 
```
git log
```

### case 3 Commited changes (for many commits)
- git reset < commit hash> ( you can undo with the hash code )
- git reset --hard < commit hash> ( you can undo inside the git and vscode )
## You can work on other project 
- find the project and create fork 
- create copy of master or main branch
- now you can work on this file and repo 
- changes marge on main project 
- pull Requirest marge to project main to my main branch ( this is use for bugs resolved )