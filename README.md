# 📊 Pizza Sales Performance Dashboard 

<img width="1000" alt="pizza" src="https://github.com/user-attachments/assets/ef31068e-3c73-477b-b436-5ab5c0fb0ea0" />
<img width="1000" alt="pizza3" src="https://github.com/user-attachments/assets/5fad3dc8-ccc3-4ab5-a639-5cf464b759d2" />


## 📊 Live Dashboard
[🔗 View the Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDUwNGU0NmItZTAxYS00MDAyLWE4YmQtMWE4NDBiMTI4YzI4IiwidCI6ImU4Njk2MTEzLWQ0NTktNDI4OS05YjkxLTk5MjcwM2M0NzNjMSJ9&pageName=6b10c0a6570901128069)

---
## 📌 Project Overview
Pizza businesses often collect large amounts of transaction data but struggle to identify which products, times, and behaviors truly drive sales.  
This project focuses on building a **Power BI dashboard** that highlights key KPIs, reveals customer behavior, and provides actionable insights for better menu planning, promotions, and inventory management.

---

## ⚙️ Data & Tools
- **Dataset**: Single CSV file containing order-level sales transactions.
- **Tools**: Power BI (Power Query + DAX).
- **Data Modeling**: Star schema built by referencing queries into multiple fact and dimension tables (orders, pizzas, categories, ingredients).

---

## 🔍 Approach
1. **Data Cleaning & Preparation**
   - Defined data types, checked for missing values.
   - Split columns for clarity (e.g., pizza size, category).
   - Built dimension tables using Power Query’s *reference method*.
2. **KPI Selection**
   - Researched typical pizza shop metrics and matched with available data.
   - Tracked: Total Revenue, Total Orders, Multi-item Order %, Best-Selling Pizzas, Ingredient Usage, Sales by Size/Time.
   - Added **contextual KPIs** (month-over-month % change).
3. **Dashboard Design**
   - **Sales Overview**: Revenue, orders, daily trends, and peak order times.
   - **Menu Analysis**: Sales by pizza, size, and ingredient usage.
   - **Customer Behavior**: Multi-item vs single-item, popular combinations.

---

## 📊 Key Insights
- **Revenue**: $817.8K from 21,350 orders.
- **Customer Behavior**: 61.6% of customers ordered multiple items → opportunity to push combo deals.
- **Product Performance**: Classic Deluxe, Hawaiian, and Pepperoni Pizzas were top sellers.
- **Seasonality**: November saw unusually high revenue with similar order counts → customers purchased higher-value pizzas.
- **Pizza Size**: Large pizzas dominated orders, reflecting preference for value.
- **Timing**: Peak orders between **5–8 PM**; Sunday consistently the lowest sales day.

---

## 🚀 Business Impact
The dashboard provides restaurant owners with insights to:
- Optimize menu offerings and inventory.
- Design and promote combo deals.
- Adjust staffing to match peak hours.
- Run seasonal promotions for high-value pizzas.

---

## 🧠 Learning Outcomes
- Gained experience in **data modeling with Power Query** and **DAX** optimization.
- Learned the importance of **context in KPIs** (e.g., comparisons vs last month).
- Improved ability to think from a **business-owner’s perspective** and translate raw data into actionable insights.
- Focused on **usability** through clear visuals, purposeful color coding, and intuitive navigation.

---

## 🔮 Future Improvements
- Perform **Market Basket Analysis** to recommend pizza pairings.
- Add **forecasting** to predict monthly/weekly sales.
- Introduce **customer segmentation** for targeted marketing.

---

## 🛠️ Tech Stack
- **Power BI** (Power Query, DAX, Visualizations)


