# git tutorials
## build repository in git
* git cd folder_name

* git ls  
browser all files in this folder

* git init  
initialize a repository in designed folder.
## add files
* git add file_name  
add file to local repository from workspace
* git commit -m "text for explain"  
commit all files you add to the repository.
* git status  
show the status of your local repository about your changes
* git diff file-name
show the diffience of this file between the local and romoto repository
* git log  
show the submmit log
* git reflog
show the command log
* HEAD  
present version
* HEAD^
earily version
* HEAD^^ or HEAD~2
two earily version
* git reset --hard HEAD 
* ![Working Directory and repository](https://www.liaoxuefeng.com/files/attachments/919020037470528/0)
* git checkout -- file_name  
abandon the changes in workspace
* rm file_name  
delete the file in your local repository rather than the repository
* git remote add origin git@github.com:michaelliao/learngit.git  
add remote repository
* git push origin master  
push the current branch to the remote repository 
* git clone git@github.com:michaelliao/gitskills.git  
clone the remote git
* git checkou -b dev  
equals to  
git branch dev  
** create branch dev 
git checkout dev
* git checkout dev  
switch to branch dev
*  git merge dev  
update branch master to dev
* git branch -d dev  
delete the branch dev
* git switch -c dev  
create and switch to branch dev  
-c: create 
