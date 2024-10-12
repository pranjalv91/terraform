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

6. Rename local branch from master to main
	**git branch -m master main**

7. Remove any connections from origin repository
	**git fetch -p origin**

8. Create an upstream from main bracnh in local to master branch in remote repository "origin"
	**git branch -u origin/master main**

9. Commit the changes to local repository with a commit message
	**git commit -m "First commit from local terraform directory to terraform repository"**

10. Push changes from local branch 'main' to remote repository 'origin' 
	**git push -f origin main**