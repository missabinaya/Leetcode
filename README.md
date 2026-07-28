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
# DAY 5

problem statement:Write a function that reverses a string. The input string is given as an array of characters s.

Explanation:

use python builtin function reverse() method to reverse the characters in the list
--------------------------------------------------------

# DAY 6

problem statement : Hint
Given an integer x, return true if x is a palindrome, and false otherwise.

 explanation:
 1.Take the integer x.
 2.Convert it into a string.
 3.Reverse the string using [::-1].
 4.Compare the original string and reversed string.
 5.If they are equal, return True; otherwise, return False
 
 --------------------------------------------------------

 # DAY 7 

 problem statement:Given a non-negative integer x, return the square root of x rounded down to the nearest integer. The returned integer should be non-negative as well

 explanation:
1.Take the input number x.
2.Find its square root using x ** 0.5.
3.Convert the result to an integer using int().
4.Return the integer value.
---------------------------------------------------------

# Day 8

problem statement: Given an integer array nums sorted in non-decreasing order, remove the duplicates in-place such that each unique element appears only once. The relative order of the elements should be kept the same.

Explanation:
1.Start.
2.Read the array nums.
3.Remove duplicate elements from the array.
4.Store only the unique elements in nums.
5.Count the number of unique elements.
6.Return the count (k).
7.Stop
--------------------------------------------------------------
# Day 9

problem statement:A phrase is a palindrome if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters include letters and numbers.