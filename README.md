# Customer-Purchase-Behavior-Analysis
End-to-end customer purchase behavior analysis using Python, SQL, and Power BI to uncover sales trends, customer segments, and business insights.
# 📊 Customer Purchase Behavior Analysis

## 🚀 Project Overview
This project analyzes customer shopping behavior using transactional data to uncover **purchase patterns, customer segments, and key revenue drivers**.

The goal is to help businesses:
- Improve customer engagement  
- Optimize marketing strategies  
- Increase sales and retention  

---

## 🧠 Business Problem
A retail company wants to understand:
- How customers purchase across categories  
- What factors influence buying decisions (discounts, reviews, shipping, etc.)  
- How to improve customer loyalty and revenue  

---

## 📂 Dataset
- **Total Records:** 3,900  
- **Features:** 18 columns  

### Key Data Includes:
- Customer demographics (Age, Gender, Location)  
- Purchase details (Category, Amount, Season)  
- Behavioral factors (Discount, Reviews, Purchase Frequency, Shipping Type)  
<img width="1465" height="273" alt="Screenshot 2026-04-27 212955" src="https://github.com/user-attachments/assets/54bae46b-80fe-4090-8570-cd306aec7021" />

---

## 🛠️ Tools & Technologies
- **Python (Pandas)** → Data Cleaning & Preprocessing  
- **MySQL (SQL)** → Data Analysis  
- **Power BI** → Dashboard & Visualization  
- **Jupyter Notebook** → Development  

---

## ⚙️ Project Workflow

### 🔹 1. Data Preparation (Python)
- Data cleaning and preprocessing  
- Handling missing values (Review Rating)  
- Feature engineering:
  - Age groups  
  - Purchase frequency  
- Removed redundant columns  
- Loaded data into MySQL  

---

### 🔹 2. Data Analysis (SQL)
Performed business-driven analysis:

- Revenue by gender  
- High-spending discount users  
- Top-rated products  
- Shipping behavior analysis  
- Subscription vs non-subscription analysis  
- Discount-dependent products  
- Customer segmentation (New / Returning / Loyal)  
- Top 3 products per category  
- Repeat buyers vs subscription behavior  
- Revenue by age group  

---

### 🔹 3. Dashboard (Power BI)
Developed an interactive dashboard with:

- KPIs:
  - Total Customers  
  - Average Purchase Amount  
  - Average Rating  
- Revenue by category  
- Sales trends  
- Customer segmentation  
- Age group analysis  

---

## 📊 Key Insights

### 📌 Customer Behavior
- Majority of customers are **loyal customers**  
- **Young adults** contribute highest revenue  

---

### 📌 Product Insights
- Some products heavily depend on **discounts**  
- Top-rated products ≠ always top-selling  

---

### 📌 Revenue Drivers
- Discounts increase purchase volume  
- Express shipping users spend slightly more  

---

### 📌 Subscription Insights
- Subscriptions do not significantly impact spending  
- Opportunity to improve subscription strategy  

---

## 💡 Business Recommendations
- 🎯 Improve subscription benefits to increase adoption  
- 🎯 Optimize discount strategies to protect margins  
- 🎯 Target high-value customer segments  
- 🎯 Promote top-rated products  
- 🎯 Use personalized marketing campaigns  

---

## 📁 Project Structure
- 📦 Customer-Purchase-Behavior-Analysis
- 📜 Customer_Purchase_Behavior_Analysis.ipynb
- 📜 Customer_Purchase_Behavior_SQL_Queries.sql
- 📊 Customer_Purchase_Behavior_Analysis.pbix
- 📄 Customer_Shopping_Behavior_Analysis_Report.pdf
- 📄 dataset.csv
- 📄 README.md

---

## 📈 Dashboard Preview
<img width="1360" height="734" alt="Screenshot 2026-04-27 212600" src="https://github.com/user-attachments/assets/eb25afe9-d6ad-48c7-a3c3-f5c0d1df2883" />


---

## 🧪 How to Run

### 🔹 Python (Jupyter)
```bash
pip install pandas sqlalchemy pymysql
```
### 🔹 MySQL Connection
```
from sqlalchemy import create_engine
from urllib.parse import quote_plus

engine = create_engine(
    "mysql+pymysql://username:password@host:port/database
)
```
### 🔹 Run SQL Queries
#### Execute queries from .sql file in MySQL Workbench
---
## 👩‍💻 Author

#### Nithya
#### Aspiring Data Analyst
