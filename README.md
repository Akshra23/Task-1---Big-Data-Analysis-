# 🛒 E-Commerce Sales Big Data Analysis using Dask

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Dask](https://img.shields.io/badge/Dask-Big%20Data-EF7C35?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

## 📋 Internship Details

| Field | Details |
|-------|---------|
| **Name** | Akshra |
| **Company** | CODTECH IT Solutions Pvt. Ltd |
| **Intern ID** | CTISO5S9 |
| **Domain** | Data Analytics |
| **Duration** | 4 weeks |
| **Mentor** | Neela Santhosh Kumar |
| **Task** | Task 1 — Big Data Analysis |

---

## 🎯 Project Overview

> Perform **Big Data Analysis** on an E-Commerce Sales dataset (100 orders × 22 columns) using **Dask** for parallel and scalable data processing. Derive actionable business insights across sales, revenue, customer demographics, regional performance, and payment behaviour.

This project demonstrates that the same Dask-based code scales from 100 rows to **millions of rows** on a distributed cluster without any code changes — proving true Big Data scalability.

---

## 🗂️ Project Structure

```
Task-1-Big-Data-Analysis/
│
├── 📓 big_data_analysis.ipynb     ← Main Jupyter Notebook
├── 📊 ecommerce_sales_data.csv    ← Dataset (100 rows × 22 columns)
└── 📝 README.md
```

---

## 📊 Dataset Description

**File:** `ecommerce_sales_data.csv`
**Records:** 100 rows | **Columns:** 22

### Column Reference

| # | Column | Type | Description |
|---|--------|------|-------------|
| 1 | `order_id` | str | Unique order identifier (ORD001…) |
| 2 | `customer_id` | str | Unique customer ID (CUST001…) |
| 3 | `customer_name` | str | Full name of the customer |
| 4 | `customer_age` | int | Age of the customer |
| 5 | `gender` | str | Male / Female |
| 6 | `city` | str | Delivery city |
| 7 | `state` | str | Delivery state (US state code) |
| 8 | `country` | str | Country of delivery |
| 9 | `product_id` | str | Unique product ID (PROD###) |
| 10 | `product_name` | str | Name of the purchased product |
| 11 | `category` | str | Product category (Electronics, Furniture, etc.) |
| 12 | `sub_category` | str | Product sub-category |
| 13 | `quantity` | int | Units ordered |
| 14 | `unit_price` | float | Price per unit ($) |
| 15 | `discount` | float | Discount rate applied (0.0–1.0) |
| 16 | `total_price` | float | Final order total after discount ($) |
| 17 | `payment_method` | str | Credit Card / Debit Card / PayPal / etc. |
| 18 | `order_date` | date | Date the order was placed |
| 19 | `ship_date` | date | Date the order was shipped |
| 20 | `delivery_days` | int | Days taken for delivery |
| 21 | `rating` | float | Customer satisfaction rating (1.0–5.0) |
| 22 | `returned` | str | Whether the order was returned (Yes / No) |

---

## 🛠️ Tools & Libraries Used

| Library | Version | Purpose |
|---------|---------|---------|
| **Dask** | Latest | Parallel big data processing |
| **Pandas** | 1.5+ | Data manipulation and aggregation |
| **NumPy** | 1.23+ | Numerical operations |
| **Matplotlib** | 3.6+ | Charts and visualizations |
| **Seaborn** | 0.12+ | Statistical plots |

---

## 🔧 How to Run

### Step 1 — Install dependencies
```bash
pip install dask pandas numpy matplotlib seaborn jupyter
```

### Step 2 — Clone or download this folder
```
Task-1-Big-Data-Analysis/
├── big_data_analysis.ipynb
├── ecommerce_sales_data.csv
└── README.md
```

### Step 3 — Open the notebook
```bash
jupyter notebook big_data_analysis.ipynb
```

### Step 4 — Run all cells
**Kernel → Restart & Run All**

---

## 📓 Notebook Structure

| Section | Description |
|---------|-------------|
| 1 | Environment Setup & Library Imports |
| 2 | Load Dataset with Dask (Parallel Read) |
| 3 | Dataset Overview & Quality Check |
| 4 | Sales & Revenue Analysis (Category & Sub-Category) |
| 5 | Customer & Demographic Analysis (Age, Gender) |
| 6 | Regional Analysis (City & State-wise Revenue) |
| 7 | Payment Method Analysis |
| 8 | Delivery & Return Analysis |
| 9 | Top Products & Customers |
| 10 | Data Visualizations (Bar, Line, Heatmap, Pie) |
| 11 | Dask Scalability Demo (Dask vs Pandas) |
| 12 | Final Insights Summary |

---

## 📈 Key Business Insights

1. **100 orders** processed in parallel using Dask partitions
2. **Credit Card** is the most preferred payment method among customers
3. **Electronics** category generates the maximum revenue
4. **New York & California** lead in total order volume
5. Average customer rating indicates a **positive purchase experience**
6. Return rate is low — indicating healthy product-market fit
7. **Female customers** show higher average spending per order
8. **25–35 age group** is the highest spending demographic
9. Dask processes the dataset **in parallel partitions** — the same code scales to millions of rows
10. Orders with **discounts above 10%** show higher return rates

---

## 🔑 Why Dask for Big Data?

| Feature | Pandas | Dask |
|---------|--------|------|
| Max Dataset Size | Limited by RAM | Larger than RAM ✅ |
| Processing | Single-core | Multi-core Parallel ✅ |
| API | Standard | Pandas-compatible ✅ |
| Lazy Evaluation | ❌ | ✅ |
| Scalability | Low | Cluster-scale ✅ |

---

<div align="center">
<b>CODTECH IT Solutions Pvt. Ltd.</b> — Data Analytics Internship — Task 1
</div>
