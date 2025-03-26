# Git Commands
Git is an open source distributed version control styles
## Table of Content
- [The Stages of Git](#the-stages-of-git)
- [The Commands](#the-commands)
    - [initializing a Repo](#initializing-a-repo)
    - [Checking the status of our files](#checking-a-status-of-files)

# The Stages of Git
![](https://miro.medium.com/v2/resize:fit:500/1*9hNsHV22lsi03i9Ah92KmQ.png)
- The workspace: this is where unstagged files are located
- The staging Area: this is wherefiles go to after they have been stagged
- The commit/local Rep: this is where the comitted files are saved as a version 
- The Remote Repo: this is where the pushed local reppo are stored remotely

# The Commands
## initializing a Repo
to initialized a repo for an existing project,
- navigate to the working directory of the project you want to initialize and use the command 'git init'
```sh
cd<project-dir>
git init
```
- create a repo on github and use the command 'git clone' to clone the repo locally and begin your project
```sh
git clone<repo-url>
```

## Checking a Status of Files
to check a status of our file, you use the command which is 'git status', this will show you if ur file are untracked, staged and ready for committing
```sh
git status
```  
## Git Add
To add changes in the working directory to the staged files and prepaing them to be committed and this marks them to be icluded in the next commit
```sh
git add
```
## Git Configuration
This process is only done for those who current installed their git app and this command allows you to configure setting for git repositories which includes the user information like 'Name and Email'
```sh
git config --global user.name"your name"
git config --global user.email"your email"
```
## Saving changes in Git
This comes after the you have added changes in the working directory in the staged files into the repository's history, so in other to save the changes in ur git you use "git commit"and with your commit message.
```sh
git commit -m "Your commit message"
```
## Staging All the Flies
This is where you stage all the changes in your files (both new, modified and deleted) in the current directory for the next commit. To do that we use
```sh
git add . 
```
## Displaying Committed hsitory
To display committed history of a git repository that shows the the author, author's email, date and time of the commit and the files you committed nd also the files you modified. To do that we use
```sh
git log
```
## Changing Master to Main
This is only for those who's current branch are like this "(master)" and they want to rename it to (main) branch.to do this we use 
```sh
git branch -M main
```
## How to Fetch and Push your local Repositories
After committing a local repositories the next step is to fetch nd push it to your github account but before that you will have to go to your github account to copy the URLs of ur github account. Then to fetch and push your remote repositories to a local repositories, we use this code
```sh
git remote -v
```
To link your remote repositories to local repositories, we use this code
```sh
git remote add origin "your github URLs"
```
Then to fetch and push your remote repositories to local respositories, we use this code
```sh
git remote -v origin "your github URLs
```
** This line was modified from github**
