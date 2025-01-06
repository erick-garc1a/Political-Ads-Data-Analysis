# Snap Chat Political-Ads-Data-Analysis

## Project Overview
This project focuses on analyzing Snapchat advertisement data to answer key questions about ad performance, demographic targeting, and ROI (Return on Investment). Using Python's pandas and matplotlib libraries, we explore how factors like age, gender, region, and spending impact ad impressions and engagement.

## Questions Answered
Do Snapchat advertisements with specific criteria such as age or gender receive more engagement compared to non-targeted ads?

Approach: Ads were categorized into targeted and non-targeted groups based on AgeBracket, Gender, and Regions (Included). Engagement was measured through impressions, and bar plots compared the results.
Which regions and age brackets have the highest impressions-to-spend ratio?

Approach: Calculated the Impressions-to-Spend ratio for all regions and age brackets, highlighting the top 10 performers.
## Key Steps
Data Preparation:

Filled missing values with placeholders (NaN handling).
Created new calculated columns like Impressions_to_Spend and Duration (ad runtime in days).
Data Analysis:

Grouped data by demographics (age, gender, region) and computed metrics like mean impressions and impressions-to-spend ratio.
Filtered top-performing regions and age brackets for ROI-focused insights.
Visualization:

Used bar charts to represent:
Targeted vs. non-targeted performance for age, gender, and region.
Top 10 regions and age brackets by impressions-to-spend ratio.
## Results
Targeted Ads:
Ads targeting specific demographics (age, gender, or region) showed notable differences in engagement compared to non-targeted ads.
High ROI Regions & Age Brackets:
Identified specific regions and age brackets yielding the highest ROI, guiding ad placement strategies.
## Files Included
Code:
Python scripts for data cleaning, analysis, and visualization.
Outputs:
Bar plots showcasing key findings.
Dataset:
Processed and raw data files.
## How to Use
Install dependencies: pandas, matplotlib, and statsmodels.
Load the dataset and run the Python script provided.
Review the generated plots and summary outputs for insights.
## Future Improvements
Include additional metrics like click-through rates for deeper engagement analysis.
Experiment with machine learning models for predictive analysis.
Expand the dataset to cover more ad campaigns for robust results.
