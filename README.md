# Vortex Tech - Week 2 Exploratory Data Analysis

**Author:** Hafiz Muhammad Mahad Hussain
**Track:** Data Science & Analytics Internship

## Project Overview
This repository contains my submission for Week 2 of the Vortex Tech Data Science & Analytics Internship. The objective of this task is to conduct a structured Exploratory Data Analysis (EDA) on a Supermarket Sales dataset (`SMA.csv`) to identify and clearly explain meaningful patterns and relationships.

## Key Insights Discovered
1. **Pricing Drives Revenue:** A strong positive correlation exists between unit price and total sales per invoice.
2. **Fixed Margins:** Gross income scales perfectly linearly with the Cost of Goods Sold (COGS) due to a static 4.76% gross margin percentage across the store.
3. **Product Line Variance:** Distinct variations exist in average transaction values across different product categories, highlighting specific revenue drivers.

## Files in this Repository
* `vortextech-datasci-week2-updated.ipynb`: The main Jupyter Notebook containing the data cleaning steps, correlation heatmap, scatter plots, and markdown explanations.
* `SMA.csv`: The supermarket sales dataset used for the analysis.

## How to Run This Project
1. Clone this repository to your local machine:
   git clone <your-github-repo-url>
2. Ensure you have Python installed along with the required data science libraries. Install dependencies using:
 pip install pandas seaborn matplotlib jupyter
3. Launch Jupyter Notebook in your terminal:
jupyter notebook vortextech-datasci-week2-updated.ipynb
4. Run all cells sequentially to view the visualizations and statistical analysis.
