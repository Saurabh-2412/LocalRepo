
---

### **Basic Git Commands**

1. **Create a New Directory:**
   ```bash
   mkdir directory_name
   ```
   Creates a new directory named `directory_name`.

2. **Check Git Status:**
   ```bash
   git status
   ```
   Shows the current status of the repository, including staged, unstaged, and untracked files.

3. **Initialize a Git Repository:**
   ```bash
   git init
   ```
   Initializes a new Git repository in the current directory.

4. **Create a File:**
   ```bash
   echo welcome to file two in gitone > file.txt
   ```
   Creates a file named `file.txt` with the content `welcome to file two in gitone`.

5. **Add Files to Staging Area:**
   ```bash
   git add file.txt
   ```
   Stages `file.txt` for the next commit.  
   Use `git add .` to stage all changes in the directory.

6. **Commit Changes:**
   ```bash
   git commit -m "add file one"
   ```
   Commits staged changes with the message `"add file one"`.

7. **Add a Remote Repository:**
   ```bash
   git remote add origin <LINK>
   ```
   Adds a remote named `origin` with the repository URL `<LINK>`.

8. **Verify Remote Repository:**
   ```bash
   git remote -v
   ```
   Lists the remote repositories linked to your local repository.

9. **Check Current Branch:**
   ```bash
   git branch
   ```
   Displays the list of branches and highlights the current branch.

10. **Rename the Default Branch:**
    ```bash
    git branch -M main
    ```
    Renames the current branch (default is `master`) to `main`.

11. **Push Changes to Remote:**
    ```bash
    git push -u origin main
    ```
    Pushes the local branch `main` to the remote `origin` and sets it as the default tracking branch.  
    Use `git push origin <branch-name>` to push other branches.

---

### **Branching and Merging**

12. **Create and Switch to a New Branch:**
    ```bash
    git checkout -b <New Branch Name>
    ```
    Creates and switches to a new branch named `<New Branch Name>`.

13. **Switch Branches:**
    ```bash
    git checkout main
    ```
    Switches to the `main` branch.

14. **Delete a Branch:**
    ```bash
    git branch -d <Branch Name>
    ```
    Deletes the branch `<Branch Name>`. Cannot delete the currently active branch.

15. **View Branch Differences:**
    ```bash
    git diff main
    ```
    Shows the difference between the current branch and the `main` branch.

16. **Merge Branches:**
    ```bash
    git merge <Branch Name>
    ```
    Merges `<Branch Name>` into the current branch. Ensure you're on the branch you want to merge into.

---

### **Pull and Sync with Remote**

17. **Pull Changes from Remote:**
    ```bash
    git pull origin main
    ```
    Fetches and merges the latest changes from the `main` branch of the remote repository `origin` into your local branch.

---

### **Alternative to Merge:**
Use **Pull Requests** in platforms like GitHub for a more collaborative merging process.