Here's your 100-problem list formatted in a clean table with the approach/pattern for each problem:

| # | Problem | Pattern/Approach | LeetCode Link |
|---|---------|------------------|---------------|
| **ARRAYS** ||||
| 1 | **Two Sum** | HashMap (O(n)) | [LC 1](https://leetcode.com/problems/two-sum/) |
| 2 | **Best Time to Buy and Sell Stock** | Single pass (track min price) | [LC 121](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) |
| 3 | **Contains Duplicate** | HashSet / Sorting | [LC 217](https://leetcode.com/problems/contains-duplicate/) |
| 4 | **Maximum Subarray (Kadane's)** | Kadane's algorithm | [LC 53](https://leetcode.com/problems/maximum-subarray/) |
| 5 | **Move Zeroes** | Two-pointer (swap) | [LC 283](https://leetcode.com/problems/move-zeroes/) |
| 6 | **Plus One** | Array traversal from end | [LC 66](https://leetcode.com/problems/plus-one/) |
| 7 | **Merge Sorted Array** | Two-pointer from end | [LC 88](https://leetcode.com/problems/merge-sorted-array/) |
| 8 | **Remove Duplicates from Sorted Array** | Two-pointer (in-place) | [LC 26](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) |
| 9 | **Remove Element** | Two-pointer (in-place) | [LC 27](https://leetcode.com/problems/remove-element/) |
| 10 | **Majority Element** | Boyer-Moore Voting | [LC 169](https://leetcode.com/problems/majority-element/) |
| 11 | **Single Number** | XOR bit manipulation | [LC 136](https://leetcode.com/problems/single-number/) |
| 12 | **Rotate Array** | Reverse entire, then parts | [LC 189](https://leetcode.com/problems/rotate-array/) |
| 13 | **Intersection of Two Arrays** | HashSet / Two-pointer | [LC 349](https://leetcode.com/problems/intersection-of-two-arrays/) |
| 14 | **Pascal's Triangle** | DP / Row building | [LC 118](https://leetcode.com/problems/pascals-triangle/) |
| 15 | **Find Pivot Index** | Prefix sum | [LC 724](https://leetcode.com/problems/find-pivot-index/) |


| **STRINGS** ||||


| 16 | **Valid Anagram** | HashMap / Sorting | [LC 242](https://leetcode.com/problems/valid-anagram/) |
| 17 | **Valid Palindrome** | Two-pointer | [LC 125](https://leetcode.com/problems/valid-palindrome/) |
| 18 | **Reverse String** | Two-pointer (swap) | [LC 344](https://leetcode.com/problems/reverse-string/) |
| 19 | **First Unique Character** | Frequency array | [LC 387](https://leetcode.com/problems/first-unique-character-in-a-string/) |
| 20 | **Longest Common Prefix** | Horizontal/Vertical scanning | [LC 14](https://leetcode.com/problems/longest-common-prefix/) |
| 21 | **Implement strStr()** | Sliding window / KMP | [LC 28](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/) |
| 22 | **Reverse Words in a String III** | Split + reverse each word | [LC 557](https://leetcode.com/problems/reverse-words-in-a-string-iii/) |
| 23 | **Ransom Note** | Frequency count | [LC 383](https://leetcode.com/problems/ransom-note/) |
| 24 | **Is Subsequence** | Two-pointer | [LC 392](https://leetcode.com/problems/is-subsequence/) |
| 25 | **Add Binary** | String traversal from end | [LC 67](https://leetcode.com/problems/add-binary/) |
| 26 | **Length of Last Word** | Traverse from end | [LC 58](https://leetcode.com/problems/length-of-last-word/) |
| 27 | **Reverse Vowels of a String** | Two-pointer | [LC 345](https://leetcode.com/problems/reverse-vowels-of-a-string/) |
| **TWO POINTERS** ||||
| 28 | **Squares of a Sorted Array** | Two-pointer from ends | [LC 977](https://leetcode.com/problems/squares-of-a-sorted-array/) |
| 29 | **Valid Palindrome II** | Two-pointer with skip | [LC 680](https://leetcode.com/problems/valid-palindrome-ii/) |
| 30 | **Two Sum II (Sorted Array)** | Two-pointer | [LC 167](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) |
| 31 | **Merge Strings Alternately** | Two-pointer | [LC 1768](https://leetcode.com/problems/merge-strings-alternately/) |
| 32 | **Remove Duplicates from Sorted Array II** | Two-pointer | [LC 80](https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/) |
| 33 | **Backspace String Compare** | Two-pointer / Stack | [LC 844](https://leetcode.com/problems/backspace-string-compare/) |
| 34 | **Sort Array By Parity** | Two-pointer | [LC 905](https://leetcode.com/problems/sort-array-by-parity/) |
| 35 | **Container With Most Water** | Two-pointer (area max) | [LC 11](https://leetcode.com/problems/container-with-most-water/) |

| **HASHMAP / HASHSET** ||||


| 36 | **Two Sum (HashMap)** | HashMap (store complement) | [LC 1](https://leetcode.com/problems/two-sum/) |
| 37 | **Group Anagrams** | HashMap (sorted string as key) | [LC 49](https://leetcode.com/problems/group-anagrams/) |
| 38 | **Contains Duplicate II** | HashMap (sliding window) | [LC 219](https://leetcode.com/problems/contains-duplicate-ii/) |
| 39 | **Isomorphic Strings** | Two HashMaps | [LC 205](https://leetcode.com/problems/isomorphic-strings/) |
| 40 | **Word Pattern** | HashMap (bijection) | [LC 290](https://leetcode.com/problems/word-pattern/) |
| 41 | **Happy Number** | HashSet (detect cycle) | [LC 202](https://leetcode.com/problems/happy-number/) |
| 42 | **Jewels and Stones** | HashSet | [LC 771](https://leetcode.com/problems/jewels-and-stones/) |
| 43 | **Two Sum IV - Input is BST** | HashMap + DFS | [LC 653](https://leetcode.com/problems/two-sum-iv-input-is-a-bst/) |
| **LINKED LIST** ||||
| 44 | **Reverse Linked List** | Iterative / Recursive | [LC 206](https://leetcode.com/problems/reverse-linked-list/) |
| 45 | **Merge Two Sorted Lists** | Dummy node + two-pointer | [LC 21](https://leetcode.com/problems/merge-two-sorted-lists/) |
| 46 | **Linked List Cycle** | Floyd's Cycle Detection | [LC 141](https://leetcode.com/problems/linked-list-cycle/) |
| 47 | **Remove Duplicates from Sorted List** | Single pass | [LC 83](https://leetcode.com/problems/remove-duplicates-from-sorted-list/) |
| 48 | **Middle of the Linked List** | Fast-slow pointer | [LC 876](https://leetcode.com/problems/middle-of-the-linked-list/) |
| 49 | **Palindrome Linked List** | Fast-slow + reverse half | [LC 234](https://leetcode.com/problems/palindrome-linked-list/) |
| 50 | **Remove Linked List Elements** | Dummy node | [LC 203](https://leetcode.com/problems/remove-linked-list-elements/) |
| 51 | **Intersection of Two Linked Lists** | Two-pointer | [LC 160](https://leetcode.com/problems/intersection-of-two-linked-lists/) |
| 52 | **Convert Binary Number to Integer** | Traversal + bit shift | [LC 1290](https://leetcode.com/problems/convert-binary-number-in-a-linked-list-to-integer/) |
| 53 | **Delete Node in a Linked List** | Overwrite with next node | [LC 237](https://leetcode.com/problems/delete-node-in-a-linked-list/) |
| **STACK / QUEUE** ||||
| 54 | **Valid Parentheses** | Stack | [LC 20](https://leetcode.com/problems/valid-parentheses/) |
| 55 | **Implement Queue using Stacks** | Two stacks | [LC 232](https://leetcode.com/problems/implement-queue-using-stacks/) |
| 56 | **Implement Stack using Queues** | Two queues | [LC 225](https://leetcode.com/problems/implement-stack-using-queues/) |
| 57 | **Min Stack** | Two stacks | [LC 155](https://leetcode.com/problems/min-stack/) |
| 58 | **Baseball Game** | Stack | [LC 682](https://leetcode.com/problems/baseball-game/) |
| 59 | **Remove All Adjacent Duplicates** | Stack | [LC 1047](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/) |
| 60 | **Next Greater Element I** | Monotonic stack | [LC 496](https://leetcode.com/problems/next-greater-element-i/) |
| 61 | **Backspace String Compare** | Stack | [LC 844](https://leetcode.com/problems/backspace-string-compare/) |
| **RECURSION & BACKTRACKING** ||||
| 62 | **Fibonacci Number** | Recursion / DP | [LC 509](https://leetcode.com/problems/fibonacci-number/) |
| 63 | **Climbing Stairs** | Recursion / DP | [LC 70](https://leetcode.com/problems/climbing-stairs/) |
| 64 | **Power of Two** | Recursion / Bit | [LC 231](https://leetcode.com/problems/power-of-two/) |
| 65 | **Reverse String (Recursive)** | Recursion | [LC 344](https://leetcode.com/problems/reverse-string/) |
| 66 | **Sum of Digits** | Recursion | Custom/GFG |
| 67 | **Factorial** | Recursion | Custom/GFG |
| **MATH & BIT MANIPULATION** ||||
| 68 | **FizzBuzz** | Modulo operator | [LC 412](https://leetcode.com/problems/fizz-buzz/) |
| 69 | **Palindrome Number** | Reverse half number | [LC 9](https://leetcode.com/problems/palindrome-number/) |
| 70 | **Roman to Integer** | HashMap + traversal | [LC 13](https://leetcode.com/problems/roman-to-integer/) |
| 71 | **Number of 1 Bits** | Bit manipulation | [LC 191](https://leetcode.com/problems/number-of-1-bits/) |
| 72 | **Counting Bits** | DP + Bit | [LC 338](https://leetcode.com/problems/counting-bits/) |
| 73 | **Missing Number** | XOR / Sum formula | [LC 268](https://leetcode.com/problems/missing-number/) |
| 74 | **Power of Three** | Loop / Log | [LC 326](https://leetcode.com/problems/power-of-three/) |
| 75 | **Add Digits** | Digital root | [LC 258](https://leetcode.com/problems/add-digits/) |
| 76 | **Reverse Integer** | Mod + overflow check | [LC 7](https://leetcode.com/problems/reverse-integer/) |
| 77 | **Excel Sheet Column Number** | Base-26 conversion | [LC 171](https://leetcode.com/problems/excel-sheet-column-number/) |
| **SORTING & SEARCHING** ||||
| 78 | **Binary Search** | Standard binary search | [LC 704](https://leetcode.com/problems/binary-search/) |
| 79 | **Search Insert Position** | Binary search | [LC 35](https://leetcode.com/problems/search-insert-position/) |
| 80 | **First Bad Version** | Binary search | [LC 278](https://leetcode.com/problems/first-bad-version/) |
| 81 | **Sqrt(x)** | Binary search | [LC 69](https://leetcode.com/problems/sqrtx/) |
| 82 | **Merge Sorted Array** | Two-pointer from end | [LC 88](https://leetcode.com/problems/merge-sorted-array/) |
| 83 | **Sort Colors** | Dutch National Flag | [LC 75](https://leetcode.com/problems/sort-colors/) |
| 84 | **Find Smallest Letter > Target** | Binary search | [LC 744](https://leetcode.com/problems/find-smallest-letter-greater-than-target/) |
| 85 | **K Closest Points to Origin** | Quickselect / Heap | [LC 973](https://leetcode.com/problems/k-closest-points-to-origin/) |
| **TREES** ||||
| 86 | **Maximum Depth of Binary Tree** | DFS / BFS | [LC 104](https://leetcode.com/problems/maximum-depth-of-binary-tree/) |
| 87 | **Invert Binary Tree** | Recursive swap | [LC 226](https://leetcode.com/problems/invert-binary-tree/) |
| 88 | **Same Tree** | Recursive comparison | [LC 100](https://leetcode.com/problems/same-tree/) |
| 89 | **Symmetric Tree** | Recursive / Iterative | [LC 101](https://leetcode.com/problems/symmetric-tree/) |
| 90 | **Path Sum** | DFS | [LC 112](https://leetcode.com/problems/path-sum/) |
| 91 | **Binary Tree Preorder Traversal** | Recursive / Iterative | [LC 144](https://leetcode.com/problems/binary-tree-preorder-traversal/) |
| 92 | **Binary Tree Inorder Traversal** | Recursive / Iterative | [LC 94](https://leetcode.com/problems/binary-tree-inorder-traversal/) |
| 93 | **Minimum Depth of Binary Tree** | BFS / DFS | [LC 111](https://leetcode.com/problems/minimum-depth-of-binary-tree/) |
| 94 | **Diameter of Binary Tree** | Post-order traversal | [LC 543](https://leetcode.com/problems/diameter-of-binary-tree/) |
| 95 | **Convert Sorted Array to BST** | Recursive BST construction | [LC 108](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) |
| **MATRIX** ||||
| 96 | **Transpose Matrix** | Swap i/j indices | [LC 867](https://leetcode.com/problems/transpose-matrix/) |
| 97 | **Flipping an Image** | Reverse row + invert | [LC 832](https://leetcode.com/problems/flipping-an-image/) |
| 98 | **Toeplitz Matrix** | Check diagonal consistency | [LC 766](https://leetcode.com/problems/toeplitz-matrix/) |
| 99 | **Island Perimeter** | Check neighbors | [LC 463](https://leetcode.com/problems/island-perimeter/) |
| 100 | **Reshape the Matrix** | Queue / Index mapping | [LC 566](https://leetcode.com/problems/reshape-the-matrix/) |
| **PRIORITY QUEUE / HEAP (ADD-ON)** ||||
| 101 | **Kth Largest Element in Array** | Min-heap / Quickselect | [LC 215](https://leetcode.com/problems/kth-largest-element-in-an-array/) |
| 102 | **Kth Largest Element in Stream** | Min-heap | [LC 703](https://leetcode.com/problems/kth-largest-element-in-a-stream/) |
| **SLIDING WINDOW (ADD-ON)** ||||
| 103 | **Maximum Average Subarray I** | Sliding window | [LC 643](https://leetcode.com/problems/maximum-average-subarray-i/) |
| 104 | **Longest Substring Without Repeating** | Sliding window + HashSet | [LC 3](https://leetcode.com/problems/longest-substring-without-repeating-characters/) |
| **GRAPH (ADD-ON)** ||||
| 105 | **Find if Path Exists** | BFS / DFS / Union-Find | [LC 1971](https://leetcode.com/problems/find-if-path-exists-in-graph/) |
| 106 | **Flood Fill** | DFS / BFS | [LC 733](https://leetcode.com/problems/flood-fill/) |
| 107 | **Number of Islands** | DFS / BFS | [LC 200](https://leetcode.com/problems/number-of-islands/) |
| **BINARY SEARCH (ADVANCED)** ||||
| 108 | **Find Minimum in Rotated Sorted Array** | Binary search | [LC 153](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) |

---

### 📝 Additional Must-Know Patterns (Bridge Problems)

| # | Problem | Pattern/Approach | LeetCode Link |
|---|---------|------------------|---------------|
| 109 | **Subarray Sum Equals K** | Prefix sum + HashMap | [LC 560](https://leetcode.com/problems/subarray-sum-equals-k/) |
| 110 | **Contiguous Array** | Prefix sum + HashMap | [LC 525](https://leetcode.com/problems/contiguous-array/) |
| 111 | **Daily Temperatures** | Monotonic stack | [LC 739](https://leetcode.com/problems/daily-temperatures/) |
| 112 | **Rotting Oranges** | BFS (multi-source) | [LC 994](https://leetcode.com/problems/rotting-oranges/) |
| 113 | **Binary Tree Level Order Traversal** | BFS (queue) | [LC 102](https://leetcode.com/problems/binary-tree-level-order-traversal/) |
| 114 | **Validate Binary Search Tree** | In-order traversal | [LC 98](https://leetcode.com/problems/validate-binary-search-tree/) |
| 115 | **Search in a Binary Search Tree** | BST property | [LC 700](https://leetcode.com/problems/search-in-a-binary-search-tree/) |

---

### 🎯 Quick Priority List for Infosys (Top 30)

If you're short on time, focus on these **highest-yield problems**:

| Priority | Problem | Pattern |
|----------|---------|---------|
| 🔥🔥🔥 | Two Sum | HashMap |
| 🔥🔥🔥 | Maximum Subarray | Kadane's |
| 🔥🔥🔥 | Valid Parentheses | Stack |
| 🔥🔥🔥 | Binary Search | Searching |
| 🔥🔥🔥 | Reverse Linked List | LL |
| 🔥🔥🔥 | Maximum Depth of Tree | Trees |
| 🔥🔥🔥 | Contains Duplicate | HashSet |
| 🔥🔥🔥 | Merge Two Sorted Lists | LL |
| 🔥🔥🔥 | Best Time to Buy/Sell | Array |
| 🔥🔥🔥 | Valid Anagram | String |
| 🔥🔥 | Move Zeroes | Two-pointer |
| 🔥🔥 | Majority Element | Boyer-Moore |
| 🔥🔥 | Valid Palindrome | Two-pointer |
| 🔥🔥 | Climbing Stairs | DP |
| 🔥🔥 | Number of 1 Bits | Bit |
| 🔥🔥 | Middle of LL | Fast-slow |
| 🔥🔥 | Invert Binary Tree | Trees |
| 🔥🔥 | FizzBuzz | Math |
| 🔥🔥 | Implement Queue using Stacks | Stack |
| 🔥🔥 | Remove Duplicates from Sorted Array | Two-pointer |
| 🔥🔥 | Plus One | Array |
| 🔥🔥 | Same Tree | Trees |
| 🔥🔥 | Roman to Integer | Math |
| 🔥🔥 | Pascal's Triangle | DP |
| 🔥🔥 | Majority Element | Boyer-Moore |
| 🔥🔥 | Backspace String Compare | Stack |
| 🔥🔥 | Sort Array By Parity | Two-pointer |
| 🔥🔥 | Missing Number | XOR |
| 🔥🔥 | Is Subsequence | Two-pointer |
| 🔥🔥 | Happy Number | HashSet |

---

### 💡 Pro Tips for LeetCode

1. **Don't memorize solutions** — memorize **patterns** (Two-pointer, Sliding Window, Monotonic Stack, etc.)
2. **Time yourself** — Easy: 10-15 min, Medium: 20-30 min
3. **Draw/explain before coding** — Scribble on paper, talk through your approach
4. **Use the "discuss" section** — Learn from other solutions after you solve
5. **Revisit problems** — Solve a problem today, again next week from scratch

This list should keep you busy for a while! Good luck with your preparation 🚀