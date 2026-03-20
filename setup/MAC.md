# macOS Setup

Goal: install the minimum tooling so you can code immediately.

## Step 1: Terminal + Shell

Open Terminal and verify:

```bash
echo $SHELL
```

On modern macOS, default shell is usually `zsh`.

## Step 2: Git

macOS may prompt to install developer tools the first time you run git:

```bash
git --version
```

Proof:

- Output of `git --version`.

## Step 3: Python

You can use `python3`:

```bash
python3 --version
pip3 --version
```

## Step 4: VS Code (or your editor)

- Install VS Code.
- Enable format-on-save.

Proof:

- Screenshot of VS Code with terminal open.

## Step 5: First Project + Git Repo

```bash
mkdir -p ~/code/intro_course
cd ~/code/intro_course
git init
printf \"# Intro Course\\n\" > README.md
git add -A
git commit -m \"init\"
```

