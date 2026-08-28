# Git Rm

## What is Git Rm?

`git rm` is a Git command used to remove a file from the Working Directory and the Staging Area.

---

## Why Do We Use Git Rm?

We use `git rm` when we want to remove a tracked file from the Git repository.

---

## Syntax

git rm <file-name>

---

## Example

Suppose we have a tracked file:

test.txt

To remove the file, use:

git rm test.txt

The file is removed from the Working Directory and the removal is staged automatically.

---

## Basic Flow

    Tracked File
          ↓
      git rm
          ↓
    File Removed
          ↓
    Staging Area
          ↓
      git commit
          ↓
      Repository

---

## Git Rm vs Git Restore

### git rm

Removes a tracked file and stages the removal.

### git restore

Restores a file or removes it from the Staging Area.

---

## Important Point

`git rm` removes the file from the Working Directory and stages the removal.

The removal becomes part of the repository history after `git commit`.

---

## Interview Questions

### 1. What is git rm?

Answer:

`git rm` is used to remove a tracked file from the Working Directory and Staging Area.

### 2. Does git rm stage the removal?

Answer:

Yes. `git rm` automatically stages the file removal.

### 3. What happens after git rm?

Answer:

The file is removed from the Working Directory and the removal is added to the Staging Area.

---

## Key Points

- `git rm` removes a tracked file.
- It removes the file from the Working Directory.
- It automatically stages the removal.
- The removal is saved in repository history after `git commit`.