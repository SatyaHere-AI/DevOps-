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
## ⌨️ Step 3: Accept Defaults
After running the command:
(Press Enter 3 times)
1.Press Enter to accept the default file location.
2.Press Enter to skip creating a passphrase (optional).
3.Press Enter again to confirm.

You should see output like:

```bash
Your identification has been saved in /home/your_user/.ssh/id_ed25519
Your public key has been saved in /home/your_user/.ssh/id_ed25519.pub
```
## 📋 Step 4: Copy the Public Key to Clipboard
Use one of the following commands:
✅ Option 1:
```bash
cat ~/.ssh/id_ed25519.pub | clip
```
✅ Option 2:
```bash
clip < ~/.ssh/id_ed25519.pub
⚠️ If clip doesn't work:

Navigate to your .ssh folder:
```bash
cd ~/.ssh

```
