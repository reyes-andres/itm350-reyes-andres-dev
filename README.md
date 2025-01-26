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

1. Run `npm install`.
2. Run `node server.js`.
3. Visit [http://localhost:8080](http://localhost:8080).

   <img width="1199" alt="image" src="https://github.com/user-attachments/assets/2cf0d1b5-5dde-491c-a158-8425df4576c5">

## Using Docker

Clone the repository and run the following command:

```
docker build -t bulletin-board .
docker run -d -p 8080:8080 bulletin-board
```


## RESTful API (contributed by Jason Lam)

1. **Use Node.js & Express for backend server and router.**
2. **RESTful requests towards the server to simulate CRUD on *events* model, instead of local hardcoded ones.**
3. Translated into Traditional Chinese.

## RESTful API written in Go 

If you would like to use a backend written in Go, [thewhitetulip](http://github.com/thewhitetulip) has written on. See [the source code](https://github.com/thewhitetulip/go-vue-events).
 
