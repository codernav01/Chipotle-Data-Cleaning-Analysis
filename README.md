# Chipotle Data Cleaning & Analysis Project

## Overview  
This project focuses on cleaning and analyzing the Chipotle orders dataset using **Python** and **Pandas**.  
The objective is to transform raw data into a structured format and extract meaningful business insights related to customer ordering behavior.

---

## Dataset Description  

- **Total Rows:** 4,622  
- **Total Columns:** 5  

### Columns:

| Column Name           | Description |
|----------------------|------------|
| order_id             | Unique identifier for each order |
| quantity             | Number of items ordered |
| item_name            | Name of the food item |
| choice_description   | Customer preferences/customizations |
| item_price           | Price of the item (originally in `$` format) |

---

## Data Cleaning Steps  

- Loaded dataset using **Pandas**
- Removed `$` symbol from `item_price`
- Converted `item_price` to numeric (`float`)
- Checked for **missing values**
- Checked for **duplicate records**
- Verified and corrected **data types**

---

## Exploratory Data Analysis (EDA)  

Performed analysis to answer key business questions:

- Total number of orders  
- Total revenue generated  
- Average revenue per order  
- Most frequently ordered items  
- Number of unique items sold  
- Item-wise order frequency  
- Customer preference trends  

---

## Key Insights  

- Identified top-selling menu items  
- Analyzed customer purchasing behavior  
- Calculated revenue metrics  
- Evaluated product demand patterns  

---

## 🛠️ Technologies Used  

- **Python**  
- **Pandas**  
- **Jupyter Notebook**  

---

## Project Structure  

```bash
Chipotle-Data-Cleaning-Project/
│
├── chipotle.tsv
├── Chipotle-Data-Cleaning-Project.ipynb
└── README.md
```

---

## Conclusion  

This project demonstrates:

- Data cleaning and preprocessing  
- Data transformation  
- Exploratory data analysis  
- Extracting actionable business insights  

It is a strong beginner-to-intermediate level project for **Data Analyst roles**.

---
