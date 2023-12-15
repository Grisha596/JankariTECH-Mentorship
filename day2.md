# CONFIGURING USER ON LOCAL MACHINE

- `git config --global user.name "user_name"` - set user name

- `git config --global user.email "user_email"` - set user email

- `git config --list` - show changes made so far using git config

# BASIC GIT COMMANDS

- `git init` - initialize a git repository

- `git clone remote_repository_url` - clone a remote repository to local machine
  
- `git add file_name` - add a file to staging area

- `git add .` - add all files to staging area

- `git commit -m "commit message"` - commit changes to local repository

- `git remote add origin remote_repository_url` - Add a remote repository

- `git push -u origin master` - push changes to remote repository

- `git pull origin master` - pull changes from remote repository

- `git status` - check status of git repository

- `git log` - check commit history

- `git branch branch_name` - create a new branch

- `git checkout branch_name` - switch to a branch

- `git checkout -b branch_name` - create a new branch and switch to it

- `git merge branch_name` - merge a branch to master branch

- `git branch -d branch_name` - delete a branch

- `git push --force-with-lease` - ensures you do not overwrite someone elses work by force pushing

- `git remote add upstream <URL>` - add a remote named upstream for the repository at <URL>

# While collaborating

- go to main branch pull the changes of remote and run git rebase
- git fetch origin main then git rebase origin/main

# Steps for creating a PR (Pull Request) 
 
1. git clone <url>
2. cd <directory>
3. git checkout -b <new_branch_name>
4. code .
5. change code as required
6. git add .
7. git commit -m "commit_message"
8. git push -u origin <new_branch_name>
9. click ctrl+link that appears after pushing it
10. add description and make a PR
11. See commit messages

# SSH Key Generation

Step 1: Generate new SSH keys

Copy and paste in command:

$ ssh-keygen -t ed25519 -C "your_email@example.com"

Then press Enter


Step 2: Add a new ssh keys   

$ cat ~/.ssh/id_ed25519.pub

Output:

ssh-ed25519 NAAAC3NzaC1lZDI1NTE5AAAAIF9hTXUaTQppZ2i9CirYIsN4/FAXR6t7EjPRyyNVIdgj nabinalemagara@gmail.com


Step3:

Copy and paste that output like in figure: setting>SSH and GPG keys


Step 4: Click on “Add SSH key”

- [Blog](https://nalem7.blogspot.com/2023/11/github.html)

# Introduction to Java Script

(Scope of variable, Camel case, Hoisting, Closure, Loops, Mutation, Object destructuring)

We can assign different value for same variable name using var but it is not possible in const and let.

Nodejs is installed to run javascript.

In terminal to install Nodejs

- `sudo apt-get install nodejs`
- `node --version`

To run .JS file in VS Code - open terminal and then type node file_name_to_run

[ELOQUENT JAVASCRIPT](https://eloquentjavascript.net/)

# Links

- https://www.youtube.com/watch?v=PkZNo7MFNFg&t=10091s