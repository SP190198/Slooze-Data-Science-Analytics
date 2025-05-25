# 🧠 Slooze Inventory, Purchase & Sales Analytics – Data Science Project

This is a take-home data science challenge project for Slooze. The aim is to optimize inventory management, procurement processes, and sales performance using historical data.
[Google Colab Project Link](https://colab.research.google.com/drive/1I2nE-8Ko_nZ3XKlup-sTflKyiGJB-7VU#scrollTo=ontTflMZq_d6)

## 📌 Project Objectives

- 📈 Forecast product demand using historical sales data
- 📊 Classify inventory using ABC analysis
- 📦 Optimize inventory through Economic Order Quantity (EOQ) calculation
- 🔁 Set Reorder Points to avoid stockouts
- 🕒 Analyze Lead Times to improve supplier and procurement efficiency


## 🔍 Analyses Performed

### 1. Demand Forecasting
- Time series analysis to forecast product demand.
- Implemented using Pandas & moving averages.
- Helps in planning inventory and procurement cycles.

### 2. ABC Inventory Classification
- Products classified into A (high value), B (moderate), and C (low value).
- Helps prioritize high-impact items for stock management.

### 3. EOQ (Economic Order Quantity)
- Calculated optimal order quantity to reduce ordering and holding costs.
- Implemented Just-in-Time (JIT) practices where applicable.

### 4. Reorder Point Analysis
- Reorder points determined using lead time and demand.
- Ensures inventory continuity and prevents stockouts.

### 5. Lead Time Analysis
- Analyzed time between order and receipt.
- Identified suppliers/products causing procurement delays.


## 📁 Project Structure

```bash
├── Slooze_Analytics_Project.ipynb   # Full Google Colab notebook with code 
├── /data
│   ├── SalesFINAL12312016.csv
│   ├── PurchasesFINAL12312016.csv
│   ├── InvoicePurchases12312016.csv
│   ├── BeginFINAL12312016.csv
│   ├── EndFINAL12312016.csv
│   └── 2017PurchasePricesDec.csv
├── README.md   
