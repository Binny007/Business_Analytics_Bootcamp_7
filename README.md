# Business_Analytics_Bootcamp_7

# Segmentation - RFM (Recency, Frequency, Monetary) Analysis


# 📊 RFM (Recency, Frequency, Monetary) Customer Segmentation Analysis

Welcome to the **RFM Segmentation** project! This repository contains a Python notebook and dataset to help you understand **Customer Segmentation** using the powerful RFM technique — a must-know for aspiring **Business Analysts** and **Data Scientists**.

---

## 🗂️ Repository Structure

📁 RFM-Segmentation/ │ ├── 📓 RFM.ipynb → Jupyter notebook with the full RFM analysis pipeline ├── 📄 online_shoppers.csv → Dataset containing customer transactions └── 📘 README.md → You're here!



---

## 📌 What is RFM Analysis?

**RFM** stands for:

- **Recency (R)**: How recently a customer made a purchase
- **Frequency (F)**: How often a customer makes a purchase
- **Monetary (M)**: How much a customer spends on average

These three metrics help businesses **segment customers**, target them effectively, and **maximize ROI**.

---

## 📈 Why RFM Matters?

✅ Helps identify high-value customers  
✅ Drives personalized marketing strategies  
✅ Improves customer retention and loyalty  
✅ Prioritizes resources and campaigns

---

## 🧠 Step-by-Step Process

### 1. 🧹 Data Cleaning & Preparation
- Raw dataset is item-level — each row is a single product purchase.
- Transformed into **customer-level** data for RFM metrics.

### 2. 📆 Recency
- Calculated as the number of days since the customer's last purchase.

### 3. 🔁 Frequency
- Total number of purchases made by a customer.

### 4. 💰 Monetary
- Average basket size (total spend per purchase).

### 5. 🏷️ RFM Scoring
- Customers are given scores (1 to 4) for each of R, F, and M.
- A combined **RFM Score** is created.
- Customers are segmented based on score thresholds.

### 6. 🎯 Customer Segments
Example RFM Segments:
| Segment          | Description |
|------------------|-------------|
| SuperStar        | Recent, frequent, and high spenders |
| Future Champion  | Loyal but not recent |
| High Potential   | Moderate buyers with some activity |
| Low Relevance    | Inactive or low-spend customers |

---

## 🎯 Value-Based Segmentation

**Value-Based Segmentation** groups customers based on their **long-term value**, not just recent behavior.

| Metric           | Description |
|------------------|-------------|
| Customer Lifetime Value (CLV) | Forecasts how much revenue a customer will generate |
| Profitability    | High vs Low margin customers |
| Engagement Level | Email opens, app usage, etc. |

💡 Combine RFM with CLV for more strategic targeting!

---

## 📊 Behavioral Segmentation

**Behavioral Segmentation** groups users by **how they behave** — beyond just purchase patterns.

| Behavior Type     | Examples |
|-------------------|----------|
| Purchase behavior | First-time vs Repeat buyers |
| Usage rate        | Light vs Heavy users |
| Loyalty status    | One-time vs Long-term users |
| Browsing behavior | Pages visited, products viewed |

🔍 Combine **RFM + Behavioral Segmentation** for truly **data-driven decision making**.

---

## 📌 Use Cases in Real-World

- 🎯 Targeted email campaigns
- 🛍️ Personalized product recommendations
- 💸 Churn prediction and customer retention
- 📦 Inventory planning based on buying behavior

---

## 📁 Dataset Overview

The dataset `online_shoppers.csv` includes the following columns:

| Column Name     | Description                          |
|------------------|--------------------------------------|
| Invoice          | Transaction ID                       |
| CustomerID       | Unique customer identifier           |
| Product          | Item purchased                       |
| Quantity         | Units bought                         |
| UnitPrice        | Price per unit                       |
| InvoiceDate      | Date of purchase                     |

---

## ⚙️ Technologies Used

- 🐍 Python 3
- 📘 Pandas
- 📊 Matplotlib
- 📁 Jupyter Notebook

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RFM-Segmentation.git
   cd RFM-Segmentation


2. Install dependencies (if running locally):
    pip install pandas matplotlib


3. Launch the notebook:
    jupyter notebook RFM.ipynb



🏁 Final Words
This RFM project is an excellent starting point for anyone looking to break into business/data analytics or enhance customer segmentation skills.

If you find this helpful, give it a ⭐ and spread the knowledge!
Let’s build smarter customer strategies together 🚀
   
