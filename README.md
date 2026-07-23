# Day 1
PROBLEM STATEMENT: Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

explanation

1.Start
2.Create an empty hash map.
3.Check each number in the array.
4.Find the required number (target - current number).
5.If the required number is in the hash map, return both indices.
6.Otherwise, store the current number and its index.
7.Repeat for all numbers.
8.If no answer is found, return an empty list.
9.Stop
------------------------------------------------------

# DAY 2

problem statement : You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list.

explanation :

1.Create a dummy node and set carry = 0.
2.Traverse both linked lists together.
3.Add the digits and the carry.
4.Store the last digit in a new node.
5.Update the carry.
6.Move to the next nodes.
7.Return dummy.next.

---------------------------------------------------

# DAY 3

problem statement: Given a string s, find the length of the longest substring without duplicate characters.

explanation:

1. Start.
2. Create an empty set.
3. Check each character in the string.
4. If the character is repeated, remove characters from the left.
5. Add the current character to the set.
6. Update the maximum length.
7. Return the maximum length.
8. Stop.
-----------------------------------------------------

# DAY 4

problem statement:  Given two sorted arrays nums1 and nums2 of size m and n respectively, return the median of the two sorted arrays.

explanation:

1.Start.
2.Combine the two arrays.
3.Sort the combined array.
4.Find the total number of elements.
5.If the number of elements is odd, return the middle element.
6.Otherwise, return the average of the two middle elements.
7.Stop.
-----------------------------------------------------