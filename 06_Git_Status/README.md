# Git Status

## What is Git Status?

`git status` is a Git command used to check the current state of files in a Git repository.

---

## Why Do We Use Git Status?

We use `git status` to check:

- New files
- Modified files
- Staged files
- Changes ready for commit
- Whether the working tree is clean

---

## Syntax

git status

---

## Untracked File

When we create a new file, Git shows it as untracked.

Example:

git status

Output:

Untracked files:
    README.md

To track the file:

git add README.md

---

## Modified File

When we modify a tracked file:

git status

Git shows:

Changes not staged for commit:
    modified: README.md

This means the file is modified but not staged.

---

## Staged File

After:

git add README.md

Git shows:

Changes to be committed:
    modified: README.md

This means the changes are ready to commit.

---

## Clean Working Tree

After committing all changes:

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

## Interview Questions

### 1. What is git status?

Answer:

`git status` is used to check the current state of files in a Git repository.

### 2. What is an untracked file?

Answer:

An untracked file is a new file that Git is not tracking yet.

### 3. What does "working tree clean" mean?

Answer:

It means there are no changes to commit.

---

## Key Points

- `git status` shows the current state of the repository.
- It shows untracked files.
- It shows modified files.
- It shows staged files.
- It shows whether the working tree is clean.