# ☕ Coffee Shop Sales Dashboard

## 📌 Project Overview
This project analyzes **coffee shop sales transactions** to uncover insights into product performance, customer preferences, and payment trends.  
The interactive dashboard highlights **top-selling products, revenue patterns, and cash vs. card usage**, helping businesses make **data-driven decisions** for inventory, pricing, and marketing.

---

## 🛠 Tools & Technologies
- **Power BI / Excel** – Data cleaning, modeling, and dashboard creation  
- **SQL** – Querying and aggregating transactional data (optional)  
- **Python (Pandas, Matplotlib, Seaborn)** – For deeper Exploratory Data Analysis (EDA) and forecasting (optional extension)

---

## 🔎 Process

### 1. Data Preparation
- Cleaned raw dataset (`date, datetime, coffee_name, cash_type, money, card`).  
- Handled **missing values** (cash transactions had no card info).  
- Converted transaction dates into **Month, Weekday, Hour** for trend analysis.  
- Removed duplicates and standardized product names.

### 2. Exploratory Data Analysis (EDA)
- Analyzed **sales trends over time**.  
- Identified **popular coffee types** and their revenue contribution.  
- Segmented purchases by **cash vs. card**.  
- Discovered **time-based sales patterns** (daily & hourly peaks).  

### 3. Dashboard Development
Built an interactive **Power BI dashboard** with:
- Bar chart – Highest selling coffee types  
- Line chart – Count of payment types by coffee name  
- Donut chart – Sales distribution by product  
- Pie chart – Cash vs. Card transactions  
- Stacked bar chart – Sales count by product & payment type  
- Table – Detailed transactions (coffee, payment type, revenue)

---

## 📊 Key Insights
- **Top Products:** Latte and Americano with Milk are the highest-selling, generating the most revenue.  
- **Customer Preferences:** Americano, Cappuccino, and Cortado also perform strongly, while Cocoa and Espresso are least popular.  
- **Payment Trends:** 92% of purchases are made via **card**, only ~8% via **cash**.  
- **Revenue Share:** Americano with Milk (21.45%) and Latte (21.45%) are the top contributors to sales.  
- **Time-Based Trends:** Peak sales occur around **10:00 AM** and **7:00 PM**, with Tuesdays being the busiest weekday.  

---

## 🎯 Business Value
- Helps identify **top-performing products** for promotions and bundling.  
- Reveals **customer payment behavior** for financial planning.  
- Supports **inventory optimization** by aligning stock with demand patterns.  
- Provides a foundation for **sales forecasting models** using time series or ML.  

---

## 🚀 Future Work
- Build **sales forecasting models** (ARIMA, Prophet, XGBoost).  
- Perform **customer segmentation** for targeted marketing.  
- Add **geographical sales analysis** (if store/location data is available).  
- Automate dashboard refresh with live data.  

---


<img width="1156" height="732" alt="Screenshot 2025-09-29 220951" src="https://github.com/user-attachments/assets/7a09d10f-0218-4b43-b183-13eca115425d" />


