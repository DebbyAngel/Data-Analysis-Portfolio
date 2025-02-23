# Marketing SQL Analysis

## Project Overview
This project applies SQL queries to a marketing campaign dataset to extract actionable insights. By leveraging **PostgreSQL**, we can quickly identify top-performing campaigns, cost-effective channels, and optimal target audiences.

## Problem Statement
With multiple campaigns, channels, and segments, it's challenging to pinpoint where to invest resources. Using SQL, we aim to:
- Rank campaigns by impressions, ROI, or conversion rates.
- Identify the most cost-effective campaigns and channels.
- Highlight high-performing locations and target audiences.

## Dataset & Files (Hosted on Google Drive)
All files for this project—raw dataset, cleaned dataset, SQL scripts, and final report—are located in the following Google Drive folder:

[**Click here to access Project 3 files**](https://drive.google.com/drive/folders/1KAtlvYI3-Vvcbs2cI5FXJQDma7Vqr7fj?usp=sharing)

Inside that folder, you'll find:
- **marketing_campaign_dataset_csv** (Raw dataset)  
- **Marketing_campaign_dataset_cleaned.csv** (Cleaned dataset)  
- **Marketing_SQL_Analysis_Report.pdf** (Detailed SQL report)  
- **Marketing_SQL_Tasks.zip** (SQL queries)

## Data Cleaning (Excel)
- Removed “days” from `Duration`.
- Stripped `$`/`,` in `Acquisition_Cost` and converted it to a numeric format.
- Standardized the `Date` column for consistent date handling.
- Confirmed no missing values remained after cleaning.

## SQL Tasks & Queries
1. **Total Impressions** per campaign  
2. **Highest ROI** campaign  
3. **Top 3 Locations** by impressions  
4. **Average Engagement Score** by target audience  
5. **Overall CTR** (Click-Through Rate) across campaigns  
6. **Most Cost-Effective Campaign** (lowest cost per conversion)  
7. **Campaigns Exceeding** 5% CTR threshold  
8. **Ranking Channels** by total conversions

## Key Findings
- **Variability** in campaign reach and impressions  
- **Top-Performing Campaign** identified by highest ROI  
- Certain **locations** excel in impressions, indicating strong regional performance  
- **Cost-Effective** strategies uncovered via cost-per-conversion analysis  
- Campaigns above **5% CTR** show high engagement potential

## Conclusion
SQL queries in **PostgreSQL** revealed clear top performers in ROI and CTR, valuable geographic insights, and opportunities to optimize budget allocation. Focusing on cost-effective campaigns and high-CTR channels can significantly improve marketing outcomes.

## Tools Used
- **Excel**: for data cleaning (removing “days,” `$`, standardizing dates)  
- **PostgreSQL**: for running SQL queries

## Author
- **Muoghalu Chinedu Deborah**  
- **LinkedIn:** [Muoghalu Chinedu Deborah](https://www.linkedin.com/in/chinedu-muoghalu-321979b9)  
- **GitHub:** [DebbyAngel](https://github.com/DebbyAngel)
