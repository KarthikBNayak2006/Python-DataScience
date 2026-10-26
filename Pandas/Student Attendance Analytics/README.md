# Student Attendance Analytics with Pandas

Analyze student attendance from an Excel workbook with Python, Pandas, and NumPy. The notebook calculates attendance status and risk indicators, summarizes students by status, and exports CSV reports.

## Files

- `Project_Student Attendance Analytics with Pandas.ipynb` — analysis notebook.
- `csea_attendance.xlsx` — input attendance workbook.
- `critical_students.csv` — students classified as critical.
- `status_summary.csv` — attendance statistics grouped by status.
- `top_10_risk_score.csv` — ten students with the highest risk scores.

## Run the notebook

Install the required packages:

```bash
python -m pip install pandas numpy openpyxl jupyter
```

Open the notebook in Jupyter and run its cells from this directory. The notebook reads `csea_attendance.xlsx` and writes its CSV reports to the current directory.

## Data privacy

The workbook, notebook outputs, and CSV reports contain identifiable student information. Share or reuse them only when you have authorization to do so.
