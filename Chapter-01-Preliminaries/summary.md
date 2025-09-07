# Chapter 1 — Preliminaries

**Book:** Python for Data Analysis (3rd Edition)  
**Author:** Wes McKinney (creator of pandas)

---

## 🔹 Important Definitions & Explanations

### 1. Purpose of the Book
- Focuses on **practical tools** (pandas, NumPy, etc.) for cleaning, analyzing, and visualizing data.  
- Emphasis is on **tools & workflows**, not on statistics or math theory.  

### 2. Types of Data
- **Tabular (Spreadsheet-like):** Rows & columns with mixed data types.  
- **Multidimensional arrays:** Numeric matrices (NumPy).  
- **Multiple tables:** Linked by keys (like SQL joins).  
- **Time series:** Data indexed by time (regular or irregular).  

### 3. Why Python for Data Analysis?
- **General-purpose** → used across many fields.  
- **Readable, beginner-friendly** syntax.  
- Works as a **“glue language”** to connect tools.  
- Solves the **two-language problem** → prototype + production in same language.  

### 4. Essential Python Libraries
- **NumPy:** Fast numerical arrays & math.  
- **pandas:** Tabular data with DataFrame & Series.  
- **matplotlib:** Plots and visualizations.  
- **IPython:** Interactive shell with magic commands.  
- **Jupyter Notebook:** Browser-based tool for code + output + notes.  
- **SciPy:** Scientific & mathematical functions.  
- **scikit-learn:** Machine learning toolkit.  
- **statsmodels:** Statistical models & tests.  

### 5. Installation & Setup
- Best way: Install **Anaconda/Miniconda** → includes Python + libraries.  
- Use **Jupyter Notebook** for interactive analysis.  
- Common imports:  
  ```python
  import numpy as np
  import pandas as pd
  import matplotlib.pyplot as plt
