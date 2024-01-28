*Welcome to the Git-Essentials-Commands repository! 🚀*

*This repository serves as a comprehensive guide for mastering Git and GitHub commands. Whether you're a beginner looking to initiate your first commit or an experienced developer aiming to enhance your version control skills, this guide is tailored for you.*


#  BASIC COMMANDS FOR GIT & GITHUB 🧑‍💻
**For First Commit:**
- `git init`: Initializes a new Git repository in the current working directory.

**To Connect Git to GitHub:**
1. `git config --global user.name "VINAY PRABHAKAR"`: Sets the name of the user for commits.
2. `git config --global user.email "info@prabhakar.tech"`: Sets the email address for commits.
3. `git remote add origin https://github.com/path_name.git`: Links the local repository to a GitHub repository.

**SSH Key Generation:**
- `ssh-keygen -t ed25519 -C "info@prabhakar.tech"`: Generates an SSH key pair.
- `cat < ~/.ssh/id_ed25519.pub`: Displays the public key in the terminal.

**GitHub SSH Key Setup:**
1. Go to GitHub account settings and click on "SSH and GPG keys."
2. Click "New SSH key" and paste the public key.
3. Click "Add SSH key."

**Branch Operations:**
- `git branch -M main`: Renames the primary branch to 'main.'
- `push --set-upstream origin main`: Pushes changes to the 'main' branch on GitHub.
- `git branch branch_name`: Creates a new branch.
- `git checkout branch_name`: Switches to the specified branch.

**Add, Commit, Push, Full, Delete, and History:**
- `git status`: Displays the current repository status.
- `git add "file name"`: Stages a single file.
- `git add --all` or `git add .`: Stages all changes.
- `git reset file.name`: Untracks a single file from the staging area.
- `git commit -m "your message"`: Commits changes with a descriptive message.
- `git log`: Checks commit history.
- `git commit -a -m "message"`: Commits all changes after staging.
- `git diff --staged`: Shows differences between the working directory and staging area.

**Push, Pull, Rollback, History Check, Revert Changes:**
- `git push`: Pushes changes to the remote repository.
- `git pull`: Fetches and merges changes from the remote repository to the local repository.
- `git log`: Checks commit history.
- `git reset --hard commit_hash`: Rolls back to a specific commit, discarding changes after that commit.
- `git revert commit_hash`: Creates a new commit that undoes the changes made in a previous commit.

**Remove Git Repository:**
- `rm -rf .git`: Removes the Git repository from the current working directory. Use with caution.
