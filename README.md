# Assignment 1 — EDS 232

**Linear Regression & Statistical Learning Concepts**

This repository contains the starter notebooks and files for Assignment 1. You will work across three tasks that build on a shared dataset comparing eDNA metabarcoding and traditional survey methods for detecting freshwater fish species.

---

## Repository Structure

```
assignment-1/
├── task1/
│   ├── hw1-task1.ipynb
│   ├── lakes_data.csv
│   └── tests/            # Autograder tests for Task 1
│       ├── q1.py
│       ├── q2.py
│       └── ...
├── task2/
│   ├── hw1-task2.ipynb
│   └── tests/            # Autograder tests for Task 2
│       ├── q1.py
│       ├── q2.py
│       └── ...
├── hw1-task3.md
├── .gitignore
└── README.md
```

---

## Tasks Overview

### Task 1 — eDNA vs. Conventional Fish Surveys: Data Wrangling (40%)

`hw1-task1.ipynb`

Explore a dataset of 68 freshwater lake surveys comparing species richness detected by eDNA metabarcoding versus conventional gear. You will load and inspect the data, compute summary statistics, filter and sort rows, create new columns, and build pivot tables using `pandas`.

**Dataset:** McElroy et al. (2020). *Calibrating environmental DNA metabarcoding to conventional surveys for measuring fish species richness.* Frontiers in Ecology and Evolution.

---

### Task 2 — Simple Linear Regression: Do the Two Methods Agree? (40%)

`hw1-task2.ipynb`

Using the same dataset, you will build a simple linear regression model from scratch using NumPy to predict traditional species richness from eDNA richness. You will then verify your results with `sklearn` and `statsmodels`, and interpret the regression output including p-values and confidence intervals.

---

### Task 3 — Statistical Learning Concepts (20%)

`hw1-task3.md`

Written responses to three conceptual exercises from ISLP Chapter 2, covering classification vs. regression, flexible vs. inflexible models, and parametric vs. non-parametric approaches.

---

## Getting Started

### 1. Fork this repository

Click **Fork** at the top right of this page to create your own copy under your GitHub account.

### 2. Clone your fork

Open a terminal and run:

```bash
git clone https://github.com/YOUR-USERNAME/assignment-1.git
cd assignment-1
```

### 3. Open the notebooks

Launch JupyterLab or your preferred environment from inside the `assignment-1` directory. Do not move notebook files out of the repository folder.

### 4. Work through the tasks

Open each file and follow the instructions. For the `.ipynb` notebooks, always **run the first cell first** to initialize the Otter autograder before attempting any exercises.

### 5. Commit and push regularly

```bash
git add .
git commit -m "describe what you completed"
git push
```

---

## Autograder (Otter Grader)

Tasks 1 and 2 use `otter-grader` for automatic feedback.

- Run the **first cell** of each notebook to initialize the grader before anything else.
- After each exercise, run the `grader.check("qN")` cell to check your answer immediately.
- Before submitting, run the final `grader.check_all()` cell and leave its output visible — Gradescope uses this output as part of your grade.
- Do **not** modify or delete any locked `grader.check()` cells.

---

## Submitting to Gradescope

1. Make a final commit and push to ensure all your work is on GitHub.
2. Go to Gradescope and open the Assignment 1 portal.
3. Select **GitHub** as your submission method.
4. Choose your forked repository and the `main` branch.

Gradescope pulls directly from your repository at the time of submission. Make sure all notebooks have been run top-to-bottom and all outputs are visible before your final push.

---
