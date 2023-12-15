# Codespace

A codespace is a development environment that's hosted in the cloud.

- Steps 

1. Open the repository for which you want codespace.
2. Click on the button beside of m to open codespace.
3. Proceed according to your requirement. 

# Introduction to QA

- Quality Assurance is a way of preventing mistakes and defects in manufactured products and avoiding problems when delivering products or services to customers; which ISO 9000 defines as "part of quality management focused on providing confidence that quality requirements will be fulfilled".<br>
- [QA](https://drive.google.com/file/d/1fw2vm2WH9IU23pGYMRAJ3epDeOGMIBnJ/view?usp=sharing)

# TDD (TEST DRIVEN DEVELOPMENT) abd BDD (BEHAVIOR DRIVEN DEVELOPMENT)

- [Blog Post by cucumber.io on TDD vs BDD](https://cucumber.io/blog/bdd/bdd-vs-tdd/)

# Git Commands

- `git rebase [-i | --interactive] [ options ] [--exec cmd] [--onto newbase | --keep-base] [upstream [branch]]` - Git rebase can integrate the changes from one branch to another by overcoming the problems that we might have faced while using the git merge command. 

- `git bisect <subcommand> <options>` - This command uses a binary search algorithm to find which commit in your project’s history introduced a bug.

- [Github](https://github.com/amrita-shrestha/LearnGitHub/tree/pptwithnotetolearn)

# Open Source Project

- Open source projects are software that anyone can use, modify, and share freely. Some of the most popular open source projects are Android, Firefox, TensorFlow, and Visual Studio Code.

# Filebrowser

- Filebrowser provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It is an open source project available on github.
- [Filebrowser](https://github.com/filebrowser/filebrowser)


# NVM (Node Version Manager)

- It allows you to install multiple node.js versions, view all versions available for installation and all installed versions on your system1.
- NVM is an open source version manager for Node.js.

# Homebrew

- Homebrew is a free and open-source software package management system that simplifies software installation on macOS and Linux.


# Installing go and making version by gobrew

- [Installation](https://github.com/kevincobain2000/gobrew)

1. git clone link_to_file_browser
2. fit remote -v
3. git frontend
4. npm install
5. npm run build
6. go mod download
 and follow the steps


sudo nano ~/.zshrc<br>
sudo xdg-open ~/.zshrc<br>
sudo source ~/.zshrc<br>

eco "$PATH"

export GO111MODULE=on

export NVM_DIR="$HOME/.nvm"<br>
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm<br>
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This load>

export PATH="$HOME/.gobrew/current/bin:$HOME/.gobrew/bin:$PATH"<br>
export GOROOT="$HOME/.gobrew/current/go"<br>
alias composer="php /usr/local/bin/composer.phar"<br>
export PATH="$HOME/.gobrew/current/bin:$HOME/.gobrew/bin:$PATH"<br>
export GOROOT="$HOME/.gobrew/current/go"