# CodSoft Data Analytics Internship

This repository contains my work for the **CodSoft Data Analytics Internship**. I completed four tasks focused on data cleaning, exploratory data analysis, data visualization, and customer data analysis using Python, Pandas, and Power BI.

## Intern Details

- **Name:** Jeevan Raj
- **Internship:** CodSoft Data Analytics Internship
- **Tasks completed:** Tasks 1–4
- **GitHub repository:** https://github.com/acharya02005-tech/as-CODSOFT_TASKSNO

## Project Overview

| Task | Title | Main tools | Status |
|---|---|---|---|
| Task 1 | Data Cleaning and Preprocessing | Python, Pandas | Completed |
| Task 2 | Exploratory Data Analysis (EDA) | Python, Pandas, visualization libraries | Completed |
| Task 3 | Data Visualization and Power BI Dashboard | Python, Pandas, Power BI | Completed |
| Task 4 | Customer Data Analysis | Power BI | Completed |


## Task 1: Data Cleaning and Preprocessing

**Notebook:** `CODSOFT_Task1_Data_Cleaning.ipynb`  
**Output dataset:** `superstore_cleaned.csv`

### Work performed
- Inspected the dataset for missing values and duplicate rows.
- Removed rows with missing fields where appropriate.
- Reviewed and standardized text values and whitespace.
- Converted date and numeric columns to suitable data types.
- Reviewed postal-code values and handled missing postal codes.
- Checked the cleaned data for remaining missing values and duplicates.
- Exported the cleaned dataset to CSV for use in later tasks.

### Dataset summary
- Original shape: **10,800 rows × 21 columns**
- Cleaned shape: **9,994 rows × 21 columns**
- Exact duplicate rows identified: **0**
- Missing values remaining after cleaning: **0**

## Task 2: Exploratory Data Analysis (EDA)

**Notebook:** `CODSOFT_Task2_EDA.ipynb`  
**Input dataset:** `superstore_cleaned.csv`

### Work performed
- Generated descriptive statistics.
- Examined sales and profit by category.
- Compared sales across regions.
- Explored monthly sales trends.
- Investigated potential outliers using the IQR method.
- Examined relationships between numerical variables using correlation analysis.
- Summarized findings as business insights.

### Key findings

- **Total Sales:** $2,297,200.86
- **Total Profit:** $286,397.02
- **Average Discount:** 15.62%
- **Distinct Orders:** 5,009

#### Sales by category

| Category | Sales |
|---|---:|
| Furniture | $741,999.80 |
| Office Supplies | $719,047.03 |
| Technology | $836,154.03 |

Technology had the highest sales among the three categories.

#### Profit by category

| Category | Profit |
|---|---:|
| Furniture | $18,451.27 |
| Office Supplies | $122,490.80 |
| Technology | $145,454.95 |

Technology generated the highest profit, while Furniture generated considerably less profit than the other categories.

#### Sales by region

| Region | Sales |
|---|---:|
| West | $725,457.82 |
| East | $678,781.24 |
| Central | $501,239.89 |
| South | $391,721.91 |

The West region had the highest sales, while the South region had the lowest sales among the four regions.

### Correlation observations

- Sales and Profit: `0.48`
- Sales and Quantity: `0.20`
- Sales and Discount: `-0.03`
- Quantity and Profit: `0.07`
- Discount and Profit: `-0.22`
- Quantity and Discount: `0.01`

These are correlations, not proof of causation. The negative correlation between discount and profit suggests that higher discounts may be associated with lower profit in this dataset.

## Task 3: Data Visualization and Power BI Dashboard

**Python notebook:** `CODSOFT_Task3_Data_Visualization.ipynb`  
**Power BI file:** `CODSOFT_Task3_Superstore_Sales_Dashboard.pbix`  
**Input dataset:** `superstore_cleaned.csv`

### Python visualizations
- Sales by category (bar chart)
- Sales distribution by category (pie chart)
- Monthly sales trend
- Sales distribution (histogram)
- Sales versus profit (scatter plot)
- Profit by category (box plot)
- Correlation heatmap

### Power BI dashboard
The Superstore dashboard includes:
- KPI cards for total sales, total profit, total orders, and average discount
- Sales by region
- Monthly sales trend
- Sales by category
- Product and customer insights
- Interactive slicers/filters for exploring the data

## Task 4: Customer Data Analysis

**Power BI file:** `CODSOFT_Task4_Customer_Data_Analysis.pbix`  
**Input dataset:** Superstore cleaned dataset

### Dashboard components
- KPI cards for total customers, total sales, and total profit
- Top 10 customers by sales
- Customer sales by segment
- Sales by state
- Interactive slicers for region, segment, and state
- Business insights and marketing recommendations

### Key observations
- The report showed **793 distinct customers**.
- The Consumer segment generated approximately **$1.16 million** in sales.
- The Corporate segment generated approximately **$0.71 million** in sales.
- The Home Office segment generated approximately **$0.43 million** in sales.
- California and New York were among the highest-sales states shown in the state analysis.

### Possible business recommendations
- Explore loyalty initiatives for repeat customers.
- Tailor marketing messages to different customer segments.
- Investigate opportunities in states and regions with lower sales.
- Review product-level profitability and discount patterns before planning promotions.

These are possible actions suggested by the analysis; their effectiveness would need to be tested against additional data.

## Tools and Technologies

- **Python** — data preparation and analysis
- **Pandas** — data manipulation and cleaning
- **Matplotlib / Seaborn** — Python data visualization
- **Power BI Desktop** — interactive reports and dashboards
- **Jupyter Notebook / Google Colab** — notebook environment
- **GitHub** — version control and sharing

## Repository Contents

The repository should include the following deliverables (adjust file names below if your actual repository uses different names):

```text
CODSOFT_TASKSNO/
├── CODSOFT_Task1_Data_Cleaning.ipynb
├── superstore_cleaned.csv
├── CODSOFT_Task2_EDA.ipynb
├── CODSOFT_Task3_Data_Visualization.ipynb
├── CODSOFT_Task3_Superstore_Sales_Dashboard.pbix
├── CODSOFT_Task4_Customer_Data_Analysis.pbix
└── README.md
```

## How to Use

### View the notebooks
1. Open an `.ipynb` notebook in GitHub to view its code and outputs.
2. To run or modify a notebook, open it in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Make sure `superstore_cleaned.csv` is available at the location expected by notebooks that use it.

### Open the Power BI reports
1. Download the relevant `.pbix` file from the repository.
2. Open it in Power BI Desktop.
3. If Power BI requests the source CSV, select `superstore_cleaned.csv` or the path used in your report.
4. Refresh the data if required.

## Learning Outcomes

Through these tasks, I practiced:
- Identifying and handling data quality issues.
- Preparing a consistent dataset for analysis.
- Exploring category performance, regional sales, trends, and relationships.
- Building charts to communicate findings.
- Creating interactive Power BI reports with KPI cards and slicers.
- Translating analytical observations into potential business recommendations.
- Organizing and sharing project deliverables through GitHub.

## Repository Link

[View my CodSoft internship project repository](https://github.com/acharya02005-tech/as-CODSOFT_TASKSNO)

## Acknowledgement

Thank you to **CodSoft** for providing an opportunity to practice data analytics through hands-on tasks.

---

*This README summarizes the work completed in this repository. Findings are based on the Superstore dataset used for the tasks. Business recommendations are exploratory and should be validated before real-world implementation.*
