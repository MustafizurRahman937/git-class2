
Copilot Search Branding

Like

Dislike
A Git cheat sheet is a compact reference listing essential Git commands such as git init, git clone, git add, git commit, git branch, git merge, and git push, helping you quickly recall common workflows.
Below is a consolidated, structured Git cheat sheet based on authoritative sources.

Getting Started
git init — Initialize a new repository. 
Linuxize
Linuxize
git clone <url> — Clone an existing repository. 
Git
Git
git config --global user.name "Name" — Set global username. 
Linuxize
Linuxize
git config --global user.email "email" — Set global email. 
Linuxize
Linuxize
Staging & Committing
git status — Show working tree status. 
Linuxize
Linuxize
git add <file> — Stage a file. 
Linuxize
Linuxize
git add . — Stage all changes. 
Git
Git
git commit -m "message" — Commit staged changes. 
Linuxize
Linuxize
git commit --amend — Amend last commit. 
Linuxize
Linuxize
Branching
git branch — List branches. 
Git
Git
git branch <name> — Create a branch. 
Linuxize
Linuxize
git switch <name> or git checkout <name> — Switch branches. 
Git
Git
git branch -d <name> — Delete a branch. 
Git
Git
Merging & Rebasing
git merge <branch> — Merge a branch into current. 
GitHub
GitHub
git rebase <branch> — Rebase onto another branch. 
Linuxize
Linuxize
git rebase -i HEAD~N — Interactive rebase. 
Git
Git
Remote Repositories
git remote -v — List remotes. 
Linuxize
Linuxize
git remote add origin <url> — Add remote. 
Linuxize
Linuxize
git fetch — Fetch from remote. 
GitHub
GitHub
git pull — Fetch and merge. 
GitHub
GitHub
git push — Push to remote. 
GitHub
GitHub
Stashing
git stash — Stash changes. 
Linuxize
Linuxize
git stash list — List stashes. 
Linuxize
Linuxize
git stash pop — Apply and remove latest stash. 
Linuxize
Linuxize
Inspecting History & Diffs
git log — View commit history. 
Linuxize
Linuxize
git log --oneline --graph — Compact graph view. 
Linuxize
Linuxize
git diff — Show unstaged diff. 
Linuxize
Linuxize
git diff --staged — Show staged diff. 
Linuxize
Linuxize
git show <commit> — Show commit details. 
Git
Git
Undo & Cleanup
git restore <file> — Discard local changes. 
Linuxize
Linuxize
git reset --soft HEAD~1 — Undo commit, keep changes. 
Linuxize
Linuxize
git reset --hard HEAD — Reset to last commit. 
Linuxize
Linuxize
git clean -fd — Remove untracked files/dirs. 
Linuxize
Linuxize
Tags
git tag — List tags. 
Linuxize
Linuxize
git tag v1.0.0 — Create tag. 
Linuxize
Linuxize
git push --tags — Push all tags. 
Linuxize
Linuxize
This cheat sheet summarizes the most commonly used Git commands for everyday development workflows.
