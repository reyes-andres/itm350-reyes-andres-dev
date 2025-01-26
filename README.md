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
Now you can vavigate to your project's directory and initialize a Git repository:
You can move to directories by using this command:`cd your-project-directory`. Then you can initialize your repo by typing:
`git init`


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
 
