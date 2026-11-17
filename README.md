# power-bi-pr1
📊 Power BI Sales Analysis Dashboard

«An interactive sales analytics dashboard built with Microsoft Power BI and Power Query»

---

🌟 Project Overview

This project presents an interactive Sales Data Analysis Dashboard developed using Microsoft Power BI.

The purpose of this project is to transform raw sales data into meaningful and interactive business insights through:

- 📈 Sales analysis
- 💰 Profit analysis
- 📦 Quantity analysis
- 🏷️ Category and Sub-Category analysis
- 🌎 Regional analysis
- 🔎 Interactive filtering
- 🔄 Cross-filtering between visuals
- 📋 Detailed order-level analysis

The project demonstrates the complete workflow from data loading and transformation to dashboard development, visualization, filtering, formatting, and interactive analysis.

---

🎯 Project Objectives

The main objectives of this project are:

1. Import the sales dataset into Power BI.
2. Clean and transform the data using Power Query.
3. Ensure appropriate data types for different columns.
4. Prepare the dataset for analysis.
5. Create meaningful KPI cards.
6. Analyze sales performance by Sub-Category.
7. Analyze profit performance by Region.
8. Create interactive Region and Category slicers.
9. Apply visual-level filtering.
10. Implement cross-filtering between visuals.
11. Create a detailed Order Details report page.
12. Apply a professional Power BI theme.
13. Build a clean, interactive and user-friendly dashboard.

---

🛠️ Tools & Technologies

Tool / Technology| Purpose
🟨 Microsoft Power BI| Dashboard development and visualization
🔄 Power Query| Data cleaning and transformation
📊 DAX / Power BI calculations| Data analysis and KPIs
📁 CSV / Dataset| Source sales data
🎨 Power BI Theme| Dashboard styling
🐙 GitHub| Project version control and submission
🎥 OBS Studio| Project presentation recording

---

📂 Project Structure

PowerBI-Sales-Analysis/
│
├── 📊 dashboard_pr1.pbix
│
├── 📁 Dataset/
│   └── sales_dataset.csv
│
├── 📁 Theme/
│   └── theme.json
│
├── 📁 Screenshots/
│   ├── dashboard_page1.png
│   ├── order_details_page2.png
│   ├── power_query.png
│   ├── kpi_cards.png
│   ├── sales_by_subcategory.png
│   ├── profit_by_region.png
│   ├── slicers.png
│   ├── visual_filter.png
│   └── cross_filtering.png
│
└── 📄 README.md

«Note: Replace the filenames above with your actual filenames if they are different.»

---

🔄 Data Loading & Transformation

1. Data Loading

The sales dataset was imported into Microsoft Power BI using the Get Data functionality.

The imported dataset contains information required for sales analysis, including fields related to:

- Orders
- Customers
- Products
- Categories
- Sub-Categories
- Regions
- Sales
- Quantity
- Discount
- Profit
- Order Dates

---

2. Power Query Transformation

After importing the dataset, the data was processed using Power Query Editor before creating the dashboard.

The transformation stage was used to prepare the raw data for accurate analysis and visualization.

🔧 Transformation Workflow

The Power Query workflow includes:

1. 📥 Importing the dataset
2. 🔍 Inspecting the available columns
3. 🧹 Cleaning the imported data
4. 🔢 Checking numerical columns
5. 📅 Correcting date-related data types
6. 🔤 Checking text fields
7. 🔢 Checking numerical data types
8. 🧮 Preparing fields for analysis
9. ✅ Applying the transformations to the Power BI model

📅 Data Type Preparation

Special attention was given to appropriate data types.

For example:

Column Type| Appropriate Data Type
Order Date| Date
Quantity| Whole Number
Sales| Decimal Number
Discount| Decimal Number
Profit| Decimal Number
Customer / Product| Text

Correct data types ensure that Power BI can correctly perform calculations, filtering and visualization.

---

🔍 Power Query Screenshot

"Power Query Transformation" (Screenshots/power_query.png)

---

📊 Dashboard Design

The project contains 2 report pages with a consistent layout and professional visual design.

---

📄 Page 1 — Sales Dashboard

The first page provides a high-level overview of the sales performance.

📌 KPI Cards

The dashboard contains 4 KPI cards:

💰 Total Sales

Displays the overall sales generated from the dataset.

📈 Total Profit

Displays the total profit generated.

📦 Total Quantity

Displays the total quantity of products sold.

🏷️ Average Discount

Displays the average discount applied to the orders.

These KPIs provide a quick summary of the overall business performance.

---

📊 Sales by Sub-Category

The dashboard contains a bar chart showing:

«Sum of Sales by Sub-Category»

This visualization allows users to compare sales performance between different product sub-categories.

A Top 5 filter based on Sales was applied to focus the visualization on the highest-performing sub-categories.

"Sales by Sub-Category" (Screenshots/sales_by_subcategory.png)

---

🌎 Profit by Region

The dashboard also contains a visualization showing:

«Profit by Region»

This allows users to compare profitability across different geographical regions.

"Profit by Region" (Screenshots/profit_by_region.png)

---

🎛️ Interactive Slicers

Two slicers were implemented:

🌎 Region

The Region slicer allows users to filter the dashboard according to a selected region.

🏷️ Category

The Category slicer allows users to filter the dashboard according to a selected product category.

These slicers make the report interactive and allow users to explore specific parts of the dataset.

"Dashboard Slicers" (Screenshots/slicers.png)

---

🔎 Visual-Level Filtering

A visual-level filter was configured for the Sales by Sub-Category chart.

The chart was configured to display the:

«Top 5 Sub-Categories by Sales»

This makes the visualization more focused and useful for identifying the strongest-performing sub-categories.

"Visual Filter" (Screenshots/visual_filter.png)

---

🔄 Cross-Filtering & Visual Interactions

Cross-filtering was configured between multiple visual pairs.

When a user selects a data point in one visualization, related visualizations respond to that selection.

For example:

«Selecting a Sub-Category can filter the Profit by Region visualization.»

This allows users to perform interactive analysis and understand relationships between different dimensions of the sales data.

"Cross Filtering" (Screenshots/cross_filtering.png)

---

📄 Page 2 — Order Details

The second report page is called:

«ORDER DETAILS»

This page provides detailed order-level information.

The table contains fields such as:

- Order ID
- Order Date
- Customer Name
- Product
- Category
- Sub-Category
- Region
- Sales
- Quantity
- Discount
- Profit

This page allows users to move from a summarized dashboard view to detailed transaction-level information.

"Order Details" (Screenshots/order_details_page2.png)

---

🎨 Dashboard Formatting & Design

Several formatting and design techniques were applied to improve the appearance and usability of the report.

Design elements include:

- 📐 16:9 report page layout
- 🎨 Light dashboard background
- 📏 Gridlines
- 🧲 Snap-to-grid alignment
- 📊 Consistent visual positioning
- 🎨 Built-in Power BI theme
- 🔤 Clear visual titles
- 📦 Organized KPI layout
- 🖱️ Interactive slicers
- 🔄 Cross-filtering

The goal was to create a dashboard that is both visually attractive and easy to navigate.

---

🎨 Theme

A built-in professional Power BI theme was applied to maintain a consistent visual appearance throughout the report.

The theme was applied across the report pages and visualizations.

"Dashboard Theme" (Screenshots/dashboard_page1.png)

---

📸 Dashboard Screenshots

🖥️ Main Dashboard

"Main Dashboard" (Screenshots/dashboard_page1.png)

---

📋 Order Details

"Order Details" (Screenshots/order_details_page2.png)

---

🔄 Power Query

"Power Query" (Screenshots/power_query.png)

---

📈 Key Dashboard Features

Feature| Status
📊 KPI Cards| ✅ Completed
📈 Sales by Sub-Category| ✅ Completed
🌎 Profit by Region| ✅ Completed
🌎 Region Slicer| ✅ Completed
🏷️ Category Slicer| ✅ Completed
🔎 Top 5 Visual Filter| ✅ Completed
🔄 Cross-Filtering| ✅ Completed
🎨 Professional Theme| ✅ Completed
📄 Order Details Page| ✅ Completed
🔄 Power Query Transformation| ✅ Completed
📐 Dashboard Formatting| ✅ Completed

---

💡 Business Insights

The dashboard can be used to answer questions such as:

Sales Performance

- Which sub-categories generate the highest sales?
- Which products contribute most to overall sales?
- How does sales performance vary across categories?

Profitability

- Which regions generate the highest profit?
- Which areas may require further investigation?
- How does profitability compare across different regions?

Product Analysis

- Which sub-categories are strongest performers?
- How does quantity sold relate to sales performance?
- How do discounts relate to profitability?

Interactive Analysis

- What happens to sales when a specific region is selected?
- What happens when a specific category is selected?
- How does selecting a sub-category affect regional profit?

---

🎥 Project Presentation Video

The complete project demonstration includes:

- 👩‍💻 Face/Webcam
- 🖥️ Power BI screen
- 📥 Data loading
- 🔄 Power Query transformation
- 📊 KPI cards
- 📈 Visualizations
- 🎛️ Slicers
- 🔎 Filtering
- 🔄 Cross-filtering
- 📋 Order Details page
- 🎨 Dashboard design

▶️ Video Link

"Watch the Complete Project Presentation" (PASTE_YOUR_GOOGLE_DRIVE_VIDEO_LINK_HERE)

«Replace the placeholder above with your actual Google Drive or YouTube link.»

---

🧪 Project Workflow

Raw Sales Dataset
        ↓
   Data Import
        ↓
   Power Query
        ↓
Data Cleaning & Transformation
        ↓
   Data Model
        ↓
   KPI Creation
        ↓
 Data Visualization
        ↓
 Interactive Filters
        ↓
  Cross-Filtering
        ↓
 Dashboard Formatting
        ↓
 Final Power BI Report

---

📁 Submission Files

This repository contains the required project files:

- 📊 Power BI ".pbix" report
- 📁 Original dataset
- 🎨 Power BI theme file
- 📸 Dashboard screenshots
- 📄 Project documentation
- 🎥 Presentation video link

---

🚀 How to Open the Project

Step 1 — Download the Repository

Clone or download this repository from GitHub.

Step 2 — Open the Power BI File

Open:

dashboard_pr1.pbix

using Microsoft Power BI Desktop.

Step 3 — Check the Dataset

If Power BI asks for the dataset location, provide the location of the dataset included in the "Dataset" folder.

Step 4 — Explore the Dashboard

Navigate between:

- Sales Dashboard
- ORDER DETAILS

and interact with the slicers and visuals.

---

📌 Project Requirements Completed

The project follows the required 13-task Power BI workflow and includes:

- ✅ Data loading
- ✅ Power Query transformation
- ✅ Data preparation
- ✅ KPI cards
- ✅ Bar charts
- ✅ Slicers
- ✅ Visual-level filtering
- ✅ Cross-filtering
- ✅ Page formatting
- ✅ Order Details page
- ✅ Theme application
- ✅ Interactive dashboard
- ✅ Final report organization

---

👩‍💻 Author

Krisha Tandel

B.Tech Computer Science Engineering

AMTICS — Uka Tarsadia University

---

⭐ Project Highlights

«From raw data → transformation → analysis → visualization → interactive dashboard»

This project demonstrates how Power BI can transform raw business data into an interactive analytical solution that supports data-driven decision making.

---

📜 License

This project was created for academic/educational purposes as part of a Power BI project submission.

---

⭐ Thank You

Thank you for reviewing this project!

Built with ❤️ using Microsoft Power BI
