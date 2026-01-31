Food Delivery Data Analysis Project

 Project Description
This project is about analyzing food delivery data by combining multiple data sources.  
The data comes in different formats such as CSV, JSON, and SQL.  
All the data is merged into one final dataset and analyzed to get useful insights.

This project was done as part of a *Hackathon / Data Analytics practice*.

 Data Files Used

 1. orders.csv
This file contains order details.
- order_id
- user_id
- restaurant_id
- order_amount
- order_date



 2. users.json
This file contains user information.
- user_id
- user_name
- city
- membership (Gold / Regular)

3. restaurants.sql
This SQL file contains restaurant details.
- restaurant_id
- restaurant_name
- city
- cuisine

---

 🔗 Data Merging Logic
- Orders data is used as the main table.
- Data is merged using *LEFT JOIN* to keep all orders.
- Join keys used:
- orders.user_id → users.user_id
- orders.restaurant_id → restaurants.restaurant_id

 Final Output
 final_food_delivery_dataset.csv

This file contains:
- Order details
- User information
- Restaurant information  

All analysis is done using this final dataset.
 Analysis Performed
- Total orders per restaurant
- Total revenue
- Average Order Value (AOV)
- Restaurant performance comparison
- Membership impact analysis

*AOV Formula:*
Sample Question Answered
*Which restaurant has the highest average order value but less than 20 orders?*

*Answer:* Ruchi Foods Chinese

 Tools Used
- Python
- Pandas
- SQLite
- Jupyter Notebook

## ▶ How to Run
1. Keep all files in one folder
2. Open the notebook file (Sripada_Hackathon.ipynb)
3. Run cells step by step  
OR  
4. Run the Python script if available


## 🎯 Learning Outcome
- Learned how to handle CSV, JSON, and SQL files
- Understood real-world data joining
- Improved data analysis skills
- Gained confidence in Python and Pandas
