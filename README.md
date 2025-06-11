# Supermarket Stores Analysis Project
## By Onoriose Baro Monarch

---

This repository contains an exploratory data analysis (EDA) project focused on understanding retail store performance across various supermarket branches. The analysis leverages a dataset of 896 stores to extract crucial insights regarding sales, store size, item availability, and customer traffic using Python.

---

## 📊 Project Goals

The primary objectives of this analysis are to:

-   Identify Key Performance Indicators (KPIs): Understand the distribution of key metrics such as store sales, store area, items available, and daily customer count.
-   Pinpoint Top and Bottom Performers: Identify stores with the highest and lowest sales, store areas, and daily customer counts to understand performance extremes.
-   Uncover Correlations: Investigate the relationships between physical attributes (store area), inventory (items available), customer engagement (daily customer count), and financial success (store sales).
-   Inform Business Strategies: Transform raw data into actionable business intelligence to guide decisions on resource allocation, sales forecasting, and overall store optimization.

---

## 📁 Data Source

The dataset used for this project is `stores.csv`.

Key variables utilized in the analysis include:

-   Store_id: A unique identifier for each supermarket branch.
-   Store_area: The physical size of the store in square yards.
-   Item_Available: The total count of distinct product items stocked.
-   Daily_customer_count: The average number of customers per day.
-   Store_sales: The cumulative sales revenue in US dollars.

---

## 🚀 Methodology

The analysis is performed using Python, leveraging its powerful data science libraries. The key steps involved are:

-   Environment Setup: Importing `pandas` for data manipulation, `numpy` for numerical operations, and `matplotlib.pyplot` along with `seaborn` for data visualization.
-   Data Loading & Initial Inspection: Loading the `stores.csv` file into a Pandas DataFrame and creating a working copy. Initial checks for data shape, data types, and missing values are performed.
-   Data Cleaning & Transformation: Renaming columns for clarity (`Store_id`, `Store_area`, `Item_Available`, `Daily_customer_count`, `Store_sales`). A thorough check for null values confirmed data completeness.
-   Performance Analysis: Sorting data to identify top and bottom performing stores across various metrics (sales, area, customer count).
-   Relationship Exploration: Investigating correlations between different store attributes, particularly how store area and customer count relate to store sales.
-   Data Visualization: Creating insightful charts (histograms, scatter plots, correlation heatmaps, bar charts) to effectively communicate findings.

---

## ✨ Key Findings

The analysis yielded several insightful results:

-   Average Performance: The average store sales were approximately $59,351, with an average store area of 1,485 sq. yards and an average daily customer count of 786.
-   Top Performer: Store 650 consistently achieved the highest sales at $116,320, serving as a potential benchmark for best practices.
-   Sales Drivers:
    -   A strong positive correlation was observed between `Daily_customer_count` and `Store_sales`, indicating that higher customer traffic directly leads to increased sales.
    -   A moderate positive correlation was found between `Store_area` and `Store_sales`, suggesting that larger stores tend to have higher sales, though not always directly proportional.
    -   `Item_Available` also showed a positive correlation (approx. 0.5) with sales, implying that a broader product variety can contribute to increased revenue.
-   Strategic Implications: Optimizing customer traffic is the most impactful immediate strategy for sales enhancement, followed by considerations of store size and merchandise diversity.

---

## 📈 Visualizations

The project generates several visualizations to illustrate the findings, including:

-   Distribution of Store Sales (Histogram)
-   Store Area vs. Sales (Scatter Plot)
-   Daily Customer Count vs. Sales (Scatter Plot)
-   Correlation Heatmap of Store Data
-   Bar chart showing Top 10 Stores by Sales

---

---

## 📧 Contact

For any questions or collaborations, feel free to reach out:

-   Onoriose Baro Monarch
-   LinkedIn: [https://ng.linkedin.com/in/baro-onoriose-ba7184299](https://ng.linkedin.com/in/baro-onoriose-ba7184299)
-   GitHub: [https://github.com/Onoriosebaro](https://github.com/Onoriosebaro)
-   Email: [Baroonoriose@gmail.com](mailto:baroonoriose@gmail.com)

---

## 📄 License

This project is open-source and available under the MIT License.
