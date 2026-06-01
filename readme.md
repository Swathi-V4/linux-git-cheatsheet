# Linux and Git Command Cheat Sheet

## 1. pwd

Shows the current directory you are in.
Useful for confirming your current location in the file system.
Example:

```bash
pwd
```

## 2. ls

Lists files and folders in the current directory.
Can be combined with options such as -l and -a.
Example:

```bash
ls
```

## 3. cd

Changes directories.
Useful for navigating between folders in the file system.
Example:

```bash
cd Documents
```

## 4. mkdir

Creates a new folder.
Creates directories for organizing files.
Example:

```bash
mkdir project
```

## 5. touch

Creates a new empty file.
Can create a file if it does not already exist.
Example:

```bash
touch readme.md
```

## 6. cat

Displays the contents of a file.
Often used to quickly view text files in the terminal.
Example:

```bash
cat readme.md
```

## 7. clear

Clears the terminal screen.
Useful for removing clutter from the terminal window.
Example:

```bash
clear
```

## 8. rm

Removes a file.
Useful for deleting files you no longer need.
Example:

```bash
rm oldfile.txt
```

## 9. git init

Creates a new Git repository in the current folder.
Useful for starting version control in a project.
Example:

```bash
git init
```

## 10. git status

Shows the current status of the repository.
Useful for checking modified, staged, and untracked files.
Example:

```bash
git status
```

## 11. git add

Stages files so they can be committed.
Useful for preparing files to be committed.
Example:

```bash
git add readme.md
```

## 12. git commit

Saves a snapshot of staged changes.
Useful for creating a snapshot of your project history.
Example:

```bash
git commit -m "Add command explanation"
```

## 13. git branch

Lists, creates, or manages branches.
Useful for organizing work into separate development branches.
Example:

```bash
git branch command-pwd
```

## 14. git checkout

Switches between branches.
Useful for moving between different versions of your project.
Example:

```bash
git checkout command-pwd
```

## 15. git merge

Combines changes from one branch into another.

Example:

```bash
git merge command-pwd
```

## 16. git remote add origin

Connects a local repository to a GitHub repository.

Example:

```bash
git remote add origin git@github.com:username/linux-git-cheatsheet.git
```

## 17. git push

Uploads local commits to GitHub.

Example:

```bash
git push -u origin main
```
