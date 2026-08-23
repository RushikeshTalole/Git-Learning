.# Git Add

## What is Git Add?

`git add` is a Git command used to move changes from the Working Directory to the Staging Area.

---

## Why Do We Use Git Add?

We use `git add` to select the changes that we want to include in the next commit.

---

## Syntax

git add <file-name>

---

## Example

Suppose we create a file:

README.md

Git shows the file as untracked.

To add the file to the Staging Area:

git add README.md

Now the file is staged and ready to be committed.

---

## Check Staged Changes

After using:

git add README.md

We can check the status using:

git status

It may show:

Changes to be committed:
    new file: README.md

This means the file is in the Staging Area.

---

## Git Add Flow

Working Directory
        ↓
    git add
        ↓
Staging Area
        ↓
   git commit
        ↓
Repository

---

## Important Point

`git add` does not create a commit.

It only moves the selected changes from the Working Directory to the Staging Area.

---

## Interview Questions

### 1. What is git add?

Answer:

`git add` is used to move changes from the Working Directory to the Staging Area.

### 2. Does git add create a commit?

Answer:

No. `git add` only stages the changes. `git commit` creates the commit.

### 3. Why do we use git add?

Answer:

We use `git add` to select changes that we want to include in the next commit.

---

## Key Points

- `git add` moves changes to the Staging Area.
- It is used before `git commit`.
- `git add` does not create a commit.
- `git status` can be used to check staged changes.
