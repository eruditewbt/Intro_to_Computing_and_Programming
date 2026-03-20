# Shell Cheat Sheets (Bash + PowerShell + cmd + Batch)

These are “minimum viable commands” to start coding.

## Bash / zsh (Linux/macOS/Termux)

```bash
pwd
ls -la
cd path/to/folder
mkdir my_project
rm -rf build/
cp a.txt b.txt
mv old.txt new.txt
cat file.txt
head -n 20 file.txt
tail -n 20 file.txt
grep -n \"pattern\" file.txt
find . -name \"*.py\"
```

## PowerShell (Windows)

```powershell
Get-Location
Get-ChildItem
Set-Location .\\my_project
New-Item -ItemType Directory my_project
Copy-Item a.txt b.txt
Move-Item old.txt new.txt
Remove-Item -Recurse -Force build
Get-Content file.txt
Select-String -Path file.txt -Pattern \"pattern\"
```

## cmd.exe (Windows)

```cmd
cd
dir
cd my_project
mkdir my_project
copy a.txt b.txt
ren old.txt new.txt
del file.txt
rmdir /s /q build
type file.txt
findstr /n \"pattern\" file.txt
```

## Windows Batch (.bat) Mini Examples

Hello:

```bat
@echo off
echo Hello from batch
```

Run a Python file:

```bat
@echo off
python hello.py
```

## When To Use What

- Use PowerShell for most scripting on Windows.
- Use `.bat` when you need a super-simple launcher (like a build runner).
- Use bash/zsh when you’re on Linux/macOS/WSL/Termux.

