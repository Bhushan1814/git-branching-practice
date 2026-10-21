## Git Branching Practice

A beginner-friendly hands-on project to understand Git branching, commits, merging, and conflict resolution using Git and GitHub.

## 📌 Project Overview

This project demonstrates a basic Git branching workflow using HTML files. It helps beginners understand how to create branches, make changes independently, commit updates, and merge changes into the main branch.

## 🎯 Objectives

• Understand Git and GitHub fundamentals.
• Practice creating and switching branches.
• Learn how to commit and track changes.
• Merge branches into the main branch.
• Understand merge conflicts and how to resolve them.
• Maintain project files using GitHub.

## 🛠️ Technologies Used

• **Git** – Version control system
• **GitHub** – Repository hosting and collaboration
• **HTML5** – Basic web page development
• **Git Bash / Terminal** – Git command execution

## 📂 Project Structure

```text
git-branching-practice/
├── README.md
├── index.html
├── about.html
└── git-branch-workflow.jfif
```

## ⚙️ Git Commands Practiced

# 1. Clone the Repository

```bash
git clone <repository-url>
cd git-branching-practice
```

# 2. Check the Current Status

```bash
git status
```

# 3. Create and Switch to a Branch

```bash
git branch feature-about
git switch feature-about
```

Alternatively:

```bash
git switch -c feature-about
```

# 4. Add and Commit Changes

```bash
git add .
git commit -m "Add about page"
```

# 5. Push the Branch to GitHub

```bash
git push -u origin feature-about
```

# 6. Merge a Branch

```bash
git switch main
git pull origin main
git merge feature-about
git push origin main
```

# 7. View Branches and Commit History

```bash
git branch
git branch -a
git log --oneline
```

## 🔄 Git Workflow

1. Create a feature branch.
2. Make changes to the HTML files.
3. Stage and commit the changes.
4. Push the feature branch to GitHub.
5. Merge the changes into the main branch.
6. Verify the updated files and commit history.

## 📚 Key Learnings

* Branch-based development workflow.
* Version control using Git.
* Commit history and change tracking.
* Branch merging and conflict resolution.
* Basic repository management on GitHub.

## 🚀 Future Improvements

* Add more HTML pages.
* Practice resolving real merge conflicts.
* Create and merge pull requests.
* Explore GitHub Issues and branch protection rules.

## 👨‍💻 Author

**Bhushan Jagtap**

GitHub: [@Bhushan1814](https://github.com/Bhushan1814)

---

⭐ If you find this project useful, feel free to explore the repository and practice the Git commands.
