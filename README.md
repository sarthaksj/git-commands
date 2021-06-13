# git-commands
A Plenty Of Useful Git Commands Which Are Needed In Day to Day Development Activities.

# Configuration Commands
##### These commands sets the author name and email address respectively to be used with your commits.
1. git config –global user.name **"[name]"**
1. git config –global user.email **"[email_address]"**
  
###### *note- Run the above commands in git bash

# Basic Commands
##### These are some starter commands to get familiar with the git ecosystem

1. To start a new repository - **git init**
1. To connect your local repository to the remote repository - **git remote add origin <repository_link>**
1. To clone the repository - **git clone <repository_url>**
1. To stage the content for the next commit - **git add .**
   1. To add only one file to the staging area - **git add [file_name]**
3. To displays the state of the working directory and the staging area - **git status**
4. To save your changes inside the local repository - **git commit -m "<commit_message>"**
5. To **push** your changes from your local repository to remote repository - **git push**
6. To **pull** your changes from your remote repository to local repository - **git pull**


# Commands For Branches
##### These are some commands to deal with branches inside your repository

1. To check all the remote and local branches - **git branch -a**
1. To check only remote branches present on github - **git branch -r** 
1. To create a branch in your local repository and also want to switch to it - **git checkout -b <branch_name>**
1. To switch from one branch to another - **git checkout <branch_name>**
1. To merge the specified branch’s history into the current branch - **git merge <branch_name>**
1. **Push** the locally created branch to github - **git push -u origin <branch_name>**
1. **Pull** a branch from remote repository which you dont have in your local repository - 
   1. **git fetch**
   1. **git checkout <branch_name> (the branch you got in fetch command)**
1. Delete a local branch - **git branch -d <branch_name>**
1. Delete a branch present in the remote repository - **git push origin :<branch_name>**
