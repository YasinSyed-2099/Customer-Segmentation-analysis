# Customer Segmentation Analysis – Istanbul

## 1. Project Title 
**Customer Segmentation & Sales Analysis – Istanbul Market**  

A Power BI project analyzing customer behavior, sales trends, and top-performing malls and product categories from 2021 to 2023. The project identifies high-value customer segments and supports data-driven marketing strategies.

---

## 2. Short Description

This project converts raw  data into actionable business insights using Power BI. It analyzes trends in total sales, quantity sold, and customer demographics, uncovering patterns by age, gender, and seasonality. Customers are segmented to identify high-value groups and support strategic decision-making. The analysis highlights top malls and product categories, helping businesses understand revenue drivers and customer behavior. Interactive dashboards with DAX measures and star-schema modeling enable easy monitoring of year-over-year performance and seasonal fluctuations. Overall, the project empowers stakeholders to make informed decisions and improve business outcomes through data-driven insights.


---

## 3. Problem Statement
Businesses face challenges in:

- Identifying high-value customer segments.
- Determining which malls and product categories need promotions or discounts.
- Understanding sales variations across gender, age, payment methods, and seasonal trends.

This project provides insights to improve **sales performance and marketing effectiveness**.

---

## 4. Goal of the Dashboard
- Track **total sales, quantity sold, and customer counts** over time.
- Identify **top malls and product categories** driving revenue.
- Highlight **gender and age group contributions** to sales.
- Segment customers for **targeted marketing campaigns**.
- Monitor trends, **ups and downs**, and calculate **year-over-year percentage changes**.
- **[Click here to download the Power BI Dashboard file(.pbix)]([https://github.com/YasinSyed-2099/Customer-Segmentation-analysis/edit/main/Customer%20Segmentation%20Analysis%20.pbix)**


### Dashboard
![Customer Segmentation Dashboard](https://raw.githubusercontent.com/YasinSyed-2099/Customer-Segmentation-analysis/main/Customer%20Segmentation%20analysis%20Image.png)


---

## 5. Data Source
The dataset is **proprietary and provided by Rubixe - AI Solutions**, so it is **not included in this repository**.  
The dataset covered **2021–2023**, with **2023 data being partial**, and included key **columns, facts, and dimensions** used for analysis:

**Fact Table – Sales**
- Customer ID
- Invoice Number
- Mall ID
- Payment Method ID
- Product Category ID
- Price
- DAX Measures: Total Quantity, Total Sales

**Dimension Tables**
- **Customer:** Customer ID, Age, Age Group, Gender, Total Customer (DAX)
- **Payment Method:** Payment Method, Payment Method ID
- **Location:** Mall ID, Shopping Mall
- **Product:** Category, Product Category ID
- **Calendar:** Day, Day Name, Invoice Date, Invoice Number, Month, Month Name, Quarter, Year

**Parameters:** Sales, Customer Count, Quantity Sold

### Model View
![Data Model View](https://github.com/YasinSyed-2099/Customer-Segmentation-analysis/blob/main/Model%20View.png)
---

## 6. Project Workflow
1. **Data Collection:** Connected SQL database directly to Power BI.
2. **Data Preparation:** Cleaned data using Power Query Editor (removed duplicates, trimmed spaces, corrected inconsistencies).
3. **Data Transformation:** Added calculated columns and DAX measures for meaningful analysis.
4. **Data Modeling:** Structured fact and dimension tables in **Star Schema**, optimized relationships and performance.
5. **Data Analysis & Visualization:** Created an **interactive dashboard** showing trends by gender, age group, mall, product category, and season.

---

## 7. Key Insights & Metrics

### Sales & Customer Trends (2021–2023)

| Year | Total Sales (M) | Total Quantity (K) | Total Customers | YoY Sales % Change | YoY Quantity % Change |
|------|----------------|-----------------|----------------|------------------|--------------------|
| 2021 | 114.560        | 136.096         | 45,382         | –                | –                  |
| 2022 | 115.436        | 137.147         | 45,551         | +0.76%           | +0.77%             |
| 2023 | Trends aligned | Trends aligned  | Trends aligned | –                | –                  |

### Additional Insights
- **Female customers (~60%)** remain the primary revenue drivers across both years.
- **Top Malls:** Mall of Istanbul and Kanyon consistently lead in sales, alternating in female segment leadership.
- **Top Product Categories:** Clothing, Shoes, and Technology dominate revenue — key focus areas for stock and marketing optimization.
- **Age Contribution:** Customers **50+** contribute most, indicating loyalty and strong spending capacity.
- **Seasonal Trends:** Q2–Q3 are peak periods, suggesting ideal timing for promotions and discounts.
- **Sales Trend:** Growth is marginal at **+0.76% YoY**, stable but signaling a need for innovation in campaigns or product offerings.

---

## 8. Conclusion
The Istanbul market shows **steady performance and gender-driven trends**, with **women and older customers** as the most valuable segments.  
Focusing on **fashion categories, seasonal campaigns, and loyalty programs** in top-performing malls like **Mall of Istanbul** and **Kanyon** will maximize revenue potential and strengthen customer engagement.

## **Contact**
- **Email:** yasinsyedmadharraja@gmail.com  
- **LinkedIn:** [linkedin.com/in/yasin-syedmadharraja](https://www.linkedin.com/in/yasin-syedmadharraja)  
- **GitHub:** [github.com/YasinSyed-2099](https://github.com/YasinSyed-2099)

## Acknowledgment
This project was completed as part of my internship at Rubixe - AI Solutions Company. The dataset and tasks were provided by the company for  analysis purposes.
