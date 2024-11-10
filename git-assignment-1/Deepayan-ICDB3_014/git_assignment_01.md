# Git Command Guide

A simple and complete reference for commonly used Git commands.

## Setting Up Git Configuration

You can configure Git at two levels: **global** and **local**.

### Global Configuration

The global configuration applies to all repositories for the current user. Use the following commands:

```bash
git config --global user.name "your global name"
git config --global user.email "your-global-email@example.com"
```

![Global Git Configuration Screenshot](https://github.com/DeepayanMallick/ic-devops-batch3/raw/git-assignment-1/git-assignment-1/screenshots/global-git-config.png)

### Local Configuration

The local configuration applies to specific repositories. If you want to set up a different user for a particular repository, use the following commands after navigating to the repository directory:

```bash
git config --local user.name "your local name"
git config --local user.email "your-local-email@example.com"
```

![Local Git Configuration Screenshot](https://github.com/DeepayanMallick/ic-devops-batch3/raw/git-assignment-1/git-assignment-1/screenshots/local-git-config.png)

## SSH Key Setup for GitHub

A simple guide to generating and configuring an SSH key for authentication with GitHub.

### Steps to Setup SSH Key for GitHub

### 1. Generate SSH Key

Run the following command to generate a new SSH key pair:

```bash
ssh-keygen
```

## How to initialize a git repository?

```bash
git init
```

### Rename the Branch (if needed)

```bash
git branch -m <branch-name>
```

### Link to the Remote Repository. Make sure your remote repository already exists in your GitHub account

```bash
git remote add origin <remote-repository>
```
