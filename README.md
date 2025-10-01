# 📊 Power BI Final Project – Amazon Products Dashboard  

This project is a **Power BI dashboard** built for analyzing Amazon product dataset.  
It includes data cleaning, transformation, and visualization of key business metrics.  

---

## 🚀 Project Workflow  

1. **Data Loading**  
   - Loaded dataset (`phone_search_clean.csv`) into Power BI.  

2. **Data Cleaning (Power Query)**  
   - Checked and corrected data types.  
   - Handled null values.  
   - Converted text fields (like "More Buying Choices") into numeric values.  
   - Removed unnecessary columns.  

3. **DAX Measures**  
   - Average Product Price  
   - Average Star Rating  
   - Total Sales Volume  
   - Sales per Product  
   - Number of Offers  
   - Count of Best Sellers  
   - Count of Amazon Choice Products  
   - Difference between Minimum Offer Price and Original Price  
   - % of Climate Friendly Products  

---

## 📊 Dashboard Visuals  

- **KPI Cards** → Total Sales, Average Price, Average Rating, Sales per Product  
- **Bar Charts** → Avg Price, Avg Rating, Sales Volume by Product  
- **Pie Charts** → Amazon Choice %, Best Seller %, Climate Friendly %  
- **Table** → Product-level details (Price, Rating, Sales, Offers, Amazon Choice, Best Seller)  

---

## 🔎 Key Insights  

- Total Sales: **156K units**  
- Average Price: **172.39**  
- Average Rating: **4.09 stars**  
- Sales per Product: **496.67 units**  
- Very few products are marked as **Amazon Choice** or **Best Seller**  
- Less than 1% are **Climate Friendly**  

---

## 📷 Dashboard Preview  


<img width="1263" height="712" alt="image" src="https://github.com/user-attachments/assets/c213dec5-dcde-4cd2-9abb-99a22a05efce" />



![Dashboard Screenshot](Amazon Products Performance Dashboard.png)  

---

## 🛠️ Tools Used  
- **Power BI** (Data Modeling & Visualization)  
- **Power Query** (ETL & Data Cleaning)  
- **DAX** (Measures & Calculations)  

---

## 📂 Repository Structure  

PowerBI-Amazon-Dashboard/
│-- Amazon_Products_Dashboard.pbix
│-- phone_search_clean.csv
│-- README.md
│-- images/
└── dashboard.png

yaml
Copy code
