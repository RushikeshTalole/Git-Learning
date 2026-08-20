# Git Init



## What is Git Init?



`git init` is used to initialize a new Git repository in a project directory.



It creates a hidden `.git` directory that stores Git's internal data and information.



---



## Why Do We Use git init?



We use `git init` when we want to start tracking a project using Git.



It converts a normal project folder into a Git repository.



---



## Syntax



git init



---



## How to Initialize a Repository?



1. Create or open a project folder.

2. Open Git Bash inside the project folder.

3. Run:



git init



4. Git creates a `.git` directory.

5. The project becomes a Git repository.



---



## Example



Suppose we have a project:



MyProject



Run:



cd MyProject



Then:



git init



Git initializes the project as a repository.



---



## What Does git init Create?



The `git init` command creates a hidden `.git` directory.



The `.git` directory stores Git's internal information such as:



- Repository configuration

- Commit history

- Branch information

- Git objects

- References



---



## Check the .git Directory



After running:



git init



Use:



ls -a



This shows hidden files and directories.



Example:



.git

.

..



---



## Check Repository Status



After initialization:



git status



Git shows information about the current repository and working directory.



---



## Important Points



- `git init` initializes a Git repository.

- It creates a hidden `.git` directory.

- The `.git` directory contains Git's internal data.

- `git status` checks the repository status.

- `git init` works locally.

- `git init` does not create a GitHub repository automatically.



---



## Interview Questions



### 1. What does git init do?



Answer:



`git init` initializes a new Git repository in the current directory.



### 2. What is the purpose of the .git directory?



Answer:



The `.git` directory stores Git's internal data, configuration, objects, references, and commit history.



### 3. Does git init create a GitHub repository?



Answer:



No. `git init` creates a local Git repository. It does not create a repository on GitHub.



### 4. Can we run git init more than once?



Answer:



Yes, but normally we run `git init` once when starting Git tracking for a project.



---



## Key Points



- `git init` = Initialize a Git repository.

- `.git` = Git's internal repository directory.

- `git status` = Check repository status.

- `git init` creates a local repository.

