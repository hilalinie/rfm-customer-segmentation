# 🛍️ RFM Customer Segmentation Analysis

## 📌 Project Overview
This project applies **RFM (Recency, Frequency, Monetary) Analysis** to an e-commerce dataset 
to segment customers based on their purchasing behavior. 
The goal is to identify high-value customers, at-risk customers, and new customers 
to enable data-driven marketing strategies.

## 📊 Dataset
- **Source:** [Online Retail II Dataset - UCI / Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
- **Size:** 1,067,371 transactions
- **Period:** December 2009 – December 2011
- **Features:** Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID, Country

## 🔍 Methodology
1. **Data Cleaning** — Removed cancelled orders, null Customer IDs, and negative values
2. **RFM Calculation** — Computed Recency, Frequency, and Monetary metrics per customer
3. **Scoring** — Assigned 1–5 scores using quintile-based segmentation
4. **Segmentation** — Classified customers into 6 meaningful segments

## 👥 Customer Segments
| Segment | Description |
|---|---|
| 💎 Şampiyonlar | Recent, frequent, high spenders |
| 🌟 Sadık Müşteriler | Regular buyers with good spending |
| 🆕 Yeni Müşteriler | Recent buyers, low frequency |
| 📈 Potansiyelli Müşteriler | Average RFM scores with growth potential |
| ⚠️ Kaybedilmekte Olanlar | Used to buy frequently but haven't recently |
| 😴 Uyuyan Müşteriler | Low recency, frequency and monetary value |

## 📈 Key Visualizations
![RFM Analysis](rfm_analysis.png)

## 🛠️ Technologies Used
- **Python** — pandas, numpy, matplotlib, seaborn
- **Google Colab** — Development environment
- **GitHub** — Version control

## 💡 Business Insights
- Champions segment drives the majority of total revenue despite being a small % of customers
- Win-back campaigns should target "Kaybedilmekte Olanlar" segment
- New customers need nurturing campaigns to increase frequency

## 🚀 How to Run
```bash
git clone https://github.com/hilalinie/rfm-customer-segmentation.git
cd rfm-customer-segmentation
pip install pandas numpy matplotlib seaborn
```
Then open the notebook in Google Colab and run all cells.

## 👤 Author
**hilalinie** | Industrial Engineering Student | Data Science Enthusiast
