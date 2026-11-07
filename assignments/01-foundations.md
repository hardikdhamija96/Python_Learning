# Assignment 1 — Foundations (Variables & Memory)

Covers: names vs boxes, mutability of references, garbage collection, memory lifecycle.

## 1. Predict before you run
```python
a = [1, 2]
b = a
c = [1, 2]
print(a == c, a is c)
print(a == b, a is b)
```
Predict the output for each `print`, then run it. Explain in one sentence why `==` and `is` disagree on the first line.

## 2. Break the sharing
Given:
```python
original = {"status": "pending"}
working_copy = original
working_copy["status"] = "done"
print(original["status"])
```
Fix this so `original` is untouched when `working_copy` changes — write the corrected version.

## 3. Reference counting, in your own words
In 2-3 sentences: why does holding onto a reference you no longer need (e.g., appending to a list inside a long-running loop and never clearing it) cause memory to climb in a real pipeline?

## 4. Stretch
Write a 10-line script that intentionally creates a large list, deletes the only reference to it (`del` or reassignment), and prints something before and after to show the point where it becomes eligible for garbage collection. (You don't need to literally observe GC — just structure the code to show you understand *when* an object becomes unreachable.)
