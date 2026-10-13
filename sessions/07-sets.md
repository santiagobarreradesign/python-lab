# Session 07 — Sets

**Time:** one evening, ~2 hours
**You write code in:** `practice/07-sets/`
**You do not write code until the tutor says so.**

Official lesson: [Day 7 — Sets](https://github.com/Asabeneh/30-Days-Of-Python/blob/master/07_Day_Sets/07_sets.md).
Tonight is one idea: a set only keeps unique items.

## What this session is for

A **set** uses curly braces `{ }`:

```py
nums = {1, 2, 2, 3}
```

Python keeps that as `{1, 2, 3}`. The duplicate `2` is dropped.

Differences from a list:

- no duplicates
- no reliable “first / second” order — do not use `nums[0]`
- good when you care about “is this already in the group?”

Useful moves tonight:

- `add` — put one item in
- `remove` — take one item out
- make a set from a list to get unique values: `set(my_list)`

## Check (do this in chat first)

What do you think `{1, 2, 2, 3}` becomes?

## After we talk

You write `practice/07-sets/sets.py` yourself.

## Commit tonight

```
session-07: a set keeps only unique items
```

## Next (do not start tonight)

Session 08 — Dictionaries
