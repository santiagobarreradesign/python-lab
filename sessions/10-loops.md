# Session 10 — Loops

**Time:** one evening, ~2 hours
**You write code in:** `practice/10-loops/`
**You do not write code until the tutor says so.**

Official lesson: [Day 10 — Loops](https://github.com/Asabeneh/30-Days-Of-Python/blob/master/10_Day_Loops/10_loops.md).
Tonight is one idea: repeat an action for each item, without copying the same line.

## What this session is for

A **loop** walks through a group one item at a time.

```py
fruits = ["apple", "banana", "mango"]

for fruit in fruits:
    print(fruit)
```

Plain English: for each fruit in the list, print that fruit.

- `for` = start the loop
- `fruit` = a temporary name for “the item I’m on right now”
- `in fruits` = the group to walk through
- indented lines = what to do each time

There is also `while` (repeat until a condition becomes False). Tonight we focus on `for` with a list.

## Check (do this in chat first)

If the list has 3 fruits, how many times do you think `print(fruit)` runs?

## After we talk

You write `practice/10-loops/loops.py` yourself.

## Commit tonight

```
session-10: a loop repeats an action for each item
```

## Next (do not start tonight)

Session 11 — Functions
