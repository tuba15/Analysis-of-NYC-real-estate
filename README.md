







# 🏙️ Analysis of NYC Real Estate from the year 2003-2023

An analysis of **descriptive** and **predictive analytics** on commercial, residential, and mixed-use properties from 2003–2023 using Power BI.

---

## 📌 Overview

This Power BI dashboard explores residential property sales trends in **Elmhurst, Queens (NYC)** between 2003 and 2023. Designed to support strategic decisions for real estate expansion, the project integrates **descriptive analytics**, **data modeling**, and **DAX-based KPIs** to uncover actionable insights.

As an aspiring Business Analyst, this project demonstrates my ability to translate data into business strategies using technical tools and analytical reasoning.

---

## 🎯 Objectives

- Understand neighborhood-wise performance through descriptive analysis  
- Compare Elmhurst with top-performing NYC neighborhoods  
- Forecast residential sales trends through 2032  
- Support go/no-go decision for real estate firm expansion based on data  

---

## 💡 Business Insights

- Residential property sales in Elmhurst **peaked in 2020** with total sales of **$1.82 billion**, largely due to increased demand during remote work trends  
- **2023 recorded the lowest sales** at only **$0.4 billion**, highlighting current market decline and investment gap  
- Compared to Midtown West (34.21%) and Upper East Side (60.84%), Elmhurst contributed only **4.95%** to total residential sales in 2023  
- However, Elmhurst presents a **95% gap** from top neighborhoods, representing potential for **affordable growth and market penetration**  
- A projected **12% market penetration** could yield revenues of **$1.1 billion**, and a 5% commission on sales would result in **$15.07 million** in potential brokerage income

---

## ⚙️ Technical Implementation

### 📊 Descriptive Analytics

- Used historical data to summarize sales volume, price trends, and comparative rankings  

### 🧩 Data Modeling

- Created a **star schema** in Power BI connecting:
  - `NYC_Transaction_Data` with `Neighborhood` (via `Neighborhood_ID`)  
  - `Neighborhood` with `Borough` (via `Borough_ID`)  
  - `Building Class` with `Transaction Data` (via `Building_Code_ID`)  
- Built **primary-foreign key relationships** to enable efficient querying  

### 🧮 DAX Measures

- **Total Residential Sales (2023):** 742 transactions  
- **Average Sale Price (2023):** ~$540,000  
- **Commission Estimate (5% of Sales):** $15.07 million  
- **Projected Market Penetration Revenue (12%):** $1.10 billion  
- All KPIs built using DAX in Power BI with dynamic filters by year and property type  

### 📈 Forecasting

- Applied time-series forecasting from 2024 to 2032 using Power BI’s analytics tools  

---

## 🛠 Tools Used

- Power BI (Data Modeling, DAX, Visuals)  
- SQL Server (Original dataset)  
- Excel (Data preprocessing and cleaning)  

---

## 📁 Project Files

- `Assignment_1.pbix`: Full dashboard file  
- `Managerial report-Powerbi.docx`: Written business analysis  

📊 [Click here to view the Dashboard](https://drive.google.com/file/d/1HMd94QcLQ3adRuls0HpoCONDysT33Mdz/view?usp=sharing)  
📝 [Click here to view the Managerial Report](https://docs.google.com/document/d/1_LE34_NU_tX9Kp9yuVok9V4ZaoDivCHw/edit?usp=sharing)  

---

## 📊 Key Visualizations

- Gauge Chart: Volume of residential sales in Elmhurst (742 sales in 2023)  
- Line and Column Chart: Sales trend from 2019–2023 showing 2020 peak and 2023 dip  
- Pie Chart: Elmhurst vs. Midtown West & Upper East Side – contribution to NYC residential sales  
- Forecast Chart: Projected residential sales from 2024 to 2032 using Power BI forecasting  
- KPI Cards: Commission, market penetration revenue, average sale price  

---

## 👤 Author

**Tuba Anwar**  
MS in Applied Business Analytics, Boston University  
📧 tubaanwar135@gmail.com  
🌐 [LinkedIn](www.linkedin.com/in/tuba-anwar-a90a7823a) 

