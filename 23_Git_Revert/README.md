# Git Revert

## What is Git Revert?

`git revert` is used to **undo the changes of a previous commit** without deleting the commit from history.

## Why Do We Use Git Revert?

* To safely undo a previous commit.
* To keep the Git history.
* Useful when changes are already pushed to GitHub.

## Syntax

```bash
git revert <commit-id>
```

## Example

```bash
git revert abc123
```

This creates a **new commit** that reverses the changes made by the selected commit.

## Basic Flow

```text
Previous Commit
       ↓
   git revert
       ↓
  New Commit
       ↓
Changes Undone
```

## Git Reset vs Git Revert

| Git Reset                              | Git Revert               |
| -------------------------------------- | ------------------------ |
| Moves back to a previous commit        | Creates a new commit     |
| Can remove commit from current history | Keeps existing history   |
| Use carefully                          | Safer for pushed commits |

## Important Point

**Git Revert = Undo changes by creating a new commit.**

## Interview Question

### What is git revert?

**Answer:**

`git revert` is used to undo the changes of a previous commit by creating a new commit.

## Key Point

**Reset → Move Back**

**Revert → Create New Commit to Undo**
