# Data-Immersion-Wrangling
# Task 1: Data Immersion & Wrangling

## Objective
To understand, assess, clean, and transform a sales dataset into an analysis-ready format.

## Tools Used
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## Tasks Performed
1. Loaded and explored the sales dataset.
2. Examined missing values and duplicate records.
3. Standardized categorical text and converted data types.
4. Handled missing Age and City values.
5. Created customer age groups.
6. Validated sales totals against Quantity × Unit_Price.
7. Exported the cleaned dataset.

## Deliverables
- `cleaned_sales_dataset.csv` — cleaned dataset
- `cleaned_sales_dataset.xlsx` — Excel output
- `data_dictionary.csv` — column descriptions
- `data_quality_report.txt` — data quality summary
- `Task1_Data_Wrangling.ipynb` — analysis notebook

## Results
The original dataset contains 1,000 rows and 12 columns. The cleaning workflow produces a dataset with 15 columns, including derived age groups and sales validation fields.

## Note
Repeated Order_ID values should be reviewed before making assumptions about unique orders. The cleaning process removes exact duplicate rows only.

## Author
Ankit Kumar
