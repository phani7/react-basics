## GIT COMMANDS

1. git init (for initializing the git )
2. git remote add origin "git repo url" (for creating the repo in the local)
3. git add . (to add that files to the remote repository)
4. git commit -m "name of the changes"
5. git branch -m  main (to creating the branch)
6. git push -u origin main (the main branch)

-------------------------------------------------------

## CREATING BRANCHES 

1. git branch (to identify the current working branch)
2. git checkout branchname (for switching the branch)

## CREATING NEW BRANCH 


1. git checkout -b branchName (for new branch)


## AFTER CREATING A NEW BRANCH AND CHANGES WE NEED TO PUSH THE DATA TO MAIN BRANCH

1. git checkout 
2. git add .  (for adding the chnages to the staging area.)
3. git commit -m "name of the changes" 
4. git push -u oringin newbranch name 


## HOW TO MERGE THE BRANCHES WITH THE MAIN 

1. git checkout Day1(main)
2. git merge Day2(sub branch)
3. git push --set-upstream origin Day1