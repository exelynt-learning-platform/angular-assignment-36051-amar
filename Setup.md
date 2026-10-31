
# Git Installation & Setup

## 1. Introduction

This assignment demonstrates the installation and configuration of Git on a Windows operating system.

Git is a distributed version control system used to track code changes, maintain project history, and collaborate with other developers.

## 2. Git Installation on Windows

### Installation Steps

1. Visited the official Git website: https://git-scm.com/install/windows
2. Downloaded the Git for Windows installer.
3. Executed the downloaded installer.
4. Followed the installation wizard using the recommended settings.
5. Completed the installation successfully.
6. Opened Git Bash to execute Git commands.

Git can also be accessed through the VS Code integrated terminal and Windows Command Prompt.

## 3. Verify Git Installation

### Command

```bash
git --version
```

### Sample Terminal Output

```text
git version 2.51.0.windows.1
```

### Explanation

The `git --version` command displays the installed Git version.

This confirms that Git is installed and accessible from the terminal.

## 4. Configure Global Git Username and Email

Git uses a username and email address to identify the author of commits.

### Configure Username

Command:

```bash
git config --global user.name "Amar"
```

### Configure Email

Command:

```bash
git config --global user.email "amar@example.com"
```

Note: `amar@example.com` is a demonstration email address. Replace it with your actual email address before submission.

### Verify Global Configuration

Command:

```bash
git config --global --list
```

### Sample Terminal Output

```text
user.name=Amar
user.email=amar@example.com
```

### Explanation

- `git config` is used to configure Git settings.
- `--global` applies the settings to all repositories for the current user account.
- `user.name` specifies the name associated with Git commits.
- `user.email` specifies the email address associated with Git commits.

## 5. Basic Terminal Commands

I practiced three basic terminal commands using Git Bash.

### Command 1: pwd

Command:

```bash
pwd
```

Sample Terminal Output:

```text
/c/Users/Amar/Desktop/git-installation-setup-week1-2368
```

Explanation:

The `pwd` command stands for Print Working Directory.

It displays the full path of the current working directory and helps identify my current location in the file system.

### Command 2: ls

Command:

```bash
ls
```

Sample Terminal Output:

```text
README.md
SETUP.md
```

Explanation:

The `ls` command lists the files and directories available in the current working directory.

It helps identify the contents of a folder.

### Command 3: cd

Command:

```bash
cd Desktop
```

Sample Terminal Output:

```text
No output displayed. The command completed successfully.
```

Verification command:

```bash
pwd
```

Sample verification output:

```text
/c/Users/Amar/Desktop
```

Explanation:

The `cd` command stands for Change Directory.

It is used to navigate from one directory to another.

For example, `cd Desktop` changes the current directory to the Desktop folder.

## 6. Understanding the Git Environment

Git provides a command-line environment for managing project versions and tracking changes.

Some commonly used Git commands are:

| Command | Purpose |
|---|---|
| `git --version` | Checks the installed Git version. |
| `git config --global --list` | Displays global Git configuration. |
| `git status` | Displays the current repository status. |
| `git init` | Initializes a new Git repository. |
| `git add` | Stages changes for a commit. |
| `git commit` | Saves staged changes in repository history. |
| `git push` | Uploads local commits to a remote repository. |
| `git pull` | Fetches and integrates remote changes. |

## 7. Installation and Configuration Summary

The following setup activities were covered:

1. Installed Git on Windows using the official Git website.
2. Verified the installed Git version.
3. Configured the global Git username.
4. Configured the global Git email address.
5. Verified the global Git configuration.
6. Practiced the `pwd`, `ls`, and `cd` terminal commands.
7. Explored Git Bash and the VS Code integrated terminal.

## 8. Conclusion

Git installation and configuration are essential steps in a developer's workflow.

Through this assignment, I learned how to verify the Git installation, configure global identity settings, navigate directories using terminal commands, and understand the basic Git environment.

I am now familiar with the initial setup required to use Git for version control and GitHub collaboration.
