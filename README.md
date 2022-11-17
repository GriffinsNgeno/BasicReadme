# Simple CLI Commands

Below is a list of CLI commands that we'll occasionally use.

## Working with files and folders

```bash

# Creating a folder
mkdir <folder name>

# Creating a file
touch <file-name>

# Navigating through a folders
cd <folder-name>

# Going one step behind a folder
cd ..

# Navigating back to the root folder
cd ~

# Removing files and folders tht have no permission
rm <folder/fole-name>

# Removing files and folders that have permission
rm -rf <folder-name>

# Opening a folder in vs code
code <folder/file-name/current dir>

# List all files within the folder(unhidden)
ls

# List out all folders (with hidden)
ls -a
```
## Basic git commands

```bash
#  Create an empty repository
git init

# Show working tree status
git status

# add file contents to the index
git add .

# Record changes to the repository
git commit -m "Write Message"

# Update remote refs along with associated objects
git push

# Clone a repository
git clone

# List,create or delete branches
git branch

# Removing files from a working tree
git rm

# Restoring working tree files
git restore

# Move or name a file, a directory
git mv

# Create, list, delete or verify a tag object
git tag

# To retrieve changes
git stash

# Undo Merge
git checkout branch-name
git log --oneline
git revert -m commit-id

# Rename a branch normally and remote
git checkout old-branch
git branch -m new name
git push origin :old-name new name

# Move existing,uncommited work to a new branch
git switch -c <new-branch> 
```
