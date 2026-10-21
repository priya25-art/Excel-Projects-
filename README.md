# Excel-Projects-
---FreshMart is a multi‑regional retail chain operating supermarkets, hypermarkets, convenience, and express stores across India. With thousands of customers, hundreds of employees, diverse suppliers, and a wide product portfolio, FreshMart generates large volumes of transactional and operational data daily.

Currently, this data is scattered across multiple systems (customers, employees, products, suppliers, stores, and sales transactions), making it difficult to derive actionable insights. The organization faces challenges in:

📊 Customer Insights: Understanding customer demographics, membership tiers, and purchase behavior to improve loyalty programs and reduce churn.

🏬 Store Performance: Comparing sales against monthly targets across regions and store types to identify underperforming outlets.

👩‍💼 Employee Productivity: Linking employee roles (cashiers, sales, managers) to transaction volumes and store performance.

🚚 Supplier Reliability: Evaluating suppliers based on lead times, ratings, and product availability to optimize the supply chain.

🛒 Product Profitability: Analyzing margins, seasonal demand, and category performance to guide pricing and promotions.

📈 Sales Forecasting: Predicting future demand by season, region, and product category to support inventory planning.

FreshMart needs a centralized analytics solution that integrates these datasets to provide:

Dashboards for executives (sales trends, store performance, supplier ratings).

Predictive models (customer churn, demand forecasting, market basket analysis).

Operational insights (employee allocation, inventory optimization).

# 📘 FreshMart Dataset – README

## 1. Overview  
The FreshMart dataset simulates a **retail chain’s operations**, covering customers, employees, products, suppliers, stores, and sales transactions. It is designed for **data analytics, machine learning, and business intelligence projects** such as customer segmentation, sales forecasting, and supply chain optimization.

---

## 2. Dataset Components  

### 🧑 Customers (`FreshMart_Customers.xlsx`)  
- **Fields:** Customer_ID, Name, Gender, DOB, Contact, City, State, Region, Membership, Registration_Date  
- **Use Cases:**  
  - Customer segmentation (Bronze/Silver/Gold tiers)  
  - Regional demographics analysis  
  - Membership-based loyalty program insights  

---

### 👩‍💼 Employees (`FreshMart_Employees.xlsx`)  
- **Fields:** Employee_ID, Name, Gender, Department, Salary, Joining_Date, Store_ID, Employment_Status  
- **Use Cases:**  
  - Workforce distribution by department (Sales, Billing, Cashier, Inventory, HR, Store Manager)  
  - Salary analysis and HR planning  
  - Linking employees to store performance  

---

### 🍞 Products (`FreshMart_Products.xlsx`)  
- **Fields:** Product_ID, Name, Category, Subcategory, Brand, Cost_Price, Selling_Price, Supplier_ID, Season, Status  
- **Use Cases:**  
  - Profit margin analysis (Selling vs Cost price)  
  - Seasonal demand forecasting (Summer, Monsoon, Winter, Festive)  
  - Supplier performance evaluation  

---

### 🏬 Stores (`FreshMart_Stores.xlsx`)  
- **Fields:** Store_ID, Store_Name, Manager, Region, City, State, Store_Type, Opening_Date, Monthly_Target, Status  
- **Use Cases:**  
  - Regional store performance (South, North, East, West)  
  - Store type comparison (Supermarket, Hypermarket, Express, Convenience)  
  - Target vs actual sales analysis  

---

### 🚚 Suppliers (`FreshMart_Suppliers.xlsx`)  
- **Fields:** Supplier_ID, Supplier_Name, Contact_Person, Phone, Email, City, Lead_Time_Days, Rating, Status  
- **Use Cases:**  
  - Supplier reliability (Lead time, Ratings)  
  - Mapping suppliers to products  
  - Supply chain optimization  

---

### 💰 Sales Transactions (`FreshMart_Sales_Transactions.xlsx`)  
- **Fields:** Transaction_ID, Customer_ID, Product_ID, Store_ID, Employee_ID, Date, Quantity, Total_Amount, Payment_Mode  
- **Use Cases:**  
  - Sales trend analysis (daily, monthly, seasonal)  
  - Customer purchase behavior  
  - Store-level revenue performance  
  - Linking transactions to employees and suppliers  

---

## 3. Potential Analytics & ML Projects  
- **Customer Churn Prediction** – based on membership and purchase history  
- **Market Basket Analysis** – identify frequently bought product combinations  
- **Sales Forecasting** – predict demand by season, store, or region  
- **Supplier Performance Dashboard** – lead time vs ratings vs product availability  
- **Employee Productivity Analysis** – link cashier/sales staff to transaction volumes  

---

## 4. Notes  
- Some fields contain inconsistencies (e.g., membership spelled as “Gld”, “Silvr”, “GOLD”). These should be standardized during preprocessing.  
- Dates are stored in numeric formats (Excel serials) and need conversion to proper date formats.  
- The **Sales Transactions file is too large** to process in one go — consider chunking or loading into a database for efficient querying.  

---

👉 Next step: I can help you **design a Power BI dashboard** or a **Python/SQL workflow** to analyze this dataset end-to-end. Would you like me to create a **data model schema diagram** showing how Customers, Employees, Products, Stores, Suppliers, and Sales Transactions link together?
