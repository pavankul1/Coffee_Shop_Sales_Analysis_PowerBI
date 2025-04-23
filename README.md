# Coffee_Shop_Sales_Analysis_PowerBI

# ☕ Coffee Shop Sales Dashboard – Power BI Project

This project is an interactive, KPI-driven Power BI dashboard built to analyze the sales, orders, and customer behavior for a fictional coffee shop business. The dashboard transforms transactional data into a clear visual story to help decision-makers track performance and trends.

---

## 📈 Key Metrics Tracked

- **Total Sales**: $157K  
- **Total Orders**: 33,527  
- **Quantity Sold**: 48,233  
- **Total Customers**: 14,673  
- **Top Product**: Barista Espresso – $20.42K  
- **Top Category**: Coffee – $60.36K  
- **Top Location**: Hell’s Kitchen – $52.60K  
- **Peak Hour**: 10–11 AM  
- **Weekday Sales**: 74.41%

---

## 📊 Dashboard Features

- **KPI Cards**: Sales, Orders, Quantity with ▲▼ indicators and % change using custom MoM DAX
- **Custom Tooltip Pages**:
  - Tooltip 1: Calendar view (day-level insights)
  - Tooltip 2: Hour x Day heatmap (footfall patterns)
- **Cross-Visual Filtering**: Used “Edit Interactions” so all visuals respond to user input
- **Dynamic Labels**:
  - `"Coffee | $60.36K"`, `"Barista Espresso | $20.42K"`, `"Downtown | $44.9K"`
- **Slicers**: Month-Year, Product Category, Store Location

---

## 🧮 DAX & Calculated Columns

- **Total_Sales** = `SUM(Transactions[Unit_Price] * Transactions[Transaction_QTY])`
- **CM/PM Sales & MoM Metrics** using `DATEADD` and `TOTALMTD`
- **Conditional Formatting**: `Color for Bars` = "Above_Avg" / "Below_Avg"
- **Custom Tooltips**: `TT for Hour`, `Foot_Note`
- **Label Formulas**: Category, Type, and Store Location bar labels

> 🧠 21 Custom DAX Measures implemented (MoM_Sales, CM_Orders, PM_QTY_Sold, etc.)

---

## 🛠 Tools & Techniques Used

- Power BI Desktop  
- Power Query for data transformation  
- DAX (Advanced Calculations & Labeling)  
- Custom Date Table  
- Tooltip Page Design  
- Data Modeling (1:M relationships)

---

## 🔗 Related Projects

This dashboard builds upon the logic and insights from my previous [SQL Analysis Project](#), showcasing the ability to extract, transform, and visualize business data across platforms.

---

## 📌 Screenshots

> ![image alt]![Screenshot 2025-04-16 164349](https://github.com/user-attachments/assets/878e87aa-f8e0-44e4-8295-f28c869c5b2e)
> ![image alt]![Screenshot 2025-04-16 171057](https://github.com/user-attachments/assets/5d034136-20a1-486e-baba-3664503d05e9)
> ![image alt]![Screenshot 2025-04-16 171111](https://github.com/user-attachments/assets/c277265b-6389-4a16-8bca-7ba28c4b1459)





