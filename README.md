# Git Intro Project

A hands-on introduction to Git — version control basics for beginners.

## About

This repository is used to practice fundamental Git concepts, including:

- Initializing a repository
- Staging and committing changes
- Creating and switching branches
- Merging branches and resolving conflicts
- Collaborating with remote repositories (push / pull)

## Files

| File | Description |
|------|-------------|
| `greeting.txt` | A simple greeting message added from a feature branch |
| `message.txt` | A text file used to demonstrate merge conflicts |
| `improvement.txt` | A file showcasing incremental improvements |

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/) installed on your machine

### Clone the repository

```bash
git clone https://github.com/Mataius-web/git-intro.git
cd git-intro
```

### Common Git commands practiced here

```bash
# Check the status of your working directory
git status

# Stage changes
git add <file>

# Commit staged changes
git commit -m "Your commit message"

# Create and switch to a new branch
git checkout -b my-branch

# Merge a branch into the current branch
git merge my-branch

# Push changes to the remote repository
git push origin my-branch
```

## License

This project is open source and available for learning purposes.
