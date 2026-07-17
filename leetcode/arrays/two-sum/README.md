# Two Sum

## Problem

Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

---

## Brute Force

Compare every pair of numbers.

Time Complexity: O(n²)

Space Complexity: O(1)

---

## Optimized Approach

Use a HashMap to store previously seen numbers and their indices.

Time Complexity: O(n)

Space Complexity: O(n)

---

## Key Learning

HashMap provides constant-time lookup, making it possible to find the complement (`target - current`) efficiently.
