# Git-Github

This project serves as a learning exercise and practical demonstration of Git and GitHub functionality. It includes a series of tasks designed to help users become familiar with Git's essential features and best practices.

## Task 1: Clone the Git Repo

In this task, users are instructed to clone the Git repository hosted on GitHub. Cloning a repository is one of the fundamental steps in collaborating with Git, and it provides a starting point for the subsequent tasks.

### Steps

- Choose a working directory
- Inside the directory; type the command ```git clone git@github.com:VeeSprout/Git-Github.git```
- ```cd``` into the newly cloned repo.

## Task 2: Fix the Bug

The second task involves creating a new branch named "use-your full name" based on the latest version of the "main" branch. Users are then asked to fix a critical bug within this branch. To address the bug, they need to replace placeholder values in the mine.py file with their full name and email address. This task introduces users to branch creation, code editing, commits, and pushing branches to the GitHub repository.

### Steps-

- Create a new branch named "use-your full name" based on the latest version of the "main" branch
  
  ```bash
    git checkout -b use-your full name main
    ```

- Open the mine.py file in the "use-your full name" branch.
  
    ```bash
        code mine.py
        ```

- Locate the code section with the name and email fields.
- Replace the placeholder values with your full name and email address.
- Commit and push the changes to your "use-your full name" branch on GitHub.

### Bug Resolution

To fix this bug, the following steps were taken:

1. Opened the `mine.py` file in the "use-your full name" branch.
2. Located the code section with the name and email fields.
3. Replaced the placeholder values with my full name and email address.

### Before Bug Fix

```python
name = "PUT YOUR NAME"
email = "PUT YOUR EMAIL"
```

### After Bug Fix

```python
name = "Your Full Name"
email = "your.email@example.com"
```

Commit and Push Changes: Save the changes to your README.md file, and then commit them with a meaningful commit message, like "Update README.md with bug fix documentation." Push the changes to your "use-your full name" branch on GitHub.

Upload a Screenshot of Your Commit: Take a screenshot of your commit that shows your name and email. You can use a screenshot tool or press the "Print Screen" key to capture it. Upload the screenshot to an image hosting service (e.g., Imgur) and include a link in your README.md.
