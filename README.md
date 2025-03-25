# Git coomands
Git is an open source distributed version control styles
# The stages of git
!{}(https://miro.medium.com/v2/resize:fit:500/1*9hNsHV22lsi03i9Ah92KmQ.png)
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

## checking a status of files
to check a status of our file, you use the command which is 'git status', this will show you if ur file are untracked, staged and ready for committing
```sh
git status
```  