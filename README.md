# Customer Segmentation & RFM Analysis

### Python · Pandas · Power BI · RFM Analysis

An end-to-end customer analytics project that analyzes customer purchasing behavior using the **RFM (Recency, Frequency, Monetary)** framework. The project processes raw transactional data from the Olist (Brazilian E-Commerce) dataset using Python and Pandas, segments customers based on purchasing behavior, and presents actionable business insights through an interactive Power BI dashboard.

---

# 🛠️ Project Workflow

1. **Data Collection**
   - Selected the Customers, Orders, and Payments datasets from the Olist E-Commerce dataset.

2. **Data Preparation**
   - Merged the datasets using customer and order identifiers.
   - Filtered only delivered orders.
   - Aggregated multiple payment records belonging to the same order.
   - Converted purchase timestamps into datetime format.

3. **RFM Analysis**
   - Calculated Recency, Frequency, and Monetary metrics for every customer.
   - Categorized customers into meaningful business segments.

4. **Data Export**
   - Generated summarized CSV files containing customer segments, revenue contribution, and RFM metrics.

5. **Power BI Dashboard**
   - Built an interactive dashboard to visualize customer behavior and revenue insights.

---

# 📂 Dataset

The project uses the following Olist datasets:

- **Customers Dataset**
  - Customer information
  - Customer location
  - Customer identifiers

- **Orders Dataset**
  - Order details
  - Purchase timestamps
  - Order status
  - Delivery information

- **Payments Dataset**
  - Payment value
  - Payment type
  - Installments

---

# 📊 RFM Metrics

## Recency (R)

Measures **how recently** a customer made a purchase.

Lower recency indicates a more active customer.

---

## Frequency (F)

Measures **how often** a customer places orders.

Higher frequency indicates greater customer loyalty.

---

## Monetary (M)

Measures **how much** a customer has spent.

Higher monetary value indicates a more valuable customer.

---

# 👥 Customer Segmentation

Customers are classified into business-friendly segments based on their purchasing behavior, including:

- Champions
- VIP At Risk
- New Customers
- New Shoppers
- Slipping Customers
- Hibernating Customers

These segments help businesses design targeted retention and marketing strategies.

---

# 📈 Dashboard Overview

The Power BI dashboard provides insights into:

### Customer Segmentation

- Customer count by segment
- Percentage distribution of customer segments

---

### Revenue Analysis

- Revenue contribution by customer segment
- High-value customer identification

---

### RFM Analysis

- Recency distribution
- Frequency distribution
- Monetary distribution
- Customer-level RFM metrics

---

# 📂 Repository Structure

```text
Customer_Segmentation_RFM/

├── datasets/
│
├── output/
│
├── source_code.ipynb
│
├── customer_segmentation_dashboard.pbix
├── customer_segmentation_dashboard.pdf
├── README.md
└── .gitignore
```

---

# 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

# 📌 Key Business Insights

This project helps answer questions such as:

- Which customers are the most valuable?
- Which customers are at risk of churn?
- Which customer segments contribute the highest revenue?
- Which customers should be targeted with retention campaigns?
- How are customers distributed across different RFM segments?

---

# 🎯 Project Outcome

This project demonstrates an end-to-end customer analytics workflow by combining data preprocessing, RFM-based customer segmentation, and interactive business intelligence dashboards. It enables businesses to better understand customer purchasing behavior and support data-driven marketing and customer retention strategies.
