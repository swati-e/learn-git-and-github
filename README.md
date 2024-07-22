# learn-git-and-github
How to Use Git and GitHub
Introduction
This tutorial covers the basics of Git and GitHub, their differences, installation, setup, and common commands. Whether you're new to version control or looking to improve your workflow, this guide will help you get started.

Table of Contents
What is Git and GitHub
Their Differences
Installations and GUIs
Setup
Setup and Init
Stage and Snapshot
Branch and Merge
Inspect and Compare
Tracking Path Changes
Ignoring Patterns
Share and Update
Rewrite History
Temporary Commits
1. What is Git and GitHub
Git is a distributed version control system designed to track changes in source code during software development. It helps developers collaborate, maintain code history, and manage project versions.

GitHub is a web-based platform that uses Git for version control. It provides a collaborative environment for developers to share, review, and manage code repositories.

2. Their Differences
Git is a version control tool used locally to manage project history.
GitHub is a cloud-based hosting service for Git repositories, enabling collaboration and code sharing.
3. Installations and GUIs
Installing Git
Windows: Download from git-scm.com and follow the installation instructions.
Mac: Use Homebrew: brew install git
Linux: Use your package manager, e.g., sudo apt-get install git
GUIs for Git
GitHub Desktop: User-friendly interface for GitHub.
Sourcetree: A free Git client for Windows and Mac.
GitKraken: Cross-platform Git GUI.
4. Setup
Configure your Git environment:

sh
Copy code
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
5. Setup and Init
Initialize a new Git repository:

sh
Copy code
git init
This command creates a .git directory in your project, initializing a new repository.

6. Stage and Snapshot
Staging is the process of adding changes to the staging area before committing.

sh
Copy code
git add <file>
Snapshot refers to committing the staged changes to the repository:

sh
Copy code
git commit -m "Your commit message"
7. Branch and Merge
Branches allow you to work on different parts of a project simultaneously.

Create a new branch:

sh
Copy code
git branch <branch-name>
git checkout <branch-name>
Or create and switch to a new branch in one command:

sh
Copy code
git checkout -b <branch-name>
Merging integrates changes from one branch into another:

sh
Copy code
git checkout main
git merge <branch-name>
8. Inspect and Compare
View commit history:

sh
Copy code
git log
Compare changes between commits, branches, or files:

sh
Copy code
git diff <commit1> <commit2>
9. Tracking Path Changes
Renaming or moving files is tracked by Git:

sh
Copy code
git mv <old-path> <new-path>
10. Ignoring Patterns
Use a .gitignore file to exclude files from being tracked:

sh
Copy code
# Example .gitignore
node_modules/
*.log
*.tmp
11. Share and Update
Push changes to a remote repository:

sh
Copy code
git push origin main
Pull updates from a remote repository:

sh
Copy code
git pull origin main
12. Rewrite History
Amend the last commit:

sh
Copy code
git commit --amend
Rebase to replay commits on top of another base tip:

sh
Copy code
git rebase <branch>
13. Temporary Commits
Stashing allows you to save changes temporarily:

sh
Copy code
git stash
Reapply stashed changes:

sh
Copy code
git stash apply
Conclusion
This tutorial covers the basics of using Git and GitHub. For more advanced topics, refer to the official Git documentation.
