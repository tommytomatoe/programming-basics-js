# programming-basics-js
Programming Basics using JavaScript

## Download source code
```
git clone git@github.com:tommytomatoe/programming-basics-js.git
git clone https://github.com/tommytomatoe/programming-basics-js.git
```

## Git Config
```
git config --global user.name "My Name"
git config --global user.email "email@domain.com"
# Optional
git config --global core.editor vim
```

## Common git commands
```
# Check status of repo
git status

# Add specified file or folder to staging
git add filename1 filename2 folder1 folder 2

# Add all files in currect working directory to staging 
git add .

# Add modified tracked files to staging. Use when no new files are created
git add -u

# Shortcut for git add .; git add -u
git add -A

# Commit changes to the repository
git commit 
# Optional shorthand: commit with message
git commit -m "My message goes here"

# Push commits to remote repository
# orign: remote repository
# master: branch
git push origin master
```