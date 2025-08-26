# 📘 Git & GitHub Learning Journey

## 🌟 Overview
This repository documents my **hands-on learning of Git & GitHub** from **Sir Zaryab's class** and my **DevOps course**. 
It covers **core version control concepts**, real-world Git workflows, and advanced features like **tags, rollback, semantic versioning, and GitHub Copilot**.

---

## 📂 Topics Covered

### 1️⃣ Introduction to Git & Version Control
- What is **Version Control System (VCS)** and why it matters.
- Centralized vs Distributed VCS.
- Git as a **distributed VCS** developed by Linus Torvalds.
- Installing Git & verifying with:
  ```bash
  git --version
  ```
---
## 2️⃣ Repository Basics

### 🔹 Creating Local Repositories:
```bash
git init
```
### 🔹 Adding files & staging:
```bash
git add .
git commit -m "First commit"
```
### 🔹 Configuring Git user info:
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
---
## 3️⃣ Remote Repositories (GitHub)


### 🔹 Creating a GitHub repo & linking:
```bash
git remote add origin <repo-url>
git branch -M main
git push -u origin main
```
### 🔹 Pulling changes:
```bash
git pull origin main
```
---
## 4️⃣ Branching & Merging

### 🔹 Creating branches for new feature:
```bash
git branch feature-1
git checkout feature-1
```
### 🔹 Merging changes back:
```bash
git checkout main
git merge feature-1
```

### 🔹 Resolving conflicts & using .gitignore.

---

## 5️⃣ Tags & Semantic Versioning

### 🔹 Creating lightweight & annotated tags:
```bash
git tag v1.0.0
git tag -a v1.0.0 -m "Release version 1.0.0"
```
### 🔹 Pushing tags:
```bash
git push origin v1.0.0
```

### 🔹 Following Semantic Versioning (MAJOR.MINOR.PATCH).

---
## 6️⃣ Rollback & Recovery

### 🔹 Viewing commit history:
```bash
git log --oneline
```
### 🔹 Reverting commits:
```bash
git revert <commit-id>
```

### 🔹 Resetting to previous states:
```bash
git reset --hard <commit-id>
```

---
## 7️⃣ SSH Authentication

### 🔹 Generating SSH key:
```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```
### 🔹 Adding SSH key to GitHub.


### 🔹 Using SSH-based remote URLs
```bash
git remote set-url origin git@github.com:user/repo.git
```
---

## 8️⃣ GitHub Copilot

- Setting up **GitHub Copilot**.
- Using AI assistance to:
    - Suggest code snippets.
    - Autocomplete boilerplate.
    - Speed up development.

---

## 🧑‍💻 Skills Demonstrated

- **Version Control** with Git.
- **Collaboration** with GitHub (push, pull, merge).
- **Branching strategies** for features & sprints.
- **Release management** using tags & semantic versioning.
- **Rollback & recovery** for safe code changes.
- **Secure authentication** via SSH keys.
- **AI-powered coding assistance** with GitHub Copilot.

---

## 🚀 How to Use

Clone this repo:

```bash
git clone https://github.com/<your-username>/git-learning.git
cd git-learning
```



---

## 🏆 Final Takeaway

Git is not just a version control tool — it’s the **foundation of modern DevOps and collaboration**.  
This repo showcases my journey of learning **Git & GitHub**, covering everything from **basic commits to advanced features** like **semantic versioning & Copilot**.
































