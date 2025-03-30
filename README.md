📌 Project Title

Sales Trends & Profitability Insights: International Breweries Analysis

📌 Project Introduction

International Breweries Plc is a leading brewing company in Nigeria, founded in 1971. It operates as a subsidiary of AB InBev, one of the world's largest beer brewing companies. The company has three major breweries strategically located in Ilesa, Osun State; Onitsha, Anambra State; and Sagamu, Ogun State, enabling them to meet consumer demand across the country.
International Breweries produces a diverse range of popular beer and non-alcoholic malt drink brands, including: Castle Lite, Budweiser, Eagle Lager, Trophy, Hero, Grand Malt, and Beta Malt.

📌 Aim

The success of any business relies on its ability to make informed, data-driven decisions. This project aims to analyze sales and profit data from a three-year period (2017–2019) to generate actionable insights that maximize profit and minimize losses. By identifying trends, evaluating high and low-performing products, and examining regional and seasonal variations, this analysis seeks to uncover opportunities for growth and address inefficiencies. Using the International Breweries dataset, the project emphasizes the importance of data in driving informed decision-making to boost sales and overall performance.


📌 Data Source & Summary

The data for this project was obtained from Kaggle and spans a period of three years. It contains records from 11 sales representatives operating across 6 regions in 5 countries, detailing the sales performance of a total of 7 different brands. You can access the dataset here [Kaggle Dataset]( https://www.kaggle.com/datasets/bluchuay/international-breweries?resource=download) 


📌 Project Overview

Over the past three years, the breweries generated a total profit of N105,587,420.00, showcasing consistent performance across their product range. A detailed analysis revealed that Francophone countries outperformed Anglophone countries, achieving 19.70% higher profit during this period.
The top three profit-generating brands were Castle Lite, Budweiser, and Eagle Lager, all of which are beer brands. In contrast, Trophy, Hero, and Grand Malt ranked as the least-selling brands, contributing the lowest profits.
Senegal topped the profit chart with N21 million (20.35%), while Togo recorded the lowest profit at 19.65%, possibly influenced by the lower popularity of Grand Malt, its highest-selling brand.
Monthly analysis showed that March delivered the highest profit (N9.07 million), while April recorded the lowest (N8.57 million). Yearly trends indicated that 2017 was the most profitable year, while 2019 generated the least profit. Similarly, 2017 recorded the highest quantity sold, whereas 2019 had the lowest.
The analysis further uncovered a strong correlation between the quantity sold and the profit generated, reinforcing the importance of sales volume in driving profitability.

📌 Methodology

Methodology
1. Data Importation
The original dataset was extracted from Excel files and imported into PostgreSQL via pgAdmin.

Data validation checks were conducted during the import process to ensure consistency and accuracy.

2. Data Cleaning and Preparation
Column names were standardized for uniform formatting and appropriate data types were assigned.

Each column’s data type was reviewed to ensure compatibility with PostgreSQL (e.g., numeric fields retained numeric formats, and dates followed standard conventions).

3. Exploratory Data Analysis (EDA)
The dataset was stored in PostgreSQL, and queries were written to aggregate, filter, and analyze key metrics, including:

Total profit, Number of brands, Total quantity sold, Number of sales representatives, Sales trends and brand performance, Regional variations 

Additional calculations were performed to determine:

Annual profit percentages, Seasonal performance trends, Comparative analysis of brands and regions

4. Data Visualization
The dataset was imported into Power BI to generate interactive visualizations and dashboards.

Patterns, trends, and insights were documented to support data-driven decision-making.

5. Tools Used
Excel, SQL, Power BI, and PowerPoint.

📌 Obserevations

* The highest profit was recorded in 2017 (36.47%), but it declined to (35.10%) in 2018 and further dropped to (28.43%) in 2019.

* The top three profit-generating brands are Castle Lite, Budweiser, and Eagle Lager, all of which are beer brands.

* The least-selling brands, which also generated the lowest profits, are Trophy, Hero, and Grand Malt.

* In 2019, Hero and Grand Malt were among the highest-selling brands, while previously top-selling brands (Castle Lite and Budweiser) recorded the lowest quantities sold. This shift may have contributed to the 
  decline in profits.

* Sales peak during the dry season (December–March), leading to higher profits, while they decline during the rainy season (April–October).

* Senegal recorded the highest profit (N21 million, 20.35%), followed by Nigeria (20.25%), Ghana (19.9%), and Benin (19.85%). The lowest profit was recorded in Togo (19.65%), possibly due to its highest-selling 
  brand (Grand Malt) being among the least popular overall.

* Sales vary across regions, depending on consumer preferences and demand for specific brands. The top-performing regions are South-South, West, and North-Central, while the least-performing regions are North- 
  East, South-East, and North-West.

📌 Key Insights from the Project

Shifts in Best-Selling Brands Impacted Profitability

* In 2019, Hero and Grand Malt became the highest-selling brands, while previously top-selling brands like Castle Lite and Budweiser recorded the lowest quantities sold.

* This shift in brand performance contributed to the observed decline in total profit.

Correlation Between Sales Volume, Profit, and Cost

* There is a strong correlation between the quantity of brands sold, total profit, and total cost.

* As the quantity sold increases, both total profit and total cost rise simultaneously, indicating the impact of sales volume on profitability and operational expenses.

Underperformance in Certain Markets (Benin & Togo)

* Benin and Togo underperformed primarily because the least-selling brands in the dataset are currently the most popular in these markets.

* To address this, localized advertising campaigns should be tailored to resonate with consumer preferences.

* Additionally, sampling campaigns can help introduce better-performing brands in these regions, potentially increasing sales.

Seasonal Influence on Beer Sales & Profit Trends

* Beer sales peak between December and March, aligning with the dry season.

* March recorded the highest profit (#9.07M), while April had the lowest (#8.57M).

* Conversely, sales decline significantly during the rainy season (April-October), demonstrating the impact of seasonal demand shifts.

* Companies can capitalize on these trends by launching strategic promotional campaigns ahead of peak months to boost revenue.


📌 Insights from Data Visualization

1. Sales Trends Over Time (Line Chart)
   
Sales showed a consistent upward trend from 2017 to 2018, but a decline was observed in 2019.

The peak sales period occurred during the dry season (December–March), indicating higher demand during this time.

A notable drop in sales in mid-2019 suggests possible external factors such as changes in market demand, economic conditions, or supply chain disruptions.

2. Regional Performance (Waterfall Chart)

Senegal recorded the highest profit (N21 million, 20.35%), followed closely by Nigeria (20.25%), Ghana (19.9%), and Benin (19.85%).

Togo had the lowest profit (19.65%), likely due to Grand Malt being its highest-selling brand, despite being one of the least popular overall.

The top-performing regions in sales were South-South, West, and North-Central, while the least-performing regions were North-East, South-East, and North-West.

Regional variations in sales could indicate differences in consumer preferences, brand awareness, and economic conditions.

3. Profitability Breakdown (Waterfall Chart/KPI Dashboard)
   
Beer brands dominated profitability, with Castle Lite, Budweiser, and Eagle Lager contributing the highest revenue.

The least profitable brands were Trophy, Hero, and Grand Malt, which also had lower sales volumes.

The 2017 financial year had the highest profit margin (36.47%), but profitability declined in 2018 (35.10%) and dropped further in 2019 (28.43%).

A detailed breakdown showed that high sales volume did not always equate to high profitability, as seen in Hero and Grand Malt in 2019.

4. Actionable Dashboards in Power BI
   
A sales performance dashboard provided an overview of revenue trends, best-selling brands, and underperforming products.

A regional analysis dashboard helped in identifying areas for market expansion or strategic focus based on sales and profitability data.

A profitability dashboard showcased profit margins per product and region, assisting in strategic decision-making for pricing and marketing efforts.

Seasonal trend analysis dashboards helped forecast demand fluctuations, enabling better inventory and sales planning.


📌 Conclusion

The analysis of International Breweries' sales trends and profitability revealed key insights into revenue patterns, regional performance, and brand profitability. The highest profit was recorded in 2017, but a declining trend in subsequent years highlights the need for strategic interventions. While Castle Lite, Budweiser, and Eagle Lager emerged as the most profitable brands, Trophy, Hero, and Grand Malt underperformed despite some recording high sales volumes.

Seasonal trends indicate that sales peak during the dry season (December–March), providing an opportunity for targeted marketing and inventory optimization. Regional performance varied significantly, with Senegal leading in profitability and Togo generating the lowest profit, suggesting potential market-specific strategies.

These insights can help International Breweries optimize product pricing, enhance distribution strategies, and implement data-driven marketing efforts to maximize profitability and market share. Understanding consumer demand across different regions and seasons will allow the company to make informed business decisions and drive sustainable growth.


📌 Recommendations

To maximize profits, International Breweries should focus on promoting high-performing brands like Castle Lite, Budweiser, and Eagle Lager while leveraging seasonal demand by increasing marketing efforts and distribution during peak sales months (December–March). Additionally, strengthening market presence in top-performing regions such as Senegal and Nigeria can further boost revenue.

To reduce losses, the company should evaluate the underperformance of brands like Trophy, Hero, and Grand Malt, identifying factors affecting their sales and profitability. Adjusting pricing strategies, refining marketing efforts, or reconsidering distribution channels may help improve their performance.

For strategic decision-making, implementing data-driven forecasting models can help optimize inventory management, prevent stock shortages during peak seasons, and reduce overstocking in low-demand periods. Expanding market research efforts to understand regional preferences can also aid in tailoring product offerings to different consumer demographics, ensuring long-term sustainable growth.





 

# Sales-Trends-Profitability-Insights-International-Breweries-Analysis
Analyzing sales trends in the International Breweries dataset to drive data-driven decision-making, maximize profits, and minimize losses.

### Files Included
* IBCode.txt  → SQL script for analyzing the dataset
* IBProjectCode.txt  → Additional SQL queries for in-depth analysis
* International_breweries.pbix → Power BI dashboard visualizing sales trends and profitability
* Internationalbreweries Power-BI Storytelling Presentation.pptx → PowerPoint presentation explaining key insights from the dashboard
* International Breweries Report.docx → Comprehensive written report summarizing findings and recommendations
* Interactive Power BI Report → Click the link below to view the interactive Power BI dashboard

  https://app.powerbi.com/reportEmbed?reportId=5abd6940-4195-4c01-bea5-18c9d38016a8&autoAuth=true&ctid=bd697c1b-c481-479c-841e-c618542675c3
  
