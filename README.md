# Sales Dashboard Overview

This repository contains a Power BI Sales Dashboard project designed to visualize key performance indicators (KPIs) of a business's sales, profit, and quantity. The dashboard includes multiple interactive features and visual elements that provide insights into sales performance across different sub-categories, cities, and customer segments.

## Features

### 1. Total KPIs
   - Total Sales: $2.12M
   - Total Amount: $428.13K
   - Total Profit: $36.96K
   - Total Quantity Sold: 5449 units

### 2. Slicers for Dynamic Filtering
   - State Slicer: Filter data based on specific states.
   - City Slicer: Narrow down sales based on cities.
   - Date Slicer: View sales trends based on specific dates.
   - Month Slicer: Analyze monthly sales trends.

### 3. Interactive Charts
   - Total Sales by Sub-Category: 
     - Top 3 sub-categories are Printers ($309.96K), Bookcases ($295.6K), and Sarees ($259.78K).
     - Bottom sub-categories include Chairs and Electronics.
   - Best Customers: 
     - Top customers: Abhishek (75 units), Priyanka (72 units), Shruti(67 units), Shreya (65 units), and Vishakha (59 units).
   - Total Quantity by Month: Visualize the total quantity of units sold by month, which shows that March and January had the highest units sold and september and July is declining. 
   - Profit and Loss Chart: Displays profit (924 times) and loss (529 times).

### 4. Donut Charts
   - Profit by Category: 
     - **Clothing**: 36%
     - **Electronics**: 36%
     - **Furniture**: 28%
   - **Payment Methods**: 
     - **Cash on Delivery (COD)**: 45%
     - Other methods include **UPI**, **Debit Card**, **Credit Card**, and **EMI**.
   - **Profit by City**:
     - Top-performing city: **Indore** ($6.8K), followed by **Pune** ($6.2K) and **Mathura** ($3.3K).
     - Other cities include **Chandigarh** and **Chennai**.
     
### 5. **Sales Performance by Month**
   - The **best-performing month** in terms of sales is **January**, while **July** is the worst.

### 6. **Category Sold**
   - **Clothing** dominates the categories with **3.4K** units sold, while **Furniture** is at the bottom with **0.9K**.

### 7. **Interactive Map**
   - The dashboard includes a **State Map** button created with bookmarks for easy navigation to regional sales data.

### 8. **Dark/Light Theme Toggle**
   - The dashboard offers a **Dark Mode** and **Light Mode** switch, implemented using DAX (Data Analysis Expressions). This feature allows users to switch between themes for better visualization based on their preferences.

### 9. **Auto-Refresh Date**
   - The **Last Refresh Date/Time** is automatically updated when the dashboard data is refreshed, keeping the analysis up to date with the latest sales data.

## Tools and Techniques

- **Power BI**: Utilized for building the dashboard, creating interactive visualizations, and connecting to data sources.
- **DAX (Data Analysis Expressions)**: Used to implement the light/dark mode toggle and other advanced calculations.
- **Bookmarks**: Employed for the State Map and theme switch functionalities.
- **Refresh Date Automation**: Ensures real-time tracking of the last data refresh.

## Project Structure

- **Dashboard Layout**: 
  The dashboard is split into several key sections: KPIs, Sub-Category Sales, Customer Analysis, Quantity by Month, and Profit by City/Category/Month. 

- **Slicers**: Four slicers are placed on the left for interactive filtering of data: **State**, **City**, **Date**, and **Month**.

## Dataset

The dataset used for this dashboard includes the following attributes:
- **Sales Data**: Includes the sales amount, quantity, profit, and other relevant information.
- **Geographical Data**: Data on states and cities where the sales occurred.
- **Customer Data**: Best customers based on sales quantity.
- **Time-Based Data**: Month and date of the transactions for time series analysis.
  
**Note:** The dataset has been cleaned and transformed for analysis purposes.

## Conclusion

This Power BI Sales Dashboard is a comprehensive tool for visualizing sales performance, identifying top customers, and analyzing profit across different categories, cities, and time periods. The interactive features, along with the light/dark mode and real-time refresh capabilities, enhance its usability for business stakeholders.
