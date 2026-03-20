# Modules (Course Map)

This course is intentionally layered:

- Layer 1: what a computer is (mental model)
- Layer 2: how the system works (hardware + OS + files + networking)
- Layer 3: how programs work (code → run → debug)
- Layer 4: how languages work (compile/interpret, runtime, libraries)
- Layer 5: how to build outcomes (projects + proof)

## Module A — Computing Mental Model

- What is a computer (input → process → output)
- Bits, bytes, and representation (numbers, text, images)
- Hardware vs software
- “What happens when you click” (high-level pipeline)

Deliverables:
- A one-page “What is a computer?” explanation
- Diagram: input → CPU/RAM → storage/output

## Module B — Computer Components (Real Hardware)

- CPU (control unit, ALU), RAM, storage (HDD/SSD), motherboard, PSU
- Ports and peripherals
- Building a PC (concept + optional physical lab)
- Troubleshooting basics

Deliverables:
- Component map (diagram)
- “My computer spec sheet” + what each part does

## Module C — Operating Systems & The Command Line

- What the OS does (processes, memory, filesystems, devices)
- The terminal as a “power tool”
- Installing software and understanding PATH
- File structure and permissions (intro)
- Shells across platforms:
  - Windows: PowerShell, `cmd.exe`, `.bat`
  - Linux/macOS: bash/zsh, shell scripts
  - Android: Termux (bash + package manager)
- Editors/IDEs:
  - what an editor is vs an IDE
  - VS Code setup, extensions, formatters, terminals
  - debugging basics (breakpoints, stepping) when ready
- Git fundamentals:
  - repo, commit, branch, remote
  - how to collaborate safely (pull, push, PR)

Deliverables:
- CLI worksheet (20 commands)
- “Setup checklist” completed
- Git proof: a repo with 3 commits and a clean README
- Editor proof: VS Code configured + screenshot + settings export

## Module D — How Computers Communicate (Networking Basics)

- Internet basics (IP, DNS, HTTP)
- Client/server model
- Requests, responses, latency, reliability

Deliverables:
- Diagram: browser → DNS → server → response
- Simple “download a file” mini-lab + explanation

## Module E — Programming Foundations (Python First)

- Variables, types, I/O, conditions, loops
- Functions, modules, errors, debugging
- Data: lists/dicts, files, JSON

Deliverables:
- 10 small programs (exercises)
- Mini-project #1

## Module F — How Languages Run (The “Under the Hood” Layer)

- Compiler vs interpreter
- Runtime, standard library, packages
- Memory basics (stack vs heap, conceptual)
- “Hello world” in multiple languages (one file each)

Deliverables:
- Diagram: source → build → run
- Notes: why errors happen and how to debug

## Module G — Language Survey (Breadth, Not Mastery)

Goal: help learners choose a direction.

- Python (general)
- JavaScript (web)
- C (low-level understanding)
- SQL (data)
- HTML/CSS (documents and layout)
- Bash/PowerShell (automation)

Deliverables:
- “Language choice guide” for your own goal

## Module H — Projects & Proof (Portfolio Layer)

- Documentation (README, diagrams, screenshots)
- Demos (short video, scriptable runs)
- Publishing (GitHub)

Deliverables:
- Mini-project #2
- Capstone starter repo

## Optional Module I — Beyond Classical Computing (Survey)

- Classical vs quantum (intuition only)
- Analog and hybrid computing (why it matters historically)
- Distributed systems and cloud intro

Deliverables:
- “Computing types” comparison table + diagram

## Optional Module J — Tooling & Automation (Practical Power)

This module turns “I can code” into “I can work like a professional”.

- Bash scripting basics (variables, pipes, exit codes)
- Windows batch basics (`.bat`), plus when to use PowerShell instead
- Termux workflow on Android (git + python + node basics)
- Project hygiene:
  - `.gitignore`
  - `README` conventions
  - folder structure
  - reproducible runs (one command)

Deliverables:
- A `scripts/` folder with one bash script and one `.bat` script that automate a real task
- A published “setup guide” for your device (Windows/Linux/macOS/Android)
