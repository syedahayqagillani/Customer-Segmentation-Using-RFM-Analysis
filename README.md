# 📊 Customer Segmentation Using RFM Analysis

## 📌 Project Overview
This project focuses on **Customer Segmentation** using **RFM (Recency, Frequency, Monetary) Analysis**.  
The goal is to understand customer behavior, segment them into meaningful groups, and suggest marketing strategies.  

---

## 🛠️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## 📂 Dataset
- **Source**: Online Retail Dataset (UCI / Kaggle)  
- **Columns include**:  
  - InvoiceNo  
  - StockCode  
  - Description  
  - Quantity  
  - InvoiceDate  
  - UnitPrice  
  - CustomerID  
  - Country  

---

## 🔑 Steps Performed
1. **Data Cleaning**
   - Removed missing values and duplicates  
   - Filtered out canceled transactions and invalid quantities  

2. **Feature Engineering**
   - Calculated Recency (days since last purchase)  
   - Calculated Frequency (number of purchases)  
   - Calculated Monetary (total spending per customer)  

3. **RFM Scoring & Segmentation**
   - Assigned scores (1–5) for each RFM metric  
   - Combined into RFM score for each customer  
   - Segmented customers into groups:  
     - **Champions** (recent, frequent, high spenders)  
     - **Loyal Customers**  
     - **At Risk Customers**  
     - **Hibernating Customers**  

4. **Visualization**
   - Heatmaps to visualize customer distribution across RFM scores  
   - Bar charts for customer segments  

5. **Insights & Marketing Ideas**
   - Give discounts or loyalty rewards to **Champions**  
   - Send re-engagement campaigns to **At Risk** customers  
   - Target **Hibernating** customers with win-back offers  

---

## 📊 Key Insights
- RFM segmentation helps businesses **prioritize marketing efforts**.  
- Small % of **Champions** drive the largest revenue.  
- **Inactive customers** represent an opportunity for re-engagement.  

---

## 🚀 How to Run
1. Clone this repository  
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
📌 Covered Topics

Data Cleaning

Feature Engineering

RFM Scoring & Segmentation

Customer Analytics

Data Visualization
📜 License

This project is licensed under the MIT License.

👤 Author

Syeda Hayqa Gillani

GitHub: https://github.com/syedahayqagillani
