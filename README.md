# Athletic Sales Analysis

This repository contains a Jupyter Notebook that analyzes sales data for athletic wear across the United States over two years. The analysis includes sales trends, retailer performance, and key insights into women's athletic footwear sales. By working through this notebook, users will develop a deeper understanding of data analysis techniques such as data merging, grouping, pivoting, and resampling.

---

## **Table of Contents**
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage Instructions](#usage-instructions)
- [Analysis Breakdown](#analysis-breakdown)

---

## **Project Overview**

This project uses sales data from a fictional athletic wear company to gain actionable insights into:
- Regions with the highest product sales.
- Retailer performance metrics.
- Trends in women's athletic footwear sales by day and week.

The notebook demonstrates the use of powerful data manipulation tools in Python, including:
- Combining and cleaning datasets.
- Grouping and pivoting data for multi-level analysis.
- Resampling data for time-based trends.

---

## **Objectives**

1. **Combine and Clean the Data**:
   - Import and merge sales data from 2020 and 2021.
   - Handle null values and ensure correct data types for analysis.

2. **Analyze Regional Sales**:
   - Identify regions, states, and cities with the highest product sales.
   - Determine regions with the highest total revenue.

3. **Evaluate Retailer Performance**:
   - Find the top-performing retailers by total sales.
   - Identify retailers that sold the most women's athletic footwear.

4. **Trend Analysis for Women's Athletic Footwear**:
   - Find the days with the highest total sales.
   - Determine the weeks with the highest total sales.

---

## **Dataset**

The repository includes the following datasets in the `Resources` directory:
- **`athletic_sales_2020.csv`**: Sales data for the year 2020.
- **`athletic_sales_2021.csv`**: Sales data for the year 2021.

These datasets include columns for:
- `region`, `state`, `city` (geographical information).
- `retailer` (sales point).
- `product_category`, `units_sold`, `total_sales` (sales metrics).
- `invoice_date` (date of sale).

---

## **Requirements**

To run the analysis, ensure you have:
- **Python**: Version 3.10 or later.
- **Jupyter Notebook** or **JupyterLab**.
- The following Python library:
  - `pandas`

Install required libraries using:
```bash
pip install pandas
```

---

## **Usage Instructions**

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/jesseparent/athletic_sales_analysis.git
   cd athletic_sales_analysis
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook athletic_sales_analysis.ipynb
   ```

3. Follow the instructions in the notebook. Execute cells in order or select **Run All** to run the complete analysis.

---

## **Analysis Breakdown**

### **1. Combine and Clean the Data**
- Import sales data from two CSV files.
- Check column names, handle null values, and ensure correct data types.
- Merge the two datasets into a single DataFrame.

### **2. Regional Sales Analysis**
- Determine the top-performing regions, states, and cities by:
  - Total products sold.
  - Total revenue.

### **3. Retailer Performance**
- Identify the top retailers by:
  - Total sales.
  - Sales of women's athletic footwear.

### **4. Sales Trends for Women's Athletic Footwear**
- Analyze sales trends by:
  - Day: Determine the top 10 days with the highest total sales.
  - Week: Identify the top 10 weeks with the highest total sales.

---


