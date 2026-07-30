# 💻 Java & Computer Science Training - Assignments Repository

Welcome to the **Java & Computer Science Training** assignment repository! 

This repository contains module-based assignments and solution templates. As you progress through the course modules—from Computer Science fundamentals to Object-Oriented Programming and Design Principles—you will complete hands-on assignments using a professional Git & GitHub workflow.

---

## 📂 Repository Structure

The course is organized into structured module directories:

```
.
├── 01.computer-science/                  # Computer Science Fundamentals
│   ├── 01.what-is-computer-science/
│   │   ├── assignment.md
│   │   └── solution.md
│   ├── 02.why-computers-unterstand-only-two-digits/
│   │   ├── assignment.md
│   │   └── solution.md
│   ├── 03.how-numbers-become-letters/
│   │   ├── assignment.md
│   │   └── solution.md
│   ├── 04.how-screen-builds-every-color/
│   │   ├── assignment.md
│   │   └── solution.md
│   ├── 05.how-thousand-pages-become-ten-steps/
│   │   ├── assignment.md
│   │   └── solution.md
│   └── 06.how-programmers-plan-before-they-code/
│       ├── assignment.md
│       └── solution.md
├── 02.command-line-interface/            # CLI Tools & Commands
├── 03.java-environment/                  # JDK, JRE, JVM & IDE Setup
├── 04.java-langague-basics/              # Syntax, Variables, Data Types & Control Flow
├── 05.object-oriented-programming/       # OOP Concepts (Classes, Objects, Inheritance, etc.)
├── 06.oo-design-principles/              # SOLID & Object-Oriented Design Principles
└── .gitignore
```

---

## 🚀 How to Submit Your Assignment

Follow this standard **Git Branching & Pull Request (PR)** workflow for every assignment submission:

### Step 1: Fork & Clone the Repository
1. Click the **Fork** button at the top-right corner of this repository to create a copy under your GitHub account.
2. Clone your forked repository to your local computer:
   ```bash
   git clone https://github.com/YOUR_USERNAME/repo-name.git
   cd repo-name
   ```

---

### Step 2: Create a Feature Branch
Do **NOT** work directly on the `main` branch. Always create a dedicated branch for each assignment submission (e.g., `assignment/cs-ep-06` or `assignemnt/cli-ep-02`):

```bash
# Create and switch to a new branch for your assignment
git switch -c assignment/cs-ep-06
```

---

### Step 3: Complete Your Solution
1. Navigate to the relevant module and lesson folder (e.g., `01.computer-science/06.how-programmers-plan-before-they-code/`).
2. Read the instructions in `assignment.md`.
3. Open `solution.md` in that folder and fill in your answers or code solutions.

---

### Step 4: Commit & Push Changes
Once you have completed your work, stage, commit, and push your branch to your forked repository:

```bash
# Check modified files
git status

# Stage your solution file
git add .

# Commit with a clear message
git commit -m "Complete Assignment: 01.computer-science / 06.how-programmers-plan-before-they-code"

# Push the branch to your GitHub fork
git push origin assignment/cs-ep-06
```

---

### Step 5: Submit a Pull Request (PR)
1. Go to your forked repository on GitHub.
2. Click the green **"Compare & pull request"** button.
3. Ensure the target base is set to the **Main Teacher Repository (`main` branch)** and the head is set to **Your Fork (`feature/cs-ep06` branch)**.
4. Click **"Create pull request"** to submit your assignment for automated review! 🤖

---

## 🤖 Automated Review with CodeRabbit

Once your Pull Request is submitted:
* An AI Code Reviewer (**CodeRabbit**) will automatically analyze your submitted `solution.md` against the guidelines in `assignment.md`.
* Feedback, suggestions, and review comments will be posted directly in your PR thread.

---

Happy Coding & Problem Solving! 🚀