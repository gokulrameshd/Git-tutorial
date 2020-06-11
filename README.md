# Git-tutorial
Git training



## Notes:
1. Distributed version control.
2. We can have both local and remote repository.
3. When ls -la is given in the terminal it gives the file and also **.git**.
This **.git** is repository which tracks all our changes.
4. Initiallizing the directory will make the git to track the changes.
5. To avoid certain files from adding to the repository , use **.gitignore** . This will create an ignore file , a text file which contains the extensions of the files which we want to ignore while committing
6. There are three stage
  * working directory
  * stagging Area
  * .git directory(repository)

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
15| Commit the files | $ git commit -m "some text"
16| Get log for the changes made | $ git log
17|Cloning a remote repository | $ git clone 'url'   'where to clone'
18|Viewing information about the remote repository |$ git remote -v 
19|Viewing information about the branhesof remote repository |$ git branch -a 
20| To get the changes made in that code | $ git diff
21| Get the changes in the repo | $ git pull origin master
22| Pushing the code to the repository | $ git push origin master
