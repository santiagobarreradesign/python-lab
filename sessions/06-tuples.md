# Session 06 — Tuples

**Time:** one evening, ~2 hours
**You write code in:** `practice/06-tuples/`
**You do not write code until the tutor says so.**

Official lesson: [Day 6 — Tuples](https://github.com/Asabeneh/30-Days-Of-Python/blob/master/06_Day_Tuples/06_tuples.md).
Tonight is one idea: a tuple is like a list that you are not allowed to change.

## What this session is for

A **tuple** uses parentheses `()`:

```py
colors = ("red", "green", "blue")
```

Same as a list for reading:

- `colors[0]` → first item
- `len(colors)` → how many

Different from a list: no `append`, no `remove`. If you try to change it, Python errors.

Use a tuple when the group should stay fixed (days of the week, RGB, a locked set of options).

## Check (do this in chat first)

What do you think happens if you try `colors.append("yellow")` on a tuple?

## After we talk

You write `practice/06-tuples/tuples.py` yourself.

## Commit tonight

```
session-06: a tuple is an ordered group that does not change
```

## Next (do not start tonight)

Session 07 — Sets
