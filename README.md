# 📊 BlinkitDataAnalysis

## 🚀 Blinkit Sales & Outlet Performance Dashboard  
A comprehensive Power BI dashboard designed to analyze Blinkit’s outlet sales, product demand, and customer ratings across various regions and outlet types.

---

## 🧭 Short Description / Purpose  
This dashboard delivers insights into Blinkit's operational and retail performance by visualizing key metrics such as total sales, average sales, outlet performance, product category trends, and customer ratings. It supports data-driven decisions for expansion, marketing, and inventory optimization.

---

## 🛠️ Tech Stack  
- 📊 **Power BI Desktop** – Core platform for building and publishing the dashboard  
- 📂 **Power Query** – Used for data cleaning, transformation, and shaping  
- 🧠 **DAX (Data Analysis Expressions)** – For dynamic KPIs, calculations like average rating and outlet-based segmentation  
- 🧱 **Data Modeling** – Relationships established among outlet type, item type, rating, fat content, and tier data  
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews  

---

## 📈 Data Source  
The dataset simulates Blinkit’s retail-level data including:
- Outlet type, size, and location (Tier 1/2/3 cities)  
- Item category sales (e.g., dairy, frozen, snacks)  
- Fat content classification (Low Fat vs. Regular)  
- Customer ratings per outlet  
- Year of establishment and outlet growth trends  

---

## 🌟 Key Features / Highlights  

### • Business Problem  
Blinkit operates in a high-speed retail space with varying outlet types, city tiers, and product preferences. Understanding performance across these dimensions is critical for optimizing sales, enhancing customer satisfaction, and deciding where to open or upgrade outlets.

### • Goal of the Dashboard  
To provide stakeholders with an at-a-glance view of:
- Outlet sales performance by type, tier, and size  
- Popular item categories and their sales distribution  
- Customer feedback and item visibility  
- Year-on-year outlet establishment growth  

### • Walkthrough of Visuals  

#### 📌 **KPIs Section (Top Center)**  
- 💰 **Total Sales:** $1.20M  
- 📈 **Average Sales:** $141  
- 📦 **No. of Items Sold:** 8,523  
- ⭐ **Average Rating:** 3.9  

#### 🎛️ **Filters (Left Panel)**  
- Interactive slicers for `Outlet Location Type`, `Outlet Size`, and `Item Type`  

#### 📊 **Sales by Item Type (Bar Chart)**  
- Top-selling categories like Fruits, Snacks, Household, and Frozen foods  

#### 🍽️ **Fat Content Breakdown (Donut Chart)**  
- Sales comparison between **Low Fat** and **Regular** items  

#### 📅 **Outlet Establishment Over Time (Area Line Chart)**  
- Visualizes outlet growth and revenue trend from 2012 to 2022  

#### 🏪 **Outlet Size Sales (Donut Chart)**  
- Revenue distribution across **Small**, **Medium**, and **High** outlet sizes  

#### 🌍 **Tier-wise Sales (Horizontal Bar)**  
- Compare performance across **Tier 1**, **Tier 2**, and **Tier 3** cities  

#### 📋 **Outlet Type Table**  
- View outlet performance by format: supermarket/grocery, with columns for:
  - Total Sales  
  - Avg Sales  
  - Number of Items  
  - Avg Rating  
  - Item Visibility  

---

## 💡 Business Impact & Insights  
- 📍 **Regional Strategy:** Identify top-performing tiers and outlet types to guide expansion  
- 🧺 **Category Optimization:** Focus on high-revenue item types to boost profit margins  
- 📦 **Inventory & Fulfillment:** Track visibility and stock distribution trends per outlet type  
- ⭐ **Customer Sentiment:** Evaluate outlet quality and service via customer ratings  

---

## 📸 Dashboard Preview  

![Blinkit Dashboard Preview](https://github.com/Su-07/BlinkitDataAnalysis/blob/main/Dashboard.png)

---

## 📁 Repository Structure  
```bash
BlinkitDataAnalysis/
│
├── Dashboard.pbix                # Power BI source file
├── Dashboard.png                 # Dashboard image preview
├── README.md                     # This README file
└── Data/                         # (Optional) Folder for sample/mock datasets
