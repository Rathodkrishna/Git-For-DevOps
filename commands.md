# Git Commands

## Commands Overview

### `git status`
Displays the current state of the working directory and staging area, including staged, unstaged, and untracked files.

### `git log`
Shows the commit history of the repository, listing all past commits.

### `git branch`
Lists all branches in the repository, highlighting the currently active branch.

### `git checkout <branch-name>`
Switches to the specified branch. For example, `git checkout main` switches to the "main" branch.

### `git head`
This command is not valid. You can use `git rev-parse --abbrev-ref HEAD` to see the current branch, or `git show HEAD` to see the latest commit on the current branch.

### `git head --oneline`
This command is not valid. Use `git log -1 --oneline` to see the most recent commit in a one-lined format.

### `git log --oneline`
Displays the commit history in a condensed format, showing each commit on one line.
