# 🚀 **Learn Git & Git Commands** 🚀

## 🔧 **Basic Setup**

Before you start using Git, ensure you have it installed and configured on your computer.

**Install Git**:
   Download and install Git from [here](https://git-scm.com/).

**Configure Git**:
   Set up your user name and email globally. This information will be used for commits.

   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your-email@example.com"
   git config --list

**Check Git Version**

Check the version of Git installed on your system:

```bash
git --version

**Check Git Version**:
    Check the version of Git installed on your system:

    ```bash
    git --version


**Clone a Repository:**
    Clone a repository from a remote source (e.g., GitHub):

    ```bash
    git clone <link>

5. **View Remote Repositories:**
    View the remotes associated with your repository:

    ```bash
    git remote -v

6. **List Global Git Configuration:**

    ```bash
    git config --global --list

7. **List all Git Configuration:**

    ```bash
    git config --list

8. **Show all Logs:**

    ```bash
    git log

9. **Get status of the file:**

    ```bash
    git status

10. **To initialize git:**

    ```bash
    git init

11. **To Commit:**

    ```bash
    git commit -m "Message_here"

12. **To change the branch name from master to main:**
    
    ```bash
    git branch -M main

13. **To add Origin of remote repository:**

    ```bash
    git remote add origin <link> # origin is the name

14. **To check remote repository:**

    ```bash
    git remote -v

15. **To push files into repository:**

    ```bash
    git push -u origin main # -u set upstream for origin and branch, origin remote repository name , main branch

16. **To check branch:**

    ```bash
    git branch #(to check branch)

17. **To rename branch:**

    ```bash
    git branch -M main #(to rename branch , default branch is master and it is changed to main)


18. **To create and navigate to new branch:**

    ```bash
    git checkout -b branch_name (to create branch and navigates to branch_name)

19. **To Navigate branch:**

    ```bash
    git checkout branch_name (to navigate)

20. **To delete branch:**

    ```bash
    git branch -d branch_name

21. **To commit changes to repository when using branches:**

    ```bash
    git push origin branch_name (while working with branches)

22. **To pull when branches are merged in Github using pull request:**

    ```bash
    git pull origin main (used to fetch and download content from a remote repo and update the local repository to match the content)

23. **To compare changes between branches:**

    ```bash
    git diff <branch_to_compare>

    
24. **To merge feature in a branch:**

    ```bash
    git merge <branch_to_merge> - used to merge features and to resolve conflicts related to features

25. **Pull Request:**
    to merge in github used to tell others about changes you have pushed to remote repository in github - to resolve conflicts related to features



26. **Undoing Changes**

    ```bash
     
    git reset <file_name> - for staging undo

    git reset - for staging undo all files

    git reset HEAD~1

    git reset <commit_hash>

    git reset --hard <commit_hash> - make changes in github

27. **Fork:**
    A rough copy - a new repository that shares code and visibility settings with the original upstream repository 
