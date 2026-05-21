# Portfolio_Project

## Tools Installed

- Cursor IDE
- Claude Code Extension
- Codex Extension
- Git (installed from git-scm.com)
- GitHub (for hosting the repository)
- Claude AI (claude.ai) — used to ask questions and get guidance throughout the process

## Steps Completed

1. Installed Cursor IDE
2. Installed Claude Code extension in Cursor
3. Installed Codex extension in Cursor
4. Created a GitHub repository
5. Cloned the repository using Git via Command Prompt with the following command:
   ```
   git clone https://github.com/criswynvilla-ship-it/Portfolio_Project.git
   ```
6. Opened the repository in Cursor
7. Used Claude AI (claude.ai) to ask questions and get help when stuck
8. Created and edited the README.md file
9. Committed and pushed the repository to GitHub

## Issues Encountered

### Issue 1:
Git clone failed because the wrong GitHub URL was used.

### Solution:
Used the correct repository clone URL ending in `.git`

### Issue 2:
Received "Too many arguments" error in Git.

### Solution:
Removed the duplicate `git clone` command and used the correct syntax. Asked Claude AI for clarification on the correct Git syntax.

### Issue 3:
README.md edits made in Cursor were not appearing on GitHub after saving.

### Solution:
Learned that saving in Cursor only saves locally. Had to run `git add .`, `git commit`, and `git push` in Command Prompt to send changes to GitHub.

### Issue 4:
Received a fatal error: `unable to auto-detect email address` when trying to commit.

### Solution:
Configured Git identity using the following commands in Command Prompt:
```
git config --global user.email "youremail@example.com"
git config --global user.name "YourName"
```
Then successfully ran `git add .`, `git commit -m "Update README.md"`, and `git push`.

## Repository Link
https://github.com/criswynvilla-ship-it/Portfolio_Project.git