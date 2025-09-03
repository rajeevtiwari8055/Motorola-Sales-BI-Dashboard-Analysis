## 📱 Motorola-Sales-BI-Dashboard-Analysis

---

## 📑 Table of Contents

- <a href="#project-overview">🧩 Project Overview</a>  
- <a href="#project-context">🏢 Project Context</a>  
- <a href="#project-objective">🎯 Project Objective</a>  
- <a href="#target-audience">🔍 Target Audience</a>  
- <a href="#business-problem">🛑 Business Problems Addressed</a>  
- <a href="#key-insights">💡 Key Features & Insights</a>  
- <a href="#data-description">📦 Data Description</a>  
- <a href="#tools-used">🛠️ Tools & Technologies Used </a>  
- <a href="#solution-approach">🧪 Solution Approach</a>  
- <a href="#business-impact">📈 Business Impact</a>  
- <a href="#learning-skills">📚 Learnings & Skills Demonstrated </a>  
- <a href="#future-enhancements">🔮 Future Enhancements</a>
- <a href="#conclusion">🔚 Conclusion</a>
- <a href="#contact">📬 Connect with Me</a> 
- <a href="#project-snapshot">🖼️ Project Snapshot</a> 

---

## <span id="project-overview">🧩 Project Overview</span>  

This interactive **Power BI Sales Dashboard** is designed for **Motorola** to analyze sales data across **cities**, **mobile models**, **payment methods**, and **customer ratings**. As my **first Power BI project**, it showcases the integration of **key KPIs**, **DAX measures**, and **dynamic filters** to extract actionable insights. The dashboard highlights **total sales**, **quantity sold**, **average transactions**, and **performance trends by month and day**. With **intuitive visuals** and **interactive components**, it empowers decision-makers to make **data-driven choices**. This project serves as a **strong foundation** for advancing into more complex analytics solutions.

---

## <span id="project-context">🏢 Project Context</span>  

In a highly competitive smartphone market, Motorola needed a robust sales intelligence tool to understand where, when, and how their products were performing. This project was developed to bridge the gap between raw data and strategic insights, offering a detailed breakdown of sales performance to guide future growth.

---

## <span id="project-objective">🎯 Project Objective</span>  

- To visualize and analyze Motorola's sales performance using key business indicators.  
- To identify sales trends by city, time, and mobile models.  
- To understand customer satisfaction through ratings.  
- To compare performance across payment modes for operational improvements.  
- To enable dynamic filtering and drill-down analysis for actionable business planning.

---

## <span id="target-audience">🔍 Target Audience </span>  

- **Sales Managers** – For monitoring targets and performance.  
- **Marketing Teams** – To identify regional strengths and consumer trends.  
- **Inventory Planners** – For demand forecasting and stock optimization.  
- **Executives** – For high-level, real-time business intelligence.

---

## <span id="business-problem">🛑 Business Problems Addressed </span>  

- No centralized system to view sales quantity, revenue, and transactions in real-time.  
- Inability to measure city-wise and brand/model-wise performance effectively.  
- Lack of customer sentiment visibility via ratings.  
- No clarity on which payment methods are preferred.  
- Missed opportunities to optimize campaigns around peak sales days/months.

---

## <span id="key-insights">💡 Key Features & Insights</span>  

### 1. 📌 KPI Cards  
- **Total Sales**: Overall revenue across all Motorola products.  
- **Total Quantity**: Total units sold.  
- **Total Transactions**: Number of purchase events.  
- **Average Sales per Transaction**: Indicates customer value and pricing efficiency.

### 2. 🏙️ Total Sales by City  
- Identifies high-performing and underperforming cities.  
- Helps in local campaign planning and stock allocation.

### 3. 📅 Units Sold by Month and Day  
- Detects monthly and daily sales patterns.  
- Useful for understanding seasonal demand.

### 4. ⭐ Customer Ratings  
- Captures user satisfaction.  
- Highlights areas where product or service quality can be improved.

### 5. 📱 Sales by Mobile Model  
- Shows which Motorola models are most popular.  
- Supports product development and marketing focus.

### 6. 💳 Sales by Payment Method  
- Breakdown of revenue by Cash, UPI, Cards, EMI, etc.  
- Aids in financial processing and digital infrastructure planning.

### 7. 🗓️ Month-wise Filter  
- Users can explore all metrics for specific months.  
- Enables seasonal analysis and planning.

### 8. 📆 Sales by Day Name  
- Reveals weekly trends (e.g., higher weekend sales).  
- Useful for campaign timing and staff planning.

### 9. 📋 Table: Brand-wise Sales & Quantity  
- Displays total quantity and transaction count for each mobile brand (Motorola sub-models).  
- Helps in procurement and vendor evaluation.

---

## <span id="data-description">📦 Data Description</span>  

The dataset contains over **5,000 records** from Motorola’s sales channels with the following fields:

- Date of Transaction  
- Mobile Model  
- Quantity Sold  
- Sales Value  
- Customer Rating  
- Payment Method  
- City  
- Brand  
- Transaction ID  

> All data was anonymized and structured in `.CSV` format for modeling.

---

## <span id="tools-used">🛠️ Tools & Technologies Used</span>  

- **Power BI** – For dashboard development and data visualization.  
- **Power Query** – For ETL (Extract, Transform, Load) operations.  
- **DAX (Data Analysis Expressions)** – For calculated KPIs and business logic.  
- **Excel/CSV** – For initial data preparation.

---

## <span id="solution-approach">🧪 Solution Approach</span>  

### 🔹 Data Cleaning  
- Removed blanks, duplicates, invalid dates, and inconsistent values.  
- Standardized city names and product models using Power Query.

### 🔹 Data Modeling  
- Star schema with fact and dimension tables for efficient slicing and aggregation.  
- Built strong relationships between Date, Product, City, and Sales tables.

### 🔹 DAX Measures  
Defined custom measures:  
- `Total Sales`  
- `Avg. Sales per Transaction`  
- `Rating Average`  
- Time intelligence functions for dynamic period analysis.

### 🔹 Visualizations Used  
- Card Visuals for KPIs  
- Bar and Column Charts for comparisons  
- Line Graphs for trends  
- Pie/Donut Charts for payment method breakdown  
- Matrix/Table for brand-level details  
- Slicers and Filters for dynamic navigation

---

## <span id="business-impact">📈 Business Impact</span>  

- Stakeholders now have **real-time visibility** into performance metrics.  
- **Sales strategies** can be tailored based on location, model, and time.  
- **Customer feedback** is instantly actionable.  
- **Financial planning** improved through payment behavior analysis.  
- **Time-based insights** help forecast demand and plan inventory better.

---

## <span id="learning-skills">📚 Learnings & Skills Demonstrated</span>  

- Power BI Advanced Visualization Techniques  
- Power Query Data Transformation  
- DAX Calculated Columns and Measures  
- Business Intelligence Storytelling  
- UI/UX Dashboard Design  
- Real-world Business Problem Solving

---

## <span id="future-enhancements">🔮 Future Enhancements</span>  

- ✅ Sales Forecasting Models using AI/ML integration  
- 📦 Inventory-Level Dashboard to show stock vs sales  
- 👤 Customer Profile Analytics for segmentation  
- 📢 Campaign Tracking Metrics for marketing ROI  
- 🌍 Geo-Mapping Visuals for city/region performance

---

## <span id="conclusion">🔚 Conclusion</span>  

This **Motorola Sales Dashboard** bridges the gap between raw sales data and strategic decision-making. With a clean and interactive layout, it offers a full-circle view of operations — from product performance and customer sentiment to regional trends and transaction insights.

By incorporating real-time metrics and intuitive visuals, this project becomes a critical tool for sales optimization, campaign targeting, and customer-focused growth.

---

## <span id="contact">📬 Connect with Me</span>  

- 📧 **Email**: [rajeevtiwari8055@gmail.com](mailto:rajeevtiwari8055@gmail.com)  
- 💻 **GitHub**: [github.com/rajeevgit8055hub](https://github.com/rajeevgit8055hub)  
- 🔗 **LinkedIn**: [linkedin.com/in/rajeev-tiwari123](https://www.linkedin.com/in/rajeev-tiwari123)  
- 🌐 **Website**: [rajeevgit8055hub.github.io/rajeevtiwari.github.io](https://rajeevgit8055hub.github.io/rajeevtiwari.github.io/)  

🤝 *Thanks for visiting my profile!*  

---

## <span id="project-snapshot">🖼️ Project Snapshot</span>     

### 🖼️ Final Dashboard
![Motorola Sales Dashboard Analysis](Motorola%20Sale%20Dashboard%20Analysis.png)

### 🖼️ Project Preview
  
![Motorola Sales Dashboard Analysis](Motorola%20Sales%20Dashboard%20Analysis.png)

---

