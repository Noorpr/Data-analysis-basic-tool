
# Data-analysis-tool 🛠️📊

This repository contains a basic yet practical Python tool that performs automatic statistical analysis on any dataset provided by the user. The primary objective is to separate and analyze **categorical** and **numerical** features, then generate corresponding `.txt` reports for each feature type.

## 🔍 Project Overview

The tool takes user input—specifically, the **feature names** from the dataset—and categorizes them based on data type. Then, it performs statistical summaries for both feature types and writes the results into two separate `.txt` files:

- `categorical_analysis.txt` — Contains frequency distributions and value counts for categorical features.
- `numerical_analysis.txt` — Includes descriptive statistics such as mean, median, standard deviation, and more for numeric features.

This project is written using **vanilla Python** with support from essential data analysis libraries:
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [SciPy](https://scipy.org/)

It reflects my growing proficiency in Python programming and working with real-world datasets using scientific libraries.

## ⚙️ How It Works

1. Load your dataset (CSV file).
2. Provide the list of features you want to analyze.
3. The tool automatically detects feature types (categorical vs numeric).
4. Analysis is performed and saved into two human-readable `.txt` files.

Example usage:
run the notebook in any environment that supports jupyter notebook

Sample output files:
```
├── categorical_analysis.txt
└── numerical_analysis.txt
```

## 📦 Dataset Information

**Source:** [E-commerce Sales Data 2024 - Kaggle](https://www.kaggle.com/datasets/datascientist97/e-commerece-sales-data-2024?select=customer_details.csv)

**Filename:** `customer_details.csv`

This dataset includes detailed information about online customer behavior such as:
- Customer demographic details
- Purchase behavior
- Contact and location information
- Sales-related metadata

It's a clean and practical dataset for beginner-to-intermediate level data analysis practice.

## ✨ Skills Illustrated

This project highlights my understanding and application of the following:
- Writing clean and modular Python code
- DataFrame manipulation with **Pandas**
- Performing mathematical and statistical computations using **NumPy** and **SciPy**
- Working with user input and file I/O operations
- Separating logic based on data types (categorical vs numerical)

## 📁 Repository Structure

```
Data-analysis-basic-tool/
├── analysis_tool.py         # Main Python script
├── categorical_analysis.txt # Output for categorical features
├── numerical_analysis.txt   # Output for numeric features
└── README.md                # This file
```

## 📌 Future Improvements

- Add automatic feature type detection without user input
- Support for visualizations (matplotlib/seaborn)
- Generate HTML or PDF summary reports
- Add unit testing for feature validation

---

> 🧠 *This simple project is a demonstration of my foundational skills in data analysis using core Python libraries and sets the stage for more advanced tools in the future.*
