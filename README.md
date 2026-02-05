📣 Meta Ad Performance Analysis – Power BI Dashboard


🔹 Project Overview

This project focuses on analyzing Facebook and Instagram paid advertising performance using Power BI.
The dashboard provides clear visibility into campaign reach, engagement, conversions, and budget utilization to help marketing teams optimize ad performance and ROI.

🎯 Business Objective

The business requires a performance tracking dashboard for advertising campaigns running on Facebook and Instagram.


The objective is to:

1.Identify the most effective platform

2.Track campaign ROI

3.Optimize budget allocation

4.Understand audience engagement patterns

5.Business Requirements Document



🛠 Tools & Technologies

1.Microsoft Power BI Desktop

2.CSV Files (Data Source)

3.Power Query (Data Cleaning & Transformation)

4.DAX (Measures & Calculations)

5.Data Modeling & Relationships

6. Power BI Service 

7. My SQL ( Data Validation)

8. 

📂 Data Preparation

Raw CSV files were imported into Power BI

Data cleaning performed using Power Query

Removed invalid / null records

Standardized columns

Data type corrections

Created calculated columns and measures using DAX



📌 Scope of the Report: 


In Scope

Paid ad campaigns on Facebook and Instagram

Out of Scope

Other platforms (Messenger, Audience Network)

Organic engagement (only paid ads considered)



📊 Key KPIs Implemented

*Impressions

*Clicks

*Shares

*Comments

*Purchases

*Engagements

*CTR (Click Through Rate)

*Engagement Rate

*Conversion Rate

*Purchase Rate

*Total Budget

*Average Budget per Campaign



📈 Dashboard Visualizations

Target Gender – Donut Chart

Performance split by gender with dynamic metric selection

Target Age Group – Bar Chart

Engagement comparison across age groups

Country – Map Visualization

Geographic distribution of ad performance

Calendar Month – Heat Map

Monthly activity trends and seasonality

Weekly Trend – Stacked Column Chart

Weekly performance by ad type

Hourly Trend – Area Chart

User activity pattern by hour of the day

Ad Type – Matrix

Comparison of performance across ad formats and platforms



🧠 Sample DAX Measures
Impressions = 
CALCULATE(COUNT(ad_events[event_type]), ad_events[event_type] = "Impression")

Clicks = 
CALCULATE(COUNT(ad_events[event_type]), ad_events[event_type] = "Click")

CTR % = 
DIVIDE([Clicks], [Impressions], 0) * 100

Engagements = 
[Clicks] + [Shares] + [Comments]




📊 Key Business Insights

Identified high-performing platforms (Facebook vs Instagram)

Found top-performing age groups and gender segments

Discovered peak engagement hours and months

Helped optimize ad budget allocation based on ROI

Business Requirements Document




🚀 How to Use

Open the .pbix file in Power BI Desktop

Refresh the CSV data source

Use slicers and metric selector

Analyze campaign performance interactively



📎 Project Files

Meta_Ad_Performance_Analysis.pbix

users.csv

Campaigns.csv

ads.csv

ad_events.csv

Image folders.file

README.md



🔮 Future Enhancements

Add campaign-level ROI analysis

Automate data refresh using APIs

Add forecasting for ad performance

Publish to Power BI Service



👤 Author

Name: Ayyanar M

Role: Power BI Developer

Domain: Marketing Analytics

Skills: Power BI, DAX, Power Query, Data Visualization

⭐ Conclusion

This project demonstrates an end-to-end Marketing Analytics Power BI solution, showcasing skills in data cleaning, DAX calculations, and interactive dashboard design aligned with real business requirements.
