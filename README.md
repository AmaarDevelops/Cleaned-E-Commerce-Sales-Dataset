# 📊 E‑Commerce Sales Data Analysis (UK Retail)

This project examines UK e‑commerce transactions (2009–2011) using **Pandas** and **NumPy**, including data cleaning, feature creation, and **RFM customer segmentation**.

---

## 📂 Dataset

- **File:** `Online Retail.csv`  
- From Kaggle: *Online Retail Dataset* by lakshmi25npathi  
- Contains columns: `InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country`

---

## 🔧 What This Script Does

1. Cleans/remove duplicates  
2. Fills missing Customer IDs and converts `InvoiceDate`  
3. Creates `Revenue` = Quantity × UnitPrice  
4. Calculates:
   - Total transactions & customers  
   - Overall, monthly, and yearly revenue  
   - Top products & countries (by sales volume)  
   - Average basket size per month  
   - Top and bottom 5% of buyers  
   - Repeat vs one-time customers  
   - Average product price  
   - Highest-revenue products  
5. Performs **RFM analysis**:
   - **R**ecency: days since last purchase  
   - **F**requency: number of invoices  
   - **M**onetary: total money spent  
6. Saves cleaned and analyzed datasets:
   - `cleaned_ecommerce_dataset.csv`  
   - `rfm_analysis.csv`

---

## 📁 File Summary

| File                              | Description                                      |
|----------------------------------|--------------------------------------------------|
| `Online Retail.csv`              | Raw data from Kaggle                             |
| `cleaned_ecommerce_dataset.csv` | Cleaned and enriched dataset                    |
| `rfm_analysis.csv`              | Customer-level RFM metrics                       |
| `script.py`                     | Python script executing the analysis             |
| `README.md`                     | This project overview and instructions           |
