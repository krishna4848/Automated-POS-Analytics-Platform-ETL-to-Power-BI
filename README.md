# POS-Sales-Financial-Dashboard-using-Power-BI
This project builds a finance-grade analytics solution for a multi-store frozen-yogurt operation modeled on Yogen Früz. The dataset contains transaction-level POS records  and the report translates raw sales into reconciled revenue, margin and operational insights.

🔍 Key Objectives

* Reconcile and validate POS data to ensure finance-grade accuracy (Total\_Sale, Profit, Margin).
* Identify revenue and margin drivers by **product**, **store**, **category**, and **payment channel**.
* Evaluate **promotion effectiveness** and **discount penetration** to protect margin.
* Surface operational levers (hourly and weekday demand) for staffing and inventory optimization.
* Provide interactive, executive-ready visuals to support FP\&A, Marketing, and Ops decisions.

📈 Insights Explored

* Top-line **revenue & profit trends** (MoM) and forecastable seasonality.
* **Pareto analysis**: which SKUs (top \~20%) drive the majority of revenue.
* **Margin delta**: full-price vs discounted transactions and the financial impact of promotions.
* **Store & channel performance**: which locations and payment methods deliver the best unit economics.
* **Operational peaks**: hourly and weekday patterns for workforce planning.

🛠️ Report Features

* Executive **KPI panel** (Revenue, Profit, Avg Order Value, Margin %, Discount Penetration).
* Multi-page layout: **Executive Summary**, **Sales Performance**, **Product Analysis**, **Promotions & Operations**.
* Advanced visuals: **Pareto (cumulative %) chart**, **Decomposition Tree**, and **Small-multiple trends**.
* Reproducible ETL in **Power Query** + finance-grade DAX measures; Python used for prototyping/EDA.
* Designed for automation: scheduled refresh, email subscriptions, and easy integration with ERP/budget sources.


