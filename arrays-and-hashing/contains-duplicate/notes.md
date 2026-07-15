# Contains Duplicate

## Pattern

Arrays and hashing.

## Brute-force approach

Use two loops to compare every possible pair.

- Time complexity: O(n²)
- Space complexity: O(1)

## Optimal approach

Use a set to store numbers that have already been visited.

For each number:

1. Check whether it is already in the set.
2. If it is, return `True`.
3. Otherwise, add it to the set.

- Time complexity: O(n)
- Space complexity: O(n)

## Main lesson

When I need to check whether a value has appeared before, I should consider using a set because membership checking is O(1) on average.
