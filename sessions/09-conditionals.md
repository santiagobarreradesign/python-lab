# Session 09 — Conditionals

**Time:** one evening, ~2 hours
**You write code in:** `practice/09-conditionals/`
**You do not write code until the tutor says so.**

Official lesson: [Day 9 — Conditionals](https://github.com/Asabeneh/30-Days-Of-Python/blob/master/09_Day_Conditionals/09_conditionals.md).
Tonight is one idea: the program chooses a path with `if` / `elif` / `else`.

## What this session is for

A **conditional** asks a yes/no question. If the answer is `True`, Python runs that block.

```py
age = 26

if age >= 18:
    print("adult")
else:
    print("not adult")
```

Important:

- The question uses `==`, `>`, `<`, etc. (not a single `=`)
- Lines under `if` must be **indented** (spaces in from the left). That is how Python knows what belongs inside the decision.
- `elif` means “else if” — another check if the first one failed
- `else` means “if nothing above was True”

## Check (do this in chat first)

If `age = 16`, which message do you think prints: `"adult"` or `"not adult"`?

## After we talk

You write `practice/09-conditionals/conditionals.py` yourself.

## Commit tonight

```
session-09: if chooses a path based on True or False
```

## Next (do not start tonight)

Session 10 — Loops
