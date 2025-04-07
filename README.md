# Task-1-Data-Cleaning-and-Preprocessing

# Netflix Titles Dataset Cleaning

## Objective
The goal of this task was to clean and prepare a raw dataset of Netflix titles by handling missing values, removing duplicates, standardizing formats, and ensuring consistency in data types.

---

## Tools Used
- Python
- Pandas library
- Jupyter Notebook / VS Code

---

## Data Cleaning Steps

1. **Renamed Columns**  
   - Standardized all column headers to lowercase and replaced spaces with underscores.

2. **Handled Missing Values**  
   - Filled missing `director`, `cast`, and `country` values with `'Unknown'`.
   - Replaced missing `rating` values with `'Unrated'`.
   - Parsed `date_added` to datetime format; handled remaining missing entries.

3. **Removed Duplicates**  
   - Dropped duplicate rows to ensure data integrity.

4. **Standardized Text Formats**  
   - Cleaned text columns like `type`, `country`, and `rating` for consistency.

5. **Processed Duration Field**  
   - Split `duration` into two new columns: `duration_num` and `duration_type`.

6. **Ensured Correct Data Types**  
   - Converted `release_year` to integer and `date_added` to datetime.

---

## Files Included
- `Netflix_movies_and_tv_shows_clustering` – Original dataset (if allowed)
- `cleaned_netflix_data.csv` – Cleaned dataset
- `Data-Cleaning-and-Preprocessing.py` – Python script used for cleaning
- `README.md` – This file

---

## Outcome
A clean, structured dataset ready for analysis or visualization, with all nulls (except handled ones), duplicates, and inconsistencies resolved.

---

