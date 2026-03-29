🔢 3Sum Closest
📖 Problem Description

Given an integer array nums of length n and an integer target, find three integers in the array such that the sum is closest to the target.

Return the sum of the three integers.

You may assume each input has exactly one solution.

💡 Approach — Sorting + Two Pointers

To solve this efficiently:

Sort the array
Fix one element (i)
Use two pointers (left, right)
Calculate sum and compare with target
Update the closest sum accordingly
🚀 Algorithm Steps
Sort the array
Initialize closestSum with first three elements
Loop through array:
Fix index i
Set left = i + 1, right = n - 1
While left < right:
Calculate sum
Update closest sum if needed
Move pointers based on comparison
Return closestSum
