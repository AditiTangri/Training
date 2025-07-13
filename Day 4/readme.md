# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING 
**DAY - 4**
**Date:** 26 June 2025  

---

## GITHUB :

Git is the free and open source distributed version control system that's responsible for everything GitHub related that happens locally on your computer.

### Understanding Github Commands  
GitHub commands are an essential part of the Git version control system, which is used to track changes in code and collaborate with others. Git operates on a series of commands that allow users to perform actions like creating repositories, managing branches, and merging changes.

---

### Check if Git is already installed  
Open your terminal and run:  
```bash
git --version
```
### Install Git on Ubuntu
If Git is not installed, you can install it using:
```bash
sudo apt update
sudo apt install git
```

###	After Installation: Set Your Identity
Once installed, configure your Git identity (required for committing code):
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
###	Create or Clone a Repository
```bash
# Initialize a new local repo
git init

# Clone an existing GitHub repo
git clone https://github.com/username/repo.git
```

#	Basic Workflow
```bash
# Check the status of your repo
git status

# Stage files for commit
git add filename       # Add one file
git add .              # Add all changed files

# Commit staged files
git commit -m "Your message here"
```

#	Push & Pull
```bash
# Push commits to GitHub 
git push origin main

# Pull latest changes from GitHub
git pull origin main
```

**By**: Aditi Tangri

**URN**: 2302460  

**CRN**: 2315004
