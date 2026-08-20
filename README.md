# Skills: Introduction to GitHub

Welcome to the Introduction to GitHub repository! This project is designed as a sandbox to help you learn the basics of version control, specifically how to create **Pull Requests (PRs)** and understand the **Merge** process.

## 🧠 Git vs. GitHub: What's the difference?

It is easy to confuse Git and GitHub, but they serve different purposes:

*   **Git** is a software tool for tracking code changes locally on your machine.
*   **GitHub** is a cloud-based platform that hosts those tracked changes so developers can collaborate and work together.

> **💡 The Analogy:** Think of Git as a local word processor on your computer, and GitHub as Microsoft OneDrive or Google Drive where you save, share, and collaborate on your documents.

## 🎯 Learning Objectives

By working through this repository, you will learn how to:
1. Create a new branch for your work.
2. Make changes and commit them using Git.
3. Push your changes to GitHub.
4. Open a **Pull Request**.
5. **Merge** your pull request into the main branch.

## 🚀 Getting Started

Follow these steps to practice making a change and opening your first Pull Request:

### Step 1: Create a New Branch
Always create a new branch for your work so you don't edit the `main` branch directly. Open your terminal and run:
```bash
git checkout -b my-first-pr
```

### Step 2: Make Your Changes
Open this project in your code editor, make a small change (like adding your name to a file), and save it.

### Step 3: Commit Your Changes
Tell Git to track the files you changed and save a "snapshot" of your work.
```bash
git add .
git commit -m "Added my name to the project"
```

### Step 4: Push to GitHub
Send your local branch up to GitHub so others can see it.
```bash
git push -u origin my-first-pr
```

### Step 5: Open a Pull Request
1. Go to this repository's page on GitHub.
2. You will see a green banner that says **Compare & pull request**. Click it!
3. Give your PR a title, write a brief description of what you changed, and click **Create pull request**.

### Step 6: Merge Your PR
Once your PR is open, you (or a teammate) can review the changes. If everything looks good:
1. Click the green **Merge pull request** button on GitHub.
2. Click **Confirm merge**. 

Congratulations, you've just merged your first PR! 🎉

---
*Happy Coding!*
