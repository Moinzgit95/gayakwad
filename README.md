# gayakwad 
mkdir tom
cd tom
git init
git config --global user.email
git config --global user.name
touch loginpage.java
git status
git add loginpage.java 
git status 
git commit -m "First commit:added source code file for login page module"
git status

git branch feature-branch
git checkout feature-branch
touch homepage.java
touch loginpage.java
git status
git add .
git status
git commit -m "first commit:added source code file for home and login page"
git status
git checkout master
git merge feature-branch
ls

git branch feature_branch
git checkout feature_branch
touch homepage.js
git add homepage.js
git stash save "frist stash : stashing homepage module"
git checkout master
touch profilepage.js
git commit -m "second commit: add source code file for profile page module"
git checkout feature_branch
git stash list
git show stash
git stash apply
git commit -m "first commit: added source code file for homepage module"
git status 

