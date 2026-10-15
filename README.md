# CodSoft Data Analytics Internship

## Task 1: Data Cleaning and Preprocessing

### Objective
Clean and preprocess the Sample Superstore dataset using Python and Pandas.

### Tools Used
- Python
- Pandas
- Google Colab
- Microsoft Excel

### Tasks Completed
- Imported and explored the dataset.
- Identified and handled missing values.
- Removed 806 highly incomplete records.
- Checked for duplicate records.
- Converted Order Date and Ship Date to datetime format.
- Ensured Sales, Quantity, Discount, and Profit were numeric.
- Removed unnecessary leading and trailing spaces from text fields.
- Validated and exported the cleaned dataset.

### Results

| Metric | Result |
|---|---:|
| Original rows | 10,800 |
| Rows removed | 806 |
| Final rows | 9,994 |
| Columns | 21 |
| Missing values remaining | 0 |
| Duplicate rows remaining | 0 |

### Project Files
- `CODSOFT_Task1_Data_Cleaning.ipynb` — notebook containing the code and outputs.
- `superstore_cleaned.csv` — cleaned dataset.

### Conclusion
The dataset was cleaned and validated using Pandas. The final dataset contains 9,994 rows and 21 columns, with zero missing values and zero exact duplicate rows reported during validation.
