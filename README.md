.

🧱 1️⃣ Basic Git Commands
Command	Description
git init	Initialize a new Git repository
git clone <repo-url>	Clone a remote repository
git add <file>	Stage file(s) for commit
git add .	Stage all changes
git status	Check current status
git commit -m "message"	Commit changes
git push origin main	Push commits to remote
git pull origin main	Pull latest changes from remote
git branch	List all branches
git branch <branch-name>	Create new branch
git checkout <branch-name>	Switch branches
git checkout -b <branch>	Create + switch branch
git log	Show commit history
git log --oneline	Condensed history
git config --global user.name "Your Name"	Set global username
git config --global user.email "email@example.com"	Set global email
🌿 2️⃣ Branching & Merging
Command	Description
git branch -d <branch>	Delete branch
git merge <branch>	Merge another branch into current
git merge --abort	Cancel merge conflict
git diff	Show unstaged changes
git diff --staged	Show staged changes
git log --graph --oneline --decorate	Visualize branches graphically
🔄 3️⃣ Remote Repository Management
Command	Description
git remote -v	List remotes
git remote add origin <url>	Add remote repository
git remote remove origin	Remove remote
git fetch origin	Fetch changes without merging
git push -u origin main	Push and set upstream branch
git push origin --delete <branch>	Delete remote branch
🧩 4️⃣ Undo & Reset Commands
Command	Description
git restore <file>	Undo working directory changes
git restore --staged <file>	Unstage a file
git reset	Unstage all staged changes
git reset --hard	Reset working directory completely
git reset --hard <commit>	Reset to a specific commit
git revert <commit>	Undo a specific commit safely
git checkout -- <file>	Restore file to last committed version
🧠 5️⃣ Viewing & Inspecting History
Command	Description
git show <commit>	Show commit details
git diff <commit1> <commit2>	Compare two commits
git blame <file>	Show who changed each line
git shortlog -s -n	Show commit summary by user
git log --stat	Show files changed per commit
git reflog	View all reference changes (safety net)
⚙️ 6️⃣ Stash Commands (Temporary Save)
Command	Description
git stash	Save uncommitted changes
git stash save "message"	Save with message
git stash list	Show stashes
git stash apply	Apply last stash
git stash pop	Apply & remove last stash
git stash drop	Delete a stash
git stash clear	Delete all stashes
🧼 7️⃣ Clean-Up Commands
Command	Description
git clean -n	Show untracked files that will be removed
git clean -f	Remove untracked files
git gc	Clean unnecessary files
git prune	Remove unreachable Git objects
🧩 8️⃣ Tagging & Releases
Command	Description
git tag	List all tags
git tag v1.0	Create a lightweight tag
git tag -a v1.0 -m "Release v1.0"	Create annotated tag
git show v1.0	Show tag info
git push origin v1.0	Push tag to remote
git push origin --tags	Push all tags
git tag -d v1.0	Delete a local tag
git push origin --delete v1.0	Delete remote tag
🔧 9️⃣ Git Configuration & Aliases
Command	Description
git config --list	Show current configuration
git config --global alias.co checkout	Create alias (shortcut)
git config --global core.editor "code --wait"	Set VS Code as default editor
git config --global color.ui auto	Enable color output
🧱 🔟 File Management
Command	Description
git rm <file>	Remove a tracked file
git rm --cached <file>	Remove file but keep locally
git mv <old> <new>	Rename or move file
git add -A	Add all changes (tracked + untracked)
💣 11️⃣ Advanced / Expert Commands
Command	Description
git cherry-pick <commit>	Apply a specific commit to current branch
git bisect start	Start binary search for buggy commit
git bisect bad / git bisect good	Mark commits as bad/good
git submodule add <repo-url>	Add another repo inside yours
git rebase <branch>	Reapply commits on top of another branch
git rebase -i HEAD~3	Interactive rebase (edit last 3 commits)
git merge --squash <branch>	Combine all commits from branch into one
git fetch --all --prune	Fetch all remotes and clean deleted branches
🧩 12️⃣ Safety & Backup
Command	Description
git archive --format=zip HEAD > latest.zip	Export current project as ZIP
git bundle create repo.bundle --all	Backup entire repo
git fsck	Check repo integrity
git verify-commit <commit>	Verify commit signature
🧾 13️⃣ Helpful Visualizations
Command	Description
git log --graph --decorate --oneline --all	Show branch graph
gitk	Open Git GUI viewer
git gui	Simple Git GUI interface
⚡ Bonus: Common Shortcuts
git co = checkout
git st = status
git ci = commit
git br = branch
git lg = log --oneline --graph --decorate --all
