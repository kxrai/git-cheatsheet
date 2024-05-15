# Git Cheatsheet

A comprehensive Git cheatsheet providing essential commands and usage examples for beginners and experienced developers alike.

## Table of Contents
1. [Git Basics](#git-basics)
2. [Branching](#branching)
3. [Merging](#merging)
4. [Stashing](#stashing)
5. [Remote Repositories](#remote-repositories)
6. [Undoing Changes](#undoing-changes)
7. [Miscellaneous Commands](#miscellaneous-commands)

---

## Git Basics

### Configure Git
```sh
# Set your name and email
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# Verify configuration
git config --list
```

### Initialize a Repository
```sh
# Create a new Git repository
git init
```

### Clone a Repository
```sh
# Clone an existing repository
git clone <repository-url>
```

### Status
```sh
# Check the status of your repository
git status
```

### Add Files
```sh
# Add a single file to staging
git add <file-name>

# Add all files to staging
git add .
```

### Commit Changes
```sh
# Commit staged changes with a message
git commit -m "Your commit message"
```

### Viewing Commit History
```sh
# View commit history
git log
```

## Branching

### Create a New Branch
```sh
# Create a new branch
git branch <branch-name>
```

### Switch to a Branch
```sh
# Switch to the specified branch
git checkout <branch-name>
```

### Create and Switch to a New Branch
```sh
# Create and switch to a new branch
git checkout -b <branch-name>
```

### List All Branches
```sh
# List all branches
git branch
```

## Merging

### Merge a Branch
```sh
# Merge the specified branch into the current branch
git merge <branch-name>
```

## Stashing

### Stash Changes
```sh
# Stash current changes
git stash
```

### Apply Stashed Changes
```sh
# Apply the most recent stash
git stash apply

# Apply a specific stash
git stash apply stash@{index}
```

### List Stashes
```sh
# List all stashes
git stash list
```

## Remote Repositories

### Add a Remote
```sh
# Add a remote repository
git remote add <remote-name> <remote-url>
```

### View Remotes
```sh
# View all remote repositories
git remote -v
```

### Fetch Changes
```sh
# Fetch changes from the remote repository
git fetch <remote-name>
```

### Pull Changes
```sh
# Pull changes from the remote repository
git pull <remote-name> <branch-name>
```

### Push Changes
```sh
# Push changes to the remote repository
git push <remote-name> <branch-name>
```

## Undoing Changes

### Unstage Changes
```sh
# Unstage a file
git reset <file-name>

# Unstage all changes
git reset
```

### Revert a Commit
```sh
# Revert the specified commit
git revert <commit-hash>
```

### Reset to a Previous Commit
```sh
# Reset to the specified commit (destructive)
git reset --hard <commit-hash>
```

## Miscellaneous Commands

### Show Differences
```sh
# Show changes between commits, commit and working tree, etc.
git diff
```

### Tagging
```sh
# Create a new tag
git tag <tag-name>

# Push tags to remote repository
git push --tags
```

### View Commit Details
```sh
# Show detailed information about a commit
git show <commit-hash>
```

---

Feel free to customize this cheatsheet according to your specific needs. Happy coding!
