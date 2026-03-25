# Terminal Commands Cheat Sheet

*Command line essentials*

---

## Navigation
```bash
pwd                 # Where am I?
ls                  # List files
ls -la              # List all files including hidden
cd folder-name      # Go into a folder
cd ..               # Go up one folder
cd ~                # Go to home folder
```

---

## File Operations
```bash
touch filename.txt          # Create empty file
mkdir folder-name           # Create folder
cp file1.txt file2.txt      # Copy file
mv oldname.txt newname.txt  # Rename/move file
rm filename.txt             # Delete file (CAREFUL!)
```

---

## Viewing Files
```bash
cat filename.txt            # Show entire file
head filename.txt           # First 10 lines
tail filename.txt           # Last 10 lines
```

---

## Git Commands
```bash
git status
git add .
git commit -m "message"
git push
git pull
```

---

## Gotchas
- `rm` deletes permanently - no undo!
- Tab completion is your friend
- Ctrl+C cancels a running command
- Ctrl+L or clear clears the screen
