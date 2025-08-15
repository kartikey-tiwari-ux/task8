# 📊 Task 8 – Simple Sales Dashboard

## 🎯 Objective
Create a basic interactive dashboard to visualize sales performance by **Product Category**, **Region**, and **Month** using the `Sample - Superstore.csv` dataset.


## 🛠 Tools Used
- **Power BI** (for dashboard creation)
- **Microsoft Excel / Python (Optional)** – for basic data cleaning
- Dataset: **Sample - Superstore.csv**


## 📂 Dataset Overview
The dataset contains:
- **Order Date** – Date of purchase
- **Region** – Geographical region of sale
- **Category** – Product category
- **Sales** – Sales amount
- **Profit** – Profit earned


## 📌 Steps Followed

1. **Import Data**
   - Loaded `Sample - Superstore.csv` into Power BI.

2. **Data Preparation**
   - Changed `Order Date` column type to Date.
   - Created a calculated column:  
     ```DAX
     MonthYear = FORMAT('Sample - Superstore'[Order Date], "MMM-YYYY")


3. **Visualizations**
   - **Line Chart** – Sales over Months.
   - **Bar Chart** – Sales by Region.
   - **Donut Chart** – Sales by Category.
   - Added a **Slicer** for Region to filter visuals.

4. **Styling**
   - Applied consistent color theme.
   - Highlighted top-performing regions/categories.

5. **Export**
   - Saved the dashboard as a PDF and took a screenshot.


## 📈 Key Insights

1. **West Region** generated the highest sales.
2. **Technology** category had the highest sales, ahead of Furniture and Office Supplies.
3. **November 2017** was the peak sales month, with ~**$118K** in sales.
4. **South Region** recorded the lowest sales (~$392K).
5. **Highest Sales** observed in California, New York, and Texas.
6. **Standard Class** is the most used shipping method (nearly 60%).
7. **Sales peak** during Q4 months, particularly in November and December.
8. Cities like New York, Los Angeles, and Philadelphia contribute heavily to sales volume.


