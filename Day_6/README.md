# Day 9 – Selection Sort 🧮

## 🔍 Problem
Sort an unsorted array using the Selection Sort algorithm.

## 📌 Concept
Selection Sort selects the minimum element from the unsorted part and places it in the correct position.

## 🧠 Time & Space
- Time: O(n²)
- Space: O(1)

## 🐍 Python Code
```python
def selection_sort(arr):
    n = len(arr)
    for i in range(n):
        min_index = i
        for j in range(i + 1, n):
            if arr[j] < arr[min_index]:
                min_index = j
        arr[i], arr[min_index] = arr[min_index], arr[i]
    return arr
