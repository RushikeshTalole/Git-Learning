# GitIgnore

## What is GitIgnore?

`.gitignore` is a file used to tell Git which files and folders should be ignored.

---

## Why Do We Use GitIgnore?

We use `.gitignore` to prevent unnecessary files from being tracked by Git.

Examples:

- Temporary files.
- Log files.
- Build files.
- Files containing local settings.

---

## File Name

The file name is:

.gitignore

---

## Example

Suppose we have:

test.txt

If we do not want Git to track this file, add it to `.gitignore`:

test.txt

Now Git will ignore `test.txt`.

---

## Basic Flow

    File / Folder
          ↓
     .gitignore
          ↓
      Git ignores it
          ↓
    Not tracked by Git

---

## Example of .gitignore

A `.gitignore` file can contain:

*.log
*.tmp
test.txt

This tells Git to ignore `.log` files, `.tmp` files, and `test.txt`.

---

## Important Point

`.gitignore` prevents untracked files from being added to Git.

It does not remove a file that is already being tracked by Git.

---

## Interview Questions

### 1. What is .gitignore?

Answer:

`.gitignore` is a file used to tell Git which files and folders should be ignored.

### 2. Why do we use .gitignore?

Answer:

We use `.gitignore` to prevent unnecessary files from being tracked by Git.

### 3. What is the name of the ignore file?

Answer:

The file is named:

`.gitignore`

---

## Key Points

- `.gitignore` tells Git which files to ignore.
- It helps keep unnecessary files out of the repository.
- It can contain file names, extensions, and folders.
- It does not automatically remove already tracked files.