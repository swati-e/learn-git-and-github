```markdown
# How to Use Git and GitHub

## Introduction
This tutorial covers the basics of Git and GitHub, including common commands and their differences.

## Table of Contents
1. [What is Git and GitHub](#what-is-git-and-github)
2. [Their Differences](#their-differences)
3. [Installations and GUIs](#installations-and-guis)
4. [Setup](#setup)
5. [Setup and Init](#setup-and-init)
6. [Stage and Snapshot](#stage-and-snapshot)
7. [Branch and Merge](#branch-and-merge)
8. [Inspect and Compare](#inspect-and-compare)
9. [Tracking Path Changes](#tracking-path-changes)
10. [Ignoring Patterns](#ignoring-patterns)
11. [Share and Update](#share-and-update)
12. [Rewrite History](#rewrite-history)
13. [Temporary Commits](#temporary-commits)

## 1. What is Git and GitHub
**Git** is a distributed version control system designed to track changes in source code during software development. It helps developers collaborate, maintain code history, and manage project versions.

**GitHub** is a web-based platform that uses Git for version control. It provides a collaborative environment for developers to share, review, and manage code repositories.

## 2. Their Differences
- **Git** is a version control tool used locally to manage project history.
- **GitHub** is a cloud-based hosting service for Git repositories, enabling collaboration and code sharing.

## 3. Installations and GUIs

### Installing Git
- **Windows**: Download from [git-scm.com](https://git-scm.com/) and follow the installation instructions.
- **Mac**: Use Homebrew:
  ```sh
  brew install git
  ```
- **Linux**: Use your package manager:
  ```sh
  sudo apt-get install git
  ```

### GUIs for Git
- **GitHub Desktop**: User-friendly interface for GitHub.
- **Sourcetree**: A free Git client for Windows and Mac.
- **GitKraken**: Cross-platform Git GUI.

## 4. Setup
Configure your Git environment:
```sh
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

## 5. Setup and Init
Initialize a new Git repository:
```sh
git init
```

## 6. Stage and Snapshot

### Staging
Add changes to the staging area:
```sh
git add <file>
```

### Snapshot
Commit the staged changes:
```sh
git commit -m "Your commit message"
```

## 7. Branch and Merge

### Creating a Branch
Create and switch to a new branch:
```sh
git checkout -b <branch-name>
```

### Merging
Integrate changes from one branch into another:
```sh
git checkout main
git merge <branch-name>
```

## 8. Inspect and Compare

### View Commit History
```sh
git log
```

### Compare Changes
```sh
git diff <commit1> <commit2>
```

## 9. Tracking Path Changes
Rename or move files:
```sh
git mv <old-path> <new-path>
```

## 10. Ignoring Patterns
Use a `.gitignore` file to exclude files:
```plaintext
# Example .gitignore
node_modules/
*.log
*.tmp
```

## 11. Share and Update

### Push Changes
```sh
git push origin main
```

### Pull Updates
```sh
git pull origin main
```

## 12. Rewrite History

### Amend Last Commit
```sh
git commit --amend
```

### Rebase
```sh
git rebase <branch>
```

## 13. Temporary Commits

### Stashing Changes
Save changes temporarily:
```sh
git stash
```

### Apply Stashed Changes
```sh
git stash apply
```

## Conclusion
This tutorial covers the basics of using Git and GitHub. For more advanced topics, refer to the [official Git documentation](https://git-scm.com/doc).
```

Copy and paste this content into your `README.md` file to ensure it displays correctly and looks well-organized on GitHub.
