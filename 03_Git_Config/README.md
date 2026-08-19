# Git Config



## What is Git Config?



Git configuration is used to set user-specific information and preferences for Git.



Git uses this information when creating commits.



---



## Why Do We Use Git Config?



Git config helps Git identify the person who creates a commit.



The most common configuration is:



- User Name

- User Email



---



## Check Git Configuration



To view the current configuration:



git config --list



---



## Set User Name



Command:



git config --global user.name "Your Name"



Example:



git config --global user.name "Rushikesh Talole"



---



## Set User Email



Command:



git config --global user.email "your-email@example.com"



Example:



git config --global user.email "your-email@example.com"



---



## Check User Name



Command:



git config --global user.name



This displays the configured Git username.



---



## Check User Email



Command:



git config --global user.email



This displays the configured Git email.



---



## Global Configuration



The `--global` option applies the configuration to all Git repositories for the current user.



Example:



git config --global user.name "Your Name"



---



## Local Configuration



The `--local` option applies the configuration only to the current repository.



Example:



git config --local user.name "Project User"



---



## Global vs Local Configuration



| Global | Local |

|---|---|

| Applies to all repositories | Applies only to current repository |

| Uses `--global` | Uses `--local` |

| User-level configuration | Repository-level configuration |

| Lower priority than local configuration | Higher priority than global configuration |



---



## Important Commands



Check all configuration:



git config --list



Set username:



git config --global user.name "Your Name"



Set email:



git config --global user.email "your-email@example.com"



Check username:



git config --global user.name



Check email:



git config --global user.email



---



## Interview Questions



### 1. Why is Git config used?



Answer:



Git config is used to set user information and other Git preferences.



### 2. Why do we configure user.name and user.email?



Answer:



Git uses user.name and user.email to identify the author of a commit.



### 3. What is the difference between --global and --local?



Answer:



`--global` applies the configuration to all repositories for the current user, while `--local` applies it only to the current repository.



### 4. Which configuration has higher priority?



Answer:



Local configuration has higher priority than global configuration.



---



## Key Points



- Git config manages Git settings.

- user.name identifies the commit author.

- user.email identifies the commit author's email.

- `--global` applies settings to all repositories.

- `--local` applies settings to the current repository.

- Local configuration overrides global configuration.

