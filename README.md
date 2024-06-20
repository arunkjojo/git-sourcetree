# Git and Sourcetree

This is a basic guide to using Git and Sourcetree for version control.

## Git Basics

### Branch Management

- **Creating a new branch:**

  ```git
    git checkout -b <branch-name>
  ```

  This command creates and checks out a new branch from the current branch.

- **Listing branches:**

  ```git
    git branch
  ```

  Lists all local branches.

- **Deleting a branch:**
  ```git
    git branch -d <branch-name>
  ```
  Deletes a local branch. Use -D to force delete if the branch hasn't been merged.

### Merging Branches

- **Merging a branch into the current branch:**

  ```git
    git checkout <target-branch>
  ```

  ```git
    git merge <source-branch>
  ```

  First, switch to the target branch, then merge the source branch into it.

- **Handling merge conflicts:**
  ```git
    git add <resolved-file>
  ```
  ```git
    git commit
  ```
  When conflicts occur during a merge, Git will pause and allow you to manually resolve the conflicts. Use the command to proceed after resolving conflicts

### Pulling and Fetching

- **Pulling changes from the remote repository:**

  ```git
    git pull origin <branch-name>
  ```

  This command fetches and integrates changes from the specified branch of the remote repository.

- **Fetching changes from the remote repository:**
  ```git
    git fetch origin
  ```
  This command fetches changes from the remote repository but does not merge them. Use this when you want to review changes before integrating.

### Rebasing

- **Rebasing a branch:**

  ```git
    git checkout <feature-branch>
  ```

  ```git
    git rebase <base-branch>
  ```

  Rebasing moves or combines a sequence of commits to a new base commit. This is useful for keeping a clean project history.

- **Interactive rebase:**
  ```git
    git rebase -i <base-commit>
  ```
  Interactive rebase allows you to edit, reorder, and squash commits.
