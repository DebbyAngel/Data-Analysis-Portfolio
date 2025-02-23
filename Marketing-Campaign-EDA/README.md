# Marketing Campaign EDA

## Project Overview
This project involves performing exploratory data analysis (EDA) on a marketing campaign dataset. The dataset includes metrics such as campaign types, ROI, clicks, impressions, CTR, CPC, conversion rates, and more. The goal is to uncover insights that can help optimize marketing strategies.

## Problem Statement
Marketing teams often struggle to identify which channels, locations, and customer segments yield the highest return on investment (ROI) and engagement. By analyzing the data, we aim to:
- Understand campaign performance by type and channel.
- Identify high-performing locations.
- Pinpoint customer segments with higher conversion rates.

## Dataset
- **Raw File Name:** `marketing_campaign_dataset_csv` (Original dataset with “days” in Duration, `$` in Acquisition_Cost, etc.)
- **File Name:** `marketing_campaign_dataset_cleaned.csv`
- **Description:** Contains campaign information (Campaign_Type, Target_Audience, Duration, Channel_Used, Conversion_Rate, Acquisition_Cost, ROI, Clicks, Impressions, etc.).  
- **Data Cleaning (Python):**  
  - Removed “days” from `Duration`.  
  - Stripped `$`/`,` from `Acquisition_Cost` and converted it to float.  
  - Standardized `Date` column to a consistent format.  
  - Created `CTR` = (Clicks / Impressions) * 100 and `CPC` = Acquisition_Cost / Clicks.  
  - Verified no missing values remained.

## EDA Steps
1. **Data Loading & Inspection**  
   - Reviewed dataset structure (`df.info()`) and descriptive stats (`df.describe()`).
2. **Feature Engineering**  
   - Added `CTR` and `CPC` to measure engagement and cost-efficiency.
3. **Visualizations & Insights**  
   - ROI distribution (boxplot).  
   - CTR by channel (barplot).  
   - Conversion rate by customer segment (barplot).  
   - ROI across locations (line plot).

## Key Findings
- **High CTR** on certain channels (e.g., Search Engine).  
- **Social Media** campaigns often yield the highest ROI.  
- Certain **customer segments** show higher conversion rates.  
- Locations like `Location_10` and `Location_6` exhibit above-average ROI.

## Conclusion & Recommendations
- **Invest more** in high-ROI channels (Social Media) and high-CTR channels (Search Engine).  
- **Focus** on customer segments with higher conversion rates.  
- **Tailor** campaigns to high-performing locations for greater impact.  
- **Continuously monitor** CTR, CPC, and ROI to adapt to market changes.

## Files in This Folder
- 'marketing_campaign_dataset_csv' (Raw Dataset)
- `Marketing_campaign_dataset_cleaned.csv` (Cleaned dataset)
- `Marketing_Campaign_EDA_DebbyRise.pdf` (Detailed PDF report)
- `Exploratory Data Analysis of Marketing Campaigns.pptx` (Presentation slides)
  
## Tools & Libraries
- **Python**: Pandas, Matplotlib, Seaborn
- **Jupyter Notebook** (or similar IDE)

## Author
- **Muoghalu Chinedu Deborah**  
- **LinkedIn:** [Muoghalu Chinedu Deborah](https://www.linkedin.com/in/chinedu-muoghalu-321979b9)  
- **GitHub:** [DebbyAngel](https://github.com/DebbyAngel)
