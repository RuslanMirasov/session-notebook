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
| `cat <filename>`                       | View file contents                                  |
| `mv <oldName> <newName>`               | Rename or move a file                               |
| `cp <folder/example.txt> <folder>`     | Copy a file                                         |
| `mv <example.txt> <folder>`            | Move a file to another directory                    |
| `pwd`                                  | Print working directory                             |
| `touch <filename.txt>`                 | Create a new empty file                             |
| `man <command>`                        | Display command manual (e.g., man ls, man cd, etc.) |

# GIT COMANDS

## REPOSITORIES

| Command                                      | Description                                          |
| -------------------------------------------- | ---------------------------------------------------- |
| `git init`                                   | Initialize a local repository                        |
| `git remote -v`                              | Check repository connection                          |
| `git remote add origin <ssh link>`           | Connect local repository to remote                   |
| `git remote remove origin`                   | Remove repository connection                         |
| `git clone <repository URL>`                 | Clone a repository                                   |
| `git pull`                                   | Update local repository to the latest version (pull) |
| `git status`                                 | View repository status                               |
| `git add <file.txt> <file.txt> \n git add .` | Stage changes                                        |
| `git commit -m "comment"`                    | Commit changes                                       |
| `git push origin main`                       | Push changes to remote repository                    |

## BRANCHES

| Command                                       | Description                                                                    |
| --------------------------------------------- | ------------------------------------------------------------------------------ |
| `git switch -c <branch_name>`                 | Create a new branch and switch to it                                           |
| `git switch <branch_name>`                    | Switch branches                                                                |
| `git branch`                                  | View existing branches                                                         |
| `git add . \n git commit -m "Commit message"` | Stage changes and commit                                                       |
| `git checkout -b <branch_name>`               | Create a new branch                                                            |
| `git checkout <branch_name>`                  | Switch between branches                                                        |
| `git branch -d <branch_name>`                 | Delete a branch                                                                |
| `git branch -D <branch_name>`                 | Force delete a branch                                                          |
| `git merge <branch_name>`                     | Merge a branch into the current one                                            |
| `git log`                                     | View commit history                                                            |
| `git checkout -- <file_name>`                 | Discard changes in a file (before staging)                                     |
| `git reset <file_name>`                       | Unstage a file (but keep it in the working directory)                          |
| `git checkout <commit_hash>`                  | Switch to a specific commit                                                    |
| `git diff`                                    | View differences between commits or between working directory and staging area |
