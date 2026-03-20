# Lab: Git Basics (Init → Commit → Branch → Merge → Push)

## Goal

You will create a repo with real history and push it to GitHub.

## Part 1: Init + First Commit

Create a folder and initialize:

```bash
mkdir git_lab
cd git_lab
git init
printf "# Git Lab\n" > README.md
git add -A
git commit -m "init"
```

Verify:

```bash
git status
git log --oneline --decorate --max-count=5
```

## Part 2: Make Changes + Commit

```bash
printf "\n## Notes\n- First commit done.\n" >> README.md
git add -A
git commit -m "add notes"
```

## Part 3: Branch + Merge

```bash
git checkout -b feature/add-file
printf "print('hello')\n" > hello.py
git add -A
git commit -m "add hello script"

git checkout main
git merge feature/add-file
```

## Part 4: Add .gitignore

```bash
printf "__pycache__/\n*.pyc\n.venv/\n" > .gitignore
git add -A
git commit -m "add gitignore"
```

## Part 5: Push to GitHub

Create an empty repo on GitHub, then:

```bash
git remote add origin <YOUR_REPO_URL>
git push -u origin main
```

## Proof Artifact

Submit:

- Your GitHub repo link
- Screenshot of `git log --oneline`

