# Day 1
PROBLEM STATEMENT: Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

ALGORITHM:

1. Start
2. Create an empty hash map to store numbers and their indices.
3. Traverse the array nums using a loop.
4. For each element num at index i:
5. Calculate the complement:
6. Check if the complement already exists in the hash map.
7. If yes, return the indices 
8. If no, store the current number and its index in the hash map:
9. If no pair is found after traversing the entire array, return an empty list 
10. Stop
-------------------------------------------------------