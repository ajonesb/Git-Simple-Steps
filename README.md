
# Git Simple Steps For Everyday Development

 Here's some very quick steps I gathered for setting up Git, getting up and running with your project from updating, creating branch, checking out branches, merging branches, merge issues, pull issues, pushing branches to repository, etc.


- git clone - clone branch

- git pull origin - updates

- git checkout  -b - create new branch

- git add . - add files to stage

- git commit -m "" - commit files with messages

- git commit --all -m "message here" - Merge pain issues, merge all and commit all.

- git merge "name of dev branch" - merge new branch with dev

- git push origin "name of branch" - push changes to repo

- git push -f origin master - If you confirm that your new code is all fine. 
Where -f stands for "force commit" (or if on another branch, git push -f <repo name> master)

- git stash - save work

- git stash apply - add saved work to new branch if neeeded

- git reset --merge  If you've decided that whatever merge you were trying to do was a bad idea after all, you can put things back to normal 

- git fetch --all - git fetch downloads the latest from remote without trying to merge or rebase anything.
- git reset --hard origin/master - git fetch downloads the latest from remote without trying to merge or rebase anything.


*** Remove git ignore and other unneccessary files that you dont wanna commit in git status que: ***

The series of commands below will remove all of the items from the Git Index (not from the working directory or local repo), and then updates the Git Index, while respecting git ignores. PS. Index = Cache

First:

- git rm -r --cached . 
- git add .

Then:

- git commit -am "Remove ignored files"



