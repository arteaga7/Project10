# Project10
This project analyzes the results of a previously conducted A/B test. Two profit analysis are performed by taking into account and without outliers in purchases. Visualizations and hypotheses tests are performed.

**Objective:** To determine if there is a significant difference in the sample proportions to make decisive decisions by using the Wilcoxon-Mann-Whitney test.

## Overview
First, the data will be analyzed taking outliers into account, then without them to determine whether these outliers distorted the A/B test. The Shapiro-Wilk test will be applied to determine whether the data are normally distributed, and the Wilcoxon-Mann-Whitney U test will also be applied to determine whether there are significant differences between groups considering the outliers. The Wilcoxon-Mann-Whitney test is used to validate proportions in independent samples without a normal distribution. In order to avoid the "seeking-problem," the cumulative sum of profits throughout the analysis is used.

Finally, some decisive conclusions are given.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy.

The Jupyter Notebook is in scripts/project10.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/Project10.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in scripts/project10.ipynb.