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

explanation:
1.Read the input string.
2.Convert all letters to lowercase.
3.Remove all characters except letters and numbers.
4.Reverse the cleaned string.
5.Compare the original cleaned string with the reversed string.
6.If both are the same, return True; otherwise, return False.
----------------------------------------------------------------

# Day 10

problem statement:Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.

Explanation:

1.Start.
2.Check each element in the array.
3.If the element is equal to or greater than the target, return its index.
4.If no such element is found, return the length of the array.
5.Stop.
----------------------------------------------------------------
# Day 11

problem statement:
Given an integer array nums and an integer val, remove all occurrences of val in nums in-place. The order of the elements may be changed. Then return the number of elements in nums which are not equal to val.

explanation:
### **Algorithm (Simple)**

1.Start.
2.Set `k = 0`.
3.Traverse each element in the array.
4.If the current element is **not equal to `val`**:
    Store it at index `k`.
    Increment `k` by 1.
5.Continue until all elements are checked.
6.Return `k`.
7.Stop.
----------------------------------------------------------------
# Day 12

problem statement:
Given the root of a binary tree, return the inorder traversal of its nodes' values.

explanation:
1.Start.
2.Create an empty list result.
3.Visit the left subtree.
4.Visit the root node and add its value to result.
5.Visit the right subtree.
6.Repeat until all nodes are visited.
7.Return result.
8.Stop.
----------------------------------------------------------------
# Day 13

problem statement:You are given a large integer represented as an integer array digits, where each digits[i] is the ith digit of the integer. The digits are ordered from most significant to least significant in left-to-right order. The large integer does not contain any leading 0's.

explanation:
1.Convert the list of digits into a number.
2.Add 1 to the number.
3.Convert the number back into a list of digits.
4.Return the new list.
----------------------------------------------------------------
   # Day 14

   problem statement:Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.

   explanation:
1.Set total = 0.
2.Read each Roman symbol.
3.If the current symbol is smaller than the next symbol, subtract it.
4.Otherwise, add it.
5.Return total.
---------------------------------------------------------------
# Day 15

problem statement:ou are given the heads of two sorted linked lists list1 and list2.Merge the two lists into one sorted list. The list should be made by splicing together the nodes of the first two lists.Return the head of the merged linked list.

explanation:

1.Start.
2.Create an empty list a.
3.Store all values from the first linked list into a.
4.Store all values from the second linked list into a.
5.Sort the list.
6.Create a new linked list using the sorted values.
7.Return the new linked list.
8.Stop.
----------------------------------------------------------------


 