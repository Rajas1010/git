# Git Commands Reference

This project provides a reference for essential Git commands that can help you manage your Git repositories effectively. The commands are organized for easy reference, making it a handy guide for both beginners and experienced Git users.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Git Basics](#git-basics)
3. [Working with Branches](#working-with-branches)
4. [Stashing Changes](#stashing-changes)
5. [Advanced Commands](#advanced-commands)
6. [Remote Repository Interaction](#remote-repository-interaction)
7. [Code Samples](#code-samples)

## Getting Started

To get started with Git, make sure you have Git installed on your system. You can download it from [here](https://git-scm.com/downloads) if it's not already installed.

## Git Basics

- **git init:** Initialize a directory as a Git repository.
- **git clone \<repository-url>:** Clone a remote repository to your local machine.
- **git add .:** Stage all changes in your working directory for the next commit.
- **git commit -m "Message":** Create a new commit with a descriptive message.
- **git status:** View the status of your working directory and staged changes.
- **git log:** Display the commit history of the repository.
- **git diff:** Show the differences between the working directory and the last commit.

## Working with Branches

- **git branch:** List all branches in the repository.
- **git branch \<branch-name>:** Create a new branch.
- **git checkout \<branch-name>:** Switch to a different branch.
- **git merge \<branch-name>:** Merge changes from one branch into the current branch.
- **git branch -d \<branch-name>:** Delete a branch (if merged).
- **git branch -D \<branch-name>:** Forcefully delete a branch (regardless of merge status).
- **git checkout -b \<branch-name>:** Create and switch to a new branch.

## Stashing Changes

- **git stash:** Temporarily save changes in a stash.
- **git stash list:** List all stashes created in the repository.
- **git stash show:** Show the changes stored in the most recent stash.
- **git stash apply:** Apply changes from the most recent stash.
- **git stash pop \<stash-index>:** Apply and remove a specific stash.
- **git stash drop \<stash-index>:** Remove a specific stash.
- **git stash clear:** Remove all stashes.

## Advanced Commands

- **git cherry-pick \<commit>:** Apply a specific commit to the current branch.
- **git revert \<commit>:** Create a new commit that undoes the changes introduced by the specified commit.
- **git reset \<commit>:** Unstage changes but keep them in the working directory.
- **git reflog:** View a log of all Git commands executed.

## Remote Repository Interaction

- **git remote add \<remote-name> \<repository-url>:** Associate a remote repository URL with a name.
- **git remote -v:** List remote repositories linked to the current repository.
- **git pull \<remote-name> \<branch-name>:** Fetch and merge changes from a remote branch.
- **git push \<remote-name> \<branch-name>:** Push committed changes to a remote branch.
- **git fetch \<remote-name>:** Fetch changes from a remote repository.

## Code Samples

Explore code samples in different languages:

- **Python:** Click the "Download Python File" button to download a Python code sample (`hello.py`).
- **Java:** Click the "Download Java File" button to obtain a Java code sample (`HelloWorld.java`).
- **HTML:** Click the "Download HTML File" button to download an HTML code sample (`index.html`).

This README serves as a quick reference for common Git commands. Use it as a handy guide to navigate your Git workflows efficiently.

---
