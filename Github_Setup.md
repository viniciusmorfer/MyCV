# GitHub Setup Guide

This guide provides step-by-step instructions for setting up Git on your Windows laptop, connecting it to your GitHub account, and pushing your project code to a new repository.

## Prerequisites
- A GitHub account ([Sign up here](https://github.com))
- Windows laptop with Git installed

---

## Step 1: Install Git

1. Download Git from [git-scm.com](https://git-scm.com).
2. Run the installer and accept the default settings.
3. Open Git Bash from the Start menu.

---

## Step 2: Configure Git

1. Open Git Bash.
2. Set your username and email:
   ```bash
   git config --global user.name "YourName"
   git config --global user.email "YourEmail@example.com"
   ```

---

## Step 3: Generate SSH Key (Optional but Recommended)

1. Generate an SSH key:
   ```bash
   ssh-keygen -t rsa -b 4096 -C "YourEmail@example.com"
   ```
2. Start the SSH agent:
   ```bash
   eval "$(ssh-agent -s)"
   ```
3. Add your private key:
   ```bash
   ssh-add ~/.ssh/id_rsa
   ```
4. Copy the SSH key to your clipboard:
   ```bash
   cat ~/.ssh/id_rsa.pub | clip
   ```
5. Add the key to GitHub:
   - Log in to GitHub.
   - Navigate to **Settings > SSH and GPG keys > New SSH key**.
   - Paste the key and click **Add SSH key**.

---

## Step 4: Create a New Repository on GitHub

1. Log in to GitHub.
2. Click the **+** icon and select **New repository**.
3. Enter a repository name, optional description, and visibility settings.
4. Click **Create repository**.

---

## Step 5: Initialize Your Local Project

1. Open Git Bash and navigate to your project directory:
   ```bash
   cd path/to/your/project
   ```
2. Initialize Git:
   ```bash
   git init
   ```
3. Add files to staging:
   ```bash
   git add .
   ```
4. Commit your changes:
   ```bash
   git commit -m "Initial commit"
   ```

---

## Step 6: Connect to Your GitHub Repository

1. Add the remote repository:
   - Using HTTPS:
     ```bash
     git remote add origin https://github.com/your-username/your-repository.git
     ```
   - Using SSH:
     ```bash
     git remote add origin git@github.com:your-username/your-repository.git
     ```

---

## Step 7: Push Your Code

1. Push your code to the main branch:
   ```bash
   git push -u origin main
   ```
2. If using the master branch:
   ```bash
   git push -u origin master
   ```

---

## Step 8: Verify Your Push

1. Visit your GitHub repository to confirm the upload.

---

## Quick Commands

- **Stage and commit changes:**
  ```bash
  git add .
  git commit -m "Your message"
  ```

- **Push changes to GitHub:**
  ```bash
  git push
  ```

- **Pull updates from GitHub:**
  ```bash
  git pull
  ```

---

For more detailed information, visit the [GitHub Docs](https://docs.github.com).
