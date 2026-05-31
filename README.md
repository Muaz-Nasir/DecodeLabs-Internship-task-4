# Project 4: Data Visualization

This project focuses on turning raw transaction records into clean, meaningful visual charts using Python. Using `matplotlib` and `seaborn`, the script builds visual layouts to track metrics over time, look at product popularity, and see categorical shares.

## Features
* **Data Ingestion:** Loads the dataset and applies our standard cleaning pipeline (handling duplicates and empty coupon values).
* **Bar Chart Representation:** Visualizes and ranks the transaction volume for each product category side-by-side.
* **Pie Chart Proportions:** Breaks down payment methods into clear percentage slices to analyze customer choices.
* **Line Chart Trendlines:** Groups operational transactions by month to map chronological business growth over time.

## Repository Layout
* `Dataset for Data Analytics.xlsx` - The main raw transaction dataset workbook.
* `visualization_plots.py` - Main Google Colab Python script containing the graphing logic.
* `README.md` - Project documentation.

## Running the Visualizations in Google Colab
1. Upload your file to your Colab workspace sidebar and name it exactly: `Dataset for Data Analytics.xlsx`
2. Run the script cell. The three required charts will render immediately on your screen.

## Summary of Visual Charts Produced

### 1. Bar Chart: Transaction Volume by Product Class
Counts row frequencies to instantly highlight which products are driving the most orders (like Printers and Tablets) versus lower volume categories.

### 2. Pie Chart: Proportional Share of Payment Methods
Divides the total transaction count across payment choices (Credit Card, Online, Cash, Debit Card, etc.) to show what percentage of customers prefer each financial method.

### 3. Line Chart: Monthly Operational Sales Trend
Extracts chronological data points and links them together across a continuous time path. This lets the viewer see peak months, slower seasons, and general business trajectory.
