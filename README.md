# A/B Testing Analysis of Marketing Campaigns

## Project Overview
This project evaluates the performance of two marketing campaigns—Control Campaign and Test Campaign—to determine which performs better based on three key metrics:

- CTR (Click-Through Rate): Measures user engagement with ads.
- Conversion Rate: Assesses how well clicks translate into purchases.
- CPP (Cost Per Purchase): Evaluates cost-effectiveness.

The analysis includes a breakdown of weekday and weekend performance, hypothesis testing to identify statistically significant differences, and actionable recommendations for optimizing the campaigns.
 
## Key Objectives
- Compare the Control Campaign and Test Campaign using performance metrics.
- Identify statistically significant differences in performance between the two campaigns.
- Provide actionable recommendations for improving campaign effectiveness.

##  Data Used
Link - https://www.kaggle.com/datasets/amirmotefaker/ab-testing-dataset
### The dataset includes:

- Campaign details: Control Campaign and Test Campaign.
- Metrics:
    - CTR (%): Calculated as Clicks /Impressions * 100
    - Conversion Rate (%): Calculated as Purchases/ Clicks * 100
    - CPP ($): Calculated as Spend (USD) /Purchases​

- Time features:
    - Day of the week.
    - Weekend indicator (Is_Weekend).

## Analysis Workflow
### Data Cleaning and Preparation:
    - Renamed columns for clarity.
    - Calculated metrics: CTR (%), Conversion Rate (%), CPP ($).
    - Added day-wise and weekend/weekday segmentation.

### Exploratory Data Analysis (EDA):
    - Visualized day-wise trends for CTR, Conversion Rate, and CPP.
    - Compared weekday and weekend performance for each metric.

### Hypothesis Testing:
    - Used two-sample t-tests to identify significant differences between campaigns for:
        - Weekday performance.
        - Weekend performance.
    - Evaluated the null hypothesis: No significant difference between campaigns.
### Recommendations:
    - Provided data-driven insights for scaling, optimizing, and improving campaigns.

## Technologies Used
- Python: For data processing, statistical analysis, and visualization.
    - Libraries: pandas, numpy, matplotlib, seaborn, scipy.
- Jupyter Notebook: Interactive development environment.
- Statistical Tools: Two-sample t-tests to evaluate differences between campaigns.
