# 🛒 Superstore ETL Project

## 📌 Objective
Clean and analyze sales order data using a structured ETL (Extract, Transform, Load) pipeline in Python and Pandas.

## 🧰 Tools Used
- Python
- Pandas
- Jupyter Notebook
- Matplotlib

## 🔁 ETL Steps

### ✅ Extract
- Loaded `train.csv` (Superstore-style data)

### ✅ Transform
- Cleaned missing values
- Converted date columns to datetime
- Created new columns: Month, Weekday
- Filtered December orders for analysis

### ✅ Load
- Saved clean data to `cleaned_orders.csv`
- Saved filtered data to `december_sales.csv`

## 📊 Sample Analysis
- Sales by category and region
- Monthly and weekday sales patterns
- Top-performing sub-categories

## 📊 Sales by Month

Here’s a bar chart showing total sales by month in the dataset:

<img width="1440" alt="Screenshot 2025-04-17 at 7 51 36 AM" src="https://github.com/user-attachments/assets/ace03237-6289-4551-8618-8338accbff91" />


## 📂 Folder Structure

