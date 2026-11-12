# CAP2012 - Data Structures | Continuous Assessment 3 (CA3)
### LeetCode Problem Solving using C++ and GitHub Submission

**Student Registration Number:** `12513808`  
**Course Code:** CAP2012  
**Course Title:** Data Structures  
**Section:** D1P2505  
**Group:** Group 2  

---

##  Repository Overview

This repository contains full C++ solutions to the 16 assigned LeetCode problems covering **Units I to IV** (Basic Concepts, Arrays, Linked Lists, Stacks & Queues). Each solution includes:
1. Complete, standard LeetCode class implementation.
2. Local driver code (`main()` function) with test cases and assertions.
3. In-depth comments explaining the approach, algorithmic logic, and edge case handling.
4. Comprehensive Time and Space Complexity analysis.
5. Viva preparation notes with common follow-up questions.

---

##  Repository Directory Structure

```
CAP2012_CA3_LeetCode_12513808/
├── Easy/
│   ├── 01_LC088_MergeSortedArray_Easy.cpp
│   ├── 02_LC1281_SubtractProductAndSum_Easy.cpp
│   ├── 03_LC026_RemoveDuplicatesFromSortedArray_Easy.cpp
│   ├── 04_LC027_RemoveElement_Easy.cpp
│   ├── 05_LC509_FibonacciNumber_Easy.cpp
│   ├── 06_LC206_ReverseLinkedList_Easy.cpp
│   ├── 07_LC083_RemoveDuplicatesFromSortedList_Easy.cpp
│   ├── 08_LC020_ValidParentheses_Easy.cpp
│   └── 09_LC232_ImplementQueueUsingStacks_Easy.cpp
├── Medium/
│   ├── 10_LC189_RotateArray_Medium.cpp
│   ├── 11_LC092_ReverseLinkedListII_Medium.cpp
│   ├── 12_LC061_RotateList_Medium.cpp
│   ├── 13_LC155_MinStack_Medium.cpp
│   └── 14_LC622_DesignCircularQueue_Medium.cpp
├── Hard/
│   ├── 15_LC023_MergeKSortedLists_Hard.cpp
│   └── 16_LC032_LongestValidParentheses_Hard.cpp
└── README.md
```

---

##  Assigned LeetCode Questions Summary Table

| S.No | LeetCode # | Problem Name | Level | Unit | Data Structure / Algorithm | Time Complexity | Space Complexity |
|:---:|:---:|:---|:---:|:---:|:---|:---:|:---:|
| **01** | [88](https://leetcode.com/problems/merge-sorted-array/) | Merge Sorted Array | Easy | II | Three Pointers (Backwards Scan) | $O(m + n)$ | $O(1)$ |
| **02** | [1281](https://leetcode.com/problems/subtract-the-product-and-sum-of-digits-of-an-integer/) | Subtract the Product and Sum of Digits of an Integer | Easy | I | Loops, Modulo Arithmetic | $O(\log_{10} n)$ | $O(1)$ |
| **03** | [26](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | Remove Duplicates from Sorted Array | Easy | II | Two Pointers (Slow & Fast) | $O(n)$ | $O(1)$ |
| **04** | [27](https://leetcode.com/problems/remove-element/) | Remove Element | Easy | II | Two Pointers (Filter in-place) | $O(n)$ | $O(1)$ |
| **05** | [509](https://leetcode.com/problems/fibonacci-number/) | Fibonacci Number | Easy | IV | Recursion & DP (Iterative) | $O(n)$ | $O(1)$ |
| **06** | [206](https://leetcode.com/problems/reverse-linked-list/) | Reverse Linked List | Easy | III | Pointer Reversal (Iterative & Recursive) | $O(n)$ | $O(1)$ |
| **07** | [83](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) | Remove Duplicates from Sorted List | Easy | III | Singly Linked List Traversal & Deletion | $O(n)$ | $O(1)$ |
| **08** | [20](https://leetcode.com/problems/valid-parentheses/) | Valid Parentheses | Easy | IV | Stack (LIFO Matching) | $O(n)$ | $O(n)$ |
| **09** | [232](https://leetcode.com/problems/implement-queue-using-stacks/) | Implement Queue using Stacks | Easy | IV | Two Stacks (`inStack` & `outStack`) | Amortized $O(1)$ | $O(n)$ |
| **10** | [189](https://leetcode.com/problems/rotate-array/) | Rotate Array | Medium | II | Array 3-Step In-Place Reversal | $O(n)$ | $O(1)$ |
| **11** | [92](https://leetcode.com/problems/reverse-linked-list-ii/) | Reverse Linked List II | Medium | III | Sublist Reversal with Dummy Node | $O(n)$ | $O(1)$ |
| **12** | [61](https://leetcode.com/problems/rotate-list/) | Rotate List | Medium | III | Circular List / Ring Link Break | $O(n)$ | $O(1)$ |
| **13** | [155](https://leetcode.com/problems/min-stack/) | Min Stack | Medium | IV | Stack of Pairs `(val, minSoFar)` | $O(1)$ all ops | $O(n)$ |
| **14** | [622](https://leetcode.com/problems/design-circular-queue/) | Design Circular Queue | Medium | IV | Ring Buffer (Modulo Array Indexing) | $O(1)$ all ops | $O(k)$ |
| **15** | [23](https://leetcode.com/problems/merge-k-sorted-lists/) | Merge k Sorted Lists | Hard | III | Min-Heap (Priority Queue) | $O(N \log k)$ | $O(k)$ |
| **16** | [32](https://leetcode.com/problems/longest-valid-parentheses/) | Longest Valid Parentheses | Hard | IV | Stack with Index Boundaries | $O(n)$ | $O(n)$ |

---

## How to Compile and Run Locally

All source files are self-contained C++ programs. You can compile and test any solution using `g++`:

```bash
# Example: Running LC 88 (Easy)
g++ -std=c++17 Easy/01_LC088_MergeSortedArray_Easy.cpp -o run
./run

# Example: Running LC 189 (Medium)
g++ -std=c++17 Medium/10_LC189_RotateArray_Medium.cpp -o run
./run

# Example: Running LC 23 (Hard)
g++ -std=c++17 Hard/15_LC023_MergeKSortedLists_Hard.cpp -o run
./run
```

---


