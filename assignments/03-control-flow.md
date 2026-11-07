# Assignment 3 — Control Flow (Conditions & Loops)

Covers: if/elif/else, truthy/falsy, ternary, for/while, break/continue.

## 1. Truthy/falsy trap
```python
def describe(count):
    if count:
        return "has data"
    return "empty or zero"
```
What does `describe(0)` return? Is that actually correct behavior if `0` is a legitimate order count (as opposed to "no data available")? Rewrite `describe` so it distinguishes `0` from `None`.

## 2. Ternary
Rewrite this as a one-line ternary:
```python
if score >= 50:
    result = "pass"
else:
    result = "fail"
```

## 3. Loop control
Given `orders = [120, 0, 85, -10, 300]`, write a loop that sums only positive amounts, skipping zero/negative ones, and stops entirely (without summing anything further) if it hits a value above 250. Print the running total at the end.

## 4. Stretch
A `while` loop that processes a queue (a list you `.pop()` from) until it's empty. Write it, and explain in one sentence what would make it infinite if you got the loop condition wrong.
