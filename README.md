# Pandas Data Analysis Practice

A hands-on notebook practising core **Pandas** and **Matplotlib** skills on a sample dataset of 463 people (`sample2.csv`).

## Dataset

| Column | Description |
|---|---|
| `id` | Unique record ID |
| `f_name`, `l_name` | First and last name |
| `age` | Age (21 to 75) |
| `profession` | Occupation |
| `location` | Country or region |

## What the notebook covers

- Loading, inspecting and summarising data (`info`, `describe`, missing values)
- Selecting and dropping columns
- Filtering with single and multiple conditions (`&`, `|`)
- `loc` (label-based) vs `iloc` (position-based) indexing
- Updating values safely on a copy of the data
- `groupby` with `mean`, `max`, `size` and `agg`
- Visualization: bar charts, histogram, pie chart, horizontal bar and box plot

## Tech stack

Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

## How to run

```bash
git clone https://github.com/snehayesudas/pandas-data-analysis-practice.git
cd pandas-data-analysis-practice
pip install -r requirements.txt
jupyter notebook pandas_basics.ipynb
```

Keep `sample2.csv` in the same folder as the notebook.

## Author

Sneha Yesudas, [LinkedIn](https://www.linkedin.com/in/snehayesudas) | [GitHub](https://github.com/snehayesudas)
