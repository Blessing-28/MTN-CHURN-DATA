## MTN-CHURN-DATA

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into The churn analysis of a tel communication company over the past year. A comprehensive view of customer behavior and factors influencing churn across age, tenure, device usage, customer satisfaction, and gender


![Uploading Result.png…]()


### Data Sources

Churn data: The primary dataset used for this analysis is the "MTN Nigeria Customer Churn.csv" file, containing detailed information about churn status of customers.
### Tools

- Excel - Data Cleaning
- Excel - Data Analysis
- Excel - Creating reports


### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the churn data to answer key questions, such as:

- What percentage of customers have churned?
- Which devices have the highest churn?
- Are lower satisfaction rates linked to higher churn?
- Why are customers leaving?
- Are long-term customers more likely to stay?
- Which genders churn more?

### Data Analysis

Include some interesting formula features worked with

```Excel formula
VLOOKUP()
IF()
COUNTIF()
```

### Results/Findings

The analysis results are summarized as follows:
1. Customers aged 40–54 and 65–80 exhibit the highest churn counts.
2. Churn is highest among customers with 36–60 months of tenure.
3. Customers with Poor and Fair ratings churned more than those with Excellent ratings.
However, churn still exists even among those who rated the service as Very Good or Excellent.
4. Customers using multiple devices churn significantly more than those on a single device.
5. Both male and female customers show high churn counts, with female churn slightly higher.
6. The leading cause for churn is High call tariffs (19.01%)
### Recommendations

Based on the analysis, we recommend the following actions:
- Improve pricing and create loyalty bundles for long-term users.
- Target middle-aged and older customers with retention campaigns.
- Address pricing complaints and provide better multi-device offers.
### Limitations

Users with multiple devices appeared more than once in the dataset based on each device they owned. This may have slightly affected the accuracy of the churn and revenue analysis, but the trends still show clear patterns across device types.
