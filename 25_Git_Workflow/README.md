# GitHub Workflow

## What is GitHub Workflow?

GitHub Workflow is the **basic process of working with Git locally and uploading changes to GitHub**.

## Basic Workflow

```text
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
     GitHub
```

## Common Commands

### 1. Check Status

```bash
git status
```

Checks the current state of the repository.

### 2. Add Changes

```bash
git add .
```

Moves changes to the Staging Area.

### 3. Commit Changes

```bash
git commit -m "Add changes"
```

Saves changes in the local repository.

### 4. Push Changes

```bash
git push
```

Uploads committed changes to GitHub.

### 5. Get Latest Changes

```bash
git pull
```

Gets the latest changes from GitHub.

## Daily GitHub Workflow

```bash
git status
git add .
git status
git commit -m "Update project"
git push
```

## Important Point

**Git = Version Control**

**GitHub = Remote Platform**

**git push = Local Repository → GitHub**

**git pull = GitHub → Local Repository**

## Interview Question

### What is the basic GitHub workflow?

**Answer:**

The basic workflow is:

`git add` → `git commit` → `git push`

It moves changes from the Working Directory to the Staging Area, then to the Local Repository, and finally to GitHub.

## Key Points

* `git add` → Stage changes.
* `git commit` → Save changes locally.
* `git push` → Upload changes to GitHub.
* `git pull` → Get latest changes from GitHub.
* `git status` → Check repository status.

**Basic Workflow:**

`Working Directory → Staging Area → Local Repository → GitHub`
