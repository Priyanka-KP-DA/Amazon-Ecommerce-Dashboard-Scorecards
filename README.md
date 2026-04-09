# 📊 E-Commerce Performance & Growth Analysis (Amazon Dataset | Excel + Power Pivot)

## 🚀 Project Overview 

What if an e-commerce business is generating millions in revenue but still missing growth opportunities?

In this project, I analyzed **5 years of Amazon e-commerce data** across Orders, Campaigns, and Website Traffic to uncover performance trends, inefficiencies, and growth levers.

This project simulates how a **Data Analyst supports business, marketing, and product teams** using structured data modeling, KPI frameworks, and dashboards.

---

## 📁 Dataset Description

Source: Kaggle (Amazon E-commerce Dataset)

The project integrates **3 core datasets**:

- **Orders Dataset** ~100,000 rows (100K transactional records) → Revenue, Orders, Customer behavior  
- **Campaign Dataset** ~1065 rows → Spend, Clicks, Impressions, Conversions  
- **Website Traffic Dataset** ~2,007 rows → Page Views, Sessions, Engagement  

Time Period: **5 Years (2019–2024)** 

👉 Note: Datasets vary in granularity, with orders being transaction-level data and campaign/traffic datasets being aggregated over time.
---

## 🧹 Data Cleaning (Power Query) & Challenges

The raw data was **messy and inconsistent**, requiring multiple transformation steps:

### Key Issues:
- Missing and inconsistent column names  
- Duplicate and redundant metrics  
- Misaligned KPIs across datasets  
- Raw metrics not analysis-ready
- Incorrect/Unrealistic values in the existing columns
- Missing major columns
- Broken logic between existing columns  

### Solutions Implemented:
Used **Power Query** to:
- Clean and Standardized column naming conventions  
- Updated the values of existing columns while keeping then as per standard.
- Created **corrected KPI fields** (e.g., corrected page views, unique views)  
- Removed redundant columns and ensured data consistency
- Transform data types
- Built helper columns for:
  → Date hierarchy (Year, Month)
  → Channel segmentation
  → KPI alignment across datasets  

---

## 🔗 Data Modeling (Power Pivot)

- Built a relational data model connecting Orders, Campaign, and Website Traffic datasets  
- Linked datasets using common dimensions (Date, Channel)  
- Designed a structured schema for scalable analysis  
- Calendar Table Implementation:
- Created a dedicated Calendar (Date Dimension) table and Connected it to all datasets  
- Generated continuous date range covering full 5-year period    
  
---

## 🧮 DAX Measures (Advanced Calculations)

Created dynamic measures using **DAX in Power Pivot**:

- CPA = SUM(Spend) / SUM(Conversions)
- ROAS = SUM(Revenue) / SUM(Spend)
- CVR = SUM(Conversions) / SUM(PageViews)
- CTR = SUM(Clicks) / SUM(Impressions)
- AOV = SUM(Revenue) / COUNT(OrderID)

👉 Ensured correct aggregation (avoided row-level calculation errors)

---

## 📊 KPI Scorecard (18 KPIs)

- 18 KPIs tracked against:
  
  → Previous performance  
  → Targets  
- Color-coded status:
  
  → 🟢 Meets/exceeds target  
  → 🟡 Near target  
  → 🔴 Underperforming

The structured 18 KPI system cover:
  
### Revenue & Profitability
→ Net Revenue  
→ Gross Revenue  
→ AOV (Average Order Value)  
→ Gross Margin %  
→ CLV  

### Marketing Efficiency
→ ROAS  
→ CAC / CPA  
→ CTR  

### Conversion & Funnel Metrics
→ Website CVR  
→ Sales CVR  
→ Bounce Rate  
→ Conversion Funnel Metrics  

### Customer & Operations
→ Repeat Rate  
→ Return Rate  
→ Order Fulfillment Rate  
→ Discount Rate  
→ Shipping Cost per Order  
→ Avg Session Duration  


---

## 📈 Trends Dashboard Design

- Built a multi-layered trends dashboard to analyze performance across marketing, traffic, and revenue over time
- Integrated cross-functional metrics (Campaign + Website + Orders) to provide a holistic business view
- Designed dual-axis charts to compare:

   → Revenue vs Spend  
   → Page Views vs Conversions  
   → CPA vs Revenue efficiency 

- Developed funnel visualizations to track user journey:
   
   → Impressions → Clicks → CTR  
   → Page Views → Conversions → CVR
  
- Enabled dynamic filtering using slicers (Year, Month, Channel) for interactive analysis
- Highlighted seasonality patterns and monthly fluctuations in performance
- Compared traffic generation vs conversion output to identify bottlenecks
- Built channel-level revenue breakdown to evaluate marketing contribution
- Ensured consistency between KPIs and visualizations using data model + DAX measures
- Designed dashboard with a focus on decision-making for stakeholders (marketing, product, operations)

---

## 🔍 Key Business Insights

- 📉 **Conversion Rate (~2%) is low despite high traffic**
  → Major drop-off in mid-funnel

- 📈 **Strong ROAS (~5.0)**
  → Marketing spend is highly efficient

- 💰 **Stable CPA (~$3)**
  → Customer acquisition cost is under control

- ⚠️ **Revenue fluctuations driven by conversion, not traffic**
  → Traffic alone is not the bottleneck

- 📊 **Balanced channel contribution**
  → No over-dependence on a single channel

---

## 🚨 Problem Statements Identified

1. High traffic but low conversion → **inefficient website experience**
2. Strong acquisition but weak monetization → **conversion gap**
3. Slight decline in key KPIs vs targets → **performance inconsistency**
4. Operational inefficiencies (returns, fulfillment gaps)

---

## 💡 Business Recommendations

- Improve **website UX & checkout flow** to boost CVR  
- Optimize **landing pages for high-intent users**  
- Reallocate budget to high-performing channels based on ROAS  
- Reduce return rates via better product info & quality control  
- Improve fulfillment efficiency to enhance customer experience
- Run A/B tests on campaigns and product pages
- Increase retention strategies (loyalty programs, remarketing)

---

## 🛠️ Tools & Skills Demonstrated

- Excel (Advanced)
- Power Query (Data Cleaning & Transformation)
- Power Pivot (Data Modeling)
- DAX (Measures & KPIs)
- Pivot Tables & Dashboarding
- Data Modeling & Relationships
- Business Analytics & KPI Design
- Data Storytelling

---

## 🎯 Key Takeaways

This project demonstrates:
- End-to-end analytics workflow (Raw Data → Insights)
- Strong understanding of e-commerce metrics
- Ability to build scalable data models
- Business-focused thinking and decision support

---

## 📷 Scorecard & Dashboard Preview


<img width="1479" height="791" alt="image" src="https://github.com/user-attachments/assets/d04f6d53-d881-4310-8655-caa1a5d56dbb" />

![Data Modelling](https://github.com/user-attachments/assets/2fcd8ab6-635d-4ca8-9cc0-89f7b4baab2a)

<img width="1477" height="788" alt="image" src="https://github.com/user-attachments/assets/e0cfc5f8-132b-493b-aa45-1ef89960d1fd" />

---

## 🤝 Let’s Connect

I’m currently working in a retail environment, where I’ve developed a strong understanding of customer behavior, in-store operations, and service quality.

Through this project, I aimed to complement that hands-on experience with data-driven analysis, focusing on how customer interactions, marketing efforts, and operational decisions impact overall business performance.

I’m particularly interested in roles that combine:
- Customer experience  
- Retail operations  
- Data-driven decision making  

I’m always open to learning, contributing, and applying analytics to improve real-world retail environments.

If you’re working in retail, e-commerce, or analytics, I’d be glad to connect and exchange ideas!

---

## ⚠️ Disclaimer

This project is based on a publicly available dataset sourced from Kaggle and is **not an actual Amazon dataset**.

To better simulate a real-world business scenario, the dataset has been significantly enhanced and transformed:
- Data was cleaned, standardized, and restructured  
- Missing values were handled and, where necessary, supplemented to maintain analytical consistency  
- Regions and fields were adjusted to follow realistic business formats  
- Additional calculated fields and helper columns were created to align with real-world KPI tracking  

The goal of these modifications was to **replicate a realistic e-commerce data environment inspired by Amazon-style analytics standards**, and to demonstrate end-to-end analytical capabilities.

This project is intended solely for **portfolio and learning purposes**, focusing on:
- Data cleaning and transformation  
- Data modeling and KPI design  
- Dashboard development and data storytelling  

All insights and visualizations are derived from this simulated dataset and should not be interpreted as real Amazon business data.
