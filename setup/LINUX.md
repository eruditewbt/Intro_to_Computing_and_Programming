# Linux Setup (Ubuntu/Debian)

Goal: install the minimum tooling so you can code immediately.

## Step 1: Update System

```bash
sudo apt update
sudo apt -y upgrade
```

## Step 2: Install Git

```bash
sudo apt -y install git
git --version
```

## Step 3: Install Python

```bash
sudo apt -y install python3 python3-pip
python3 --version
pip3 --version
```

## Step 4: Install VS Code

Options:

- Use your distro’s package manager method.
- Or use a portable editor you trust.

Proof:

- Screenshot of editor + terminal.

## Step 5: First Project + Git Repo

```bash
mkdir -p ~/code/intro_course
cd ~/code/intro_course
git init
printf \"# Intro Course\\n\" > README.md
git add -A
git commit -m \"init\"
```

## Shell Basics (Bash)

Verify your shell:

```bash
echo $SHELL
```

