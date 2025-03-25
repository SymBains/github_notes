# Git and GitHub Notes/Cheatsheet

Git is a distributed version control system (VCS) that helps developers track changes in their code, collaborate with others, and manage different versions of their projects efficiently.

GitHub is a cloud-based hosting service for Git repositories. It allows developers to store, share, and collaborate on projects online.

### How it Works
1. Working Directory → The folder where your project files are.
2. Staging Area → Where you add files before committing.
3. Local Repository → Where commits are stored locally.
4. Remote Repository → A GitHub repository where your commits are pushed for collaboration.

### Basic Workflow
1. Make changes to files.
2. `git add` → Stage the changes.
3. `git commit` → Save a snapshot of your changes.
4. `git push` → Upload your changes to GitHub

## Commands

### Configuration
| Command | Description |
|---------|-------------|
| `git config --global user.name "Your Name"` | Set your Git username |
| `git config --global user.email "you@example.com"` | Set your Git email |
| `git config --list` | View all Git configuration settings |

### Setup and Snapshotting
| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository |
| `git status` | Show the working directory and staging area status |
| `git add <file>` | Stage a specific file |
| `git add .` | Stage all changes |
| `git commit -m "message"` | Commit staged changes with a message |
| `git commit --amend -m "new message"` | Edit the last commit message |
| `git diff` |Shows differences between working directory and last commit|
| `git log` |Displays commit history|

### Branching & Merging
A branch is a separate line of development in your repository. The main branch is the default, but you can create new branches to work on features without affecting the main code.

Merging combines changes from different branches into one branch.

| Command | Description |
|---------|-------------|
| `git branch` | List branches |
| `git branch <branch-name>` | Create a new branch |
| `git checkout <branch-name>` | Switch to a branch |
| `git checkout -b <branch-name>` | Create and switch to a new branch |
| `git merge <branch-name>` | Merge a branch into the current branch |

### Remote Repositories
| Command | Description |
|---------|-------------|
| `git remote add origin <repo-url>` | Add a remote repository |
| `git remote -v` | Show remote repositories |
| `git push origin <branch-name>` | Push a branch to the remote repository |
| `git push -u origin <branch-name>` | Push a branch and set upstream tracking |
| `git pull origin <branch-name>` | Fetch and merge changes from the remote branch |
| `git fetch` | Fetch changes from a remote repository |
| `git clone` | Clone a remote repository locally |

## Notes
- A `.gitignore` file tells Git which files to ignore. This is useful for preventing unnecessary files (logs, compiled binaries, API keys, etc.) from being tracked.
- 


