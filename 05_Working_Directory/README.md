# Working Directory

## What is Working Directory?

The Working Directory is the folder on our computer where we create, modify, delete, and manage project files.

It is also called the working tree.

---

## Example

Suppose our Git repository contains:

Git-Learning
│
├── README.md
├── 01_Git_Introduction
├── 02_Git_Installation
└── 05_Working_Directory

The `Git-Learning` folder is the working directory of the repository.

---

## What Can We Do in the Working Directory?

In the Working Directory, we can:

- Create new files.
- Modify existing files.
- Delete files.
- Rename files.
- View project files.

Git detects these changes when we use:

git status

---

## Working Directory and Git

When we modify a file, the change initially exists in the Working Directory.

The change is not automatically staged.

To move the change to the Staging Area, we use:

git add <file-name>

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

## Example

Suppose we create:

Main.java

Initially, the file is in the Working Directory.

After:

git add Main.java

The file is added to the Staging Area.

After:

git commit -m "Add Main program"

The staged change becomes part of the repository history.

---

## Check Working Directory Status

We can use:

git status

It shows the current state of files in the Working Directory and Staging Area.

---

## Important Points

- Working Directory is where we work with project files.
- We can create, modify, delete, and rename files here.
- Changes in the Working Directory are not automatically staged.
- `git status` shows the current state of the Working Directory.
- `git add` moves changes from the Working Directory to the Staging Area.
- `git commit` saves staged changes into repository history.

---

## Interview Questions

### 1. What is a Working Directory?

Answer:

The Working Directory is the folder on our computer where we create and modify files of a Git project.

### 2. Are Working Directory changes automatically staged?

Answer:

No. We need to use `git add` to move changes from the Working Directory to the Staging Area.

### 3. Which command shows the status of the Working Directory?

Answer:

`git status` shows the current state of files in the Working Directory and Staging Area.

### 4. What happens when we modify a tracked file?

Answer:

The modification first exists in the Working Directory. We need to use `git add` to stage the modification.

---

## Key Points

- Working Directory = Place where we work on project files.
- `git status` = Check current state.
- `git add` = Move changes to Staging Area.
- `git commit` = Save staged changes into repository history.