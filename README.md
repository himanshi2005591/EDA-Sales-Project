# ML Projects: Exploratory Data Analysis & Sales Prediction

This repository contains two beginner-friendly data analysis projects focused on Exploratory Data Analysis (EDA) and simple predictive modeling using Python, Jupyter Notebook, and essential data science libraries.

These projects demonstrate how to clean and analyze real-world data, visualize insights, and apply basic machine learning techniques.

## Project 1: Exploratory Data Analysis (EDA)

**Objective:**  
Perform in-depth EDA on a retail dataset to identify trends, patterns, anomalies, and business insights.

**Dataset:**  
- Global Superstore (contains columns such as Sales, Profit, Region, Product Category, etc.)

**Tasks Performed:**
- ✅ Data Cleaning (missing values, duplicates, outliers)
- ✅ Descriptive Statistics (mean, median, std, variance)
- ✅ Correlation Analysis
- ✅ Visualizations:
  - Histograms (distribution of sales and profit)
  - Boxplots (outliers)
  - Heatmaps (correlation matrix)

📂 Notebook: `Project_1/project_1_notebook.ipynb`  
📄 Data File: `Project_1/project_1_data.csv`

## Project 2: Sales Performance Analysis & Prediction

**Objective:**  
Analyze a company's sales data to uncover performance trends and build a simple regression model to predict sales based on profit and discount.

**Dataset:**  
- `sales_data.csv` (includes Product, Region, Sales, Profit, Discount, Category, Date)

**Tasks Performed:**
- ✅ Time Series Analysis (sales trends over time)
- ✅ Visual Analysis (region/category-wise performance)
- ✅ Relationship Exploration (profit vs. discount)
- ✅ Linear Regression Model:
  - Features: Profit, Discount
  - Target: Sales
  - Metrics: R² Score, Mean Squared Error

📂 Notebook: `Project_2/project_2_notebook.ipynb`  
📄 Data File: `Project_2/sales_data.csv`

## Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (for regression model)

## Getting Started

To run the notebooks:

1. Clone or download this repository
2. Open each `.ipynb` file using [Jupyter Notebook](https://jupyter.org/) or VS Code
3. Make sure the CSV files are in the same folders as the notebooks
4. Run all cells step by step

```bash
# To install required libraries (if missing)
pip install pandas numpy matplotlib seaborn scikit-learn



