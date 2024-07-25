# BASIC COMMANDS

| Command                                | Description                                         |
| -------------------------------------- | --------------------------------------------------- |
| `export HOME="/mnt/d/spiced-bootcamp"` | Change home directory (for the session)             |
| `ls`                                   | List directory contents                             |
| `cd /`                                 | Change to root directory                            |
| `cd ~`                                 | Change to home directory                            |
| `cd ..`                                | Change to parent directory                          |
| `cd -`                                 | Change to previous directory                        |
| `mkdir <directory>`                    | Create a directory                                  |
| `rm <file>`                            | Remove a file                                       |
| `rmdir <directory>`                    | Remove an empty directory                           |
| `rm -rf <directory>`                   | Remove an not empty directory                       |
| `cat <filename>`                       | View file contents                                  |
| `mv <oldName> <newName>`               | Rename or move a file                               |
| `cp <folder/example.txt> <folder>`     | Copy a file                                         |
| `mv <example.txt> <folder>`            | Move a file to another directory                    |
| `pwd`                                  | Print working directory                             |
| `touch <filename.txt>`                 | Create a new empty file                             |
| `man <command>`                        | Display command manual (e.g., man ls, man cd, etc.) |

# GIT COMANDS

## REPOSITORIES

| Command                            | Description                                          |
| ---------------------------------- | ---------------------------------------------------- |
| `git init`                         | Initialize a local repository                        |
| `git remote -v`                    | Check repository connection                          |
| `git remote add origin <ssh link>` | Connect local repository to remote                   |
| `git remote remove origin`         | Remove repository connection                         |
| `git clone <repository URL>`       | Clone a repository                                   |
| `git pull origin main`             | Update local repository to the latest version (pull) |
| `git status`                       | View repository status                               |
| `git add .`                        | Stage changes                                        |
| `git commit -m "comment"`          | Commit changes                                       |
| `git push origin main`             | Push changes to remote repository                    |

## BRANCHES

| Command                       | Description                          |
| ----------------------------- | ------------------------------------ |
| `git switch -c <branch_name>` | Create a new branch and switch to it |
| `git switch <branch_name>`    | Switch branches                      |
| `git branch`                  | View existing branches               |
| `git log --oneline`           | View commits and branches            |
| `git branch -d <branch_name>` | Delete a branch                      |
| `git branch -D <branch_name>` | Force delete a branch                |
