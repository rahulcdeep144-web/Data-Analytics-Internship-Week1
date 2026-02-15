# Week 1 – Data Cleaning on Superstore Dataset

This repository contains my Week 1 internship project: cleaning the Superstore sales dataset using both **Excel** and **Python (pandas)**. The goal was to prepare the raw data for analysis by handling missing values, removing duplicates, and creating new time‑based features.

## 📁 Dataset Description

- **Source:** Kaggle – [Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting)
- **File:** `train.csv`
- **Original rows:** 9,801
- **Original columns:** 21
- **Description:** The dataset contains sales transactions for a global superstore, including fields like Order ID, Order Date, Ship Mode, Customer ID, Product ID, Sales, Quantity, Discount, Profit, etc.

## 🧹 Cleaning Steps Performed

| Step | Description | Details |
|------|-------------|---------|
| **1. Handle missing values** | Removed rows with missing `Postal Code` | 11 rows affected (0.1% of data) – critical for location analysis |
| **2. Remove duplicates** | Removed duplicates based on `Order ID` + `Product ID` | 8 duplicate rows removed |
| **3. Feature engineering** | Added `Order Year` and `Order Month` columns | Extracted from `Order Date` for time‑series analysis |
| **4. Validation** | Cleaned data in both Excel and Python | Results matched, confirming consistency |

## 🛠️ Tools Used

- **Microsoft Excel** – Initial data inspection, manual cleaning, and structured table formatting
- **Python (pandas)** – Automated data loading, cleaning, and feature creation
- **Google Colab** – Interactive Python environment for running the cleaning script
- **ChatGPT** – Assisted with code review and optimisation suggestions

## 📊 Cleaned Dataset

The cleaned dataset is available as `cleaned_superstore.csv` in this repository.  
It contains **9,762 rows** (9,801 – 11 blanks – 8 duplicates) and **20 columns** (original 18 + 2 new features).

[⬇️ Download cleaned_superstore.csv](./cleaned_superstore.csv)

---

## 📌 Key Takeaways

- Data cleaning is **80% of real‑world analytics** – this project reinforced the importance of handling missing values and duplicates systematically.
- Using **both Excel and Python** demonstrates versatility and cross‑tool proficiency.
- **AI‑assisted code review** (ChatGPT) helped improve the Python script’s efficiency and robustness.

---

## 🔜 Next Steps (Week 2)

- Dive into **Advanced Excel** (pivot tables, dynamic arrays)
- Study **Probability** fundamentals
- Begin **automating Excel reports with Python**

---

*If you have any questions or feedback, feel free to reach out!*  
**– Rahul Rathod**
