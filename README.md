# ghana_financial_inclusion_(2017-2024)
Financial inclusion analysis using Excel, SQL, Power BI, Python &amp; data from BoG, GSS, and World Bank
Project Overview

This project analyzes the evolution of financial inclusion in Ghana between 2017 and 2024. The analysis integrates mobile money usage data, money supply and deposit data, and regional demographic indicators to evaluate access, usage patterns, deposit stability, and borrowing growth.

To assess how financial inclusion is progressing in Ghana, dataset  retrieved include :

Global Findex Database (Mobile money) dataset
Captured ownership and usage rates across regions.

Monthly Monetary Survey(Money supply) dataset
Tracked deposit levels, liquidity patterns, and circulation of funds.

Regional and demographic dataset, (Interest dataset)
Linked inclusion indicators to specific regions and demographic groups.
Total population of 39M was derived by summing age brackets from this table to serve as the population base.

Project Objective

The analysis aimed to:

Examine how financial inclusion evolved in Ghana from 2017 to 2024.
Analyze deposit trends and mobile money usage patterns.
Explore the relationship between interest rates, deposit behavior, and mobile money adoption.
Identify financially underserved regions and explain structural gaps.
Develop data driven recommendations to improve banking access and increase deposit mobilization.

Methodology

Population Base Definition
Established a consistent base of 39M individuals using the demographic dataset.

Transaction Segmentation
Classified individuals into digital transaction categories to measure depth of financial engagement.

Deposit Structure Analysis
Measured composition of demand, savings and time, and foreign currency deposits to assess system stability.

Trend Evaluation
Examined deposit trends from 2017 to 2023 and borrowing patterns from selected years between 2017 and 2024.

Regional Assessment
Compared mobile money usage and inclusion indicators across regions to identify underserved areas.

Key Insights
1.Digital access is expanding but concentrated
Mobile money drives inclusion, but usage remains concentrated in single channel behavior.

2.Deposit structure is transactionlly dominated
Demand deposits represent 37.5 percent of total deposits while Foreign currency deposits account for 29.4 percent, indicating exposure to currency risk.

3.Deposits are vulnerable to macroeconomic shocks
Deposits increased from 2017 to 2019, declined in 2020 and 2021, recovered in 2022, and dropped sharply in 2023 amomg all three varibles hence the need for further research.

4.Foreign currency deposits represent nearly one third of total deposits, signaling currency risk concerns.

5.Borrowing is accelerating
Average borrowing increased by 85.8 percent between 2017 and 2024, indicating rising reliance on credit.

6.Some regions show significantly lower digital financial engagement, indicating geographic inequality in access.

Data Limitation

Financial inclusion data spans 2017 to 2024.
Deposit data spans 2017 to 2023.
Average borrowing data is available only for selected years, 2017, 2021, and 2024.

Because deposit data is unavailable for 2024 and borrowing years are discontinuous, full year by year comparison between credit growth and deposit expansion is constrained.
RECOMMENDATION

1. Expand Financial Infrastructure in Underserved Regions
Establish additional banking outlets and mobile money agent networks in regions such as Oti and Savannah to reduce geographic inequality.

2.Promote Digital Financial Literacy
Implement targeted financial education programs for rural communities, youth, and low-income groups to improve responsible usage of digital financial services.

3.Encourage Sustainable Savings Growth
Develop interest-based savings products, micro-savings tools, and incentive-based programs to maintain deposit stability.

4.Strengthen Monitoring of Borrowing Trends
Closely monitor rising borrowing patterns to mitigate potential liquidity stress and reduce long-term default risks.

## Dashboard
![Financial Inclusion Dashboard](DashboardF.png)


## Project Structure

ghana-financial-inclusion-2017-2024/
│
├── data/ 
│   ├── raw/         # Original datasets ( CSVs, Excel file)
│   ├── cleaned/     # Cleaned and transformed datasets ready for analysis
│
├── Mysql           # For creating database and query
├── notebooks/      # Jupyter/Python notebooks for data query
├── Power BI/       # For dashboard and storytelling
│   
└── README.md       # Project Documentation




