# Assignment 05: How Thousand Pages Become Ten Steps?

Welcome to Assignment 05!

In this lesson, we explored how algorithms help computers solve problems efficiently. We compared two fundamental search methods: **Linear Search** (page-by-page search) and **Binary Search** (divide-and-conquer search using alphabetical order), and learned why choosing the right algorithm impacts performance as data grows.

To test your understanding of algorithmic logic and search steps, please complete the following tasks.

---

## 🎯 Task

Answer the following questions accurately in your `solution.md` file based on the concepts from Episode 05.

### 1. Concept Questions
* **(a)** What is an **Algorithm** in Computer Science?
* **(b)** Why does **Binary Search** require the phonebook (or dataset) to be sorted alphabetically before searching? What would happen if the phonebook were randomly shuffled?

### 2. Search Method Comparison
Suppose you are searching for a name in a **1,000-page** phonebook:

* **(a)** Describe how **Linear Search** operates. In the **worst-case scenario** (e.g., the target name is on the very last page), how many steps would Linear Search take?
* **(b)** Describe how **Binary Search** operates. How does it eliminate half of the remaining pages in each step?

### 3. Step Reduction Calculation
Trace the steps of **Binary Search** when starting with **1,000 pages**:

* **(a)** Show the step-by-step reduction of remaining pages until only 1 page remains (e.g., $1000 \to 500 \to \dots$).
* **(b)** Based on your calculation, how many total steps does Binary Search take in the worst-case scenario for 1,000 pages?
* **(c)** Why does using a good algorithm become critically important when dealing with millions of records instead of just a few hundred?

---

## 📝 How to Complete the Assignment

Write your answers in the provided `solution.md` file.

> **⚠️ Important:** Do not write your answers in this `assignment.md` file.

---

## 🚀 Submission Requirements

* Answer all questions clearly and show your working steps where necessary.
* Write in your own words. *(AI-generated content is not allowed).*
* Replace all `[placeholder]` texts in `solution.md` with your actual answers.

___

## 💻 Git Submission Guide

Since we are using a Fork and Pull Request (PR) workflow, follow these steps in your Terminal:

```bash
# 1. Create and switch to a new branch for CS Assignment 05
git switch -c assignment/cs-ep-05

# 2. Check the status of your changed files
git status

# 3. Stage the solution file
git add .

# 4. Commit your changes
git commit -m "CS Episode 05: Algorithms"

# 5. Push the new branch to your forked repository
git push origin assignment/cs-ep-05
```

**Final Step:** Go to your forked repository on GitHub, switch to the `assignment/cs-ep-05` branch, and click **"Compare & pull request"** to submit your assignment to the main repository for review.

## ⏰ Deadline

**Due Date:** 2026-07-08