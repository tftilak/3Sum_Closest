# 3Sum Closest

## Problem Link
🔗 https://leetcode.com/problems/3sum-closest/

## Problem Statement
Given an integer array `nums` of length `n` and an integer `target`, find three integers in `nums` such that the sum is closest to `target`.

Return the sum of the three integers.

## Approach
1. Sort the array.
2. Fix one element using a loop.
3. Use the Two Pointer technique to find the closest sum.
4. Update the result whenever a closer sum is found.
5. Return immediately if an exact target match is found.

## Time Complexity
**O(n²)**

## Space Complexity
**O(1)**

## Example

**Input**
```text
nums = [-1, 2, 1, -4]
target = 1
