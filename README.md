# Task 5 — Exploratory Data Analysis (EDA)

## Objective
Explore a Titanic-style passenger dataset using Pandas, Matplotlib and Seaborn. The notebook includes `.describe()`, `.info()`, `.value_counts()`, histograms, boxplots, scatter/pair plots, and a correlation heatmap.

## Deliverables
- `Task5_EDA_Analysis.ipynb` — Jupyter Notebook with analysis code and observations.
- `Task5_EDA_Findings_Report.pdf` — PDF report of findings.
- `data/titanic_style_sample.csv` — sample dataset.
- `plots/` — exported figures used in the report.
- `requirements.txt` — packages needed to run the notebook.

## Important dataset note
The included CSV is **simulated Titanic-style data**, not the original Titanic/Kaggle dataset. This was used so the project is self-contained and runnable offline. The task allows the Titanic dataset or another relevant dataset. If you choose the official Titanic dataset, replace the CSV and rerun the notebook before making claims about historical Titanic passengers.

## Run
1. Install Python 3.10+ and Jupyter.
2. Open a terminal in this folder.
3. Run `pip install -r requirements.txt`.
4. Run `jupyter notebook Task5_EDA_Analysis.ipynb`.
5. Run the cells from top to bottom.

## Findings in brief
- The dataset contains 891 rows and 9 columns.
- Age includes missing values; the notebook reports missingness and checks duplicates.
- Fare distribution is examined for skewness and potential outliers.
- Survival rates are compared across sex and passenger class.
- A correlation heatmap is included for numeric columns.

## Interview questions
Short answers to all seven interview questions from the task sheet are included at the end of the notebook and in the PDF report.
