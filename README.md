# PowerQuery, Pivot Tables, DAX – Excel Data Model & Dashboard

## 📊 Project Overview

This project showcases a complete Excel-based Business Intelligence solution using:

- **Power Query** for data cleaning and transformation
- **Power Pivot** and **DAX** for building a semantic data model with custom measures and KPIs
- **Pivot Tables & Charts** for dynamic analysis
- **Professional Dashboard Design** with interactive filtering and visual storytelling

The dataset used for this project is from **Maven Analytics**, and it represents detailed sales transactions across countries, categories, and time periods. The goal is to deliver actionable insights and a clean executive dashboard for business users.

---

## 🔧 Tools & Technologies Used

- **Power Query :** Data cleansing, shaping, and loading
- **Power Pivot:** Data modeling and relationship management
- **DAX:** Custom measures and KPIs
- **Excel Pivot Tables & Pivot Charts**
- **Slicers & Visual Enhancements** for interactivity

---

## 🧹 Data Preparation (Power Query)

The dataset was first imported into Power Query, where the following transformations were applied:

- Data type adjustments (dates, numbers, text)
- Standardization of date formats
- Removal of nulls and inconsistencies
- Creating a separate **Date Dimension Table**
- Joining tables where necessary for a clean star schema

---

## 🧠 Data Model (Power Pivot)

A clean star schema was created with relationships between:

- **Fact table:** Sales Transactions
- **Dimension tables:** Products, Calendar, Stores

The data model supports dynamic time intelligence and segment-based analysis.

![Data Model Diagram](https://github.com/user-attachments/assets/7df70ef5-bccc-4689-b93f-532db0ff5d6a)

---

## 🧮 DAX Measures & KPIs

Several DAX measures were created to support business analysis:

- `Total Revenue`
- `Revenue Previous Month`
- `Total Orders`

These KPIs enable easy comparison between current and previous periods.

![Pivot Fields with Measures](https://github.com/user-attachments/assets/2aa3557f-f734-49f7-817b-f5258270d89c)

---

## 📈 Excel Dashboard

A professionally designed Excel dashboard combines several visual elements to deliver key insights:

![Dashboard](https://github.com/user-attachments/assets/078da913-0663-4ff6-b054-bf8aaf90c199)

### Dashboard Sections:

#### 1. **Monthly Revenue (Line Chart)**
Displays total monthly revenue over time, allowing for trend analysis. Peaks and troughs are clearly visible.

#### 2. **Sales by Country (Pie Chart)**
Highlights geographic distribution of sales. The United States dominates with 43% of total sales, followed by the UK and Online channels.

#### 3. **Current vs Previous Total Revenue (Bar Chart)**
Shows current month revenue vs. previous month, providing instant visual feedback on performance.

#### 4. **Orders by Category (Bar Chart)**
Breakdown of total orders by product category. "Computers" lead in volume, followed by "Cell Phones" and "Music/Movies".

#### 5. **Country Filter (Slicer)**
A slicer on the left enables quick filtering of the entire dashboard by country, enhancing interactivity and drill-down capabilities.

---

## 🎯 Business Value

This dashboard enables:
- Tracking performance over time
- Identifying high-performing categories and regions
- Monitoring growth trends and seasonality
- Providing executive-level insights for decision-making


