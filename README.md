# Project1_Sales_Analysis

## Overview
This project is a comprehensive **Sales Analysis** using the Global Superstore dataset. The goal is to explore the dataset, clean it, analyze key sales metrics, and visualize insights to help businesses make data-driven decisions.

**Tools Used:**  
- Python 3  
- Jupyter Notebook  
- Pandas & NumPy (Data Manipulation)  
- Matplotlib & Seaborn (Data Visualization)  

---

## Project Goals
1. Load and inspect the Global Superstore dataset.
2. Identify and handle missing or duplicate data.
3. Explore sales, profit, quantity, and discount trends.
4. Visualize sales performance across categories, regions, and customer segments.
5. Share insights that can support business decisions.

---

## Dataset
- **Source:** `GlobalSuperstore1.xlsx`  
- **Number of Rows:** 30,454  
- **Number of Columns:** 22  
- **Key Columns:**
  - `Order ID`, `Customer ID`, `Order Date`, `Ship Date`
  - `Segment`, `Region`, `Category`, `Sub-Category`
  - `Sales`, `Profit`, `Quantity`, `Discount`

---

## Key Steps Taken
1. **Data Loading**  
   Loaded the dataset into a Pandas DataFrame.

2. **Data Cleaning**  
   - Checked for missing values (`df.isnull().sum()`)  
   - Checked for duplicates (`df.duplicated().sum()`)  
   - Dropped unnecessary files using `.gitignore`  

3. **Exploratory Data Analysis (EDA)**  
   - Summarized dataset information (`df.info()` and `df.describe()`)  
   - Visualized sales, profit, and quantity trends  
   - Analyzed performance by `Category`, `Sub-Category`, `Region`, and `Segment`  

4. **Insights & Visualizations**  
   - Identified the **most profitable categories** and products.  
   - Analyzed **regional sales trends** to find high-performing regions.  
   - Explored **shipping and order priorities** affecting delivery and sales.  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/kavyagorrepati-2025/Project1_Sales_Analysis.git
2.Open the project folder in Jupyter Notebook:
    `jupyter notebook`
    
3.Run `data_analysis.ipynb` to see all analysis, charts, and insights.

---

## Outcomes
  -Cleaned and analyzed a large dataset efficiently.
  
  -Generated actionable business insights from sales, profit, and shipping data.
  
  -Gained experience in data cleaning, visualization, and exploratory analysis.
  
  -Project is GitHub-ready, demonstrating data analysis skills for portfolio purposes.

---


## Next Steps / Enhancements
  -Build interactive dashboards using Power BI.
  
  -Predict future sales using Machine Learning models.
  
  -Automate analysis for real-time sales reporting.

---

## Author
Kavya Gorrepati

Data Analyst Enthusiast | Skilled in Python [pandas(data manipulation)
 numpy(numerical analysis) matplotlib, seaborn, plotly(data visualization)], SQL, Power BI, Snowflake, Microsoft Azure  and Data Storytelling


GitHub: kavyagorrepati-2025

Email: kavyagk2025@gmail.com
