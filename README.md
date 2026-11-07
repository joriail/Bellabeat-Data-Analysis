# Bellabeat Daily Activity Analysis

## Project Overview
This project is a case study completed as part of the **Google Data Analytics Professional Certificate**. It explores Fitbit fitness-tracker data to identify smart-device usage patterns and develop data-informed marketing recommendations for Bellabeat.

## Business Questions
1. What are the trends in smart-device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends influence Bellabeat's marketing strategy?

## Tools
- Python (Pandas, Matplotlib, Seaborn)
- Tableau Public

## Dataset
Fitbit Fitness Tracker Data (Kaggle, public-domain CC0 dataset):
https://www.kaggle.com/datasets/arashnic/fitbit

The dataset contains historical observations from March 12 to April 12, 2016. The daily activity analysis includes 457 records from 35 unique users. These data are not Bellabeat customer data, so findings should be treated as exploratory rather than representative of Bellabeat's customer base.

## Key Findings
- Average daily steps: **6,546.56**.
- Average daily distance: **4.66 km**.
- Average device-reported daily calories: **2,189.45**.
- Average sedentary time: **995.28 minutes per day**.
- Average lightly active time: **170.07 minutes per day**.
- Average steps peaked at **7 PM** and were lowest at **3 AM**.
- Wednesday had the highest average daily steps; Tuesday had the lowest.
- The observed sleep-steps relationship was weakly negative and should not be interpreted as causal.

## Recommendations
- Test gentle movement reminders during extended sedentary periods.
- Test optional activity prompts or progress updates in the early evening.
- Pilot a Tuesday activity challenge to encourage engagement on a comparatively less active day.
- Offer personalized activity and sleep insights, while avoiding claims of causation.
- Validate these ideas with Bellabeat customers before scaling marketing campaigns.

## Limitations
- The dataset is historical (2016) and does not contain Bellabeat customer data.
- The sample is small and uneven across users and metrics.
- Zero-step records may reflect non-wear or incomplete tracking; their meaning is uncertain.
- Sleep records cover fewer users than daily activity records.
- Repeated observations from the same users and the observational design limit inference. Correlation does not establish causation.

## Tableau Dashboard
[View the interactive Bellabeat dashboard on Tableau Public](https://public.tableau.com/app/profile/juri.alsadun/viz/BellabeatDailyActivityAnalysis/Dashboard1)

## Repository Contents
- `Python_Analysis/`: original Python analysis script (uploaded without code edits).
- `Tableau_Dashboard_Link.txt`: link to the published Tableau dashboard.
- `Bellabeat_Case_Study_Report.docx`: written case-study report (to be added as a binary document file).
