# Git Clone

## What is Git Clone?

`git clone` is a Git command used to **copy a remote repository from GitHub to our local computer**.

---

## Why Do We Use Git Clone?

We use `git clone` to:

* Download a repository from GitHub.
* Create a local copy of the repository.
* Work on the project on our computer.
* Get the repository files and Git history.

---

## Syntax

```bash
git clone <repository-url>
```

---

## Example

```bash
git clone https://github.com/username/repository.git
```

This creates a local copy of the remote repository.

---

## Basic Flow

```text
    Remote Repository
           ↓
       git clone
           ↓
    Local Repository
```

---

## Git Clone vs Git Pull

### git clone

`git clone` is used to **create a new local copy** of a remote repository.

### git pull

`git pull` is used to **get the latest changes** in an already cloned local repository.

---

## Simple Difference

| git clone                      | git pull                             |
| ------------------------------ | ------------------------------------ |
| Creates a new local repository | Updates an existing local repository |
| Used for first-time download   | Used for latest changes              |
| Copies the repository          | Gets new changes                     |

---

## Important Point

**Git Clone = Remote Repository → New Local Repository**

---

## Interview Questions

### 1. What is git clone?

**Answer:**

`git clone` is used to create a local copy of a remote repository.

### 2. Why do we use git clone?

**Answer:**

We use `git clone` to download a remote repository from GitHub to our local computer.

### 3. What is the difference between git clone and git pull?

**Answer:**

`git clone` creates a new local copy of a repository, while `git pull` gets the latest changes in an existing local repository.

---

## Key Points

* `git clone` copies a remote repository.
* It creates a local repository.
* It is commonly used with GitHub.
* `git pull` is used to get latest changes.
* Syntax: `git clone <repository-url>`
