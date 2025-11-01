**🍕 Pizza Place Sales Analysis Dashboard**
**📊 Project Overview**

This Power BI project analyzes sales performance for a pizza store using interactive visuals and KPIs.
It helps identify sales trends, best-selling pizzas, and category performance to make data-driven decisions.

**🚀 Key Insights**

**Total Sales**: ₹817.86K

**Total Orders**: 21K

**Average Pizzas per Order**: 2.28

**Total Pizzas Sold**: 50K

📈 The dashboard provides insights into:

**Monthly Sales Trends**

**Orders by Pizza Size and Category**

**Sales by Day of Week**

**Top 5 & Bottom 5 Best-Selling Pizzas**

**🧠 Features**

Interactive **filters** (by Name, Size, and Category)

Dynamic **KPIs** and **visuals** for quick decision-making

**Category-wise** and **size-wise** comparisons

**Pie charts, bar charts, and line graphs** for better visualization

**🗂️ Dataset Details**

The project uses four datasets:

File Name                	Description
orders.csv	            Contains details about each customer order
order_details.csv	      Links orders with specific pizzas ordered
pizza.csv	              Includes pizza ID, name, size, and type
pizza_types.csv	        Provides information about pizza categories and ingredients


**🛠️ Tools & Technologies**

**1 Power BI Desktop**

**2 Microsoft Excel / CSV** for data source

**3 DAX** for KPI calculations

**4 Data Cleaning & Model Relationships**

**📸 Dashboard Preview**

**🧾 KPIs Used**

**1Total Sales** = SUM(order_details.total_price)

**2Total Orders** = COUNT(orders.order_id)

**3Avg Pizzas per Order** = [Total Pizzas Sold] / [Total Orders]

**4Total Pizzas Sold** = SUM(order_details.quantity)

**🧩 How to Use**

1 Download the repository.

2 Open Pizza.pbix in Power BI Desktop.

3 Load the CSV files into the data model if required.

4 Explore visuals using slicers and filters.

**🏁 Project Goal**

To provide a **data-driven business overview** of pizza sales and help identify areas for growth.


**👩‍💻 Author**

**Akshada Mahadik**
📧 [akshadamahadik08@gmail.com]
🌐 [https://www.linkedin.com/in/akshada-mahadik-84482338a/]
