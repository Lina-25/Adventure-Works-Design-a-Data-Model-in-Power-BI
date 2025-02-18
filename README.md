## 📊 AdventureWorks Sales & Profit Analysis - Power BI Dashboard

This Power BI dashboard offers a comprehensive, interactive analysis of AdventureWorks' sales and profit data. With dynamic filters, cross-highlighting, and drill-down features, it enables users to uncover valuable business insights across multiple pages. The dashboard allows for in-depth analysis by providing views at various levels, such as year, quarter, and employee performance.

---

## 🔧 Technical Overview

The Power BI dashboard is designed with a robust data model to enable seamless filtering and analysis across multiple pages. Here are the key features implemented:

1. **Data Modeling & Relationships**: Efficient data relationships ensure smooth filtering and aggregation across the visuals on the dashboard.
2. **Interactive Dashboards**: The dashboard includes dynamic filtering, cross-highlighting, and drill-down features for detailed exploration of sales and profit data.
3. **Hierarchical Drill-Down**: Users can drill down from high-level yearly data to quarterly or monthly data, providing flexibility in analysis.
4. **Advanced Data Visualizations**: The dashboard employs combo charts, stacked bar charts, ribbon charts, and matrix tables to deliver a diverse set of insights.
5. **Performance Monitoring & Analysis**: Metrics like sales, profit, and profit margin are presented alongside targets, enabling users to compare actual performance to expectations.
6. **Cross-Filtering & Cross-Highlighting**: Selecting a region, category, or employee automatically updates and highlights related data across all visualizations.

These features ensure that the dashboard is interactive and user-friendly, enabling effective analysis of AdventureWorks' business performance.

---

## 🖥️ Dashboard Visualizations

### **1️⃣ Overview Page**
- **Filters:**
  - Year filter (Select a specific year to update all visuals)
  - Region filter (Dynamic selection of regions)
- **Combo Chart:** Clustered Column Chart & Line Chart
  - **X-Axis:** Month
  - **Primary Y-Axis (Bars):** Sum of Sales
  - **Secondary Y-Axis (Line):** Profit
  - **Interactivity:** Selecting a month updates all other visuals.
- **Stacked Bar Chart:** Sales by Country & Category
  - **X-Axis:** Sum of Sales
  - **Y-Axis:** Country
  - **Legend:** Product Categories (Accessories, Bikes, Clothing, Components)
  - **Cross-Filtering & Highlighting:** Clicking on a category updates all charts.
- **Stacked Bar Chart:** Quantity Sold by Category
  - **X-Axis:** Sum of Quantity
  - **Y-Axis:** Category
  - **Cross-Filtering:** Selecting a category updates other visuals.
- **AdventureWorks Logo:** Added for consistency and aesthetics.

#### Visuals for Overview Page:

![Screen Shot 2025-02-18 at 10 22 49](https://github.com/user-attachments/assets/4bbb5d3b-bbea-4376-a767-520c51dbab59)

---

### **2️⃣ Profit Page**
- **Filters:**
  - **Year Filter:** Select a specific year to update the data dynamically.
- **Matrix Table:** Yearly Performance Overview
  - **Columns:** Year, Quarter (Q1 - Q4)
  - **Rows:** Order Count, Sum of Sales, Sum of Cost, Profit, Profit Margin
  - **Total:** Displays the totals at the bottom of the table for all metrics.
  - **Drill-Down Feature:** Allows detailed analysis of performance from the yearly to quarterly level.
- **Filter Panel:** Positioned at the side for easy selection and update of the year and region.

#### Visuals for Profit Page:

![Screen Shot 2025-02-18 at 10 23 16](https://github.com/user-attachments/assets/ec603599-22e8-4e32-9f34-7ecc66f22dee)

---

### **3️⃣ My Performance Page**
- **Filters:**
  - **Year Filter:** Used for filtering data based on selected year.
- **Key Performance Metrics Display (KPIs):**
  - **Sum of Sales:** Displays the total sales.
  - **Target:** Shows the sales target for comparison.
  - **Variance:** Highlights the difference between actual sales and the target, indicating performance.
- **Bar Chart:** Monthly Sales vs. Target
  - **X-Axis:** Month
  - **Y-Axis:** Sales and Target Values
  - **Bars:** Side-by-side bars representing the actual sales and target for each month, with different colors to clearly distinguish between the two.
  - **Interactivity:** Hovering over a bar displays additional details about the sales or target for that month.

#### Visuals for My Performance Page:
![Screen Shot 2025-02-18 at 10 23 55](https://github.com/user-attachments/assets/62775ebe-2e56-411e-a91a-1617c4fd9539)


---

## 🚀 How to Use the Dashboard

1. **View the dashboard on [Power BI Service](#)** _(Insert published dashboard link)_
2. **Select a year and region** to dynamically update all visuals.
3. **Analyze sales trends** using the combo chart to compare total sales and profit over time.
4. **Explore country-wise sales performance** by selecting a region or product category.
5. **Drill down into profit analysis** by viewing quarterly and yearly performance.
6. **Compare sales vs target performance** for each employee and evaluate individual contributions.

---

## ✨ Key Skills & Techniques Demonstrated

✅ **Data Visualization in Power BI** – Implemented Combo Charts, Stacked Bar Charts, Ribbon Charts, and Matrix Tables for structured analysis.  
✅ **Hierarchical Drill-Down & Navigation** – Enabled users to analyze performance from yearly to quarterly levels.  
✅ **Cross-Filtering & Cross-Highlighting** – Enhanced dashboard interactivity for in-depth data exploration.  
✅ **Data Modeling & Relationships** – Designed data relationships to ensure smooth filtering and calculation across visuals.  
✅ **Target vs Sales Performance Analysis** – Compared actual sales against set targets to assess business performance and employee achievements.

---

## 📝 Findings

The combination of charts and pages in this dashboard provides a clear overview of the performance across various business aspects and individual employees:

- The **Overview Page** helps identify the best performing years and countries for sales and profit, offering insights into the highest-performing product categories by region.
- The **Profit Page** enables detailed tracking of profit margins by quarter and region, allowing for the identification of patterns and areas for improvement. It’s easy to determine which quarters performed the best, and insights can be derived to support future strategies.
- The **My Performance Page** provides a comprehensive view of employee performance. By analyzing sales, targets, and variance, managers can identify which employees are meeting or exceeding targets and make informed decisions about how to support those who are not meeting expectations. It also helps assess the accuracy of target estimates and adjust strategies for future periods.

This dashboard ultimately supports business growth and helps track performance effectively, empowering managers with the data necessary to make strategic decisions.

