# Sales-Trends-Profitability-Insights-International-Breweries-Analysis
Analyzing sales trends in the International Breweries dataset to drive data-driven decision-making, maximize profits, and minimize losses.

📌 Project Title

Sales Trends & Profitability Insights: International Breweries Analysis

📌 Project Introduction

International Breweries Plc, a Nigerian subsidiary of global brewing giant AB InBev, operates major facilities in Ilesa, Onitsha, and Sagamu. Established in 1971, the company serves a wide consumer base across Nigeria with a diverse product lineup, including popular beer and malt brands such as Castle Lite, Budweiser, Eagle Lager, Trophy, Hero, Grand Malt, and Beta Malt.

📌 Aim
This project analyzes sales and profit data (2017–2019) to uncover trends, identify high and low-performing brands, and explore regional and seasonal patterns to drive strategic, data-informed business decisions.

📌 Data Summary

Source: Kaggle Dataset

Scope: 3 years of sales data, 7 brands, 11 sales reps, 6 regions, 5 countries

📌 Tools Used

Excel, PostgreSQL (pgAdmin), SQL, Power BI, PowerPoint

📌 Project Overview

Over a three-year period, International Breweries generated a total profit of ₦105.59 million, with Francophone countries outperforming Anglophone ones by 19.7%. The most profitable brands were Castle Lite, Budweiser, and Eagle Lager, while Trophy, Hero, and Grand Malt contributed the least. Senegal led in profits (₦21M), and Togo recorded the lowest.

* March was the most profitable month; April the least.

* 2017 was the best year in both profit and quantity sold, while 2019 was the lowest.

* A strong correlation was found between sales volume and profit, emphasizing the value of sales performance in profitability.

📌 Methodology 

The project followed a structured approach:

Data Importation: The dataset was extracted from Excel and imported into PostgreSQL using pgAdmin, with validation checks to ensure accuracy.

Data Cleaning: Column names were standardized and data types adjusted for consistency and compatibility.

Exploratory Data Analysis (EDA): SQL queries were used to analyze key metrics—profit, quantity sold, brand performance, regional trends, and seasonal insights.

Data Visualization: The cleaned data was visualized in Power BI, creating interactive dashboards to uncover trends and support strategic decision-making.

📌 Observations & Key Insights 

* Profit Trends Over Time:
  
The highest profit was recorded in 2017 at 36.47%, but profits steadily declined to 35.10% in 2018 and further to 28.43% in 2019. This downward trend coincides with significant shifts in the best-selling brands, highlighting a connection between brand performance and profitability.

* Shifts in Best-Selling Brands Affecting Profitability:
  
In 2019, Hero and Grand Malt emerged as the highest-selling brands, replacing previously dominant brands like Castle Lite and Budweiser, which recorded the lowest quantities sold that year. This shift contributed directly to the overall decline in total profit, emphasizing the critical role of brand preference dynamics in financial outcomes.

* Top and Bottom Performing Brands:
  
Castle Lite, Budweiser, and Eagle Lager— all beer brands — consistently generated the highest profits, while Trophy, Hero, and Grand Malt lagged in both sales and profitability overall. Interestingly, Hero and Grand Malt’s surge in sales in 2019, despite lower profitability, suggests potential margin or cost issues needing further analysis.

* Regional Market Performance and Consumer Preferences:
  
Profitability varies markedly by region, with Senegal leading at N21 million (20.35%), followed closely by Nigeria (20.25%), Ghana (19.9%), and Benin (19.85%). Togo showed the lowest profits (19.65%), likely due to its top-selling brand, Grand Malt, being among the least popular overall. Similarly, the South-South, West, and North-Central regions outperformed others, whereas North-East, South-East, and North-West regions underperformed. The underperformance in markets like Benin and Togo underscores the need for localized marketing strategies and brand introduction campaigns to align better with consumer preferences.

* Correlation Between Sales Volume, Profit, and Cost:
  
There is a clear correlation between the quantity of brands sold, total profit, and total cost—meaning that as sales volumes increase, both profit and operational costs rise. This relationship highlights the importance of balancing sales growth with cost management to optimize profitability.

* Seasonality Influences Sales and Profit:
  
Sales and profit peak during the dry season (December to March), with March recording the highest profit (#9.07M). Conversely, sales dip significantly during the rainy season (April to October), with April experiencing the lowest profit (#8.57M). This seasonal pattern indicates strong demand fluctuations, suggesting companies could boost revenues by strategically timing promotional campaigns before peak sales periods.


📌 Insights from Data Visualization

1.	Sales Trends Over Time (Line Chart)
   
* Sales showed a consistent upward trend from 2017 to 2018, but a decline was observed in 2019.
  
* The peak sales period occurred during the dry season (December–March), indicating higher demand during this time.
  
* A notable drop in sales in mid-2019 suggests possible external factors such as changes in market demand, economic conditions, or supply chain disruptions.
  
2.	Regional Performance (Waterfall Chart)
   
* Senegal recorded the highest profit (N21 million, 20.35%), followed closely by Nigeria (20.25%), Ghana (19.9%), and Benin (19.85%).
  
* Togo had the lowest profit (19.65%), likely due to Grand Malt being its highest-selling brand, despite being one of the least popular overall.
  
* The top-performing regions in sales were South-South, West, and North-Central, while the least-performing regions were North-East, South-East, and North-West.
  
* Regional variations in sales could indicate differences in consumer preferences, brand awareness, and economic conditions.
  
3.	Profitability Breakdown (Waterfall Chart)
   
* Beer brands dominated profitability, with Castle Lite, Budweiser, and Eagle Lager contributing the highest revenue.
  
* The least profitable brands were Trophy, Hero, and Grand Malt, which also had lower sales volumes.
  
* The 2017 financial year had the highest profit margin (36.47%), but profitability declined in 2018 (35.10%) and dropped further in 2019 (28.43%).
  
* A detailed breakdown showed that high sales volume did not always equate to high profitability, as seen in Hero and Grand Malt in 2019.
  
4.	Actionable Dashboards in Power BI
   
* A sales performance dashboard provided an overview of revenue trends, best-selling brands, and underperforming products.
  
* A regional analysis dashboard helped in identifying areas for market expansion or strategic focus based on sales and profitability data.
  
* A profitability dashboard showcased profit margins per product and region, assisting in strategic decision-making for pricing and marketing efforts.
  
* Seasonal trend analysis dashboards helped forecast demand fluctuations, enabling better inventory and sales planning.
  
* Interactive Power BI Dashboard → Click the link below to view the interactive Power BI dashboard

📌 Power BI Dashboard
  
👉 [View Interactive Dashboard](https://app.powerbi.com/reportEmbed?reportId=5abd6940-4195-4c01-bea5-18c9d38016a8&autoAuth=true&ctid=bd697c1b-c481-479c-841e-c618542675c3)

📌 Conclusion

The analysis of International Breweries’ sales and profitability data from 2017 to 2019 revealed critical patterns in revenue generation, brand performance, seasonal influence, and regional demand.

* 2017 was the most profitable year (36.47%), with profits declining to 35.10% in 2018 and 28.43% in 2019.

* Castle Lite, Budweiser, and Eagle Lager consistently ranked as top profit-generating brands.

* In contrast, Trophy, Hero, and Grand Malt recorded lower profits, despite some becoming high-selling brands by 2019—suggesting that high sales volume does not always guarantee profitability.

* Francophone countries, particularly Senegal, outperformed Anglophone counterparts, while Togo underperformed, likely due to brand preference misalignment.

* A strong correlation exists between quantity sold, total profit, and total cost, emphasizing the importance of managing both volume and efficiency.

* Seasonal trends show that sales and profits peak during the dry season (December–March) and drop during the rainy season (April–October), presenting clear opportunities for campaign timing and resource planning.


📌 Recommendations

To boost performance and profitability, the following strategies are recommended:

* Double down on high-performing brands (Castle Lite, Budweiser, Eagle Lager) with increased investment in promotion, availability, and distribution.

* Re-evaluate and support underperforming brands (Trophy, Hero, Grand Malt) by refining pricing, marketing, or possibly repositioning based on local demand insights.

* Leverage seasonal trends by planning promotional campaigns and stocking efforts in advance of the peak dry season (December–March).

* Localize strategies by region: Tailor marketing efforts and brand awareness campaigns for underperforming countries like Benin and Togo to align with consumer preferences.

* Introduce product sampling campaigns in weak markets to increase exposure to high-performing brands and influence buyer behavior.

* Implement forecasting models to optimize inventory, avoid stockouts during high-demand periods, and reduce overstocking during slow months.

* Utilize interactive dashboards (e.g., Power BI) to monitor performance in real time and guide responsive, data-backed decisions.



