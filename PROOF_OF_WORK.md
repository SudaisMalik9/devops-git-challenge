# Proof of Work — DevOps Git Challenge

## Repository

* GitHub: https://github.com/SudaisMalik9/devops-git-challenge
* Branches: main, development, staging

## Tasks Completed

* Configured Git identity.
* Created deploy.sh and README.md.
* Committed and pushed the initial version.
* Created the development branch and updated the deployment environment.
* Used git stash and git stash pop.
* Created the staging branch and committed a conflicting change.
* Merged staging into development and resolved the merge conflict.
* Pushed development and staging to GitHub.
* Merged the development Pull Request into main.
* Pulled the updated main branch.

## Git Commit History

PS C:\\Users\\shapa\\devops-git-challenge> git log --oneline --graph --all

\*   2bb1559 (HEAD -> main, origin/main) Merge pull request #1 from SudaisMalik9/development

|\\

| \*   134de66 (origin/development, development) fix: resolved merge conflict

| |\\

| | \* 9c703c7 (origin/staging, staging) fix: staging label

| |/

|/|

| \* ad839c3 feat: updated script with staging env

|/

\* 565999a feat: initial commit with deploy script

## Reflection Questions

### 1\. What is the difference between Git and GitHub?

Git is a version control system that tracks file changes and commits locally. GitHub is an online platform for hosting Git repositories and collaborating with others.

### 2\. What are the Working Directory, Staging Area, and Local Repository?

* Working Directory: Where project files are edited.
* Staging Area: Where selected changes are prepared using git add.
* Local Repository: Where commits and project history are stored.

### 3\. What is the difference between git stash pop and git stash apply?

git stash pop restores stashed changes and removes the stash entry after successful application. git stash apply restores the changes but keeps the stash entry.

### 4\. What is the difference between git fetch and git pull?

git fetch downloads remote updates without integrating them into the current branch. git pull downloads remote updates and integrates them into the current branch, usually by merging or rebasing.

## Conclusion

This activity provided practical experience with branching, committing, stashing, resolving merge conflicts, pushing branches, and using GitHub Pull Requests.

