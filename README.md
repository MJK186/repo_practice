# repo_practice
to perform all the command of git 

#!/bin/bash

# Initialize a new Git repository
git init

# Check the status of files
git status

# Add files to staging area
git add filename       # Add a single file
git add .              # Add all files

# Commit staged files
git commit -m "Your commit message"

# See commit history
git log

# Branch commands
git branch             # List all branches
git branch new-branch  # Create a new branch
git checkout new-branch # Switch to branch

# Merge a branch into current branch
git merge new-branch

# Connect local repo to remote GitHub repo
git remote add origin https://github.com/username/repo.git

# Push changes to remote
git push -u origin main

# Pull latest changes from remote
git pull origin main

# Clone a repository from GitHub
git clone https://github.com/username/repo.git

# Remove a file from tracking but keep locally
git rm --cached filename

# Undo last commit but keep changes staged
git reset --soft HEAD~1
