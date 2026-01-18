# 🛒 Zepto Product & Supply Chain Analysis

### 📊 Project Overview
This project analyzes a dataset of **3,000+ Zepto products** to identify revenue leaks, inventory inefficiencies, and pricing strategy gaps. Using **SQL** for data extraction and **Power BI** for visualization, the analysis reveals actionable insights for inventory managers to reduce stockouts and optimize revenue.

### 🛠️ Tech Stack
* **Database:** PostgreSQL / SQL Server
* **Analysis:** Advanced SQL (Window Functions, Aggregations)
* **Visualization:** Power BI (DAX Measures, Custom Formatting)

### 🔍 Key Insights & Dashboard Features
1.  **Revenue Risk Analysis:** identified **₹39k in immediate potential revenue lost** due to stockouts of high-demand items.
2.  **Inventory Logistics:** Found that **81% of inventory weight** is tied up in "Bulk" items (>5kg), impacting warehouse storage costs.
3.  **Pricing Inefficiency:** Discovered a disconnect in the pricing strategy where **High-MRP items (>₹500)** have significantly lower discount rates than low-margin items.
4.  **Stockout Leaders:** Isolate top 10 revenue-draining products (e.g., *Yummiez Green Peas*) that are currently unavailable.

### 📸 Dashboard
<img width="1171" height="659" alt="image" src="https://github.com/user-attachments/assets/1d32cefe-8aab-4e31-8c8f-0ac53d698a13" />


### 💻 How to Run
1.  **Load Data:** Import `zepto_dataset.csv` into your SQL database.
2.  **Run Queries:** Execute the SQL scripts in `analysis.sql` to generate base tables.
3.  **View Dashboard:** Open `Zepto_Analytics.pbix` in Power BI Desktop.
