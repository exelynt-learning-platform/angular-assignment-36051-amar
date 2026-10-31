
# Git Installation & Setup

## 1. Introduction

The purpose of this assignment is to install Git, verify the installation, configure global Git credentials, and understand basic terminal commands.

Git is a distributed version control system that helps developers track code changes, manage project versions, and collaborate with other developers.

## 2. Git Installation on Windows

### Installation Steps

1. Open the official Git website:
   https://git-scm.com/install/windows

2. Download the Git for Windows installer.

3. Run the downloaded installer.

4. Follow the installation wizard and use the recommended default settings.

5. Complete the installation.

6. Open Git Bash or the VS Code integrated terminal.

Git can be accessed through:
- Git Bash
- Windows Command Prompt
- VS Code Integrated Terminal

## 3. Verify Git Installation

### Command

```bash
git --version
```

### Actual Terminal Output

```text
PASTE YOUR ACTUAL GIT VERSION OUTPUT HERE
```

### Explanation

The `git --version` command displays the installed Git version.

It confirms that Git has been installed successfully and is accessible from the terminal.

## 4. Configure Global Git Username and Email

Git uses a username and email address to identify the author of commits.

### Configure Username

```bash
git config --global user.name "YOUR ACTUAL NAME"
```

### Configure Email

```bash
git config --global user.email "YOUR ACTUAL EMAIL"
```

Replace the example values with your actual name and email address.

### Verify Global Configuration

Command:

```bash
git config --global --list
```

### Actual Terminal Output

```text
PASTE YOUR ACTUAL CONFIGURATION OUTPUT HERE
```

### Explanation

- `git config` is used to configure Git settings.
- `--global` applies the configuration to all repositories for the current user account.
- `user.name` specifies the name associated with Git commits.
- `user.email` specifies the email address associated with Git commits.

## 5. Basic Terminal Commands

I practiced the following three basic terminal commands using Git Bash.

### Command 1: pwd

Command:

```bash
pwd
```

Actual Output:

```text
PASTE YOUR ACTUAL PWD OUTPUT HERE
```

Explanation:

The `pwd` command stands for Print Working Directory.

It displays the full path of the current working directory and helps identify my current location in the file system.

### Command 2: ls

Command:

```bash
ls
```

Actual Output:

```text
PASTE YOUR ACTUAL LS OUTPUT HERE
```

Explanation:

The `ls` command lists the files and directories available in the current working directory.

It helps me understand the contents of a folder.

### Command 3: cd

Command:

```bash
cd Desktop
```

Actual Output:

```text
PASTE YOUR ACTUAL CD OUTPUT OR EXPLAIN THAT THE COMMAND COMPLETED HERE
```

Explanation:

The `cd` command stands for Change Directory.

It is used to navigate from one directory to another.

For example, `cd Desktop` changes the current directory to the Desktop folder.

To verify the new location, I can execute:

```bash
pwd
```

## 6. Understanding the Git Environment

The Git environment allows developers to execute Git commands and manage project versions.

I can use Git through Git Bash or the VS Code integrated terminal.

Some commonly used Git commands are:

| Command | Purpose |
|---|---|
| `git --version` | Checks the installed Git version. |
| `git config --global --list` | Displays global Git configuration. |
| `git status` | Displays the current repository status. |
| `git init` | Initializes a new Git repository. |
| `git add` | Stages changes for a commit. |
| `git commit` | Saves staged changes in the repository history. |
| `git push` | Uploads local commits to a remote repository. |
| `git pull` | Fetches and integrates remote changes. |

## 7. Git Installation Verification Summary

The following activities were completed as part of this assignment:

1. Installed Git on Windows using the official Git website.
2. Verified Git installation using `git --version`.
3. Configured the global Git username.
4. Configured the global Git email address.
5. Verified the configuration using `git config --global --list`.
6. Practiced the `pwd`, `ls`, and `cd` terminal commands.
7. Understood how to use Git Bash and the VS Code terminal.

## 8. Conclusion

Git was installed and configured on my Windows system.

I learned how to verify the Git version, configure global username and email settings, and navigate directories using basic terminal commands.

This setup provides the foundation for using Git for version control, tracking project changes, and collaborating through GitHub.
