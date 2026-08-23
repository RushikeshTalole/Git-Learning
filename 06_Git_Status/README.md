# Git Status

## What is Git Status?

`git status` is a Git command used to check the current state of files in a Git repository.

---

## Why Do We Use Git Status?

We use `git status` to check:

- Untracked files
- Modified files
- Staged files
- Changes ready for commit
- Whether the working tree is clean

---

## Syntax

git status

---

## Untracked File

When we create a new file, Git shows it as an untracked file.

Example:

git status

Output:

Untracked files:
    README.md

This means Git is not tracking the file yet.

To track the file:

git add README.md

---

## Modified File

When we modify a tracked file, Git shows:

Changes not staged for commit:
    modified: README.md

This means the file is modified, but the changes are not staged yet.

To stage the changes:

git add README.md

---

## Staged File

After using:

git add README.md

Git shows:

Changes to be committed:
    modified: README.md

This means the changes are in the Staging Area and are ready to commit.

---

## Clean Working Tree

After committing all changes:

git commit -m "Update README"

Then:

git status

Output:

nothing to commit, working tree clean

This means there are no changes to commit.

---

## Basic Flow

Working Directory
        ↓
git status
        ↓
git add
        ↓
Staging Area
        ↓
git commit
        ↓
Repository

---

## Important Git Status States

### 1. Untracked

A new file that Git is not tracking.

### 2. Modified

A tracked file has been changed but the changes are not staged.

### 3. Staged

Changes have been added to the Staging Area and are ready to commit.

### 4. Clean

There are no changes to commit.

---

## Interview Questions

### 1. What is git status?

Answer:

`git status` is used to check the current state of files in a Git repository.

### 2. What is an untracked file?

Answer:

An untracked file is a new file that Git is not tracking yet.

### 3. What does "Changes not staged for commit" mean?

Answer:

It means a tracked file has been modified, but the changes have not been added to the Staging Area.

### 4. What does "Changes to be committed" mean?

Answer:

It means the changes are in the Staging Area and are ready to be committed.

### 5. What does "working tree clean" mean?

Answer:

It means there are no changes waiting to be committed.

---

## Key Points

- `git status` shows the current state of the repository.
- It shows untracked files.
- It shows modified files.
- It shows staged files.
- It shows whether the working tree is clean.
- It is commonly used before `git add` and `git commit`.