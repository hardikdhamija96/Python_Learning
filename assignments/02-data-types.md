# Assignment 2 — Data Types (int, float, str, bool)

Covers: dynamic typing, division operators, string formatting.

## 1. Division gotcha
```python
orders = 17
days = 5
```
Write one line giving the exact average orders/day (float), and one line giving the whole number of fully "complete" day-batches (floor division). Label which is which.

## 2. Type coercion crash
Fix this without changing the variable values:
```python
price = 49.99
qty = 3
print("Total: " + price * qty)
```

## 3. f-string practice
Given `customer = "Acme"`, `revenue = 125000.5`, write an f-string that prints:
`Acme generated 125000.50 in revenue` — note the revenue is formatted to exactly 2 decimal places. (Hint: f-strings support format specs like `{value:.2f}`.)

## 4. Stretch
Write a function `safe_divide(a, b)` that returns the float division result, but returns `None` instead of crashing when `b == 0`. Call it with both a valid and a zero divisor and print both results.
