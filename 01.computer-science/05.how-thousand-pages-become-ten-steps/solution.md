# 📝 Solution: How Thousand Pages Become Ten Steps?

**Student Name:** May Mon Nwe Myo Hla
**Date:** 2026-08-08

---

### Task 1: Concept Questions

#### (a) Definition of an Algorithm
* **Answer:**
  > An algorithm is a step-by-step of rules or instructions used to solve a problem, perform a calculation, or complete a task.

#### (b) Importance of Alphabetical Order (Sorted Data)
* **Why sorting is required for Binary Search:** Sorting is required for Binary Search because the algorithm relies on the predictable ordering of elements to eliminate half of the remaining search space with every single step.
* **What happens if data is unsorted:** When data is unsorted, search operations become slower because algorithms must check every single item one by one.
---

### Task 2: Search Method Comparison

#### (a) Linear Search
* **How it works:** Linear Search works by checking every element in a data collection sequentially from start to finish until it finds the target value.
* **Worst-case steps for 1,000 pages:** 1000 steps

#### (b) Binary Search
* **How it works:** Binary search is a fast way to find an item in a sorted list. It works by checking the middle item first, comparing it to your target, and throwing away half of the remaining choices because the data is in order.

---

### Task 3: Step Reduction Calculation

#### (a) Step-by-Step Reduction (Starting with 1,000 pages)
* **Step 1:** 1,000 ÷ 2 = `500` pages remaining
* **Step 2:** 500 ÷ 2 = `250` pages remaining
* **Step 3:** `250` ÷ 2 = `125` pages remaining
* **Step 4:** `125` ÷ 2 = `62.5` pages remaining
* **Step 5:** `62.5` ÷ 2 = `31.25` pages remaining
* **Step 6:** `31.25` ÷ 2 = `15.625` pages remaining
* **Step 7:** `15.625` ÷ 2 = `7.8125` pages remaining
* **Step 8:** `7.8125` ÷ 2 = `3.90625` pages remaining
* **Step 9:** `3.90625` ÷ 2 = `1.953125` pages remaining
* **Step 10:** `1.953125` ÷ 2 = `0.9765625` page remaining

#### (b) Total Steps for Binary Search
* **Answer:** `≈` 10 steps

#### (c) Impact on Large Datasets (Millions of Data)
* **Answer:**
  > Algorithm choice is critical for large datasets because a poor choice can cause systems to crash or take days to finish a task that a better algorithm could complete in a second.When data grows into millions of rows, the differences between algorithm efficiencies change from minor details into massive performance gaps.

---