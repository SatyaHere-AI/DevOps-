# 🌌 Git Terminal — Shortcut Keys & Basic Commands

**Quick, copy-pasteable terminal reference & step-by-step setup.**  
Use the copy button in each code block to run commands directly.

---

## Table of contents
1. [Basic Shortcut Keys](#basic-shortcut-keys)  
2. [Basic Commands — Meaning](#basic-commands-meaning)  
3. [Step-by-step: Commands to run in Terminal](#step-by-step-commands-in-terminal)  


---

## Basic Shortcut Keys
- `Ctrl+Alt+T` — Opens Terminal  
- `Ctrl+C` — Stops a code from running  
- `Ctrl+A` — Go to beginning of line  
- `Ctrl+E` — Go to end of line  
- `Ctrl+Shift+C` — Copy in Terminal  
- `Ctrl+Shift+V` — Paste in Terminal

---

## Basic Commands — Meaning
- `whoami` — Displays current username  
- `sudo` — "Super User Do" (administrator access)  
- `clear` — Clears current terminal screen  
- `pwd` — Prints current working directory .  
- `ls` — Lists contents of current directory .
- `ls -a` — Lists hidden contents of current directory .    
- `mkdir` — Creates a new directory (folder)  
- `cd` — Change directory to the entered folder   
- `rmdir` — Deletes empty directory  
- `cp` — Copy file or folder to another location  
- `apt` — Advanced Package Tool (for installing packages on Debian/Ubuntu)  
- `touch` — Create a new file (e.g. `touch Satya.py`)

---

## Step-by-step: Commands in Terminal

> Open terminal from desktop either by clicking the icon or pressing `Ctrl+Alt+T`.

### Step 1 — Update & upgrade packages
```bash
sudo apt update && sudo apt upgrade
```

### Step 2 — (Optional) Install GEdit
```bash
sudo apt install gedit
```

### Step 3 — Install build essentials
```bash
sudo apt install build-essential
```
### Step 4 — Check Python version
```bash
python --version
```
### Step 5 — Check pip
```bash
pip3 --version
```
### Step 6 — If pip not present, install it
```bash
sudo apt install python3-pip
```
### Step 7 — Install Git
```bash
sudo apt install git
```
### Step 8 — Configure Git username and email
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
### ⭐ Contribute

If you have extra useful commands or shortcut tips, feel free to fork this repo and make a pull request!
  
