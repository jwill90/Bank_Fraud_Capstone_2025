
# A Data Analysis of Consumer Fraud & Identity Theft

**Motivation**
My motivation for this financial crimes analysis project stems from combining my criminal justice interests with the analytical foundation from my healthcare career and current data analytics bootcamp, preparing me to contribute effectively to a goal of working on a bank fraud investigation teams and/or security operations environment.

**Data**
FinCEN: https://www.fincen.gov
FinCEN SAR Data Analysis: Consumer Fraud & Identity Theft. This repository contains the analysis of Suspicious Activity Reports SARs data sourced from the Financial Crimes Enforcement Network. The goal is to uncover patterns, trends, and correlations related to consumer fraud and identity theft within the U.S. financial system. 

The project utilized FinCEN datasets of known SAR to gain insight into the payment methods and instruments utilized when suspicious activity is reported. Federal Data: Available for the period 2014–2024. State Data: Available for the period 2020–2025.The datasets contain crucial information associated with various industry types (e.g., depository institutions, money services businesses, securities/futures). This project will be focusing on industry Type: Depository Institutions 

**Project Objectives**: This analysis is structured around two primary objectives: 

Objective 1: Data Preparation Perform Exploratory Data Analysis EDA, data cleaning, and standardization/normalization of the SAR datasets to ensure accuracy and consistency for analysis. 

Objective 2: Data Visualization & Insights Explore the cleaned data and generate visualizations to report findings and answer key investigative questions: 

**Initial Questions:**  
1. Temporal Trends: How has the total number of SAR changed over time (monthly, quarterly, or yearly) for each institution type? Identify any seasonal trends or sudden spikes in reporting.
2. Payment Method Growth: Which payment methods show the highest growth rate in suspicious activity?
3. Geographic Hotspots (Federal): What are the top 5 states with the highest number of?
4. Geographic Hotspots (Local): What are the top 5 counties with the highest number of SARs?
5. Activity Classification: What are the most common types of suspicious activity reported (e.g., Money Laundering, Structuring, Identity Theft)?
6. Anomalies: Identify any anomalous reporting periods, and determine the activity types most impacted during those times.
7. Pandemic Impact: How did the COVID-19 pandemic (2020–2022) affect different types of financial crimes reported via SARs?

**Analysis**

**How has the total number of SAR changed over time (monthly, quarterly, or yearly) for each institution type? Identify any seasonal trends or sudden spikes in reporting**
The state with the highest number of SAR filings is California with 2,291,535 SARs. Following California are Ohio (1,445,487 SARs), New York (1,423,928 SARs), North Carolina (1,252,861 SARs), and Texas (1,196,373 SARs). 

**Payment Method Growth: Which payment methods show the highest growth rate in suspicious activity?**
The top payment method/instrument utilized during 2014-2024 was U.S. Currency 

**Activity Classification: What are the most common types of suspicious activity reported (e.g., Money Laundering, Structuring, Identity Theft)?**
Fraud was the most common type of suspicious activity reported coming in at 1.22M SARs filings, followed by Other Suspicious Activity coming in at 0.48M, Money Laundering 62K, Structuring at 44K, and lastly Mortgage Fraud coming at 36K

**Anomalies: Identify any anomalous reporting periods, and determine the activity types most impacted during those times**
The three anomalous months were March (1,235,838 SARs), August (1,266,992 SARs), and October (1,239,840 SARs). 

**Pandemic Impact: How did the COVID-19 pandemic (2020–2022) affect different types of financial crimes reported via SARs?**
Fraud was the top suspicious activity type which consisted of 71% of the SARs filings, followed by ACH coming in at 20% 

**Limitations**
State data (2020-2025) 
Reason behind the missing data:  
- Anti-Money Laundering Act of 2020
- Effective Jan 1, 2021
- Requires crypto businesses to report geographic location
- Enables FinCEN to collect  geographic data on suspicious crypto activity
Unable to obtain a list of financial institutions reporting the SAR filings

**Conclusion**
Top States:  California, Ohio, and New York have the highest total number of SAR filings

Top Counties: Sussex, DE has a significantly high number of SAR filings, topping the county list, followed by San Francisco, CA and New Castle, DE
Over 60% of large U.S. corporations and holding companies are headquartered in Delaware

Anomalous Periods: March, August, and October which consistently showed a higher volume of SAR filings than the annual average
May be related to quarterly and fiscal reporting practices 

U.S. Currency is the top payment instrument utilized in suspicious activity report filings


[Capstone Project Link ](https://app.powerbi.com/view?r=eyJrIjoiOGU3MTMxZmItNGQ0My00NzFjLWIzYTQtMDc3MDZmY2NkN2UwIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9)    





