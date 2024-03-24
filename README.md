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

4.git clone url link

5.cd amazon
 ls
 git fetch
 ls
 git rebase origin

6. same as 2nd exp but
   in git merge command so
   git merge feature-branch -m "first merge:merging feature-branch into master" --no-ff

7. git checkout master
 git tag v1.0
 git tag
 git tag -a v1.1 -m"tag for release ver 1.1"
 git show v1.0
 git tag -l "v1.*"
 git push origin v1.0
 
8.mkdir Git cherry picking
cd Git cherry picking
git init
vi alpha.txt
git add . | git commit –m “1st commit”
vi beta.txt
git add . | git commit –m “2st commit”
vi gamma.txt
git add . | git commit –m “3st commit”
git reflog //It shows all commit history
git add .
git status
git commit –m “all deleted”
git reflog
git cherry-pick id //----add commit history id eg:34946d4------
git log // it show all commit history with commit id

