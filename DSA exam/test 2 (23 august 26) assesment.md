## Score: 6/6 correct

| # | Problem | Status | Notes |
|---|---|---|---|
| 1 | Move Zeroes | ✅ Correct | Optimal — O(n) time, O(1) space |
| 2 | Single Number | ✅ Correct | XOR trick, meets the O(1)-space follow-up |
| 3 | Plus One | ✅ Correct | Carry chain + all-9s edge case handled |
| 4 | Remove Element | ✅ Correct | Clean two-pointer |
| 5 | Majority Element | ✅ Correct, but not the follow-up | Hashmap approach — correct output, but this is O(n) **time and O(n) space**, not O(1) space |
| 6 | Merge Sorted Array | ✅ Correct | Three-pointer merge from the back |

**Overall: all 6 functionally correct this time — nice.** Five of six are already at the optimal complexity.

## What to work on

**Majority Element — the follow-up is still open.** Your hashmap solution correctly returns the majority element, but the problem explicitly asks: *"could you solve it in O(n) time and O(1) space?"* Right now your `freq` dict grows with the number of distinct elements, so that's O(n) extra space, not O(1).

This is a good one to actually work through, since the technique — **Boyer-Moore Voting Algorithm** — is a genuinely different idea from anything in this set so far (not two-pointer, not XOR, not hashmap): you keep a running "candidate" and a counter, and the core insight is that a true majority element (appearing more than n/2 times) can survive being "cancelled out" by all other elements combined.

