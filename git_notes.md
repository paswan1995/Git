# Git & Version Control - Interview Notes

## What is Version Control System (VCS)?

A Version Control System is a tool that helps to:

* Store source code
* Track changes over time
* Maintain history
* Enable team collaboration

---

## Types of VCS

### 1. Single System VCS

* Code stored in one system
* No collaboration
* Risk of data loss

### 2. Centralized VCS (Client-Server)

Examples: SVN, ClearCase

* Central server stores code
* Developers connect to server
* Requires internet

### 3. Distributed VCS

Examples: Git, Mercurial

* Each developer has full copy
* Works offline
* No single point of failure

---

## What is Git?

* Distributed Version Control System
* Tracks changes in code
* Supports collaboration
* Widely used in DevOps

---

## Git Architecture

### 1. Working Directory

* Where files are created and modified

### 2. Staging Area

* Temporary area before commit
* Command: git add

### 3. Local Repository

* Stores committed code
* Command: git commit

---

## Git Workflow

Working Directory → Staging Area → Local Repository

Commands:

* git add → move to staging
* git commit → save to repo

---

## Other Areas

### Remote Repository

* Stored on GitHub/GitLab
* Commands: git push, git pull

### Stash

* Temporary save without commit
* Command: git stash

---

## Important Git Commands

git init
git add .
git commit -m "message"
git status
git log
git push
git pull
git clone

---

## Key Interview Points

* Git is distributed
* No single point of failure
* Faster than centralized systems
* Supports branching and merging
* Used in CI/CD pipelines

---

## Real-life Analogy

* Working Directory → Files on desk
* Staging Area → Files in box
* Local Repo → Sealed box stored safely
