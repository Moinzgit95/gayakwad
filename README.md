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
