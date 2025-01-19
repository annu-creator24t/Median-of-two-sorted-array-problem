Median of Two Sorted Arrays.
This problem involves finding the median of two sorted arrays nums1 and nums2 with a time complexity of O(log(min(m, n))).

Problem Statement:
Given two sorted arrays, find the median of the merged sorted array. The overall runtime complexity must be optimized.

Examples:
Input: nums1 = [1, 3], nums2 = [2]
Output: 2.0
Explanation: The merged array is [1, 2, 3], and the median is 2.

Input: nums1 = [1, 2], nums2 = [3, 4]
Output: 2.5
Explanation: The merged array is [1, 2, 3, 4], and the median is (2 + 3) / 2 = 2.5.

Constraints:
The arrays are sorted.
Sizes of arrays can be zero or non-zero.
Must use a binary search approach for optimization.
Approach
The solution uses binary search on the smaller array to partition both arrays into two halves and calculate the median efficiently.
