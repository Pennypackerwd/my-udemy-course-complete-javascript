# my-udemy-course-complete-javascript
https:#www.udemy.com/course/javascript-training/learn/lecture/8110338#overview

## git instructions

### checkout new branch

```powershell
# Always make sure you're on your main branch
git checkout main

# Always make sure your local is up to date with any changes to your remote
git pull

# Cut a new branch with a name specific to what you're doing
git checkout -b my-new-branch

# Confirm you're in your new branch
git branch 
```

### commit and push

```powershell
# Stage all of the files you want to commit. There are ways to do individual files
# but the easiest way is to just add everything.
git add .

# Commit those changes with a short explanation message
git commit -m "Made some changes"

# Push your changes up to the remote
git push

# If this was your first push for a branch, chances are it will throw and error saying there is no remote setup.
# Just copy and paste the output command into PowerShell and it will do what it needs to do for you.
```

### undo commit

```powershell
# undo a commit that hasn't been pushed on the current branch
git reset HEAD~
```