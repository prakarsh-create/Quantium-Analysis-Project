# Quantium-Analysis-Project
# Chip Category Customer Analysis (Quantium Case Study)

## 📌 Project Overview
This project analyzes customer purchasing behavior in the **chips category** to support a strategic recommendation for the Category Manager (Julia).  
The goal is to understand **who buys chips, how they buy them, and what drives spend**, using transaction-level data combined with customer segmentation.

The analysis is performed in **Python** using `pandas`, `matplotlib`, and `seaborn`, following a real-world retail analytics workflow.

---

## 🎯 Business Objective
To provide **data-driven insights** that help:
- Identify key customer segments driving chip sales
- Understand purchasing patterns across lifestages and price sensitivity
- Recommend actionable strategies to improve category performance

---

## 📂 Datasets Used

### 1. QVI Transaction Data
Contains detailed purchase-level information:
- `DATE` – Date of transaction
- `PROD_NAME` – Product description
- `PROD_QTY` – Quantity purchased
- `TOT_SALES` – Total sales value
- `LYLTY_CARD_NBR` – Customer loyalty card number

### 2. QVI Purchase Behaviour Data
Contains customer segmentation attributes:
- `LYLTY_CARD_NBR` – Customer loyalty card number
- `LIFESTAGE` – Customer life stage (e.g., families, singles)
- `PREMIUM_CUSTOMER` – Budget / Mainstream / Premium

The two datasets are joined using `LYLTY_CARD_NBR`.

---

## 🛠 Tools & Technologies
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook / VS Code

---

## 🔍 Analysis Approach

### 1. Data Loading & Validation
- Loaded datasets and inspected structure
- Checked data types, missing values, and basic statis
