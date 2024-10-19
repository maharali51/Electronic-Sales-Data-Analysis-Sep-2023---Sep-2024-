# Electronic-Sales-Data-Analysis-Sep-2023---Sep-2024-
Project's Title: 
Electronic Sales Data Analysis (Sep 2023 - Sep 2024)
Project Objective:

The objective of this project is to analyze sales data of electronic products, focusing on identifying key trends, patterns, and relationships within the data. The analysis is divided into three parts: univariate analysis, bivariate analysis, and time series analysis.

Project Description: 
This project focuses on analyzing a dataset of electronic product sales over a one-year period, from September 2023 to September 2024. The data includes various details such as product type, sales quantity, customer demographics, and sales trends over time. Using Python, the project aims to uncover valuable insights that can inform decision-making for sales teams, marketing professionals, and business executives.

The analysis covers univariate, bivariate, and time series analysis, along with interactive visualizations. It highlights key patterns such as best-selling products, seasonal sales trends, and customer preferences. This project utilizes powerful Python libraries like Pandas, Matplotlib, Seaborn, and Plotly to manipulate data, visualize trends, and present insights in an interactive format.

The goal is to offer data-driven solutions to common industry challenges, helping businesses optimize product offerings, streamline sales processes, and enhance customer engagement strategies.

How to Install and Run the Project:
# pandas
import pandas as pd
!pip install pyspan
import pyspan as ps

path = 'Electronic_sales_Sep2023-Sep2024.csv'
# df = dataframe'
df =pd.read_csv(path)

pd.set_option('display.max_columns',None)
df.head()
# print(df.head)

# For checking the total no of columns and rows
# df.shape
Key Dependencies:
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Datetime

Python Libraries Used:

The following libraries were used in the project:

Pandas: 
      For data manipulation and cleaning.
NumPy: 
      For numerical operations and calculations.
Matplotlib & Seaborn: 
      For data visualization.
Plotly:
      For interactive graphs.
Datetime: 
      For handling and analyzing date-related data.

Benefits to the Industry
     This project provides actionable insights that can help:
Retailers optimize product offerings and inventory management.
Sales Teams improve forecasting and target potential customer segments.
Marketing Teams develop data-driven campaigns.
Executives make informed business decisions based on accurate sales performance.


Target Audience
Data Analysts 
              who are looking to explore sales patterns and trends.
Business Analysts 
              who need to derive actionable insights from raw sales data.
Retail Professionals 
              interested in improving product and sales strategies.
Students and Python Learners  
             looking for hands-on experience in data analysis projects.


 Univariate Analysis: 
                    Through the univariate analysis, we examined the distribution of key variables in the dataset. For example:
The age distribution of customers gave insights into the dominant age groups purchasing electronic products. Analyzing the product types provided a clear picture of the most popular products, helping identify which product categories drive the majority of sales.

2. Bivariate Analysis:
                    Bivariate analysis allowed us to investigate relationships between two variables:
The boxplot of product types vs total price showed the variance in sales amounts across different product categories, highlighting which categories tend to have higher average sales values. Scatter plots and similar visualizations helped identify any potential correlations between customer characteristics (e.g., age, loyalty) and their spending behavior, offering valuable insights for targeting specific customer demographics with relevant offers.

3.Time Series Analysis: 
                      The time series analysis provided an overview of how sales trends evolved over time:
The monthly sales trends helped identify any seasonal patterns or fluctuations, which can be useful for inventory planning and forecasting. By decomposing the time series into trend, seasonal, and residual components, we were able to clearly see the underlying trends and seasonality in electronic sales, potentially guiding decisions on promotional timing and sales strategies.


