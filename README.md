# BI-calculations-Project
This project demonstrates a complete workflow of data cleaning, transformation, business intelligence (BI) calculations, and reporting using **Python**. It is designed to extract actionable insights from raw transactional data and deliver them in Excel and PDF formats suitable for business decision-making.

## 📁 Project Overview

The dataset used simulates retail purchase data containing information like:
- Purchase Date
- Product Categories
- Customer Gender
- Payment Methods
- Discount Types
- Gross/Net Revenue

### ✔️ Key Steps:
1. **Data Loading and Cleaning**
   - Removed duplicates and missing values
   - Converted data types (e.g., dates, currency fields)
   - Standardized formats and validated input

2. **Data Analysis & BI Calculations**
   - Revenue by Product Category
   - Monthly Sales Trends
   - Gender-wise Purchase Analysis
   - Discount Performance
   - City-wise Revenue Distribution
   - Payment Method Count and Percentage Breakdown

3. **Reports & Visualization**
   - Line charts using `matplotlib`

---

## 🛠 Technologies Used

- Python 3.x
- pandas
- matplotlib
- openpyxl
- xlsxwriter
- reportlab

---

## 📊 Sample Outputs

📁 **BI_Insights_Report.xlsx**  
Includes:
- Raw cleaned data
- Revenue by category
- Monthly sales trend
- Gender & city analysis
- Discount insights
- Payment method usage

📄 **BI_Insights_Report.pdf**  
Clean summary report with key metrics and breakdowns.

---

## 🚀 How to Run

1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/bi-data-cleaning-project.git
   cd bi-data-cleaning-project

    Install dependencies

pip install -r requirements.txt

Run the main script

    python bi_insights.py

📌 Author

Shubbham Jadhav
Senior Quality Analyst | Business Intelligence Enthusiast
