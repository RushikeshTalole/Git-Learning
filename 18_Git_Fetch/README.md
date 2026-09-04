# Git Fetch

## What is Git Fetch?

`git fetch` is a Git command used to **download the latest changes from a remote repository**.

It does not change our current working files.

---

## Why Do We Use Git Fetch?

We use `git fetch` to:

* Get the latest changes from GitHub.
* Check changes available in the remote repository.
* Keep our local repository updated.
* Review changes before applying them.

---

## Syntax

```bash
git fetch
```

---

## Example

Suppose another developer makes changes on GitHub.

We can use:

```bash
git fetch
```

Git gets the latest changes from the remote repository, but our current files are not automatically changed.

---

## Basic Flow

```text
    Remote Repository
           ↓
       git fetch
           ↓
    Local Repository
           ↓
     Check Changes
```

---

## Git Fetch vs Git Pull

### git fetch

`git fetch` gets the latest changes from the remote repository **without applying them to the current branch**.

### git pull

`git pull` gets the latest changes from the remote repository **and applies them to the current branch**.

---

## Simple Difference

| git fetch              | git pull                    |
| ---------------------- | --------------------------- |
| Gets remote changes    | Gets remote changes         |
| Does not apply changes | Applies changes             |
| Used to check changes  | Used to update local branch |

---

## Important Point

**Git Fetch = Get changes + Check them**

**Git Pull = Get changes + Apply them**

---

## Interview Questions

### 1. What is git fetch?

**Answer:**

`git fetch` is used to download the latest changes from a remote repository without applying them to the current branch.

### 2. What is the difference between git fetch and git pull?

**Answer:**

`git fetch` gets remote changes without applying them, while `git pull` gets and applies the changes to the current branch.

### 3. Does git fetch change our working files?

**Answer:**

No, `git fetch` does not automatically change our working files.

---

## Key Points

* `git fetch` gets changes from a remote repository.
* It does not apply changes to the current branch.
* It does not change our working files.
* It helps us check remote changes first.
* `git pull` gets and applies changes.
* Syntax: `git fetch`
