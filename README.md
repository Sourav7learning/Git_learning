# 📘 Git & GitHub Complete Guide  

## 🚀 What is Git?  
- **Git** is a **distributed version control system**.  
- It helps developers **track changes** in code, collaborate with teams, and revert history if needed.  
- Every developer has a full copy of the repository (history + code).  

---

## 🌍 What is GitHub?  
- **GitHub** is a cloud platform that hosts Git repositories.  
- It adds collaboration features: **Pull Requests, Issues, Actions (CI/CD), Wiki, Pages**.  
- Think of Git as the engine, GitHub as the garage where everyone works together.  

---

## 💡 Why Git & GitHub are Important  
- **Collaboration**: Multiple developers can work on the same project.  
- **Version Control**: Track who changed what and when.  
- **Backup**: Your code is safely stored in the cloud.  
- **Open Source**: Millions of public repositories to learn from.  
- **Automation**: Integrates with CI/CD pipelines.  

---

## 🛠️ Git Setup  
```bash
# Configure username & email (once per machine)
git config --global user.name "Your Name"
git config --global user.email "you@example.com"


#Create or Clone a Repository

# Start a new repo locally
git init

# Clone existing repo
git clone https://github.com/username/repo.git

# Check repo status
git status

# Stage changes
git add file.txt        # add single file
git add .               # add all files

# Commit changes
git commit -m "Meaningful commit message"

# Push to remote
git push origin master
# Check config
git config --list
