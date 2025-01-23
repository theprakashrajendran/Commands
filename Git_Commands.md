###############################################################################
# Useful Git commands
###############################################################################

git status
git checkout -b feature/{branchname}

Stagging
git add . or --all 			 To track all files
git add {filename}

git status 				 Files that have changes will be shown in green

To push file to server
git commit -m "{message}"

git push origin {feature_branch_name}

git checkout main 			 To go to current branch

git fetch 				 To sync server and local (all branches or changes) / will bring all the user changes done in the server to local repository

git pull origin main

git pull 				 (Change done in particular branch) after entering into branch

will pull all the files from server to local 


git checkout {branchname} 		 To enter into other branch


git merge {branch name} 		 To resolve merging conflicts ex: both user did change in same line


*Before merging, make sure to pull any changes from the server using git pull
To revert changes after commit
git checkout --filename 		 To revert changes to a specific file

git checkout --hard  			 To revert to the previous commit
git checkout -- filepath or name
git status

git branch 				 To see local branches
git branch -d {branch name} 		 To delete a local branch
git branch --delete {branch name} 	 To delete a server branch

gitignore 				 Mentioned files types in this file will not be tracked

After a pull request, the feature branch can be deleted


