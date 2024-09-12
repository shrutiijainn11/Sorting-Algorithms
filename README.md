# Sorting-Algorithms
Different sorting algorithms implementation in java

Algorithms included:
## Insertion Sort
### Time Complexity:
- Best: O(n)
- Average: O(n²)
- Worst: O(n²)
### Key Points:
- Efficient for small or nearly sorted data.
- Builds the sorted list one element at a time by inserting each element into its correct position.
- Used in hybrid algorithms like TimSort.

## Bubble Sort
### Time Complexity:
- Best: O(n)
- Average: O(n²)
- Worst: O(n²)
### Key Points:
- Simple but inefficient for large datasets.
- Repeatedly swaps adjacent elements if they are in the wrong order.
- Suitable for small datasets or nearly sorted data.

## Selection Sort
### Time Complexity:
- Best: O(n²)
- Average: O(n²)
- Worst: O(n²)
### Key Points:
- Selects the smallest (or largest) element from the unsorted portion and swaps it with the first unsorted element.
- Inefficient for large datasets.
- Does not require extra space (in-place sorting)

Merge Sort
Time Complexity:
Best, Average, and Worst: O(n log n)
Key Points:
Divide-and-conquer algorithm.
Divides the array into two halves, recursively sorts them, and then merges the sorted halves.
Requires extra space (not in-place).
Stable sorting algorithm.
5. Quick Sort
Time Complexity:
Best: O(n log n)
Average: O(n log n)
Worst: O(n²)
Key Points:
Uses a pivot to partition the array into two halves and recursively sorts them.
In-place sorting (no extra space needed).
Performance depends on pivot choice; random or median-of-three pivot can help avoid worst-case scenarios.
Unstable sorting algorithm.

