# Project Paths

Once a learner finishes setup and the first Git lab, they should move into a live repo and start building.

This file gives the fastest clean handoff into the next prepared repos.

## Before You Jump

Make sure you can already do these in this foundations repo:

- use your terminal
- open a project in VS Code
- run Git basics
- create commits
- follow a README without getting blocked on setup

If not, finish:

- `labs/EDITOR_IDE_SETUP.md`
- `labs/GIT_BASICS.md`
- `setup/SETUP_INDEX.md`

## Path 1: HACKCLUB

Repo:

- https://github.com/eruditewbt/HACKCLUB

Use HACKCLUB if you want:

- Python-first AI practice
- practical experimentation
- modular course pages
- small runnable snippets
- AI + web + automation exploration

### Start Once

Clone and enter:

```bash
git clone https://github.com/eruditewbt/HACKCLUB.git
cd HACKCLUB
```

Create a virtual environment and install the common starter stack:

Windows PowerShell:

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install pytest fastapi uvicorn pydantic numpy pandas scikit-learn matplotlib
```

Linux/macOS/bash:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install pytest fastapi uvicorn pydantic numpy pandas scikit-learn matplotlib
```

Then open the course entry:

- `COURSE/python_ai_modular/index.html`

Strong first files to use:

- `python_snippets/course_basics/variables_and_flow.py`
- `python_snippets/course_basics/functions_and_oop.py`
- `python_snippets/course_basics/errors_and_files.py`
- `AI/course_snippets/basic_rag_demo.py`

### First Goal

Do one of these:

- run one Python basics snippet
- open the modular course page and complete module 01
- document one extension you added to a snippet

## Path 2: JAVASCRIPT

Repo:

- https://github.com/eruditewbt/JAVASCRIPT

Use JAVASCRIPT if you want:

- JavaScript fundamentals to production systems
- Node.js workflow
- collaborative projects
- testing and quality gates
- full-stack and product engineering

### Start Once

Clone and enter:

```bash
git clone https://github.com/eruditewbt/JAVASCRIPT.git
cd JAVASCRIPT
```

Verify prerequisites:

```bash
node -v
npm -v
git --version
```

Install dependencies:

```bash
npm install
```

Optional Git identity setup:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Run the baseline repo checks:

```bash
npm run repo:smoke
npm run repo:audit
```

Strong first places to open:

- `plan.md`
- `course/`
- `javascript-training/`
- `projects/`

### First Goal

Do one of these:

- complete one JavaScript training module
- create a task branch and fix one small issue
- run smoke checks and document what each command does

## Community Flow

As soon as you enter either repo:

1. Join Discord: https://discord.gg/8e4bQNknA
2. Subscribe on YouTube: https://www.youtube.com/@eruditewbt
3. Post your setup proof
4. Pick one small task
5. Commit and share your progress

## Simple Recommendation

- If you are still new to coding:
  start with this foundations repo, then move to HACKCLUB.
- If you already understand basic coding and want stronger product workflow:
  move into JAVASCRIPT.

