# Git Assignment

## Overview

This assignment was completed to practise the core Git workflow used in software development and DevOps.

The assignment covered creating a local Git repository, tracking changes, staging files, creating commits, working with branches, managing changes, and pushing a repository to GitHub.

## Objectives

* Understand the basic Git workflow
* Create and manage a Git repository
* Track and stage changes
* Create meaningful commits
* Inspect changes and commit history
* Work with branches
* Understand merging and conflicts
* Use Git stash and rebase
* Undo and recover changes
* Push work to GitHub
* Use `.gitignore`
* Build a practical Git command reference

## Git Workflow

The basic workflow practised throughout the assignment was:

```text
Working Directory
       ↓
   git add
       ↓
Staging Area
       ↓
  git commit
       ↓
Local Repository
       ↓
   git push
       ↓
     GitHub
```

## Topics Covered

### 1. Repository & Core Workflow

Commands practised:

```bash
git init
git status
git add <file>
git add .
git restore --staged <file>
git commit -m "message"
git push
```

Learned how Git tracks files and how changes move from the working directory into the staging area and eventually into the repository.

### 2. Inspecting Changes

```bash
git diff
git diff --staged
git log
git show
```

These commands were used to inspect changes before committing and review previous commits.

### 3. File Operations

Practised tracking new files, modified files and deleted files with Git.

### 4. Branching

Branches allow changes to be developed separately from the main branch.

```bash
git branch
git switch <branch>
git switch -c <branch>
```

### 5. Merging & Conflicts

Practised combining work from different branches and understanding what happens when Git cannot automatically merge changes.

### 6. Stash

```bash
git stash
git stash pop
```

Used to temporarily save uncommitted changes when switching between tasks.

### 7. Rebase

```bash
git rebase <branch>
```

Learned how rebase can replay commits onto another branch and create a cleaner project history.

### 8. Undo & Recovery

Practised different ways of undoing changes while understanding the difference between working-directory changes, staged changes and committed changes.

### 9. GitHub

The local repository was connected to GitHub and changes were pushed to the remote repository.

```bash
git remote -v
git push -u origin main
```

### 10. `.gitignore`

Used `.gitignore` to prevent files and directories that should not be tracked from being added to the repository.

## Key Concepts Learned

### Working Directory

The files currently being edited on the local machine.

### Staging Area

A preparation area where changes are selected before creating a commit.

### Commit

A saved snapshot of the staged changes in the Git repository.

### Branch

An independent line of development.

### Remote Repository

A repository hosted somewhere outside the local machine, such as GitHub.

### HEAD

A reference that points to the commit currently checked out.

## Useful Git Command Reference

| Command                       | Purpose                               |
| ----------------------------- | ------------------------------------- |
| `git status`                  | Check the current repository state    |
| `git add <file>`              | Stage a file                          |
| `git add .`                   | Stage all changes                     |
| `git restore --staged <file>` | Unstage a file                        |
| `git commit -m "message"`     | Create a commit                       |
| `git log`                     | View commit history                   |
| `git diff`                    | View unstaged changes                 |
| `git diff --staged`           | View staged changes                   |
| `git show`                    | Inspect a commit                      |
| `git branch`                  | List branches                         |
| `git switch <branch>`         | Switch branches                       |
| `git switch -c <branch>`      | Create and switch to a branch         |
| `git merge <branch>`          | Merge a branch                        |
| `git stash`                   | Temporarily store changes             |
| `git stash pop`               | Restore stashed changes               |
| `git rebase <branch>`         | Reapply commits onto another branch   |
| `git remote -v`               | View remote repositories              |
| `git push`                    | Upload commits to a remote            |
| `git pull`                    | Download and integrate remote changes |
| `git clone <url>`             | Copy a remote repository locally      |

## What I Learned

This assignment helped me understand Git as a workflow rather than simply a collection of commands.

The main workflow is:

```text
Edit
 ↓
Check
 ↓
Stage
 ↓
Review
 ↓
Commit
 ↓
Push
```

Understanding the difference between the **working directory**, **staging area**, **local repository**, and **remote repository** was particularly important.

## Assignment Completion

The repository was created locally, changes were tracked and committed, and the work was pushed to GitHub.

The practical work from this assignment is supported by the repository history and the command reference above.
