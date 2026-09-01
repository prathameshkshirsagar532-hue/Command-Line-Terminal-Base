

#
# Terminal CMD

claude install in Terminal command 
```bash

curl -fsSL https://claude.ai/install.sh
```

```bash

```
```bash

```




# GitHub

git install in Terminal 
```bash
winget install --id Git.Git -e --source winget
```
check git version 
```bash
git --version
```

#



#
### login git in Terminal 

Two method for git login
#
M-I

install git Cli
```bash
winget install GitHub.cli
```
#
M-II
login git in Terminal 
```bash
git auth login
```
```bash
git add .
```
```bash
git commit -m "my_commit"
```
```bash
git push main origin 
```
```bash

```
```bash

```
#


#
📂 1. Setup & Initialization :Used when starting with Git for the very first time on your system or creating a new project

Sets your commit username
```bash
git config --global user.name "user_name"
```
 Sets your commit email address
```bash
git config --global user.email "your.email@example.com"
```
Initializes a brand new local Git repository in your current folder
```bash
git init
```
Downloads an existing project from GitHub to your computer
```bash
git clone <repository_url>

```







#
📝 2. Everyday Workflow : The core commands you will use multiple times a day to track and save your work

Shows modified, staged, and untracked files in your project
```bash
git status
```
Adds a specific file to the staging area (prepares it to be saved).
```bash
git add <file_name>
```
Adds all changed and new files to the staging area at once
```bash
git add .
```
Permanently saves your staged snapshot with a custom message.
```bash
git commit -m "Your message"
```

#




# 🛠️ Git Commands Cheat Sheet: Basic to Advanced

## 📂 1. Setup & Initialization
Used when starting with Git for the very first time on your system or creating a new project.

Sets your commit username.
```bash
git config --global user.name "Your Name"
```

Sets your commit email address.
```bash
git config --global user.email "your.email@example.com"
```

Initializes a brand new local Git repository in your current folder.
```bash
git init
```

Downloads an existing project from GitHub to your computer.
```bash
git clone <repository_url>
```

---

## 📝 2. Everyday Workflow
The core commands you will use multiple times a day to track and save your work.

Shows modified, staged, and untracked files in your project.
```bash
git status
```

Adds a specific file to the staging area (prepares it to be saved).
```bash
git add <file_name>
```

Adds all changed and new files to the staging area at once.
```bash
git add .
```

Permanently saves your staged snapshot with a custom message.
```bash
git commit -m "Your descriptive message"
```

---

## 🌐 3. Sharing & Syncing with GitHub
Commands used to connect your local computer to remote platforms like GitHub.

Links your local repository to a remote GitHub repository.
```bash
git remote add origin <repository_url>
```

Uploads your local code to GitHub for the first time and sets the default branch.
```bash
git push -u origin main
```

Uploads your latest local commits to GitHub (after the initial setup).
```bash
git push
```

Fetches updates from GitHub and instantly merges them into your local files.
```bash
git pull
```

Downloads history from GitHub without changing your local files (safe inspection).
```bash
git fetch
```

---

## 🌿 4. Branching & Merging
Used to work on new features isolated from the main working code.

Lists all local branches in your repository (current branch is highlighted).
```bash
git branch
```

Creates a new branch with the specified name.
```bash
git branch <branch_name>
```

Switches from your current branch to the specified branch.
```bash
git checkout <branch_name>
```

Creates a new branch and immediately switches to it.
```bash
git checkout -b <branch_name>
```

Combines the history and code of the specified branch into your active branch.
```bash
git merge <branch_name>
```

Deletes the specified branch once its code has been merged.
```bash
git branch -d <branch_name>
```

---

## 🔍 5. Inspection & History
Commands to look back in time and see what changes were made, when, and by whom.

Shows the full history of all commits made in the current branch.
```bash
git log
```

Displays a compact, one-line version of your commit history.
```bash
git log --oneline
```

Shows the exact line-by-line differences in your unstaged files.
```bash
git diff
```

Shows who modified each line of a specific file and when.
```bash
git blame <file_name>
```

---

## 🚀 6. Advanced Commands
Used for fixing mistakes, rewriting history, or managing complex project workflows.

Undoes your last commit, keeping all your changes safe in the staging area.
```bash
git reset --soft HEAD~1
```

Permanently deletes your last commit and completely erases all uncommitted changes. (Use with caution!)
```bash
git reset --hard HEAD~1
```

Safely creates a completely new commit that undoes the changes of an old, specific commit.
```bash
git revert <commit_id>
```

Temporarily shelves (hides) your uncommitted modifications so you can switch branches without committing.
```bash
git stash
```

Brings back your latest stashed changes to your working directory.
```bash
git stash pop
```

Copies a specific commit from a completely different branch and applies it onto your current branch.
```bash
git cherry-pick <commit_id>
```

Integrates all the latest updates from the main branch into your current branch for a linear history.
```bash
git rebase main
```
#



# Claude Extensions use command

claude watermark remove command use in claude Extensions 
```bash

/remove-ai-marks
```
For a Download this Extension use this repo:

https://github.com/guillaumemeyer/watermarks-remover/blob/main/skills/remove-ai-marks/SKILL.md

download Raw file add on claude Extensions
#

```bash

```
```bash

```
