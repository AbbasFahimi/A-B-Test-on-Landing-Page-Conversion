# A/B Test: Landing Page Conversion Analysis

This project analyzes whether a new landing page leads to a higher or lower conversion rate than the old one using A/B testing.

## 📊 Dataset

The dataset is from [Kaggle's A/B Testing dataset].  
It contains information about user visits to either the old or new version of a webpage and whether they converted.

## 🔍 Goal

Test whether the new landing page increases or decreases conversion rate using hypothesis testing.

## ✅ Steps:

- Data Cleaning (removing mismatched records and duplicates)
- Exploratory Data Analysis
- Visualization
- Hypothesis Testing using Z-test for proportions

## 🧪 Test Summary

- p-value: 0.1898
- Conclusion: No statistically significant difference found between old and new page.

## 📁 Files

- `notebooks/abtest_landingpage.ipynb`: All analysis code.
- `data/ab_data.csv`: Raw dataset.
- `images/barplot.png`: Visualizations.

## 📦 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```
