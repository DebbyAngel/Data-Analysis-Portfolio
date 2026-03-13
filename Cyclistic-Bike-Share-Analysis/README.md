# Cyclistic Bike-Share Analysis
## Google Data Analytics Capstone

## Project Overview
This project presents a full data analysis of Cyclistic, a fictional bike-share 
company in Chicago, as part of the Google Data Analytics Certificate capstone. 
The goal was to analyze how annual members and casual riders use Cyclistic bikes 
differently, and to deliver data-backed marketing recommendations to convert 
casual riders into annual members.

## Problem Statement
Cyclistic's finance team concluded that annual members are significantly more 
profitable than casual riders. The marketing director, Lily Moreno, believes 
converting existing casual riders into members is the key to future growth. 
To support this strategy, the following question was assigned:

**How do annual members and casual riders use Cyclistic bikes differently?**

## Dataset & Files (Hosted on Google Drive)
All project files are located in the following Google Drive folder:

[**Click here to access Project Files**](https://drive.google.com/drive/folders/1stujwb7t4dVKViLApib-QuiJN0rBIvrq?usp=sharing)

Inside the folder, you'll find:
- **Cyclistic_Analysis_Report_2023.docx** — Full written analysis report
- **Cyclistic_Analysis_2023.pptx** — Presentation slides
- **Cyclistic_Colab_Notebook.pdf** — Python code, cleaning steps & visualizations
- **Cyclistic_Analysis_Notebook.ipynb** — [Click here to view Python Notebook on Google Colab](https://colab.research.google.com/drive/1baf8G24LK1N5ePZyW2BfA6UXKwjqjI-g?usp=sharing)

## Data Source
- **Provider:** Motivate International Inc. (Divvy Bikes, Chicago)
- **License:** CC0 Public Domain
- **Period:** January – December 2023 (12 monthly CSV files)
- **Raw Records:** 5,719,877 trips
- **Clean Records:** 4,244,411 trips (after removing invalid rides)

## Data Cleaning
- Combined 12 monthly CSV files into a single DataFrame using Python (pandas)
- Converted timestamps and calculated ride_length in minutes
- Removed rides under 1 minute (false starts) and over 24 hours (lost/stolen)
- Removed rows with missing station names
- Result: 1,475,466 records removed, 4,244,411 clean records retained

## Key Findings
1. **Ride Duration:** Casual riders average 23.21 min vs members at 12.38 min — casuals ride 87.5% longer
2. **Day of Week:** Members peak Tuesday–Thursday (commuters); casuals peak Saturday–Sunday (leisure)
3. **Seasonality:** Both groups peak in summer; casual ridership drops 8x from July to January
4. **Time of Day:** Members show 8AM & 5PM commuter peaks; casuals build gradually through the afternoon
5. **Bike Type:** Only casual riders use docked bikes (75,492 rides); members use none
6. **Top Stations:** Casual riders concentrate at lakefront/tourist stations; members spread citywide

## Top 3 Recommendations
1. **Summer Weekend Campaign** — Target casual riders May–August at peak stations with limited-time membership discounts
2. **In-App Conversion Prompts** — Trigger membership upgrade prompts for casuals who complete 3+ weekend rides
3. **Electric Bike Members-Only Benefit** — Offer discounted e-bike access as an exclusive membership perk

## Tools & Libraries
- **Python:** pandas, matplotlib
- **Environment:** Google Colab
- **Reporting:** Microsoft Word, Microsoft PowerPoint

## Author
- **Muoghalu Chinedu Deborah**
- **LinkedIn:** [Muoghalu Chinedu Deborah](https://www.linkedin.com/in/chinedu-muoghalu-321979b9)
- **GitHub:** [DebbyAngel](https://github.com/DebbyAngel)
