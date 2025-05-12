# Git and GitHub Learning Challenge - Season 2 Day 2

## Challenge Steps

### 1. Installing Git (on Ubuntu)
```bash
sudo apt-get install git
```

### 2. Make an Account on GitHub
Create your account at [github.com](https://github.com/)

### 3. Fork and Clone Repository
```bash
# First fork the repository on GitHub.com
# Then clone your fork locally
git clone https://github.com/YourUsername/LearnWithSagar.git
cd LearnWithSagar
```

### 4. Set Up Username and Email
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### 5. Create a Feature Branch and Make Changes
```bash
git checkout -b feature/your-feature-name
# Make changes to files in your text editor
```

### 6. Stage and Commit Your Changes
```bash
git add .
git commit -m "Descriptive commit message"
```

### 7. Push the Changes
```bash
git push origin feature/your-feature-name
```

### 8. Create a Pull Request on GitHub
Go to your forked repository on GitHub and click the "Pull Request" button

### 9. Simulate a Merge Conflict
Modify the same file from another GitHub account, then:
```bash
git checkout main
git pull origin main
git checkout feature/your-feature-name
git merge main
# Conflicts will appear
```

### 10. Resolve Conflicts Manually and Commit
```bash
# Edit files to resolve conflicts
git add .
git commit -m "Resolved merge conflict in your-feature-name"
```

### 11. Clean Up - Delete Your Feature Branch Locally and Remotely
```bash
git checkout main
git branch -d feature/your-feature-name
git push origin --delete feature/your-feature-name
```

## Important Git Commands Summary

| Command | Description |
|---------|-------------|
| `git init` | Initializes a new Git repository |
| `git clone` | Copies a remote repository to your local machine |
| `git config` | Configures user details like name and email |
| `git checkout -b` | Creates and switches to a new branch |
| `git add .` | Stages all changes for commit |
| `git commit -m "message"` | Saves changes to the repository with a message |
| `git push origin branch` | Pushes local changes to a remote repository |
| `git pull origin main` | Fetches and merges the latest changes from the main branch |
| `git merge branch` | Merges another branch into the current branch |
| `git log` | Displays the commit history |
| `git diff` | Shows changes between commits, branches, or working directory |
| `git branch -d branch` | Deletes a local branch |
| `git push origin --delete branch` | Deletes a remote branch |

## Key Terminology
- **HEAD**: Represents the current branch or commit you are working on
- **origin**: The default name for the remote repository from which the local repository was cloned
