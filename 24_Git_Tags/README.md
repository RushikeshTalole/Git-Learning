# Git Tags

## What is Git Tag?

`git tag` is used to **mark a specific commit** in Git history.

Tags are commonly used to identify important versions of a project.

## Why Do We Use Git Tags?

We use tags to:

* Mark important commits.
* Identify project versions.
* Create version names like `v1.0`, `v2.0`.
* Easily find a specific release.

## Create a Tag

```bash
git tag v1.0
```

This creates a tag named `v1.0` on the current commit.

## View Tags

```bash
git tag
```

This shows all available tags.

## Tag a Specific Commit

```bash
git tag v1.0 <commit-id>
```

## Delete a Tag

```bash
git tag -d v1.0
```

## Basic Flow

```text
       Commit
          ↓
      git tag
          ↓
       v1.0
          ↓
    Project Version
```

## Example

```bash
git tag v1.0
git tag
```

Output:

```text
v1.0
```

## Important Point

**Git Tag = Name/Label given to an important commit.**

Example:

```text
v1.0 → First Version
v2.0 → Second Version
```

## Interview Question

### What is git tag?

**Answer:**

`git tag` is used to mark a specific commit, usually to identify an important version or release of a project.

## Key Point

**Git Tag = Mark a specific commit with a version name.**
