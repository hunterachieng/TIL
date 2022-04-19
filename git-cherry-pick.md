# Git Cherry pick

Cherry pick is used to pick out specific commits from a certain branch and merge them into a seperate branch.
  
 To make this happen, 

checkout to `master branch`

From the branch, create a new branch

`git checkout -b release-v4.11.5`

From this branch you can now cherry pick

`git cherry-pick {commit hash ie 23242fe}`

Success!!
  Happy coding!!
