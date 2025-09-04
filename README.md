# Git and GitHub Tutorial

This repository (A02) contains a step-by-step tutorial on how to use **Git** and **GitHub**. The tutorial is designed for beginners and explains the process of version control using **Git**, collaborating via **GitHub**, and integrating with an IDE like WebStorm.

## Tutorial: How to Use Git and GitHub

Follow these steps to get started with **Git** and **GitHub**. We'll use WebStorm for examples.

### Step 1: Install Git
1. Download **Git** from https://git-scm.com/downloads.
2. Install and configure with `git config --global user.name "Your Name"`.

### Step 2: Create a GitHub Repository
1. Log in to GitHub at https://github.com.
2. Create a new repository named A02.

### Step 3: Clone the Repository
Use `git clone https://github.com/yourUCID/A02.git` or WebStorm's VCS menu to clone the remote repository.

### Step 4: Make Changes and Commit
1. Edit files.
2. Stage with `git add .`.
3. **Commit** with `git commit -m "Message"`.

### Step 5: Push Changes
Use `git push origin main` to upload to the remote.

### Step 6: Work with Branches
Create a **branch** with `git checkout -b new-branch`, make changes, then **merge** back with `git **merge** new-branch`.

### Step 7: Pull Updates
Use `git **pull**` to **fetch** and **merge** from the **remote**. Resolve any **merge conflict** manually.

Always use clear **commit** messages like:
- Task: Create Repository
- Feature: added workflow for using github
- Fix: changed readme.md for definition of terms

## Part 1: Directions on Using WebStorm

1. Download WebStorm from https://www.jetbrains.com/webstorm/download/.
2. Install and launch.
3. Configure **Git** in Settings > Version Control > Git.
4. Clone a repo via VCS > Get from Version Control.
5. Commit via VCS > Commit.
6. Push/Pull via VCS > Git > Push/Pull.

## Part 2: Glossary

- **Branch**: A parallel version of the repository for isolated development.
- **Clone**: Copying a repository from remote to local.
- **Commit**: Saving a snapshot of changes with a message.
- **Fetch**: Downloading updates from remote without merging.
- **GIT**: Distributed version control system for tracking code changes.
- **Github**: Web platform for hosting Git repositories.
- **Merge**: Combining changes from one branch into another.
- **Merge Conflict**: When changes in branches conflict and need manual resolution.
- **Push**: Uploading local commits to the remote repository.
- **Pull**: Fetching and merging remote changes into local.
- **Remote**: The repository hosted on a server like GitHub.
- **Repository**: A project folder with files and version history.

## References
1. Git Documentation - https://git-scm.com/docs
2. GitHub Quickstart - https://docs.github.com/en/get-started/quickstart
3. WebStorm Git Integration - https://www.jetbrains.com/help/webstorm/using-git-integration.html
