---
layout: page
title: Git Cheat Sheet
description: Git is essential for effective and efficient version control, collaboration, and management of software development and docs-as-code projects.
img: assets/img/git3.jpg
importance: 3
category: code
---

1. Git Branching:

    To create a new branch and switch to it:

    ```
    git checkout -b feature-branch
    ```
    
    To list all branches:

    ```
    git branch
    ```
    
    To switch to a different branch:

    ```
    git checkout master
    ```
    
    To delete a branch:

    ```
    git branch -d feature-branch
    ```

2. Git Rebase:

    To rebase your current branch onto the master branch:

    ```
    git checkout feature-branch
    git rebase master
    ```
    To abort a rebase:

    ```
    git rebase --abort
    ```

3. Git Submodules:

    To add a Git submodule to your repository:

    ```
    git submodule add <repository_url> <directory>
    ```

    To clone a repository that contains submodules:

    ```
    git clone --recursive <repository_url>
    ```
4. Git Hooks:

    To create a pre-commit hook that runs a script before each commit:

    ```
    touch .git/hooks/pre-commit
    chmod +x .git/hooks/pre-commit
    ```
    Edit the `pre-commit` file with your script.

5. Git Stash:

    To temporarily save changes in a stash:

    ```
    git stash save "Work in progress"
    ```
    To apply a stash:

    ```
    git stash apply
    ```

    Git Bisect:
    To start a bisect:

    ```
    git bisect start
    ```
    To mark a commit as good:

    ```
    git bisect good
    ```

    To mark a commit as bad:

    ```
    git bisect bad
    ```

7. Git Cherry-pick:

    To apply a commit from another branch:

    ```
    git cherry-pick <commit>
```

For more commands refer to the [Git documentaion](https://git-scm.com/doc) 
