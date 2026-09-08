# Axion Ray Steering Wheel Repair Analysis

Automotive repair data analysis project involving data validation, cleaning, dataset integration, NLP-based complaint tagging, and exploratory data analysis to identify recurring steering wheel failures and root causes.

## Project Overview

This project analyzes steering wheel repair and order datasets to uncover recurring defects, cost drivers, and operational trends. The workflow includes:

- Data validation and cleaning
- Handling messy real-world datasets
- Dataset integration and preprocessing
- NLP-based complaint tagging
- Exploratory Data Analysis (EDA)
- Root cause identification
- Stakeholder reporting

---

## Repository Structure

```text
axionray-steering-wheel-analysis/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── final/
│
├── notebooks/
├── reports/
├── visuals/
├── src/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Key Findings

- Heated steering wheel failures were among the most frequent high-cost defects.
- Leather/stitching issues indicated recurring supplier quality problems.
- Labor cost strongly correlated with total repair cost.
- Horn harness failures suggested potential assembly defects.
- Colder regions showed increased heated steering wheel failures.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Included Assets

### Raw Datasets
- Original messy Task 1 and Task 2 datasets

### Processed Datasets
- Cleaned repair records
- Integrated datasets
- Final analytical outputs

### Notebook
- Full EDA and preprocessing workflow

### Reports
- Stakeholder-facing summary report

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open:

```text
notebooks/steering_wheel_analysis.ipynb
```

---

## Author

Abhishek Kumar
