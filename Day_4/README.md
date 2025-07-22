# Day 4 - Jump Search 

##  Problem
Given a **sorted array**, efficiently find the index of a target using Jump Search.

##  Algorithm
- Choose block size as √n
- Jump forward block by block
- Perform linear search in identified block

##  Example
Input: `[1, 4, 7, 12, 15, 19, 24]`, Target: `19`  
Output: `Element found at index 5`

##  Time Complexity
- Best: O(1)
- Worst: O(√n)
