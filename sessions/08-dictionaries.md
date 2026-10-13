# Session 08 — Dictionaries

**Time:** one evening, ~2 hours
**You write code in:** `practice/08-dictionaries/`
**You do not write code until the tutor says so.**

Official lesson: [Day 8 — Dictionaries](https://github.com/Asabeneh/30-Days-Of-Python/blob/master/08_Day_Dictionaries/08_dictionaries.md).
Tonight is one idea: look up a value by a **key** (a label), not by position.

## What this session is for

A **dictionary** uses `{ }` with `key: value` pairs:

```py
person = {
    "first_name": "Santiago",
    "age": 26,
    "city": "Bogota",
}
```

- `person["first_name"]` → get the value for that key
- `person["age"] = 27` → change a value (or add a new key)
- `person.pop("city")` → remove a key

Unlike a list, you do not ask “item 0.” You ask “what is under the label `first_name`?”

Design analogy: like a Figma component’s properties — each property has a name and a value. The analogy breaks if you expect order to matter like layers; keys are labels, not positions.

## Check (do this in chat first)

If `person = {"first_name": "Santiago", "age": 26}`, what do you think `person["age"]` is?

## After we talk

You write `practice/08-dictionaries/dictionaries.py` yourself.

## Commit tonight

```
session-08: a dictionary looks up a value by a key
```

## Next (do not start tonight)

Session 09 — Conditionals
