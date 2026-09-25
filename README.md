# Retail Sales Analysis & AI-Based Demand Forecasting

**Author:** Surya Chand Behera
**Program:** Data Analytics with AI 

## Project Description

This project analyzes three years (2023-2025) of retail sales transaction data to uncover trends across product categories, regions, and customer segments, and builds an AI-based regression model (Random Forest / Linear Regression) to forecast the next quarter's monthly sales demand. The workflow combines Python for data cleaning, analysis, and modeling with Excel for the source data and the final stakeholder-facing summary report.

## Dataset

- **File:** `Retail_Sales_Data.xlsx`
- **Description:** A retail transactions dataset (Order ID, Order Date, Category, Sub-Category, Region, Segment, Quantity, Discount, Sales, Profit) covering daily orders from January 2023 to December 2025, modeled on the well-known Superstore retail sales dataset structure.
- **Note:** This dataset was synthetically generated to reflect realistic retail sales patterns (seasonality, category mix, regional variation, and discount effects on profit) for the purposes of this academic project, since a live company dataset was not available. It includes intentional missing values and duplicate records to demonstrate real-world data cleaning.

## Technologies Used

- **Python:** pandas, NumPy (data cleaning & feature engineering)
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** scikit-learn (Linear Regression, Random Forest Regressor)
- **Excel:** openpyxl (reading source data, writing a formatted summary workbook with a native chart)

## Project Files

| File                                                | Description                                                            |
| --------------------------------------------------- | ---------------------------------------------------------------------- |
| `Surya_Chand_Behera_RetailSalesForecasting.ipynb` | Full project code: data cleaning, EDA, forecasting model, Excel export |
| `requirements.txt`                                | Python library dependencies                                            |
| `Surya_Chand_Behera_ProjectReport.docx`           | Complete project documentation                                         |
| `README.md`                                       | This file                                                              |
| `Retail_Sales_Data.xlsx`                          | Source dataset used by the notebook                                    |
| `Retail_Sales_Summary_Report.xlsx`                | Generated output: formatted summary tables and forecast chart          |

## Setup & Run Instructions

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Ensure `Retail_Sales_Data.xlsx` is in the same folder as the notebook.
3. Open and run all cells in `Surya_Chand_Behera_RetailSalesForecasting.ipynb` (Jupyter Notebook or JupyterLab).
4. The notebook will generate chart images and produce `Retail_Sales_Summary_Report.xlsx` as the final formatted Excel deliverable.

## Key Findings

- Sales peak sharply in November-December each year and dip in January-February.
- Technology and Furniture are the top revenue-generating categories; Furniture profit margins shrink significantly at discounts above 20%.
- The East and West regions consistently outperform Central and South in total sales.
- The Random Forest forecasting model outperformed the Linear Regression baseline and projects continued seasonal growth into the next quarter.

## Author Contact

- **Email:** suryachanbehera470@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/surya-chand-behera
