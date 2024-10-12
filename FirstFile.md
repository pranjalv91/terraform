<!--- 
This is a test file with instructions for first commit from local branch 'main' to remote repo 'origin'
--->

## Instructions
---

1. Go to the directory where git needs to be initialized
	**cd "C:\Users\Pranjal Verlekar\Documents\VisualStudioCode\terraform"**

2. Command to initialize git in a working directory
	**git init**

3. Add remote repository
	**git remote add origin https://github.com/pranjalv91/terraform.git**

4. Verify the remote repository
	**git remote -v**

5. Add changes to the staging area
	**git add .**
	
6. Check the status of your changes
	**git status**
	
7. Commit the changes to local repository with a commit message
	**git commit -m "First commit from local terraform directory to terraform repository"**
	
8. Check which branch are you using on your local
	**git branch**
	
<!--- 
Should return "master" as the local branch which is not correct. It should be "main" and not "master"
The branch needs to renamed from master to main in local.
And an upstream connection needs to be made from local branch 'main' to remote repo branch 'origin/master'
This will be done in the next few steps below.
--->	
 
9. Rename local branch from master to main
	**git branch -m master main**

10. Remove any connections from origin repository
	**git fetch -p origin**

11. Create an upstream from main branch in local to master branch in remote repository "origin"
	**git branch -u origin/master main**

12. Push changes from local branch 'main' to remote repository 'origin' 
	**git push -f origin main**
	
<!--- Use the -f option to force push changes only for the first time from the main branch to remote repo 'origin' --->