# Windows Setup (Windows 10/11)

Goal: install the minimum tooling so you can code immediately.

## What You’ll Install

- VS Code (editor)
- Git (version control)
- Python (first programming language for the course)
- Optional: WSL2 (Linux environment on Windows)

## Step 1: VS Code

- Install VS Code.
- Open VS Code → Settings → search “format on save” → enable it.

Recommended extensions:

- Python
- Pylance
- GitLens (optional)

Proof:

- Screenshot of VS Code with integrated terminal open.

## Step 2: Git

- Install Git for Windows.
- Verify in PowerShell:

```powershell
git --version
```

Proof:

- Output of `git --version`.

## Step 3: Python

- Install Python 3.x.
- During install: ensure “Add python.exe to PATH” is enabled.
- Verify:

```powershell
python --version
pip --version
```

If `python` doesn’t work, try:

```powershell
py --version
```

Proof:

- Output of version checks.

## Step 4: Create Your First Project Folder

```powershell
mkdir code
cd code
mkdir intro_course
cd intro_course
code .
```

## Step 5: Your First Git Repo

```powershell
git init
echo \"# Intro Course\" > README.md
git add -A
git commit -m \"init\"
```

## Optional: WSL2 (Recommended If You Want Linux Skills)

WSL lets you use Ubuntu on Windows.

- Install WSL2 + Ubuntu.
- In Ubuntu terminal verify:

```bash
uname -a
```

You can still use VS Code from WSL with the Remote WSL extension.

