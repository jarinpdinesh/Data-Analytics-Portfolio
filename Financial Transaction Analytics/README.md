# 💳 Financial Transaction Analytics & Risk Reporting Pipeline

## 📌 Project Overview
Analyzed 12,000 transaction records across spending categories to identify checkout bottlenecks, transaction failure rates, and fraud false-positives.

## 🛠️ Tools Used
- **SQL:** Aggregations, CTEs, Data Extraction
- **Excel:** Data Cleaning (`COUNTBLANK`, `ABS`, nested `IFS`)
- **Power BI:** Star Schema Modeling, DAX Measures, Interactive Dashboards

## 🔑 Key Findings & Business Impact
- **50.03% Checkout Failure Rate** and **49.24% False-Positive Fraud Flag Rate** identified across digital payment channels (Cards: 48.25%, UPI: 48.75%).
- **Imputed 3,600+ missing records** across customer names and payment modes.
- Identified **Kerala as the top revenue market (₹120.4M)** via Power BI star-schema analytics.
- **Strategic Recommendations:** Proposed dynamic payment gateway failover routing and conditional OTP verification for high-value orders (>₹50,000).