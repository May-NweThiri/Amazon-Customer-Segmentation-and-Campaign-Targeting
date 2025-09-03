
# Amazon Data Analysis for Marketing Campaign

##  Introduction
This project focuses on a comprehensive analysis of an Amazon dataset from Kaggle, with the ultimate goal of supporting a marketing campaign. The process begins with **data cleaning and preparation**, as raw datasets often contain inconsistencies such as missing values, duplicates, and formatting issues that can reduce the quality of analysis. By applying a structured ETL (Extract, Transform, Load) process, we ensure a clean, accurate, and reliable dataset for subsequent analysis.

* **Extract**: Raw datasets (customers, orders, deliveries, products, stock) were obtained from Kaggle and loaded into Pandas for processing.
* **Transform**: Data was cleaned by handling missing values (e.g., discounts, order_status, unit_cost, stock_level), standardizing formats (countries, dates), removing duplicates, and recalculating values using business logic (e.g., margins, delivery times).
* **Load**: The cleaned datasets are saved and will be used for further analysis, visualization, and integration into business intelligence tools.

This project ensures that the Amazon dataset is consistent and analysis-ready, forming a solid foundation for exploring customer behavior, sales performance, and operational efficiency to inform a data-driven marketing strategy.



##  Key Objectives

This project is divided into two main phases:

1.  **Data Cleaning & Preprocessing**: The initial phase, ensuring the dataset is free from errors and inconsistencies.
2.  **Data Analysis & Insights**: The subsequent phase, where we will perform an in-depth analysis to uncover key trends and patterns. This includes:
    * Analyzing customer demographics and purchasing behavior.
    * Identifying top-selling products and best-performing regions.
    * Calculating key performance indicators (KPIs) like customer lifetime value (CLV) and churn rate.
    * Using these insights to develop targeted marketing strategies.



## Project Structure

This repository contains the following files:

* `dataCleaning_amazon.ipynb`: A Jupyter Notebook containing all the code for the data cleaning process.
* `dataAnalysis_amazon.ipynb`: (To be added) A Jupyter Notebook for the data analysis and insight-finding phase.
* `README.md`: This file, providing an overview of the project.
* `data files /`: This directory is where the raw and cleaned datasets are stored.



##  Tools and Libraries

The project was developed using **Python** and the following libraries:

* **Pandas**: For data manipulation and analysis.
* **NumPy**: For numerical operations.
* **Matplotlib**: For data visualization.
* **Plotly**: For creating interactive visualizations.



##  Contribution

If you find any issues or have suggestions for improvement, please feel free to open a new issue or submit a pull request.


