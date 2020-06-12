# Git-tutorial
Git training



## Notes:
1. Distributed version control.
2. We can have both local and remote repository.
3. When ls -la is given in the terminal it gives the file and also **.git**.
This **.git** is repository which tracks all our changes.
4. Initiallizing the directory will make the git to track the changes.
5. To avoid certain files from adding to the repository , use **.gitignore** . This will create an ignore file , a text file which contains the extensions of the files which we want to ignore while committing.
6. There are three stages,
	  * working directory
	  * stagging Area
	  * .git directory(repository)
7. So whenever we have to  commit , it consist of two steps,
	* Commit changes 
		* $ git diff
		* $ git status
		* $ git add -A
		* $ git commit -m "Mention the change here! "
	* Then Push
		* $ git pull origin master
		* $ git push origin master
8. In the real time many persons will be working on the projects and there will be multiple changes made in the code.  ** $ git pull ** pulls all the changes made.

9. **origin** - Name of the repository and **master** is the branch
10. We can create a branch for desired feature.
11. **$ git branch** will display the branches in the local repo. 
12. The current working branch will be denoted by '*'.



Commands::grinning:

S.No|    Function                 |         Command
----|-----------------------------|------------------------
1   |Get git version              |$ git --version
2   |Set global user name         |$ git config --global user.name "name"
3   |Set global user email         |$ git config --global user.email "mail address"
4| get git config       |$ git config --list
5 | get help        | $ git config --help
6 | Initiate a repository from existing code | $ git init
7|list all the directories| $ ls -la
8| Remove the file from git tracking | $ rm -rf .git
9|get status | $ git status
10|Ignore files | $ touch .gitignore
11|Add all the files to staging area|$ git add -A
12| Add but ingore certain file types to staging area | $ git add .gitignore
13|Remove the files from the staging area | $ git reset "file name"
14|Remove the all files from the staging area | $ git reset
15| Commit the files | $ git commit -m *some text*
16| Get log for the changes made | $ git log
17|Cloning a remote repository | $ git clone *url*   *where to clone*
18|Viewing information about the remote repository |$ git remote -v 
19|Viewing information about the branhesof remote repository |$ git branch -a 
20| To get the changes made in that code | $ git diff
21| Get the changes in the repo | $ git pull origin master
22| Pushing the code to the repository | $ git push origin master
22|Get branch from local repo| $ git branch 
23| Create a branch | $ git branch *branch name*
24| Change the working branch | $ git checkout *branch name*
25| push the branch to remote repo | $ git push -u origin *branch name*

