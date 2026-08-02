# Two Sum

## Pattern

Hash map lookup.

## Approach

Store each number and its index as we iterate.

For the current number, calculate:

`complement = target - current_number`

If the complement is already in the hash map, return both indices.

## Complexity

- Time: O(n)
- Space: O(n)

## What I learned

A hash map lets us check whether the required complement has already appeared in O(1) average time.
