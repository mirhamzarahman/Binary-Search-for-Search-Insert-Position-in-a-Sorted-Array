

## Approach

The solution uses **binary search**.

- Return the index immediately if the target is found.
- If the search ends without finding the target, the `left` pointer represents the correct insertion position.

This guarantees logarithmic time complexity.

## Complexity

- **Time:** `O(log n)`
- **Space:** `O(1)`

## Concepts Used

- Binary Search
- Sorted Arrays
- Search Algorithms

## Language

- JavaScript
