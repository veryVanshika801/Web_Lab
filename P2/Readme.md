
# P2 – Portfolio Repository with an Initial Commit

## Aim

To create a Git repository for a portfolio project and save the first commit.

## Commands

Run these commands inside a new portfolio project folder:

```bash
git init
git status
git add .
git commit -m "Initial commit"

git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of your GitHub repository.

## Description

- `git init` creates a new local Git repository.
- `git status` shows the current status of the project files.
- `git add .` adds all project files to the staging area.
- `git commit -m "Initial commit"` saves the changes as the first commit.
- `git branch -M main` changes the branch name to main.
- `git remote add origin` connects the local repository with GitHub.
- `git push -u origin main` uploads the project files to GitHub.

## Result

A Git repository was successfully created for the portfolio project. The initial commit was saved and the project was uploaded to GitHub.
