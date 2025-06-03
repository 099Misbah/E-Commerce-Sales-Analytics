# 🛒 E-Commerce Sales Analytics Dashboard

🚀 **Objective**:  
To analyze and visualize sales data from Amazon, International, and General sources to gain comprehensive business insights using Python and Power BI.

---

## 📁 Data Sources
- **Amazon.xlsx**
- **International.xlsx**
- **General.xlsx**

---

## 🧹 Data Cleaning & Preprocessing (Python - Google Colab)
### Key Steps:
- ✅ Standardized column names using `str.strip().lower().replace(' ', '_')`
- ✅ Added a **source** column to trace data origin
- ✅ Dropped irrelevant or mostly-null columns (e.g., SKU, stock)
- ✅ Imputed missing values:
  - Mode for categorical
  - Mean/Median for numerical
- ✅ Converted `date` to `datetime` using `pd.to_datetime(errors='coerce')`

---

## 📊 Power BI Dashboard Features
### 🟢 KPIs:
- Total Products Sold  
- Average Order Value  
- Return Rate  
- Revenue per Order  

### 🔵 Filters:
- Date Range  
- Ship Country  
- Fulfilment Type  
- Shipping Service Level  
- Sales Channel  

### 🟡 Visuals:
- Monthly Sales Trend (Line Chart)  
- Orders by Ship State (Map)  
- Orders by Category (Bar Chart)  
- Order Status Breakdown (Donut Chart)  
- Top 10 Products (Table)  
- Cancelled Orders Trend (Line Chart)  
- Fulfilment Type vs Amount (Clustered Bar)


## 🔧 Challenges & Solutions

Column Name Inconsistencies | Used `.str.strip().str.lower()` to clean 
Missing Values | Mode/Mean/Median imputation 
Source Traceability | Added a `source` column before merging 
99% Missing Columns | Dropped (`stock` column) 
Non-Date Formats | Used `pd.to_datetime(errors='coerce')` 


## 🛠️ Tools & Technologies
- Python (Pandas)
- Power BI (DAX, Custom Visuals)
- Google Colab
- Excel


📒 [Colab File](https://github.com/MisbahjabinShaikh)


📸 Dashboard Preview
![Dashboard Screenshot](https://github.com/user-attachments/assets/2029ab4e-e4b5-4e58-89f1-5d029628a01a)
)

## 🔗 Connect With Me
💼 [LinkedIn](https://www.linkedin.com/in/misbahjabin-shaikh/)
