git status
git add *
git commit -m "comment"

git add '*.txt'   	//add all text files 
git log

//GitHub
 git remote add origin https://github.com/try-git/try_git.github.com
 git push -u origin master

 git pull origin master //download or pull from github

 //check difference
 git diff HEAD
 git diff --staged


 git reset //unstage files
 git checkout -- octocat.txt 		//not too 

 //Create a branch
 git branch new_branch 		//create the new_branch
 git branch 				//view branches
 git checkout new_branch 	//switch to new_branch

//Removing files
git rm '*.txt'				//remove all .txt files
git rm -r folder_files 		//remove a folder 

//if files were deleted without git rm, use:
git commit -am "Delete stuff"   //to auto use git rm while commiting

//Switch to master and merge changes from a branch
git checkout master
git merge new_branch

//Delete a branch
git branch -d new_branch

//Push to remote repository
git push

//add all (two versions)
git add *
git add --all
