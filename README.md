# DSA-Sheet
# 🚀 DSA Zero to Hero Sheet

> A structured, topic-wise Data Structures & Algorithms sheet: **20 topics x 15 problems = 300 hand-picked LeetCode problems**, ordered from fundamentals to hard.

![Problems](https://img.shields.io/badge/Problems-300-blue) ![Topics](https://img.shields.io/badge/Topics-20-green) ![Platform](https://img.shields.io/badge/Platform-LeetCode-orange)

## 👋 About Me

Hi, I'm **Krishu Prajapati**, a BCA student who loves coding and solves problems every single day. I built this sheet for all my fellow techies, friends and juniors who want to learn DSA the right way.

If you follow it topic by topic, your grip on DSA will become **strong**: you'll be able to solve problems on your own, and you'll feel **confident** when a brand-new problem shows up. 💪

> *Consistency beats intensity. Solve a little every day, and the patterns will start to click.*

## 📌 How to Use This Sheet

1. Go **topic by topic** in the given order; each topic builds on the previous ones.
2. Inside a topic, solve in this order: **Basic → Easy → Medium → Hard**.
3. Read the *Concept* and *Patterns* first, then attempt problems **without hints for 20-30 minutes**.
4. Stuck? Study the pattern, then re-solve the same problem **from scratch after 3 days**.
5. Tick the checkbox (`☐` → `☑`) in your own fork as you go.

**Per-topic structure**

| Level | Count | Goal |
|---|:-:|---|
| 🟢 Basic | 5 | Learn the syntax, traversal and core idea |
| 🟡 Easy | 4 | Apply the idea with one twist |
| 🟠 Medium | 4 | Combine patterns, interview-standard questions |
| 🔴 Hard | 2 | Optimization and edge-case mastery |

> Levels reflect this sheet's learning progression; the official LeetCode difficulty tag on a few problems can differ by one level.

## 📚 Table of Contents

1. [Arrays](#1-arrays)
2. [Strings](#2-strings)
3. [Two Pointers & Sliding Window](#3-two-pointers--sliding-window)
4. [Hashing (HashMap / HashSet)](#4-hashing-hashmap--hashset)
5. [Prefix Sum & Difference Array](#5-prefix-sum--difference-array)
6. [Binary Search](#6-binary-search)
7. [Sorting](#7-sorting)
8. [Recursion & Backtracking](#8-recursion--backtracking)
9. [Linked List](#9-linked-list)
10. [Stack](#10-stack)
11. [Queue, Deque & BFS Basics](#11-queue-deque--bfs-basics)
12. [Binary Trees](#12-binary-trees)
13. [Binary Search Tree (BST)](#13-binary-search-tree-bst)
14. [Heap / Priority Queue](#14-heap--priority-queue)
15. [Greedy](#15-greedy)
16. [Dynamic Programming](#16-dynamic-programming)
17. [Graphs (BFS / DFS / Topological)](#17-graphs-bfs--dfs--topological)
18. [Bit Manipulation](#18-bit-manipulation)
19. [Math & Number Theory](#19-math--number-theory)
20. [Matrix / 2D Arrays](#20-matrix--2d-arrays)

## 🗓️ Suggested 12-Week Plan

| Week | Topics |
|:-:|---|
| 1 | Arrays, Strings |
| 2 | Two Pointers & Sliding Window, Hashing |
| 3 | Prefix Sum, Binary Search |
| 4 | Sorting, Recursion & Backtracking |
| 5 | Linked List, Stack |
| 6 | Queue & Deque, Binary Trees |
| 7 | BST, Heap |
| 8 | Greedy |
| 9-10 | Dynamic Programming |
| 11 | Graphs |
| 12 | Bit Manipulation, Math, Matrix + revision |

---

## 1. Arrays

**📖 Concept:** Contiguous block of memory holding same-type elements; O(1) random access, O(n) insert/delete in the middle. Almost every interview problem starts as an array problem.

**🧩 Patterns:** Traversal, in-place modification, Kadane's algorithm, prefix/suffix products, cyclic placement, reverse-trick rotation.

**⏱️ Complexity cheat-sheet:** Access O(1) | Search O(n) | Insert/Delete O(n)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Richest Customer Wealth | [Solve](https://leetcode.com/problems/richest-customer-wealth/) |
| ☐ | 2 | Running Sum of 1d Array | [Solve](https://leetcode.com/problems/running-sum-of-1d-array/) |
| ☐ | 3 | Shuffle the Array | [Solve](https://leetcode.com/problems/shuffle-the-array/) |
| ☐ | 4 | Concatenation of Array | [Solve](https://leetcode.com/problems/concatenation-of-array/) |
| ☐ | 5 | Build Array from Permutation | [Solve](https://leetcode.com/problems/build-array-from-permutation/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Remove Duplicates from Sorted Array | [Solve](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) |
| ☐ | 2 | Move Zeroes | [Solve](https://leetcode.com/problems/move-zeroes/) |
| ☐ | 3 | Best Time to Buy and Sell Stock | [Solve](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) |
| ☐ | 4 | Majority Element | [Solve](https://leetcode.com/problems/majority-element/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Maximum Subarray | [Solve](https://leetcode.com/problems/maximum-subarray/) |
| ☐ | 2 | Product of Array Except Self | [Solve](https://leetcode.com/problems/product-of-array-except-self/) |
| ☐ | 3 | Rotate Array | [Solve](https://leetcode.com/problems/rotate-array/) |
| ☐ | 4 | Next Permutation | [Solve](https://leetcode.com/problems/next-permutation/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | First Missing Positive | [Solve](https://leetcode.com/problems/first-missing-positive/) |
| ☐ | 2 | Trapping Rain Water | [Solve](https://leetcode.com/problems/trapping-rain-water/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 2. Strings

**📖 Concept:** Sequence of characters (immutable in Java/Python, mutable in C++). Treat them as char arrays plus frequency tables.

**🧩 Patterns:** Frequency count, two pointers, expand-around-center, sliding window, simulation/parsing.

**⏱️ Complexity cheat-sheet:** Traversal O(n) | Concatenation in a loop O(n^2) if careless

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Reverse String | [Solve](https://leetcode.com/problems/reverse-string/) |
| ☐ | 2 | Valid Palindrome | [Solve](https://leetcode.com/problems/valid-palindrome/) |
| ☐ | 3 | Length of Last Word | [Solve](https://leetcode.com/problems/length-of-last-word/) |
| ☐ | 4 | To Lower Case | [Solve](https://leetcode.com/problems/to-lower-case/) |
| ☐ | 5 | Defanging an Ip Address | [Solve](https://leetcode.com/problems/defanging-an-ip-address/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Valid Anagram | [Solve](https://leetcode.com/problems/valid-anagram/) |
| ☐ | 2 | Longest Common Prefix | [Solve](https://leetcode.com/problems/longest-common-prefix/) |
| ☐ | 3 | Is Subsequence | [Solve](https://leetcode.com/problems/is-subsequence/) |
| ☐ | 4 | Isomorphic Strings | [Solve](https://leetcode.com/problems/isomorphic-strings/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Longest Substring Without Repeating Characters | [Solve](https://leetcode.com/problems/longest-substring-without-repeating-characters/) |
| ☐ | 2 | Longest Palindromic Substring | [Solve](https://leetcode.com/problems/longest-palindromic-substring/) |
| ☐ | 3 | Group Anagrams | [Solve](https://leetcode.com/problems/group-anagrams/) |
| ☐ | 4 | String to Integer (atoi) | [Solve](https://leetcode.com/problems/string-to-integer-atoi/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Minimum Window Substring | [Solve](https://leetcode.com/problems/minimum-window-substring/) |
| ☐ | 2 | Shortest Palindrome | [Solve](https://leetcode.com/problems/shortest-palindrome/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 3. Two Pointers & Sliding Window

**📖 Concept:** Two indices move through data to avoid nested loops. Sliding window keeps a running state of a contiguous range (fixed or variable size).

**🧩 Patterns:** Opposite-end pointers, fast/slow, fixed window, variable window with hashmap, monotonic deque.

**⏱️ Complexity cheat-sheet:** Usually O(n) time, O(1) or O(k) space

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Two Sum II - Input Array Is Sorted | [Solve](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) |
| ☐ | 2 | Squares of a Sorted Array | [Solve](https://leetcode.com/problems/squares-of-a-sorted-array/) |
| ☐ | 3 | Merge Sorted Array | [Solve](https://leetcode.com/problems/merge-sorted-array/) |
| ☐ | 4 | Reverse Vowels of a String | [Solve](https://leetcode.com/problems/reverse-vowels-of-a-string/) |
| ☐ | 5 | Valid Palindrome II | [Solve](https://leetcode.com/problems/valid-palindrome-ii/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Maximum Average Subarray I | [Solve](https://leetcode.com/problems/maximum-average-subarray-i/) |
| ☐ | 2 | Contains Duplicate II | [Solve](https://leetcode.com/problems/contains-duplicate-ii/) |
| ☐ | 3 | Backspace String Compare | [Solve](https://leetcode.com/problems/backspace-string-compare/) |
| ☐ | 4 | Minimum Difference Between Highest and Lowest of K Scores | [Solve](https://leetcode.com/problems/minimum-difference-between-highest-and-lowest-of-k-scores/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | 3Sum | [Solve](https://leetcode.com/problems/3sum/) |
| ☐ | 2 | Container with Most Water | [Solve](https://leetcode.com/problems/container-with-most-water/) |
| ☐ | 3 | Longest Repeating Character Replacement | [Solve](https://leetcode.com/problems/longest-repeating-character-replacement/) |
| ☐ | 4 | Minimum Size Subarray Sum | [Solve](https://leetcode.com/problems/minimum-size-subarray-sum/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Sliding Window Maximum | [Solve](https://leetcode.com/problems/sliding-window-maximum/) |
| ☐ | 2 | Substring with Concatenation of All Words | [Solve](https://leetcode.com/problems/substring-with-concatenation-of-all-words/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 4. Hashing (HashMap / HashSet)

**📖 Concept:** Key-value lookup in average O(1) using a hash function. Trades memory for speed.

**🧩 Patterns:** Frequency map, complement lookup, seen-set, prefix-sum + map, bucket/canonical-form keys, design problems.

**⏱️ Complexity cheat-sheet:** Insert/Search/Delete O(1) average, O(n) worst

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Contains Duplicate | [Solve](https://leetcode.com/problems/contains-duplicate/) |
| ☐ | 2 | Two Sum | [Solve](https://leetcode.com/problems/two-sum/) |
| ☐ | 3 | Ransom Note | [Solve](https://leetcode.com/problems/ransom-note/) |
| ☐ | 4 | Jewels and Stones | [Solve](https://leetcode.com/problems/jewels-and-stones/) |
| ☐ | 5 | First Unique Character in a String | [Solve](https://leetcode.com/problems/first-unique-character-in-a-string/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Intersection of Two Arrays | [Solve](https://leetcode.com/problems/intersection-of-two-arrays/) |
| ☐ | 2 | Happy Number | [Solve](https://leetcode.com/problems/happy-number/) |
| ☐ | 3 | Word Pattern | [Solve](https://leetcode.com/problems/word-pattern/) |
| ☐ | 4 | Find the Difference | [Solve](https://leetcode.com/problems/find-the-difference/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Top K Frequent Elements | [Solve](https://leetcode.com/problems/top-k-frequent-elements/) |
| ☐ | 2 | Longest Consecutive Sequence | [Solve](https://leetcode.com/problems/longest-consecutive-sequence/) |
| ☐ | 3 | Subarray Sum Equals K | [Solve](https://leetcode.com/problems/subarray-sum-equals-k/) |
| ☐ | 4 | 4Sum II | [Solve](https://leetcode.com/problems/4sum-ii/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Max Points on a Line | [Solve](https://leetcode.com/problems/max-points-on-a-line/) |
| ☐ | 2 | LFU Cache | [Solve](https://leetcode.com/problems/lfu-cache/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 5. Prefix Sum & Difference Array

**📖 Concept:** Precompute cumulative sums so any range sum becomes prefix[r] - prefix[l-1] in O(1).

**🧩 Patterns:** 1D/2D prefix, running balance, prefix + hashmap, pivot index, split-point counting.

**⏱️ Complexity cheat-sheet:** Build O(n) | Query O(1)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Range Sum Query Immutable | [Solve](https://leetcode.com/problems/range-sum-query-immutable/) |
| ☐ | 2 | Find Pivot Index | [Solve](https://leetcode.com/problems/find-pivot-index/) |
| ☐ | 3 | Find the Highest Altitude | [Solve](https://leetcode.com/problems/find-the-highest-altitude/) |
| ☐ | 4 | Left and Right Sum Differences | [Solve](https://leetcode.com/problems/left-and-right-sum-differences/) |
| ☐ | 5 | Sum of All Odd Length Subarrays | [Solve](https://leetcode.com/problems/sum-of-all-odd-length-subarrays/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Minimum Value to Get Positive Step by Step Sum | [Solve](https://leetcode.com/problems/minimum-value-to-get-positive-step-by-step-sum/) |
| ☐ | 2 | Maximum Score after Splitting a String | [Solve](https://leetcode.com/problems/maximum-score-after-splitting-a-string/) |
| ☐ | 3 | Check if All the Integers in a Range Are Covered | [Solve](https://leetcode.com/problems/check-if-all-the-integers-in-a-range-are-covered/) |
| ☐ | 4 | Find the Distinct Difference Array | [Solve](https://leetcode.com/problems/find-the-distinct-difference-array/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Contiguous Array | [Solve](https://leetcode.com/problems/contiguous-array/) |
| ☐ | 2 | Continuous Subarray Sum | [Solve](https://leetcode.com/problems/continuous-subarray-sum/) |
| ☐ | 3 | Range Sum Query 2d Immutable | [Solve](https://leetcode.com/problems/range-sum-query-2d-immutable/) |
| ☐ | 4 | Count Number of Nice Subarrays | [Solve](https://leetcode.com/problems/count-number-of-nice-subarrays/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Maximum Sum of 3 Non Overlapping Subarrays | [Solve](https://leetcode.com/problems/maximum-sum-of-3-non-overlapping-subarrays/) |
| ☐ | 2 | Count of Range Sum | [Solve](https://leetcode.com/problems/count-of-range-sum/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 6. Binary Search

**📖 Concept:** Halve the search space each step on sorted or monotonic data. Also works on the answer itself ('binary search on answer').

**🧩 Patterns:** Classic search, lower/upper bound, rotated array, peak finding, binary search on answer space.

**⏱️ Complexity cheat-sheet:** O(log n) time, O(1) space

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Binary Search | [Solve](https://leetcode.com/problems/binary-search/) |
| ☐ | 2 | Search Insert Position | [Solve](https://leetcode.com/problems/search-insert-position/) |
| ☐ | 3 | Sqrt(x) | [Solve](https://leetcode.com/problems/sqrtx/) |
| ☐ | 4 | First Bad Version | [Solve](https://leetcode.com/problems/first-bad-version/) |
| ☐ | 5 | Guess Number Higher or Lower | [Solve](https://leetcode.com/problems/guess-number-higher-or-lower/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Valid Perfect Square | [Solve](https://leetcode.com/problems/valid-perfect-square/) |
| ☐ | 2 | Arranging Coins | [Solve](https://leetcode.com/problems/arranging-coins/) |
| ☐ | 3 | Find Smallest Letter Greater than Target | [Solve](https://leetcode.com/problems/find-smallest-letter-greater-than-target/) |
| ☐ | 4 | Special Array with X Elements Greater than or Equal X | [Solve](https://leetcode.com/problems/special-array-with-x-elements-greater-than-or-equal-x/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Search in Rotated Sorted Array | [Solve](https://leetcode.com/problems/search-in-rotated-sorted-array/) |
| ☐ | 2 | Find First and Last Position of Element in Sorted Array | [Solve](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/) |
| ☐ | 3 | Find Peak Element | [Solve](https://leetcode.com/problems/find-peak-element/) |
| ☐ | 4 | Koko Eating Bananas | [Solve](https://leetcode.com/problems/koko-eating-bananas/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Median of Two Sorted Arrays | [Solve](https://leetcode.com/problems/median-of-two-sorted-arrays/) |
| ☐ | 2 | Split Array Largest Sum | [Solve](https://leetcode.com/problems/split-array-largest-sum/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 7. Sorting

**📖 Concept:** Arrange data in order so later steps (two pointers, greedy, binary search) become easy. Know merge sort, quick sort and counting sort cold.

**🧩 Patterns:** Custom comparators, sort + scan, counting sort, merge-sort-based counting (inversions), partition (Dutch flag).

**⏱️ Complexity cheat-sheet:** Comparison sort O(n log n) | Counting sort O(n + k)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Height Checker | [Solve](https://leetcode.com/problems/height-checker/) |
| ☐ | 2 | Relative Sort Array | [Solve](https://leetcode.com/problems/relative-sort-array/) |
| ☐ | 3 | Sort Array by Parity | [Solve](https://leetcode.com/problems/sort-array-by-parity/) |
| ☐ | 4 | Sort the People | [Solve](https://leetcode.com/problems/sort-the-people/) |
| ☐ | 5 | Sort Integers by the Number of 1 Bits | [Solve](https://leetcode.com/problems/sort-integers-by-the-number-of-1-bits/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Array Partition | [Solve](https://leetcode.com/problems/array-partition/) |
| ☐ | 2 | Maximum Product of Three Numbers | [Solve](https://leetcode.com/problems/maximum-product-of-three-numbers/) |
| ☐ | 3 | Third Maximum Number | [Solve](https://leetcode.com/problems/third-maximum-number/) |
| ☐ | 4 | Minimum Absolute Difference | [Solve](https://leetcode.com/problems/minimum-absolute-difference/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Sort Colors | [Solve](https://leetcode.com/problems/sort-colors/) |
| ☐ | 2 | Merge Intervals | [Solve](https://leetcode.com/problems/merge-intervals/) |
| ☐ | 3 | Kth Largest Element in an Array | [Solve](https://leetcode.com/problems/kth-largest-element-in-an-array/) |
| ☐ | 4 | Largest Number | [Solve](https://leetcode.com/problems/largest-number/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Count of Smaller Numbers after Self | [Solve](https://leetcode.com/problems/count-of-smaller-numbers-after-self/) |
| ☐ | 2 | Reverse Pairs | [Solve](https://leetcode.com/problems/reverse-pairs/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 8. Recursion & Backtracking

**📖 Concept:** A function calls itself on a smaller input. Backtracking = recursion + choose, explore, un-choose to enumerate all valid solutions.

**🧩 Patterns:** Base case + recurrence, subsets/permutations/combinations template, pruning, constraint grids.

**⏱️ Complexity cheat-sheet:** Backtracking is often O(2^n) or O(n!); depth = stack space

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Fibonacci Number | [Solve](https://leetcode.com/problems/fibonacci-number/) |
| ☐ | 2 | Power of Two | [Solve](https://leetcode.com/problems/power-of-two/) |
| ☐ | 3 | Power of Three | [Solve](https://leetcode.com/problems/power-of-three/) |
| ☐ | 4 | Power of Four | [Solve](https://leetcode.com/problems/power-of-four/) |
| ☐ | 5 | Pascal's Triangle | [Solve](https://leetcode.com/problems/pascals-triangle/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Pascal's Triangle II | [Solve](https://leetcode.com/problems/pascals-triangle-ii/) |
| ☐ | 2 | Binary Watch | [Solve](https://leetcode.com/problems/binary-watch/) |
| ☐ | 3 | Sum of All Subset Xor Totals | [Solve](https://leetcode.com/problems/sum-of-all-subset-xor-totals/) |
| ☐ | 4 | Maximum Nesting Depth of the Parentheses | [Solve](https://leetcode.com/problems/maximum-nesting-depth-of-the-parentheses/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Subsets | [Solve](https://leetcode.com/problems/subsets/) |
| ☐ | 2 | Permutations | [Solve](https://leetcode.com/problems/permutations/) |
| ☐ | 3 | Combination Sum | [Solve](https://leetcode.com/problems/combination-sum/) |
| ☐ | 4 | Generate Parentheses | [Solve](https://leetcode.com/problems/generate-parentheses/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | N-Queens | [Solve](https://leetcode.com/problems/n-queens/) |
| ☐ | 2 | Sudoku Solver | [Solve](https://leetcode.com/problems/sudoku-solver/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 9. Linked List

**📖 Concept:** Nodes connected by pointers. O(1) insert/delete when you hold the node, O(n) access. Pointer manipulation is the whole skill.

**🧩 Patterns:** Dummy head, fast/slow pointers, in-place reversal, merge, Floyd cycle detection.

**⏱️ Complexity cheat-sheet:** Access O(n) | Insert/Delete at known node O(1)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Reverse Linked List | [Solve](https://leetcode.com/problems/reverse-linked-list/) |
| ☐ | 2 | Middle of the Linked List | [Solve](https://leetcode.com/problems/middle-of-the-linked-list/) |
| ☐ | 3 | Merge Two Sorted Lists | [Solve](https://leetcode.com/problems/merge-two-sorted-lists/) |
| ☐ | 4 | Remove Linked List Elements | [Solve](https://leetcode.com/problems/remove-linked-list-elements/) |
| ☐ | 5 | Delete Node in a Linked List | [Solve](https://leetcode.com/problems/delete-node-in-a-linked-list/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Linked List Cycle | [Solve](https://leetcode.com/problems/linked-list-cycle/) |
| ☐ | 2 | Palindrome Linked List | [Solve](https://leetcode.com/problems/palindrome-linked-list/) |
| ☐ | 3 | Intersection of Two Linked Lists | [Solve](https://leetcode.com/problems/intersection-of-two-linked-lists/) |
| ☐ | 4 | Remove Duplicates from Sorted List | [Solve](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Add Two Numbers | [Solve](https://leetcode.com/problems/add-two-numbers/) |
| ☐ | 2 | Remove Nth Node from End of List | [Solve](https://leetcode.com/problems/remove-nth-node-from-end-of-list/) |
| ☐ | 3 | Linked List Cycle II | [Solve](https://leetcode.com/problems/linked-list-cycle-ii/) |
| ☐ | 4 | Reorder List | [Solve](https://leetcode.com/problems/reorder-list/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Reverse Nodes in K Group | [Solve](https://leetcode.com/problems/reverse-nodes-in-k-group/) |
| ☐ | 2 | Merge K Sorted Lists | [Solve](https://leetcode.com/problems/merge-k-sorted-lists/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 10. Stack

**📖 Concept:** LIFO structure. Perfect for matching, undo, nested structures and 'next greater/smaller' via a monotonic stack.

**🧩 Patterns:** Bracket matching, monotonic stack, expression evaluation, stack simulation.

**⏱️ Complexity cheat-sheet:** Push/Pop/Peek O(1)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Valid Parentheses | [Solve](https://leetcode.com/problems/valid-parentheses/) |
| ☐ | 2 | Baseball Game | [Solve](https://leetcode.com/problems/baseball-game/) |
| ☐ | 3 | Make the String Great | [Solve](https://leetcode.com/problems/make-the-string-great/) |
| ☐ | 4 | Remove Outermost Parentheses | [Solve](https://leetcode.com/problems/remove-outermost-parentheses/) |
| ☐ | 5 | Final Prices with a Special Discount in a Shop | [Solve](https://leetcode.com/problems/final-prices-with-a-special-discount-in-a-shop/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Next Greater Element I | [Solve](https://leetcode.com/problems/next-greater-element-i/) |
| ☐ | 2 | Implement Queue Using Stacks | [Solve](https://leetcode.com/problems/implement-queue-using-stacks/) |
| ☐ | 3 | Remove All Adjacent Duplicates in String | [Solve](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) |
| ☐ | 4 | Implement Stack Using Queues | [Solve](https://leetcode.com/problems/implement-stack-using-queues/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Min Stack | [Solve](https://leetcode.com/problems/min-stack/) |
| ☐ | 2 | Daily Temperatures | [Solve](https://leetcode.com/problems/daily-temperatures/) |
| ☐ | 3 | Evaluate Reverse Polish Notation | [Solve](https://leetcode.com/problems/evaluate-reverse-polish-notation/) |
| ☐ | 4 | Decode String | [Solve](https://leetcode.com/problems/decode-string/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Largest Rectangle in Histogram | [Solve](https://leetcode.com/problems/largest-rectangle-in-histogram/) |
| ☐ | 2 | Basic Calculator | [Solve](https://leetcode.com/problems/basic-calculator/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 11. Queue, Deque & BFS Basics

**📖 Concept:** FIFO structure. Deque allows both-end operations. Queue drives BFS and level-order processing.

**🧩 Patterns:** Simulation, level-order BFS, circular queue, monotonic deque, multi-source BFS.

**⏱️ Complexity cheat-sheet:** Enqueue/Dequeue O(1)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Number of Recent Calls | [Solve](https://leetcode.com/problems/number-of-recent-calls/) |
| ☐ | 2 | Time Needed to Buy Tickets | [Solve](https://leetcode.com/problems/time-needed-to-buy-tickets/) |
| ☐ | 3 | Number of Students Unable to Eat Lunch | [Solve](https://leetcode.com/problems/number-of-students-unable-to-eat-lunch/) |
| ☐ | 4 | Average Waiting Time | [Solve](https://leetcode.com/problems/average-waiting-time/) |
| ☐ | 5 | Find the Winner of the Circular Game | [Solve](https://leetcode.com/problems/find-the-winner-of-the-circular-game/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Binary Tree Level Order Traversal II | [Solve](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/) |
| ☐ | 2 | Average of Levels in Binary Tree | [Solve](https://leetcode.com/problems/average-of-levels-in-binary-tree/) |
| ☐ | 3 | Minimum Depth of Binary Tree | [Solve](https://leetcode.com/problems/minimum-depth-of-binary-tree/) |
| ☐ | 4 | Cousins in Binary Tree | [Solve](https://leetcode.com/problems/cousins-in-binary-tree/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Design Circular Queue | [Solve](https://leetcode.com/problems/design-circular-queue/) |
| ☐ | 2 | Dota2 Senate | [Solve](https://leetcode.com/problems/dota2-senate/) |
| ☐ | 3 | Reveal Cards in Increasing Order | [Solve](https://leetcode.com/problems/reveal-cards-in-increasing-order/) |
| ☐ | 4 | Open the Lock | [Solve](https://leetcode.com/problems/open-the-lock/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Shortest Subarray with Sum at Least K | [Solve](https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/) |
| ☐ | 2 | Constrained Subsequence Sum | [Solve](https://leetcode.com/problems/constrained-subsequence-sum/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 12. Binary Trees

**📖 Concept:** Hierarchical structure, each node has up to two children. Most tree problems are DFS recursion (return info upward) or BFS by level.

**🧩 Patterns:** Pre/in/post-order, level-order, height/diameter via post-order, LCA, construct from traversals, path problems.

**⏱️ Complexity cheat-sheet:** Traversal O(n) | Space O(h) recursion

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Maximum Depth of Binary Tree | [Solve](https://leetcode.com/problems/maximum-depth-of-binary-tree/) |
| ☐ | 2 | Invert Binary Tree | [Solve](https://leetcode.com/problems/invert-binary-tree/) |
| ☐ | 3 | Same Tree | [Solve](https://leetcode.com/problems/same-tree/) |
| ☐ | 4 | Symmetric Tree | [Solve](https://leetcode.com/problems/symmetric-tree/) |
| ☐ | 5 | Binary Tree Inorder Traversal | [Solve](https://leetcode.com/problems/binary-tree-inorder-traversal/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Path Sum | [Solve](https://leetcode.com/problems/path-sum/) |
| ☐ | 2 | Diameter of Binary Tree | [Solve](https://leetcode.com/problems/diameter-of-binary-tree/) |
| ☐ | 3 | Balanced Binary Tree | [Solve](https://leetcode.com/problems/balanced-binary-tree/) |
| ☐ | 4 | Subtree of Another Tree | [Solve](https://leetcode.com/problems/subtree-of-another-tree/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Binary Tree Level Order Traversal | [Solve](https://leetcode.com/problems/binary-tree-level-order-traversal/) |
| ☐ | 2 | Lowest Common Ancestor of a Binary Tree | [Solve](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) |
| ☐ | 3 | Binary Tree Right Side View | [Solve](https://leetcode.com/problems/binary-tree-right-side-view/) |
| ☐ | 4 | Construct Binary Tree from Preorder and Inorder Traversal | [Solve](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Binary Tree Maximum Path Sum | [Solve](https://leetcode.com/problems/binary-tree-maximum-path-sum/) |
| ☐ | 2 | Serialize and Deserialize Binary Tree | [Solve](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 13. Binary Search Tree (BST)

**📖 Concept:** Binary tree where left < node < right. Inorder traversal gives sorted order; search/insert/delete are O(h).

**🧩 Patterns:** Inorder = sorted, bounds validation, successor/predecessor, build from sorted array, BST iterators.

**⏱️ Complexity cheat-sheet:** Balanced O(log n) | Skewed O(n)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Search in a Binary Search Tree | [Solve](https://leetcode.com/problems/search-in-a-binary-search-tree/) |
| ☐ | 2 | Range Sum of BST | [Solve](https://leetcode.com/problems/range-sum-of-bst/) |
| ☐ | 3 | Minimum Absolute Difference in BST | [Solve](https://leetcode.com/problems/minimum-absolute-difference-in-bst/) |
| ☐ | 4 | Convert Sorted Array to Binary Search Tree | [Solve](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) |
| ☐ | 5 | Increasing Order Search Tree | [Solve](https://leetcode.com/problems/increasing-order-search-tree/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Lowest Common Ancestor of a Binary Search Tree | [Solve](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) |
| ☐ | 2 | Two Sum IV - Input is a BST | [Solve](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) |
| ☐ | 3 | Trim a Binary Search Tree | [Solve](https://leetcode.com/problems/trim-a-binary-search-tree/) |
| ☐ | 4 | Find Mode in Binary Search Tree | [Solve](https://leetcode.com/problems/find-mode-in-binary-search-tree/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Validate Binary Search Tree | [Solve](https://leetcode.com/problems/validate-binary-search-tree/) |
| ☐ | 2 | Kth Smallest Element in a BST | [Solve](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) |
| ☐ | 3 | Delete Node in a BST | [Solve](https://leetcode.com/problems/delete-node-in-a-bst/) |
| ☐ | 4 | Recover Binary Search Tree | [Solve](https://leetcode.com/problems/recover-binary-search-tree/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Maximum Sum BST in Binary Tree | [Solve](https://leetcode.com/problems/maximum-sum-bst-in-binary-tree/) |
| ☐ | 2 | Create Sorted Array Through Instructions | [Solve](https://leetcode.com/problems/create-sorted-array-through-instructions/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 14. Heap / Priority Queue

**📖 Concept:** Complete binary tree giving O(1) access to min or max and O(log n) insert/remove. Go-to for top-K, streaming and scheduling.

**🧩 Patterns:** Top-K with size-K heap, two heaps (median), merge K sorted, greedy + heap, lazy deletion.

**⏱️ Complexity cheat-sheet:** Push/Pop O(log n) | Peek O(1) | Heapify O(n)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Last Stone Weight | [Solve](https://leetcode.com/problems/last-stone-weight/) |
| ☐ | 2 | Kth Largest Element in a Stream | [Solve](https://leetcode.com/problems/kth-largest-element-in-a-stream/) |
| ☐ | 3 | Relative Ranks | [Solve](https://leetcode.com/problems/relative-ranks/) |
| ☐ | 4 | The K Weakest Rows in a Matrix | [Solve](https://leetcode.com/problems/the-k-weakest-rows-in-a-matrix/) |
| ☐ | 5 | Maximum Product of Two Elements in an Array | [Solve](https://leetcode.com/problems/maximum-product-of-two-elements-in-an-array/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Find Subsequence of Length K with the Largest Sum | [Solve](https://leetcode.com/problems/find-subsequence-of-length-k-with-the-largest-sum/) |
| ☐ | 2 | Minimum Cost of Buying Candies with Discount | [Solve](https://leetcode.com/problems/minimum-cost-of-buying-candies-with-discount/) |
| ☐ | 3 | Take Gifts from the Richest Pile | [Solve](https://leetcode.com/problems/take-gifts-from-the-richest-pile/) |
| ☐ | 4 | Kth Distinct String in an Array | [Solve](https://leetcode.com/problems/kth-distinct-string-in-an-array/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | K Closest Points to Origin | [Solve](https://leetcode.com/problems/k-closest-points-to-origin/) |
| ☐ | 2 | Task Scheduler | [Solve](https://leetcode.com/problems/task-scheduler/) |
| ☐ | 3 | Sort Characters by Frequency | [Solve](https://leetcode.com/problems/sort-characters-by-frequency/) |
| ☐ | 4 | Reorganize String | [Solve](https://leetcode.com/problems/reorganize-string/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Find Median from Data Stream | [Solve](https://leetcode.com/problems/find-median-from-data-stream/) |
| ☐ | 2 | Smallest Range Covering Elements from K Lists | [Solve](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 15. Greedy

**📖 Concept:** Pick the locally best option at each step and prove it leads to a global optimum. Usually sort first.

**🧩 Patterns:** Sort + scan, interval scheduling, jump/reachability, exchange argument, two-pass (left/right) greedy.

**⏱️ Complexity cheat-sheet:** Typically O(n log n) due to sorting

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Assign Cookies | [Solve](https://leetcode.com/problems/assign-cookies/) |
| ☐ | 2 | Lemonade Change | [Solve](https://leetcode.com/problems/lemonade-change/) |
| ☐ | 3 | Best Time to Buy and Sell Stock II | [Solve](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) |
| ☐ | 4 | Maximum Units on a Truck | [Solve](https://leetcode.com/problems/maximum-units-on-a-truck/) |
| ☐ | 5 | Can Place Flowers | [Solve](https://leetcode.com/problems/can-place-flowers/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Largest Perimeter Triangle | [Solve](https://leetcode.com/problems/largest-perimeter-triangle/) |
| ☐ | 2 | Minimum Changes to Make Alternating Binary String | [Solve](https://leetcode.com/problems/minimum-changes-to-make-alternating-binary-string/) |
| ☐ | 3 | Split a String in Balanced Strings | [Solve](https://leetcode.com/problems/split-a-string-in-balanced-strings/) |
| ☐ | 4 | Minimum Number of Moves to Seat Everyone | [Solve](https://leetcode.com/problems/minimum-number-of-moves-to-seat-everyone/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Jump Game | [Solve](https://leetcode.com/problems/jump-game/) |
| ☐ | 2 | Jump Game II | [Solve](https://leetcode.com/problems/jump-game-ii/) |
| ☐ | 3 | Gas Station | [Solve](https://leetcode.com/problems/gas-station/) |
| ☐ | 4 | Partition Labels | [Solve](https://leetcode.com/problems/partition-labels/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Candy | [Solve](https://leetcode.com/problems/candy/) |
| ☐ | 2 | Patching Array | [Solve](https://leetcode.com/problems/patching-array/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 16. Dynamic Programming

**📖 Concept:** Break a problem into overlapping subproblems, store results (memoization or tabulation). If brute force recursion repeats work, think DP.

**🧩 Patterns:** 1D DP, grid DP, knapsack (0/1, unbounded), LIS/LCS, interval DP, state-machine DP.

**⏱️ Complexity cheat-sheet:** Time = states x transitions | Space often optimizable to O(1)/O(n)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Climbing Stairs | [Solve](https://leetcode.com/problems/climbing-stairs/) |
| ☐ | 2 | Min Cost Climbing Stairs | [Solve](https://leetcode.com/problems/min-cost-climbing-stairs/) |
| ☐ | 3 | House Robber | [Solve](https://leetcode.com/problems/house-robber/) |
| ☐ | 4 | Divisor Game | [Solve](https://leetcode.com/problems/divisor-game/) |
| ☐ | 5 | Counting Bits | [Solve](https://leetcode.com/problems/counting-bits/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | N-th Tribonacci Number | [Solve](https://leetcode.com/problems/n-th-tribonacci-number/) |
| ☐ | 2 | Get Maximum in Generated Array | [Solve](https://leetcode.com/problems/get-maximum-in-generated-array/) |
| ☐ | 3 | Maximum Ascending Subarray Sum | [Solve](https://leetcode.com/problems/maximum-ascending-subarray-sum/) |
| ☐ | 4 | Longest Continuous Increasing Subsequence | [Solve](https://leetcode.com/problems/longest-continuous-increasing-subsequence/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Coin Change | [Solve](https://leetcode.com/problems/coin-change/) |
| ☐ | 2 | Longest Increasing Subsequence | [Solve](https://leetcode.com/problems/longest-increasing-subsequence/) |
| ☐ | 3 | Unique Paths | [Solve](https://leetcode.com/problems/unique-paths/) |
| ☐ | 4 | Partition Equal Subset Sum | [Solve](https://leetcode.com/problems/partition-equal-subset-sum/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Regular Expression Matching | [Solve](https://leetcode.com/problems/regular-expression-matching/) |
| ☐ | 2 | Burst Balloons | [Solve](https://leetcode.com/problems/burst-balloons/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 17. Graphs (BFS / DFS / Topological)

**📖 Concept:** Nodes and edges, stored as adjacency list or matrix. Master BFS (shortest path in unweighted graphs), DFS (components, cycles) and topological sort.

**🧩 Patterns:** Grid flood-fill, connected components, cycle detection, topological sort (Kahn), BFS shortest path, bridges.

**⏱️ Complexity cheat-sheet:** O(V + E) traversal

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Find if Path Exists in Graph | [Solve](https://leetcode.com/problems/find-if-path-exists-in-graph/) |
| ☐ | 2 | Find Center of Star Graph | [Solve](https://leetcode.com/problems/find-center-of-star-graph/) |
| ☐ | 3 | Island Perimeter | [Solve](https://leetcode.com/problems/island-perimeter/) |
| ☐ | 4 | Flood Fill | [Solve](https://leetcode.com/problems/flood-fill/) |
| ☐ | 5 | Find the Town Judge | [Solve](https://leetcode.com/problems/find-the-town-judge/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | N Ary Tree Preorder Traversal | [Solve](https://leetcode.com/problems/n-ary-tree-preorder-traversal/) |
| ☐ | 2 | N Ary Tree Postorder Traversal | [Solve](https://leetcode.com/problems/n-ary-tree-postorder-traversal/) |
| ☐ | 3 | Maximum Depth of N Ary Tree | [Solve](https://leetcode.com/problems/maximum-depth-of-n-ary-tree/) |
| ☐ | 4 | Leaf Similar Trees | [Solve](https://leetcode.com/problems/leaf-similar-trees/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Number of Islands | [Solve](https://leetcode.com/problems/number-of-islands/) |
| ☐ | 2 | Clone Graph | [Solve](https://leetcode.com/problems/clone-graph/) |
| ☐ | 3 | Course Schedule | [Solve](https://leetcode.com/problems/course-schedule/) |
| ☐ | 4 | Rotting Oranges | [Solve](https://leetcode.com/problems/rotting-oranges/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Word Ladder | [Solve](https://leetcode.com/problems/word-ladder/) |
| ☐ | 2 | Critical Connections in a Network | [Solve](https://leetcode.com/problems/critical-connections-in-a-network/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 18. Bit Manipulation

**📖 Concept:** Operate directly on binary representation using AND, OR, XOR, NOT and shifts. Gives O(1) tricks and compact state.

**🧩 Patterns:** XOR cancellation, n & (n-1), masks, bit counting, bitmask state, binary trie.

**⏱️ Complexity cheat-sheet:** Mostly O(1) or O(bits)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Number of 1 Bits | [Solve](https://leetcode.com/problems/number-of-1-bits/) |
| ☐ | 2 | Hamming Distance | [Solve](https://leetcode.com/problems/hamming-distance/) |
| ☐ | 3 | Reverse Bits | [Solve](https://leetcode.com/problems/reverse-bits/) |
| ☐ | 4 | Number Complement | [Solve](https://leetcode.com/problems/number-complement/) |
| ☐ | 5 | Binary Number with Alternating Bits | [Solve](https://leetcode.com/problems/binary-number-with-alternating-bits/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Single Number | [Solve](https://leetcode.com/problems/single-number/) |
| ☐ | 2 | Missing Number | [Solve](https://leetcode.com/problems/missing-number/) |
| ☐ | 3 | Add Binary | [Solve](https://leetcode.com/problems/add-binary/) |
| ☐ | 4 | Minimum Bit Flips to Convert Number | [Solve](https://leetcode.com/problems/minimum-bit-flips-to-convert-number/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Single Number II | [Solve](https://leetcode.com/problems/single-number-ii/) |
| ☐ | 2 | Single Number III | [Solve](https://leetcode.com/problems/single-number-iii/) |
| ☐ | 3 | Sum of Two Integers | [Solve](https://leetcode.com/problems/sum-of-two-integers/) |
| ☐ | 4 | Bitwise and of Numbers Range | [Solve](https://leetcode.com/problems/bitwise-and-of-numbers-range/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Maximum XOR With an Element From Array | [Solve](https://leetcode.com/problems/maximum-xor-with-an-element-from-array/) |
| ☐ | 2 | Minimum One Bit Operations to Make Integers Zero | [Solve](https://leetcode.com/problems/minimum-one-bit-operations-to-make-integers-zero/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 19. Math & Number Theory

**📖 Concept:** Digits, primes, GCD, modular arithmetic and number properties that turn brute force into formulas.

**🧩 Patterns:** Digit extraction, sieve of Eratosthenes, GCD/Euclid, fast exponentiation, base conversion.

**⏱️ Complexity cheat-sheet:** Sieve O(n log log n) | Fast power O(log n)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Palindrome Number | [Solve](https://leetcode.com/problems/palindrome-number/) |
| ☐ | 2 | Plus One | [Solve](https://leetcode.com/problems/plus-one/) |
| ☐ | 3 | Add Digits | [Solve](https://leetcode.com/problems/add-digits/) |
| ☐ | 4 | Fizz Buzz | [Solve](https://leetcode.com/problems/fizz-buzz/) |
| ☐ | 5 | Excel Sheet Column Number | [Solve](https://leetcode.com/problems/excel-sheet-column-number/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Roman to Integer | [Solve](https://leetcode.com/problems/roman-to-integer/) |
| ☐ | 2 | Ugly Number | [Solve](https://leetcode.com/problems/ugly-number/) |
| ☐ | 3 | Excel Sheet Column Title | [Solve](https://leetcode.com/problems/excel-sheet-column-title/) |
| ☐ | 4 | Greatest Common Divisor of Strings | [Solve](https://leetcode.com/problems/greatest-common-divisor-of-strings/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Count Primes | [Solve](https://leetcode.com/problems/count-primes/) |
| ☐ | 2 | Pow(x, n) | [Solve](https://leetcode.com/problems/powx-n/) |
| ☐ | 3 | Reverse Integer | [Solve](https://leetcode.com/problems/reverse-integer/) |
| ☐ | 4 | Multiply Strings | [Solve](https://leetcode.com/problems/multiply-strings/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Integer to English Words | [Solve](https://leetcode.com/problems/integer-to-english-words/) |
| ☐ | 2 | Number of Digit One | [Solve](https://leetcode.com/problems/number-of-digit-one/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 20. Matrix / 2D Arrays

**📖 Concept:** Grid of rows and columns. Problems test index handling, in-place transforms and traversal patterns.

**🧩 Patterns:** Boundary-shrinking spiral, transpose + reverse, in-place markers, staircase search, DFS/DP on grid.

**⏱️ Complexity cheat-sheet:** Traversal O(m x n)

### 🟢 Basic (5)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Transpose Matrix | [Solve](https://leetcode.com/problems/transpose-matrix/) |
| ☐ | 2 | Flipping an Image | [Solve](https://leetcode.com/problems/flipping-an-image/) |
| ☐ | 3 | Matrix Diagonal Sum | [Solve](https://leetcode.com/problems/matrix-diagonal-sum/) |
| ☐ | 4 | Reshape the Matrix | [Solve](https://leetcode.com/problems/reshape-the-matrix/) |
| ☐ | 5 | Count Negative Numbers in a Sorted Matrix | [Solve](https://leetcode.com/problems/count-negative-numbers-in-a-sorted-matrix/) |

### 🟡 Easy (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Toeplitz Matrix | [Solve](https://leetcode.com/problems/toeplitz-matrix/) |
| ☐ | 2 | Lucky Numbers in a Matrix | [Solve](https://leetcode.com/problems/lucky-numbers-in-a-matrix/) |
| ☐ | 3 | Check if Every Row and Column Contains All Numbers | [Solve](https://leetcode.com/problems/check-if-every-row-and-column-contains-all-numbers/) |
| ☐ | 4 | Image Smoother | [Solve](https://leetcode.com/problems/image-smoother/) |

### 🟠 Medium (4)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Rotate Image | [Solve](https://leetcode.com/problems/rotate-image/) |
| ☐ | 2 | Spiral Matrix | [Solve](https://leetcode.com/problems/spiral-matrix/) |
| ☐ | 3 | Set Matrix Zeroes | [Solve](https://leetcode.com/problems/set-matrix-zeroes/) |
| ☐ | 4 | Search a 2d Matrix | [Solve](https://leetcode.com/problems/search-a-2d-matrix/) |

### 🔴 Hard (2)
| ✅ | # | Problem | Link |
|:-:|:-:|---|---|
| ☐ | 1 | Maximal Rectangle | [Solve](https://leetcode.com/problems/maximal-rectangle/) |
| ☐ | 2 | Longest Increasing Path in a Matrix | [Solve](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/) |

[⬆ Back to top](#-dsa-zero-to-hero-sheet)

---

## 💡 Problem-Solving Checklist

- Restate the problem and note constraints (`n` decides the allowed time complexity).
- Write a brute-force first, then ask: *what work is repeated?*
- Pick a pattern: two pointers, hashing, binary search, DP, graph, etc.
- Dry-run on a small example and on edge cases (empty, single element, duplicates, negatives).
- State final time and space complexity out loud.

## 🤝 Contributing

Found a broken link or want to suggest a better problem? Open an issue or a pull request.

## ⭐ Support

If this sheet helps you, give the repo a star and share it with a friend who is preparing for placements.
