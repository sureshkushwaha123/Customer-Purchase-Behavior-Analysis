# 🛒 Customer Purchase Behavior & Sentiment Analysis  
---

This project delivers an **end-to-end analytics pipeline** combining **SQL, Python, and Power BI** to analyze customer purchases and sentiments.  
It transforms raw transactional and review data into **actionable business insights** that guide product strategy, customer engagement, and revenue growth.  

📊 **Interactive Dashboard**: [View Here](https://app.powerbi.com/view?r=eyJrIjoiZmVlNTUwMzItYjYzOC00ZjQ5LTkwZDYtMmZjOTBkZDU0NmY0IiwidCI6IjZjZTcwOTA0LTUwOWMtNGI0Zi1iNjc2LTJiMGRlZjA3M2U2YyJ9)  

---

## 🎯 Objectives  

- Discover **patterns in customer purchase behavior**.  
- Apply **sentiment analysis** to understand customer opinions on products.  
- Develop an **interactive Power BI dashboard** for business stakeholders.  
- Provide **data-driven recommendations** for sales, marketing, and product teams.  

---

## 📂 Data Sources  

1. **Customer Purchases** (`customer_purchase_data.csv`)  
   - Transaction ID, Customer ID, Product, Category, Quantity, Price, Date, Country.  

2. **Customer Reviews** (`customer_reviews_data.csv`)  
   - Review ID, Customer ID, Product ID, Review Text, Review Date.  

---

## 🔑 Project Workflow  

### 1️⃣ SQL (Data Engineering)  
- Created a **MySQL schema** for purchases & reviews.  
- Ingested and cleaned datasets.  
- Built queries for:  
  - Revenue & purchase trends.  
  - Top customers & categories.  
  - Time-based performance analysis.  

---

### 2️⃣ Python (Data Analysis)  
- Extracted SQL data using `pymysql`.  
- Cleaned and transformed with **pandas, numpy**.  
- Applied **TextBlob** for sentiment classification → Positive, Neutral, Negative.  
- Created **visualizations** (purchase patterns, sentiment breakdowns).  

---

### 3️⃣ Power BI (Visualization & Reporting)  
- Built an **interactive dashboard** with:  
  - 📈 Sales trends (monthly, quarterly, yearly).  
  - 👥 Customer segmentation (top spenders, purchase frequency).  
  - 🛍️ Product category performance.  
  - 😊 Sentiment insights linked to product performance.  
- Enabled **filters & drilldowns** (by product, region, customer).  

---

## 📊 Dashboard Highlights  

<img width="756" height="434" alt="Revenue Trends" src="https://github.com/user-attachments/assets/360b46fc-8e2a-4048-8f01-b11907f94edf" />  

- **Revenue Trends** – Identify seasonal spikes and long-term growth.  
- **Top Customers** – Recognize high-value customers.  
- **Product Performance** – Discover top-performing & underperforming categories.  
- **Sentiment Analysis** – Link customer opinions to repeat purchases & product success.  

<img width="763" height="427" alt="Customer Segmentation" src="https://github.com/user-attachments/assets/78244bc3-2434-47cb-a859-d636d334d45a" />  

---

## 🚀 Insights Generated  

✅ **Seasonality** – Strong Q4 spikes → opportunity for targeted campaigns.  
✅ **Customer Value** – Top 5% of customers contribute disproportionately to revenue.  
✅ **Product Strategy** – Fashion & electronics dominate; accessories show untapped growth.  
✅ **Sentiment Signals** – Negative reviews cluster around delivery & quality → key improvement areas.  
✅ **Business Readiness** – Executives can explore data interactively via Power BI.  

---

## 🛠️ Tech Stack  

- **SQL (MySQL)** – Data modeling & queries.  
- **Python** – Analysis & sentiment classification.  
- **Libraries** – pandas, numpy, matplotlib, seaborn, TextBlob, pymysql.  
- **Power BI** – Interactive dashboard & storytelling.  

---

## ⚡ Business Value  

This project demonstrates the **core skills of a Business Analyst**:  
- Turning **raw data → structured insights**.  
- Building **dashboards for executive decision-making**.  
- Linking **customer behavior & sentiment** with **business growth strategies**.  

---

## 🙌 Acknowledgments  

Special thanks to open-source tools & libraries (`pandas`, `TextBlob`, `matplotlib`, Power BI community`).  

---
