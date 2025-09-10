# 🛠️ Daily Git Commands with Definitions

Here’s a list of the most commonly used Git commands in daily development, along with their definitions and examples.

---

## 1. `git init`
- Initializes a new Git repository in the current folder.
- Creates a hidden `.git` directory where Git stores all tracking info.

---

## 2. `git clone <repo-url>`
- Copies (clones) an existing remote repository to your local machine.
- Example:  
  ```bash
  git clone https://github.com/user/project.git
  ```

---

## 3. `git status`
- Shows the current state of your working directory.
- Tells you which files are:
  - Modified but not staged
  - Staged for commit
  - Untracked (not under Git yet)

---

## 4. `git add <file>` / `git add .`
- Moves changes from your working directory into the staging area (ready to commit).
- Example:  
  ```bash
  git add file1.txt      # Add specific file
  git add .              # Add all changed files
  ```

---

## 5. `git commit -m "message"`
- Saves (commits) the staged changes into the repository history with a message.
- Example:  
  ```bash
  git commit -m "Fixed login bug"
  ```

---

## 6. `git log`
- Shows the commit history with commit IDs, messages, and authors.
- Useful for checking what happened in the project.

---

## 7. `git diff`
- Shows the exact changes (line by line) that were made but not yet staged or committed.

---

## 8. `git branch`
- Lists all branches in the repo.
- Example:  
  ```bash
  git branch feature-login   # Create a new branch
  ```

---

## 9. `git checkout <branch>` (or `git switch <branch>`)
- Moves you to another branch.
- Example:  
  ```bash
  git checkout main
  git switch feature-login
  ```

---

## 10. `git merge <branch>`
- Combines changes from another branch into the current branch.
- Example:  
  ```bash
  git merge feature-login
  ```

---

## 11. `git pull`
- Fetches changes from the remote repository and merges them into your local branch.
- Equivalent to:  
  ```bash
  git fetch + git merge
  ```

---

## 12. `git push`
- Uploads your local commits to the remote repository.
- Example:  
  ```bash
  git push origin main
  ```

---

## 13. `git fetch`
- Downloads commits, files, and refs from a remote repository *without merging*.
- Lets you review changes before integrating.

---

## 14. `git reset`
- Unstages files or moves back to a previous commit.
- Example:  
  ```bash
  git reset file.txt       # Remove file from staging area
  git reset --hard HEAD~1  # Reset to previous commit, losing changes
  ```

---

## 15. `git stash`
- Temporarily saves your uncommitted changes so you can work on something else.
- Example:  
  ```bash
  git stash        # Save changes
  git stash pop    # Apply them back
  ```

---

👉 These are the **daily driver Git commands** most developers use.
