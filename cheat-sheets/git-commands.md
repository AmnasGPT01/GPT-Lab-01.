# Git Commands Cheat Sheet

*Commands I need but always forget*

---

## Basic Git Commands

### Check Status
```bash
git status
```
Shows what files have changed

---

### See What Changed
```bash
git diff
```
Shows the actual changes in files

---

### Add Files to Commit
```bash
git add filename.txt      # Add specific file
git add .                 # Add all files
git add *.py              # Add all Python files
```

---

### Commit Changes
```bash
git commit -m "Description of what I changed"
```

---

### Push to GitHub
```bash
git push
```

---

### Pull Latest Changes
```bash
git pull
```

---

### See Commit History
```bash
git log
git log --oneline     # Shorter version
```

---

### Create New Branch
```bash
git checkout -b branch-name
```

---

### Switch Branches
```bash
git checkout branch-name
```

---

### Go Back to Main Branch
```bash
git checkout main
```

---

## Common Workflows

### Daily Workflow
```bash
git pull                    # Get latest changes
# ... do your work ...
git add .                   # Add all changes
git commit -m "message"     # Commit
git push                    # Push to GitHub
```

---

## Gotchas
- `git add .` adds **everything** - be careful!
- Commit messages should describe **what** changed, not just "update"
- Always `git pull` before starting work to avoid conflicts

---

## Resources
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [Oh Shit Git](https://ohshitgit.com/) - How to fix git mistakes
