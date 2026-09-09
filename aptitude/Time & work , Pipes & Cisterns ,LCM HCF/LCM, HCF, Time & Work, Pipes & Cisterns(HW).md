# 📘 Complete Aptitude Guide - LCM, HCF, Time & Work, Pipes & Cisterns

## TCS NQT 2026 - All Questions with Solutions

---

## 🧠 PART 1: THE MASTER FORMULA (LCM METHOD)

This is the **only method** you need for 90% of these problems. It avoids fractions completely.

| Step | Action |
|------|--------|
| **1** | Take the **LCM** of all given time periods (days/hours/minutes). This = **Total Work** (in units). |
| **2** | Find each person's/pipe's **Efficiency** = `Total Work / Their Time`. |
| **3** | **Add** efficiencies for workers/inlets. **Subtract** efficiencies for emptiers/outlets. |
| **4** | **Required Time** = `Total Work / Net Efficiency`. |

---

## 📊 PART 2: LCM & HCF - COMPLETE REFERENCE

### Prime Numbers List (1 to 100)
- **1–50:** 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47 → **15 primes**
- **51–100:** 53, 59, 61, 67, 71, 73, 79, 83, 89, 97 → **10 primes**
- **101–200:** There are **21 primes**.

---

### LCM & HCF of Fractions
| Formula |
|---------|
| LCM of fractions = **LCM(Numerators) / HCF(Denominators)** |
| HCF of fractions = **HCF(Numerators) / LCM(Denominators)** |

---

### LCM of Decimals (Trick Method)
1. Multiply all numbers by the same power of 10 to remove decimals.
2. Find LCM of the integers.
3. Divide back by the same power of 10.

---

### Last Digit of a Product (Shortcut)
> **Find last digit of:** 7656 × 7163 × 6353 × 4167

| Step | Calculation |
|------|-------------|
| Multiply only unit digits | 6 × 3 × 3 × 7 |
| Step-by-step | 6×3=18 (unit 8), 8×3=24 (unit 4), 4×7=28 (unit 8) |
| **Last digit** | **8** |

---

## 🔢 PART 3: LCM & HCF - SOLVED QUESTIONS

---

### Question 1
> **Two numbers are in the ratio of 5:7. If their LCM is 105, what is the difference between their squares?**

**Options:** A) 216 B) 210 C) 72 D) 840

**Solution:**
| Step | Calculation |
|------|-------------|
| Let HCF = h | Numbers are 5h and 7h |
| Product = LCM × HCF | 5h × 7h = 105 × h |
| Solve | 35h² = 105h → h = 3 |
| Numbers | 5×3=15, 7×3=21 |
| Difference of squares | 21² - 15² = 441 - 225 = **216** |

**✅ Correct Answer: (A) 216**

---

### Question 2
> **What is the least number which when divided by 4, 5, 6 and 7 leaves a remainder 3, but when divided by 9 leaves no remainder?**

**Options:** A) 1683 B) 417 C) 843 D) 423

**Solution:**
| Step | Calculation |
|------|-------------|
| LCM of 4,5,6,7 | 420 |
| Required number | 420y + 3 (must be divisible by 9) |
| Try y=1 | 420+3 = 423 |
| Check 423 ÷ 9 | 47 (no remainder) ✓ |
| Check with 4,5,6,7 | All give remainder 3 ✓ |

**✅ Correct Answer: (D) 423**

---

### Question 3
> **The HCF of two numbers is 36, and their LCM is 1296. If one of the numbers is 144, what is the other number?**

**Options:** A) 288 B) 324 C) 216 D) 252

**Solution:**
| Step | Calculation |
|------|-------------|
| Formula | HCF × LCM = Product of numbers |
| Substitute | 36 × 1296 = 144 × y |
| Solve | 46,656 = 144y → y = 324 |

**✅ Correct Answer: (B) 324**

---

### Question 4
> **The product of two numbers is 4107. If the HCF of these numbers is 37, then the greater number is:**

**Options:** A) 101 B) 107 C) 111 D) 185

**Solution:**
| Step | Calculation |
|------|-------------|
| Let numbers | 37x and 37y |
| Product | 37x × 37y = 4107 |
| xy = | 4107 / (37×37) = 3 |
| Co-prime pairs | (1,3) |
| Greater number | 3 × 37 = **111** |

**✅ Correct Answer: (C) 111**

---

## 👷 PART 4: TIME & WORK - SOLVED QUESTIONS

---

### Question 5
> **Worker A can complete work in 7 days. Worker B can complete work in 9 days. If they work together, in how many days will the work be completed?**

**Options:** A) 2 days B) 16 days C) 4 days D) 9 days

**Solution (LCM Method):**
| Step | Calculation |
|------|-------------|
| Total Work | LCM(7,9) = 63 units |
| A's efficiency | 63/7 = 9 units/day |
| B's efficiency | 63/9 = 7 units/day |
| Combined | 9+7 = 16 units/day |
| Time | 63/16 = 3.9375 days ≈ **4 days** |

**✅ Correct Answer: (C) 4 days**

---

### Question 6
> **A and B can make a website in 10 days. B and C in 15 days. A and C in 20 days. In what time C can make the website alone?**

**Options:** A) 60 days B) 45 days C) 40 days D) 120 days

**Solution:**
| Step | Calculation |
|------|-------------|
| One day work | A+B = 1/10, B+C = 1/15, A+C = 1/20 |
| Add all | 2(A+B+C) = 1/10 + 1/15 + 1/20 |
| Simplify | = 6/60 + 4/60 + 3/60 = 13/60 |
| A+B+C = | 13/120 |
| C alone | (A+B+C) - (A+B) = 13/120 - 1/10 |
| C = | 13/120 - 12/120 = 1/120 |
| **C's time** | **120 days** |

**✅ Correct Answer: (D) 120 days**

---

### Question 7
> **A can do work in 18 days, B in 24 days. A and B work together for 8 days, then A leaves. How long will B take to finish the remaining work?**

**Options:** A) 5 days B) 6 days C) 16/3 days D) 14/3 days

**Solution (LCM Method):**
| Step | Calculation |
|------|-------------|
| Total Work | LCM(18,24) = 72 units |
| A's efficiency | 72/18 = 4 units/day |
| B's efficiency | 72/24 = 3 units/day |
| Combined | 4+3 = 7 units/day |
| Work in 8 days | 7×8 = 56 units |
| Remaining | 72-56 = 16 units |
| Time for B | 16/3 days |

**✅ Correct Answer: (C) 16/3 days**

---

### Question 8
> **Earning of 5 men or 7 women per day is Rs 5250. What will be the per day earning of 7 men and 13 women together?**

**Options:** A) 17000 B) 17100.5 C) 17100 D) 17290

**Solution:**
| Step | Calculation |
|------|-------------|
| 1 man's earning | 5250/5 = 1050 |
| 1 woman's earning | 5250/7 = 750 |
| 7 men + 13 women | 7×1050 + 13×750 |
| = | 7350 + 9750 = **17100** |

**✅ Correct Answer: (C) 17100**

---

### Question 9
> **A 100 m road can be laid in 10 days by 20 women. In how many days can a 50 m road be laid by 10 women?**

**Options:** A) 5 B) 10 C) 20 D) 15

**Solution:**
| Step | Calculation |
|------|-------------|
| Work per woman per day | 100m / (20×10) = 0.5m/day |
| For 10 women | 10×0.5 = 5m/day |
| Time for 50m | 50/5 = **10 days** |

**✅ Correct Answer: (B) 10**

---

### Question 10
> **A man can work equivalent to 2 boys. If 12 men can do work in 66 days, in how many days will 15 men and 6 boys complete the work?**

**Options:** A) 44 days B) 55 days C) 66 days D) 60 days

**Solution:**
| Step | Calculation |
|------|-------------|
| 6 boys = 3 men | (since 1 man = 2 boys) |
| Total men | 15 + 3 = 18 men |
| Time | 66 × 12 / 18 = **44 days** |

**✅ Correct Answer: (A) 44 days**

---

### Question 11
> **A can complete work in 20 days and B in 30 days. Only half of the work has to be done before vacations. Find the number of days in which A and B can complete the work together.**

**Options:** A) 6 days B) 8 days C) 10 days D) 12 days

**Solution:**
| Step | Calculation |
|------|-------------|
| Total Work | LCM(20,30) = 60 units |
| A's efficiency | 60/20 = 3 units/day |
| B's efficiency | 60/30 = 2 units/day |
| Combined | 5 units/day |
| Half work | 60/2 = 30 units |
| Time | 30/5 = **6 days** |

**✅ Correct Answer: (A) 6 days**

---

### Question 12
> **A and B can complete work in 15 days, B alone in 20 days. Find number of days in which A alone can do the work.**

**Options:** A) 20 days B) 30 days C) 60 days D) 45 days

**Solution:**
| Step | Calculation |
|------|-------------|
| Total Work | LCM(15,20) = 60 units |
| A+B efficiency | 60/15 = 4 units/day |
| B's efficiency | 60/20 = 3 units/day |
| A's efficiency | 4-3 = 1 unit/day |
| **A's time** | 60/1 = **60 days** |

**✅ Correct Answer: (C) 60 days**

---

### Question 13
> **A can complete work in 12 days and B in 18 days. If they work together for 2 days and then A leaves, how long will B take to complete the rest?**

**Options:** A) 26 days B) 23 days C) 13 days D) 18 days

**Solution (LCM Method):**
| Step | Calculation |
|------|-------------|
| Total Work | LCM(12,18) = 36 units |
| A's efficiency | 36/12 = 3 units/day |
| B's efficiency | 36/18 = 2 units/day |
| Combined | 5 units/day |
| Work in 2 days | 5×2 = 10 units |
| Remaining | 36-10 = 26 units |
| Time for B | 26/2 = **13 days** |

**✅ Correct Answer: (C) 13 days**

---

### Question 14
> **A and B can complete work together in 30 days. They work together for 20 days, then B leaves. A completes remaining work in 20 days. Find A alone's time.**

**Options:** A) 60 days B) 20 days C) 30 days D) 45 days

**Solution:**
| Step | Calculation |
|------|-------------|
| Work in 20 days | 20/30 = 2/3 |
| Remaining | 1 - 2/3 = 1/3 |
| A does 1/3 in 20 days | So A does whole in 20×3 = **60 days** |

**✅ Correct Answer: (A) 60 days**

---

### Question 15
> **A work can be done by 2 men and 3 women in 10 days. The same work can be done by 3 men and 2 women in 8 days. Find how long will it take 2 men and 1 woman to do the complete work.**

**Options:** A) 12 days B) 12.5 days C) 10 days D) 11 days

**Solution:**
| Step | Calculation |
|------|-------------|
| Equate work | 20 men + 30 women = 24 men + 16 women |
| Relation | 2 men = 7 women |
| 2 men + 1 woman | = 7 + 1 = 8 women |
| 2 men + 3 women | = 7 + 3 = 10 women |
| 10 women = 10 days | 8 women = 10×10/8 = **12.5 days** |

**✅ Correct Answer: (B) 12.5 days**

---

## 🚿 PART 5: PIPES & CISTERNS

**Rule:** Inlet = Positive (+), Outlet/Leak = Negative (-).

---

### Example: One Inlet + One Outlet
> **Q:** Fill pipe = 8 hrs, Empty pipe = 16 hrs. Time to fill if both open?

| Step | Calculation |
|------|-------------|
| Total Work | LCM(8,16) = 16 units |
| Efficiencies | Inlet = +2, Outlet = -1 |
| Net | 2 - 1 = 1 unit/hr |
| **Time** | 16/1 = **16 hours** |

---

### Example: Two Inlets + One Outlet
> **Q:** Two fill pipes = 12 min & 15 min. Waste pipe empties. All together fill in 20 min. How long for waste pipe alone to empty?

| Step | Calculation |
|------|-------------|
| Total Work | LCM(12,15,20) = 60 units |
| Efficiencies | Pipe1 = +5, Pipe2 = +4, All 3 = +3 |
| Waste pipe | 3 - (5+4) = -6 units/min |
| **Time to empty** | 60/6 = **10 min** |

---

### Example: Fill Half Tank
> **Q:** A fills in 12 hrs, B empties in 20 hrs. Time to fill **half** the tank?

| Step | Calculation |
|------|-------------|
| Total Work | LCM(12,20) = 60 units |
| Efficiencies | A = +5, B = -3 → Net = +2 units/hr |
| Half work | 60/2 = 30 units |
| **Time for half** | 30/2 = **15 hours** |

---

## ⚡ PART 6: QUICK FORMULAS & SHORTCUTS

### For Two Workers/Pipes
| Situation | Formula |
|-----------|---------|
| A & B together (both filling) | `(A×B) / (A+B)` |
| One fills, one empties | `(A×B) / (B – A)` (where B > A) |

### If Someone is "x%" as Efficient
If B is **twice** as efficient as A, then B's time = **half** of A's time.

---

## ✅ COMPLETE ANSWER KEY

| Q.No | Answer |
|------|--------|
| 1 | A (216) |
| 2 | D (423) |
| 3 | B (324) |
| 4 | C (111) |
| 5 | C (4 days) |
| 6 | D (120 days) |
| 7 | C (16/3 days) |
| 8 | C (17100) |
| 9 | B (10 days) |
| 10 | A (44 days) |
| 11 | A (6 days) |
| 12 | C (60 days) |
| 13 | C (13 days) |
| 14 | A (60 days) |
| 15 | B (12.5 days) |

---

## 📥 QUICK REFERENCE CARD

```text
TOTAL WORK = LCM of all times
EFFICIENCY = Total Work / Individual Time
NET EFFICIENCY = Sum(Inlets) - Sum(Outlets)
TIME = Total Work / Net Efficiency

LCM of fractions = LCM(Numerators) / HCF(Denominators)
HCF of fractions = HCF(Numerators) / LCM(Denominators)

HCF × LCM = Product of two numbers
Last digit of product = Multiply only unit digits
```

---

**This is the complete guide with all 15 questions and solutions!** 🚀