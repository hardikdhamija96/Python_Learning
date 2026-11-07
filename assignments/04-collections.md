# Assignment 4 — Collections (list, tuple, dict, set)

Covers: ordered/mutable/duplicate semantics, slicing, unpacking, dict.get, set operations, list vs tuple methods.

## 1. Slicing
Given `data = [5, 10, 15, 20, 25, 30]`, write expressions (no loops) to get:
- the last three items
- every other item starting from index 0
- everything except the first and last item

## 2. Safe dict access
Given a list of row dicts where not every row has every key:
```python
rows = [{"id": 1, "amount": 500}, {"id": 2}, {"id": 3, "amount": 75}]
```
Write a loop that sums `amount` across all rows, treating a missing key as `0`, without crashing.

## 3. Dedup with sets
Given `ids = [101, 102, 101, 103, 102, 104]`, write one line to get the unique ids, and one line to check whether `105` is among them.

## 4. Tuple vs list, applied
You're writing a function that returns `(row_count, error_count)` from processing a batch. Explain in 1-2 sentences why returning a tuple here is a better choice than returning a list.

## 5. Stretch
Given two lists of customer IDs from two different data sources, use set operations to find: customers in both, customers only in the first, and customers only in the second. Print each as a sorted list.
