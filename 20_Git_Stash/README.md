# Git Stash

## What is Git Stash?

`git stash` is used to **temporarily save changes**.

It saves our unfinished work without making a commit.

---

## Why Do We Use Git Stash?

We use `git stash` to:

* Save unfinished work.
* Switch to another branch.
* Do urgent work.
* Continue the work later.

---

## Syntax

```bash
git stash
```

---

## Example

Save changes:

```bash
git stash
```

Get changes back:

```bash
git stash pop
```

---

## Basic Flow

```text
Working Changes
       ↓
   git stash
       ↓
 Temporary Storage
       ↓
 git stash pop
       ↓
Working Changes
```

---

## Important Point

**Git Stash = Temporary Save**

**Git Commit = Permanent Save**

---

## Interview Question

### What is git stash?

**Answer:**

`git stash` is used to temporarily save uncommitted changes.

---

## Key Points

* `git stash` temporarily saves changes.
* It does not create a commit.
* `git stash pop` restores changes.
* Useful for unfinished work.
