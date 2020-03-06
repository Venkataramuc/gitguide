# Git guide

Github is code hosting platform for a version control.

This guide teachs you Github essentials like Repositories, Branchs , Commits and Pull requests.
# Git Stash  
git stash  
git stash pop # to apply recent stash.  
git stash --keep-index # to track the git add details also  
git stash --include-untracked  `# to track the untracked files means even newly added files. If you specify --include-untracked or -u , Git will include untracked files in the stash being created. `		  
git stash list `all the stash		`.   
git stash save "name of the stash" `# so we can capture  the name of the stash`    
git stash apply 1 # here we need to give id which we can see from git stash list 

git stash save "name of the stash" -k -u # to track the new & untracked files. 

# Git Log

git lg.   
git log --raw


# git Branch
git branch.   
git branch --list.  
git branch --no-merge    
git branch -merge   



