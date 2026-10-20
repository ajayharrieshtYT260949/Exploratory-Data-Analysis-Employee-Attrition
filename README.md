# Exploratory Data Analysis — Employee Attrition

## Project Overview
This project explores employee data using Python, pandas, NumPy, Matplotlib, and Seaborn. The goal is to identify numerical patterns in employee attrition, department performance, overtime, income, job roles, and job satisfaction.

## Objectives
- Calculate summary statistics for numeric columns.
- Compare employee groups using `groupby().agg()`.
- Identify the top three numeric correlations.
- Answer five business questions with calculated results.
- Merge department budget information with employee data using `pd.merge()`.

## Project Structure
```text
.
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── notebooks/
│   └── employee_eda.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Technologies
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Run
1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install dependencies using `python -m pip install -r requirements.txt`.
4. Open `notebooks/employee_eda.ipynb` in VS Code.
5. Select the project's Python environment as the notebook kernel.
6. Run the notebook cells from top to bottom.

## Analysis Performed
- Data overview and quality checks
- Mean, median, minimum, maximum, and standard deviation
- Department, gender, and overtime comparisons
- Top three correlations among numeric variables
- Five business questions with numeric answers
- Department budget table merged using `pd.merge()`
- Department attrition visualization

## Important Notes
Department budget figures are illustrative examples, not verified company financial data. Correlation does not establish causation. Dataset findings describe the supplied data and should not automatically be generalized to other organizations.

## Results
The notebook displays the calculated statistics, group comparisons, correlations, business-question answers, merge results, and chart.

## Dataset Attribution
Retain the original dataset source and applicable license or usage terms here. Include the original source URL and attribution when known.
