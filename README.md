# 🍽️ SmartBite – Online Food Delivery Database Management System

📊 **A complete company-level Microsoft Access DBMS project for analyzing and managing an online food delivery business.**  
SmartBite is a comprehensive, production-ready Microsoft Access Database Management System designed specifically for analyzing and managing every aspect of an online food delivery business.
In today’s fast-paced food delivery industry, managing huge volumes of orders, multiple restaurant partners, diverse payment methods, customer loyalty programs, cancellations, and real-time revenue insights demands a robust and automated database solution. SmartBite addresses all these needs in one place. 

📌 SmartBite is not just a practice project — it’s a complete company-level solution that demonstrates how Microsoft Access can powerfully handle real-world business requirements in the food delivery sector.

---

## 📌 Project Overview

SmartBite is a **real-world, production-ready DBMS** designed entirely in **Microsoft Access (.accdb)**.  
This system shows how an online food delivery business can manage massive order data, multiple restaurants, loyal customers, discounts, cancellations, and real-time revenue tracking — all inside one connected database.

---

## 🎯 Project Purpose

The purpose of SmartBite is to fix the typical pain points food delivery businesses face when dealing with huge amounts of monthly order data.  
Without a proper system, data remains scattered and reporting becomes manual and error-prone. SmartBite centralizes everything in one place.

- ❌ Disorganized order files scattered month-to-month  
- ❌ Manual, repetitive sales and revenue reporting  
- ❌ No clear view of loyal vs regular customer behavior  
- ❌ High data entry mistakes and inconsistent records  
- ❌ No single source of truth for payment trends and cancellation analysis

---

## ✅ Key Objectives

This project helps you learn practical skills by solving real business needs step by step.  
Below are the main goals you achieve with SmartBite.

- 📦 Build reliable **Food Items**, **Restaurants**, and **Customers** master tables  
- 📅 Manage January to April transactions, then **merge them** into a unified **AllOrders** table  
- 💰 Calculate **Gross Revenue** and **Net Revenue**, apply auto-discounts for Gold Members, and compute commissions for restaurants  
- 📊 Analyze **Top Selling Food Items**, Restaurant-wise performance, and Payment Method preferences  
- ❌ Track **Cancelled Orders**, identify trends, and monitor cancellation %  
- 📈 Visualize **Month-wise Revenue Growth**  
- 🧾 Leverage **Crosstab**, **Append**, and **Union Queries** for deep reporting  
- 🗂️ Use clean, user-friendly **Forms** for daily data entry  
- 📄 Deliver polished **Reports** for management reviews  
- 🔒 Apply **Validation Rules** to maintain error-free data

---

## 🧩 Inside SmartBite – Tables & Structure

SmartBite is organized into well-designed master tables, monthly order tables, and a final merged dataset.  
Here’s what’s inside:

- **Food Items Table:** Realistic names, types, unit prices (₹150–₹350 range)  
- **Customers Table:** Segments customers as **Gold Members** or **Regular Members**  
- **Restaurants Table:** Includes restaurant types (Dine-In, Takeaway, Cloud Kitchen, etc.)  
- **Monthly Orders Tables:** Separate tables for January, February, March, and April  
- **AllOrders Table:** Final merged dataset combining all months using **Append Queries**

---

## 🔗 Core Relationships

SmartBite maintains **clean, accurate data** by enforcing relationships and referential integrity rules.  
This ensures every order is linked properly with no orphan records.

- Every Order links to valid **Food Items**  
- Every Order links to valid **Customers**  
- Every Order links to valid **Restaurants**  
- Foreign keys maintain data consistency — **no orphan records**

---

## 🔍 Data Validation Rules

To ensure high data quality, SmartBite uses strong validation rules and restrictions.  
These checks make sure the records stay logical and clean.

- Prevent **negative quantity** entries  
- Restrict **invalid payment modes** (only Cash, Card, UPI, Wallet allowed)  
- Ensure valid **delivery status** (Delivered, Cancelled, In-Process)  
- Auto-generate **unique Order IDs** using **AutoNumber**

---

## 📊 Real-World Business Problems Solved

SmartBite is designed to answer real daily business questions that any food delivery company faces.  
These insights make decision-making faster and more reliable.

- **Sales Analysis:** What sells the most? What are the top 5 food items?  
- **Revenue Calculation:** How much gross revenue did we earn? How much did loyal customers save?  
- **Cancellations:** Which restaurants or food items have high cancellation rates?  
- **Customer Segmentation:** Do Gold Members order more than Regular? Which payment mode is preferred?  
- **Restaurant Performance:** Which restaurant needs improvement?  
- **Growth Trends:** How are month-wise sales growing?  
- **Payment Trends:** Which payment mode is safest with the least cancellations?  
- **Forms:** Generate clean Forms for management anytime — even for launching new products!
- **Reporting:** Generate clean reports for management anytime.

---

## ⚙️ Smart Access Features

This project uses many advanced Microsoft Access tools to automate reporting and maintain data quality.  
These features turn SmartBite into a **company-level solution**, not just a simple student project.

- ✅ **Crosstab Queries:** Monthly trends for top food items  
- ✅ **Group By Queries:** Segment cancellations, customer behavior  
- ✅ **Append & Union Queries:** Merge month-wise transactions smoothly  
- ✅ **Macros:** Automate report openings and quick filters  
- ✅ **Locked Tables:** Protect final data from accidental changes  
- ✅ **AutoNumber IDs:** Ensure unique tracking for each order  
- ✅ **User-Friendly Forms:** Add Orders, Customers, Restaurants; Search Orders by ID or Date

---

## 📌 What You Deliver with SmartBite

By building SmartBite, you deliver an actual business-ready database, not just an academic file.  
Your `.accdb` covers every stage of food delivery data handling.

- **Master Data:** Food Items, Restaurants, Customers  
- **Monthly Transactions:** Orders for each month  
- **Merged Data:** AllOrders final dataset  
- **Queries:** Revenue, Sales, Cancellations, Segmentation, Payment breakdown  
- **Forms:** Add new orders, customers, restaurants; search and update records  
- **Reports:** Restaurant Sales, Delivery Status, Payment Trends, Loyalty Analysis  
- **Macros:** Automate repetitive reporting  
- **Validation:** Strong rules to keep everything clean

---

## 🧮 Key Calculations

This project includes the main calculations every food delivery business needs.  
You can adjust, expand, or automate them further as you learn.

- **Gross Revenue:** Quantity × Unit Price  
- **Discount:** 10% for Gold Members  
- **Net Revenue:** Gross Revenue minus Discount  
- **Commission:** 20% of Net Revenue  
- **Cancellation %:** Cancelled Orders ÷ Total Orders × 100

---

## 💡 Business Questions Answered

SmartBite gives you ready answers to these essential business queries anytime you run your reports.

- ✅ Which food item is the bestseller this month?  
- ✅ Gold vs Regular: Who orders more?  
- ✅ Which restaurant’s performance needs improvement?  
- ✅ How is the business growing Jan–Apr?  
- ✅ Which payment method has the fewest cancellations?

---

## 🎁 Extra Realism Features

SmartBite also includes extra touches that make it more realistic and closer to how real companies work.  
These small details build trust and usability.

- 📌 Realistic pricing and restaurant categorization  
- 📌 Locked tables to avoid accidental edits  
- 📌 Auto-generated Order IDs  
- 📌 Macros for automation and time saving  
- 📌 Interactive Reports for stakeholders

---

## ✅ Final Result

SmartBite proves that **Microsoft Access** is powerful enough to manage **real food delivery data** — not just simple tables.  
You get complete sales insights, revenue tracking, customer loyalty management, cancellation trends, and automated reporting — ready to use for any company.

---

## 🖼️ Project Screenshots

Below are two sample screenshots showing the main DBMS and reports view.

## 📊 SmartBite – Online Food Delivery DBMS Preview** 
 
![SmartBite – Reports & Dashboard View](SmartBite-%20Online%20Food%20Delivery%20DBMS1.png)
![SmartBite – Main DBMS Preview](SmartBite-%20Online%20Food%20Delivery%20DBMS.png) 
---

