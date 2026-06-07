# Git Course

A hands-on course designed to teach the fundamentals and practical workflows of Git, the most widely used version control system.

## 📚 Course Objectives

By the end of this course, you will be able to:

* Understand version control concepts
* Initialize and manage Git repositories
* Track and commit changes
* Work with branches and merges
* Resolve merge conflicts
* Collaborate using remote repositories
* Use GitHub (or other Git hosting platforms)
* Apply Git best practices in real-world projects

---

## 🛠 Prerequisites

* Basic command-line knowledge
* A code editor (VS Code recommended)
* Git installed on your machine

Verify installation:

```bash
git --version
```

---

## 📖 Course Outline

### Module 1: Introduction to Version Control

* What is Version Control?
* Why Git?
* Distributed vs Centralized VCS
* Git Architecture

### Module 2: Getting Started with Git

* Installing Git
* Configuring Git

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Module 3: Creating Repositories

* Initialize a repository

```bash
git init
```

* Clone an existing repository

```bash
git clone <repository-url>
```

### Module 4: Tracking Changes

* Check status

```bash
git status
```

* Stage files

```bash
git add .
```

* Commit changes

```bash
git commit -m "Initial commit"
```

### Module 5: Viewing History

```bash
git log
git log --oneline
git diff
```

### Module 6: Branching

Create a branch:

```bash
git branch feature-login
```

Switch branches:

```bash
git switch feature-login
```

Create and switch:

```bash
git switch -c feature-login
```

### Module 7: Merging

Merge a branch:

```bash
git merge feature-login
```

Topics:

* Fast-forward merges
* Three-way merges
* Merge conflicts

### Module 8: Working with Remote Repositories

Add a remote:

```bash
git remote add origin <repository-url>
```

Push changes:

```bash
git push origin main
```

Pull updates:

```bash
git pull origin main
```

Fetch changes:

```bash
git fetch
```

### Module 9: Stashing Work in Progress

Save changes:

```bash
git stash push -m "WIP: login page"
```

List stashes:

```bash
git stash list
```

Apply a specific stash:

```bash
git stash apply stash@{1}
```

Remove a stash:

```bash
git stash drop stash@{1}
```

### Module 10: Undoing Changes

Discard local changes:

```bash
git restore <file>
```

Unstage files:

```bash
git restore --staged <file>
```

Amend commits:

```bash
git commit --amend
```

Revert commits:

```bash
git revert <commit-hash>
```

### Module 11: Advanced Git

* Interactive Rebase
* Cherry-pick
* Tags
* Git Hooks
* Squashing Commits

Examples:

```bash
git rebase -i HEAD~3
git cherry-pick <commit-hash>
git tag v1.0.0
```

---

## 🧪 Practice Exercises

### Exercise 1

1. Create a repository.
2. Add a README file.
3. Commit the changes.

### Exercise 2

1. Create a feature branch.
2. Make changes.
3. Merge the branch into main.

### Exercise 3

1. Create two branches.
2. Modify the same file.
3. Resolve a merge conflict.

### Exercise 4

1. Create multiple stashes.
2. Apply a specific stash.
3. Drop the stash after verification.

---

## 📋 Git Cheat Sheet

```bash
git init
git clone <url>
git status
git add .
git commit -m "message"
git log --oneline
git branch
git switch <branch>
git switch -c <branch>
git merge <branch>
git fetch
git pull
git push
git stash
git stash list
git stash apply stash@{n}
git restore <file>
git revert <commit>
```

---

## ✅ Best Practices

* Commit small, focused changes
* Write meaningful commit messages
* Pull frequently before pushing
* Use feature branches
* Review changes before committing
* Avoid committing secrets or credentials
* Keep your main branch stable

---

## 🎯 Final Project

Create a repository and demonstrate:

* Branch creation
* Multiple commits
* Merge operations
* Remote collaboration
* Stash management
* Conflict resolution

---

## 📚 Additional Resources

* Official Git Documentation: https://git-scm.com/doc
* Pro Git Book: https://git-scm.com/book
* GitHub Documentation: https://docs.github.com

---

Happy coding and version controlling! 🚀
