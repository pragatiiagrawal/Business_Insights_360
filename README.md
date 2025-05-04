# 🌐 **Business-Insights-360**

### 🔗 [**Live Dashboard Link**](https://app.powerbi.com/view?r=eyJrIjoiY2NmNzgyNTYtYTAzNS00ODRjLWEwNzYtMDBiMDM2Mzg2OGYyIiwidCI6IjRhMjQyMDI5LTEwMmEtNDI5Ni1iYTY3LTAwNzUxNDEyZjUwYiJ9)  
### 📥 [**Download Dashboard PDF – Business_Insights_360**](https://github.com/pragatiiagrawal/Business_Insights_360/blob/f6261d1d33004cc86036f0f27288c1419fc28513/Business_Insights_360.pdf)


## 🏢 **Company Overview**

**AtliQ Hardwares** is one of the fastest-growing companies in the electronic goods market, specializing in high-quality PCs, keyboards, mice, and printers for both consumers and businesses. With a mission to innovate and deliver top-tier products, AtliQ has established itself as a leader in providing reliable and affordable electronic solutions globally.

---

## ⚠️ **Problem Statement**

AtliQ's reliance on Excel-based analytics created inefficiencies in reporting, leading to time-consuming processes, errors, and limited scalability. As the company expanded globally, the complexity of data grew, and their reporting system failed to provide real-time insights for decision-making. Key regions like LATAM faced financial losses due to slow, inconsistent data analysis.

The solution: Build a dynamic BI system for faster, more accurate insights to support strategic planning.

---

## 🎯 **Objective**

- Modernize reporting by replacing Excel-based analysis with interactive Power BI dashboards.
- Create department-wise views for Finance, Sales, Marketing, and Supply Chain.
- Provide real-time insights to enable quicker, data-driven decisions.
- Improve reporting efficiency and centralize analytics for scalability.

---

## 🔍 **Dataset Overview**

The project integrates various data sources to provide comprehensive insights:

| **Source** | **Table Name**            | **Description**                              |
|------------|---------------------------|----------------------------------------------|
| **MySQL**  | **Fact_Forecast_Monthly**  | Forecasted product demand by month           |
| **MySQL**  | **Fact_Sales_Monthly**     | Actual sales data                           |
| **MySQL**  | **Fact_Manufacturing_Cost**| Monthly manufacturing costs                  |
| **Excel**  | **Target**                 | Sales targets                               |
| **Excel**  | **Market_Share**           | Competitor market share data                |

---

## 🔗 **Data Model Diagram**

The Snowflake schema organizes data into related tables, ensuring high performance and scalability for analytics.

![Data Model Diagram]<img width="1696" alt="Image" src="https://github.com/user-attachments/assets/da7812d5-2634-4d1a-bf1f-534e6db14483" />

---

# 🔑 **Key Business Insights & Functionalities**

## 🏠 Home Page  
   A streamlined homepage provides a welcoming introduction and easy navigation to each department’s view, enhancing user experience.

   ![Home Page Preview](https://github.com/user-attachments/assets/15b89824-0327-45d0-81d9-f3ac2a51bdb1)

## 💰 Finance View   
   The **P&L Statement** allows for quick analysis of financial performance by region, customer, and product, helping users identify revenue and cost trends.

   ![Finance View](https://github.com/user-attachments/assets/a62e57d3-695e-448a-ad0a-8b147b72c66a)

## 📈 Sales View  
   Focused on **Net Sales**, **Gross Margin**, and **Profitability**, the sales view includes an interactive **Growth Matrix** to track performance and assess profitability.

   ![Sales View](https://github.com/user-attachments/assets/2fa9bee3-3870-4af9-aec2-47c978be3468)
<img width="637" alt="Image" src="https://github.com/user-attachments/assets/2daa77bc-46a7-4ef5-9fad-0dc6dc912ab3" />
## 📢 Marketing View  
   A detailed analysis of product performance using metrics like **Net Sales** and **Gross Margin** helps optimize marketing strategies.

   ![Marketing View](https://github.com/user-attachments/assets/7f5dbc65-509f-4aa4-8c0a-7ad560c9ef08)

## 🚚 Supply Chain View   
   Key metrics like **Forecast Accuracy** and **Risk Profiles** are tracked, enabling proactive supply chain optimization and risk management.

   ![Supply Chain View](https://github.com/user-attachments/assets/d879dcfc-107f-4adc-9a7c-4b9ef8f886f4)

## 👔Executive View   
   A consolidated view for senior leadership that highlights key performance metrics across all business functions for strategic decision-making.

   ![Executive View](https://github.com/user-attachments/assets/2c45ac3f-b317-4005-881a-de0d06fc6af4)

---

# 🛠️ **Project Implementation**

- ###  Database Design & Setup  
A **Snowflake schema** was implemented for efficient data storage, improving performance and scalability. Relationships between fact and dimension tables support seamless analysis.

- ###  ETL & Data Transformation  
Using **Python** and **SQL**, data was extracted from multiple sources (MySQL, Excel), cleaned, and transformed into a suitable format for analysis. This ensured data accuracy and consistency.

- ###  Data Modeling & DAX Implementation  
The data model was designed to integrate over 10 tables. DAX measures were applied to calculate KPIs like **Net Profit**, **Sales Growth**, and **Forecast Accuracy**.

- ###  Dashboard & Report Development 
Interactive dashboards were built in **Power BI**. Features like **slicers**, **bookmarks**, and **buttons** enabled personalized navigation, making it easier for users to drill down into data.

- ###  Automation & Real-Time Updates  
With **Power BI Gateway**, the dashboard refreshes automatically, ensuring real-time data updates and reducing the need for manual data entry.

---

## 👩‍💻 **Tech Stack**

- **Data Visualization**: Power BI  
- **Data Modeling**: Snowflake Schema, DAX  
- **ETL Tools**: Python, SQL  
- **Tools**: Power BI Desktop, Power BI Service

---

## 💡 **Key Insights**

- **Finance**: Rising sales are offset by increasing operational costs, affecting profitability.  
- **Sales**: Large accounts like Amazon and Flipkart are key revenue drivers, while smaller accounts need more focus.  
- **Marketing**: APAC region shows inefficiencies, lowering marketing ROI.  
- **Supply Chain**: Moderate forecast accuracy and inventory issues in LATAM and India.  
- **Growth Trends**: Strong growth in North America and India, especially in PCs, though profitability is under pressure.

---

## ✅ **Recommendations**

- Streamline freight and operational expenses to improve margins.  
- Prioritize high-performing accounts and optimize resources for underperforming ones.  
- Adjust marketing strategies in low-growth regions.  
- Enhance demand forecasting and inventory management to reduce stockouts.  
- Focus investment on high-demand, high-profit products.

---

## 🎯 **Key Learnings**

- Improved my skills in **Power BI**, **DAX**, and **data visualization**.  
- Transitioned from Excel-based reporting to a modern BI platform for real-time insights.  
- Enhanced data storytelling and aligned reports with business goals.

---

## 🏁 **Conclusion**

This project empowered AtliQ with a modern BI platform that streamlined reporting and improved decision-making across finance, sales, marketing, and operations. The **Business-Insights-360** dashboard offers dynamic, real-time insights that support proactive business strategies, replacing outdated Excel-based processes with an interactive, scalable solution.
