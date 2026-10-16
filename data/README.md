# Data

Raw data is not stored in this repository (the cleaned panel alone is about 90 MB).

Place these two files in this folder before running `notebooks/01_clean_merge.ipynb`:

| File | Source |
|---|---|
| `total_bank_data.csv` | Kaggle, *U.S. Banks Financial Quarterly Ratios* (2001–2023). Download the dataset from Kaggle and rename the file if needed. |
| `FEDFUNDS.csv` | FRED series FEDFUNDS, <https://fred.stlouisfed.org/series/FEDFUNDS>. Download at quarterly frequency (columns `observation_date`, `FEDFUNDS`). |

Notebook 01 writes `final_dataset.csv` (639,871 rows, 12 columns) into this folder. Notebooks 02 and 03 read it.
