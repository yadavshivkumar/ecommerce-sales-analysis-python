# E-Commerce Sales Analysis 📊

## 📌 Project Overview

The **E-Commerce Sales Analysis** project is a data analysis project developed using Python. It explores sales performance, profitability, product categories, sub-categories, and customer segments using the Sample Superstore dataset.

The project uses data manipulation techniques and interactive visualizations to identify sales trends, understand profit distribution, and compare business performance across different categories and customer segments.

## 🎯 Project Objectives

- Analyze monthly sales trends.
- Evaluate sales performance across product categories.
- Identify top-performing product sub-categories by sales.
- Analyze monthly profit trends.
- Compare profitability across product categories and sub-categories.
- Evaluate sales and profit across customer segments.
- Calculate the sales-to-profit ratio for different customer segments.
- Create interactive visualizations to communicate business insights.

## 📂 Dataset Information

**Dataset Name:** Sample - Superstore.csv

The dataset contains order-level information about sales transactions, customers, products, shipping, discounts, and profitability.

### Dataset Details

- **Total Records:** 9,994
- **Total Columns:** 21
- **File Format:** CSV

### Important Columns

| Column | Description |
|---|---|
| Row ID | Unique row identifier |
| Order ID | Unique order identifier |
| Order Date | Date when the order was placed |
| Ship Date | Date when the order was shipped |
| Ship Mode | Shipping method used |
| Customer ID | Unique customer identifier |
| Customer Name | Name of the customer |
| Segment | Customer segment |
| Country | Country where the order was placed |
| City | City associated with the order |
| State | State associated with the order |
| Region | Geographical region |
| Product ID | Unique product identifier |
| Category | Main product category |
| Sub-Category | Product sub-category |
| Product Name | Name of the product |
| Sales | Sales amount |
| Quantity | Quantity of products ordered |
| Discount | Discount applied to the order |
| Profit | Profit generated from the order |

*Note: The dataset also includes the Postal Code column.*

## 🛠️ Technologies Used

- **Python** — Programming language for data analysis.
- **Pandas** — Data manipulation and aggregation.
- **Plotly Express** — Interactive data visualizations.
- **Plotly Graph Objects** — Customized charts and comparative visualizations.
- **Jupyter Notebook** — Interactive development and analysis environment.

## 📊 Project Workflow

### 1. Data Loading

Imported the Sample Superstore dataset into a Pandas DataFrame using `read_csv()`.

### 2. Data Exploration

Explored the dataset using:

- `df.head()` to inspect the first few records.
- `df.info()` to examine column names, data types, and non-null counts.
- `df.describe()` to calculate descriptive statistics for numerical columns.

### 3. Date Processing

Converted the Order Date and Ship Date columns into datetime format.

Extracted additional time-based features:

- Order Month
- Order Year
- Order Day of Week

These features support time-based sales and profit analysis.

### 4. Sales Analysis

Analyzed sales performance using the following visualizations:

- Monthly Sales Analysis
- Sales Analysis by Category
- Sales Analysis by Sub-Category

### 5. Profit Analysis

Evaluated profitability using:

- Monthly Profit Analysis
- Profit Analysis by Category
- Profit Analysis by Sub-Category

### 6. Customer Segment Analysis

Grouped the data by customer segment to compare total sales and profit.

A comparative bar chart was created using Plotly Graph Objects.

### 7. Sales-to-Profit Ratio

Calculated the sales-to-profit ratio for each customer segment to examine the relationship between sales volume and profit.

## 📈 Key Analysis and Visualizations

### 1. Monthly Sales Analysis

A line chart showing the variation in total sales across calendar months.

### 2. Sales Analysis by Category

A donut chart illustrating the distribution of sales across product categories.

### 3. Sales Analysis by Sub-Category

A bar chart comparing total sales among product sub-categories.

### 4. Monthly Profit Analysis

A line chart showing monthly profit patterns.

### 5. Profit Analysis by Category

A donut chart comparing profit contributions across product categories.

### 6. Profit Analysis by Sub-Category

A bar chart comparing the profitability of different product sub-categories.

### 7. Sales and Profit by Customer Segment

A comparative bar chart showing total sales and profit for each customer segment.

### 8. Sales-to-Profit Ratio by Segment

A calculated metric used to compare sales and profit across customer segments.

## 💡 Business Applications

The analysis can help businesses:

- Monitor monthly sales performance.
- Understand which product categories contribute most to sales.
- Compare profitability across product sub-categories.
- Evaluate the financial performance of customer segments.
- Identify areas requiring further investigation.
- Support data-driven sales and business decisions.

## 📁 Project Structure

```text
E-Commerce-sales-analysis/
│
├── data/
│   └── Sample - Superstore.csv
│
├── e commerce sales.ipynb
│
└── README.md
```

*The structure above is a suggested organization. Adjust the filenames and folders to match your actual GitHub repository.*

## ⚙️ Installation and Setup

### Prerequisites

Install Python 3 and Jupyter Notebook before running the project.

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
```

### Step 2: Navigate to the Project Directory

```bash
cd E-Commerce-sales-analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas plotly notebook
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the Analysis

Open the Jupyter Notebook and execute the cells sequentially.

**Important:** Update the CSV file path in the notebook to match the location of the dataset on your computer.

## 🔮 Future Improvements

- Add an interactive sales dashboard.
- Analyze yearly sales and profit trends.
- Investigate the impact of discounts on profitability.
- Compare regional sales performance.
- Identify the most profitable products.
- Analyze shipping time and shipping mode performance.
- Add automated data quality checks.
- Export key findings and visualizations into a business report.



## 📌 Conclusion

The E-Commerce Sales Analysis project demonstrates the use of Python, Pandas, and Plotly to explore transactional sales data and visualize business performance.

By analyzing sales trends, product categories, sub-categories, customer segments, and profitability, the project provides a foundation for understanding business data and developing data-driven insights.

---

⭐ If you find this project useful, consider giving the repository a star!