git status
git add *
git commit -m "comment"

//Git add and commit shortcut (will not add untracked files)
git commit -a -m "your message"

git add '*.txt'   	//add all text files 
git log

//GitHub
 git remote add origin https://github.com/try-git/try_git.github.com
 git push -u origin master

 git pull origin master //download or pull from github

 //check difference
 git diff HEAD
 git diff --staged

//unstage files
 git reset 
 git reset HEAD fild.md
 git checkout -- octocat.txt 		//Restore file to last state of commit 

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

//Git config
git config --global user.name "Anthony Ngene"
git config --global user.email ngeneanthony@gmail.com

//reset last commit 
git reset --soft HEAD^
git reset --soft HEAD^^ //reset the last two commits
git reset --hard HEAD^

git commit -amend -m 'message'


/*
* 	GIT REMOTE
*/

git remote -v 
