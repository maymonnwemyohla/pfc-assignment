# Assignment 06: How Programmers Plan Before They Code

Welcome to Assignment 06!

In this lesson, we explored how programmers use **Pseudocode** as a blueprint to plan and structure program logic before writing actual code in programming languages like Java, Python, or JavaScript. We learned key concepts such as `Input`, `Actions` (Verbs), `Decisions` (`IF/ELSE`), `Repetition` (`REPEAT/UNTIL`), and `Output`.

To test your ability to structure logic into structured Pseudocode, please complete the following tasks.

---

## 🎯 Task

Answer the following questions and write your Pseudocode solution in your `solution.md` file.

### 1. Concept Questions
* **(a)** What is **Pseudocode**, and why do programmers use it before writing real code?
* **(b)** Match each Pseudocode keyword to its correct function:
  * Keywords: `INPUT`, `OUTPUT`, `SET`, `IF / ELSE`, `REPEAT / UNTIL`
  * Functions:
    1. Check conditions and make decisions.
    2. Loop or repeat actions until a condition is met.
    3. Display a message or result to the user.
    4. Store or update a value in a variable.
    5. Receive data or response from the user.

### 2. Coffee-Making Logic Analysis
Refer to the Coffee-Making Pseudocode from Episode 06:
* Identify which line(s) represent a **Decision**, which represent a **Repetition (Loop)**, and which represent an **Action Verb**.

### 3. Pseudocode Challenge: Automatic Washing Machine

Write a structured Pseudocode program for an **Automatic Washing Machine** in `solution.md` following these rules:

1. **Start & Setup:** Begin with `START`. Set `washStatus = "IDLE"`.
2. **Input:** Ask the user to choose the wash cycle (`washCycle`) and check if hot water is needed (`hotWaterChoice`).
3. **Decision (`IF / ELSE`):**
   * If `hotWaterChoice` is `"YES"`, turn on the heater (`OUTPUT "Heating water..."`).
   * Otherwise (`ELSE`), output `"Using cold water..."`.
4. **Action Steps:** Fill water, add detergent.
5. **Repetition (`REPEAT / UNTIL`):**
   * Spin the wash drum (`SPIN drum`).
   * Repeat spinning UNTIL `washTimer` reaches 0.
6. **Finish:** Drain water, set `washStatus = "FINISHED"`, display a beep message, and end with `END`.

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
# 1. Create and switch to a new branch for CS Assignment 06
git switch -c assignment/cs-ep-06

# 2. Check the status of your changed files
git status

# 3. Stage the solution file
git add .

# 4. Commit your changes
git commit -m "CS Episode 06: Psuedo code"

# 5. Push the new branch to your forked repository
git push origin assignment/cs-ep-06
```

**Final Step:** Go to your forked repository on GitHub, switch to the `assignment/cs-ep-06` branch, and click **"Compare & pull request"** to submit your assignment to the main repository for review.

## ⏰ Deadline

**Due Date:** 2026-07-09