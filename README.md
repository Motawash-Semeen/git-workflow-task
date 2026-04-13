# Git Workflow Task

## Commands Used

### Repository Setup
- git init
- git branch -M main
- git checkout -b develop

### Branching
- git checkout -b feature/payment
- git checkout -b feature/profile
- git checkout -b bugfix/login-error

### Merge Strategy
- git merge feature/payment

### Rebase Strategy
- git rebase develop

### Commit Management
- git rebase -i HEAD~5

---

## Explanation

### Merge vs Rebase

**Merge:**
- Combines branches
- Keeps history
- Creates merge commit

**Rebase:**
- Rewrites history
- Cleaner linear history
- No extra merge commit

---

### Squash & Reword

**Squash:**
- Combines multiple commits into one

**Reword:**
- Changes commit message

---

## Screenshots

## 📸 Branch List
![Branch Screenshot](screenshots/branches_image.png)

## 📸 Commit History
![Commit History](screenshots/git_commit_image.png)

## 🔀 Pull Request
![PR Screenshot](screenshots/pr_image01.png)

![PR Screenshot](screenshots/pr_image02.png)

![PR Screenshot](screenshots/pr_image03.png)
