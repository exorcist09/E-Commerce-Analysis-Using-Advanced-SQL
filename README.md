# ** Salescope -An E-Commerce-Analysis**  

## 📦 Project Overview

This project presents a comprehensive analysis of the **order fulfillment process** for an e-commerce business, focusing on:

- **Sales trends**
- **Product performance**
- **Customer segmentation**
- **Shipping cost optimization**
- **Payment method preferences**

Using **advanced SQL techniques** and **Python-based data visualization**, the project uncovers actionable insights to:

- 📈 **Boost sales**
- 🚚 **Streamline logistics**
- 😊 **Enhance customer satisfaction**

---

## 🔧 **Technologies Used**  
- **Database**: SQLite  
- **Query Language**: SQL  
- **Data Processing**: Pandas  
- **Visualization**: Matplotlib, Seaborn  
- **Development Environment**: Jupyter Notebook  

---

## 📂 **Dataset Overview**  
- **Source**: E-Commerce transaction records with **51,290 rows** and **16 columns**  
- **Data Transformation**: The raw dataset was **normalized into four tables** for efficient querying:
  - `Orders` – Order details, including sales, profit, and shipping costs.  
  - `Customers` – Customer demographics such as gender, login type, and device.  
  - `Products` – List of all products and their categories.  
  - `Categories` – Broader classification of product types.  

---

## 🚀 **Advanced SQL Techniques Used**  
This project incorporates **Advanced SQL Techniques** to improve query performance, simplify analysis, and generate powerful insights:  

### **1️⃣ Window Functions**  
   - Used to **rank top-selling products** and **calculate cumulative sales over time**.  
   - Helps in **understanding product demand trends dynamically**.  

### **2️⃣ Common Table Expressions (CTEs)**  
   - Simplifies **customer segmentation analysis** by organizing complex queries.  
   - Enhances readability and maintains **modular query execution**.  

### **3️⃣ Ranking Functions (RANK() OVER)**  
   - Assigns rankings to products based on total sales.  
   - Useful for **identifying best-performing items efficiently**.  

### **4️⃣ Partitioning & Indexing for Performance Optimization**  
   - Used for **query optimization**, especially for large datasets.  
   - Ensures **faster retrieval of insights** from orders and customer data.  

---

# 📊 Business Insights & Recommendations

## 🔹 Key Highlights

- **Total Sales:** $7.8M | **Profit:** $3.6M  
- **Peak Months:** May & November  
- **Top Products:** T-Shirts, Watches, Running Shoes  
- **Best Categories:** Fashion & Footwear  
- **High-Spenders:** Primarily male customers  
- **Preferred Payment:** Credit Cards (74%)

---

## 🔍 Insights

### 🛍️ Sales & Products
- Peak seasonal demand in **May** and **November**
- Bundle slow-moving items with bestsellers to boost overall sales

### 👥 Customer Behavior
- Male users dominate high-spending segment  
- Targeted offers + VIP loyalty program = better retention

### 🚚 Fulfillment & Logistics
- High-priority shipping = higher costs  
- Promote **bulk orders** and **standard delivery** to optimize logistics

### 💳 Payments
- Low e-wallet usage → incentivize with **cashbacks**
- Introduce **Buy Now, Pay Later (BNPL)** to reduce cart abandonment

---

## 💡 Business Recommendations

- ⚙️ **Automate** warehouse ops (Current avg. time: 5.25 days)
- 🎯 Launch **targeted seasonal promotions**
- 🏅 Implement **loyalty programs** & personalized offers
- 📦 Offer **free shipping for bulk**; optimize courier partnerships
- 💸 Boost e-wallet adoption & add **BNPL options**

---


##  **Project Files & Repository Structure**  
 `Ecommerce_SQL_DATAProject.db` – SQLite database file  
 `ecommerce_schema.sql` – Collection of SQL scripts used in analysis  
 `E_Commerce_Analysis_using_Advanced_SQL.ipynb` – Jupyter Notebook for SQL execution & visualization  
 `E_Commerce_Analysis_using_Advanced_SQL.html` – Summary of key insights & recommendations  

---

## 🛠 **How to Run the Project**  
1️⃣ **Clone the repository**  
```sh
git clone https://github.com/yourusername/E-Commerce-Analysis-Using-Advanced-SQL.git
cd ecommerce-sql-analysis
```
2️⃣ **Load the database (`Ecommerce_SQL_DATAProject.db`) into SQLite or DB Browser for SQLite.**  
3️⃣ **Execute SQL queries from `ecommerce_schema.sql` to explore insights.**  
4️⃣ **Run `E_Commerce_Analysis_using_Advanced_SQL.ipynb` in Jupyter Notebook to visualize trends using Python.**  


