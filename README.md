# **Chocolate Sales Dashboard**

## **Introduction**
In this project, I built an interactive executive dashboard to analyze chocolate sales data across multiple dimensions. The goal was to provide meaningful insights into the overall performance of different chocolate products (bars, bites, others) and analyze sales by geography, teams, and product categories. By utilizing Power Pivot, DAX (Data Analysis Expressions), and advanced Excel formulas, this dashboard helps stakeholders understand trends, performance metrics, and the profitability of different products.

### **Problem Statement**
Businesses often face the challenge of tracking and understanding sales performance across regions, teams, and product lines. For chocolate products, which are sold across multiple countries and through several sales teams, it is essential to have a consolidated view of key metrics such as sales, profit, and shipments, along with their trends over time. This dashboard serves as a tool to make data-driven decisions for improving sales strategy and maximizing profits.

### **Objective**
To build a dynamic and interactive dashboard that provides:
1. Total and monthly values for sales, shipments, profit, and profit percentages.
2. Geographic sales analysis, highlighting the best-performing countries.
3. Team performance breakdown.
4. Detailed product performance analysis.


## **Process Overview**

### 1. **Data Cleaning and Preparation**
   - Cleaned the tables to remove duplicates and irrelevant data.
   - Established relationships between the tables using Power Pivot for better data integration and analysis.

### 2. **Calculation Worksheet**
   - Built a separate worksheet for all the necessary calculations, ensuring data consistency and efficiency when referencing measures across the dashboard.

### 3. **Dashboard Overview**
   The dashboard consists of four main sections:
   - **Total Sales, Boxes, Shipments, Profit, and Profit %**: These metrics are displayed both monthly and overall, filtered by the product category (bars, bites, others) using a slicer.
   - **Country Sales and Profit %**: Shows performance across different countries, highlighting the best-performing regions.
   - **Team Performance**: Breakdown of sales and profit by teams: Yummies, Delish, Jucies, and Tempo.
   - **Product Performance**: Displays key metrics for individual products, sorted by sales, profit, boxes, and shipments.


## **Steps and Process**

### **1. Total Sales, Boxes, Shipments, Profit, and Profit %**
   - Utilized DAX measures to calculate monthly and overall values for sales, shipments, cost, profit, and profit percentages.
   - Incorporated a category slicer to filter data by bars, bites, or other product categories.
   - Built and fine-tuned KPI tiles to display these values dynamically as per the category selection.
   - Integrated monthly and overall sales figures into interactive visuals.

### **2. Country Sales and Profit %**
   - Added interactive maps to visualize country-wise performance.
   - Sorted the country data using Excel formulas, and linked the data to map visuals with dynamic picture links.
   - Highlighted the top-performing country based on both sales and profit %.
   - Added additional metrics such as total shipments and profit percentages alongside the map visuals.

### **3. Team Performance**
   - Developed a team performance area featuring a bubble chart to visualize sales and profit by team.
   - Used sparklines to showcase a 28-day sales trend for each team.
   - Created team-related pivots to sort and display data dynamically, adding sorting options for enhanced user interaction.
   - Implemented conditional formatting to display team rankings based on sales and profit, helping identify top-performing teams and individuals.

### **4. Product Performance**
   - Built a section dedicated to product performance, with detailed pivots showing sales, profit, boxes, and shipments.
   - Created gauge charts to show the profit percentage for each product category.
   - Sorted products by sales, shipments, and profit using two-tier sorting logic, allowing users to drill down into the data for specific products.
   - Used sparklines to display the last 28 days’ product performance trends, alongside sorting options for deeper analysis.


## **Key Questions and Answers**

![Excel_Dashboard](https://github.com/user-attachments/assets/5960550f-64dc-423a-8112-495d8ed712a6)

- **What are the overall sales and profit generated?**
  - **Sales**: $21.70 million
  - **Profit**: $15.02 million
  - **Profit %**: 69.2%

- **What are the monthly sales and profit for each product category?**
  - **Bars**: Sales - $10.74 M, Profit - $7.41 M
  - **Bites**: Sales - $7.08 M, Profit - $4.27 M
  - **Others**: Sales - $3.88 M, Profit - $3.34 M

- **Which category performed the best?**
  - Bars performed the best overall with the highest sales and profit.

- **Which country performed the best in terms of sales and profit %?**
  - **USA**: Profit % - 70.6%
  - **New Zealand**: Sales - $3.78 million

- **What team performed the best in terms of sales and profit?**
  - **Yummies** led in both sales ($7.89 million) and profit ($5.47 million), followed by Delish, Jucies, and Tempo.

- **Who are the top-performing salespeople in the Yummies team?**
  - The top salesperson can be seen in the bubble chart under the Yummies section.
    ![yummies](https://github.com/user-attachments/assets/6fd7e414-f3c0-42b2-9989-1ce84728b353)

- **What are the top products sorted by sales, shipments, profit, and boxes?**
  - The product details table shows the top-performing products for the Bars Category, sorted by the chosen metric (here Sales).
    ![WhatsApp Image 2024-09-06 at 00 56 34_579f15cf](https://github.com/user-attachments/assets/d3967abd-952b-4759-abe5-49dd12e4072d)


## **What I Learned**

Throughout the project, I gained valuable insights into creating an interactive and dynamic dashboard, including:

- **Designing an Executive Dashboard**: Creating visually appealing, user-friendly dashboards for key stakeholders.
- **Using Power Pivot and DAX**: Mastering advanced Excel tools for building complex data models and performing detailed calculations.
- **Building Custom Visuals**: Leveraging Excel’s features like sparklines, bubble charts, and gauge charts to enhance the dashboard’s interactivity.
- **Applying Conditional Formatting**: Using formulas and rules to make data visually engaging and informative.
- **Creating Dynamic Tables**: Using formulas like `SORT`, `FILTER`, and `SORTBY` to build responsive and interactive tables.
- **Integrating Slicers**: Providing users with control over the data displayed in the dashboard, adding a layer of interactivity.
  

## **Conclusion**

This project demonstrates how to build a robust and interactive executive dashboard for chocolate sales analysis. By integrating various Excel tools like Power Pivot, DAX, dynamic charts, and slicers, I was able to gain valuable insights into product, team, and geographical performance. The dashboard provides stakeholders with an efficient tool to analyze key metrics, improve sales strategies, and optimize profits.
