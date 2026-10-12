# Session 01 — Python runs a line

**Time:** one evening, ~2 hours
**You write code in:** `practice/01-interpreter/`
**You do not write code until the tutor says so.**

Official lesson: [Day 1 — Introduction](https://github.com/Asabeneh/30-Days-Of-Python/blob/master/readme.md).
Tonight is the interpreter, the shell, and a file. The data-type tour in that lesson waits for later sessions.

## What this session is for

Python is a program on your computer. You hand it text. It reads one line, does that line, then reads the next.

The interactive shell (`>>>`) is a conversation: you type a line, it answers.
A `.py` file is that conversation saved. A file stays quiet unless you `print`.

Indentation is structure. Other languages use `{ }` to say "this is inside that." Python uses spaces. A bad indent is a broken program.

## Check (do this in chat first)

What do you already think happens when someone runs a Python file?

## After we talk

Three things you will do yourself:

1. Install Python 3 from [python.org](https://www.python.org/downloads/). On the installer, check **Add python.exe to PATH**. Then run `python --version` in a new terminal. You want a version of 3.6 or newer.
2. Open the shell with `python`. Type `2 x 3`. Read the error. Fix the line so the math runs. Leave the shell with `exit()`.
3. Create `practice/01-interpreter/hello.py`. Print your name, and print one sentence about what you think Python just did. Run the file from the terminal.

## Where this trips people up

- On this PC, typing `python` currently launches a Microsoft Store stub. That is not Python. The installer plus "Add to PATH" is what replaces it. Open a **new** terminal after installing, or the old one still sees the stub.
- The shell shows results on its own. A file does not. If you write `2 + 3` in a file and run it, nothing appears. `print(2 + 3)` does.
- Indenting the first line of a file, or mixing tabs and spaces, raises `IndentationError`.

## Commit tonight

```
session-01: python reads a file one line at a time
```

## Next (do not start tonight)

Session 02 — Variables
