# Day 1
PROBLEM STATEMENT: Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

algorithm:

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

algorithm:

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

algorithm:

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

algorithm:

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

algorithm:

use python builtin function reverse() method to reverse the characters in the list
--------------------------------------------------------

# DAY 6

problem statement : Hint
Given an integer x, return true if x is a palindrome, and false otherwise.

algorithm:
 1.Take the integer x.
 2.Convert it into a string.
 3.Reverse the string using [::-1].
 4.Compare the original string and reversed string.
 5.If they are equal, return True; otherwise, return False
 
 --------------------------------------------------------

 # DAY 7 

 problem statement:Given a non-negative integer x, return the square root of x rounded down to the nearest integer. The returned integer should be non-negative as well

algorithm:
1.If x is 0 or 1, return x.
2.Set left = 1 and right = x.
3.Find the middle number mid.
4.If mid × mid == x, return mid.
5.If mid × mid < x, search in the right half.
6.Otherwise, search in the left half.
7.When the loop ends, return right the integer square root
---------------------------------------------------------

# Day 8

problem statement: Given an integer array nums sorted in non-decreasing order, remove the duplicates in-place such that each unique element appears only once. The relative order of the elements should be kept the same.

algorithm:
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

algorithm:
1.Read the input string.
2.Convert all letters to lowercase.
3.Remove all characters except letters and numbers.
4.Reverse the cleaned string.
5.Compare the original cleaned string with the reversed string.
6.If both are the same, return True; otherwise, return False.
----------------------------------------------------------------

# Day 10

problem statement:Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.

algorithm:

1.Start.
2.Check each element in the array.
3.If the element is equal to or greater than the target, return its index.
4.If no such element is found, return the length of the array.
5.Stop.
----------------------------------------------------------------
# Day 11

problem statement:
Given an integer array nums and an integer val, remove all occurrences of val in nums in-place. The order of the elements may be changed. Then return the number of elements in nums which are not equal to val.

algorithm:
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

algorithm:
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

algorithm:
1.Convert the list of digits into a number.
2.Add 1 to the number.
3.Convert the number back into a list of digits.
4.Return the new list.
----------------------------------------------------------------
   # Day 14

   problem statement:Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.

  algorithm:
1.Set total = 0.
2.Read each Roman symbol.
3.If the current symbol is smaller than the next symbol, subtract it.
4.Otherwise, add it.
5.Return total.
---------------------------------------------------------------
# Day 15

problem statement:ou are given the heads of two sorted linked lists list1 and list2.Merge the two lists into one sorted list. The list should be made by splicing together the nodes of the first two lists.Return the head of the merged linked list.

algorithm:

1.Start.
2.Create an empty list a.
3.Store all values from the first linked list into a.
4.Store all values from the second linked list into a.
5.Sort the list.
6.Create a new linked list using the sorted values.
7.Return the new linked list.
8.Stop.
----------------------------------------------------------------
# Day 16

problem statement:Given an integer num, repeatedly add all its digits until the result has only one digit, and return it.

algorithm:

1.Start.
2.Input num.
3.While num is greater than 9:
4.Set sum = 0.
5.Add all the digits of num.
6.Store the result in num.
7.Return num.
8.Stop.
----------------------------------------------------------------
 # Day 17

 problem statement:Given two strings needle and haystack, return the index of the first occurrence of needle in haystack, or -1 if needle is not part of haystack.

 algorithm:
1.Start.
2.Read the input strings haystack and needle.
3.Search for the first occurrence of needle in haystack using the find() method.
4.If needle is found, return its starting index.
5.Otherwise, return -1.
6.Stop.
-----------------------------------------------------------------
# Day 18

problem statement:
Write a function to find the longest common prefix string amongst an array of strings.
If there is no common prefix, return an empty string "".

Algorithm:
1.Start
2.Take the first string as the prefix.
3.Compare the prefix with each remaining string.
4.If the string does not start with the prefix, remove the last character from prefix.
5.Repeat until the string starts with prefix.
6.If prefix becomes empty, return "".
7.After checking all strings, return prefix.
8.Stop
--------------------------------------------------------------------------------------------
# Day 19

problem statement:
You are given two integer arrays nums1 and nums2, sorted in non-decreasing order, and two integers m and n, representing the number of elements in nums1 and nums2 respectively.

algorithm:

1.Start
2.Take the last valid element of nums1.
3.Take the last element of nums2.
4.Compare both elements.
5.Put the larger element at the end of nums1.
6.Move the corresponding position backward.
7.Repeat until all elements of nums2 are merged.
8.Stop
-----------------------------------------------------------------
# Day 20

problem statement:
Given the head of a sorted linked list, delete all duplicates such that each element appears only once. Return the linked list sorted as well.

algorithm:
1.Start
2.Set current to the head of the list.
3.Check if current and current.next have the same value.
4.If they are the same, skip the duplicate node.
5.Otherwise, move current to the next node.
6.Repeat until the end of the list.
7.Return the head.
8.Stop
---------------------------------------------------------------
# Day 21

problem statement:
Given a string s consisting of words and spaces, return the length of the last word in the string.

algorithm:

1.Start.
2.Set i to the last character.
3.Skip spaces from the end.
4.Count characters until a space is found.
5.Return the count.
6.Stop.
-------------------------------------------------------
# Day 22

problem statement:Given two binary strings a and b, return their sum as a binary string

algorithm:
1.Convert binary a to decimal.
2.Convert binary b to decimal.
3.Add the two numbers.
4.Convert the sum back to binary.
5.Return the result.
-------------------------------------------------------

# Day 23

problem statement:You are climbing a staircase. It takes `n` steps to reach the top.
Each time you can either climb `1` or `2` steps. In how many distinct ways can you climb to the top?

algorithm:
1.Start
2.Read n.
3.If n <= 2, return n.
4.Set a = 1 and b = 2.
5.Repeat from 3 to n.
6.Calculate a, b = b, a + b.
7.Return b.
8.Stop
---------------------------------------------------------
# Day 24

problem statement:
Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid

Algorithm:

1.Start
2.Create an empty stack.
3.For each bracket:
4.Push opening brackets.
5.For closing brackets, check the top of stack.
6.If brackets don't match, return False.
7.If stack is empty at the end, return True.
8.Stop.
----------------------------------------------------------

# Day 25

problem statement:
Given a positive integer num, return true if num is a perfect square or false otherwise.

Algorithm:
1.Start with i = 1.
2.Check whether i × i == num.
3.If yes, return True.
4.If i × i > num, return False.
5.Otherwise, increase i by 1 and repeat
-----------------------------------------------------------
# Day 26

problem statement:


algorithm:
1.Start
2.Read integer n.
3.Create an empty list answer.
4.Repeat i from 1 to n.
5.If i is divisible by 3 and 5, add "FizzBuzz".
6.Else if i is divisible by 3, add "Fizz".
7.Else if i is divisible by 5, add "Buzz".
8.Otherwise, add i as a string.
9.Return answer.
10.Stop
------------------------------------------------------------