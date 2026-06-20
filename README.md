# 📊 Pandas Analysis, Cleaning and Grouping

## 📌 Project Overview
This project demonstrates basic data analysis and data cleaning using Python's Pandas library. The notebook works on a sales dataset containing transaction details such as date, region, product category, customer age, and sales amount.

The main goal of this project is to learn how to:
- Inspect a dataset
- Handle missing values
- Perform grouping and aggregation
- Create custom functions for analysis

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Google Colab 

## 📂 Dataset Information
The dataset contains the following columns:

- `transaction_id` – Unique ID for each transaction
- `date` – Date of the transaction
- `region` – Region where the sale occurred
- `product_category` – Category of the product sold
- `customer_age` – Age of the customer
- `sales_amount` – Amount of sales generated

---
## 📖 Tasks Performed

### 1️⃣ Dataset Inspection
- Displayed dataset information using `df.info()`
- Checked for missing values using `df.isna().sum()`

### 2️⃣ Handling Missing Values
- Filled missing values in `region` using the mode (most frequent value)
- Filled missing values in `product_category` using the mode
- Filled missing values in `customer_age` using the rounded mean

### 3️⃣ GroupBy Analysis
Performed analysis such as:
- Total sales by region
- Average sales by product category
- Sales summaries using grouping operations

### 4️⃣ Custom Aggregation
Created custom functions to perform additional analysis.
Example:
- Calculated the sales range:
  ```
  Maximum Sales - Minimum Sales
  ```
- Found sales range for different regions.

## 📊 Key Concepts Learned
- Data inspection
- Missing value handling
- GroupBy operations
- Aggregation functions
- Custom functions in Pandas
- Data summarization techniques
---
## 🎯 Learning Outcome
By completing this project, I learned how to clean real-world datasets, handle missing information, group data efficiently, and perform meaningful sales analysis using Pandas.
This project was created as part of my practice in learning Python, Pandas, and data analysis.
