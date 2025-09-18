# CFAL2-Python_data_science_ai_for_2025


# Git commands for reference
## 1. Clone a Remote Repository
```bash
git clone <remote-repo-url>
cd <repo-folder>
```
## 2. Check Local and Remote Branches
# Local branches
```bash
git branch
```
# Remote branches
```bash
git branch -r
```
# Local + Remote branches
```bash
git branch -a
```
## 3. Create a Local Branch Tracking a Remote Branch
```bash
git checkout -b feature origin/feature
```
Pull the latest changes from the remote branch to your local branch. 
```bash
git pull
```
## 4. Development: Add / Modify Files
```bash
# Check changes
git status

# Stage files for commit
git add <file1> <file2>
# Or stage all changes
git add .

# Commit changes
git commit -m "Describe your changes"
```
## 5. Push Changes to Remote Branch
```bash
git push origin feature
```
For the first push, set upstream:
```bash
git push -u origin feature
```
After setting upstream, you can simply use git push in the future.
## 6. Create Additional Branches (e.g., release)
```bash
git checkout -b release
git push -u origin release
```
Creates a new local branch release and pushes it to remote.
## 7. Delete Branches
```bash
# Delete local branch
git branch -d feature
git branch -D feature   # Force delete if not merged

# Delete remote branch
git push origin --delete feature
```


from IPython.core.interactiveshell import InteractiveShell
InteractiveShell.ast_node_interactivity = "all"




