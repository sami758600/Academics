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

⭐ This is part of my **DSA consistency challenge** — solving problems daily and documenting my progress.
