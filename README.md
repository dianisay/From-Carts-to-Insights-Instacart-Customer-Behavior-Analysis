# 🛒 From Carts to Insights: Instacart Customer Behavior Analysis

## 📌 Introduction
This project analyzes **Instacart’s grocery orders dataset** to explore customer purchasing behavior.  
The objective is to identify shopping patterns, such as when users place orders, how often they reorder items, and which products dominate customer carts.

---

## 📂 Dataset
The project uses five CSV files (subset of Instacart’s public dataset):

1. **instacart_orders.csv** – details of customer orders  
2. **products.csv** – product information  
3. **order_products.csv** – items included in each order  
4. **aisles.csv** – grocery aisle categories  
5. **departments.csv** – department categories  

Each dataset required preprocessing to handle **missing values, duplicates, and formatting issues**.

---

## ⚙️ Methodology
The workflow follows three key stages:

1. **Data Exploration**  
   - Initial inspection of dataset structure  
   - Validation of ranges (e.g., `order_hour_of_day`, `order_dow`)  

2. **Data Preprocessing**  
   - Ensured correct datatypes for IDs  
   - Treated missing values and duplicates  
   - Documented preprocessing choices and reasoning  

3. **Exploratory Data Analysis (EDA)**  
   - **Customer habits**: distribution of orders by weekday, time of day, and reorder intervals  
   - **Product insights**: most purchased items, reorder ratios, and top first-cart additions  
   - **Customer patterns**: order frequency and item count per order  

---

## 📊 Key Analyses
- Distribution of orders by **hour of day** and **day of week**  
- Average **days between orders**  
- Top **20 most frequently purchased products**  
- Top **20 most reordered products**  
- Ratio of reordered items per product and per customer  
- Top products most frequently added **first to the cart**  

---

## ✅ Conclusion
This project highlights skills in:  
- **Python (pandas, matplotlib, seaborn)**  
- **Data cleaning and preprocessing**  
- **Exploratory Data Analysis (EDA)** with large datasets  
- **Customer behavior insights** derived from raw transaction data  

The results demonstrate how data-driven analysis can uncover actionable insights in **e-commerce and consumer analytics**.  

---

## 💻 Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📈 Sample Visualization
_Add sample plots (e.g., distribution of orders by hour, reorder ratios, or top products)._  

---

## 🤝 Contact
Created by **[Your Name]**  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile) | [Portfolio](https://yourportfolio.com)
