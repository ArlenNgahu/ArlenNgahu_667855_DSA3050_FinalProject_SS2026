# Advanced Power BI Analytical Solution

## 1. Student Information
- Name: Arlen Ngahu 
- Admission Number: 667855 
- Course Code: DSA 3050A  


---

## 2. Project Overview

In this project, I developed an advanced Power BI analytical solution within the E-commerce domain. I focused on analyzing sales performance, customer behavior, and product trends to generate meaningful business insights.

I approached this project as a real-world business intelligence scenario, where I transformed raw transactional data into a structured data model and interactive dashboard. The final solution enables users to explore performance trends, identify key revenue drivers, and make informed decisions.

---

## 3. Problem Statement

The objective of this project was to analyze E-commerce data to answer key business questions, including:

- Which products and categories contribute the most to total revenue?  
- How does revenue vary across different time periods?  
- Who are the most valuable customers?  
- What patterns exist in customer purchasing behavior?  

The goal was to generate actionable insights that can improve business performance, optimize product strategies, and support data-driven decision-making.

---

## 4. Dataset Description

I used an open-source E-commerce dataset obtained from Kaggle. The dataset consists of multiple related tables representing different aspects of an online retail system.

The key tables include:

- **Orders**: Contains high-level transaction details such as Order ID, User ID, Order Date, and Order Status  
- **Order Items**: Contains detailed product-level transaction data, including Product ID, Quantity, and Price  
- **Products**: Provides product details such as Product Name and Category  
- **Users**: Contains customer-related information  
- **Reviews** (optional): Includes product ratings and feedback  

The dataset is suitable for advanced analysis because it contains both transactional and descriptive data, supports relational modeling, and includes time-based fields.

---

## 5. Tools Used

- **Power BI** – Data modeling, DAX calculations, and dashboard creation  
- **Power Query** – Data cleaning and transformation  
- **GitHub** – Version control and project documentation  

---

## 6. Steps Followed

### Data Acquisition
I imported multiple tables into Power BI and explored their structure and relationships.

### Data Cleaning and Transformation
I performed several data preparation steps, including:
- Removing unnecessary columns  
- Handling missing values  
- Correcting data types  
- Removing duplicates  
- Creating a Revenue column (Price × Quantity)  
- Extracting date components such as Year and Month  
- Standardizing categorical values  

### Data Modeling
I structured the data using a star schema, with:
- A central fact table (Order Items)  
- Dimension tables (Products, Users, Date)  

I created a Date table and established relationships to support time intelligence analysis.

### DAX Calculations
I created measures to calculate revenue, growth, rankings, and cumulative performance.

### Dashboard Development
I designed a multi-page dashboard to present insights in a structured and interactive format.

---

## 7. Dashboard Features

The dashboard includes the following features:

- Interactive slicers for filtering data by date, category, and location  
- Drill-down capabilities for detailed analysis (Category → Product)  
- Cross-filtering between visuals  
- Time-based analysis using a Date table  
- Multiple pages for different analytical perspectives  
- Advanced visuals such as decomposition trees, treemaps, and combo charts  

---

## 8. Key DAX Measures

The following DAX measures were created to support analysis:

- **Total Revenue** = SUM of Revenue  
- **Total Orders** = DISTINCTCOUNT of Order ID  
- **Total Quantity** = SUM of Quantity  
- **Distinct Customers** = DISTINCTCOUNT of User ID  
- **Running Revenue** = Cumulative revenue over time  
- **Growth Percentage** = Change in revenue across periods  
- **Product Ranking** = Ranking products based on revenue  
- **Revenue Contribution** = Proportion of total revenue  

These measures enabled deeper insights into performance and trends.

---

## 9. Key Insights

From my analysis, I identified several important insights:

- Revenue is highly concentrated among a few products, including **Willow Result, Astra Pull, and Willow Special**  
- **Electronics** is the dominant category, outperforming others by approximately **2 million in revenue**  
- **Groceries** is the lowest-performing category  
- **Low-value transactions account for 85.16%**, while **high-value transactions account for 14.84%**  
- Revenue peaks in **July (1,136,289.63)** and is lowest in **December (566,118.90)**  
- Customer behavior is dominated by frequent low-value purchases  

These insights highlight key performance drivers and areas for improvement.

---

## 10. Challenges Encountered

During this project, I encountered several challenges:

- Incorrect Date table relationships, which caused issues in time-based analysis  
- DAX measures (such as Running Revenue) returning incorrect results  
- Handling missing and inconsistent data  
- Ensuring proper data modeling using a star schema  
- Fixing visualization issues such as flat line charts  

I resolved these challenges through debugging, restructuring the data model, and validating calculations.

---

## 11. Conclusion

This project demonstrates my ability to clean, transform, model, and analyze data using Power BI.

The final dashboard provides meaningful insights into sales performance, customer behavior, and product trends. It supports data-driven decision-making and highlights opportunities for improving business performance.

Overall, this project reflects my understanding of advanced Power BI concepts, including data modeling, DAX, and interactive dashboard design.