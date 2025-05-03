# 📊 **Business-Insights-360**

### 🔗 [**Dashboard Link**](https://bit.ly/4gkfp8y)  
### 🎥 [**Dashboard Video Walkthrough**](https://1drv.ms/v/c/2449c1e3aabe59cb/EQc6ZWsh96FDv5eOYCwRFbUBmmIvauCOdL6P35bboa-Eow)

---

## 🧩 **Problem Overview**

This project, developed as part of the **Power BI course at Codebasics**, aims to build a robust **business intelligence system** for **AtliQ**, a rapidly growing global company.

- **AtliQ** relied on **Excel** for data analytics, resulting in **time-consuming**, **error-prone**, and **inefficient** reports.
- The company faced **growing data complexity** with operations expanding across multiple countries.
- There was a lack of a **scalable system** and **real-time visibility** into business performance.
- **Excel** slowed down analytics, causing delays and **hindering decision-making**.
- Insights were lacking in **depth**, **consistency**, and **speed**, with the **Latin American market** experiencing **financial losses** due to delayed decisions.
- **Strategic planning** was hindered by **poor data visibility**, prompting the transition to **Power BI** for **dynamic**, **real-time**, and **actionable insights**.

![Dashboard Preview](https://github.com/user-attachments/assets/3d3dfc1d-d10a-441e-a0a7-bb795d79051f)


## 🎯 **Project Objectives**

The project aimed to overhaul AtliQ’s reporting and analytics process by leveraging **Power BI**.

- Replace **Excel-based analysis** with modern **BI dashboards**.  
- Create an **interactive** and **department-wise view** of **key metrics**.  
- Provide **real-time insights** to **management** and **stakeholders**.  
- Support **faster**, **data-driven decisions** across business functions.  
- Improve **operational efficiency** and **minimize reporting delays**.

---

## 📊 **Dataset**

Below is a breakdown of the datasets used for this project:

| **Source Type**   | **Table Name**                 | **Description**                                         |
|-------------------|---------------------------------|---------------------------------------------------------|
| **MySQL (GDB041)**| **Fact_Forecast_Monthly**      | Forecasted demand for products by month                |
| **MySQL (GDB041)**| **Fact_Sales_Monthly**         | Actual sales data by month                             |
| **MySQL (GDB056)**| **Fact_Manufacturing_Cost**    | Monthly manufacturing cost per product                 |
| **MySQL (GDB056)**| **Fact_Freight_Cost**          | Freight or shipping cost details                       |
| **MySQL (GDB056)**| **Fact_Gross_Price**           | Gross price assigned to products                       |
| **MySQL (GDB056)**| **Fact_Pre_Invoice_Deduction** | Discounts or deductions before invoicing               |
| **MySQL (GDB056)**| **Fact_Post_Invoice_Deduction**| Discounts or deductions after invoicing                |
| **MySQL (GDB041)**| **Dim_Customer**               | Customer master data                                   |
| **MySQL (GDB041)**| **Dim_Product**                | Product master data                                    |
| **MySQL (GDB041)**| **Dim_Market**                 | Market and region mapping                              |
| **Excel**         | **Target**                     | Sales targets for comparison                           |
| **Excel**         | **Market_Share**               | Competitor-wise market share data                      |
| **Excel**         | **Operational_Expenses**       | Operating expenses for each region                     |

---

## 🔗 **Data Model Diagram**

The data model integrates multiple fact and dimension tables to support comprehensive business analysis.

![Data model for BI 360 Project](https://github.com/user-attachments/assets/e646449b-4bf4-4a20-a3df-4bb5652b39fa)

---

## 🌟 **Key Business Insights & Functionalities**

1. **Home Page**  
   - The **Home Page** serves as the introductory screen, providing users with the project title and an easy-to-navigate menu for a smooth user experience.

   ![Buisness Insight 360 Dahboard_page-0001](https://github.com/user-attachments/assets/7a2f5ab4-769d-4a28-a995-03637b195093)

---

2. **Finance View**  
   - Provides a detailed **Profit & Loss (P&L)** statement for customers, products, and regions.  
   - Offers in-depth analysis of financial performance, including revenue, expenses, and profitability.

   ![Image](https://github.com/user-attachments/assets/0cbfa7fd-c1cd-404c-a391-ef95e3e0f067)

---

3. **Sales View**  
   - Delivers insights based on **Net Sales**, **Gross Margin**, and **Profitability**.  
   - Includes a **Growth Matrix** to assess sales performance and profitability across different customers, products, and regions.

   ![Image](https://github.com/user-attachments/assets/66bcd1a1-9c17-43c3-ab4b-dc6b6f6475d7)

---

4. **Marketing View**  
   - Evaluates product-level performance with metrics like **Net Sales** and **Gross Margin**.  
   - Visualizes product profitability and growth potential to assist in smarter marketing prioritization.

   ![Image](https://github.com/user-attachments/assets/08877d77-9aa8-4d32-8c14-1e26c143b5a4)

   ![Image](https://github.com/user-attachments/assets/a26de978-5c83-4e4d-8a45-2ba09972b9b8)

---

5. **Supply Chain View**  
   - Tracks essential supply chain metrics like **Forecast Accuracy**, **Net Error**, and **Risk Profiles**.  
   - Helps identify areas for supply chain optimization and risk management.

   ![Image](https://github.com/user-attachments/assets/edade995-8d7b-4ea7-947f-f36a2a1117ca)

---

6. **Executive View**  
   - Consolidates key insights across all business areas for senior leadership.  
   - Provides a high-level summary of business performance to support data-driven executive decisions.

   ![Image](https://github.com/user-attachments/assets/77a5f7fb-691a-40ae-8014-aa0b3d4ab101)

---

## 🌟 **Project Implementation**

The development of this Power BI dashboard followed a structured approach involving data extraction, transformation, modeling, and visualization. Below is an overview of the implementation process:

### 1. **Database Design and Setup**  
- The database served as the foundation for storing and managing business data consistently across the system.  
- A **Snowflake schema** was implemented to organize data into well-structured, related tables—enhancing performance and scalability for analytics.

### 2. **Data Extraction and ETL Processes**  
- Data was sourced from multiple platforms, including **MySQL databases** and **Excel files**, ensuring comprehensive business inputs.  
- Robust **ETL (Extract, Transform, Load)** workflows using Python and SQL were applied to clean, normalize, and convert raw data into analysis-ready formats.  
- These processes ensured data accuracy, integrity, and consistency.

### 3. **Data Modeling**  
- Developed an integrated data model using the **Snowflake schema**, connecting over ten related tables for seamless cross-functional analysis.  
- Implemented advanced metrics and business logic using **DAX (Data Analysis Expressions)** to derive key KPIs and insights.

### 4. **Visualization and Reporting**  
- Built interactive dashboards in **Power BI**, incorporating visual elements such as charts, KPIs, and summary tables.  
- Features like **slicers**, **bookmarks**, and **buttons** enabled personalized navigation and drill-down analysis.  
- Published reports to **Power BI Service** for secure sharing and stakeholder access.

### 5. **Automation & Data Refresh**  
- Configured **Power BI Gateway** for automated data refresh and scheduling.  
- Enabled real-time updates and reduced manual effort through scheduled refresh intervals.

---

## 🔧 **Technical Stack**

- **Power BI:** For building dynamic dashboards and interactive reporting  
- **MySQL:** Primary database for storing structured data  
- **ETL Tools:** Python and SQL for data extraction and transformation  
- **DAX:** Used to implement calculated columns, measures, and KPIs  
- **Power BI Service:** For publishing, sharing, and managing report updates  
- **Snowflake Schema:** Adopted for efficient data modeling and performance

---

## 💡 **Insights**

- **Finance:** Net profit is declining despite growing sales—indicating rising operational costs.  
- **Sales:** Major clients like Amazon and Flipkart contribute the most revenue; smaller accounts underperform.  
- **Marketing:** Regional inefficiencies, especially in the Gaming category and APAC region, are impacting margins.  
- **Supply Chain:** Forecast accuracy is moderate; LATAM and India face inventory issues.  
- **Executive Summary:** Market share is improving, but profitability is tightening. Growth is strong in PCs and in regions like North America and India.

---

## ✅ **Recommendations**

- Optimize freight and operational expenses to improve profit margins.  
- Focus on high-performing accounts; reassess resource allocation for underperforming ones.  
- Redirect marketing efforts in low-growth segments and geographies.  
- Improve demand forecasting and inventory management processes.  
- Eliminate low-impact products; prioritize investment in high-demand categories.

---

## 🎯 **Key Learnings**

### **Technical Skills:**
- Designed scalable data models and relationships in Power BI  
- Created DAX measures for KPIs like net profit and forecast accuracy  
- Built intuitive dashboards with navigation and drill-through features  
- Transitioned from Excel-based reporting to a modern BI platform, enabling real-time insights

### **Soft Skills:**
- Applied data-driven decision-making to real-world business challenges  
- Enhanced visual storytelling and dashboard design  
- Aligned report outputs with stakeholder needs and expectations

---

## 🏁 **Conclusion**

This project enhanced my skills in **Power BI** and **data analytics**, providing AtliQ with a data-driven solution. By transitioning from Excel to a modern BI platform, AtliQ gained real-time insights across **finance**, **sales**, **marketing**, and **operations**, enabling smarter decision-making and proactive business strategies.
