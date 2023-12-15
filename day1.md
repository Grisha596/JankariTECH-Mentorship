# File system

A file system defines how files are named, stored, and retrieved from a storage device.


# Basic Linux commands

- `pwd(present working directory)` : It prints the working directory.

- `mkdir directory_name` : Creats a new directory.

- `touch file_name` : Creates a new file.

- `ls` : Lists directory contents of files and directories.

- `ls -a` : Lists all files in current directory including hidden files.

- `rm [OPTION]... FILE...` : Generally used to delete the files created in the directory.

- `-rf` : Used with rm to remove files or directory forcely.

- `rmdir <options> <directory>` : Deletes empty repository.

- `cp [OPTION] Source  Destination` : Copies files or groups of files or directories.

- `mv` : Used for renaming the files in Linux.

- `cd [directory]` : Replace [directory] with the path of the destination directory you want to navigate to.

- `cd ..` : Goes back to previous directory.

- `xdg-open {file | URL}` : Used to open a file or URL in the user’s preferred application.

- `nano file_name` : Same as xdg-open.

- `cat file_name` : Shows content of a file.

- `cat file1 file2` : Displays contents of multiple files.

- `sudo apt.get update` : Retrieve the information and packages from the authenticated sources for installation, upgrade, and removal of packages along with their dependencies.

- `sudo apt upgrade` : Used when we want to download package information from all configured sources.

- `chmod [options] [mode] [File_name]` : Used to change the access mode of a file/file permission. 

Two modes: Symbolic and Octal mode. 

1. Symbolic mode 

- The following operators can be used with the symbolic mode:<br>
 `+` : Add permissions<br>
 `-` : Remove permissions<br>
 `=` : Set the permissions to the specified values

- The following letters that can be used in symbolic mode:<br>
 `r` : Read permission<br>
 `w` : Write permission<br>
 `x` : Execute permission 

- The following Reference that are used:<br>
 `u` : Owner/User<br>
 `g` : Group<br>
 `o` : Others<br>
 `a` : All (owner,groups,others)

 - chmod role=permission file_name
 - _rw_rwx__x

2. Octal mode

- In this method we specify permission using three-digit number. Where..

- First digit specify the permission for Owner.
- Second digit specify the permission for Group. 
- Third digit specify the permission for Others

NOTE: The digits are calculated by adding the values of the individual permissions.

| Value | Permission        |
|-------|-------------------|
| 4     | Read Permission   |
| 2     | Write Permission  |
| 1     | Execute Permission|

- `ls -l` :  Viewing the current permissions of a file or directory.

- `sudo passwd [username]` : Used to change the user account passwords. 
 
- `chown` : Used to change the file Owner or group.<br>
`chown [OPTION]… [OWNER][:GROUP] FILE…`<br>
`chown [OPTION]… –reference=RFILE FILE…`

- `chown owner_name file_name` : To change the Owner of the file.

- `chown :group1 file1.txt` : To change the group of the file.

- `chown master:group1 file1.txt` : To change both owner and group of the file.

# Installing VS Code

Visual Studio Code is a free, lightweight and extensible code editor for building web, desktop and mobile applications.

# Introduction to Git and Github

Git is a version control system that lets you manage and keep track of your source code history.<br>
GitHub is a cloud-based hosting service that lets you manage Git repositories. It is where people can share and collaborate on the files they have created.

# Links

- https://opensource.com/life/16/10/introduction-linux-filesystems
- https://www.geeksforgeeks.org/basic-linux-commands/
- https://help.ubuntu.com/community/LinuxFilesystemTreeOverview
- https://cloud.owncloud.com/s/YiMTOkYEZZv0JBc
- https://nalem7.blogspot.com/2023/11/github.html
- https://phoenixnap.com/kb/install-vscode-ubuntu