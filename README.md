## What is Git

Git is a distributed version control system. Git allow teams to work on project from different locations and track changes in the project files they work on. 

## How to use Git
Here is a Basic guide showing how to get started:

### 1. Install Git
Firt, we need to install Git on your PC. You can download it from: https://git-scm.com/downloads

### 2. Configure Git
After installing the program, configure it with your information: 

`git config --global user.name "Your Name"`

`git config --global user.email "your.email@example.com"`

### 2. Initialize your Repository
Now you can navigate to your project's directory and initialize a Git repository:
You can move to directories by using this command:`cd your-project-directory`. Then you can initialize your repo by typing:
`git init`

## Adding Files
To start adding file to the staging area in Git, you can use the `git add command`

`git add <file-name>` to add specific file

`git add . ` to add all the modified and new files in the dir.

## Pushing changes
To send local commits to our remote repository we use the command `git push`

`git push origin <branch-name>`  Use this command to push to a specific branch on the origin remote.

We need to tell Git which remote branch should be the default target for pushes and pulls, for this, we use this command to link our local to a remote branch: `git push origin --set-upstream <branch-name>`

## Pulling changes
To update our local repository with the latest changes from out remote repository, we can use `git pull`
To pull from a specific branch you can use: `git pull origin <branch-name>`

## Changing the remote origin URL
When changing the URL is needed use the `git remote set-url` command. And for changin the url for the origin remote use the command: `git remote set-url origin <new-url>`

## Stashing Changes
To temporarily save changes that you aren't ready to commit, use `git stash`.

You can also list all the stashes by using this commnad: `git stash list`

## Reverting Changes
If you need to revert a previous commit, you can use the following command: `git revert <commit>`

## Resetting Changes
If you need to undo commits and changes you may use git `reset <commit-hash>` 

## Viewing the commit history
To see the project's commit history you may use `git log`

You may also use the folling display options:

`git log --oneline` to show the commit history in a condensed, one-line format


`git log --graph` to display the commit history as a graph

## Viewing changes / Differences
For viewing changes between commits, branches or the working directory you can use the command `git diff`

## Viewing Details
To show detailed information about Git objects, you can use the command `git show <commit>`
