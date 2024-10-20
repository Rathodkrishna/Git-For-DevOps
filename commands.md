# Git Command Cheat Sheet

## Basic Commands
- `git init`: Initialize a new Git repository.
- `git clone [url]`: Clone an existing repository from a URL.
- `git status`: Check the status of your working directory.
- `git add [file]`: Add a file to the staging area.
- `git commit -m "[message]"`: Commit changes to the repository with a message.
- `git log`: View the commit history.
- `git diff`: Show changes between commits, commit and working tree, etc.

## Branching & Merging
- `git branch`: List all branches in the repository.
- `git branch [branch-name]`: Create a new branch.
- `git checkout [branch-name]`: Switch to a specified branch.
- `git merge [branch-name]`: Merge a specified branch into the current branch.
- `git branch -d [branch-name]`: Delete a branch.

## Remote Repositories
- `git remote -v`: View the remote repositories.
- `git remote add [name] [url]`: Add a new remote repository.
- `git fetch [remote]`: Fetch changes from the remote repository.
- `git pull [remote] [branch]`: Fetch and merge changes from the remote branch.
- `git push [remote] [branch]`: Push local changes to the remote repository.

## Stashing Changes
- `git stash`: Stash the changes in the working directory.
- `git stash pop`: Apply the stashed changes and remove them from the stash.
- `git stash list`: List all stashed changes.

## Undoing Changes
- `git checkout -- [file]`: Discard changes in the working directory.
- `git reset [file]`: Unstage a staged file.
- `git reset --hard`: Reset the working directory and index to the last commit (losing changes).

## Tags
- `git tag`: List all tags.
- `git tag [tag-name]`: Create a new tag.
- `git push [remote] [tag-name]`: Push a tag to a remote repository.

## Other Useful Commands
- `git config --global user.name "[name]"`: Set the Git username.
- `git config --global user.email "[email]"`: Set the Git email address.
- `git rm [file]`: Remove a file from the working directory and stage the removal.

