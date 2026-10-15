# E-Commerce Sales Analytics

**Author:** Kriti Jain  
**Project Name:** E-Commerce Sales Analytics

---

## 📌 Project Description

This project performs end-to-end exploratory data analysis and business intelligence on a large-scale e-commerce transactional dataset containing **138,116 orders** from 2021 to 2025. The analysis covers revenue trends, profitability, customer segmentation (RFM), product/brand performance, marketing channel effectiveness, delivery performance, and demographic insights.

The goal is to extract actionable business insights that drive growth, improve customer retention, and optimize operations.

---

## 📂 Dataset

**Source:** Kaggle — E-Commerce Sales and Customer Analytics  
**Link:** [https://www.kaggle.com/datasets/datascikhan/e-commerce-sales-and-customer-analytics](https://www.kaggle.com/datasets/datascikhan/e-commerce-sales-and-customer-analytics)

### Files Used

| File | Description |
|------|-------------|
| `ecommerce_sales_customer_analytics_150k.csv` | Main orders table — 138,116 rows × 46 columns |
| `customer_master.csv` | Customer profile data — demographics & acquisition cost |
| `order_items.csv` | Line-level order items linked to products |
| `product_catalog.csv` | Product catalogue — category, brand, pricing |

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3.10+ | Core language |
| Pandas | Data loading, wrangling, aggregation |
| NumPy | Numerical operations |
| Matplotlib | Chart rendering |
| Seaborn | Statistical visualisations |
| Jupyter Notebook | Interactive analysis environment |

---

## ⚙️ Setup & Run Instructions

### Prerequisites
- Python 3.10 or higher
- pip

### 1. Clone / Download
Place all dataset CSV files in the **same directory** as the notebook.

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook
```bash
jupyter notebook KritiJain_ECommerceSalesAnalytics.ipynb
```

### 4. Run All Cells
Use **Kernel → Restart & Run All** to execute all analysis cells in order.

---

## 📊 Key Analyses Performed

1. Revenue trend (monthly & annual)  
2. Annual Revenue vs Profit comparison  
3. Sales by Region  
4. Top 10 Product Categories by Revenue  
5. Sales Channel distribution (pie + bar)  
6. Customer Segment revenue analysis  
7. Payment Method analysis  
8. Profit Margin distribution  
9. Shipping Method & Delivery Performance  
10. Marketing Channel effectiveness  
11. Customer Age & Gender demographics  
12. Top 10 Brands by Revenue  
13. Correlation heatmap (numeric features)  
14. Order Status breakdown  
15. Customer Rating analysis  
16. RFM-based Customer Segmentation  

---

## 📁 Project Files

| File | Format | Description |
|------|--------|-------------|
| `KritiJain_ECommerceSalesAnalytics.ipynb` | Jupyter Notebook | Full analysis code |
| `requirements.txt` | Text | Python dependencies |
| `KritiJain_ProjectReport.docx` | Word Document | Detailed project report |
| `README.md` | Markdown | This file |

---

## 📈 Key Findings (From Dataset Statistics)

- **Total Revenue:** $177,134,263.74  
- **Total Profit:** $76,146,395.76  
- **Average Order Value:** $1,282.50  
- **Average Customer Rating:** 3.68 / 5.0  
- **Return Rate:** 6.85%  
- **Cancellation Rate:** 6.08%  

---

*Project developed as part of a Data Analytics assignment.*
