OVERVIEW

In this application, you will explore a dataset from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. Your goal is to understand what factors make a car more or less expensive. As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

CRISP-DM Framework

To frame the task, throughout our practical applications, we will refer back to a standard process in industry for data projects called CRISP-DM. This process provides a framework for working through a data problem. Your first step in this application will be to read through a brief overview of CRISP-DM here. After reading the overview, answer the questions below.

Business Understanding

I would like to determine what factors make a car more or less expensive. I would like to understand pricing drivers in the used car market. I will be identifying statistical significant factors that influence vehicle prices.

Data Understanding

I loaded vehicles.csv dataset and explored dataset structure. I identified data types (numerical: year, odometer, price. categorical: manufacturer, condition, etc.) I have both numerical and categorical variables that could influence price.

Data Preparation

I implemenented data cleaning which filtered out unrealistic prices anything < $500 or > $100,000. I removed extreme values that could skew analysis. I used .dropna() for correlation calculations and focus on relevant colums for price analysis. I used minimum sample sizes of 100+ listings for meaningful analysis.

Modeling

The visualization models are scatter plots, box plots to reveal patterns. I did a comparative analysis of the price distribution across different categories. I did descriptive staticstics by analysis for categorical variables.

Evaluation

In my evaluation, I asked myself the question, does the findings make practical sense? Can any stakeholder use this information to make a decision?

Deployment

See below for report.

Factors that INCREASE car prices:

Newer model year - Strong positive correlation with price
Lower mileage - Cars with fewer miles command higher prices
Better condition - New/Like New vehicles are significantly more expensive
Luxury manufacturers - Premium brands (Mercedes, BMW, Audi) vs economy brands
Vehicle type - Sports cars, luxury SUVs, and trucks often more expensive
Larger engines - More cylinders typically correlate with higher prices
Advanced fuel systems - Hybrid and diesel vehicles often carry premiums

Factors that DECREASE car prices:

High mileage - Strong negative correlation
Older age - Depreciation over time
Poor condition - Salvage, fair condition significantly reduce value
Economy manufacturers - Budget brands vs luxury brands
Smaller engines - Fewer cylinders, smaller displacement
Basic features - Manual transmission, basic trim levels

