# 🚀 Setting Up SSH Key for GitHub (Windows - Git Bash / WSL)

This guide walks you through generating an **ED25519 SSH key pair** and adding it to your **GitHub** profile. SSH keys are a secure way to connect with GitHub without entering your username and password every time.

---

## 🔧 Prerequisites

- Windows OS
- [Git Bash](https://gitforwindows.org/) or [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install)
- A GitHub account

---

## 🧩 Step 1: Open Git Bash or WSL

1. Press `Win` + `S` and search for **Git Bash** or **WSL (e.g., Ubuntu)**.
2. Open it.

---

## 🔐 Step 2: Generate SSH Key Pair

Run the following command in the terminal. Replace the email with **your GitHub email**:

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```
📌 Example:
```bash
ssh-keygen -t ed25519 -C "abo@gmail.com"
```
