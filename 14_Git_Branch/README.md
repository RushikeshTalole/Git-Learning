# Git Branch

## What is Git Branch?

A branch in Git is a separate line of development.

It allows us to work on changes without affecting the main branch.

---

## Why Do We Use Git Branch?

We use branches to:

- Work on new features.
- Make changes separately.
- Keep the main branch safe.

---

## Check Current Branch

To see the current branch, use:

git branch

The branch with `*` is the current branch.

---

## Create a New Branch

To create a new branch:

git branch feature

This creates a new branch named `feature`.

---

## Switch to a Branch

To switch to another branch:

git checkout feature

Now we are working on the `feature` branch.

---

## Basic Flow

    Main Branch
         ↓
    Create Branch
         ↓
    Feature Branch
         ↓
    Work on Changes

---

## Example

Create a branch:

git branch feature

Switch to the branch:

git checkout feature

Now any new work can be done on the `feature` branch.

---

## Important Point

A branch allows us to work separately from the main branch.

The main branch is not affected by changes made on another branch until they are merged.

---

## Interview Questions

### 1. What is a Git branch?

Answer:

A Git branch is a separate line of development used to work on changes independently.

### 2. Why do we use branches?

Answer:

We use branches to work on new features or changes without directly affecting the main branch.

### 3. How do you create a branch?

Answer:

We use:

git branch branch-name

### 4. How do you switch to a branch?

Answer:

We use:

git checkout branch-name

---

## Key Points

- A branch is a separate line of development.
- Branches allow us to work independently.
- `git branch` shows available branches.
- `git branch feature` creates a new branch.
- `git checkout feature` switches to a branch.