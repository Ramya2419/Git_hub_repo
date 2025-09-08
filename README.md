# Git_hub_repo
Git and Github Information 

Git is a version control system.
To keep track of code<br>
Synchronise code
<br>
It is used for:
Tracking code changes
Tracking who made changes
Coding collaboration

Key Git Concepts
Repository: A folder where Git tracks your project and its history.
Clone: Make a copy of a remote repository on your computer.
Stage: Tell Git which changes you want to save next.
Commit: Save a snapshot of your staged changes.
Branch: Work on different versions or features at the same time.
Merge: Combine changes from different branches.
Pull: Get the latest changes from a remote repository.
Push: Send your changes to a remote repository.



Github<br>
Website that allows developers to store and manage the code using git.

Configuring Git
git config --global user.name "My name"
git config --global user.email "xyz@gmail.com"
git config --list

git config --list will provide credentials, user.name, user.email
Use --global to set the value for every repository on your computer.
Use --local (the default) to set it only for the current repository.

Configuration Levels
There are three levels of configuration:

System (all users): git config --system
Global (current user): git config --global
Local (current repo): git config --local
The order of precedence is:

Local (current repo)
Global (current user)
System (all users)
The reason to use the different levels is that you can set different values for different users or repositories.

Global(remote) - Github
Local - PC, Laptop

Clone & Status
Clone
cloning  a repo on our local machine(copying from github to local machine)
git clone <url>

Status
display the state of the code
git status
(Before changing any contents of repo within vs code)
On branch main
Your branch is up to date with 'origin/main'. nothing to commit, working tree clean

(after changing the content in vs code for the epo folder)
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
