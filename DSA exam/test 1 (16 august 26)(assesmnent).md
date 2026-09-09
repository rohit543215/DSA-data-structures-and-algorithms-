# 📊 Quick Assessment

## Score: **5.5/10 (55%) - D+**

---

## Problem-by-Problem Breakdown

| # | Problem | Status | Score |
|---|---------|--------|-------|
| 1 | Two Sum | ✅ Perfect | 10/10 |
| 2 | Buy/Sell Stock | ✅ Perfect | 10/10 |
| 3 | Contains Duplicate | ⚠️ Works but inefficient | 7/10 |
| 4 | Max Subarray | ✅ Perfect | 10/10 |
| 5 | Move Zeroes | ❌ Logic error | 4/10 |
| 6 | Plus One | ❌ Completely wrong | 2/10 |
| 7 | Merge Sorted | ❌ Syntax errors | 1/10 |
| 8 | Remove Duplicates | ✅ Perfect | 10/10 |

---

## 🚨 Critical Issues to Fix

### 1. **Move Zeroes** - Wrong pointer increment
```python
# ❌ Your code
if nums[i]!=0:
    nums[start_pos]=nums[i]
start_pos+=1  # Increments for zeros too!

# ✅ Fix
if nums[i]!=0:
    nums[start_pos]=nums[i]
    start_pos+=1  # Only increment for non-zeros
```

### 2. **Plus One** - Doesn't handle carries
```python
# ❌ Your code - only checks last digit
for i in range(-1,-2,-1):  # Only runs ONCE!

# ✅ Fix
for i in range(len(digits)-1, -1, -1):
    if digits[i] == 9:
        digits[i] = 0
    else:
        digits[i] += 1
        return digits
return [1] + digits
```

### 3. **Merge Sorted** - Syntax errors
```python
# ❌ Your code
p_write[nums1[p1]]=nums1[p1]  # Wrong syntax

# ✅ Fix
nums1[p_write] = nums1[p1]    # Correct
```

### 4. **Contains Duplicate** - Misunderstood set
```python
# ❌ Your code
freq=set(nums)  # Already has all elements!
if i in freq:   # Always True

# ✅ Fix
seen = set()
for num in nums:
    if num in seen:
        return True
    seen.add(num)
return False
```

---

## 🎯 What to Focus On

1. **Two-pointer technique** (Problems 5, 7)
2. **Edge cases** (Problem 6 - all 9s)
3. **Array indexing** (Problem 7)
4. **Syntax** - careful with variable names

---

## 📝 Must Re-solve

1. **Plus One** (Practice with [9,9,9])--> done
2. **Move Zeroes** (Trace with [0,1,0,3,12])--> done
3. **Merge Sorted** (Test with empty arrays)--> done

---

**Bottom line:** Solid on 5/8 problems. Need practice on pointer manipulation and edge cases. You can fix this quickly! 💪