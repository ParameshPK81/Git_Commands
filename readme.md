# Git - Version Control System

This document provides a basic overview of essential Git commands.

**1. Checking Git Version**

*   **Command:** `git --version`
*   **Purpose:** Displays the installed Git version.

**2. Cloning a Repository**

*   **Command:** `git clone <link>`
*   **Purpose:** Creates a local copy of a repository from a remote source (e.g., GitHub).

**3. Viewing Remote Repositories**

*   **Command:** `git remote -v`
*   **Purpose:** Lists all remote repositories associated with the current repository.

**4. Global Git Configuration**

*   **Command:** `git config --global --list` 
*   **Purpose:** Displays all globally configured Git settings.

*   **Command:** `git config --global user.name "your_name"`
*   **Purpose:** Sets the global username for Git commits.

*   **Command:** `git config --global user.email "your_email@example.com"`
*   **Purpose:** Sets the global email address for Git commits.

*   **Command:** `git config --list`
*   **Purpose:** Displays the current repository's configuration settings.

**5. Working with Commits**

*   **Command:** `git log`
*   **Purpose:** Shows the commit history of the current branch.

*   **Command:** `git status`
*   **Purpose:** Displays the current state of the working directory and staging area.

*   **Command:** `git init`
*   **Purpose:** Initializes a new Git repository in the current directory.

*   **Command:** `git add .`
*   **Purpose:** Adds all changes in the working directory to the staging area.

*   **Command:** `git commit -m "Your Commit Message"`
*   **Purpose:** Creates a new commit with the specified message.

**6. Branching and Merging**

*   **Command:** `git branch`
*   **Purpose:** Lists all local branches.

*   **Command:** `git branch -M main` 
*   **Purpose:** Renames the current branch to "main" (recommended over "master").

*   **Command:** `git remote add origin <link>` 
*   **Purpose:** Adds a remote named "origin" to the repository.

*   **Command:** `git push -u origin main` 
*   **Purpose:** Pushes the "main" branch to the remote repository and sets the upstream branch.

*   **Command:** `git checkout -b branch_name`
*   **Purpose:** Creates a new branch and switches to it.

*   **Command:** `git checkout branch_name`
*   **Purpose:** Switches to the specified branch.

*   **Command:** `git branch -d branch_name`
*   **Purpose:** Deletes the specified branch.

*   **Command:** `git push origin branch_name`
*   **Purpose:** Pushes the specified branch to the remote repository.

*   **Command:** `git pull origin main`
*   **Purpose:** Fetches and merges changes from the remote "main" branch into the current branch.

*   **Command:** `git diff <branch_to_compare>`
*   **Purpose:** Shows the differences between the current branch and the specified branch.

*   **Command:** `git merge <branch_to_merge>`
*   **Purpose:** Merges the specified branch into the current branch.

*   **Pull Request:** A mechanism (typically used on platforms like GitHub) to propose merging changes from one branch into another.

**7. Undoing Changes**

*   **Command:** `git reset <file_name>`
*   **Purpose:** Unstages changes for the specified file.

*   **Command:** `git reset`
*   **Purpose:** Unstages changes for all files.

*   **Command:** `git reset HEAD~1`
*   **Purpose:** Unstages and discards the last commit.

*   **Command:** `git reset --hard <commit_hash>`
*   **Purpose:** Resets the current branch to the specified commit (use with caution).

**8. Forking**

*   **Fork:** A copy of a repository that allows you to make changes without affecting the original repository.

This README provides a concise and easy-to-understand overview of essential Git commands. Remember to consult the official Git documentation for more advanced usage and detailed information.