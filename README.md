# Sorting-Algorithms

<br>

## 1. Bubble Sort:
- **Description:** Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
- **Best Case:** O(n) - Occurs when the array is already sorted, and no swaps are needed.
- **Worst Case:** O(n^2) - Occurs when the array is in reverse order, and each element needs maximum swaps.

## 2. Selection Sort:
- **Description:** Divides the input into sorted and unsorted regions, repeatedly selects the smallest element in the unsorted region, and swaps it with the first element.
- **Best Case:** O(n^2) - Occurs when the array is in reverse order, and maximum swaps are needed.
- **Worst Case:** O(n^2) - Always, as it doesn't adapt to the existing order.

## 3. Insertion Sort:
- **Description:** Builds the sorted array one element at a time, repeatedly takes an element and inserts it into its correct position in the sorted part of the array.
- **Best Case:** O(n) - Occurs when the array is already sorted.
- **Worst Case:** O(n^2) - Occurs when the array is in reverse order, and each element needs maximum shifts.

## 4. Merge Sort:
- **Description:** Divides the array into halves, recursively sorts each half, and then merges them.
- **Best Case:** O(n log n) - Consistently efficient for any input.
- **Worst Case:** O(n log n) - Consistently efficient, even when the array is in reverse order.

## 5. Heap Sort:
- **Description:** Builds a max heap and repeatedly extracts the maximum element.
- **Best Case:** O(n log n) - Consistently efficient for any input.
- **Worst Case:** O(n log n) - Consistently efficient, even when the array is in reverse order.

# Differences:

- **Bubble, Selection, and Insertion Sort:**
  - Are simple and easy to understand.
  - Have quadratic time complexity in the worst case.
  - Are less efficient for large datasets.

- **Merge Sort:**
  - Is a divide-and-conquer algorithm.
  - Provides consistent O(n log n) time complexity.
  - Requires additional space for merging.

- **Heap Sort:**
  - Utilizes a binary heap data structure.
  - Has an in-place sorting property.
  - Maintains O(n log n) time complexity.

Understanding the best and worst-case scenarios is essential for selecting the appropriate sorting algorithm based on the characteristics of the data to be sorted.
