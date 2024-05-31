# git-command-cheatseets
1. Set the user name 

git config --global user.name "Your Name"

2. Set the user email

git config --global user.email "your.email@example.com"

3. Check the user name

git config --global user.name

4. check the user email

git config --global user.email

5. Check the git version

git --version

6. check current branch

git branch --show-current

git status

7. check the all branch

git branch -a

8. check the remote version

git remote -v

9. rename the remote orgin

git remote rename origin newname

10. how to commit 

git commit -m "Your commit message"

11. how to add signle file for commit

git add filename

12. how to add all file for commit

git add .

13. how create new branch 

git branch new-branch-name

14. how to change branch

git checkout branch-name

git switch branch-name

15. how to copy one branch to another branch

git checkout -b new-branch-name source-branch-name
git switch -c new-branch-name source-branch-name

16.How to merge code 

git checkout target-branch
git merge source-branch

git checkout main
git merge feature-branch

17. How to set git repo to change or rename current repo

git remote set-url origin reponame



