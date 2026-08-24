# Git Commit

## What is Git Commit?

`git commit` is a Git command used to save staged changes into the repository history.

---

## Why Do We Use Git Commit?

We use `git commit` to permanently save the changes that are currently in the Staging Area.

---

## Syntax

git commit -m "commit message"

---

## Example

Suppose we have a file:

README.md

First, add the file to the Staging Area:

git add README.md

Then create a commit:

git commit -m "Add README file"

The staged changes are now saved in the repository history.

---

## Commit Message

A commit message describes what changes were made.

Example:

git commit -m "Add Git Commit notes"

A good commit message should be short and meaningful.

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
Repository

---

## Check Commit Status

After committing, use:

git status

If there are no remaining changes, Git shows:

nothing to commit, working tree clean

---

## Important Point

`git commit` only commits changes that are already in the Staging Area.

Changes that are only in the Working Directory are not included until they are staged using `git add`.

---

## Interview Questions

### 1. What is git commit?

Answer:

`git commit` is used to save staged changes into the repository history.

### 2. Why do we use a commit message?

Answer:

A commit message describes the changes included in the commit.

### 3. Does git commit automatically stage changes?

Answer:

No. Normally, we use `git add` to stage changes before creating a commit.

### 4. Which command is used to create a commit?

Answer:

`git commit -m "message"`

---

## Key Points

- `git commit` saves staged changes into repository history.
- `git add` is normally used before `git commit`.
- A commit should have a meaningful message.
- `git status` can be used to check the current state.