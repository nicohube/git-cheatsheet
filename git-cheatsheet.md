# Git Cheatsheet

## Configuring Git

- `git config --global user.name "Your Name"`: Set your global username.
- `git config --global user.email "your@example.com"`: Set your global email address.
- `git config --list`: List your Git configuration.

## Creating a Repository

- `git init`: Initialize a new Git repository.
- `git clone <repository_url>`: Clone a remote repository to your local machine.

## Basic Workflow

- `git status`: Check the status of your repository.
- `git add <file>`: Add a file or changes to the staging area.
- `git commit -m "Commit message"`: Commit the staged changes.
- `git push`: Push committed changes to a remote repository.
- `git pull`: Pull and merge changes from a remote repository.
- `git log`: View commit history.

## Branching and Merging

- `git branch`: List branches in the repository.
- `git branch <branch_name>`: Create a new branch.
- `git checkout <branch_name>`: Switch to a different branch.
- `git merge <branch_name>`: Merge a branch into the current branch.
- `git branch -d <branch_name>`: Delete a branch.

## Collaboration

- `git remote add <name> <repository_url>`: Add a remote repository.
- `git remote -v`: List remote repositories.
- `git fetch <remote_name>`: Fetch changes from a remote repository.
- `git pull <remote_name> <branch_name>`: Pull changes from a remote repository.
- `git push <remote_name> <branch_name>`: Push changes to a remote repository.

## Undoing Changes

- `git checkout -- <file>`: Discard changes in a file.
- `git reset HEAD <file>`: Unstage changes in a file.
- `git revert <commit_id>`: Create a new commit that undoes the specified commit.

## Miscellaneous

- `git diff`: Show changes between commits, branches, or files.
- `git stash`: Stash changes for later use.
- `git tag <tag_name>`: Create a new tag for a specific commit.
