Git guideline:  
	* git --version: check version git  
 * git config -global user.name "your_username": input your username
 * git config -global user.email "your_email": input your email  
 	* Create a new repository on the command line
 - 1: git init: create local repository (eg: .git)
 - 2: git status: show status
 - 3: Create file .gitignore in folder on website: gitignore.io - we don't want some file upload to github which in .gitignore
 - 4: git add .: upload all include .gitignore
 - 5: git add *: upload which is new without .gitignore
 - 6: git add file_want_to_upload: upload which file we want to upload
 - 7: git commit -m "write_your_comment": upload files and reasons
 - 8: git remote add origin https://github.com/name_your_project
 - 9: git push -u origin main: main/master is depend on you  
	* Upload new something in folder in initial computer
 - 1: git add * or git add file_want_to_upload
 - 2: git commit -m "write_your_comment"
 - 3: git push -u origin main
	* Upload new something but the project in Github had something new before
 - 1: git pull: take new thing
 - 2: git add *
 - 3: git commit -m "write_your_comment"
 - 4: git push -u origin main
	* Download project but not yours:
 - git clone https://github.com/name_project
	* More:
 - git branch: show which branch where project is (eg: main/master/...)
 - git branch -b name_branch: create new branch
 - git checkout name_branch: move to name_branch
 - git merge name_branch: merge name_branch into branch
 - cd my-project: move to my-project
 - git branch -M main: move to main branch