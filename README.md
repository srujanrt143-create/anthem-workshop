# 🇮🇳 National Anthem — Git & GitHub Workshop

<p align="center">
  <strong>Hands-On Version Control and Collaborative Development</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Git-Version%20Control-orange?logo=git" />
  <img src="https://img.shields.io/badge/GitHub-Repository-black?logo=github" />
  <img src="https://img.shields.io/badge/Python-3.14-blue?logo=python" />
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-lightgrey?logo=flask" />
  <img src="https://img.shields.io/badge/Platform-Windows%2011-blue?logo=windows" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## 📌 Project Overview

The **National Anthem — Git & GitHub Workshop** is a hands-on practical project focused on learning version control and collaborative software development.

The project demonstrates how Git and GitHub help developers manage source code, track changes, maintain commit history, work with branches, merge independent development work, and resolve merge conflicts.

The workshop was practised using **Windows PowerShell** on a Windows laptop.

## 🎯 Objectives

- Understand Git and GitHub fundamentals.
- Initialize and manage local repositories.
- Connect local projects to GitHub.
- Perform push and pull operations.
- Create and manage feature branches.
- Make and track multiple commits.
- Merge feature branches into the main branch.
- Create and resolve merge conflicts.
- Develop and run a Flask web application.
- Understand Git history and repository synchronization.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Git | Version control |
| GitHub | Remote repository hosting |
| Windows PowerShell | Command-line interface |
| Python 3.14 | Backend programming |
| Flask | Web application framework |
| HTML5 | Web page structure |
| GitHub README | Project documentation |

## 📂 Project Structure

```text
anthem-workshop/
│
├── README.md
├── anthem.txt
├── app.py
│
└── templates/
    └── index.html
```

## 🚀 Workshop Activities Completed

### Part 0 — Git Configuration

- Installed and configured Git.
- Configured Git username and email.
- Set the default branch to `main`.
- Prepared the Windows PowerShell development environment.

### Part 1 — Repository Creation and Publishing

- Initialized a local Git repository.
- Created the `anthem.txt` file.
- Added and committed the first anthem line.
- Created the GitHub repository.
- Connected the local repository to GitHub.
- Published the project using Git push.

### Part 2 — Project Development and Synchronization

- Created the Flask backend application.
- Created the HTML template.
- Added project files to Git.
- Committed application changes.
- Practised Git pull and push operations.
- Verified repository synchronization.

### Part 3 — Branching and Merging

- Created the `feature/second-stanza` branch.
- Added two separate commits.
- Pushed the feature branch to GitHub.
- Merged the feature branch into `main`.
- Verified the commit history and branch changes.

### Part 4 — Merge Conflict Resolution

- Created the `title-english` branch.
- Created the `title-bilingual` branch.
- Modified the same HTML heading differently.
- Generated an intentional merge conflict.
- Inspected the conflict markers.
- Resolved the conflict manually.
- Committed and pushed the resolved changes.

### Flask Application Testing

- Installed Flask using pip.
- Executed the Python application.
- Started the Flask development server.
- Verified successful server startup.
- Confirmed that the application runs on port 5000.

**Local application address:**

```text
http://127.0.0.1:5000
```

## 💻 Important Git Commands Practised

```powershell
# Initialize repository
git init

# Check repository status
git status

# Add files
git add .

# Commit changes
git commit -m "Your commit message"

# Connect remote repository
git remote add origin REPOSITORY_URL

# Push changes
git push origin main

# Pull latest changes
git pull origin main

# Create feature branch
git switch -c feature/new-feature

# Switch branches
git switch main

# Merge branches
git merge feature/new-feature

# View branches
git branch -a

# View commit history
git log --oneline --graph

# Check tracked files
git ls-files
```

## ✅ Final Repository Verification

The following project files were verified using `git ls-files`:

```text
README.md
anthem.txt
app.py
templates/index.html
```

The final Git verification confirmed:

- Main branch synchronized with GitHub.
- Merge conflict successfully resolved.
- Project files tracked by Git.
- Flask development server started successfully.
- Working tree clean with no pending changes.

## 📚 Key Learnings

Through this practical workshop, I gained experience in:

1. Git installation and configuration.
2. Local and remote repository management.
3. Version control and commit tracking.
4. GitHub push and pull operations.
5. Feature branch creation and merging.
6. Merge conflict identification and resolution.
7. Flask application development and execution.
8. PowerShell-based development workflows.

## 👨‍💻 Author

**Srujan**

GitHub Username: [@srujanrt143-create](https://github.com/srujanrt143-create)

## 🔗 Project Repository

[View National Anthem Workshop on GitHub](https://github.com/srujanrt143-create/anthem-workshop)

---

<p align="center">
  <strong>Built with ❤️ by Srujan</strong>
  <br/>
  <sub>Learn • Practise • Build • Collaborate • Grow</sub>
</p>
