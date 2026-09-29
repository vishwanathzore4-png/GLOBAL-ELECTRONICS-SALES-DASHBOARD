# GLOBAL-ELECTRONICS-SALES-DASHBOARD
[https://github.com/vishwanathzore4-png/GLOBAL-ELECTRONICS-SALES-DASHBOARD/blob/main/Global%20Electronics%20Sales%20Dashboard.png
(Note: Replace the image link above with the actual path to your screenshot in the repository if the naming is different)

📖 Overview
The Global Electronics Sales Dashboard is a comprehensive data visualization project designed to analyze sales performance across different regions, product categories, and time periods. Using a dataset spanning from 2016 to 2021, this dashboard provides actionable insights into revenue trends, profitability, customer demographics, and product performance.

This project simulates a real-world business intelligence tool used by executives to monitor KPIs such as Total Sales ($55.76M), Profit Margins (58.58%), and Year-over-Year Growth.

🚀 Features & Insights
The dashboard is divided into three main analytical views:

1. Executive Summary (Overview)
Key Performance Indicators (KPIs): Instant view of Total Sales ($55.76M), Total Profit ($32.66M), Total Orders (26.33K), and Profit Margin (58.58%).

Sales by Category: A breakdown of revenue contribution by product types (Computers, Home Appliances, Cameras, etc.).

Top 5 Countries: A bar chart highlighting the highest revenue-generating markets (United States, United Kingdom, Germany, Italy, Netherlands).

Monthly Sales Trend: A line graph visualizing seasonality and sales spikes throughout the calendar year.

2. Product Analysis
Revenue Contribution by Brand: Identifies top-performing brands like Adventure Works, Wide World Importers, and Proseware.

Sales & Profit by Category: A comparative bar chart showing both revenue and profit margins per category to identify high-margin products.

Sales by Price Range: Analysis of which price points ($100-$500, $500-$1000, etc.) generate the most volume.

Units Sold: Ranking categories by the sheer number of units moved (Computers lead significantly).

3. Sales Analysis & Trends
Geographic Distribution: Revenue breakdown by Continent (North America, Europe, Australia).

Year-over-Year (YoY) Growth: A bar chart tracking growth percentages from 2017 to 2021.

Currency Analysis: Sales distribution across USD, EUR, GBP, CAD, and AUD.

Day of Week Analysis: Identifies peak shopping days (notably Tuesdays and Saturdays).

🛠️ Tech Stack & Tools
Data Cleaning & Preprocessing: Python (Pandas, NumPy)

Data Visualization: Microsoft Power BI

Data Processing: Power Query (ETL)

Calculations: DAX (Data Analysis Expressions) for custom metrics like Profit Margin and YoY Growth.

Design: Custom UI with dark mode theme and interactive slicers.

🧹 Data Cleaning (Python)
Before visualizing the data in Power BI, the raw dataset underwent a rigorous cleaning process using Python to ensure accuracy and consistency. The cleaning script handles missing values, data type conversions, and feature engineering.

Key Cleaning Steps:
Handling Missing Values: Checked for null values in critical columns (e.g., Customer Names, Revenue) and imputed or dropped them as necessary.

Date Formatting: Converted the Order Date column from string/object to DateTime format to enable time-series analysis (Monthly/Yearly trends).

Data Type Conversion: Ensured numerical columns like Quantity, Unit Price, and Profit were correctly formatted as floats or integers.

Feature Engineering: Created new columns such as Year, Month, and Day of Week to facilitate the dashboard's time-based filtering.

Duplicate Removal: Identified and removed duplicate transaction records to prevent inflated sales figures.

Currency Standardization: (If applicable) Ensured all monetary values were converted to a standard base currency (USD) for global comparison.


# 7. Export Cleaned Data for Power BI
df.to_csv('Data/Global_Electronics_Sales_Cleaned.csv', index=False)
print("Data Cleaning Complete. File saved.")
📂 Repository Structure
bash
├── Data/
│   ├── Global_Electronics_Sales_Raw.csv     # Original raw dataset
│   └── Global_Electronics_Sales_Cleaned.csv # Cleaned dataset ready for BI
├── Scripts/
│   └── data_cleaning.py                     # Python script for data preprocessing
├── Dashboard/
│   └── Global_Electronics_Sales.pbix        # Power BI source file
├── Images/
│   └── dashboard_preview.png                # Screenshots of the dashboard
└── README.md                                # Project documentation
📊 Key Metrics (Snapshot)
Metric	Value
Date Range	01-01-2016 to 20-02-2021
Total Revenue	$55.76M
Total Profit	$32.66M
Profit Margin	58.58%
Total Orders	26.33K
Unique Customers	11.89K
⚙️ How to Use
Clone the repository:

bash
git clone https://github.com/vishwanathzore4-png/GLOBAL-ELECTRONICS-SALES-DASHBOARD.git
Run the Python Script (Optional):

If you want to see the cleaning process, navigate to the Scripts/ folder and run python data_cleaning.py.

Open the Project:

If you have Power BI Desktop installed, open the .pbix file located in the Dashboard/ folder.

If viewing the code only, refer to the high-resolution images in the Images/ folder.

Interact:

Use the Date Range filter in the top right to adjust the time period.

Use the Countries slicer in the sidebar to filter data for specific regions.

Click on specific chart elements (e.g., a slice in the pie chart) to cross-filter the entire page.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📧 Contact
Vishwanath Zore

GitHub: @vishwanathzore4-png](https://github.com/vishwanathzore4-png/GLOBAL-ELECTRONICS-SALES-DASHBOARD/blob/main/Global%20Electronics%20Sales%20Dashboard.png
(Note: Replace the image link above with the actual path to your screenshot in the repository if the naming is different)

📖 Overview
The Global Electronics Sales Dashboard is a comprehensive data visualization project designed to analyze sales performance across different regions, product categories, and time periods. Using a dataset spanning from 2016 to 2021, this dashboard provides actionable insights into revenue trends, profitability, customer demographics, and product performance.

This project simulates a real-world business intelligence tool used by executives to monitor KPIs such as Total Sales ($55.76M), Profit Margins (58.58%), and Year-over-Year Growth.

🚀 Features & Insights
The dashboard is divided into three main analytical views:

1. Executive Summary (Overview)
Key Performance Indicators (KPIs): Instant view of Total Sales ($55.76M), Total Profit ($32.66M), Total Orders (26.33K), and Profit Margin (58.58%).

Sales by Category: A breakdown of revenue contribution by product types (Computers, Home Appliances, Cameras, etc.).

Top 5 Countries: A bar chart highlighting the highest revenue-generating markets (United States, United Kingdom, Germany, Italy, Netherlands).

Monthly Sales Trend: A line graph visualizing seasonality and sales spikes throughout the calendar year.

2. Product Analysis
Revenue Contribution by Brand: Identifies top-performing brands like Adventure Works, Wide World Importers, and Proseware.

Sales & Profit by Category: A comparative bar chart showing both revenue and profit margins per category to identify high-margin products.

Sales by Price Range: Analysis of which price points ($100-$500, $500-$1000, etc.) generate the most volume.

Units Sold: Ranking categories by the sheer number of units moved (Computers lead significantly).

3. Sales Analysis & Trends
Geographic Distribution: Revenue breakdown by Continent (North America, Europe, Australia).

Year-over-Year (YoY) Growth: A bar chart tracking growth percentages from 2017 to 2021.

Currency Analysis: Sales distribution across USD, EUR, GBP, CAD, and AUD.

Day of Week Analysis: Identifies peak shopping days (notably Tuesdays and Saturdays).

🛠️ Tech Stack & Tools
Data Cleaning & Preprocessing: Python (Jupyter Notebook)

Data Visualization: Microsoft Power BI

Data Processing: Power Query (ETL)

Calculations: DAX (Data Analysis Expressions) for custom metrics like Profit Margin and YoY Growth.

Design: Custom UI with dark mode theme and interactive slicers.

🧹 Data Cleaning (Jupyter Notebook)
Before visualizing the data in Power BI, the raw dataset underwent a rigorous cleaning process using Python. The entire data preprocessing workflow is documented in the Jupyter Notebook uploaded to this repository.

The notebook covers the following essential data cleaning steps to prepare the dataset for accurate analysis:

Handling Missing Values: Identifying and appropriately managing null values in critical columns such as Customer Names and Revenue.

Date Formatting: Converting the Order Date column into a proper DateTime format to enable accurate time-series analysis (Monthly/Yearly trends).

Data Type Conversion: Ensuring numerical columns like Quantity, Unit Price, and Profit are correctly formatted for mathematical operations.

Feature Engineering: Creating new, derived columns such as Year, Month, and Day of Week to facilitate the dashboard's time-based filtering and grouping.

Duplicate Removal: Identifying and removing duplicate transaction records to prevent inflated sales figures.

Currency Standardization: Ensuring all monetary values are consistent for global comparison.

You can view the full step-by-step cleaning process by opening the .ipynb file included in this repository.

📂 Repository Structure
bash
├── Data/
│   ├── Global_Electronics_Sales_Raw.csv     # Original raw dataset
│   └── Global_Electronics_Sales_Cleaned.csv # Cleaned dataset ready for BI
├── Notebooks/
│   └── Data_Cleaning.ipynb                  # Jupyter Notebook for data preprocessing
├── Dashboard/
│   └── Global_Electronics_Sales.pbix        # Power BI source file
├── Images/
│   └── dashboard_preview.png                # Screenshots of the dashboard
└── README.md                                # Project documentation
📊 Key Metrics (Snapshot)
Metric	Value
Date Range	01-01-2016 to 20-02-2021
Total Revenue	$55.76M
Total Profit	$32.66M
Profit Margin	58.58%
Total Orders	26.33K
Unique Customers	11.89K
⚙️ How to Use
Clone the repository:

bash
git clone https://github.com/vishwanathzore4-png/GLOBAL-ELECTRONICS-SALES-DASHBOARD.git
Review the Data Cleaning:

Open the .ipynb file in Jupyter Notebook or JupyterLab to review the Python data preprocessing steps.

Open the Project:

If you have Power BI Desktop installed, open the .pbix file located in the Dashboard/ folder.

If viewing the code only, refer to the high-resolution images in the Images/ folder.

Interact:

Use the Date Range filter in the top right to adjust the time period.

Use the Countries slicer in the sidebar to filter data for specific regions.

Click on specific chart elements (e.g., a slice in the pie chart) to cross-filter the entire page.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📧 Contact
Vishwanath Zore

GitHub: @vishwanathzore4-png
