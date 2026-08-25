# Git Log

## What is Git Log?

`git log` is a Git command used to view the commit history of a Git repository.

---

## Why Do We Use Git Log?

We use `git log` to see:

- Previous commits.
- Commit IDs.
- Commit messages.
- Author information.
- Commit dates.

---

## Syntax

git log

---

## Example

Run:

git log

Git shows information about previous commits.

Example:

commit 5ebad09
Author: Rushikesh Talole
Date: ...

    Add Git Status notes

Each commit has a unique commit ID.

---

## Commit ID

A commit ID is a unique identifier assigned to a commit.

Example:

5ebad09

We can use the commit ID to identify a specific commit.

---

## View Short Commit History

We can use:

git log --oneline

This shows commits in a shorter format.

Example:

5ebad09 Add Git Status notes
adca0fd Fix Working Directory README formatting
4445e9b Add Git Init notes

---

## Important Point

`git log` only shows the commit history.

It does not create, modify, or delete commits.

---

## Interview Questions

### 1. What is git log?

Answer:

`git log` is used to view the commit history of a Git repository.

### 2. What information does git log show?

Answer:

It shows information such as commit ID, author, date, and commit message.

### 3. What is the use of git log --oneline?

Answer:

`git log --oneline` shows the commit history in a short and compact format.

---

## Key Points

- `git log` shows commit history.
- It shows commit ID and commit message.
- It also shows author and date information.
- `git log --oneline` shows a short commit history.
