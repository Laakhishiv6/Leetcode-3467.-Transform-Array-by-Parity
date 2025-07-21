# Leetcode-3467.-Transform-Array-by-Parity

# Description
You are given an integer array nums. Transform nums by performing the following operations in the exact order specified:

Replace each even number with 0.
Replace each odd numbers with 1.
Sort the modified array in non-decreasing order.
Return the resulting array after performing these operations.
# Solution

1. We have been given an array of numbers.
2. Create an empty array named res
3. Loop through each element in the array and find whether the element is even or odd
4. If the number is even , replace it with 0
5. If the number is odd ,replace it with 1
6. add the values in res array
7. Sort res and return the array

Example
Input: nums = [4,3,2,1]
Output: [0,0,1,1]

nums=[4,3,2,1]
4 is even replace with 0
3 is odd replace with 1
2 is even replace with 0
1 is odd replace with 1

Output : [0,1,0,1]
After Sorting : [0,0,1,1]
