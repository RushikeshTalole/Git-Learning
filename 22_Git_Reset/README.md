# Git Reset

## What is Git Reset?

`git reset` is used to **undo changes or move back to a previous commit**.

## Why Do We Use Git Reset?

* To unstage changes.
* To undo a commit.
* To go back to a previous commit.

## Syntax

```bash
git reset
```

## Example

```bash
git reset
```

This removes files from the **Staging Area** but keeps the changes in the **Working Directory**.

## Basic Flow

```text
Working Directory
       ↓
   git add .
       ↓
 Staging Area
       ↓
  git reset
       ↓
Working Directory
```

## Important Point

**Git Reset = Undo / Move Back**

### Common Commands

```bash
git reset
```

Unstage changes.

```bash
git reset --soft HEAD~1
```

Undo the last commit but keep changes staged.

```bash
git reset --hard HEAD~1
```

Undo the last commit and remove the changes.

 `--hard` should be used carefully because it can permanently remove changes.

## Interview Question

### What is git reset?

**Answer:**

`git reset` is used to unstage changes or move the current branch to a previous commit.

## Key Point

**`git reset` can undo commits or unstage changes.**
