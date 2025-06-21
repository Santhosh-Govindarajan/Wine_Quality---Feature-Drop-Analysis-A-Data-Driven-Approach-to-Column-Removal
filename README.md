# Wine_Quality---Whether-to-remove-column-or-not-

# Feature Drop Analysis – A Data-Driven Approach to Column Removal

## 📌 Overview

Choosing which columns to drop in a dataset isn't always straightforward. This repository provides a structured approach to:
- Understand column relevance logically
- Use correlation analysis to detect direct/indirect relationships
- Apply statistical hypothesis testing to determine column independence

## 🧠 Methods Covered
- **Domain-based Logical Analysis**
- **Correlation Matrix Interpretation**
- **Chi-Square Test (Categorical vs Categorical)**
- **Two-Sample T-Test (Continuous vs Continuous)**
- **ANOVA Test (Categorical vs Continuous)**

## 📁 Files Included
- `feature_analysis.ipynb`: Complete Jupyter Notebook with all methods
- `sample_dataset.csv`: Dummy dataset for testing
- `README.md`: This file

## 📊 Output
The notebook outputs:
- Columns flagged for dropping --> As the Data is distributed properly there is no need to remove any column is the outcome
- Visuals (heatmaps, p-value tables)

## 🔧 Requirements
- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scipy
