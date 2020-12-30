# github-command

## Merging Development Branches into Master 
1. Add changes on your branch
2. Commit
3. checkout to master
4. git pull
5. checkout to your local branch
6. git merge master
7. solve conflict (if any)
8. git checkout master
9. merge your branch to master
10. git push

## Create a new branch in remote repository
* Create a new folder in your local machine
* cd 'your-folder-name'
* git init
* git remote add origin git://remote-github-repo-url.git
* git checkout -b new-branch-name 
* git push -u origin new-branch-name

## git pull from master
* git pull origin master

## push to master branch
*  git push origin master
