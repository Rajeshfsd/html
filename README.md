# 🧠 Git Commands Cheat Sheet

A complete list of essential **Git commands** for daily use, from basic to expert level.

---

## 🧱 1️⃣ Basic Commands

| Command | Description |
|----------|--------------|
| `git init` | Initialize a new Git repository |
| `git clone <repo-url>` | Clone a remote repository |
| `git add <file>` | Stage file(s) for commit |
| `git commit -m "message"` | Commit staged changes |
| `git push origin main` | Push commits to GitHub |
| `git pull origin main` | Pull updates from GitHub |
| `git status` | Check current status |
| `git branch` | List all branches |
| `git checkout -b <branch>` | Create + switch branch |

---

## 🌿 2️⃣ Branching & Merging

| Command | Description |
|----------|--------------|
| `git branch -d <branch>` | Delete branch |
| `git merge <branch>` | Merge another branch |
| `git merge --abort` | Cancel a merge |
| `git log --graph --oneline --decorate` | Visualize branch graph |

---

## 🔄 3️⃣ Remote Repository

| Command | Description |
|----------|--------------|
| `git remote -v` | List remotes |
| `git remote add origin <url>` | Add remote |
| `git push -u origin main` | Push & set upstream |
| `git fetch origin` | Fetch remote updates |
| `git push origin --delete <branch>` | Delete remote branch |

---

## 🧩 4️⃣ Undo / Fix Mistakes

| Command | Description |
|----------|--------------|
| `git restore <file>` | Undo working changes |
| `git reset --hard` | Discard all uncommitted changes |
| `git revert <commit>` | Undo a specific commit |
| `git checkout -- <file>` | Restore file to last commit |

---

## 🧠 5️⃣ History & Diffs

| Command | Description |
|----------|--------------|
| `git log` | View commit history |
| `git diff` | View unstaged changes |
| `git show <commit>` | Show commit details |
| `git blame <file>` | Show who changed each line |

---

## ⚙️ 6️⃣ Stashing

| Command | Description |
|----------|--------------|
| `git stash` | Save uncommitted work |
| `git stash list` | List saved stashes |
| `git stash pop` | Apply & remove stash |
| `git stash clear` | Remove all stashes |

---

## 🧱 7️⃣ File Management

| Command | Description |
|----------|--------------|
| `git rm <file>` | Remove a tracked file |
| `git mv old new` | Rename/move file |
| `git add -A` | Add all changes |

---

## 🧩 8️⃣ Tagging & Releases

| Command | Description |
|----------|--------------|
| `git tag v1.0` | Create tag |
| `git tag -a v1.0 -m "msg"` | Annotated tag |
| `git push origin v1.0` | Push tag |
| `git push origin --tags` | Push all tags |

---

## 💣 9️⃣ Advanced Commands

| Command | Description |
|----------|--------------|
| `git cherry-pick <commit>` | Apply a specific commit |
| `git rebase <branch>` | Move commits on top of another branch |
| `git merge --squash <branch>` | Combine all commits into one |
| `git submodule add <url>` | Add another repo inside your repo |

---

## ⚡ 10️⃣ Helpful Aliases

```bash
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.lg "log --oneline --graph --decorate --all"
