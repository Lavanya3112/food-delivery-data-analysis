# Food Delivery Data Analysis

This repository contains an end-to-end data analysis project completed as part of an online technical hackathon.  
The project focuses on combining data from multiple sources and extracting meaningful business insights using Python and SQL.

---

## 📁 Dataset Description

The analysis is based on three different datasets provided in different formats:

- **orders.csv**  
  Contains transactional order-level data such as order ID, user ID, restaurant ID, order date, and total amount.

- **users.json**  
  Contains user-related information including user ID, name, city, and membership type (Gold / Regular).

- **restaurants.sql**  
  SQL script containing restaurant master data such as restaurant name, cuisine type, and ratings.

After merging all datasets, a final consolidated dataset is created:
- **final_food_delivery_dataset.csv**

This final dataset is used as the single source of truth for all analyses.

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas & NumPy** – data cleaning, merging, aggregation
- **SQLite (SQL)** – querying structured data
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook** – analysis workflow

---

## 🔄 Data Processing Workflow

1. Loaded CSV and JSON files using Pandas
2. Executed SQL script using SQLite to create restaurant tables
3. Merged datasets using left joins to retain all order records
4. Stored the final merged dataset for analysis
5. Performed exploratory analysis using both Pandas and SQL
6. Visualized trends using Matplotlib and Seaborn

---

## 📊 Key Analyses Performed

- Revenue comparison between Gold and Regular members
- City-wise and cuisine-wise revenue analysis
- Average order value calculations
- Identification of high-performing cuisines and restaurants
- Membership impact on order behavior
- Quarterly revenue trend analysis
- High-rating restaurant order analysis

---

## 📈 Visualizations

The project includes multiple visualizations such as:
- Revenue by membership type
- City-wise revenue distribution
- Cuisine-wise performance
- Quarterly revenue trends

These visualizations help in understanding business patterns and seasonality.

---

## 📂 Repository Structure

food-delivery-data-analysis/
│
│ ├── orders.csv
│ ├── users.json
│ ├── restaurants.sql
│ └── final_food_delivery_dataset.csv


---

## ✅ Conclusion

This project demonstrates the ability to work with real-world data formats, perform data integration, write analytical SQL queries, and derive insights using Python-based data analysis and visualization libraries.

The analysis highlights how membership type, city, cuisine, and ratings influence revenue and ordering behavior.

---

