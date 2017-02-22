# Git_Commands version 2
A list of command which are used very often.



## Git Configuation locally and globally




## Git Initiate
git init   (it initiate git inside project)




## Git Add Files

git add -A    (stages All files incluing new, modified and deleted)

git add .     (stages new and modified, without deleted)

git add -u    (stages modified and deleted, without new)

git add fileName  (in case you want to add a single file only)

git add *.html  (this will add all html file)


## Git Remove Files
git rm --cached fileName



## Git Commit
git commit -m 'your comment'




## Git Status
git status   (all files should be in green, if not then add using below command)




## Git Adding remote repository
git remote add origin https://github.com/sudheerpal/Git_Commands.git      (adding for first time)

git remote get-url origin                                                  (checking current remote URL)

git remote set-url origin https://github.com/sudheerpal/Git_Commands.git  (to set/change git remote to different URL)




## Git Push
git push -u origin master    (for the first time, when publishing code to remote repo)
git push      (can be used later)




## Git Pull





## Git Stash
git stash (making a backup of your changes, before pulling)

git stash apply (apply the changes, after new git pull)

git stash drop  (discarding the changes, after new git pull)


## Git Branching
git branch branchName    (creates a new branch)

git checkout branchName  (moves index to new branch)

git merge branchName     (its merges a branch to master branch, IMP. please make sure, you checkout to master branch before merging.)
