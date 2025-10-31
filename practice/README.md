# ThinkStats2 Practice Project

A project to practice statistical concepts and code examples from the ThinkStats book.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Selecting the Python Interpreter](#selecting-the-python-interpreter)
- [Select the Notebook Kernel](#select-the-notebook-kernel)
- [Project Structure](#project-structure)
- [Chapters](#chapters)
  - [Chapter 1: Exploratory Data Analysis](#chapter-1-exploratory-data-analysis)
  - [Chapter 2: Distributions](#chapter-2-distributions)
  - [Chapter 3: Probability Mass Functions](#chapter-3-probability-mass-functions)
  - [Chapter 4: Cumulative Distribution Functions](#chapter-4-cumulative-distribution-functions)
  - [Chapter 5: Modeling Distributions](#chapter-5-modeling-distributions)
  - [Chapter 6: Probability Density Functions](#chapter-6-probability-density-functions)
  - [Chapter 7: Relationships Between Variables](#chapter-7-relationships-between-variables)
  - [Chapter 8: Estimation](#chapter-8-estimation)
  - [Chapter 9: Hypothesis Testing](#chapter-9-hypothesis-testing)
  - [Chapter 10: Linear Least Squares](#chapter-10-linear-least-squares)
  - [Chapter 11: Regression](#chapter-11-regression)
  - [Chapter 12: Time Series Analysis](#chapter-12-time-series-analysis)
  - [Chapter 13: Survival Analysis](#chapter-13-survival-analysis)
  - [Chapter 14: Analytic Methods](#chapter-14-analytic-methods)
- [Key Concepts Learned](#key-concepts-learned)
- [Datasets Used](#datasets-used)
- [Tools and Libraries](#tools-and-libraries)
- [Running the Code](#running-the-code)
- [Notes and Insights](#notes-and-insights)
- [Future Work](#future-work)

## Overview

This project contains my practice implementations and explorations of statistical concepts from Allen B. Downey's "Think Stats: Exploratory Data Analysis in Python". The goal is to reinforce learning through hands-on coding and experimentation.

## Installation

This project uses Poetry for dependency management. To set up the environment:

```bash
# Install dependencies
poetry install

# Activate the virtual environment
poetry shell

# Or run commands directly
poetry run python your_script.py
```

## Selecting the Python Interpreter
In this step you need to point VS Code to the Python executable that Poetry created for your project.

1. Open the Command Palatte: `Ctrl+Shift+P`.
2. Type `Python: Select Interpreter` and press Enter.
3. A list of avaialable Python interpreters will appear. Look for an interpreter that is labeled with the "Poetry" environment created for your project, which will typically point to the path inside a `.venv` directory. If you do not see it you can always `Browse` into it. (".venv/bin/python")

## Select the Notebook Kernel
When you open the notebook, VS Code needs to know which Python environment (kernel) to use.
1. In the top-right corner of the notebook editor, click on "Select Kernel".
2. You will see a similar list of interpreters.
3. Choose the same Poetry environment you selected in Step 3 above.

## Project Structure

```
practice/
├── code/           # Practice scripts and notebooks
├── data/           # Datasets (if any)
|── src/            # source modules
├── tests/          # Unit tests
└── utils/          # Utility functions
```

## Chapters

### Chapter 1: Exploratory Data Analysis
*Add your notes and code examples here*

- [ ] Basic data exploration techniques
- [ ] Summary statistics
- [ ] Data cleaning and preparation

**Key Files:**
- `code/chapter01_practice.py`
- `notebooks/chapter01_exploration.ipynb`

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 2: Distributions
*Add your notes and code examples here*

- [ ] Histograms
- [ ] Probability Mass Functions (PMFs)
- [ ] Central tendency and spread

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 3: Probability Mass Functions
*Add your notes and code examples here*

- [ ] PMF operations
- [ ] Comparing distributions
- [ ] Outliers and skewness

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 4: Cumulative Distribution Functions
*Add your notes and code examples here*

- [ ] CDF implementation
- [ ] Percentiles and quantiles
- [ ] Comparing CDFs

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 5: Modeling Distributions
*Add your notes and code examples here*

- [ ] Exponential distributions
- [ ] Normal distributions
- [ ] Lognormal distributions

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 6: Probability Density Functions
*Add your notes and code examples here*

- [ ] PDF concepts
- [ ] Kernel density estimation
- [ ] Continuous distributions

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 7: Relationships Between Variables
*Add your notes and code examples here*

- [ ] Scatter plots
- [ ] Correlation
- [ ] Covariance

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 8: Estimation
*Add your notes and code examples here*

- [ ] Point estimation
- [ ] Confidence intervals
- [ ] Bootstrap methods

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 9: Hypothesis Testing
*Add your notes and code examples here*

- [ ] Null and alternative hypotheses
- [ ] p-values
- [ ] Statistical significance

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 10: Linear Least Squares
*Add your notes and code examples here*

- [ ] Linear regression
- [ ] Residuals
- [ ] Goodness of fit

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 11: Regression
*Add your notes and code examples here*

- [ ] Multiple regression
- [ ] Non-linear relationships
- [ ] Model validation

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 12: Time Series Analysis
*Add your notes and code examples here*

- [ ] Time series patterns
- [ ] Trend analysis
- [ ] Forecasting

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 13: Survival Analysis
*Add your notes and code examples here*

- [ ] Survival functions
- [ ] Hazard functions
- [ ] Kaplan-Meier estimation

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

### Chapter 14: Analytic Methods
*Add your notes and code examples here*

- [ ] Analytic solutions
- [ ] Numerical methods
- [ ] Performance comparison

**Key Files:**
<!-- Add your file references -->

**Notes:**
<!-- Add your insights and observations -->

---

## Key Concepts Learned

<!-- Add major insights and concepts as you progress -->

- **Statistical Thinking**:
- **Data Visualization**:
- **Hypothesis Testing**:
- **Regression Analysis**:

## Datasets Used

<!-- List and describe datasets you work with -->

- **NSFG (National Survey of Family Growth)**:
- **BRFSS (Behavioral Risk Factor Surveillance System)**:
- **Custom datasets**:

## Tools and Libraries

- **Python**: Core programming language
- **NumPy**: Numerical computations
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **SciPy**: Scientific computing
- **Jupyter**: Interactive notebooks
- **NetworkX**: Network analysis
- **SymPy**: Symbolic mathematics
- **EmpiricalDist**: Empirical distributions
- **StatsModels**: Statistical modeling
- **StataDict**: Stata dictionary files

## Running the Code

```bash
# Run a specific script
poetry run python code/chapter01_practice.py

# Start Jupyter notebook
poetry run jupyter notebook

# Run tests
poetry run pytest
```

## Notes and Insights

<!-- Add your personal notes, insights, and discoveries -->

### General Observations
-

### Challenges Encountered
-

### Interesting Findings
-

## Future Work

<!-- Add ideas for extending the project -->

- [ ] Implement additional statistical methods
- [ ] Create interactive visualizations
- [ ] Apply concepts to real-world datasets
- [ ] Build a statistical analysis toolkit

---

*Last updated: [Date]*

**Progress**: Chapter X of 14 completed