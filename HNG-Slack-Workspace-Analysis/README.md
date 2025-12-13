# HNG Slack Workspace Exploratory & Predictive Analysis

## Project Overview
This project presents an exploratory and predictive analysis of engagement patterns within the HNG13 Slack workspace. Using daily activity metrics, engineered behavioral features, and machine learning, the analysis examines how participation evolves over time and identifies the key drivers of engagement across the cohort lifecycle.

## Problem Statement
Large online learning communities often struggle to maintain consistent engagement as programs progress. While member counts may remain high, actual participation can fluctuate significantly. This project seeks to understand what truly drives activity in the HNG Slack workspace and whether engagement levels can be reasonably predicted using historical behavior.

## Dataset & Files (Hosted on Google Drive)

All files for this project-including raw dataset, engineered dataset, notebook, report, and prediction outputs—are located in a shared Google Drive folder:

**[Click here to access project files](https://drive.google.com/drive/folders/1o0bWaIUbEYm-FepQ07vgikWHP7oeLLAt)**

Inside the folder, you'll find:
- **HNG13 Slack Analytics Dataset (Oct 1 – Dec 6, 2025)** (Raw dataset)
- **HNG13_Engineered_Dataset** (Feature-engineered dataset)
- **HNG13_predictions** (Model prediction outputs)
- **Pulse_Analytics_Exploratory & Predictive_Analysis_Jupyter_Notebook.pdf** (Jupyter Notebook)
- **Pulse_Analytics_Exploratory & Predictive_Analysis_Report.pdf** (Detailed PDF report)
- **Visualizations** (Charts and plots used in analysis)

## Interactive Dashboard
An interactive Power BI dashboard was built to complement the analysis and make insights easily accessible:

**Power BI Dashboard:**  
[Click here to view the interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmY5ZDJkYzgtOWU2OC00ZmZjLWE1MjYtY2I0YWFjNDNiNGIwIiwidCI6IjQ1NjUyNTE0LTMwNjItNDFmZS05OTg2LTQ1MzA2YzRiNzBjNCJ9)

## Data Preparation
- Cleaned and structured daily Slack activity data.
- Removed rows with insufficient history for lag and rolling features.
- Verified data consistency across engagement, messaging, and membership metrics.

## Exploratory Analysis
The exploratory analysis focused on understanding how engagement changed over time:
- Daily active participation showed a clear lifecycle pattern, with early growth, mid-cohort peaks, and end-of-program decline.
- Messaging volume closely mirrored engagement intensity, with spikes during deadlines and collaboration sprints.
- File uploads followed a more structured pattern, aligning with formal submissions and reviews.

## Feature Engineering
To support predictive modeling, several features were engineered:
- **Lag features** (1, 2, 3, and 7 days) to capture short-term engagement momentum.
- **Rolling window statistics** (7-day and 14-day averages and standard deviation) to model weekly trends.
- **Ratio features** such as messages per active user and files per active user to measure engagement quality.
- **Temporal features** including day of week, week of year, and month to capture seasonality.

## Predictive Modeling
A **Random Forest Regressor** was trained to predict daily active users:
- Model trained on 80% of the timeline and evaluated on the remaining 20%.
- The model captured overall engagement trends effectively during stable periods.
- Performance declined near the end of the cohort due to sudden behavioral shifts, a common challenge in human-driven systems.

## Key Findings
- Messaging activity (daily people posting messages) is the strongest driver of overall engagement.
- Membership size alone does not guarantee participation; engagement quality matters more than raw counts.
- Engagement follows a predictable decline curve as the cohort nears completion.
- Predictive models can track trends well but struggle with abrupt drops caused by deadlines and end-of-program fatigue.

## Conclusion & Recommendations
The analysis shows that sustained communication is critical to maintaining engagement in large learning communities. Structured messaging, timely interventions, and mid-cohort engagement boosts can help counter natural participation decline. The Power BI dashboard provides a practical, real-time tool for monitoring engagement, evaluating trends, and supporting data-driven decision-making for future cohorts.

## Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Power BI
- Matplotlib

## Author
- **Muoghalu Chinedu Deborah**
- **LinkedIn:** [Muoghalu Chinedu Deborah](https://www.linkedin.com/in/chinedu-muoghalu-321979b9)
- **GitHub:** [DebbyAngel](https://github.com/DebbyAngel)
