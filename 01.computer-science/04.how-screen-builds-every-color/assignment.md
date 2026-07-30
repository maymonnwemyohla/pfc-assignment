# Assignment 04: How Screen Builds Every Color?

Welcome to Assignment 04!

In this lesson, we explored how digital screens display millions of vibrant colors using tiny sub-pixels based on the **RGB (Red, Green, Blue)** color model, how color depth determines image quality, and how image file sizes are calculated.

To test your understanding of digital colors and pixel mechanics, please complete the following tasks.

---

## 🎯 Task

Answer the following questions accurately in your `solution.md` file.

### 1. Concept Questions
* **(a)** Explain briefly how a computer screen creates various colors (like Yellow or White) using only **Red, Green, and Blue** light.
* **(b)** Why does standard digital color use **8 bits (1 byte) per color channel** (R, G, B)? How many total color channels are in a standard pixel, and how many total bits does a full RGB pixel use?

### 2. RGB Values & Hex Codes
* **(a)** In an 8-bit per channel RGB system, each color channel ranges from `0` to `255`. State the RGB values for the following colors:
  * **Pure Red:** `RGB( ____, ____, ____ )`
  * **Pure White:** `RGB( ____, ____, ____ )`
  * **Pure Black:** `RGB( ____, ____, ____ )`
* **(b)** Hexadecimal (Hex) color codes convert RGB values into base-16 representations. Express the RGB value `RGB(255, 0, 0)` as a **6-digit Hex Code** (e.g., `#FFFFFF`).

### 3. Resolution & Image Memory Calculation
Consider an uncompressed digital photo with a resolution of **1920 × 1080 pixels** (Full HD) using **24-bit True Color** (3 Bytes per pixel):

* **(a)** How many total **pixels** are on this screen/image?
* **(b)** Calculate the total raw file size in **Bytes**. *(Show your calculation step)*
* **(c)** Convert the total size into **Megabytes (MB)**. *(Note: 1 MB = 1,024 × 1,024 Bytes or 1,048,576 Bytes)*

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
# 1. Create and switch to a new branch for CS Assignment 04
git switch -c assignment/cs-ep-04

# 2. Check the status of your changed files
git status

# 3. Stage the solution file
git add .

# 4. Commit your changes
git commit -m "CS Episode 04: RGB and Pixels"

# 5. Push the new branch to your forked repository
git push origin assignment/cs-ep-04
```

**Final Step:** Go to your forked repository on GitHub, switch to the `assignment/cs-ep-04` branch, and click **"Compare & pull request"** to submit your assignment to the main repository for review.

## ⏰ Deadline

**Due Date:** 2026-07-07