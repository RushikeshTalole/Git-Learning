# Git Diff

## What is Git Diff?

`git diff` is a Git command used to see the changes made in the Working Directory.

---

## Why Do We Use Git Diff?

We use `git diff` to check what changes have been made to a file before staging them.

---

## Syntax

git diff

---

## Example

Suppose we have a tracked file:

README.md

We modify the file.

Before staging the changes, we can use:

git diff

Git shows the changes made in the Working Directory.

---

## What Does Git Diff Show?

`git diff` can show:

- Added lines.
- Removed lines.
- Modified lines.

It helps us review changes before using `git add`.

---

## Basic Flow

    Working Directory
            ↓
        git diff
            ↓
      Review Changes
            ↓
         git add
            ↓
      Staging Area

---

## Git Diff and Staging Area

`git diff` shows changes that are in the Working Directory but are not staged yet.

For staged changes, we use:

git diff --staged

---

## Difference Between git diff and git diff --staged

### git diff

Shows unstaged changes in the Working Directory.

### git diff --staged

Shows changes that are already in the Staging Area.

---

## Important Point

`git diff` does not modify the file.

It only shows the differences between the current file and the last committed version.

---

## Interview Questions

### 1. What is git diff?

Answer:

`git diff` is used to see changes made in the Working Directory that have not been staged yet.

### 2. Does git diff modify files?

Answer:

No. `git diff` only shows the differences.

### 3. What is the difference between git diff and git diff --staged?

Answer:

`git diff` shows unstaged changes, while `git diff --staged` shows staged changes.

---

## Key Points

- `git diff` shows unstaged changes.
- It helps us review changes before staging.
- `git diff --staged` shows staged changes.
- `git diff` does not modify files.