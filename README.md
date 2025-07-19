# 🧾 US Regional Sales and Profit Analysis Dashboard

This project provides an interactive Power BI dashboard analyzing sales, profit, cost, and regional performance across various US states. It offers insights into order trends, sales channels, and profitability based on geographic and temporal dimensions.

---

## 📊 Dashboard Overview

The dashboard helps users:
- Analyze **sales and profit performance** across different US states and regions
- Monitor **channel-wise performance** (Online, Retail, etc.)
- Track **monthly order trends**
- Evaluate **profit margins, revenue, and cost distribution**
- Understand **customer behavior** and **product-level insights**

---

## 🗂️ Dataset Description

The dataset contains the following columns:

| Column Name         | Description                                          |
|---------------------|------------------------------------------------------|
| `order_number`      | Unique ID for each order                             |
| `order_date`        | Date when the order was placed                       |
| `customer_name`     | Name of the customer                                 |
| `channel`           | Sales channel (e.g., Online, Retail, etc.)           |
| `product_name`      | Name of the product                                  |
| `quantity`          | Quantity of product sold                             |
| `unit_price`        | Price per unit of the product                        |
| `revenue`           | Total revenue from the order                         |
| `cost`              | Total cost associated with the order                 |
| `state`             | US state code                                        |
| `state_name`        | Full state name                                      |
| `us_region`         | US region (e.g., Northeast, Midwest, etc.)           |
| `lat` / `lon`       | Latitude and longitude for mapping                   |
| `budget`            | Target/allocated budget for the state or region      |
| `total_cost`        | Total cost across all orders                         |
| `profit`            | Revenue - Cost                                       |
| `profit_margin_pct` | Profit as a percentage of revenue                    |
| `order_month_name`  | Month name of the order                              |
| `order_month_num`   | Numeric month (1–12)                                 |
| `order_month`       | YYYY-MM format                                       |

---

## ⚙️ Tools & Technologies

- **Power BI** – For data modeling and dashboard creation
- **Excel / CSV** – For data cleaning and input
- **DAX (Data Analysis Expressions)** – For creating calculated measures and KPIs
- **Geo Maps** – For regional and state-level visualization

---

## 📌 Key Features

- 📍 **State-wise & Region-wise Sales Heatmaps**
- 📈 **Monthly Revenue and Profit Trend Charts**
- 🛒 **Channel-wise Sales Breakdown**
- 💰 **Profit Margin and Cost Analysis**
- 🧑‍💼 **Top Customers and Products by Revenue**
- ✅ **Budget vs Actual Comparison**

---

## 📷 Dashboard Screenshots

### 🖼️ Overview Screenshot
![Dashboard Screenshot 1](https://github.com/rushikesh092002/US-Regional-Sales-and-Profit-Analysis-Dashboard/blob/d5814bf611a6567b6e13b2ae894b7cafab34064c/Screenshot%202025-07-10%20125755.png?raw=true)

### 🖼️ Channel-wise Sales
![Dashboard Screenshot 2](https://github.com/rushikesh092002/US-Regional-Sales-and-Profit-Analysis-Dashboard/blob/d5814bf611a6567b6e13b2ae894b7cafab34064c/Screenshot%202025-07-10%20125808.png?raw=true)

### 🖼️ Regional Revenue Insights
![Dashboard Screenshot 3](https://github.com/rushikesh092002/US-Regional-Sales-and-Profit-Analysis-Dashboard/blob/d5814bf611a6567b6e13b2ae894b7cafab34064c/Screenshot%202025-07-10%20125817.png?raw=true)




## 🚀 How to Use

1. Download or clone this repository.
2. Open the Power BI file (`.pbix`) in Power BI Desktop.
3. Connect the dataset if needed and refresh the model.
4. Interact with filters, slicers, and visuals to explore the data.


## 📈 Future Enhancements

- Add **forecasting features** using Power BI's built-in tools
- Integrate **real-time data sources**
- Include **drill-down capabilities** by product category or customer segment
- Add **mobile-optimized layout**

---

## 👨‍💻 Author

**Rushikesh Gaikhe**  
📧 Email: rushikeshgaikhe09@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rushikeshgaikhe/)  
🐙 [GitHub](https://github.com/RushikeshGaikhe)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
