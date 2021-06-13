# git-commands
A Plenty Of Useful Git Commands Which Are Needed In Day to Day Development Activities.

# Basic Commands
##### These are some starter commands to get familiar with the git ecosystem

1. To clone the repository - **git clone <repository_url>**
1. To stage the content for the next commit - **git add .**
1. To displays the state of the working directory and the staging area - **git status**
1. To save your changes inside the local repository - **git commit -m <commit_message>**
1. To **push** your changes from your local repository to remote repository - **git push**
1. To **pull** your changes from your remote repository to local repository - **git pull**


# Commands For Branches
##### These are some commands to deal with branches inside your repository

1. To check all the remote and local branches - **git branch -a**
1. To check only remote branches present on github - **git branch -r** 
1. To create a branch in your local repository - **git checkout -b <branch_name>**
1. **Push** the locally created branch to github - **git push -u origin <branch_name>**
1. **Pull** a branch from remote repository which you dont have in your local repository - 
   1. **git fetch**
   1. **git checkout <branchname>(the branch you got in fetch commend)**
1. Delete a local branch - **git branch -d <branch_name>**
1. Delete a branch present in the remote repository - **git push origin :<branch_name>**
