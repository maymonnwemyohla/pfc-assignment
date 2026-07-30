# Assignment 03: How Numbers Become Letters?

Welcome to Assignment 03!

In this lesson, we explored how computers represent human readable text using numbers through character encoding standards such as **ASCII** and **Unicode (UTF-8)**, and how computers handle text length in terms of bytes.

To solidify your understanding of text encoding, please complete the following tasks.

---

## 🎯 Task

Answer the following questions accurately in your `solution.md` file.

### 1. Concept Questions

* **(a)** Explain briefly how a computer displays the character `'A'` on the screen when you press it on your keyboard. (Include the role of ASCII/Unicode).
* **(b)** What is the main difference between **ASCII** and **Unicode**? Why was Unicode created?

### 2. ASCII & Character Encoding

* **(a)** In standard ASCII, how many bits are used to represent a single character? What is the maximum number of unique characters ASCII can represent?
* **(b)** Look up or calculate the ASCII values for the word **`CAT`** in uppercase:
  * What are the decimal ASCII values for `'C'`, `'A'`, and `'T'`?
  * Convert those decimal values into **8-bit binary** representations.

### 3. Text Storage & Byte Calculation

Consider the following string:
`"Hello, World!"` (including the comma and space, total 13 characters using standard ASCII/UTF-8 single-byte characters).

* **(a)** How many **Bytes** of memory are required to store this string?
* **(b)** How many **Bits** in total is that?
* **(c)** Why do non-English characters (like Myanmar script `မင်္ဂလာပါ` or Emojis `😊`) often take up more bytes per character compared to standard English letters in UTF-8?

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
# 1. Create and switch to a new branch for CS Assignment 03
git switch -c assignment/cs-ep-03

# 2. Check the status of your changed files
git status

# 3. Stage the solution file
git add .

# 4. Commit your changes
git commit -m "CS Episode 03: ASCII & Unicode"

# 5. Push the new branch to your forked repository
git push origin assignment/cs-ep-03
```

**Final Step:** Go to your forked repository on GitHub, switch to the `assignment/cs-ep-03` branch, and click **"Compare & pull request"** to submit your assignment to the main repository for review.

## ⏰ Deadline

**Due Date:** 2026-07-06