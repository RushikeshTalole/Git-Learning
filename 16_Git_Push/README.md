# Git Push

## What is Git Push?

`git push` is a Git command used to upload local commits to a remote repository.

---

## Why Do We Use Git Push?

We use `git push` to send our committed changes from the local repository to a remote repository such as GitHub.

---

## Syntax

git push

---

## Example

Suppose we have committed our changes:

git commit -m "Add new notes"

To upload the commit to GitHub, use:

git push

The committed changes are sent to the remote repository.

---

## Basic Flow

    Working Directory
          ↓
       git add
          ↓
    Staging Area
          ↓
      git commit
          ↓
    Local Repository
          ↓
       git push
          ↓
    Remote Repository
          ↓
        GitHub

---

## Important Point

`git push` uploads committed changes to the remote repository.

Changes must be committed before they can be pushed.

---

## Example

Check the status:

git status

Stage the changes:

git add README.md

Create a commit:

git commit -m "Add Git Push notes"

Push the commit:

git push

---

## Interview Questions

### 1. What is git push?

Answer:

`git push` is used to upload local commits to a remote repository.

### 2. Where does git push send the commits?

Answer:

It sends the commits from the local repository to a remote repository such as GitHub.

### 3. Can we push changes without committing them?

Answer:

No. Changes should be committed before using `git push`.

---

## Key Points

- `git push` uploads commits to a remote repository.
- It is commonly used to upload changes to GitHub.
- Changes should be committed before pushing.
- `git push` sends local commits to the remote repository.