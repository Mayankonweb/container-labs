# GitHub and GitHub Codespaces Setup

## Overview

Before starting the Containerlab exercises, create a personal copy of the repository and launch a GitHub Codespace.

The repository used for this step is:

https://github.com/Mayankonweb/container-labs/fork

> **Important:** This repository does not contain the lab material itself. Its primary purpose is to provide a pre-configured environment that makes GitHub Codespaces setup straightforward and consistent across systems.

Using this repository ensures that everyone starts with a similar development environment without spending time on software installation or dependency configuration.

---

# Step 1 — Create a GitHub Account

If you do not already have a GitHub account, create one at:

https://github.com

GitHub accounts are free for educational and personal use.

---

# Step 2 — Fork the Repository

Open the repository:

```text
https://github.com/Mayankonweb/container-labs/fork
```

Click the **Fork** button near the top-right corner of the page.

A fork creates your own copy of the repository under your GitHub account.

Example:

```text
Original Repository:
Mayankonweb/container-labs

Your Fork:
your-username/container-labs
```

This allows you to:

* Create your own Codespace
* Make changes without affecting the original repository
* Save your work in your own GitHub account

---

# What is GitHub?

GitHub is a cloud platform built around Git.

It is commonly used for:

* Software development
* Version control
* Collaboration
* Documentation
* Research projects
* Open-source software

GitHub allows developers to:

* Store code online
* Track changes over time
* Collaborate with others
* Review modifications
* Manage project history

Today, GitHub is one of the most widely used software development platforms in the world.

---

# Why Is GitHub Used?

GitHub provides several useful capabilities:

### Version Control

Track every change made to files.

### Collaboration

Multiple users can work on the same project.

### Backup

Code remains stored safely in the cloud.

### Reproducibility

Projects can be shared and reproduced easily.

### Development Platforms

Services such as GitHub Codespaces provide cloud-based development environments.

---

# Learning Resources

Those interested in learning more about Git and GitHub may refer to:

### GitHub Skills

https://skills.github.com

### GitHub Documentation

https://docs.github.com

### Introduction to GitHub

https://docs.github.com/en/get-started/start-your-journey/about-github-and-git

### Introduction to Git

https://git-scm.com/doc

---

# What is GitHub Codespaces?

GitHub Codespaces is a cloud-based development environment provided by GitHub.

A Codespace provides:

* Linux environment
* Terminal access
* VS Code interface in the browser
* Pre-installed tools
* Remote development environment

Instead of installing software locally, development can be performed entirely in the browser.

Conceptually:

```text
Your Browser
      │
      ▼
GitHub Codespace
      │
      ▼
Linux Machine in the Cloud
```

The Codespace behaves like a remote Linux computer that you can use for development and experimentation.

---

# Why Use GitHub Codespaces?

Codespaces simplify setup significantly.

Advantages include:

* No local software installation
* Consistent environment across systems
* Browser-based development
* Integrated terminal
* Easy repository access

This is particularly useful when software dependencies are complex or platform-specific.

---

# Step 3 — Create a Codespace

After creating your fork:

1. Open your forked repository.
2. Click the green **Code** button.
3. Select the **Codespaces** tab.
4. Click **Create codespace on main**.

GitHub will provision a cloud development environment.

This process may take a few minutes.

---

# Step 4 — Verify the Environment

Once the Codespace opens:

Open the integrated terminal and run:

```bash
pwd
```

```bash
ls
```

You should see the contents of your forked repository.

---

# Working Inside the Codespace

The Codespace provides:

* File explorer
* Integrated terminal
* Git integration
* VS Code editor
* Linux shell environment

Most commands used throughout the labs can be executed directly inside this terminal.

Examples:

```bash
mkdir test
```

```bash
cd test
```

```bash
git status
```

```bash
python --version
```

---

# Summary

Before proceeding further:

* Create a GitHub account (if needed)
* Fork the repository
* Open your fork
* Create a GitHub Codespace from your fork
* Verify that the terminal is accessible

Once the Codespace is running, you are ready to begin the Containerlab exercises using a consistent cloud-based development environment.
