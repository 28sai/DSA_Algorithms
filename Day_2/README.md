# Day 2 - Binary Search 

##  Problem
Given a **sorted** array, find the index of a target element using Binary Search.

##  Algorithm
- Initialize `left` and `right` pointers.
- Find the `mid` index.
- If `arr[mid] == target`, return `mid`.
- Else adjust the search range and repeat.

##  Code
See: `binary_search.py`

##  Example
Input: `[5, 10, 15, 20, 25, 30]`, Target: `20`  
Output: `Element found at index 3`

##  Time Complexity
- Best: O(1)
- Worst: O(log n)

