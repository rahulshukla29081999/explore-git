This file documents essential Git & GitHub commands commonly used in real-world development workflows.
It works as a quick reference for beginners and a revision guide for experienced developers.

---GIT SETUP & CONFIGURATION---

git --version
Check installed Git version

git config --global user.name "Rahul Shukla"
Configure global Git username

git config --global user.email shuklarahulkanpur@gmail.com

Configure global Git email

git config --list
Verify Git configuration

---REPOSITORY BASICS---

git init
Initialize a new Git repository

git status
Check current file status

---STAGING & COMMIT---

git add index.html
Stage a specific file

git add .
Stage all modified files

git commit -m "first v1 of index.html"
Create a commit (snapshot of changes)

---HISTORY & CHANGES---

git log
View detailed commit history

git log --oneline
Compact one-line commit history

git diff
View unstaged changes

git diff --cached
View staged changes

git show <commitID>
Inspect a specific commit

git show <commitID>:index.html
View a file from an old commit

---BRANCHING & NAVIGATION---

git checkout <branch>
Switch to another branch

git checkout -b <branch>
Create and switch to a new branch

git branch -M main
Rename default branch from master to main

---UNDO & RESET---

git restore .
Discard changes in working directory

git restore --staged <file>
Unstage a file

git reset --soft HEAD^
Undo last commit but keep changes staged

git reset --hard HEAD^
Completely remove last commit and changes

---REMOTE & GITHUB OPERATIONS---

git remote -v
View connected remote repositories

git push
Push commits to GitHub

git pull
Fetch and merge latest changes

git clone <repo-url>
Clone a remote repository

---COLLABORATION WORKFLOW---

Merge Conflict
Resolve conflicting changes manually when Git cannot auto-merge

Fork & Pull Request
Fork a repository, make changes, and raise a Pull Request for review

---IGNORE & CLEANUP---

.gitignore
Prevent unwanted files (logs, secrets, build files) from being tracked

git clean
Remove untracked files from working directory

---GIT TAGS---

git tag
Mark important commits (versions / releases)

Tags are commonly used for:

Release versions (v1.0, v2.0)

Production deployments

Stable checkpoints

---CONCLUSION---

This guide covers core Git & GitHub commands required for:

Daily development work

Team collaboration

Open-source contributions

Interview preparation

Mastering these commands builds a strong foundation for DevOps, CI/CD, Docker, Kubernetes, and Cloud workflows.

Author: Rahul Shukla
Role: DevOps Learner
