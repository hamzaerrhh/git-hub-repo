# GitHub Project

This project is created to learn the basics of **Git**, **GitHub**, **Version Control**, and using **Git commands in the terminal (CMD)**.

---

## What is Git, GitHub, and Version Control?

### Version Control
Version control is a system that helps track changes made to files over time.  
It allows you to:
- Save different versions of your project
- Restore previous versions if needed
- Collaborate with others safely

### Git
Git is a **distributed version control system** that runs on your local machine.  
It helps developers:
- Track code changes
- Manage project history
- Create branches and merge code

### GitHub
GitHub is an **online platform** that hosts Git repositories.  
It allows you to:
- Store your projects in the cloud
- Share code with others
- Collaborate on projects and contribute to open source

---

## Install Git on Your Machine

1. Download Git from the official website:  
   https://git-scm.com/

2. Install Git by following the instructions for your operating system.

3. Verify the installation by running the following command in your terminal:

```bash
git --version
```
If Git is installed correctly, it will display the installed version.

## Step 1: Initialize Git in a Project

Once Git is installed, you can initialize a Git repository in your project folder:

Open your terminal (CMD, PowerShell, or Terminal).

Navigate to your project folder using the cd command. For example:
```bash
cd path/to/your/project
```

Initialize Git in the folder:
```bash
git init
```

📌 What this does:

Creates a hidden .git folder in your project

Starts tracking changes in your files

Prepares your project to use Git commands like add, commit, and push
