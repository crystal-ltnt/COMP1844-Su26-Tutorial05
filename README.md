# COMP1844 — Summer 2026 — Tutorial 05: Statistical Analysis

### Overview

This laboratory session focuses on **Statistical Analysis**, a key topic in Mathematics and Data Science. Students will solve a range of statistics-related problems using **NumPy** and **P****andas**, which provide the data structures and functionality needed for statistical computation, and **Matplotlib** to visualise the datasets.

---

## Repository structure

```
COMP1844-Su26-Tutorial05/
├── README.md
└── LaboratorySession5.pdf
```

---

## Prerequisites

- Python 3.x
- NumPy, pandas, matplotlib
- Completion of Tutorial 04 (pandas Series & DataFrames, data preprocessing)

---

## Tasks

### Task 1: Random Dataset and Line Chart

Initialise an array containing **20 random values** from the interval `[0 .. 100]`. Visualise the values of the data points and plot the dataset using a **Line Chart**.

Libraries:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

### Task 2: Statistical Measures with NumPy

By using functions from the NumPy library, find the following statistical measures:

- Mean value
- Median value
- Range
- Standard deviation

### Task 3: pandas DataFrame

Initialise a pandas **DataFrame** with the values from the previously initialised array. Print both data structures and observe any differences in the output.

### Task 4: Descriptive Statistics with `describe`

By using the `**describe`** method from the pandas library, provide the following information for the generated dataset:

- Mean
- Lower quartile
- Median
- Upper quartile

### Task 5: Interquartile Range

Calculate the **Interquartile Range (IQR)** for the dataset.

---

## Getting Started

1. Create a new Jupyter notebook (Jupyter Notebook, JupyterLab, or VS Code).
2. Import the required libraries (`numpy`, `pandas`, `matplotlib.pyplot`).
3. Work through Tasks 1–5 in order — each task builds on the dataset generated in Task 1.

---



## References

- [NumPy Documentation](https://numpy.org/doc/)
- [NumPy — Statistics functions](https://numpy.org/doc/stable/reference/routines.statistics.html)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

---

## License

This lab session is part of the COMP1844 module at the University of Greenwich.

Laboratory Session 5 - Summer 2026
