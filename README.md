# Olist E-Commerce Strategic Customer Segmentation Analysis
## Data Platform Analytics & Behavioral Value Pipeline

An end-to-end data engineering and business intelligence project that processes raw transactional e-commerce data from Olist (Brazil), engineers behavioral consumer features using the **RFM (Recency, Frequency, Monetary)** framework in Python, and deploys an executive-ready dashboard presentation.

---

### 🚀 Business Case & Strategic Insights
The analysis uncovers a critical structural asymmetry within the Olist platform: **We do not have a customer acquisition problem; we have a severe customer retention problem.**

* **The Scale Bottleneck:** Over **85%** of the active user base is concentrated in low-velocity or inactive states (**Slipping** at 48.83%, **New Shoppers** at 19.11%, and **Hibernating** at 17.09%).
* **The Financial Powerhouse:** A mere **14.53%** of the customer base (**VIP at Risk**) generates a staggering **34.2% (R$ 5.27M)** of total platform revenue. 
* **The Revenue Leak:** The **Slipping** segment represents a massive **R$ 5.65M (36.65%)** in historical capital that is actively leaking from the platform.

**Core Recommendation:** Reallocate marketing capital away from expensive top-of-funnel customer acquisition campaigns and immediately deploy automated CRM retention sequences to lock in the *VIP at Risk* segment while launching a targeted win-back campaign for the *Slipping* high-value cohort.

---

### 📂 Repository Directory Layout & Core Assets

```text
Olist_E_Commerce_Customer_Segmentation/
├── datasets/                           # Raw transactional tables (Relational Base)
├── output/                             # Pipeline Outputs & Exploratory Analysis
│   ├── olist_customer_operational_ledger.csv
│   ├── olist_executive_revenue_matrix.csv
│   ├── olist_marketing_volume_share.csv
│   └── *.png                           # Matplotlib & Seaborn distribution graphs
├── source_code.ipynb                   # Master Python Pipeline (Heavily Commented)
├── customer_segmentation_dashboard.pbix # Master Power BI Desktop Project File
└── customer_segmentation_dashboard.pdf  # High-Resolution Executive Dashboard PDF
