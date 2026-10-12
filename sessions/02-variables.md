# Session 02 — Variables

**Time:** one evening, ~2 hours
**You write code in:** `practice/02-variables/`
**You do not write code until the tutor says so.**

Official lesson: [Day 2 — Variables, built-in functions](https://github.com/Asabeneh/30-Days-Of-Python/blob/master/02_Day_Variables_builtin_functions/02_variables_builtin_functions.md).
Tonight is naming values. Casting, `input()`, and circle math wait.

## What this session is for

A variable is a **name stuck on a value** so you can use that value later.

```py
first_name = "Santiago"
```

`=` here is not math equality. It is assignment: “put this value in that name.”

Naming rules that matter tonight:

- Start with a letter or `_`
- Letters, numbers, `_` only — no spaces, no hyphens
- Case matters: `Name` and `name` are different
- Prefer `snake_case` for multi-word names: `first_name`

## Check (do this in chat first)

What do you already think a variable is for?

## After we talk

You will write `practice/02-variables/variables.py` yourself:

1. A comment at the top: `# Day 2: variables`
2. Variables for your first name, last name, country, city, age
3. `print` each one with a label (example: `print("First name:", first_name)`)
4. Use `type(...)` on two of them and print the results
5. Use `len(...)` on your first name and print that length

## Where this trips people up

- Writing `first-name` — Python reads that as subtraction, not a name
- Thinking `=` means “are these equal?” — that is `==`, later
- Forgetting quotes around text — `Santiago` without quotes is a name Python looks up, not a string

## Commit tonight

```
session-02: a variable is a name stuck on a value
```

## Next (do not start tonight)

Session 03 — Operators
