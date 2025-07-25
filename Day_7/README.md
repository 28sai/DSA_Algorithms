# 📅 Day 8 – Selection Sort

**🧠 Concept:**  
Selection Sort selects the minimum element from the unsorted part and places it at the beginning. Repeats until the array is sorted.

**📌 Time Complexity:** O(n²)  
**📌 Space Complexity:** O(1)  
**📌 Stable:** ❌

---

### 🧪 Python Code

```python
def selection_sort(arr):
    n = len(arr)
    for i in range(n):
        min_idx = i
        for j in range(i + 1, n):
            if arr[j] < arr[min_idx]:
                min_idx = j
        arr[i], arr[min_idx] = arr[min_idx], arr[i]
    return arr

# Example
arr = [64, 25, 12, 22, 11]
print("Sorted array:", selection_sort(arr))
