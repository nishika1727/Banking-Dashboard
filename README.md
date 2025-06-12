# Banking Sales Dashboard (Power BI)

An interactive dashboard created in Power BI that visualizes key banking sales metrics and answers client-specific questions using dynamic filters, relationships, and clean visuals. This project demonstrates skills in data modeling, Power Query, DAX, and report design.

## 📌 Project Objective

The goal was to provide a detailed and interactive sales analysis based on a dataset containing customer, product, and promotional data. Insights such as top-selling products, profit trends, order analysis, and discount evaluations were visualized to support decision-making.

---

## 📊 Key Features

✅ Top & Bottom 5 Products by:
- Sales
- Profit
- Quantity Sold

✅ Sales Trends:
- Daily, Monthly, Quarterly, Yearly breakdown

✅ Sales vs Profit Relationship

✅ Period Comparison:
- Sales, Profit, Quantity for selected periods

✅ Discount Insights:
- Average discount by category

✅ Key KPIs:
- Total Orders
- Net Sales
- Average Discount
- Total Profit

✅ Filterable Visuals by:
- Product
- Customer ID
- Date
- Promotion Categories

✅ Sales by Cities (Map/Chart)

---

## 🧱 Data Model

The dashboard follows a **Star Schema** structure:

- 📄 **Fact Table**: Order Details (sales, quantity, date, discount, profit)
- 📄 **Dimension Tables**:
  - Customer
  - Product
  - Promotion Code

---

## 🛠️ Tools Used

- Power BI Desktop
- Power Query Editor
- DAX for calculations
- GitHub for version control and publishing

---

## 📷 Dashboard Previews

### 📌 Overview Page
![Overview](assets/screenshots/overview.png)

### 🔎 Filter Panel Example
![Filters](assets/screenshots/filters-example.png)

### 🎥 Walkthrough (Optional)
![Dashboard Demo](assets/demo.gif)

---

## 📝 How to Run

1. Clone this repo or download the `.pbix` file.
2. Open it in Power BI Desktop.
3. If necessary, replace the dataset with your own in the `dataset/` folder.

---

## 📁 Folder Structure

```plaintext
banking-sales-dashboard/
├── assets/
│   ├── screenshots/
│   └── demo.gif
├── dataset/
├── Banking Dashboard.pbix
├── README.md
└── .gitignore
