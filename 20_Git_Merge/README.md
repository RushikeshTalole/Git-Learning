# Git Merge

## What is Git Merge?

`git merge` is a Git command used to **combine changes from one branch into another branch**.

---

## Why Do We Use Git Merge?

We use `git merge` to:

* Combine changes from different branches.
* Bring feature branch changes into the main branch.
* Work on features separately and then combine them.

---

## Syntax

```bash
git merge <branch-name>
```

---

## Example

Suppose we have:

* `main` branch
* `feature` branch

First, switch to the branch where we want to add the changes:

```bash
git checkout main
```

Then merge the `feature` branch:

```bash
git merge feature
```

Now the changes from `feature` are combined into `main`.

---

## Basic Flow

```text
       Feature Branch
             ↓
        git merge
             ↓
        Main Branch
```

---

## Important Point

**Merge = Combine changes from one branch into another branch.**

The branch we are currently on is the branch that receives the changes.

---

## Example Flow

```bash
git checkout main
git merge feature
```

Here, the changes from `feature` are merged into `main`.

---

## Git Merge vs Git Branch

### git branch

`git branch` is used to **create and manage branches**.

### git merge

`git merge` is used to **combine changes from branches**.

---

## Interview Questions

### 1. What is git merge?

**Answer:**

`git merge` is used to combine changes from one branch into another branch.

### 2. Which branch receives the changes during merge?

**Answer:**

The branch on which we are currently working receives the changes.

### 3. Give an example of git merge.

**Answer:**

```bash
git checkout main
git merge feature
```

This merges the `feature` branch into the `main` branch.

---

## Key Points

* `git merge` combines branch changes.
* It is used to combine feature work with another branch.
* The current branch receives the changes.
* First switch to the target branch.
* Then run `git merge <branch-name>`.
