# Day 3 - Ternary Search 

##  Problem
Search for a target in a **sorted array** using Ternary Search by dividing the range into 3 parts.

##  Algorithm
- Calculate `mid1` and `mid2`
- Check if `arr[mid1]` or `arr[mid2]` is the target
- Decide which third to continue the search in

##  Example
Input: `[2, 5, 8, 12, 15, 20, 25]`, Target: `15`  
Output: `Element found at index 4`

##  Time Complexity
- Best: O(1)
- Worst: O(log₃ n)

##  Folder Structure:
