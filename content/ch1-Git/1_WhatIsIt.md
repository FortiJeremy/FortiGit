---
title: "Git"
chapter: true
weight: 1
---

## Chapter 1 - What is Git

### Git Summary

Git is a distributed version control system designed to help developers manage and collaborate on software projects. It was created by Linus Torvalds in 2005 and has since become one of the most widely used version control systems in the world. Git is open source software and is free to use, making it accessible to developers of all levels.

The core idea behind Git is to provide a way for developers to track changes made to a codebase over time, allowing multiple developers to work on the same project without interfering with each other. Git accomplishes this by creating a local repository on each developer's computer, which stores a complete copy of the codebase and all changes made to it.

One of the key features of Git is its ability to handle branching and merging. This allows developers to work on multiple independent lines of development simultaneously and merge changes back into the main codebase when they are ready. This makes it easy for developers to work on different features or bug fixes without interfering with each other's work.

Git also provides a number of other useful features, such as the ability to revert changes made to a codebase, track the history of changes, and collaborate with other developers using remote repositories hosted on services like GitHub or Bitbucket.

### The Three States of Git

Git has three main states that files can be in: the working directory, the staging area, and the repository.

    The working directory: This is the directory on your local machine where you make changes to your files.

    The staging area: This is an intermediate area where you can review and stage changes before committing them to the repository. Files in the staging area are not yet committed, but they are marked as being ready for commit.

    The repository: This is where Git permanently stores the committed changes to your files. The repository includes the entire history of changes made to the files.

### Moving Files Between States

Files can move between the three states in Git as follows:

    Working directory to staging area: You can add changes made to files in the working directory to the staging area using the git add command.

    Staging area to repository: Once you have reviewed and staged your changes, you can commit them to the repository using the git commit command. This permanently saves the changes to the repository.

    Repository to working directory: You can update the files in your working directory with the most recent changes from the repository using the git pull command.

### How Git Keeps Track of Changes

Git keeps track of changes to files using a system of snapshots. Each time you commit changes, Git takes a snapshot of the files in the repository at that point in time. When you view the history of commits, you can see the differences between each snapshot and how the files have changed over time.

Git uses a unique identifier called a SHA-1 hash to track each commit and ensure the integrity of the repository. This means that any changes to the repository are immediately detectable, and you can always trace back to the original commit that introduced a particular change.

Overall, understanding the three states of Git and how Git tracks changes to files is essential for effectively using Git for version control.
