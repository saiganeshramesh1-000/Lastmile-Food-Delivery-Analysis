# Lastmile Food Delivery Analysis #
## 📌 Overview 
  This project focuses on analyzing food delivery operations through data cleaning, exploratory data analysis (EDA), and interactive dashboard creation.
  It aims to uncover business insights related to order performance, revenue trends, delivery efficiency, and cancellation patterns.
  ## 📂 Dataset
  - **Source:**[Last Mile Delivery Analysis](https://www.kaggle.com/datasets/sujalsuthar/food-delivery-order-history-data)
- **Rows:** 21,320 orders
- **Columns:** 29 features
- **Target Variable:** `Order Status` (Delivered / Cancelled / Rejected / Returned / Timed Out)
- **Duplicates:** None
  ## 🛠️ Tools 

| Layer | Tool |
|---|---|
| Data Analysis | Python — Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| BI Dashboard | Power BI Desktop |

## 📈 Key Findings

- Analyzed **21,320** food delivery orders, generating a total revenue of **₹14.55M**.
- Achieved a **99.19%** delivery success rate, with **21k** orders successfully delivered. Only **186 orders (0.81%)** resulted in rejection, return, cancellation, pickup, or timeout.
- **Greater Kailash 2 (GK2)** generated the highest revenue (**₹4.76M**), followed by **Sector 4 (₹4.49M)** and **DLF Phase 1 (₹2.60M)**.
- **Tandoori Junction** recorded the highest average kitchen preparation time (**21 minutes**), followed by **Dilli Burger Adda (19 minutes)**.
- A total of **186** orders were cancelled, resulting in **₹47,402.47** in cancellation compensation.
- **Customer cancellations (48%)** and **platform cancellations (44%)** together accounted for **92%** of all cancelled orders.
- **Greater Kailash 2 (69 cancellations)** and **Sector 4 (63 cancellations)** recorded the highest number of cancelled orders.
- For cancelled orders, **Tandoori Junction** had the highest average kitchen preparation time (**20 minutes**), suggesting that longer preparation times may increase the likelihood of cancellations.
- Correlation analysis revealed a **moderate positive relationship (0.45)** between **kitchen preparation time** and **rider wait time**, indicating that longer preparation times generally lead to increased rider waiting times.
- The order value is **₹500-₹700**. 





