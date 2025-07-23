# Day 5 - Exponential Search 

##  Problem
Given a **sorted array**, find the target using Exponential Search, ideal when array size is large or unknown.

##  Algorithm
1. Check if target is at index 0.
2. Double the range until target is within bounds.
3. Perform Binary Search in that range.

##  Example
Input: `[3, 6, 9, 12, 15, 18, 21, 24]`, Target: `21`  
Output: `Element found at index 6`

##  Time Complexity
- Best: O(1)
- Worst: O(log i) → i is the index of target
