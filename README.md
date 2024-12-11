# Exploratory Data Analysis (EDA)

This repository contains exploratory data analysis (EDA),where I explore and analyze datasets to derive insights and patterns. Below is an overview of the projects in this repository:

## 1. Global Terrorism EDA

- File: `Global_Terrorism_EDA.ipynb`
- Description: This notebook presents an exploratory analysis of global terrorism data. Using descriptive statistics and visualizations, the analysis aims to uncover patterns and trends in terrorist incidents worldwide

### Dataset:
- File: `Global Terrorism Dataset.md`
- Description: This document provides detailed information about the Global Terrorism dataset used in the corresponding EDA notebook.

![Screenshot 2024-12-11 at 7 42 38 AM](https://github.com/user-attachments/assets/6f76ebbf-b211-4ce5-9eef-907168ecc858)

![Screenshot 2024-12-11 at 7 43 27 AM](https://github.com/user-attachments/assets/ad1e6ef3-ed6c-415d-b507-4010ae230e6a)

![Screenshot 2024-12-11 at 7 43 48 AM](https://github.com/user-attachments/assets/382cbdda-0a8d-4b09-a62e-da59a5018330)

### What We Used
- **Dataset:** Global Terrorism Database (GTD), containing information on terrorist incidents worldwide.
- **Libraries and Tools:**
  - Python
  - Pandas and NumPy for data preprocessing and manipulation
  - Matplotlib and Seaborn for data visualization
  - Plotly for interactive visualizations

### What We Did
- **Data Cleaning:**
  - Handled missing values and ensured consistent formatting for key attributes such as attack types, regions, and target types.
  - Removed irrelevant columns and normalized categorical variables for analysis.
- **Feature Engineering:**
  - Derived new features such as "attack frequency per region" and "fatality-to-injury ratios."
  - Segmented the data by region, attack type, and time periods.
- **Exploratory Analysis:**
  - Identified patterns and trends in terrorist incidents over time.
  - Highlighted regions and countries most affected by terrorism.
  - Analyzed common attack types and target categories.

### What We Got
- **Insights:**
  - Identified significant trends, such as the increase in terrorism incidents post-2000.
  - Highlighted the most affected regions, with detailed breakdowns by country and year.
  - Correlation analysis between fatalities, injuries, and attack types.
- **Visualizations:**
  - Time-series plots showing the rise and fall of terrorist activities globally.
  - Heatmaps indicating attack density by region and year.
  - Bar charts and pie charts detailing the distribution of attack types and targets.


## 2. Students Data EDA

- File: `Students_Data_EDA.ipynb`
- Description: This project involves the exploratory analysis of a dataset related to student information. The notebook explores various aspects of student data, such as demographics, academic performance, and other relevant factors.

### Dataset:

- File: `student_extended_ml_dataset2.csv`
- Description: This dataset is an extension of the student data exploration, providing additional features for potential machine learning applications. The file includes an updated dataset with new variables for further analysis and modeling.

![Screenshot 2024-12-11 at 7 44 35 AM](https://github.com/user-attachments/assets/96c44f85-97b7-45eb-a79b-2e8c471eeca4)

![Screenshot 2024-12-11 at 7 44 55 AM](https://github.com/user-attachments/assets/1e5e826d-9d46-4455-9b3c-9c56c0b5f40d)

## 3. eCommerce Behavior Analysis

- File: `eCommerce_behavior_EDA.ipynb`
- Description: In this analysis, I delve into the eCommerce Behavior dataset to uncover insights into user behavior, preferences, and trends in online shopping. The notebook includes visualizations and statistical summaries to enhance understanding.

### Dataset:
- File: `eCommerce Behavior Dataset.md`
- Description: This document provides detailed information about the eCommerce Behavior dataset used in the corresponding EDA notebook. It includes data sources, features, and any additional context necessary for understanding the dataset.

![Screenshot 2024-12-11 at 7 45 17 AM](https://github.com/user-attachments/assets/f9701005-fa51-4fac-87f3-1bd9465900d3)

![Screenshot 2024-12-11 at 7 45 33 AM](https://github.com/user-attachments/assets/fa4c03a6-5b1e-4ff3-b154-d0165e3db291)

![Screenshot 2024-12-11 at 7 45 50 AM](https://github.com/user-attachments/assets/7baf506a-4ca5-43af-b773-f176c53c8502)

### What We Used
- **Dataset:** A comprehensive dataset tracking user behavior on an eCommerce platform, including page views, add-to-cart actions, and purchases.
- **Libraries and Tools:**
  - Python
  - Pandas and NumPy for data preprocessing
  - Matplotlib and Seaborn for static visualizations
  - Tableau for advanced dashboard creation

### What We Did
- **Data Cleaning:**
  - Standardized event types (e.g., "page view," "add to cart," "purchase") and timestamps.
  - Handled missing values in critical columns like user ID and session durations.
- **User Segmentation:**
  - Grouped users by behavior patterns, such as frequent buyers, cart abandoners, and browsers.
  - Created cohorts based on session dates to analyze retention.
- **Exploratory Analysis:**
  - Analyzed conversion rates at each stage of the user funnel.
  - Identified factors contributing to cart abandonment.
  - Tracked session durations and their impact on purchases.

### What We Got
- **Insights:**
  - Identified key drop-off points in the user funnel, such as the transition from "add to cart" to "purchase."
  - Highlighted factors driving higher conversion rates, such as shorter session durations and specific product categories.
  - Recognized seasonal trends in purchasing behavior.
- **Visualizations:**
  - Funnel charts depicting user behavior flow from browsing to purchase.
  - Heatmaps for session activity distribution by time and day.
  - Line plots showing retention rates across user cohorts.

## Usage

To run the code and reproduce the results:

Clone this repository:

```bash
git clone https://github.com/Sattu2806/Exploratory-Data-Analysis-EDA-on-Diverse-Datasets
cd Exploratory-Data-Analysis-EDA-on-Diverse-Datasets
```
