
## GIT Commands

### REMOVE REMOTE BRANCH and tracking info  

#### Remove branch locally   
- $ git branch -D branch_name  

#### Remove branch remotely  
- $ git push --delete origin branch_name  
  
#### Remove tracking info  
- $ git remote prune origin  
- $ git fetch -p   
 
git branch -rd $(git branch -a | grep -v 'master' | cut -d'/' -f2-10 | xargs)  
to remove all remote tracking branch excluding master

 
### PUSH TO REMOTE  

#### Push local branch to remote other branch  
- $ git push remote local_branch_name:remote_branch_name
 




