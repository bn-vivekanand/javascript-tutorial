# Git and JavaScript Learning Guide

This repository contains my learnings and commonly used commands for Git version control, with a focus on JavaScript development.

## Git Basics

### Checking Status and Making Changes

1. Check the status of your repository:
   ```
   git status
   ```

2. Add files to staging:
   - Add a specific file:
     ```
     git add FILE_NAME
     ```
   - Add all changed files:
     ```
     git add .
     ```

3. Commit your changes:
   ```
   git commit -m "Your descriptive commit message"
   ```

4. Push changes to remote repository:
   - Push to the current branch:
     ```
     git push
     ```
   - Push to a specific branch:
     ```
     git push origin BRANCH_NAME
     ```

### Branch Management

5. Create and switch to a new branch:
   ```
   git checkout -b NEW_BRANCH_NAME
   ```

6. Switch to an existing branch:
   ```
   git checkout BRANCH_NAME
   ```

7. List all branches:
   ```
   git branch
   ```

8. Delete a branch (locally):
   ```
   git branch -d BRANCH_NAME
   ```

### Advanced Git Commands

9. View commit history:
   ```
   git log
   ```

10. Fetch latest changes from remote without merging:
    ```
    git fetch
    ```

11. Pull latest changes and merge into current branch:
    ```
    git pull
    ```

12. Merge another branch into current branch:
    ```
    git merge BRANCH_NAME
    ```

13. Stash changes temporarily:
    ```
    git stash
    ```

14. Apply stashed changes:
    ```
    git stash pop
    ```

15. Rebase current branch onto another:
    ```
    git rebase BRANCH_NAME
    ```

## JavaScript Development Tips

- Always use semicolons at the end of statements.
- Follow a consistent coding style (e.g., Airbnb JavaScript Style Guide).
- Use `const` for variables that won't be reassigned, and `let` for those that will.
- Utilize modern ES6+ features like arrow functions, template literals, and destructuring.
- Implement proper error handling using try-catch blocks.
- Write clear, descriptive variable and function names.
- Comment your code, but focus on writing self-documenting code where possible.
- Use version control (Git) consistently throughout your development process.

## Useful Resources

- [Official Git Documentation](https://git-scm.com/doc)
- [JavaScript MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Node.js Official Website](https://nodejs.org/)

Remember to regularly update this README as you learn new concepts and techniques in both Git and JavaScript development.
