# Bubble-Sort

Bubble Sort compares each pair of adjacent elements in the array and swaps them if they are in the wrong order. This process repeats until the array is sorted.

## Explanation
- The outer loop runs n times (where n is the length of the array).
- The inner loop compares adjacent elements and swaps them if they are in the wrong order.
- If no swaps are made during a pass through the inner loop, the array is considered sorted, and the loop terminates early (this is the optimization part).

## Time Complexity
- Worst and average case: O(n²)
- Best case (if the array is already sorted): O(n)
