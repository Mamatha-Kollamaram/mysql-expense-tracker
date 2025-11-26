# 📊 Personal Expense Tracker (MySQL Project)

A beginner-friendly SQL project that demonstrates database design, sample data insertion, analytical queries, views, triggers, and stored procedures — all inside MySQL.
This project helped me learn practical MySQL and understand how real systems store & analyze data.

## 🚀 Project Overview

This is a pure MySQL project that works like a simple personal expense tracker.  
You can:  

* Store users, expense categories, payment methods, and expenses  
* Analyze spending patterns  
* Prevent invalid inputs  
* Insert new expenses using a stored procedure  
* Reuse analytics using SQL views  
No frontend — the focus is purely on learning SQL the right way.  

## 🛠️ Features & Concepts Used
### 1. Database Design

* users  
* categories  
* payment_methods  
* expenses  
* Foreign keys  
* Constraints (unique, check)  

### 2. Sample Data

Used for testing analytics like:  
* Total spending  
* Monthly breakdown  
* Category insights  

### 3. Analytical Queries

Includes:  
* Total spending  
* Highest & lowest spending category  
* Spending per category  
* Spending per payment method  
* Monthly spending trend  
* Average daily spending  

### 4. Views

Reusable views created:  
* v_total_spending_per_category  
* v_total_spending_per_payment_method  
* v_monthly_spending  
* v_daily_avg_spending  

### 5. Stored Procedure

Easy expense insertion:  
* CALL add_expense(user_id, category_id, method_id, amount, date, note);  

### 6. Trigger

Prevents future expenses from being entered:  
* trg_no_future_expense  

## 📂 Project Structure

mysql-expense-tracker/  
│  
├── schema.sql                        # Database tables  
├── sample_data.sql                   # Insert sample data  
├── views.sql                         # SQL views  
├── analytics_queries.sql             # Insight queries  
├── procedures.sql                    # Stored procedures  
├── triggers.sql                      # Triggers for validation  
└── README.md                         # Documentation  

## 📦 How to Run

Run these files in order:  
1. schema.sql  
2. sample_data.sql  
3. views.sql  
4. procedures.sql  
5. triggers.sql  
6. analytics_queries.sql  

You can run them using MySQL Workbench, XAMPP, or any SQL client.  

## 📈 Insights This Project Provides

* Total monthly spending  
* Which category consumes most money  
* Which payment method you use the most  
* Daily average spending  
* Category-wise financial behaviour  

## 🎯 What I Learned

* How to design a relational database  
* Writing JOINs, GROUP BY, aggregated queries  
* Creating views for clean analytics  
* Writing stored procedures  
* Writing triggers for data validation  
* Organizing SQL code into a clean project structure

This project is part of my journey to improve backend + database foundations.  

## 💡 Future Enhancements

(If I extend this project later)  
* Add multiple users with login  
* Add monthly budget tracking  
* Export insights to Power BI  
* Build a Java/Python frontend  
* Add charts or dashboards  

If this helped you or inspired you, feel free to ⭐ the repo! 😊  
