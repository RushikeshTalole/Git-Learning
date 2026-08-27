# Git Restore

## What is Git Restore?

`git restore` is a Git command used to restore files and remove unwanted changes.

---

## Why Do We Use Git Restore?

We use `git restore` to:

- Remove a file from the Staging Area.
- Discard changes from the Working Directory.

---

## 1. Remove File from Staging Area

Suppose we add a file using:

git add README.md

The file moves to the Staging Area.

To remove it from the Staging Area, use:

git restore --staged README.md

The changes remain in the Working Directory.

---

## Basic Flow

    Staging Area
          ↓
    git restore --staged
          ↓
    Working Directory

---

## 2. Discard Working Directory Changes

Suppose we modify a tracked file:

README.md

If we want to discard the changes, use:

git restore README.md

The file returns to its last committed version.

---

## Basic Flow

    Working Directory
          ↓
    git restore README.md
          ↓
    Last Committed Version

---

## Important Difference

### git restore --staged

Removes the file from the Staging Area but keeps the changes in the Working Directory.

### git restore

Discards the changes from the Working Directory.

---

## Example

Suppose we modify:

README.md

Then we use:

git restore README.md

The changes are discarded and the file returns to its last committed version.

---

## Interview Questions

### 1. What is git restore?

Answer:

`git restore` is used to restore files and remove unwanted changes.

### 2. How do you remove a file from the Staging Area?

Answer:

We use:

git restore --staged README.md

### 3. How do you discard Working Directory changes?

Answer:

We use:

git restore README.md

---

## Key Points

- `git restore` is used to restore files.
- `git restore --staged` removes a file from the Staging Area.
- `git restore README.md` discards Working Directory changes.
- `git restore --staged` keeps the changes in the Working Directory.