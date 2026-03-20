# Android Setup (Termux)

Termux turns your Android phone into a small Linux-like environment.

Goal: install Git + Python so you can code and practice fundamentals even without a laptop.

## Step 1: Install Termux

Install Termux from a trusted source for your device.

## Step 2: Update Packages

```bash
pkg update -y
pkg upgrade -y
```

## Step 3: Install Git + Python

```bash
pkg install -y git python
git --version
python --version
pip --version
```

## Step 4: Basic Folder Setup

```bash
mkdir -p ~/code/intro_course
cd ~/code/intro_course
```

## Step 5: First Program

```bash
cat > hello.py << 'EOF'
print("Hello from Termux")
EOF
python hello.py
```

## Step 6: First Git Repo

```bash
git init
printf "# Intro Course (Termux)\n" > README.md
git add -A
git commit -m "init"
```

## Notes / Limits

- Termux is great for fundamentals, scripting, Git, and lightweight programming.
- For heavy GUI apps, data science tooling, or large builds, a laptop/desktop is better.

