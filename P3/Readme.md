
# P3 – Feature Branch Git Workflow

## Aim

To create a new feature branch, make a small change, and push the branch to GitHub.

## Commands

Run these commands from the project repository:

```bash
git switch -c feature/my-change
git status
git add .
git commit -m "Add a portfolio change"
git push -u origin feature/my-change
```

## Description

- `git switch -c feature/my-change` creates a new branch and switches to it.
- `git status` displays the current changes in the project.
- `git add .` stages all modified and new files.
- `git commit -m "Add a portfolio change"` saves the changes in the new branch.
- `git push -u origin feature/my-change` uploads the feature branch to GitHub.

## Result

A new feature branch was successfully created. Changes were committed and the branch was pushed to the remote GitHub repository.
