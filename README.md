
# GIT COMMANDS CHEAT SHEET

## Configure Git Settings

- Set configuration values for your username and email:
  ```bash
  git config --global user.name "YOUR NAME"
  git config --global user.email "YOUR EMAIL"
  ```
- Set default branch to main:
  ```bash
  git config --global init.defaultBranch main
  ```

## Get Help

- Get help on a command:
  ```bash
  git help COMMAND
  git COMMAND -h
  ```

## Initialize and Clone Repositories

- Initialize a new git repository:
  ```bash
  git init
  ```
- Clone a repository:
  ```bash
  git clone REPOSITORY_URL
  ```

## Staging and Committing Changes

- Add a file to the staging area:
  ```bash
  git add FILE
  ```
- Add all file changes to the staging area:
  ```bash
  git add --all
  git add -A
  git add .
  ```
- Check the unstaged changes:
  ```bash
  git diff
  ```
- Commit the staged changes:
  ```bash
  git commit -m "MESSAGE"
  ```
- Reset staging area to the last commit:
  ```bash
  git reset
  ```
- Check the state of the working directory and the staging area:
  ```bash
  git status
  ```

## File Management

- Remove a file from the index and working directory:
  ```bash
  git rm FILENAME
  ```
- Rename a file:
  ```bash
  git mv OLD_NAME NEW_NAME
  ```

## Viewing History and Logs

- List the commit history:
  ```bash
  git log
  ```

## Branch Management

- List all the local branches:
  ```bash
  git branch
  ```
- Create a new branch:
  ```bash
  git branch BRANCH_NAME
  ```
- Rename the current branch:
  ```bash
  git branch -m NEW_BRANCH_NAME
  ```
- Delete a branch:
  ```bash
  git branch -d BRANCH_NAME
  ```
- Switch to another branch:
  ```bash
  git switch BRANCH_NAME
  ```
- Merge a specified branch into the current branch:
  ```bash
  git merge BRANCH_NAME
  ```

## Remote Repository Management

- Create a connection to a remote repository:
  ```bash
  git remote add NAME REPOSITORY_URL
  ```
- Push the committed changes to a remote repository:
  ```bash
  git push REMOTE BRANCH
  ```
- Download content from a remote repository:
  ```bash
  git pull REMOTE
  ```

