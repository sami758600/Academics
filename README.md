# 🎓 Academics Repository  

This repository contains my **academic learning journey** — including Data Structures & Algorithms (DSA) practice, computer science fundamentals, and subject-based projects.  
I’ll be organizing problem-solving progress, notes, and mini-projects here.  

---

## 📂 Repository Structure

- **academics/**
  - **dsa/** – Data Structures & Algorithms practice
    - day1/ – Problems solved on Day 1
    - day2/ – Problems solved on Day 2
  - **notes/** – Subject-wise notes (to be added later)
  - **miniprojects/** – Mini-projects & course projects (to be added later)





# 📅 DSA Practice – Day 1  

Today’s focus was on **array-based problems** from LeetCode.  
I solved 3 problems using **dictionary/hashmap** based approaches.  

---

## ✅ Problems Solved

### 1. [169. Majority Element](https://leetcode.com/problems/majority-element/)
- **Approach:**  
  - Count frequencies of elements using a dictionary.  
  - Return the element with count > ⌊n/2⌋.  
- **Code Used:** Hashmap counting.  
- **Optimization Note:** Can also be solved in O(n) time and O(1) space using the **Boyer–Moore Voting Algorithm**.

---

### 2. [229. Majority Element II](https://leetcode.com/problems/majority-element-ii/)
- **Approach:**  
  - Count frequencies using a dictionary.  
  - Collect elements appearing more than ⌊n/3⌋ times.  
- **Code Used:** Hashmap + iteration.  
- **Optimization Note:** There’s an extension of the Boyer–Moore algorithm for this problem too.

---

### 3. [217. Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
- **Approach:**  
  - Store frequencies in a dictionary.  
  - If any element count ≥ 2 → return `True`.  
- **Code Used:** Hashmap.  
- **Optimization Note:** Can be solved more cleanly using a **HashSet** by checking if an element already exists.

---

## 📊 Learnings
- Practiced using **hashmaps for frequency counting**.  
- Understood how **Boyer–Moore Voting Algorithm** works (O(1) space trick).  
- Reinforced the idea of **tradeoffs between space and time complexity**.

---


# 📅 DSA Practice – Day 2  

Today’s focus was on **math-based problems** from LeetCode involving powers of integers.  
I solved 2 problems.  

---

## ✅ Problems Solved

### 1. [342. Power of Four](https://leetcode.com/problems/power-of-four/)
- **Approach:**  
  - Used logarithms: check if `log₄(n)` is an integer.  
  - Implemented by rounding `log(n)/log(4)` and verifying with `4^a == n`.  
- **Code Used:** `math.log()` based check.  
- **Alternative Approaches:**  
  - Bit manipulation tricks (`n & (n-1) == 0` + mask check).  
  - Iterative division by 4.

---

### 2. [326. Power of Three](https://leetcode.com/problems/power-of-three/)
- **Approach:**  
  - Similar to Power of Four → check if `log₃(n)` is an integer.  
  - Verified by rounding and checking `3^a == n`.  
- **Code Used:** `math.log()` based check.  
- **Alternative Approaches:**  
  - Iterative division by 3.  
  - Using the maximum power of 3 that fits in 32-bit integer range.

---

## 📊 Learnings
- Gained confidence in applying **math + logarithms** in DSA problems.  
- Noticed potential pitfalls of **floating-point precision** with logs.  
- Explored **alternative approaches** (division vs bit manipulation).  
- Reinforced idea that **multiple paths exist** to solve the same problem.  

---

⭐ Part of my **DSA consistency challenge** — documenting progress problem by problem.

