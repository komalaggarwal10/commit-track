to configure git:
git config --list
git config --global user.name "username"
git config --global user.email "user@gmail.com"

to clone a repo
git clone "repo-link"

to check status of the code
git status
four types of status are: untracked, modified, staged, unmodified

to list files in a folder: ls
to list all files(hidden also) in a folder: ls -a

to add all changes in staging area:
git add .

to commit changes to remote:
git commit -m "commit message"

to push changes to github:
git push origin main

to create a new git repo from terminal:
git init

to add remote link for repo:
git remote add origin <link>

to check current branch and view all branches:
git branch

to rename branch:
git branch -M main

to navigate to a different branch:
git checkout <branchname>

to create new branch:
git checkout -b <new branchname>

to delete branch:
git branch -d <branchname>

to compare differences in branches:
git diff <branchname>

to merge two branches:
git merge <branchname>

