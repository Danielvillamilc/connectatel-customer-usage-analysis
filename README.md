# Daniel-repository
Look my first project in Data Analytics
🎯 Objective

This project analyzes customer behavior in a telecommunications company (ConnectaTel) operating in Latin America.

The goal is to understand how users interact with mobile services (calls and messages), identify usage patterns, detect outliers, and segment customers to generate actionable business insights.

📁 Datasets Used

The analysis is based on three datasets:

plans.csv → Information about available plans (pricing, included minutes, data, extra costs).
users_latam.csv → Customer data (age, city, registration date, plan, churn).
usage.csv → User activity data (calls duration and message length).

🔄 Analysis Steps

1. Data Loading & Exploration
- Loaded datasets and reviewed structure, columns, and data types.
2. Data Quality Assessment
- Identified missing values, invalid values (sentinels), and inconsistencies.
3. Data Cleaning
- Replaced invalid values (e.g., age = -999).
- Standardized date formats.
- Handled missing values depending on context.
4. Exploratory Data Analysis (EDA)
- Calculated summary statistics (mean, median, percentiles).
- Visualized distributions using histograms and boxplots.
5. Outlier Detection
- Used IQR and Z-score methods.
- Identified high-usage customers (not errors, but valuable segments).
6. Feature Engineering & Segmentation
- Created customer segments:
- By usage (low, medium, high)
- By age (young, adult, senior)
7. Visualization & Insights
- Compared behavior across segments and plans.
- Identified patterns and business opportunities.
  
▶️ How to Run the Project

You can run this project using Google Colab or Jupyter Notebook:

1. Open the notebook in Google Colab.
2. Upload the datasets (plans.csv, users_latam.csv, usage.csv) to the /datasets/ folder.
3. Run all cells sequentially.
   
🔁 Reproducibility Guide

To reproduce this analysis:

- Ensure Python environment with: pandas, numpy, matplotlib, seaborn
- Place datasets in the correct path:
/datasets/plans.csv
/datasets/users_latam.csv
/datasets/usage.csv
- Execute the notebook from top to bottom.
  
💡 Key Insights
* Most users fall into a medium usage segment, indicating stable service consumption.
* High-usage customers (outliers) represent valuable segments, not errors.
* Usage patterns vary across customer groups, creating opportunities for targeted plans.
* Data segmentation enables better decision-making in pricing and customer retention.
  
🚀 Business Value

This analysis helps:
- Optimize telecom plans
- Identify high-value customers
- Improve retention strategies
- Design data-driven commercial decisions

  
👤 Author

Daniel Villamil
Data Analyst | Social Impact & Analytics
