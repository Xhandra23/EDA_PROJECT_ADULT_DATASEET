# Adult Income Dataset – Exploratory Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Adult Income dataset using Python and Pandas.

The analysis explores demographic, education, employment, working-hours, capital-gain/loss, and income-related information.

## Dataset
- File: `data/adult.csv`
- Records: 32,561
- Columns: 15
- Target column: `Income`

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- AutoViz
- Sweetviz
- D-Tale
- ydata-profiling
- Jupyter Notebook

## Project Structure

```text
Adult-Income-EDA/
├── data/
│   └── adult.csv
├── notebooks/
│   └── EDA_project.ipynb
├── reports/
│   └── (generated reports go here)
├── .gitignore
├── requirements.txt
└── README.md
```

## Analysis Performed
1. Loaded the dataset with Pandas.
2. Inspected rows, columns, shape, data types, counts, and descriptive statistics.
3. Calculated basic statistics such as mean, minimum, maximum, and median.
4. Selected and filtered records using Pandas.
5. Checked missing values.
6. Replaced `?` values and handled missing values in selected columns.
7. Created visualizations for age and capital-gain patterns.
8. Explored automated EDA using AutoViz, Sweetviz, D-Tale, and ydata-profiling.

## How to Run

### 1. Clone the repository
```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd Adult-Income-EDA
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Open the notebook
```bash
jupyter notebook notebooks/EDA_project.ipynb
```

## Git Commands

```bash
git init
git add .
git commit -m "Initial Adult Income EDA project"
git branch -M main
git remote add origin <YOUR_GITHUB_REPOSITORY_URL>
git push -u origin main
```

## Resume Project Description

**Adult Income Dataset – Exploratory Data Analysis:** Performed data cleaning, statistical analysis, missing-value handling, filtering, and visualization on 32K+ records using Python, Pandas, NumPy, Matplotlib, and Seaborn, with automated EDA using popular profiling tools.

## Note
The notebook was originally created in a Google Colab-style environment. The dataset path has been changed to a relative project path so it can be used in a GitHub repository.
